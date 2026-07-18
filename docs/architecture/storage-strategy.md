# Storage Strategy

## Purpose

Storage should preserve business integrity while remaining implementation independent.

This document defines storage principles rather than database technologies.

---

## Primary Storage

Stores transactional business data.

Source of truth for all domains.

---

## Object Storage

Stores binary content.

Examples

- Files
- Images
- Videos
- Documents

Business entities reference objects rather than embedding them.

---

## Search Index

Optimized for discovery.

May be rebuilt at any time.

Never becomes the source of truth.

---

## Cache

Optimized for performance.

Failure should never affect correctness.

---

## Analytics Storage

Stores derived analytical data.

Built from domain events.

May be regenerated from historical events when required.

---

## Principles

Business data should be normalized.

Read models may be denormalized.

Binary content remains external to transactional storage.

Historical data should remain queryable.

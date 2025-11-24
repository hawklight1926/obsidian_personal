---
title: "Show HN: I wrote a minimal memory allocator in C"
url: "https://github.com/t9nzin/memory"
date: "2025-11-23"
updated: ""
categories: []
authors: ""
description: "Custom Memory Allocator

A custom implementation of malloc, calloc, realloc, and free in C.

Overview

This project implements a memory allocator from scratch using sbrk for small allocations and mmap for large allocations. It includes optimizations like block splitting to reduce fragmentation and coalescing to merge adjacent free blocks. Please note that this allocator is not thread-safe. Concurrent calls to malloc/free/realloc will cause undefined behavior. I've also written a blog post (~20 m..."
image: ""
read: false
ignored: false
pinned: false
---

## 要約
(要約生成に失敗しました)

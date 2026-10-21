# Divi — TypeTasks (Logic Layer)

A type-safe task tracker logic layer built with TypeScript.

## Part 1: Model & Types

This project contains the typed data model and operations (the logic layer) for TypeTasks:
- `Task` model and `TaskStatus` union (`"todo" | "in-progress" | "done"`)
- Fully typed operations: `addTask`, `completeTask`, `filterByStatus`, `advanceTask`, `deleteTask`, `countByStatus`, `seedNextId`
- No UI components yet — clean compiled data model layer.

## Build

Compile TypeScript to JavaScript:
```bash
tsc
```
Emits `model.js`.

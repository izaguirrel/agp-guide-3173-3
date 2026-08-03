# agp-guide-3173-3

Test repository for GUIDE-3173 manual testing - Go ecosystem.

## Purpose

This repo tests that AGP update failures show the **actual Go command** that failed.

To create an update failure, we'll use `go mod tidy` which might fail if there are issues with the module graph.

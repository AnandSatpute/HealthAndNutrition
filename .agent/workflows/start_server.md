---
description: How to start the MkDocs development server
---

From the project root `/Users/anands/Documents/NutritionAndHealth`, run:

// turbo
1. Start the dev server on port 8080:
```
cd /Users/anands/Documents/NutritionAndHealth && .venv/bin/mkdocs serve -f mkdocs/mkdocs.yml --dev-addr=127.0.0.1:8080
```

The site will be available at **http://127.0.0.1:8080/**

> **Note:** Always use `-f mkdocs/mkdocs.yml` — this is the real config file. The `mkdocs.yml` in the project root is a legacy file and will error on startup.

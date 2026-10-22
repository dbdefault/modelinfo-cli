---
"modelinfo-cli": patch
---

Comparison mode now uses `os.path.basename` for model labels so Windows backslash paths show the file name instead of the full path (#56).

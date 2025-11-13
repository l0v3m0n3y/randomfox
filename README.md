# randomfox
api for site randomfox.ca site random image fox
# Example
```nim
import asyncdispatch, randomfox, json, strutils
let data = waitFor random_fox()
echo data
```

# Launch (your script)
```
nim c -d:ssl -r  your_app.nim
```

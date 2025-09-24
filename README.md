# XboxAuroraSkinsMirror

This is just a mirror. All credits go to the original authors.

### update code

```sh
find skins -type f -name "*.xzp" | while read -r f; do
    base=$(basename "$f")
    ln -s "../$f" "all/$base"
done
```

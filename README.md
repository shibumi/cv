If the project doesn't compile do:

```
rm -rf ~/.texlive/texmf-var/luatex-cache
luaotfload-tool -u # maybe: luaotfload-tool -u -f
```

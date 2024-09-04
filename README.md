
[https://github.com/caksoylar/keymap-drawer](keymap-drawer)

키맵 파싱
```
keymap -c keymap_drawer.config.yaml parse -z config/cradio.keymap > keymap-drawer/cradio.yaml
```

SVG 그리기
```
keymap draw keymap-drawer/cradio.yaml > keymap-drawer/cradio.svg
```
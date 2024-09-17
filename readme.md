# jam
60% layout keyboard

## flash
setup workspace

```bash
qmk setup
git clone https://github.com/natoujam/jam ~/qmk_firmware/keyboard
```

compile and flash

```bash
qmk compile -kb jam -km via
qmk flash -kb jam -km via
```

# Building Anywherelan

## Dependencies

* Go (1.20)
* Git
* gcc, gtk3, libappindicator3 for awl-tray on Linux ([see more](https://github.com/anywherelan/systray#platform-notes))
  - only for development, do not need for release build
* gomobile and Android Studio for Android ([see more](https://pkg.go.dev/golang.org/x/mobile/cmd/gomobile))
* Flutter (3.3)

## Build

The first step is to clone [awl](https://github.com/anywherelan/awl) and [awl-flutter](https://github.com/anywherelan/awl-flutter) in one parent directory.

```bash
cd awl
./build.sh release
ls build
```

See [build.sh](build.sh) for more details.

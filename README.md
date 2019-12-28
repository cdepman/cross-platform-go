testing cross platform UI framework [Fyne](https://fyne.io/develop/)
capable of building to OSX/Linux/Windows/iOS/Android

To build packages, install `go get fyne.io/fyne/cmd/fyne`

On OSX:
  Build for OSX:
  `fyne package -os darwin -icon main.png`
  Build for Windows:
  `brew install mingw-w64`
  `CC=x86_64-w64-mingw32-gcc CGO_ENABLED=1 GOOS=windows fyne package -os windows -icon main.png`
# flatpak-check-extra-data

A script to check the validity and availability of extra-data downloads
in a JSON Flatpak manifest.

## Requirements

- lua
- lua-json
- lua-sec
- lua-socket

## Usage

```
./flatpak-check-extra-data /path/to/com.adobe.Flash-Player-Projector.json
```

## Similar projects

- [flatpak-external-data-checker](https://github.com/endlessm/flatpak-external-data-checker)

## License

- main script under the GNU General Public License v2 or later
- sha256.lua and inspect.lua under an MIT license, see headers for details

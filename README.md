# kodo-browser-bin

Arch Linux PKGBUILD for Kodo Browser - A file manager-like application for Qiniu Kodo Object Storage.

## Description

Kodo Browser provides Windows Explorer-like functionality for Qiniu Kodo Object Storage. Users can easily browse files, upload and download files, with support for resumable transfers and more.

## Installation

### Using makepkg

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/kodo-browser-bin.git
   cd kodo-browser-bin
   ```

2. Build and install the package:
   ```bash
   makepkg -si
   ```

### Using AUR Helper (if available)

```bash
yay -S kodo-browser-bin
# or
paru -S kodo-browser-bin
```

## Usage

After installation, you can launch Kodo Browser:

- From the command line: `kodo-browser`
- From your application menu: Search for "Kodo Browser"

## Package Information

- **Package Name**: `kodo-browser-bin`
- **Version**: 2.3.2
- **Architecture**: x86_64
- **License**: Apache-2.0
- **Upstream**: https://github.com/qiniu/kodo-browser

## Dependencies

- `unzip` (build dependency)

## Files

- `PKGBUILD` - Arch Linux package build script
- `.SRCINFO` - Package metadata for AUR
- `kodo-browser.sh` - Binary wrapper script
- `kodo-browser.desktop` - Desktop entry file

## License

This PKGBUILD is provided as-is. The upstream Kodo Browser is licensed under Apache-2.0.

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

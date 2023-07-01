# Poly Dark GRUB Theme for Ventoy

This is my personal theme and setup for [Ventoy](https://github.com/ventoy/Ventoy).

It's based on [Poly Dark](https://github.com/shvchk/poly-dark) by shvchk, but modified for my preferences.

Pull requests are welcome, but this is for my personal use, so they may or may not be merged according to my preferences.

## Installation

Copy the contents of this git repo to the `/ventoy` folder in the first partition of the device Ventoy is installed on.

The current configuration requires that all isos are located in `/iso`, but that can be changed by removing or modifying this line in `ventoy.json`

```json
{
	"//": "ONLY search the /iso directory for files",
	"VTOY_DEFAULT_SEARCH_ROOT": "/iso"
}
```

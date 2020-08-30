<h1 align="center">
	<img src="https://upload.wikimedia.org/wikipedia/commons/e/e1/Thunderbird_Logo%2C_2018.svg" alt="Firefox" height=200 width=200 align="middle">
	Thunderbird AppImage
</h1>

Mozilla Thunderbird Stable, Beta and Nightly (unofficial) AppImages by GitHub Actions Continuous Integration

## Get Started

Download the latest release from

| Stable | Beta | Nightly |
| ------- | --------- | --------| 
| <img src="https://upload.wikimedia.org/wikipedia/commons/e/e1/Thunderbird_Logo%2C_2018.svg" height=100> | <img src="https://www.thunderbird.net/media/img/thunderbird/logos/beta-high-res.png" height=100>  | <img src="https://user-images.githubusercontent.com/48695438/91668637-d4c96e00-eb16-11ea-8661-c320504fdc17.png" height=100> |
| [Download](https://github.com/srevinsaju/thunderbird-appImage/releases/tag/stable) | [Download](https://github.com/srevinsaju/thunderbird-appimage/releases/tag/beta) | [Download](https://github.com/srevinsaju/thunderbird-appimage/releases/tag/nightly) | 


### Executing
#### File Manager
Just double click the `*.AppImage` file and you are done!

> In normal cases, the above method should work, but in some rare cases
the `+x` permissisions. So, right click > Properties > Allow Execution

#### Terminal 
```bash
./thunderbird-*.AppImage
```
```bash
chmod +x Firefox-*.AppImage
./thunderbird-*.AppImage
```

In case, if FUSE support libraries are not installed on the host system, it is 
still possible to run the AppImage

```bash
./thunderbird-*.AppImage --appimage-extract
cd squashfs-root
./AppRun
```

### Related AppImages 
* [Firefox AppImage](https://github.com/srevinsaju/Firefox-AppImage)


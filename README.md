# XRF
XRF is a small utility written for the Xbox One System OS. It's written to allow the retrieval of console information, experimentation and to take advantage of Win32 functionality.

### Prerequisites
- Visual Studio 2015/2017
- Windows 10 SDK (Preferably latest)
- Xbox One Devkit

### Deployment
After compiling, you can utilize a post-build event to transfer the executable via Network Share. Executable is required to be on the console before execution, obviously.

### Usage
Printing basic console information
```
XRF cinfo
```
Printing current user of process
```
XRF whoami
```
Display contents of flash
```
XRF dispflash
```
Reading a specified filename from flash (Requires Administrator)
```
XRF readflash [filename] [destination]
```
Dumping flash raw (Requires Administrator)
```
XRF dumpflash [dumpname]
```

### Credit:
- emoose
- tuxuser
- gligli

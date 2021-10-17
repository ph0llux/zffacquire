# zffacquire

```zffacquire``` is a command line utility for acquiring images into the forensic format Zff.

# Installation

First, you need to [install rust and cargo](https://rustup.rs/) to build or install ```zffacquire```.
Then you can easily build this tool yourself by using cargo:
```bash
[/home/ph0llux/projects/zffacquire] $ cargo build --release
```
Or you can install the tool directly from crates.io:
```bash
$ cargo install zffacquire
```

# Usage

To create an image with the default parameters, the following command is just enough:
```bash
zffacquire -i /dev/sda -o /media/usb-hdd/your_zff_image
```

The complete feature set of ```zffacquire``` can be shown using ```zffacquire -h```.
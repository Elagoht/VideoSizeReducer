# Video Size Reducer

![Nemo Action](https://shields.io/badge/Nemo-Action-87CF3E?logo=linuxmint&logoColor=white&style=for-the-badge)
![Video Gap Remove](https://shields.io/badge/Remove_Video_Gap-000000?logo=airplayvideo&logoColor=white&style=for-the-badge)

This python script compress the input video by changing video codec. After install, on nemo file manager and nemo desktop, you can simply use it right click to a video and select *Reduce Size*.

Alternatively you can use it via terminal. just give file path as parameter.

Example usage:

> videosizereducer $HOME/Videos/input.mp4

## Dependencies

ffmpeg must be installed on your system.

You can install it on 

* Debian based:

    ```bash
    sudo apt install ffmpeg
    ```

* Fedora:

    ```bash
    sudo dnf install https://download1.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm https://download1.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-$(rpm -E %fedora).noarch.rpm
    sudo dnf install ffmpeg ffmpeg-devel
    ```
* Arch Based:

    ```bash
    sudo pacman -S ffmpeg
    ```

## Installation

1. Download package and extract it.
2. Open directory in terminal.
3. Type:

    ```bash 
    sudo ./install.sh
    ```

You're done.

## Usage via Nemo

Watch video on Youtube.

[![video](https://img.youtube.com/vi/7SX63QEYEyk/maxresdefault.jpg)](https://www.youtube.com/watch?v=7SX63QEYEyk)

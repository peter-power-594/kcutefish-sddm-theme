# SDDM Theme for CutefishOS

![screenshot](screenshot.png)

## Ubuntu dependencies

```shell
sudo apt install build-essential cmake extra-cmake-modules qtbase5-dev qtdeclarative5-dev qtquickcontrols2-5-dev qttools5-dev qttools5-dev-tools
```
## Build

```shell
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
```

## Install

```shell
sudo make Install
```

## Uninstall

```shell
rm /usr/share/sddm/themes/cutefish/Main.qml
rm /usr/share/sddm/themes/cutefish/SessionMenu.qml
rm /usr/share/sddm/themes/cutefish/UserView.qml
rm /usr/share/sddm/themes/cutefish/FishUIMenu.qml
rm /usr/share/sddm/themes/cutefish/FishUIMenuItem.qml
rm /usr/share/sddm/themes/cutefish/system-shutdown-symbolic.svg
rm /usr/share/sddm/themes/cutefish/theme.conf
rm /etc/sddm.conf.d/hidpi.conf
rm /etc/sddm.conf
```

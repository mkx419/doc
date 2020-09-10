# How to build xfce4-docklike-plugin
## 1. Install Build Depends
```Bash
sudo apt install build-essential git libglib2.0-dev libgtk-3-dev libwnck-3-dev libxfce4panel-2.0-dev libxfce4ui-2-dev xorg-dev xfce4-dev-tools
```

## 2. Clone
```Bash
git clone https://github.com/nsz32/docklike-plugin.git
```

## 3. Build
```Bash
./autogen.sh
make
```

## 4. Install
```Bash
sudo make install
```

# OnePlus 15T canoe OrangeFox device tree

## Working

## Not working


# How To Build

### Clone & Sync Source
```
mkdir -p ~/android/OrangeFox_14
cd ~/android/OrangeFox_14
git clone https://gitlab.com/OrangeFox/sync.git
cd sync
./orangefox_sync.sh --branch 14.1 --path ~/android/fox_14.1
```
### Clone Device-tree

### BUILD!
```
cd ~/android/fox_14.1
source build/envsetup.sh
lunch twrp_infiniti-ap2a-eng
mka adbd recoveryimage
```

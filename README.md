# PokeClient

![GitHub repo size](https://img.shields.io/github/repo-size/demonicat/pokeclient)
[![GitHub](https://img.shields.io/github/license/demonicat/pokeclient)](https://github.com/demonicat/pokeclient/blob/main/LICENSE)

Based on [mehah/otclient](https://github.com/mehah/otclient/tree/d10976788162d69f6731ce263bce891487725293)

## Compiling on Arch Linux
```sh
sudo pacman -Syu base-devel git cmake boost physfs openssl lua51 glew libvorbis openal zlib libogg nlohmann-json protobuf --needed

git clone git@github.com:demonicat/pokeclient.git

cd pokeclient/src/framework/protobuf/proto/

./generate.sh

cd ../../../../

cmake . -B build

make -C build -j$(nproc)
```



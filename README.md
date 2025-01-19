# C_Cpp_3dpinball

- https://github.com/k4zmu2a/SpaceCadetPinball

- dat file
  - https://github.com/k4zmu2a/SpaceCadetPinball/issues/36

```bash
# sudo apt install freepats libsdl2-dev libsdl2-mixer-dev timidity
git clone --depth 1 https://github.com/k4zmu2a/SpaceCadetPinball
cd SpaceCadetPinball
cmake . && cmake --build .
git clone --depth 1 https://github.com/FmasterofU/WinXP-Pinball
mv WinXP-Pinball/Pinball/* bin
rm -rf WinXP-Pinball
./bin/SpaceCadetPinball
```

# Build(LinuxOS(Ubuntu24.04))

```bash
# On Debian and Ubuntu
sudo apt install cmake build-essential ninja-build libsdl2-dev libsdl2-mixer-dev libsdl2-mixer-2.0-0 libsdl2-2.0-0 fluidsynth

# On Fedora
sudo dnf install cmake ninja-build SDL2 SDL2-devel SDL2_mixer SDL2_mixer-devel fluidsynth fluidsynth-libs mscore-fonts g++

# Build
https://github.com/YoungHaKim7/C_Cpp_3dpinball
cd C_Cpp_3dpinball
mkdir -p build && cd build
cmake -GNinja ..
ninja
```

# windows.h 같은거
- https://github.com/Leandros/WindowsHModular

<hr />

# cmake훈련하기 좋은 코드
- https://github.com/RaldS7/btrfs-windows
- 여기 보다가 찾음
  - https://news.ycombinator.com/item?id=34781163

# 일반인 3D pinball 잘함
- https://youtu.be/_5PNfUFFQlk?si=obK1uuCStu7CriiD
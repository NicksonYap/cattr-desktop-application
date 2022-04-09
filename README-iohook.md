
```sh
cd node_modules
git clone https://github.com/wilix-team/iohook.git
cd iohook
npm install
node build.js --runtime electron --version 13.0.1 --abi 89 --upload=false --msvs_version=2019
cp -Force build/Release/* builds/electron-v89-win32-x64/build/Release
```
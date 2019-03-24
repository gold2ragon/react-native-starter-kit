### Issues
<a href="https://stackoverflow.com/questions/50836558/react-native-config-h-not-found">#1. Config.h not found</a>

1. Close Xcode.
2. cd <Project-Folder>/node_modules/react-native/third-party/glog-0.3.4
3. Run ./configure
4. Run make
5. Run make install
6. Open Xcode and try building the Project.


<a href="https://github.com/facebook/react-native/issues/21310">#2. Module @babel/runtime/helpers/interopRequireDefault does not exist in the Haste module map</a>
```console
npm i @babel/runtime
```
```json
"dependencies": {
  "@babel/runtime": "^7.4.2",
},
```
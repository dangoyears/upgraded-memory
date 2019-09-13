# UpgradedMemory

## 调试工具

- Chrome 调试：在开发者菜单中选择 "Debug JS Remotely" 选项，会自动打开[调试页面](http://localhost:8081/debugger-ui)。据文档说该工具只能提供 console 和在 sources 项中断点调试的功能而已。

- react-devtools：`npm run react-devtools` 启动，可用于查看 elements。或直接在开发者菜单中打开 "toggle Inspector" 选项查看。

- react-native-debugger：Chrome 调试无法查看网络请求，可以使用 [react-native-debugger](https://github.com/jhen0409/react-native-debugger) 进行观测，之后有需要再安装即可，或直接使用 Charles 抓包。

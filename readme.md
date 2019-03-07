## 项目简介
Shape of Future的依赖包。包括了CTP的C++原生库，以及CTP C（自己编译得到）。

## 项目结构

`native-deps.zip`: 按照linux-x64/win-x64/win-x86目录结构组织的CTP C++原生库与CTP C封装库（和体系结构与平台相关）。

## 使用
* `native-deps.zip`由paket管理即可下载与解压，使用构建工具将解压的目录结构拷贝至执行目录。运行时由CTP C#封装根据运行环境从正确的目录加载库。
* 本包应该单独上传至一个公开的repo，以便由paket下载。


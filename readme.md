## 项目简介
Shape of Future的依赖包。

## 项目结构

`ctp-native-deps.zip`: 按照格式组织的CTP原生库（和体系结构与平台相关）。
`c-native-deps.zip`: 按照格式组织的CTP C封装（和体系结构与平台相关）。
`ctp-csharp.1.0.0.nupkg`: CTP C#封装（nuget包，与体系结构平台无关）。

## 使用
* `ctp-csharp.1.0.0.nupkg`由paket管理即可。
* `c-native-deps.zip`由paket下载解压后，由构建工具将目录结构拷贝只运行目录。
* `ctp-native-deps.zip`由paket下载，然后由构建工具根据构建目标的不同选择不同目录下的内容并拷贝至运行目录（只拷贝文件，不带目录结构）。
* 本包应该单独上传至一个公开的repo，以便由paket下载。


# Astral 3D Editor

🌍
*[English](README.md)*
🌍
*[简体中文](README.zh-cn.md)*

### Based on vue3 and ThreeJs, see [Doc](http://editor-doc.astraljs.com/) for details

<div style="text-align: center">

![Static Badge](https://img.shields.io/badge/Vue-3.3.4-green)
![Static Badge](https://img.shields.io/badge/NaiveUI-2.34.4-green)
![Static Badge](https://img.shields.io/badge/ThreeJS-r170-8732D7)
![Static Badge](https://img.shields.io/badge/Cesium-1.107.0-8732D7)
![Static Badge](https://img.shields.io/badge/UnoCSS-0.46.5-8732D7)
<br />
![Static Badge](https://img.shields.io/badge/license-MIT-blue)

</div>

***

## WeChat Group
<img src="https://upyun.astraljs.com/static/images/WeChatGroup.jpg" width="500px">

Click [here](https://upyun.astraljs.com/static/images/WeChatGroup.jpg) view the latest group invitation pictures。

***

## Peculiarity：
- [x] Model import display, support OBJ, FBX, GLTF, GLB, RVT, IFC, SEA, 3DM, 3DS, 3MF, AMF, DAE, DRC, PLY, SVG, JSON and other 30+ formats;
- [x] BIM model (RVT, IFC) lightweight display;
- [x] Analysis of CAD drawings (DWG, DXF);
- [x] Scene subcontract store read;
- [x] WebSocket collaboration;
- [x] Upyun USS store;
- [x] Golang + MySQL backend support;
- [x] Run script;
- [x] Plug-in system;
- [ ] Animation editor;
- [ ] Physical engine support;
- [ ] Particle system support;
- [ ] WebGPU support;
- [ ] Data components (tentatively support: API interface, WebSocket, not support: front-end SQL, GraphQL);
- [ ] VUE / React components support;
- [ ] Low code data large screen;

[//]: # (## 工程结构)
[//]: # (```)
[//]: # (|-- .vscode                          // vscode配置文件)
[//]: # (|-- build                            // 打包配置)
[//]: # (|-- public )
[//]: # (|   |-- library                      // 静态资源库)
[//]: # (|   |-- release                      // 发布包模板         )
[//]: # (|   |-- static                       // 项目静态资源)
[//]: # (|   |-- logo.svg                     // Logo               )
[//]: # (|-- src                              // 源码目录               )
[//]: # (|   |-- cesium                       // cesium 场景相关)
[//]: # (|   |-- components                   // 组件)
[//]: # (|   |-- config                       // 项目各类配置)
[//]: # (|   |-- core                         // 编辑器核心代码)
[//]: # (|       |-- commands                 // 编辑器操作命令集合)
[//]: # (|       |-- exporters                // 自定义模型导出器)
[//]: # (|       |-- libs                     // 第三方相关js库)
[//]: # (|   |-- hooks                        // 钩子函数)
[//]: # (|   |-- http                         // 封装请求)
[//]: # (|   |-- language                     // i18n 国际化配置文件夹)
[//]: # (|   |-- router                       // 路由配置)
[//]: # (|   |-- store                        // Pinia 状态管理)
[//]: # (|   |-- utils                        // 全局公用函数目录    )
[//]: # (|   |-- views                        // vue页面            )
[//]: # (|   |-- App.vue                      // App入口文件)
[//]: # (|   |-- main.ts                      // 程序入口文件 )
[//]: # (|-- types                            // 全局类型定义目录 )
[//]: # (|-- .env                             // 通用环境文件)
[//]: # (|-- .env.development                 // 开发环境)
[//]: # (|-- .env.production                  // 生产环境)
[//]: # (|-- .gitignore                       // git ingnore)
[//]: # (|-- index.html                       // 入口html文件)
[//]: # (|-- package.json                     // 项目及工具的依赖配置文件)
[//]: # (|-- README.md                        // README)
[//]: # (|-- tsconfig.json                     // 指定了编译项目所需的根目录下的文件以及编译选项)
[//]: # (|-- vite.config.ts                    // Vite配置文件)
[//]: # (|-- yarn.lock                    )
[//]: # (```)

## Back-end code
* Golang's implementation: [Astral3DEditorGoBack](https://github.com/mlt131220/ES3DEditorGoBack)

## Quick start
```shell
   git clone https://github.com/mlt131220/Astral3DEditor.git
```

## Run
```shell
    cd Astral3DEditor
    yarn install
    yarn run dev
```
Tips:
* `Node > 18.0.0`;

## Build
```shell
    yarn run build
```

## Thanks for sponsoring🌹🌹🌹
If the project is to help to you, please leave you in [here](https://github.com/mlt131220/ES-3DEditor/issues/2) site, let more people see. Your reply will be the motivation for me to continue updating and maintaining。 </br></br>
This project code is completely open source and free to learn & use, if you are happy and want to donate, you can scan the QR code below：</br>
<img src="https://upyun.astraljs.com/static/images/alipay.jpg" width="320px">
<img src="https://upyun.astraljs.com/static/images/wepay.jpg" width="320px">

## Declaration of interest
This project is open source based on the Apache-2.0 protocol, anyone can use it for free, but in any case, please do not use it for commercial purposes, please contact the author for authorization.

## Disclaimer
This project is only for learning and exchange, do not use for any illegal purposes, otherwise the consequences will be your own.
The author assumes no legal responsibility for any problems arising from the use of this project (original project or after secondary creation).

## Star History
[![Star History Chart](https://api.star-history.com/svg?repos=mlt131220/Astral3DEditor&type=Date)](https://star-history.com/#mlt131220/Astral3DEditor&Date)

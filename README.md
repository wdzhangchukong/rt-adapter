# rt-adapter
Cocos runtime Tiny Game
## 使用方法
---
* 将 `rt-adapter.js` 放入工程内.

* 修改 REMOTE_SERVER_ROOT 属性，为 `res/raw-assets` 的上级目录.

* 在要调用动态加载网络资源之前,使用下列代码引入即可.

```
require("rt-adapter");
```
---
## 打包
---

* 将打包好后的 `res/raw-assets` 目录放到服务器中的 `res/raw-assets` 目录,并且从原包路径中移除.

---



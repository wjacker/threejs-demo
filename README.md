# 基于threejs的 3D场景展现 <br />

### 项目概述<br />
3D 场景模型展现。

### Demo地址：<br />
<http://39.107.106.239:8888/>


### 主要功能<br />
1. 单个3D模型的导入导出，目前支持格式有：.obj, .mtl, .3ds
2. 3D模型的基本操作：移动（水平|垂直移动），旋转，大小调整，删除
3. 整体场景的导入导出, 优化了整体场景导出的大小问题，从全量导出（单个场景导出在8M以上）到只导出关键指标（2KB以内）
4. 3D 场景跟外部页面的联动，支持从外部页面拖拽3D 物体进入3D 场景
5. 3D 场景的镜头旋转以及缩放控制，场景中墙体根据视角的位置智能隐藏/显示

### TODO<br />
1. 更多的3D模型支持，以及更多材质的支持
2. 3D 模型动画
3. 3D 模型的复制，更改模型的材质/贴图等功能

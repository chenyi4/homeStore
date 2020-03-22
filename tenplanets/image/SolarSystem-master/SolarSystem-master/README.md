##太阳系模拟系统
**目录说明**
**功能简介**
**其他说明**

---------------------------------------------------------------------

###目录说明
目录 | 说明
--- | ---
doc | 该工程的说明文档
SolarSystem | 该工程的源码

###功能简介
 基于 three.js 的 WebGL API 模拟实现一个太阳系系统。 主要功能模块如下： <br/>
 **1. 运动模块：实现各行星的公转与自转；**<br/>
 **2. 轨道绘制：绘制每个行星的公转和自传轨道；**<br/>
 **3. 土星环绘制：使用自定义的几何体创建土星环；**<br/>
 **4. 太阳绘制：着色器绘制太阳；**<br/>
 **5. 群星绘制：很多随机的 Point 构成远处恒星；**<br/>
 **6. 各行星视角：好似身处于行星之上，观看太阳系。**<br/>

###其他说明
 该工程没有兼容浏览器，在Chrome下测试没有问题<br/>
该工程由于需要加载资源文件，需要搭建服务器，也可以直接在webstorm中打开。<br/>
该工程参考的纹理文件来自 \<\<WebGLBook>>
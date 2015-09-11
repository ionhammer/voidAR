# voidAR
太虚AR引擎例子，目前支持Unity3d 4.x和iOS平台

====================如何使用=======================

1、导入TXAR.unitypackage；

2、在Project面板中按照路径Assets\TXAR\Scene，找到Scene打开,在Hierarchy中结构为：

-All 

-Directional light

-Marine_Marker

-Tank_Marker

-UI

-ShadowPlane

3、选中Marine_Marker或者Tank_Marker，在Inspector中找到Marker(Script)中Image选项值，选中后在Project面板中可查看到识别Marker的图片（Assets\StreamingAssets目录下，图片名称为10的为战士，11为坦克）；

4、在A4纸上用粗笔（比如黑色水彩笔）画出Marker图片的内容，内容大致相同即可；

5、点击运行按钮，程序启动后将开启摄像头，摄像头对着画出Marker图片，识别成功后将在Marker图片上显示对应3D模型。

自定义Marker实现参见 《太虚 alpha-0.01.doc》。

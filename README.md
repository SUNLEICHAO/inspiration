# inspiration

> 初始化完成；
> v0.01 首页和收藏夹基础完成
> v1.00 基本样式完成
> v1.01 包括图片布局自适应在内的多处修复
> v1.02 包括图片展示时,空位的摆放方式等多处的体验优化
> v1.03 “返回”和“加号”的hover效果

## 待解决

+ （体验）其他问题
+ 字体与设计图中的字体不相同

## 已解决

+ 首页，图片缩放后变小，间距变大（gird需要先行定义好个数，可以直接flex）
+ header的首页和收藏夹宽度问题（flex-shirk-0，禁止行宽自动缩小）
+ 收藏页，宽屏时没有适应往后排列（原因：宽度固定）
+ （体验）导航和搜索栏的间距，加边距
+ （体验）搜索栏尝试放中间
+ （体验）首页展示的图片，改进展示方式（grid布局响应式，大小和个数响应式变化）
+ （体验）设定body最大宽度，超过1920px后，内容自动居中，而不是继续自动加宽
+ （体验）

## 登录页面和登陆方式的显示/隐藏方式

1. 登陆页面
  page-login元素在存在"active"类名时，显示；否则将会隐藏。
2. 登陆方式切换
   两个login-box元素分别对应“二维码登录”和“手机号码登录”，当有"active"类时，显示当前登陆方式。

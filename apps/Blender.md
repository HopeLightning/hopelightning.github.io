# Blender
## 简介
- 教程
	- 经典教程
		- 【1】 Blender Guru 的甜甜圈教程，几乎所有大神都是从这个甜甜圈开启的 blender 之路。  
			- 3.0全新版教程地址：[网页链接](https://weibo.cn/sinaurl?u=https%3A%2F%2Fwww.youtube.com%2Fplaylist%3Flist%3DPLjEaoINr3zgFX8ZsChQVQsuDSjEqdWMAD)  


---
## Note

### 参考视图设置
#### 快捷键
- `Shift + A` 添加图像中的参考
#### 相关参数
- `物体数据属性`中![在这里插入图片描述](https://img-blog.csdnimg.cn/20200303132113373.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2hlbGxvX3R1dGU=,size_16,color_FFFFFF,t_70#pic_center)
	- `深度`：**后**（显示在模型后）  
	- `边`：**前**（在背面时不显示）  
	- `显示正交`：**是**（正交视图-显示）  
	- `显示透视`：**否**（透视视图-不显示）
#### 相关操作
- 复制，旋转，移动创建其他视图
- 选中，按 `M` 添加到新集合，设为不可选择

### 参数化
#### 水流制作
#待办 [Tutorial: Advanced anime water splash FX in blender - YouTube](https://www.youtube.com/watch?v=zZsfr5f273c)

#### 几何节点
- #待办 
	- [Geometry Nodes Blender 3.0 Tutorial for Beginners | Part 1 - YouTube](https://www.youtube.com/watch?v=yZgLhffsVd8)
	- [blender 3.1 geometry nodes制作程序化花朵_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1WL4y1F7Mi?spm_id_from=333.337.search-card.all.click&vd_source=e9cede70e26825b2d2f7ca049a5aec1e)
	- [blender Geometry Nodes 变形过渡效果_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1QM4y1F79m/?spm_id_from=333.788.recommend_more_video.0&vd_source=e9cede70e26825b2d2f7ca049a5aec1e)
	- 浆果参数化 [Blender 2.93 New Geometry Nodes Tutorial - YouTube](https://www.youtube.com/watch?v=TjGL4RjR13Q)
	- [Blender 2.93 Splash Walk-through - YouTube](https://www.youtube.com/watch?v=hJsxNAIAn30&t=447s)
	- 动效
		- [Blender3D - Transforming effect using Geometry nodes - YouTube](https://www.youtube.com/watch?v=B2HMdtND4ws)

### 风格化
#### 音乐可视化
- 链接
	- [Create A Sci-fi City Looping Animation in Eevee (Blender Tutorial) - YouTube](https://www.youtube.com/watch?v=L6jMlmlbiVo)
	- [Easy Reactive Audio visualizer For Your Entire Song (Blender Eevee Tutorial) - YouTube](https://www.youtube.com/watch?v=0yA49cwE_V4)
	- [Create A Beautiful Aud-io Visualizer With Eevee in Blender 2.90 (Blender Tutorial) - YouTube](https://www.youtube.com/watch?v=Mha6OXjoDwE&t=448s)

- 曲面 进入 ‘编辑模式’ 右键 表面细分 切面数调至 100 
- 

#### 三渲二
- 三渲二（粗描边风格）
	- 轮廓线
		- 附完主体材质后
		- 新建材质
			- 删掉**Principled BSDF**节点
			- 勾选**背面剔除(Backface Culling)**(可先不勾选，方便操作)
		- 使用**实体化**修改器
			- 勾选
				- 均匀厚度(Even Thickness)
				- 填充(Fill)
				- 翻转法线（Flip）
			- Material Offset 调整
			- 修改**偏移Offset**和**厚度Thickness**
	- 轮廓线上色
		- 添加**Mix shader**即可
		- 渐变色
			- 添加**Transparent BSDF**和**Emission**
				- **Shift + Ctrl 右键拖动**两个节点即可创建Mixshader节点并连接

### 材质
#### 金属
- **金属材质**
	- 材质制作
		- 拉高金属度
		- 糙度拉低
		- 【世界环境】颜色改成环境纹理
			- 思路：添加 黑白对比强烈的复杂图像 增加材质细节
		- 【渲染】-【胶片】中选择透明（消除背景）
		- 【着色器编辑器】在世界环境中，修改背景图片颜色、对比度
			- 对比度也可在【渲染】-【色彩管理】中修改胶片效果获得
#### 材质节点
- #待办 
	- [All 80+ Blender material nodes explained in under 30 minutes - YouTube](https://www.youtube.com/watch?v=cQ0qtcSymDI)
#### 衣物
- 衣物缝合
	- 先给人体加上碰撞属性，`外部厚度`设为0.001
	-  
### 插件
#### [[Rigify]]

#### [[Easy Windy Leaves]]

### 技巧
#待办 [I packed 50 BLENDER TIPS into one video! - YouTube](https://www.youtube.com/watch?v=4YDf_ctubbI)

### 学习对象
- 个人
	- [开发游戏的老王的博客_CSDN博客-Blender笔记,游戏美术笔记,Godot笔记领域博主](https://orzgame.blog.csdn.net/?type=blog)

### [[07-30-2022]]
- 相关
	- [blender《春》2019全新动画短片_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV17b411g7C5/?spm_id_from=333.788.recommend_more_video.-1&vd_source=e9cede70e26825b2d2f7ca049a5aec1e)
	- [Blender内置灯光插件，最快AAA级布光！_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1M94y1D7dk/?spm_id_from=trigger_reload&vd_source=e9cede70e26825b2d2f7ca049a5aec1e "Blender内置灯光插件，最快AAA级布光！_哔哩哔哩_bilibili")
		- Blender内置插件 **3点布光**
	- [blender-学什么打光啊，这套灯光资产就够了_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1M94y1D7dk/?spm_id_from=trigger_reload)
		- 利用**灯光资产打光**
	- [Blender 3D灯光插件LeoMoon light studio_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1xU4y1Q7it/?spm_id_from=333.788.recommend_more_video.-1&vd_source=e9cede70e26825b2d2f7ca049a5aec1e "Blender 3D灯光插件LeoMoon light studio_哔哩哔哩_bilibili")
		- 插件[[LeoMoon light studio🔧]]

---
## 错误
### [[Modifier]]
#### [[01-21-2022]]
- 编辑模式下，无法应用修改器、细分表面。

#### [[03-22-2021]]
 原文地址 [spimet.com](https://spimet.com/blog/archives/206)

> (Blender)- 自學記錄 - EEVEE 和 CYCLES 差異–Part01


關於 Blender ，網路上已有很多相關的教學 (在此並不多述請自學) ，但一直沒辨法有效率的學好，每個方法各有各的優點，反而越來越迷茫，最終，發現原來是根本的問題 (基礎沒打好)，沒法舉一反三，因此留下自學記錄 (都是一些基礎，我想包含筆者在內，沒什麼人會去看說明書。)，除了加深自已的印象外，也希望給和筆者一樣遇到迷茫時一個方向。

綱要

1.  渲染器的基本概念
2.  Eevee 渲染器
3.  Cycles 渲染器

**1. 渲染器的基本概念**

所謂 3D 軟體中的 “渲染器”，最簡單理解它們的方式就是——計算公式。

當你把模型建好，附上材質或貼圖，打好燈光並確定了攝像機之後，就要把工作交給計算機，讓它幫助你對此場景中的光影光色做出計算。

不同的渲染器側重的功能有所差異，有些側重於效率（更節約資源、更快）而犧牲一部分的準確性；另一些則需要花費更多的時間與機器資源來得到更準確的光影光色效果（更準確）。

通常這兩者是無法兼得的。

因此，根據實際需要調整相應引數來完善整個工作流就很重要。

例如在未確定效果的階段，我們可以使用更快的渲染器、更低的引數來獲得效率，在最終輸出的階段使用更準確的渲染器、更高的引數來獲得更好的圖面效果。

開啟 Blender 軟體，點選右側渲染圖示—Render Engine（渲染引擎）：

在 Render Engine 的下拉選單中，你可以看到 Blender 中有三種渲染引擎，分別是 Eevee、Workbench 和 Cycles。

其中 Workbench 已經很少被提及和使用了（它最節約資源，但效果是非常非常勉強的，因此略過）；

Eevee 是偏向效率和節約資源的渲染器，但在某些特別的場景氛圍中，Eevee 的效果也非常好，也可以作為最終輸出的渲染器；

Cycles 則是傳統的更講究準確性的渲染器，它更慢，但能對光色做出更準確的計算。

當你需要使用某種渲染器的時候，在 Render Engine 裡做出相應選擇就可以了。

**2. Eevee 渲染器**

2-1. Eevee 渲染器特徵：

Eevee 渲染器是 Blender 最新推出的一款渲染器。它的速度非常快，而且節約資源——哪怕你用筆記本，也可以很快地進行渲染。

在場景中建立平面、猴頭（細分 2 級後光滑顯示）、球體（細分 2 級後光滑顯示）和方塊，給它們附上一些簡單材質：

平面：深灰色，粗糙度 0.1；

猴頭：黃色，粗糙度 0.1；

球體：白色，粗糙度 0.9；

方塊：紅色，粗糙度 0.5。

渲染模式顯示，選擇 Eevee 渲染器，顯示如下圖：

![](https://spimet.com/wp-content/uploads/2021/01/6-4-1.jpg)

在 Eevee 渲染器下操控物體，你會發現特別流暢——這也是為什麼很多人使用 Eevee 渲染器作為預覽場景大致效果的原因之一。

但 Eevee 渲染器的 “快”，是以犧牲一部分計算量為代價而獲得的。

對比 Eevee 和 Cycles 渲染器在這個場景下的渲染效果：

![](https://spimet.com/wp-content/uploads/2021/01/6-4-2.jpg)

可以看到，預設情況下，Eevee 省略掉了對光線反彈的計算——你無法在球體底部看到紅色方塊帶來的紅色反光，也無法在光滑的地面上看到本應該有的各個物體的鏡面反射，這一切在 Cycles 渲染器裡是能夠得到正常顯示的—— Eevee 就是因為這個原因，才會這麼快。

因此，如果你使用渲染的目的在於研究質感、或者得到一個具備準確漫反射氛圍的畫面的話，建議使用 Cycles 渲染器。

如果你的硬體不夠強大，而且處在創作過程中，僅僅想要觀察場景的大致效果，Eevee 會很好用，而且它的輸出質量將會非常好，類似於噪點什麼的會比 Cycles 少很多。

**2-2. 提高 Eevee 渲染器渲染質量的若干引數：**

上一小節說過，Eevee 因為省略了一些計算量，因此在渲染準確度上打了折扣，但我們也是可以通過調整一些引數讓它的渲染效果變得更好一些的，下面是一些比較有用的引數。

**2-2-1. Sampling（取樣值）：**

與渲染質量相關性最大的是這個 Sampling（取樣值）。

**2-2-2Render 是渲染取樣：**

也就是最終出圖（按了 F12 後）輸出的影象質量，數字越高，精度越高，速度越慢。Eevee 一般只需要 64 或 128 就夠了，差別不大。

**2-2-3. Viewport 是預覽取樣：**

就是你在主窗口裡看到的實時渲染效果，你可以把它改成 64，這有助於提高顯示效果。

**2-2-4 Ambient Occlusion（環境光遮蔽）：**

環境光遮蔽也被稱為 “閉塞或 AO”，它是一種不太準確的計算死角的方式，但速度非常快——勾選 Ambient Occlusion 可以讓死角變暗一些，顯得更真實。

![](https://spimet.com/wp-content/uploads/2021/01/6-4-3.jpg)

看上圖，開啟 AO 之後，球體與方塊接觸的部分就會出現死角，這更符合我們的視覺經驗。

你可以通過這兩個引數調節 AO（也就是死角）的範圍和強度，沒有標準答案，以自己感覺協調為準。

**2-2-5 Bloom（輝光）：**

簡單說，勾選 Bloom 輝光，能模擬光線之間照射到人眼視網膜上產生光暈的效果，這也是在模擬一種視覺經驗。

![](https://spimet.com/wp-content/uploads/2021/01/6-4-4.jpg)

通過調節閾值、半徑和強度可以改變輝光的形態：

閾值：代表畫素達到什麼亮度時新增輝光（即：明度高於某個值的畫素才顯示輝光）

半徑：輝光的面積

強度：輝光的亮度

調整這些值之後，輝光會發生變化：

![](https://spimet.com/wp-content/uploads/2021/01/6-4-6.jpg)

輝光的其他引數不太重要，預設即可。

**2-2-6 Screen Space Reflections（螢幕空間反射）：**

勾選 Screen Space Reflections 螢幕空間反射，可以讓具備一定光滑度的材質獲得模擬的鏡面反射效果——因為是模擬的，所以並不準確，但總比沒有要好。

![](https://spimet.com/wp-content/uploads/2021/01/6-4-10.jpg)

如果反射明顯有問題，你也可以從螢幕空間反射的子選單裡調整反射細節，試一試就明白了。

**2-2-7 Shadows（陰影）：**

適當調高 Shadows 陰影中的引數，可以獲得更好的光影質量，引數方面可以直接使用下面這個引數：

**Method : ESM**

**Cube Size : 1024 px**

**Cascade Size : 2048 px**

**勾選**

**High Bitdepth**

**Soft Shadows**

**Light Threshold : 0.01**

把場景中的燈光換成面光源：

![](https://spimet.com/wp-content/uploads/2021/01/6-4-11.jpg)

在燈光具有一定面積的情況下，建議調高參數，這樣投影可以獲得比較真實的軟邊效果（左圖的投影則顯得很假）。

調整上述引數，可以讓 Eevee 的渲染效果變得更好一些。

其實還有一些方法可以讓 Eevee 獲得更好的渲染效果，包括設定反射平面等等，但都太繁瑣了，而且這樣就會損失速度優勢，那還不如直接使用 Cycles 渲染器。

PS : 硬體拉高一些儘量拉高一些，好的機器配置比什麼都重要。

 **3. Cycles 渲染器**

**3-1 Eevee 渲染器由於做了計算量上的省略，所以即便你把上面講到的引數調高，速度也不會變慢多少。但 Cycles 渲染器就不一樣了，很多引數會明顯改變所需的渲染時間。**

**3-2 對渲染效果影響最大的幾個引數是:**

Device（渲染方式）；

Sampling（取樣值）。

其他引數可以預設。

Device（渲染方式）：

對於 Device（渲染方式）來說，如果你的 GPU（顯示卡）不錯，可以考慮在下拉選單中選擇 GPU Compute，這樣相當於讓 GPU 和 CPU 一起工作，速度會快很多，特別是對複雜場景而言更是如此。

如果你的下拉菜單隻有 CPU，說明你的顯示卡不支援 GPU 和 CPU 一起工作的渲染方式，那就選擇 CPU。

另外，讓 GPU 和 CPU 一起工作未必是最快的渲染方式，這取決於顯示卡素質，如果在實際中速度提升並不明顯（甚至變慢了）的話，可以只選擇 CPU。

**3-2-1 Sampling（取樣值）：**

Cycles 渲染器的 Sampling（取樣值）和 Eevee 的取樣值是一樣的，只是調高參數對速度的影響會更明顯。

一般 Viewport（預覽取樣）引數預設 32 即可，如果還嫌太慢，可以設為 16；

Render（渲染取樣）一般不要超過 512，如果只是渲染一個大體的光色參考，經常都是預設 128 的引數。如果渲染噪點過於嚴重，可以考慮把引數調高一些，類似於 256、512 或 1024（會明顯變慢）。

除了渲染方式和取樣值，最終渲染影象的大小也很影響速度。

![](https://spimet.com/wp-content/uploads/2021/01/6-4-15.jpg)

點選右側輸出按鈕，在你設定好輸出的長寬比等因素之後，假如只是測試渲染，你可以把上圖中那個 100% 改為 50% 或 20%，這樣渲染尺寸會變小，渲染速度也會加快，等到渲染質量能夠接受之後，再開 100% 或 200% 獲得更大的圖片畫素進行最終渲染就可以了。

免責聲明：

1. 本影像檔案皆從網上搜集轉載，不承擔任何技術及版權問題

2. 如有下載連結僅供寬頻測試研究用途，請下載後在 24 小時內刪除，請勿用於商業

1. 若侵犯了您的合法權益，請來信通知我們，我們會及時刪除，給您帶來的不便，深表歉意。



### [[03-24-2022]]

### [[03-29-2022]]
> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [www.jianshu.com](https://www.jianshu.com/p/9f17b8b8b778)

Blender 黑铁骑士

P5 讲

• 按住鼠标中键旋转视角  
• 滚动滚轮视角推拉  
• shift + 中键 视角平移  
• G 移动  
• S 缩放  
• R 旋转  
• X 删除物体  
• I 插入关键帧  
• shift+A 新建  
• command+3 细分  
• command+p 设置父级目标  
• Pagedown（修改为 command+↓）→锁定到视图 可以锁定摄像机视图  
• Pageup（修改为 command+↑）

P6 讲 视角操作

• control+option+Q 进入四视图  
• ~ 视图切换  
• 0 摄像机视角  
• N 隐藏属性工具栏

P7 讲 移动旋转缩放（使用辅助系统）

• 变换坐标系（全局、局部、法向、万向、视图、游标）

P8 讲 移动旋转缩放（使用快捷键）

• G 移动  
• S 缩放  
• R 旋转  
• G+(XYZ) 沿对应轴移动  
• S+(XYZ) 沿对应轴缩放  
• R+(XYZ) 围绕对应轴旋转  
• G+(shift+XYZ) 沿对应平面移动  
• S+(shift+XYZ) 沿对应平面缩放

P9 讲 移动旋转缩放（使用参数）

P10 讲 移动旋转缩放（数据归零）

• option+G 坐标归零  
• option+R 旋转归零  
• option+S 缩放归零  
• command+A→全部变换 将物体坐标原点回到世界坐标原点（maya 冻结变换？）

P11 编辑模式和点线面

• TAB 切换（编辑、顶点、面、边）模式 * 需要安装 M3 插件  
• 进入编辑模式之后，1→点模式，2→线模式，3→面模式

P12 “选择” 操作入门

• W 四种选择工具切换（调整、框选、刷选、套索选择）  
• 透显模式（option+Z）打开后可以选择背面的点线面  
• option + 对应的点线面 循环选择  
• 选择点、线、面→command/control 选择最短路径  
• 选择点、线、面→shift 加选→command 减选  
• A 全选  
• AA 取消全选  
• command/control+i 反选

P13 “细分” 操作入门

• 右键→细分  
• control+· 开启 / 退出辅助工具

P14“挤出” 操作入门

• E 挤出  
• 辅助工具→视图叠加层→显示法线  
• 长按挤出→沿法向挤出 / 挤出各个面 / 挤出至光标  
• option+E/shift + 空格→9 沿法向挤出  
• option+E/shift + 空格→0 挤出各个面  
• option+E/shift + 空格→shift+1 挤出至光标

P15 " 环切 “操作入门

• command+R/control+R “环切”  
• command+R/control+R→滚轮 ” 环切 “并增加 / 减少分段数

P16 ” 倒角 “操作入门

• command+B/control+B “倒角”  
• command+B/control+B→滚轮 “倒角” 并增加 / 减少分段数  
• 轮廓形状→0：内凹直角 0.25：斜面 0.5：圆角 0.75：锐圆角 1：直角  
• command+B→P 调节轮廓形状  
• 二次修改 fn+F9

P17 “内插面” 操作入门

• I 内插面（也就是内部挤压）调整厚度→control 调整深度  
• 多个面同时内插时，按一次 I 两边内插，按两次 I 4 边内插

P18 “切刀和切分” 操作入门（含环切进阶知识）

• command+R/control+R 环切  
• command+shift+R 偏移环切边  
• 按住 control + 切割工具可以自动吸附关键点，按回车完成切割  
• 切分操作需要注意，必须选中边 / 面，或者 A 全选。黄色箭头是外侧，黄色箭头反向是内侧

P19 “多边形工具” 操作入门（仅了解即可）  
P20 “多边形工具” 操作入门（仅了解即可）

• 吸附 / shift 多选吸附的项目  
• 在未开启吸附模式时，按住 control 可以强行开启吸附模式

P21 “环绕和环绕副本工具” 操作入门（类似于 C4D 的阵列）

• 弯管实例  
• 注意调节好环绕中心点即可  
• 环绕副本工具可以用来制作一些围绕旋转等效果

P22 “光滑和随机工具” 操作入门

• 光滑的作用是让物体的边缘进行相应的收缩平滑，不仅对面有作用，对边线也起作用  
• 随机工具作用类似于噪波

P23 “边和点滑动工具” 操作入门

• GG 滑动边 / 点 不同于 G，GG 是让选中的点 / 边沿表面进行移动，而 G 是让选中的点 / 边自由移动不受表面的约束。  
• 在选中面的状态下，GG 可以让面进行放大 / 缩小，这个放大缩小是沿物体表面进行的，而选中面之后 S 虽然也是放大 / 小，但并不会沿物体表面，而是在这个面所在的平面进行的。  
• 对于修改曲面上的点 / 线 / 面，GG 可以做到不改变曲面趋势进行点 / 线 / 面的调节。

P24 “法线缩放和推拉工具” 操作入门

• option+S 沿法线进行缩放  
• 要对 “沿法向挤出” 和“法线缩放”进行区分：“沿法向挤出”会创建新的面，而法线缩放不会。

P25 “切变和球形化工具” 操作入门

• 切变得作用是保持其他结构不变的情况下，改变某一表面的朝向也就是法向  
• 球形化作用是将选中的布线围绕中心点扩张，结合常用来在平面挖洞

P26 “断离工具” 操作入门

• 断离边线可以实现从某个选中的点分裂出来一个新的点  
• 断离区域可以配合环形选择将某个物体从中间断开

P27 “删除和融并” 操作入门

• X 删除→顶点  
→边  
→面  
→仅边和面  
→仅面  
→融并顶点 （用于消除点而不会删除掉关联的面）  
→融并边 （用于消除边而不会删除掉关联的面）  
→融并面 （选中两个或两个以上的相邻面融并成一个面，可以理解为减面）  
→有限融并  
→边线塌陷  
→循环边

P28 “点菜单” 操作入门

• control+V 顶点菜单  
• F 填充（桥接？/ 封闭多边形孔洞）  
• option+M 合并（按照选择的顺序将点合并到一个点）

P29 “边菜单” 操作入门

• control+E 边菜单→挤出边线  
→边线倒角  
→桥接循环边 （用于将两个面打通通路，“挖隧道” 或者 “接骨”）  
→细分 （对边线进行细分，增加分段）  
→细分并排边  
→反细分  
→顺时针旋转边  
→逆时针旋转边  
→滑移边线 （本质就是 GG）  
→拆边  
→边线折痕  
→倒角边权重  
→标记缝合边  
→清除缝合边  
→标记锐边  
→清除锐边  
→为顶点标记锐边  
→为顶点清除锐边标记  
→标记 freestyle 边  
→清除 freestyle 边

P30 “面菜单” 操作入门

• control+F 面菜单→挤出面  
→沿法向挤出面  
→挤出各个面  
→内插面  
→尖分面  
→面三角化  
→三角面变四边面  
→面实体化 （给面增加个厚度，或者加个壳 shell）  
→线框 （根据选中的面生成一个线框，这个线框具有厚度而且独立于选中的面）  
→填充  
→栅格填充  
→完美建面  
→交集（切割） （需要在编辑模式下创建的物体才有效果）  
→交集（布尔） （需要在编辑模式下创建的物体才有效果）  
→焊接边线到面  
→平滑着色  
→平直着色  
→面数据

• 文字转网格：物体模式→物体→转换为→文字转网格 -> 曲线→编辑模式→选中已转化的字符→L 全选→control+F→完美建面→调整角度
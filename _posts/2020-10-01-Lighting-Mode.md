---
layout: post
title:  "IlluminationMode"
author: john
categories: [ Jekyll, tutorial ]
tags: [red, yellow]
image: assets/images/11.jpg
description: "着色的起点."
featured: true
hidden: true
rating: 4.5
---

三．光照模型（illumination model）当光照射到物体表面时,物体对光会发生反射、透射、吸收、衍射、折射、和干涉,其中被物体吸收的部分转化为热,反射、透射的光进入人的视觉系统,使我们能看见物体。为模拟这一现象,我们建立一些数学模型来替代复杂的物理模型，这些模型就称为明暗效应模型或者光照明模型。

- 局部光照
- 处理光源直接照射物体表面的光照明模型被称为局部光照明模型
- 全局光照
- 全局光照模型是基于光学物理原理的，光照强度的计算依赖于光能在现实世界中的传播情况，考虑光线与整个场景中各物体表面及物体表面间的相互影响，包括多次反射 、透射 、散射等


#### Blin-Phone Lighting
- diffuse + spectular
- 变量(光线方向，物体表面法线，视角方向)

### 如何解决自然现象
- 菲涅尔现象
- 次表面反射
- 

#### How to use?
![image](images/avatar.png)

It's actually really simple! Add the rating in your YAML front matter. It also supports halfs:
![rootimage](../assets/images/3.jpg)

hello root only
![titleimage](assets/images/2.jpg)

```html
---
layout: post
title:  "Inception Movie"
author: john
categories: [ Jekyll, tutorial ]
tags: [red, yellow]
image: assets/images/11.jpg
description: "My review of Inception movie. Actors, directing and more."
rating: 4.5
---
```

***

文档名称 | 青春纪念册产品需求文档
-|-
文档状态 | 进行中
小程序名称 | 青春纪念册
文档作者 | 林晓君
发布日期 | 未定

### PRD：产品需求文档
##### 加值宣言
  * 根据调查，市场上大部分为相册记录功能，通过上传照片生成相册h5或其他，功能比较单一，不能满足市场的需要。且传播方式是通过链接分享查看，保存能力不佳，易丢失。
  * 市场上目前没有相关的毕业册纪念app，对于记录班级信息，班级的美好时光，同学之间关系的维系等等。且学生群体强大，对班级纪念册和同学联系等功能也具有较高的期望，市场潜力很大。
  * 以微信小程序呈现，用户能够更加方便的就可以进行登录和使用，无需下载注册。

这是一款线上的纪念册小程序，通过手机微信登录就可以使用。主要面向对象是广大学生群体甚至是已毕业的群体。此小程序将会与各个学校进行合作，联手打造学生的青春纪念册。用户可以通过此小程序查看自己在校的美好记录和回忆，通过此小程序，同学们可以浏览同班同学们上传的在校美好回忆杀，比如班级大事件、班级和朋友间照片，或是当年发生趣事等等。更有去年今日的事件列表，带你回到那时的今天。用户也可以在此app上发布自己的动态。

**主要功能：**人脸识别功能。使用人脸识别api。识别照片中的每一个面孔，点击头像可以出现其名字，还可查看有关于他的相册和基本信息。

**主要功能：**同城聚餐功能，规划路线。使用了高德地图的静态地图以及路径规划。通过同城定位即可知道小伙伴们都在哪个城市，同时可以邀请同城的同学发送聚餐邀请并进行路径规划至聚餐地点。

##### 核心价值
通过线上的纪念册这一平台，各个同学可以分享自己的近况和同学同城聚会。维系同学之间的关系，唤起你校园的回忆。

##### 最小可行性产品
记录、查看和回忆在校生活的点滴，可以识别图中同学的脸进入其照片夹以及信息页，实现同城聚会功能和路径规划功能。

##### 目标用户
在读中小学生、大学生群体，已毕业的毕业生群体。

##### 用户痛点
场景一：小林想查看毕业照，但是她的毕业册不见了。
场景二：小林想知道同学们都在哪个生活，也想和在同一个城市生活的同学们聚聚餐、唠唠嗑。
场景三：小林在浏览班级照片时，忘记这个她曾经喜欢的男孩子的名字，不知道他现在过得好不好，现在他是长什么样子呢？

##### 功能
1.**高德地图定位功能和路径规划功能**（有使用api）。毕业纪念app会自动定位用户的城市（当然这里会获得用户的允许），然后在你的好友圈地图上就可以清晰知道大家分布在中国的哪里。在同一城市的大家也可以更方便的交流、甚至校友、班级聚会。还可以为用户聚会提供路径规划的功能，选择目标聚会点后，进行用户到目标聚会点的路径规划。

2.**人脸识别功能**（有使用api）。
录入信息后，系统匹配同学们的脸和照片。用户查看照片时，点击脸部将出现该同学的名字，双击则进入该同学的照片夹和信息页，了解这位同学。

##### 用户需求:（使用的人工智能要反映到需求列表中）
用户案例 | api使用| 重要程度
-|-|-
用户想知道照片中的同学的名字 | 人脸识别 | 重要
用户想要知道同学们所在城市 | 静态地图 | 重要
用户不想打开别的app进行路径导航，希望能直接给出到聚会地点的导航指引 | 路径规划 | 次重要

##### 具体应用场景
1.今天洋子在下班的路上偶遇她的高中同学，但是她忘记了对方的名字，为了避免尴尬情况发生，于是她立刻打开青春纪念册小程序浏览高中班级的班级合照，然后点击该同学的脸部自动人脸识别识别那位同学的名字，并进入主页看到她现在的照片，发现她已经成为了猫狗双全的人生赢家，知道了同学名字和近况后，她自信的和高中同学打了招呼，并一起吃了个晚饭，度过了一个愉快的夜晚。

2.毕业了好几年，同学各奔东西，小林想大家都去了什么地方呢？于是她打开青春纪念册小程序，查看同学圈大家的城市的定位。她发现蛮多熟人都在同城，于是对他们发送了聚餐邀请，并选择了目的聚餐点，等待其他同学的聚餐回复。过了一个小时，大家都陆陆续续的回复了，小林好开心哦！很快可以见到好久不见的老同学了呢！

3.小海是小林大学的姐妹，有一天她收到了小林来自青春纪念册的聚会邀请，刚好那天有空，她也好想这位多年没见的姐妹了，于是开心的接受了邀请。但是聚会点的那个餐厅她不熟悉，但是她又不想打开第三方导航app查询，正在为此事头疼时，突然发现小程序居然提供了多种导航方案，小海很开心。

***
### 产品原型
* [产品原型](http://nfunm049.gitee.io/memorial-book)
* [原型下载地址](https://gitee.com/NFUNM049/Memorial-Book)

1.授权页

![授权.png](https://upload-images.jianshu.io/upload_images/9455364-2ba922990613ae8c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2.主页

![](https://upload-images.jianshu.io/upload_images/9455364-69c012b057340b83.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3.相册

![相册.png](https://upload-images.jianshu.io/upload_images/9455364-c39986393acb18c0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

4.同城聚会

![同城聚会.png](https://upload-images.jianshu.io/upload_images/9455364-a826a5b8990eb2c2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![邀请聚会.png](https://upload-images.jianshu.io/upload_images/9455364-2db4ea863e0a0c62.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![邀请聚会2.png](https://upload-images.jianshu.io/upload_images/9455364-b4aad5a89e495989.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

5.我的
![我的.png](https://upload-images.jianshu.io/upload_images/9455364-c48604cd344b17fd.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



***
### api选择与调用
#### api的选择
1.人脸识别

我使用了azure、face++和阿里云的人脸识别api服务，通过单人照、双人照、五人照进行测试比较分析。**最终选择使用face++的人脸识别服务。**

**优点：**face++识别准确，表现卓越，功能丰富，且人脸识别为其公司的尖端技术，比azure和阿里云的人脸识别服务更胜一筹。
**缺点：**在使用较低质量或人脸模糊的照片时，不能进行很好的识别。照片需具有较高的质量，且为正脸，脸部无遮挡。

2.静态地图 路径规划

**静态地图和路径规划我都选择了高德地图提供的api服务。**

**优点：**与百度提供的服务相比，高德的api十分简单易上手，一行代码，而百度最少要五行，对新手来说比较友好；数据量比较丰富；对开发者比较友好。
**缺点：**
1、偶尔出现报错，需要clean project；
2、网络不好时，定位不准确。

#### api的调用
* [face++人脸识别-人脸检测](https://www.faceplusplus.com.cn/face-detection/)
接口描述：检测并定位图片中的人脸，返回高精度的人脸框坐标。Face++还支持存储检测到的人脸元数据，以便日后使用。

接口地址：[https://api-cn.faceplusplus.com/facepp/v3/detect](https://api-cn.faceplusplus.com/facepp/v3/detect)

输入：
```
# -*- coding: utf-8 -*-
import urllib.request
import urllib.error
import time

http_url = 'https://api-cn.faceplusplus.com/facepp/v3/detect'
key = "输入key"
secret = "输入secret"
filepath = r"D:\F盘 \api\timg.jpg"
boundary = '----------%s' % hex(int(time.time() * 1000))
data = []
data.append('--%s' % boundary)
data.append('Content-Disposition: form-data; name="%s"\r\n' % 'api_key')
data.append(key)
data.append('--%s' % boundary)
data.append('Content-Disposition: form-data; name="%s"\r\n' % 'api_secret')
data.append(secret)
data.append('--%s' % boundary)
fr = open(filepath, 'rb')
data.append('Content-Disposition: form-data; name="%s"; filename=" "' % 'image_file')
data.append('Content-Type: %s\r\n' % 'application/octet-stream')
data.append(fr.read())
fr.close()
data.append('--%s' % boundary)
data.append('Content-Disposition: form-data; name="%s"\r\n' % 'return_landmark')
data.append('1')
data.append('--%s' % boundary)
data.append('Content-Disposition: form-data; name="%s"\r\n' % 'return_attributes')
data.append(
    "gender,age,smiling,headpose,facequality,blur,eyestatus,emotion,ethnicity,beauty,mouthstatus,eyegaze,skinstatus")
data.append('--%s--\r\n' % boundary)

for i, d in enumerate(data):
    if isinstance(d, str):
        data[i] = d.encode('utf-8')

http_body = b'\r\n'.join(data)

# build http request
req = urllib.request.Request(url=http_url, data=http_body)

# header
req.add_header('Content-Type', 'multipart/form-data; boundary=%s' % boundary)

try:
    # post data to server
    resp = urllib.request.urlopen(req, timeout=5)
    # get response
    qrcont = resp.read()
    # if you want to load as json, you should decode first,
    # for example: json.loads(qrount.decode('utf-8'))
    print(qrcont.decode('utf-8'))
except urllib.error.HTTPError as e:
    print(e.read().decode('utf-8'))
```

* [高德地图-静态地图](https://lbs.amap.com/api/webservice/guide/api/staticmaps)

接口描述：静态地图服务通过返回一张地图图片响应HTTP请求，使用户能够将高德地图以图片形式嵌入自己的网页中。用户可以指定请求的地图位置、图片大小、以及在地图上添加覆盖物，如标签、标注、折线、多边形。

接口地址：https://restapi.amap.com/v3/staticmap?parameters

输入：
```
import requests
from PIL import Image
from io import BytesIO

def jingtai(location):
    '''静态地图'''
    url = "https://restapi.amap.com/v3/staticmap?parameters"
    params = {
        'key' : key_xu,
        'location' : location,
        'zoom' : "15",
        'size' : "1920*1080"
   }
    response = requests.get(url,params=params)
    data = Image.open(BytesIO(response.content))
    return data
```

* [高德地图-路径规划](https://lbs.amap.com/api/webservice/guide/api/direction)

接口描述：路径规划API是一套以HTTP形式提供的步行、公交、驾车查询及行驶距离计算接口，返回JSON 或 XML格式的查询数据，用于实现路径规划功能的开发。 

接口地址：https://restapi.amap.com/v3/direction/walking?parameters

输入：
```
def walking(origin,destination):
    '''进行路径规划'''
    url = "https://restapi.amap.com/v3/direction/walking?parameters"
    params = {
        'key' : key_xu,
        'origin' : origin,
        'destination' : destination
    }
    response = requests.get(url,params=params)
    data = response.json()
    return data
```



- [特色](#特色)
- [什么是markdown](#什么是-markdown)
- [Markdown TodoList](#Markdown-TodoList)
- [公式](#公式)


# Towxml

![Towxml](https://www.vvadd.com/wxml_demo/logo--horizontal.svg)

由于微信小程序==不允许直接渲染==`HTML`，因此富文本编辑器生成的`HTML`内容无法直接在小程序中展示。

<audio autoplay="true" loop="true" name="此时此刻" author="许巍" poster="https://www.vvadd.com/wxml_demo/music.jpg"  src="https://www.vvadd.com/wxml_demo/music.mp3"></audio>

**Towxml** 正是为了解决这一切，Towxml是一个可将`HTML`、`markdown`转换为`WXML`(WeiXin Markup Language)的渲染库。

## 特色

- 支持echarts图表（3.0+）✨
- 支持LaTex数学公式（3.0+）✨
- 支持yuml流程图（3.0+）✨
- 支持按需构建（3.0+）✨
- 支持代码语法高亮
- 支持emoji表情:wink:
- 支持上标、下标、下划线、删除线、表格、视频、图片（几乎所有html元素）……
- 支持typographer字符替换
- 支持多主题切换
- 支持Markdown TodoList
- 支持事件绑定（这样允许自行扩展功能哟，例如：点击页面中的某个元素，更新当前页面内容等...）
- 极致的中文排版优化
- 支持前后解析数据

---


## 什么是 Markdown

**Markdown** 是一种方便记忆、书写的纯文本标记语言，用户可以使用这些标记符号以最小的输入代价生成极富表现力的文档：譬如您正在阅读的这份文档。它使用简单的符号标记不同的标题，分割不同的段落，**粗体** 或者 *斜体* 某些文字。

**更多详见** [http://www.markdown.cn/](http://www.markdown.cn/)


## Markdown TodoList

- [ ] 一起去旅行
- [ ] 跟同学聚会
- [x] 晚上十点足球比赛
- [x] 测试用例撰写

## 公式

行内数学公式$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$ 演示。公式单引号演示${X}''$。LaTeX是一种基于TeX的文档排版系统,把大片排版的格式细节隐藏在若干样式之后，以内容的逻辑结构统帅纷繁的格式，遂成为现在最流行的科技写作——尤其是数学写作的工具之一。

$$
\frac{1}{(\sqrt{\phi \sqrt{5}}-\phi) e^{\frac25 \pi}} =
1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {1+\frac{e^{-6\pi}}
{1+\frac{e^{-8\pi}} {1+\ldots} } } }
$$

$$

    \left( \sum_{k=1}^n a_k b_k \right)^{\!\!2} \leq
     \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
$$


## 图文排列

**边城`沈从文`著——中篇小说**

> 在川湘交界的茶峒附近，小溪白塔旁边，住着主人公翠翠和她爷爷老船夫。茶峒城里有个船总叫顺顺，他有两个儿子，老大叫天保，老二叫傩送。

![凤凰古城](https://www.vvadd.com/wxml_demo/img.jpg)
端午节翠翠去看[龙舟赛](http://link)，偶然相遇相貌英俊的青年水手傩（nuó）送，傩送在翠翠的心里留下了深刻的印象。同时，傩送的兄长天保也喜欢上了翠翠，并提前托媒人提了亲。天保告诉傩送一年前他就爱上了翠翠，而傩送告诉天保他两年前就爱上了翠翠，天保听了后也吃了一惊。然而此时，当地的团总以新磨坊为陪嫁，想把女儿许配给傩送。而傩送宁肯继承一条破船也要与翠翠成婚。

兄弟俩没有按照当地风俗以决斗论胜负，而是采用公平而浪漫的唱山歌的方式表达感情，让翠翠自己从中选择。傩送是唱歌好手，天保自知唱不过弟弟，心灰意冷，断然驾船远行做生意。

碧溪边只听过一夜傩送的歌声，后来，歌却再没有响起来。老船夫忍不住去问，本以为是老大唱的，却得知：唱歌人是傩送，老大讲出实情后便去做生意。几天后老船夫听说老大坐水船出了事，淹死了……

码头的船总顺顺因为儿子天保的死对老船夫变得冷淡。船总顺顺不愿意翠翠再做傩送的媳妇。老船夫只好郁闷地回到家，翠翠问他，他也没说起什么。夜里下了大雨，夹杂着吓人的雷声。第二天翠翠起来发现船已被冲走，屋后的白塔也冲塌了，翠翠去找爷爷却发现老人已在雷声将息时死去了…… 老军人杨马兵热心地前来陪伴翠翠，也以渡船为生，等待着傩送的归来。


## rich-text 支持测试

<rich-text>
<table>
    <tr>
        <td>背景</td>
        <td colspan="2">第二次世界大战中，世界反法西斯国家提出了建立战后国际安全组织的主张</td>
    </tr>
    <tr>
        <td>成立</td>
        <td colspan="2">1945年10月</td>
    </tr>
    <tr>
        <td>地位</td>
        <td colspan="2">联合国是人类构建世界和平的成果，也是影响最大的国际组织</td>
    </tr>
    <tr>
        <td>总部</td>
        <td colspan="2">设在美国纽约</td>
    </tr>
    <tr>
        <td rowspan="3">主要机构</td>
        <td rowspan="3">联合国大会、联合国安全理事会、联合国秘书处等</td>
        <td>联合国大会简称“联大”，由全体会员国组成，每年举行一届大会</td>
    </tr>
    <tr>
        <td>联合国安全理事会，简称“安理会”，担负着维护国际和平与安全的主要责任。安理会由中国、法国、俄罗斯、英国、美国5个常任理事国和10个非常任理事国组成，常任理事国拥有否决权</td>
    </tr>
    <tr>
        <td>联合国秘书处是联合国的行政秘书事务机构</td>
    </tr>
    <tr>
        <td>职能</td>
            <td colspan="2">根据安理会或联大的决议，联合国可以向冲突地区派出军事人员，以恢复或维持和平。以联合国名义派出的武装力量，被人们称为“联合国维持和平部队”</td>
        </tr>
    <tr>
        <td>作用</td>
        <td colspan="2">联合国在维护国际和平与安全方面发挥了积极作用，使许多国家和地区避免了一些可能发生的战争</td>
    </tr>
 </table>
</rich-text>



## Code

Python

``` python
@requires_authorization
def somefunc(param1='', param2=0):
    '''A docstring'''
    if param1 > param2: # interesting
        print 'Greater'
    return (param2 - param1 + 1) or None
class SomeClass:
    pass
>>> message = '''interpreter
... prompt'''
```

Xml

```xml
<?xml version="1.0"?>
<!DOCTYPE mycat:schema SYSTEM "schema.dtd">
<mycat:schema xmlns:mycat="http://io.mycat/">
	<schema name="doubaSchema" checkSQLschema="false" sqlMaxLimit="100" dataNode="dn1"></schema>
	
	<dataNode name="dn1" dataHost="dh1" database="douba" />
	
	<dataHost name="dh1" maxCon="500" minCon="20" balance="1" writeType="0" dbType="mysql" dbDriver="native" switchType="2" slaveThreshold="100">
		<heartbeat>show slave status</heartbeat>
		
		<writeHost host="hostM41" url="192.168.2.41:3306" user="root" password="123456" >
			<readHost host="hostS42" url="192.168.2.42:3306" user="root" password="123456" />
			<readHost host="hostS43" url="192.168.2.43:3306" user="root" password="123456" />
		</writeHost>
	</dataHost>
</mycat:schema>
```

Html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
    content text...
</body>
</html>
```

Css

```css
html,body {background:white;}
.box {width:200px; height:200px;}
```

Javascript

```javascript
(()=>{
    const fs = require('fs');
    
    let sum = (a,b)=>{
        return a+b;
    };
    
    console.log(sum(1+2));
})()
```

Bash

```bash
# 查看当前仓库情况
$ git status

# On branch branch -b
# You have unmerged paths.
```

## emoji 8-)

> Classic markup: :wink: :crush: :cry: :tear: :laughing: :yum:
>
> Shortcuts (emoticons): :-) :-( 8-) ;)


## Table

| Item      			|    Value | Qty  |
| :-----------------------------| --------:| :--: |
| Computer  			| 1600 USD |  5   |
| Phone     			|   12 USD |  12  |
| Pipe$\sqrt[n]{a}$:wink: 	|    1 USD | 234  |


### Typographic replacements

Enable typographer option to see result.
(c) (C) (r) (R) (tm) (TM) (p) (P) +-
test.. test... test..... test?..... test!....
!!!!!! ???? ,,  -- ---
"Smartypants, double quotes" and 'single quotes'


## Emphasis

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Strikethrough~~


## Blockquotes

> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.


## Lists

Unordered

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
    - Marker character change forces new list start:
        * Ac tristique libero volutpat at
        + Facilisis in pretium nisl aliquet
        - Nulla volutpat aliquam velit
+ Very easy!


Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa

1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`


Start numbering with offset:

57. foo
1. bar


## Links

[https://github.com/sbfkcel/towxml](https://github.com/sbfkcel/towxml)
[https://www.npmjs.com/package/towxml](https://www.npmjs.com/package/towxml)


## Subscript/Superscript

- 19^th^
- H~2~O


## ins

++Inserted text++


## Mark

==Marked text==

## Echarts

```echarts
{
  "height": 260,
  "option": {
    "xAxis": {
      "type": "category",
      "boundaryGap": false,
      "data": [
        "Mon",
        "Tue",
        "Wed",
        "Thu",
        "Fri",
        "Sat",
        "Sun"
      ]
    },
    "yAxis": {
      "type": "value"
    },
    "series": [
      {
        "data": [
          820,
          932,
          901,
          934,
          1290,
          1330,
          1320
        ],
        "type": "line",
        "areaStyle": {}
      }
    ]
  }
}
```

## Echarts

```echarts
{
  "height": 260,
  "option": {
    "tooltip": {
      "trigger": "axis",
      "axisPointer": {
        "type": "cross",
        "label": {
          "backgroundColor": "#6a7985"
        }
      }
    },
    "legend": {
      "data": [
        "邮件营销",
        "联盟广告"
      ]
    },
    "xAxis": [
      {
        "type": "category",
        "boundaryGap": false,
        "data": [
          "周一",
          "周二",
          "周三",
          "周四",
          "周五",
          "周六",
          "周日"
        ]
      }
    ],
    "yAxis": [
      {
        "type": "value"
      }
    ],
    "series": [
      {
        "name": "邮件营销",
        "type": "line",
        "stack": "总量",
        "areaStyle": {},
        "data": [
          120,
          132,
          101,
          134,
          90,
          230,
          210
        ]
      },
      {
        "name": "联盟广告",
        "type": "line",
        "stack": "总量",
        "areaStyle": {},
        "data": [
          220,
          182,
          191,
          234,
          290,
          330,
          310
        ]
      }
    ]
  }
}
```

## Class diagram

```yuml
// {type:class}
// {direction:topDown}
// {generate:true}

[note: You can stick notes on diagrams too!{bg:cornsilk}]
[Customer]<>1-orders 0..*>[Order]
[Order]++*-*>[LineItem]
[Order]-1>[DeliveryMethod]
[Order]*-*>[Product|EAN_Code|promo_price()]
[Category]<->[Product]
[DeliveryMethod]^[National]
[DeliveryMethod]^[International]
```

## Use-case diagram

```yuml
// {type:usecase}
// {direction:leftToRight}
// {generate:true}

(note: figure 1.2{bg:beige})
[User]-(Login)
[Site Maintainer]-(Add User)
(Add User)<(Add Company)
[Site Maintainer]-(Upload Docs)
(Upload Docs)<(Manage Folders)
[User]-(Upload Docs)
[User]-(Full Text Search Docs)
(Full Text Search Docs)>(Preview Doc)
(Full Text Search Docs)>(Download Docs)
[User]-(Browse Docs)
(Browse Docs)>(Preview Doc)
(Download Docs)
[Site Maintainer]-(Post New Event to the Web Site)
[User]-(View Events)
```

## Activity diagram

```yuml
// {type:activity}
// {generate:true}

(start)-><a>[kettle empty]->(Fill Kettle)->|b|
<a>[kettle full]->|b|->(Boil Kettle)->|c|
|b|->(Add Tea Bag)->(Add Milk)->|c|->(Pour Water)
(Pour Water)->(end)
```

## State diagram

```yuml
// {type:state}
// {generate:true}

(start)[Start]->(Simulator running)
(Simulator running)[Pause]->(Simulator paused|do / wait)
(Simulator running)[Stop]->(end)
(Log retrieval)[Continue]->(Simulator running)
(Simulator paused)[Unpause]->(Simulator running)
(Simulator paused)[Data requested]->(Log retrieval|do / output log)
(Log retrieval)->(end)
```

## Deployment diagram

```yuml
// {type:deployment}
// {generate:true}

[Presentation Server]-[Policy Server]
[Policy Server]-[Document Server]
[Product Server]-[Document Server]
[Document Server]ASP.Net-[Workstation]
[Policy Server]-[Database Server]
[Product Server]-[Database Server]
[Policy Server]-[note: To be clustered to meet throughput needs{bg:cornsilk}]
[Policy Server]-[Directory Server]
[Policy Server]-[Underwriting & Rating Server]
```

## Package diagram

```yuml
// {type:package}
// {generate:true}
[Elegibility & Benefits]->[Elegibility Search]
[Remittances] -> [Remittance Search]
[Notifications] -> [Notification Search]
[Check Claim Status] -> [Claim Search]
[Submit a Claim Online] -> [Patient Search]
[Physician/Provider Directory]
[Remittance Search] -> [Search]
[Notification Search] -> [Search]
[Claim Search] -> [Search]
[Patient Search] -> [Search]
[Eligibility Search] -> [Search]
```

## Sequence diagram

```yuml
// {type:sequence}
// {generate:true}

[:Computer]sendUnsentEmail>[:Server]
[:Computer]newEmail>[:Server]
[:Server]reponse.>[:Computer]
[:Computer]downloadEmail>[:Server]
[:Computer]deleteOldEmail>[:Server]
```

## Video
<video class="vidoe" src="https://www.vvadd.com/wxml_demo/video.mp4">视频</video>



## 时序图

```mermaid
sequenceDiagram
participant a as 学生
participant b as 教务系统
participant c as 课程
participant d as 成绩
opt 认证
a->>b: 用户名/密码
end
a->>+b: 请求课程列表
b->>+c: 获取课程列表
c-->>-b: 返回课程列表
b->>+d: 获取成绩信息
d-->>-b: 返回成绩信息
b-->>-a: 显示成绩
```


---


由`Towxml`生成

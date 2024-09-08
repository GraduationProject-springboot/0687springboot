# [首页查询更多项目](https://github.com/GraduationProject-springboot) 包安装运行


# 0687springbootCSGO赛事管理系统--论文

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV14HerezEwW?p=41)


# 绪论
## 1.1开发背景
传统的管理方式都在使用手工记录的方式进行记录，这种方式耗时，而且对于信息量比较大的情况想要快速查找某一信息非常慢，对于CSGO赛事的统计获取比较繁琐，随着网络技术的发展，采用电脑管理相关数据信息管理与数据查询等诸多环节已成为必然趋势；数据情况的透明化，提高了信息管理的透明度，提高管理效率。

传统的CSGO赛事管理系统需要对各类信息及时的进行记录、规整、更新、收藏，这是对数据信息统计管理的极大消耗，在其进行过程中，还会出现因信息的重复传递，出现本可以避免的出错问题，例如：前后CSGO赛事信息不一致、种类纰漏以及备注不详细等等一系列问题。在信息告诉更替的时代，信息的准确性，经济可行性也无疑是众人关注的焦点。那么我们系统的目的性也就很明确。

如今，随着社会的不断发展，计算机技术已经逐渐成熟和完善，并且已经融入到人们生活的方方面面之中，系统的各项管理都开始向信息化的方向扩展。计算机拥有查询迅速、储存量大、安全性好、可靠性高、节约人力，花费少等长处。这些长处使其能够对管理效率给予极大的提高。所以，用计算机来代替传统的人工方式来进行CSGO赛事管理已是大势所趋，CSGO赛事管理系统应运而生。

在世界范围内，CSGO赛事管理系统已经得到了非常广泛的应用，范围变的越来越广，功能也在不断的完善，操作简便、节省人力、成本低廉，但工作的效率确一直不断的提高。为CSGO赛事行业管理全程提供自动化和全面的纪录，避免出错的概率，提高用户的满意程度。

CSGO赛事管理系统的作用就是提供一个在线CSGO赛事管理的信息储存以及搜索的系统，用来协助对CSGO赛事信息进行统一管理。一个完善的CSGO赛事管理系统，可以对CSGO赛事进行精细化的管理。
## 1.2课题研究的目的和意义
人们现在的生活方式因为网络的普及发生了巨大变化，由于网络管理在人们的视野中出现，人们对网络管理额外的关注。人们只要在有网络的地方足不出户查看到世界各地的各类。目前的挑战是前台界面的设计，要把顾客的眼球吸引住，选则比较人性化的界面设计，要更直观的表现，让用户能更多的了解在CSGO赛事管理系统的信息。

本系统的主要意义在于，全力以赴为用户提供一个操作方便，界面简洁，信息直观的CSGO赛事管理系统。使用该系统的用户，可以先浏览到最新上架的CSGO赛事信息，并可以注册成为本网站的用户。
## 1.3课题设计目标
针对CSGO赛事行业的管理现状，本CSGO赛事管理系统主要实现以下几个目标：

`    `1.系统界面简洁，操作简便。

`    `2.拥有精准，高效的查询功能。

`    `3.能使管理人员能够及时的获得精确的报表

`    `4.对数据内容的管理安全，稳定，易维护

`    `5.对信息全面跟踪，方便管理人员进行管理。

`    `6.提供客户登录和修改密码等服务，加强系统安全。

7.提供用户管理和数据备份，确保信息的安全性和可靠性。












# 2.开发技术介绍
## 2.1 Java语言简介
Java是由SUN公司推出，该公司于2010年被oracle公司收购。Java本是印度尼西亚的一个叫做爪洼岛的英文名称，也因此得来java是一杯正冒着热气咖啡的标识。Java语言在移动互联网的大背景下具备了显著的优势和广阔的前景，它是面向对象的，分布式的，动态的，具有系统无关性、安全性、健壮性。Java语言的基本语句语法和C++一样，但是它面向对象的技术更加彻底，因为Java要求将所有的内容都必须封装成类，把类作为程序的基本单位。由于不允许类外有变量、方法。 Java语言的分布式体现在数据分布和操作分布，它是面向网络的语言，可以处理TCP/IP协议，它也支持客户机/服务器的计算模式。Java语言的动态性是指类在运行时是动态安装的，使得Java可以动态的维护程序。Java不支持指针，对内存访问的所有操作都是通过对象实例化实现的，这样就避免了指针操作中易产生的错误，同时也预防了病毒对系统的破坏和威胁。

Java语言的编程风格与C语言非常接近，它继承了C++面向对象技术的核心，它面世之后发展迅速，非常流行，对高级C语言形成了很大的冲击。业内人士称之为“一次编译、到处执行”。当然java也有缺点，在每次执行编译后，字节码都需要消耗一定的时间，在某些程度上降低了性能。但是这并不影响java成为此次设计语言的选择。Java语言简单易学，使用它的编程时间短，功能性强，开发者学习起来更简便、更快。Java的主要特性有以下几个：

1.面向对象

面向对象有四个特点：封装、继承、多态、抽象。抽象是指忽略一个问题中的次要部分，关注主要部分。多态是指对同一种消息做出的不同反应。继承是指在原有的父类方法基础上增加自己独有的方法，而不改变原来父类。

2.系统无关性

Java编译出来的是字节码，直接由虚拟机执行。在任何系统上，只要有Java虚拟机，Java代码都能运行。

3.可靠性和安全性

Java对内存的访问都必须通过对象的实例变量来实现，避免了指针中出现的错误。

4.多线程	

Java提供了多线程功能，利用编程实现同一时间同时工作的功能。
## 2.2 MySql数据库
在软件项目，通过经营性数据的数据库，可以保证其安全，独立和数据一致，访问数据的系统来提供，所以有效减少时间程序员开发应用程序。

MySQL可以支持多线程，可以方便使用系统的资源，提高运行的速度。并提供odbc、jdbc和tcp/ ip，以各种形式连接到MySQL; 功能方面表现欠缺，规模小，但对于这个系统就足够了。

因为MySQL是源代码对外开放的，所以任何人都可以通过相应的方法下载，并根据个性化需求进行修改。由于MySQL的速度，可靠性和适应性，MySQL受到重视。

MySQL虽然功能可能不是很强大，但由于其开源，广泛传播，导致很多人都意识到这个数据库。
## 2.3 MySQL环境配置
本系统的数据使用的是MySQL，所以要将MySQL安装到指定目录，如果下载的是非安装的MySQL压缩包，直接解压到指定目录就可以了。然后点击C:\Program Files\MySQL\bin\winMySQLadmin.exe这个文件其中C:\Program Files\MySQL是MySQL安装目录。输入winMySQLadmin的初始用户、密码（注：这不是MySQL里的用户、密码）随便填不必在意，确定之后右下角任务的启动栏会出现一个红绿灯的图标，红灯亮代表服务停止，绿灯亮代表服务正常，左击这个图标->winnt->install the service 安装此服务，再左击这个图标->winnt->start the service 启动MySQL服务。

修改MySQL数据库的root密码。用cmd进入命令行模式输入如下命令:

cd C:\Program Files\MySQL\bin

MySQLadmin -u root -p password 123

回车出现Enter password: ，这是要输入原密码. 刚安装时密码为空，所以直接回车，此时MySQL 中账号 root 的密码被改为 123 安装完毕。
## 2.4 B/S结构
B/S的系统是通过能上网的电脑就可以使用，它最大的优点是不需要安装专门的软件，首先浏览器向服务器发出请求，然后服务器处理请求把信息再返回给浏览器。不需要再次对数据进行存取与计算数据，只要负责显示数据来降低要求，如果说客户端像个“瘦子”，而服务器会越来越“胖”。B/S体系结构与C/S体系结构相比，最大的不同是：B/S体系的应用软件使用网络浏览器作为与用户交互的系统，而C/S则需要开发专用的应用程序。

![2009318052962238](/md/blog.010.png)

图2-1 B/S结构图
## 2.5SpringBoot框架
SpringBoot是一个全新开源的轻量级框架。基于Spring4.0设计，其不仅继承了Spring框架原来有的优秀特性，而且还通过简化配置文件来进一步简化了Spring应用的整个搭建以及开发过程。另外在原本的Spring中由于随着项目的扩大导入的jar包数量越来越大，随之出现了jar包版本之间的兼容性问题，而此时SpringBoot通过集成大量的框架使得依赖包的版本冲突，以及引用的不稳定性问题得到了很好的解决。

SpringBoot可以看做是Spring的加强版本，但实质上都是Spring的相关技术，有了这些优秀的开源框架，程序员在开发过程中将事半功倍。









# 3.系统分析
## 3.1需求分析
CSGO赛事管理系统的作用，可以提高CSGO赛事管理的工作人员的效率，协助他们对CSGO赛事信息进行统一管理，为管理者提供信息储存和查询搜索系统。一个良好的CSGO赛事管理系统可以实现对CSGO赛事信息的精细化管理：对在线CSGO赛事管理流程的全过程进行电子化操作，其主要作用是管理和控制CSGO赛事所有的信息，分析库存数据，使工作人员对CSGO赛事管理系统进行监管，根据系统所提供的相应信息，采取适当的措施，及时补救管理中的漏洞，提高在线CSGO赛事管理的工作效率，使得在线CSGO赛事管理变的更加系统和规范。
## 3.2系统可行性分析
可行性分析是在进行初步调查之后，对系统开发的必要性和可行性的研究。针对本系统，主要从技术可行性，经济可行性，社会可行性，法律可行性等方面来论证，具体分析如下：

技术可行性：当今社会人类的科技水平的不断发展，软件开发产业也在不断的壮大。目前，市面上流行的开发产品，已经能过满足不同行业的各种需要。

经济可行性：在当今社会，计算机的性能已经有了很大的提升，价格也不断的下降。因此，并不需要对此程序投入过高的成本。并且，在程序投入使用之后，可以为管理人员带来极大的便捷，大大提高工作效率，减少人力浪费，避免许多不必要的工作和开支。

社会可行性：管理者效率的增加，以及在管理过程中出现错误的可能性的大大减少，也是为了更好的发展铺平道路服务大众。这理应得到各界的一致认可。

法律可行性：本系统绝不违反任何相关的法律法规。
## 3.3 系统现状分析
系统使用用户的数量直接决定了用户信息管理者的工作量，毫无疑问，管理者的工作量较大较繁琐。通过总结出系统当前对用户管理的工作状态得以下分析：

统筹规划，如果系统在信息化管理中不够全面，缺少综合性、系统性、整体性，那不可避免的需要投入大量人力物力来规划整理信息。引入信息化管理方式无疑可以达到节省信息管理成本的目的不仅减少资源浪费还可以使CSGO赛事信息变得井井有条，成为市场竞争中的一大优势。

要循序渐进，做事不能心急，一步一个脚印，都不可能一步到位，就算信息管理系统也一样，要让系统发挥最大效率还是应该多调研，多听取用户和管理者的意见，并进行必要的统筹规划，有组织有目的地设计系统功能，团结各个部门发挥主观能动性。

(1)信息安全措施不到位

隐私权神圣不可侵犯，这是中华人民共和国宪法赋予我们的权利，任何人都不能侵犯我们的正当权益，而网络用户信息管理存在极大安全隐患，信息泄露的案列不在少数，加强信息安全措施是完善网络信息管理过程中不可避免的一环。

` `(2)资源不能充分共享

资源共享是网络的一大特点，没有共享就没有社交，网络也就失去了他应有的魅力，如果能够实现用户信息共享，无疑对于用户的发展存在不可或缺的帮助。

(3)现有系统可扩展性不高。

如今科学技术发展飞速，随着而来的就是技术更新，那势必会给软件更新带来挑战，因此，系统必须具备良好的开放性和可扩充性，为了不落后于时代，这是必备特色之一。

基于上述分析，在线CSGO赛事管理系统应该切合实际，做到确实有效，集体表现为：一是系统能够整理并集合归类用户信息，防止用户信息混乱，难以整理；二是系统要安全稳定，不能泄露用户信息，造成隐私泄露，不仅伤害用户利益更是对经营者名誉的损毁；三是系统要具有良好的开放性，不仅要方便定期的维护维修，更要方便及时增加新功能，保证先进的时代契合性。经过详细的讨论论证，确定系统的总体要求。
## 3.4 性能需求分析
对系统的性能，从（功能、运行、界面、安全）等方面进行，下面我们逐一进行分析；

\1. 系统的功能是否完整进行分析：系统的功能，能对应设计出原始代码和算法，以表格同文字的形式进行详细介绍个人信息保证功能完整；

\2. 系统的运行是否通畅进行分析：系统的每个功能都有编写数据的关系和应对的代码，通过需求分析和可行性分析进行分析和显示系统的物理数据，保证其进行通畅；

\3. 系统的界面设计进行分析：对系统中的软件进行处理与分析的方式是由不同代码来进行的；从而使界面容易操作。

\4. 系统的安全性进行分析：这样才可以每个角色的不同对应的信息也就不同，在登录系统务必使用自己的账号，密码登录，账号与密码错误自然就登录失败了。登录成功可以对自己的信息进行操作，不能对别人的账号的信息进行查看等操作，这样自然保证系统的安全性。
## 3.5系统流程分析
### 3.5.1操作流程
系统登录流程图，如图所示：

![](/md/blog.011.png)

图3-1登录流程图
### 3.5.2添加信息流程
添加信息流程图，如图所示：

![](/md/blog.012.png)

图3-2添加信息流程图
### 3.5.3删除信息流程
删除信息流程图，如图所示：

![](/md/blog.013.png)

图3-3删除信息流程图

# 4系统总体设计
## 4.1系统结构
CSGO赛事管理系统，它是一个由人、电脑及其他组件构成的，一种能够收集、存储、加工、传送信息的系统。该系统可以帮助决策者找出当前急需解决的问题，然后将信息快速的反馈，使管理人员能够以最快的时间知道目前的现状，进行更进一步的计划。

当前MIS系统结构目前存在两种较为流行的结构:C/S和B/S两种。

C/S结构的系统：C/S结构就是客户机服务器结构，它可以法派任务到Client端和Server端来进行，充分利用两端硬件环境的优势，来降低系统的通讯的花费。客户端主要作用是处理人机交互，执行客户端应用程序，收集数据以及向服务器发送任务请求。服务器基本作用是执行后台程序，它主要对客户机的请求申请进行反馈，除此之外，它的作用还包括：数据库存储系统的共享管理、通讯管理、文件管理等等。

B/S结构的系统：这种网络结构简化了客户端，并把系统功能实现的中心集中到服务器上，在这种模式中，只需要一个浏览器就可以了。这种结构将很多的工作交于WEB服务器，只通过浏览器请求WEB服务，随后根据请求返回信息。

通常在只在企业网内部使用，采用C/S。而使用不仅限于内网的情况下使用B/S。考虑到本管理系统的一系列需求，所以，该系统开发使用B/S结构开发。其主要功能结构如下图所示。

![](/md/blog.014.png)

图4-1 系统总体功能结构图
## 4.2数据库设计
数据库设计是指为系统提供最优化的数据库模式，使得应用程序能够有效的存储数据，满足用户的各类需求。
### 4.2.1 数据库概念结构设计
概念结构设计是根据用户需求形成的。用最常的E-R方法描述数据模型进行数据库的概念设计，首先设计局部的E-R模式，最后各局部ER模式综合成一个全局模式。然后再把概念模式转换成逻辑模式。将概念设计从设计过程中独立开来，设计复杂程度降低，不受特定DBMS的限制。

1.所有实体和属性的定义如下所示。

参赛战队管理属性图如下图4-2所示。

![](/md/blog.015.png)

图4-2参赛战队管理实体属性图

赛事信息管理实体属性图，如图4-3所示：

![](/md/blog.016.png)图4-3赛事信息管理实体属性图
### 4.2.2数据库逻辑结构设计
根据E-R得出数据库包涵了以下几张数据表来实现了对数据库的存储、调用。以下分别列出数据表的每个字段名、数据类型、主外键及备注。

表4-1：申请合作

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|saishimingcheng|varchar|200|赛事名称|||
|saishitubiao|varchar|200|赛事图标|||
|jubandi|varchar|200|举办地|||
|gongsizhanghao|varchar|200|公司账号|||
|gongsimingcheng|varchar|200|公司名称|||
|cehuashu|varchar|200|策划书|||
|hetong|varchar|200|合同|||
|sfsh|varchar|200|是否审核||否|
|shhf|longtext|4294967295|审核回复|||

表4-2：赛事信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|saishimingcheng|varchar|200|赛事名称|||
|saishitubiao|varchar|200|赛事图标|||
|saishijieduan|varchar|200|赛事阶段|||
|jubandi|varchar|200|举办地|||
|kaishiriqi|date||开始日期|||
|jieshuriqi|date||结束日期|||
|baomingzhuangtai|varchar|200|报名状态|||
|clicktime|datetime||最近点击时间|||

表4-3：赛事报名

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|saishimingcheng|varchar|200|赛事名称|||
|saishitubiao|varchar|200|赛事图标|||
|jubandi|varchar|200|举办地|||
|cansaizhanghao|varchar|200|参赛账号|||
|zhanduimingcheng|varchar|200|战队名称|||
|baomingriqi|date||报名日期|||
|sfsh|varchar|200|是否审核||否|
|shhf|longtext|4294967295|审核回复|||

表4-4：赛事通知

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|introduction|longtext|4294967295|简介|||
|picture|varchar|200|图片|||
|content|longtext|4294967295|内容|||

表4-5：合作方

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|gongsizhanghao|varchar|200|公司账号|||
|mima|varchar|200|密码|||
|gongsimingcheng|varchar|200|公司名称|||
|yingyezhizhao|varchar|200|营业执照|||
|fuzeren|varchar|200|负责人|||
|shoujihaoma|varchar|200|手机号码|||
|youxiang|varchar|200|邮箱|||
|suoshuguojia|varchar|200|所属国家|||
|sfsh|varchar|200|是否审核||否|
|shhf|longtext|4294967295|审核回复|||

表4-6：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||

表4-7：参赛战队

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|cansaizhanghao|varchar|200|参赛账号|||
|mima|varchar|200|密码|||
|zhanduimingcheng|varchar|200|战队名称|||
|touxiang|varchar|200|头像|||
|lianxifangshi|varchar|200|联系方式|||
|youxiang|varchar|200|邮箱|||
|suoshuguojia|varchar|200|所属国家|||

表4-8：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|

表4-9：token表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|userid|bigint||用户id|||
|username|varchar|100|用户名|||
|tablename|varchar|100|表名|||
|role|varchar|100|角色|||
|token|varchar|200|密码|||
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|
|expiratedtime|timestamp||过期时间||CURRENT\_TIMESTAMP|

# 5 系统详细设计
## 5.1系统功能模块
CSGO赛事管理系统，在系统首页可以查看首页，赛事信息，赛事通知，个人中心，后台管理等内容，并进行详细操作；如图5-1所示。

![](/md/blog.017.png)

图5-1系统首页界面图

赛事信息，在赛事信息页面可以查看赛事名称，赛事图标，举办地，开始日期，结束日期，报名状态等内容；如图5-2所示。

![](/md/blog.018.png)

图5-2赛事信息界面图

赛事通知，在赛事通知页面通过填写标题信息，并进行搜索操作，如图5-3所示。

![](/md/blog.019.png)

图5-3赛事通知界面图

参赛战队注册，在注册页面通过填写参赛账号，密码，确认密码，战队名称，联系方式，邮箱，所属国家等内容进行注册；如图5-4所示。

![](/md/blog.020.png)

图5-4个参赛战队注册界面图
## 5.2管理员功能模块
管理员登录，管理员进入系统前在登录页面根据要求填写用户名和密码，选择角色等信息，点击登录进行登录操作，如图5-5所示。

![](/md/blog.021.png)

图5-5管理员登录界面图

管理员登录系统后，可以对首页，个人中心，参赛战队管理，合作方管理，赛事信息管理，申请合作管理，赛事报名管理，系统管理等功能进行相应的操作管理，如图5-6所示。

![](/md/blog.022.png)

图5-6管理员功能界面图

参赛战队管理，在参赛战队管理页面可以对索引，参赛账号，战队名称，头像，联系方式，邮箱，所属国家等内容进行修改和删除等操作，如图5-7所示。

![](/md/blog.023.png)

图5-7参赛战队管理界面图

合作方管理，在合作方页面可以对索引，公司账号，公司名称，营业执照，负责人，手机号码，邮箱，所属国家，审核回复，审核状态，审核等内容进行详情，修改和删除等操作，如图5-8所示。

![](/md/blog.024.png)

图5-8合作方管理界面图

赛事信息管理，在赛事信息管理页面可以对索引，赛事名称，赛事图标，赛事阶段，举办地，开始日期，结束日期，报名状态等内容进行详情，修改和删除等操作，如图5-9所示。

![](/md/blog.025.png)

图5-9赛事信息管理界面图

申请合作管理，在申请合作页面可以对索引，赛事名称，赛事图标，举办地，公司账号，公司名称，策划书，合同，审核回复，审核状态，审核内容进行详情，修改和删除等操作；如图5-10所示。

![](/md/blog.022.png)

图5-10申请合作管理界面图

赛事报名管理，在赛事报名页面可以对索引，赛事名称，赛事图标，举办地，赛事账号，战队名称，报名日期，审核回复，审核状态，审核等内容进行详情，修改和删除等操作；如图5-11所示。

![](/md/blog.026.png)

图5-11赛事报名管理界面图

系统管理，在赛事通知页面可以对索引，标题，图片等内容进行详情，修改和删除等操作；还可以对轮播图管理进行详细操作；如图5-12所示。

![](/md/blog.027.png)

图5-12系统管理界面图

## 5.3参赛战队功能模块
参赛战队登录系统后，可以对首页，个人中心，赛事信息管理，赛事报名管理等功能进行相应的操作管理，如图5-13所示。

![](/md/blog.028.png)

图5-13参赛战队功能界面图
## 5.4合作方功能模块
合作方登录系统后，可以对首页，个人中心，赛事信息管理，申请合作管理等功能进行相应的操作管理，如图5-14所示。

![](/md/blog.029.png)

图5-14合作方功能界面图


#

# 系统










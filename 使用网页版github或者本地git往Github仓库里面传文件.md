## 一.新仓库创建流程：
1.项目负责人根据以下要求起好新仓库的名字：
Dataset__project name （数据集相关/数据集处理代码等）; 
Research__project name（团队内发表论文相关的代码） ; 
Engineering__project name（团队内工程开发相关的代码）；
Survey__project name（调研相关的论文或开源项目汇总等） ; 
Experience __project name （实践经验记录，CSDN等搬运） ;
project name和前面的类别之间是两个英文字符下划线。
例如仓库内容是关于发表论文的相关资料和代码的，名字就可以起为Research__HPAGA，其中Research是类别，HPAGA是project name.
2.项目负责人联系管理员，把自己的github账户邮箱，仓库名，发送给管理员。管理员会创建一个新的私仓库，并赋予项目负责人该仓库的操作权限，项目负责人注意查收自己邮箱，接受权限邀请。
## 二.新仓库管理要求:
1.公开要求：新仓库最开始均为私有仓库。如需公开，请将所有项目文件上传完毕并与老师确认后，联系仓库管理员公开。
2.项目负责人自行上传项目相关文件，具体上传方法请见下文。
3.项目负责人负责写好readme文件，注意readme文件为markdown格式。如果不知道markdown格式的文件怎么写，我推荐大家使用先使用语雀进行文档编辑（和正常用word进行编辑差不多），然后将文档以.md格式导出，这样就可以获得markdown格式的文件了。
4.仓库中的文件总大小不超过200MB,大文件放链接，不要直接放文件。大文件不利于上传和下载，同时别的访客克隆这个仓库的时候也不好操作。
## 三.Github仓库文件操作办法:
项目负责人在自己的邮箱接受权限邀请后，大家可以在自己的仓库列表中看到管理员创建的新仓库。仓库文件操作有两种方法，一种是直接通过网页登录github账户，通过网页版GitHub直接操作。另外一种是通过本地电脑下载git，通过git命令行工具进行操作。
首先访问github.com,登录自己的账号，大家就会进入到这个界面
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717571330661-3a95d565-bbf8-452e-b2c6-4ba0a0e4bf7a.png#averageHue=%23ba9f75&clientId=ud8c33ae9-b8a7-4&from=paste&height=926&id=HZwhQ&originHeight=926&originWidth=1898&originalType=binary&ratio=1&rotation=0&showTitle=false&size=341708&status=done&style=none&taskId=u44af80f2-f9e6-4c40-9c28-04f1bec2276&title=&width=1898)
然后点击右上角自己的头像，再点击Your respositories进入属于自己的仓库列表。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717571584584-eacde916-7232-40dc-b6c2-0b75dfe7807f.png#averageHue=%23ba9f75&clientId=ud8c33ae9-b8a7-4&from=paste&height=926&id=iwcff&originHeight=926&originWidth=1898&originalType=binary&ratio=1&rotation=0&showTitle=false&size=342582&status=done&style=none&taskId=u74bdb278-3645-46ba-97f2-8c1d0a68554&title=&width=1898)
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717572062156-42a14793-8c40-487d-bb62-eaf39dadbb4d.png#averageHue=%23dadde0&clientId=ud8c33ae9-b8a7-4&from=paste&height=926&id=vnz2p&originHeight=926&originWidth=1908&originalType=binary&ratio=1&rotation=0&showTitle=false&size=334793&status=done&style=none&taskId=ud6f8be77-31ab-42e8-9bb5-d92dc45b839&title=&width=1908)
完成上面两步大家就会进入到自己的仓库列表。大家选择自己要传文件的仓库就可以了。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717637995703-60ca5937-37b9-49ec-a0ed-0cce40014b01.png#averageHue=%23fefdfd&clientId=u7129cc1e-774e-4&from=paste&height=917&id=ue0d22ad0&originHeight=917&originWidth=1918&originalType=binary&ratio=1&rotation=0&showTitle=false&size=129150&status=done&style=none&taskId=u9e7ae053-de92-43a9-86f4-dd1ff65f7a6&title=&width=1918)
### 第一种：通过网页版github进行文件操作
#### 文件上传
通过网页版Github提交，他限制提交的总文件大小不超过25Mb,同时限制文件数量。如果大家的文件比较小，数量比较少，推荐使用这种方式。
本节接下来以First_learing这个仓库为例，展示如何通过网页版传文件。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717572418972-d8ee36e3-f065-4a81-b4dc-4eb2d70814ae.png#averageHue=%23fefcfc&clientId=ud8c33ae9-b8a7-4&from=paste&height=921&id=u30a2e203&originHeight=921&originWidth=1889&originalType=binary&ratio=1&rotation=0&showTitle=false&size=341854&status=done&style=none&taskId=uec175839-98ee-4fc8-af14-1b475159707&title=&width=1889)
点击上面图片中红色框中的仓库名，进入仓库，大家会来到下面这个界面（在这个界面注意要选择code这个选项卡）
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717572881075-eeb0693d-6399-4740-8ccc-58bfd8a1e82e.png#averageHue=%23fefefe&clientId=ud8c33ae9-b8a7-4&from=paste&height=898&id=u607aa2cc&originHeight=898&originWidth=1913&originalType=binary&ratio=1&rotation=0&showTitle=false&size=259983&status=done&style=none&taskId=u78194e21-2587-4752-8762-32b0ecce13e&title=&width=1913)
然后大家点击Add files ,选择upload files上传文件。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717573036134-ad79567f-e664-4a7b-a40b-9afc2264644b.png#averageHue=%23fefefe&clientId=ud8c33ae9-b8a7-4&from=paste&height=926&id=uc71ca9f1&originHeight=926&originWidth=1910&originalType=binary&ratio=1&rotation=0&showTitle=false&size=93952&status=done&style=none&taskId=u26662c40-04dd-46e0-8066-1a87de669ec&title=&width=1910)
然后大家点击屏幕中间的choose your files上传自己的文件，然后点击左下角的Commit changes提交文件就可以了。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717573229796-0d745fab-5e4f-44f6-9310-f640e2931b28.png#averageHue=%23fefefd&clientId=ud8c33ae9-b8a7-4&from=paste&height=738&id=y1gKt&originHeight=923&originWidth=1891&originalType=binary&ratio=1&rotation=0&showTitle=false&size=66097&status=done&style=none&taskId=u622fd0d4-dcd2-43e9-8250-08e4c16adba&title=&width=1512.8)
下图，我提交了一个名为Test_LH.txt的文件，提交成功后，大家就可以看到自己提交的新文件了。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717573451907-dc1615e2-ec0e-4906-a3db-fc1d6e7a099b.png#averageHue=%23fefdfd&clientId=ud8c33ae9-b8a7-4&from=paste&height=732&id=u6d869bc0&originHeight=915&originWidth=1905&originalType=binary&ratio=1&rotation=0&showTitle=false&size=88286&status=done&style=none&taskId=u4a33cbbb-d2f8-4384-9fcc-4292bada2e8&title=&width=1524)
#### 文件更改
我们以修改自己仓库的Test_LH.txt文件为例，展示如何通过网页版Github修改仓库内文件内容。假设我们要修改下图中这个Test_LH.txt文件，我们首先点击进入这个文件
![](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717573451907-dc1615e2-ec0e-4906-a3db-fc1d6e7a099b.png?x-oss-process=image%2Fformat%2Cwebp#averageHue=%23fefdfd&from=url&id=fGwwE&originHeight=915&originWidth=1905&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717573810913-603dae8d-b8e2-415d-81cf-4f1ac0283874.png#averageHue=%23fefefe&clientId=ud8c33ae9-b8a7-4&from=paste&height=735&id=ube9b9397&originHeight=919&originWidth=1899&originalType=binary&ratio=1&rotation=0&showTitle=false&size=52564&status=done&style=none&taskId=u224b3a86-c7c1-4024-a8f5-ffc1fae73e3&title=&width=1519.2)
然后我们点击图片右侧这个类似于笔的按钮（Edit this file），就可以更改这个文件的内容了。![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717574051096-e94b9f2c-822d-4a2a-8ac3-2f831c36fdb2.png#averageHue=%23fefefe&clientId=ud8c33ae9-b8a7-4&from=paste&height=740&id=ua88cc9c2&originHeight=925&originWidth=1910&originalType=binary&ratio=1&rotation=0&showTitle=false&size=61634&status=done&style=none&taskId=uf5d1cb9e-de22-49e3-8038-9322e08854b&title=&width=1528)
大家更改完文件内容，点击右上角的绿色按钮（Commit changes）就可以提交这个更改了。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717576509410-b97ca3ae-5439-4fbb-9f31-6612a5826291.png#averageHue=%23fefefe&clientId=ud8c33ae9-b8a7-4&from=paste&height=734&id=ua5572dd2&originHeight=918&originWidth=1886&originalType=binary&ratio=1&rotation=0&showTitle=false&size=67236&status=done&style=none&taskId=u2af8e1da-cec1-4e2c-abc0-6c8910b753b&title=&width=1508.8)
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717576560618-f738796b-2d1f-4466-951a-accff2af2155.png#averageHue=%23e3e6e9&clientId=ud8c33ae9-b8a7-4&from=paste&height=735&id=u0d484617&originHeight=919&originWidth=1906&originalType=binary&ratio=1&rotation=0&showTitle=false&size=94903&status=done&style=none&taskId=uc9fda2b6-c52d-46f0-bb83-21224deafb5&title=&width=1524.8)
至此，文件就完成了更改。
#### 文件删除
我们以删除Test_LH.txt文件为例，展示如何通过网页版Github删除仓库内文件。假设我们要删除下图中这个Test_LH.txt文件，我们首先点击进入这个文件
![](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717573451907-dc1615e2-ec0e-4906-a3db-fc1d6e7a099b.png?x-oss-process=image%2Fformat%2Cwebp#averageHue=%23fefdfd&from=url&id=XeL8f&originHeight=915&originWidth=1905&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717577040694-1dfa0639-dedd-4676-9b5c-6624c20bab31.png#averageHue=%23fefefe&clientId=ud8c33ae9-b8a7-4&from=paste&height=734&id=u47fe003c&originHeight=917&originWidth=1892&originalType=binary&ratio=1&rotation=0&showTitle=false&size=53476&status=done&style=none&taskId=uf415b89a-422f-4bf3-9012-8a473de8ff8&title=&width=1513.6)
然后我们点击图片右上角这个类似于省略号的按钮（More file actions）
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717577063355-4fe8ffad-59e2-4fb5-bfb3-c930b3bbf8b1.png#averageHue=%23fefefe&clientId=ud8c33ae9-b8a7-4&from=paste&height=734&id=u84a19119&originHeight=917&originWidth=1892&originalType=binary&ratio=1&rotation=0&showTitle=false&size=64735&status=done&style=none&taskId=u90ee8c61-0f6e-405f-a749-927b312ca30&title=&width=1513.6)
选择Delete files
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717577162026-f3e3612f-f3c0-46d4-9dc5-8797b441d2f4.png#averageHue=%23fefefe&clientId=ud8c33ae9-b8a7-4&from=paste&height=734&id=u7d5ec755&originHeight=917&originWidth=1901&originalType=binary&ratio=1&rotation=0&showTitle=false&size=78920&status=done&style=none&taskId=ufe9e1e3e-daad-4a39-9079-381febb9195&title=&width=1520.8)
然后点击右上角的绿色按钮（Commit changes）,就可以删除这个文件了。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717577247344-b1d8f170-f1d5-40d8-8418-c035dc64d2d9.png#averageHue=%23fefefe&clientId=ud8c33ae9-b8a7-4&from=paste&height=730&id=u5216a235&originHeight=913&originWidth=1889&originalType=binary&ratio=1&rotation=0&showTitle=false&size=54818&status=done&style=none&taskId=u7bd6cc70-c1da-4dfa-9178-04c8eb21310&title=&width=1511.2)
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717577372470-783b2d69-4ab0-464d-9594-7cdac96ae2f2.png#averageHue=%23e4e7e9&clientId=ud8c33ae9-b8a7-4&from=paste&height=742&id=XPOD3&originHeight=927&originWidth=1920&originalType=binary&ratio=1&rotation=0&showTitle=false&size=80141&status=done&style=none&taskId=ufffa83e8-5f1a-472d-ae26-58512527111&title=&width=1536)
至此我们就删除了Test_LH.txt这个文件。
### 第二种：通过本地git进行文件操作
使用本地的git上传也有限制，单个文件大小不能超过100Mb。
#### git的下载和安装
在本地安装Git后，可以直接使用命令语句来进行项目的上传与克隆，还是非常方便的。下面展示的是在Windows 64 位系统下的下载和安装。以下步骤可能根据安装包的版本和操作系统的版本不同略有差异。
##### 一、下载
1、首先在浏览器中搜索Git，进入到Git的官方下载界面，[Git官网链接](https://git-scm.com/)
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717583109512-e923de2e-6d62-42d3-8943-4ee73898c41e.png#averageHue=%23eae9e0&clientId=ud8c33ae9-b8a7-4&from=paste&height=974&id=u99c90d30&originHeight=974&originWidth=1929&originalType=binary&ratio=1&rotation=0&showTitle=false&size=579209&status=done&style=none&taskId=u169a5110-7487-4fde-a54e-6f2eafa8365&title=&width=1929)
2、点击上图红色框中的Downloads
进入下载界面，选择自己需要平台的文件
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717583199075-6d4a0ceb-2b67-4cd4-9a92-2949a6d0a9b3.png#averageHue=%23efeee7&clientId=ud8c33ae9-b8a7-4&from=paste&height=920&id=u6be25a15&originHeight=920&originWidth=1912&originalType=binary&ratio=1&rotation=0&showTitle=false&size=441451&status=done&style=none&taskId=ud509394a-4980-4c78-8e92-468b96131ba&title=&width=1912)
3、下载标准版就可以
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717583303432-b551fffd-1791-4961-a47c-4c74a96e299c.png#averageHue=%23f2f1eb&clientId=ud8c33ae9-b8a7-4&from=paste&height=930&id=u26dcf36a&originHeight=930&originWidth=1920&originalType=binary&ratio=1&rotation=0&showTitle=false&size=386473&status=done&style=none&taskId=u8f65b55c-a711-472e-8321-f4967f245a8&title=&width=1920)
##### 二：安装
**1、选择自己常用的位置**
因为Git还需要配置一些东西，最好这个安装地址容易找。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717583470976-4276f2fc-4b23-4f25-81d6-028202c99324.png#averageHue=%23f0efee&clientId=ud8c33ae9-b8a7-4&from=paste&height=392&id=u89d5fcfa&originHeight=392&originWidth=499&originalType=binary&ratio=1&rotation=0&showTitle=false&size=15570&status=done&style=none&taskId=u1514437a-2dbf-4b09-9edb-405dc5e706f&title=&width=499)
2、这个内容按照下图选择就好，然后点击Next
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717583621455-e0c40045-3672-4dcd-b53d-bb320f14548e.png#averageHue=%23f1efed&clientId=ud8c33ae9-b8a7-4&from=paste&height=391&id=u7de96366&originHeight=391&originWidth=502&originalType=binary&ratio=1&rotation=0&showTitle=false&size=23127&status=done&style=none&taskId=u26699d42-3cdc-4752-b176-673b7bd96e6&title=&width=502)
3.点击Next
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717583661233-43a98ddf-ef7c-4542-bea6-7a8eb081d504.png#averageHue=%23efefee&clientId=ud8c33ae9-b8a7-4&from=paste&height=392&id=ud67b7c4c&originHeight=392&originWidth=500&originalType=binary&ratio=1&rotation=0&showTitle=false&size=14803&status=done&style=none&taskId=ud92b8bab-e538-42c1-b0a5-c5fc2629ffb&title=&width=500)
4.默认是Vim文本编辑器就好，点击Next
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717583725895-9050e09b-d747-40e9-ad68-bb74b5c3fb62.png#averageHue=%23edebea&clientId=ud8c33ae9-b8a7-4&from=paste&height=391&id=ueee34b30&originHeight=391&originWidth=504&originalType=binary&ratio=1&rotation=0&showTitle=false&size=21429&status=done&style=none&taskId=u64055deb-1f8f-41ba-a238-dabb48fc440&title=&width=504)
5.不用动，默认选择就可以，点击Next
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717583764529-924a5c70-9f48-42bf-b37f-a8923794d6df.png#averageHue=%23edebe9&clientId=ud8c33ae9-b8a7-4&from=paste&height=396&id=u4c20543c&originHeight=396&originWidth=500&originalType=binary&ratio=1&rotation=0&showTitle=false&size=21546&status=done&style=none&taskId=udf12d48a-4e06-4c39-b81d-765e6dad34e&title=&width=500)
6.不用动，默认选择就可以，点击Next
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717583831341-5e2589a5-ef1e-4adf-b215-a91b2d0764ce.png#averageHue=%23ece9e6&clientId=ud8c33ae9-b8a7-4&from=paste&height=388&id=u0a2e01b3&originHeight=388&originWidth=494&originalType=binary&ratio=1&rotation=0&showTitle=false&size=27960&status=done&style=none&taskId=u1ed29af7-e48c-4cce-b157-2ba290ec376&title=&width=494)
7.不用动，默认选择就可以，点击Next
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717583871555-0b625635-f82e-4a01-8537-a5c5bb7ce634.png#averageHue=%23eeedec&clientId=ud8c33ae9-b8a7-4&from=paste&height=393&id=ue6eb6eb4&originHeight=393&originWidth=500&originalType=binary&ratio=1&rotation=0&showTitle=false&size=16251&status=done&style=none&taskId=u3ddaa612-3d5b-412d-a022-5b6839905d2&title=&width=500)
8.不用动，默认选择就可以，点击Next
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717583967131-29cd4a48-5888-421f-8d97-c2026aadaea9.png#averageHue=%23ecebea&clientId=ud8c33ae9-b8a7-4&from=paste&height=401&id=uf0a7848d&originHeight=401&originWidth=510&originalType=binary&ratio=1&rotation=0&showTitle=false&size=19337&status=done&style=none&taskId=udd0c1b3a-14ea-425e-9e26-708e639a772&title=&width=510)
9.如果是Windows系统就不用动，默认选择就可以，点击Next。别的操作系统大家自行csdn吧
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717584016715-83afc094-13d5-4fc2-aeab-880fe55776b8.png#averageHue=%23ebe8e6&clientId=ud8c33ae9-b8a7-4&from=paste&height=392&id=ue10347b4&originHeight=392&originWidth=500&originalType=binary&ratio=1&rotation=0&showTitle=false&size=25334&status=done&style=none&taskId=u88ba7e4c-5806-4665-a5c0-e019277be03&title=&width=500)
10、不用动，默认选择就可以，点击Next
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717584097390-8ed825a9-e654-4c22-afb3-d29151892708.png#averageHue=%23eae8e6&clientId=ud8c33ae9-b8a7-4&from=paste&height=400&id=ub8c3249b&originHeight=400&originWidth=507&originalType=binary&ratio=1&rotation=0&showTitle=false&size=25663&status=done&style=none&taskId=ucc610518-d440-45a7-9634-cc5d9944af7&title=&width=507)
11.不用动，默认选择就可以，点击Next
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717584162274-fba760f1-6e86-40c9-9675-bd7f50149067.png#averageHue=%23edeceb&clientId=ud8c33ae9-b8a7-4&from=paste&height=390&id=u5ec3c0fc&originHeight=390&originWidth=499&originalType=binary&ratio=1&rotation=0&showTitle=false&size=18987&status=done&style=none&taskId=u6945e701-278b-44e5-a744-62b3123219e&title=&width=499)
12.就是得到管理凭证，比如登录的账号名、密码等,不用动，默认选择就可以，点击Next
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717584215209-ca8ae2dd-f732-46a6-886d-1a5d71d66275.png#averageHue=%23efeeed&clientId=ud8c33ae9-b8a7-4&from=paste&height=392&id=ua775928e&originHeight=392&originWidth=502&originalType=binary&ratio=1&rotation=0&showTitle=false&size=14981&status=done&style=none&taskId=ufd2a72a8-c858-47f5-9c6b-56d2ee6f0e7&title=&width=502)
13.不用动，默认选择就可以，点击Next
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717584278565-d7c72fe8-0ca8-47bf-b42b-25fc25c2bf70.png#averageHue=%23edeceb&clientId=ud8c33ae9-b8a7-4&from=paste&height=395&id=uefbacb36&originHeight=395&originWidth=499&originalType=binary&ratio=1&rotation=0&showTitle=false&size=17677&status=done&style=none&taskId=u795b6750-7e8e-41bc-b85b-75331250513&title=&width=499)
14.都是新的功能，基础的文件提交用不上，所以都不用选，如果有需要可以选，然后点击Install
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717584374742-4e69e4e8-8979-400b-8ced-1c325d88ab19.png#averageHue=%23eeeceb&clientId=ud8c33ae9-b8a7-4&from=paste&height=388&id=u6fc1bfcf&originHeight=388&originWidth=491&originalType=binary&ratio=1&rotation=0&showTitle=false&size=20206&status=done&style=none&taskId=ub07ce22d-262e-42ef-a56e-523817bba6f&title=&width=491)
15.在桌面空白处，鼠标右击，看到这个程序，就说明安装成功了。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717584579359-267e6c05-149a-4f22-8ea9-f565201afb12.png#averageHue=%23e3e0e0&clientId=ud8c33ae9-b8a7-4&from=paste&height=477&id=uf4bd9e24&originHeight=477&originWidth=325&originalType=binary&ratio=1&rotation=0&showTitle=false&size=53918&status=done&style=none&taskId=u5e9e6907-14a7-4f49-a469-c9edd524af5&title=&width=325)
##### 三、设置git的环境变量
通常这部分系统会自动添加进去，为了以防万一，大家还是查看一下。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717585304746-1bbf6de8-1f1d-493a-90b7-879368ef6db7.png#averageHue=%23f2f1f0&clientId=ud8c33ae9-b8a7-4&from=paste&height=661&id=u8f660e4f&originHeight=661&originWidth=611&originalType=binary&ratio=1&rotation=0&showTitle=false&size=35235&status=done&style=none&taskId=u4bba9bb4-fcbb-482e-8abf-e0adfa715fe&title=&width=611)
看系统变量这个Path这个变量，双击Path，看到自己刚才安装的路径里面有这个，就说明已经自动配置好了
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717585387112-93cde1e5-7213-49bb-a79e-ae9ec927d7c2.png#averageHue=%23f4f3f2&clientId=ud8c33ae9-b8a7-4&from=paste&height=209&id=ua80dfe18&originHeight=209&originWidth=489&originalType=binary&ratio=1&rotation=0&showTitle=false&size=7479&status=done&style=none&taskId=u9971f702-c2c6-407c-8a43-5d9efde0842&title=&width=489)
配置完成，把鼠标放在桌面空白位置，右击打开git bash 是下面这样的。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717585583786-64b34a22-f73a-498c-bf38-5129e0f6fe8a.png#averageHue=%231a1a1a&clientId=ud8c33ae9-b8a7-4&from=paste&height=371&id=u8f7c7ccf&originHeight=371&originWidth=580&originalType=binary&ratio=1&rotation=0&showTitle=false&size=7682&status=done&style=none&taskId=u4e5a8076-e115-43e6-80a2-ba6b93a72bf&title=&width=580)
至此，git就安装好了。
#### git的使用
git的使用视频讲解，大家可以看B站上面的这个教程[一小时Git](https://www.bilibili.com/video/BV1HM411377j/?p=12&spm_id_from=333.1007.top_right_bar_window_history.content.click)
使用git传文件的原理大致就是，首先将云端的仓库克隆到本地，让后往这个本地仓库直接添加文件，再把这个更改后的本地仓库推送到云端。大家尽量开着梯子，这样网速会快一点。下面是详细的步骤，大家一步一步跟着走就可以。下面我将以往private-rpo这仓库中提交文件为例。
1.首先，我们在本地创建一个文件夹Test。右击文件夹，使用Open Git  Bash here打开。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717586325930-0d93c2ca-1862-44a5-b96b-79af8b0bc89e.png#averageHue=%23c0bfbe&clientId=ud8c33ae9-b8a7-4&from=paste&height=551&id=uccddd7aa&originHeight=551&originWidth=248&originalType=binary&ratio=1&rotation=0&showTitle=false&size=99847&status=done&style=none&taskId=u8e8498b1-57c4-4a56-ad69-e7e0216aa9d&title=&width=248)
然后就是这个界面。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717586552022-9b75e58f-f666-4c7e-b651-7a107d16cbad.png#averageHue=%231a1a1a&clientId=ud8c33ae9-b8a7-4&from=paste&height=371&id=u702063e4&originHeight=371&originWidth=586&originalType=binary&ratio=1&rotation=0&showTitle=false&size=13351&status=done&style=none&taskId=u7c024a20-88b1-4aec-b5cf-89a76c977fd&title=&width=586)
2.打开自己GitHub网站上面要传文件的仓库，按照下图1234步骤，复制自己仓库的HTTPS地址。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717586718772-355014c6-47fe-4500-a81a-a76dc7b5c215.png#averageHue=%23e3bd8b&clientId=ud8c33ae9-b8a7-4&from=paste&height=893&id=uc4edd122&originHeight=893&originWidth=1893&originalType=binary&ratio=1&rotation=0&showTitle=false&size=208374&status=done&style=none&taskId=u2d987b74-086a-43c2-b319-613b49143fc&title=&width=1893)
3.然后转到上面打开的小黑框输入下面的命令,后面的地址大家根据自己的创建的仓库地址填。大家在输入命令的时候不要用Ctrl+v和Ctrl+c。git小黑框粘贴的快捷键是shift+ins,复制的快捷键是Ctrl+ins.
```git
git clone https://github.com/BUCT-IUSRC/private-rpo.git
```
等待一会命令执行，如下图所示这样，仓库private-rpo就从云端克隆到我们本地这个Test文件夹里面了。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717587618587-12dff63d-3684-4b29-8636-51b3de914ef9.png#averageHue=%231e1d1c&clientId=ud8c33ae9-b8a7-4&from=paste&height=378&id=ucc984cf0&originHeight=378&originWidth=583&originalType=binary&ratio=1&rotation=0&showTitle=false&size=27645&status=done&style=none&taskId=u154fb1ba-df8c-4e01-b3dc-c1f93f9e8af&title=&width=583)
在Test文件夹里面就有这样一个名为private-rpo的仓库了
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717587672560-7a98019f-b8b7-4636-8871-c85c8fa0dd95.png#averageHue=%23fdfdfd&clientId=ud8c33ae9-b8a7-4&from=paste&height=673&id=uf3bd99ab&originHeight=673&originWidth=1406&originalType=binary&ratio=1&rotation=0&showTitle=false&size=38551&status=done&style=none&taskId=u5bde638b-b608-4b5a-b2d1-b933320a0b7&title=&width=1406)
这个private-rpo文件夹里面现在什么都没有，只有一个readme文件。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717587754690-e04c9ab4-4b81-4588-9a18-cb2625e654a5.png#averageHue=%23fdfdfc&clientId=ud8c33ae9-b8a7-4&from=paste&height=674&id=u642467d0&originHeight=674&originWidth=1409&originalType=binary&ratio=1&rotation=0&showTitle=false&size=43521&status=done&style=none&taskId=ueae433b9-7b1d-4e73-95a1-52d5bbffe1f&title=&width=1409)
大家在克隆过程可能会遇到下面几个问题：
a.解决办法，换个梯子重连一下。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717595397751-35cd1faa-41ae-4a26-b530-167cb10d640a.png#averageHue=%235f5d5c&clientId=ud8c33ae9-b8a7-4&from=paste&height=154&id=gML7C&originHeight=154&originWidth=956&originalType=binary&ratio=1&rotation=0&showTitle=false&size=65373&status=done&style=none&taskId=uf5a09a44-ffa0-400e-a7d3-8606b18d80a&title=&width=956)
b.解决办法：命令重新手动输入一下，参考链接[链接](https://blog.csdn.net/jiunian_2761/article/details/100005715?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522171759554916800186578545%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=171759554916800186578545&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-2-100005715-null-null.142^v100^control&utm_term=fatal%3A%20protocol%20httpsis%20not%20supported&spm=1018.2226.3001.4187)。
![be9fe340a5437dc1a4c7bcca9807620.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717595476460-983b0214-0358-492a-8bb0-7d91efa0fc69.png#averageHue=%23161412&clientId=ud8c33ae9-b8a7-4&from=paste&height=156&id=u700d7d45&originHeight=156&originWidth=673&originalType=binary&ratio=1&rotation=0&showTitle=false&size=12796&status=done&style=none&taskId=u5176e35a-d89b-46b7-9001-84d72eae368&title=&width=673)
c:这个问题![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717597842545-ef7b7307-3234-4e6a-aa3c-d0991e3c344f.png#averageHue=%230b0805&clientId=ud8c33ae9-b8a7-4&from=paste&height=38&id=uc107b7cf&originHeight=38&originWidth=753&originalType=binary&ratio=1&rotation=0&showTitle=false&size=4514&status=done&style=none&taskId=uf07b3362-0686-4cc1-9bf3-f57dea7596d&title=&width=753)
可以先执行下面的代码，然后打开梯子，再执行 git clone 
```git
git config --global --unset https.proxy
```
如果上面的解决方法都不好使，大家可以先ping github.com
如果ping github.com有反应，大家可以换个梯子，重新开一下小黑框试一下。
如果ping github.com没有反应，大家可以参考这个链接操作一下[无法Ping 通github.com解决办法](https://blog.csdn.net/Hacker_MAI/article/details/123270836)。
4.然后我们将所需要提交的文件放到上图这个private-rpob文件夹里面。下面这个Test_LH.txt就是我要提交的文件。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717587840622-229d5863-4da8-4ebf-ba88-f1fa3623417a.png#averageHue=%23fdfdfc&clientId=ud8c33ae9-b8a7-4&from=paste&height=670&id=u8016bb01&originHeight=670&originWidth=1403&originalType=binary&ratio=1&rotation=0&showTitle=false&size=44780&status=done&style=none&taskId=ud7851ab2-eb58-4e58-8100-0c5024875f2&title=&width=1403)
5.使用Open Git  Bash here 打开private-rpo这个文件夹，操作步骤同第1步，鼠标右键点击private-rpo文件夹，选Open Git  Bash here。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717588169652-86642481-1404-44bd-b301-4024e649d5cf.png#averageHue=%23eeeded&clientId=ud8c33ae9-b8a7-4&from=paste&height=662&id=u28ecb274&originHeight=662&originWidth=789&originalType=binary&ratio=1&rotation=0&showTitle=false&size=134876&status=done&style=none&taskId=u85855a0b-8ad8-43c2-82f2-2472a33610a&title=&width=789)
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717588078642-9c7c92a4-3271-46ea-ac83-6ab1d74ae0d0.png#averageHue=%231c1b1b&clientId=ud8c33ae9-b8a7-4&from=paste&height=372&id=u32bbbcad&originHeight=372&originWidth=582&originalType=binary&ratio=1&rotation=0&showTitle=false&size=7875&status=done&style=none&taskId=udf89737a-8335-430d-915b-50cb3072578&title=&width=582)
6.执行下面代码，这个代码的意思就是将刚才我们放到private-rpo这个仓库里面的全部新文件即Test_LH.txt放到暂存区。暂存区的概念大家可以看这个视频教程[一小时学Git](https://www.bilibili.com/video/BV1HM411377j?p=4&vd_source=b423b1ff18a4202f6ff579ab1b225792)，里面有详细解释。
```git
git add .
```
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717588290165-ee19fe9f-6d1f-46c5-a430-a7188801f942.png#averageHue=%231a1919&clientId=ud8c33ae9-b8a7-4&from=paste&height=369&id=u69572621&originHeight=369&originWidth=579&originalType=binary&ratio=1&rotation=0&showTitle=false&size=11566&status=done&style=none&taskId=u98cf860b-2f95-4795-b03f-b7f5f55ae1b&title=&width=579)
7.执行下面代码，这个代码的意思就是将刚才我们放到private-rpo这个仓库暂存区里面的新文件即Test_LH.txt，正式放到这个本地仓库。
```git
git commit -m "LH first_commit"
```
双引号里面的内容大家是可以随意编辑的，就是一个提交备注。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717588474379-940547b7-aadf-42f7-ac8d-b7beb9c477a5.png#averageHue=%231e1e1d&clientId=ud8c33ae9-b8a7-4&from=paste&height=374&id=u2d10b109&originHeight=374&originWidth=580&originalType=binary&ratio=1&rotation=0&showTitle=false&size=18019&status=done&style=none&taskId=u1f1cbb7e-5fec-405d-8ada-8002da90d76&title=&width=580)
7.执行下面代码，这个代码的意思就是将刚才我们本地这个private-rpo这个仓库推送到云端。

```git
git push
```
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717589056030-bf5c46ac-17f5-499c-ad7b-a5aeb7d5c0d6.png#averageHue=%230b0805&clientId=ud8c33ae9-b8a7-4&from=paste&height=149&id=u2392f8b9&originHeight=149&originWidth=440&originalType=binary&ratio=1&rotation=0&showTitle=false&size=12395&status=done&style=none&taskId=u18ff7a33-725a-4ad9-ad89-c0cdfaae305&title=&width=440)
这样文件就传到云端了。
如果大家使用git push 遇到了下面的问题。
![image.png](https://cdn.nlark.com/yuque/0/2024/png/38931856/1717589163718-0a2fdadc-d963-4378-b821-446475acc16c.png#averageHue=%230a0704&clientId=ud8c33ae9-b8a7-4&from=paste&height=66&id=HxdFc&originHeight=66&originWidth=568&originalType=binary&ratio=1&rotation=0&showTitle=false&size=7475&status=done&style=none&taskId=u96f3fd2f-8c58-44e9-a070-1b5b9c1b1ce&title=&width=568)
可以先执行下面的代码，然后再执行 git push
```git
git config --global --unset https.proxy
```
如果遇到了网络不好问题，大家可以试试换一个梯子，或者重新打开一下小黑框。
最后，大家注意，只要在本地对自己仓库的文件夹进行了操作，无论是删除还是添加文件。都需要执行一遍下面代码，这样本地仓库的更改才会同步到云端。
```git
git add .
git commit -m "注释"
git push
```



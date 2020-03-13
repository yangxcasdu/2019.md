以下是我最初开始使用Github记录下遇到的困惑和一些操作，如果你也在最开始使用GitHub遇到相同的困惑，也许可以给你一些启发，若发现不合理之处，欢迎指正。 

## 遇到的一些问题
* [注册账号](#第一个问题之注册账号)
* [页面浏览](#第二个问题之页面浏览)
* [申请加入](#第三个问题之申请加入)
* [新手任务](#第四个问题之新手任务)
* [会刊更新](#第五个问题之会刊更新)
* [探索更多](#第六个问题之探索更多)

### 第一个问题之注册账号

*  **问题阐述**：首先打开github官网申请注册一个github账号，输入申请账号之后网页会有一个邮箱验证确保你不是机器人。但是提交之后浏览器一直弹出红色报错，英文水平有限，磕磕绊绊读了大概是验证码有错误。

*  **解决办法**：[GitHub注册失败，卡在第一步](https://www.cnblogs.com/lgx211/p/10113028.html)，百度搜索发现有人和我遇到一样的问题，如果你也卡在这一步，其实是很正常的，因为每个人都是这样，Take it easy！以下是几个可以参考的做法：

   *  我的做法是尝试了换浏览器从IE换到Chrome，无果。关掉电脑自带防火墙，又试了一次，成功，运气太好了！
   *  [手机自带的Safari浏览器，填入相同的信息，不一会儿，验证信息收到了，注册成功！](https://www.cnblogs.com/lgx211/p/10113028.html)
   *  [使用 VPN 进行注册](https://blog.csdn.net/weixin_42423311/article/details/84503654)
   *  待补充...

   解决验证报错问题之后，进入注册剩余步骤，选择账户类型，完成问卷，验证邮箱。这些都比较顺畅。可参考[GitHub账户注册流程](https://blog.csdn.net/weixin_42423311/article/details/84503654)

*  **用时**:约1个小时。


### 第二个问题之页面浏览

*  **问题阐述**：进入页面之后发现纯英文阅读障碍，然而我还连界面和每一个标签的意义都不知道，更不要提克隆、创建分支、提交这些。

*  **解决办法**：继续百度[这些Github基本概念，你要知道](https://sspai.com/post/58120)，在这篇帖子中我大概知道GitHub是一个可以做什么的地方，这让我产生了兴趣，同时也了解了几个基本概念，以下摘录：
   *  ①Repository：译为仓库，你可以将它理解为文件夹，可以用来存放项目相关的文件。<br> 
      点击网页右上角的加号<br>![点击加号](https://github.com/yangxcasdu/2019.md/blob/master/Images/Newrepository.png)<br>
      可以新建或导入仓库。<br> 
      ![新建仓库](https://github.com/yangxcasdu/2019.md/blob/master/Images/createanddescription.jpg)<br>
      新建仓库时，你需要设置 仓库的名称、仓库的可见性，而对仓库的描述则不是必填项。勾选下方的使用README初始化仓库，则会在新建的仓库中生成一个README文件。 <br>
      创建好仓库后，你可以点击Create new file按钮来书写代码，也可以点击README.md右边的编辑按钮，来对仓库的说明文档进行编辑。<br>
      更加详尽的REANME.md文件操作将在下文介绍。<br>
   
   *  ②Watch : 关注你感兴趣的仓库或资源<br>
      Watch按钮，里面有4个选项，对应4种不同的通知权限。<br>
      ![四种通知权限](https://github.com/yangxcasdu/2019.md/blob/master/Images/watch4.png)<br>
      默认情况下，Watch是处于Not Watching状态的，如果你在Github上看到一个不错的仓库，想长期关注它的动态，那你可以选择切换到第二或第三种状态。 打开通知后，当仓库或资源更新后，你可以在账户的个人中心收到通知，如果你绑定了邮箱，那么你也可以通过邮件收到更新提醒。
   *  ③Star：点赞或收藏。点赞别人的项目。
   
   *  ④fork：复刻/派生。为了方便你 在他人分享的源码基础上，进行二次开发，创建不同的软件。 当你使用fork拷贝了他人的项目，你可以在仓库名称下方的小字，看到fork的来源。
   ![看到来源](https://github.com/yangxcasdu/2019.md/blob/master/Images/fork.png)<br>
   *  ⑤Issue：讨论区或留言区。 这个部分我用得比较多，而很多最开始该如何使用的问题也在上面提出，得到有经验的前辈的帮助很及时，这也是我在很迷惑的时候还能坚持的一个原因。
   *  ⑥Follow：添加好友。
   *  ⑦Comment：评论。

*  **用时**:浏览概念大概3o分钟左右，使用Repository和Issue这两个部分比较多，实际上fork是后来慢慢才学会，并不妨碍。

### 第三个问题之申请加入

*  **问题阐述**：我怎么才能加入CASDU账号成为电子版会刊编辑之一。
*  **解决办法**：按照论坛[【关于会刊电子版转载的通知】](http://bbs.casdu.cn/forum.php?mod=viewthread&tid=11669&extra=page%3D1)里的指示，给 banbooliu@gmail.com 发邮件，申请加入，申请通过后会有邮件回复。<br>
   ![收到邮件](https://github.com/yangxcasdu/2019.md/blob/master/Images/youjian.png)<br>
   这一步很顺畅，很快组织就通过邮件发送了邀请，通过了之后发现kuikan已经出现在自己的仓库。

*  **用时**：收到回复邮件很快，但是我看到已经是当天傍晚。

### 第四个问题之新手任务

*  **问题阐述**：我尝试做[新手任务](https://github.com/casdu/introduction)，但是有些难度。

*  **解决办法**：在百度上寻找更加通俗的教程[GitHub网页版开始教程](https://blog.csdn.net/wait_for_taht_day5/article/details/79587844)，在这里可以找到以下的步骤：
   * 创建一个开源库
   * 开始和管理一个新的分支
   * 修改一个文件并且向GitHub提交这些修改
   * 开启和合并一个合并请求

*  **用时**：用了一个下午进行浏览，但是并未实际进行操作，因为在接下来的会刊更新中没有使用到修改合并，casdu/huikan这个仓库已经是出现在我的主页了，那么我就直接在网页端进行编辑了。

### 第五个问题之会刊更新

*  **问题阐述**：首先我提到kuikan已经在我的目录，那么我直接在网页上进行编辑就可以，我在kuikan下新建立一个2019.md文件，但是只限于将手头的word文字码上去，不知道如何使用Markdown格式进行美化操作。
*  **解决办法**：[百度(GitHub上README.md排版样式教程)](https://blog.csdn.net/weixin_39923425/article/details/79584378)、GitHubGuides[LearnMarkdown](https://guides.github.com/features/mastering-markdown/)、提出新的ISSUE向有经验者进行询问、查找已经更新的2018.md点击history[查看以往的代码](https://github.com/casdu/huikan/commit/c2ef5b1248072c59ef5848928fdb8421073875f3#diff-482416b57c0af3e14b6c5c55da5373cb)。
   以下是更新会刊需要用到的几种格式：
   
   * 1、各级标题（用于区分重要性、文章标题等）
   * 2、缩进    （用于作者介绍、引用他人文字）  
   * 3、超链接  （用于目录与文章标题跳转、回到目录、转到外部链接等）
   * 4、分级    （更加美观的目录显示）：
   * 5、空格    （用于不同格式之间的切断，上面的操作中空格同样非常重要）

*  **用时**：markdown格式学习以及初次录入一篇文章约一个下午。引入目录花费30分钟。  
          断断续续进行更新，偶尔更新几篇的频率，在转载过程中又是一次新的阅读，在完成全部2019.md录入约一个月。

###  第六个问题之探索更多
*   **问题阐述**：后续markdown格式探索之图片显示、表格显示、表情显示
*   **解决办法**：[图片显示](https://blog.csdn.net/itmyhome1990/article/details/48765703?depth_1-utm_source=distribute.pc_relevant.none-task&utm_source=distribute.pc_relevant.none-task)、[表格显示](https://blog.csdn.net/tuxingchen6/article/details/55222951#comments)、[表情显示](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md#smileys--emotion)
*   **用时**：不定时瞅瞅 :rofl:


## 最后谈一些我对于Github 的理解:

Github是一个和论坛很类似的平台，和论坛做对比的话，论坛的帖子就像一本本已经装订好的本子，而这个本子一开始是楼主所有的由他进行书写。
同时论坛上有很多的版主和用户，版主的权限是很多的，可以对书写的内容审核如果不好可以修改，也可加精加权限等等。
用户呢，参与本子的后续书写也可以点评，但是发现之前如果有可以改动的地方是无能为力的，因为用户的权限比较低。
而Github就像一本活页本，它是公共的，这意味很多人都可以用到它，但是挪出活页本的一页去复印的时候，会显示来源在哪里。
而且，活页本的好处就是不断更新，对于每一个加入电子版会刊编辑的伙伴，可以进行权限操作，编辑和加工，相当于就是人人都是版主，
同时这也Github的功能之一，Working with a team? GitHub is built for collaboration. Set up an organization to improve the way your team works together, and get access to more features. 翻译过来就是说，GitHub是为协作而构建的。建立一个组织来改进团队合作的方式，并获得更多功能。

探索也是一种乐趣。

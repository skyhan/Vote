### 来投吧v1.0版本需求文档 ###


----------

本文档旨在**帮助天狗理解需求** ，共同完成我们的来投吧

[md文档编辑器下载](http://markdownpad.com/ "戳我下载MD编辑器")
### 文档维护历史记录 ###

----------
    2014/1/5 17:48:06   耿宗尊
### 终极目标 ###

----------



我们的终极目标是最终打造一个专业的投票平台，让投票的人使用起来非常简单，让发起投票的人觉得功能十分强大，暂时想到的后续的发展道路可以如下：
	
    1.作为第三方的专业投票网站，充当中间人和裁判员的角色，保证用户的投票公正性的保密性
    
	2.手机客户端，更加快捷方便，让发起投票的人可以实时方便的查看TOKEN。
	  可以利用手机的联系人让投票人迅速的收到投票的信息。

    3.数据挖掘，搜索的功能，提供给用户想要的数据，匿名投票的数据真实能反应人最真实的想法。
	  数据应该是有价值的，可以给想要决策的人一些建议，比如想去哪里旅游的投票。

    4.调查问卷的形式，很多调查问卷还是纸质的。
	  并且一般现场调查问卷，很多人也不好意思写真实的法，而且还没有酬劳。
	  如果可以将用户复印的钱拿出来作为网络上调查的钱，既可以节省成本也可以很快收集到数据。
	  当然，答题的人要有积分，积分可以兑换钱或者小礼品。这个想法不错，就是实现起来可能会复杂一些。



### 来投吧V1.0版本要做的 ###

----------
分为两个迭代
	<table>
    <tr>
		<td>投票方式</td>
		<td>简介</td>
        <td>优点</td>
		<td>缺点</td>
		<td>适用场合</td>
    </tr>
	<tr>
		<td>IP投票</td>
		<td>该投票无需注册，谁都可以发起，根据IP来判定其唯一性</td>
		<td>十分方便，无需注册</td>
		<td>安全性不高，可利用IP进行重复投票，或者找人拉票</td>
		<td>适用实时的投票，或者投票人是信赖的（*比如室友投票去哪吃，选室长等*）</td>
    </tr>	
	<tr>
		<td>Token投票</td>
		<td>仅投票人需要注册，只有注册的人可以发起投票，针对一个投票</td>
		<td>安全，可靠性高，投票人依然无需注册</td>
		<td>发起投票的人需要注册，并且需要将token发给每个人</td>
		<td>适用一些正规的投票，要求结果准确安全（*比如公司提名的一些奖项*）</td>
    </tr>
	</table>



### 采用的框架 ###
 
前端采用[backbone.js](http://backbonejs.org/ "backbone官网传送门")+[bootstrap](http://getbootstrap.com/ "bootstrap官网传送门")，后端采用reastful风格提供数据（JSON格式），数据库采用MySQL.

### 参考 ###
 
 投票人拿token进入投票的页面可参考百度网盘的提取文件，[[猛戳我查看]](http://pan.baidu.com/share/init?shareid=1933522150&uk=1077187917 "投票人拿token进入")

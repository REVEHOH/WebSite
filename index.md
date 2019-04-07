<html>
 <head>
  <link href="main.css" type="text/css" rel="stylesheet" />
 <link rel="stylesheet" href="js&jq/jquery-ui.css">
  <script src="js&jq/button.js"></script>
  <script src="js&jq/jquery-3.3.1.min.js"></script>
  <script src="js&jq/jquery-ui.min.js"></script>	
<script type="text/javascript"> 
           $(document).ready(function() {
                $('#navigationMenu li .normalMenu').each(function() {
				// each()方法规定为每个匹配元素规定运行的函数
                    $(this).before($(this).clone().removeClass().addClass('hoverMenu'));
					// clone()方法克隆并追加选定的元素（包含其子节点、文本和属性）
					// removeClass()方法从元素移除一个或多个类，如果没有规定参数则删除所有类
                });
                $('#navigationMenu li').hover(
				// hover()方法规定当鼠标指针在元素悬停和离开上时要运行的两个函数
					function() { $(this).find('.hoverMenu').stop().animate({ marginTop: '0px' }, 200);},
					// find()方法搜索当前元素中的后代元素
					function() { $(this).find('.hoverMenu').stop().animate({ marginTop: '-24px' }, 200);}
				);
            });
</script>
 <script>
			$(function() {
				var keywords = ["晨曦恋歌", "幸运小猫", "店长也疯狂", "街头热血篮球", "别跑精灵", 
				                 "皇后在上", "甜心恋人", "浅浅梦女王", "聊天女仆之魔法", "恋在风下",
								 "火柴人生存挑战", "果汁瓶跳跃", "蛇与方块", "我的世界消消乐", "积木拼图",
								 "超人不会飞", "逃离度假别墅", "六角拼拼", "挑战瞬间记忆", "史上最坑爹的游戏8",
								 "倚天屠龙记", "魔域来了之魔域神曲", "英雄霸业", "屠神", "水龙吟", ];
				$("#search").autocomplete({
					source: keywords
				});
			});
</script>
  </head>
  <body>
    <div class="container">
      <div class="header">
        <h1 class="header">QXLY小游戏</h1>
      <div class="left">
        <a href="index.htm" title="女生 闯关 益智 休闲 传奇 ">首页</a>
        <a href="2-1女生.htm" title="攻略 恋爱 文字 休闲 剧情">女生</a>
        <a href="2-3闯关.htm" title="消消乐 赛车 益智 娱乐 跑酷">闯关</a>
        <a href="2-4益智.htm" title="答题 围棋 象棋 解密 密室">益智</a>
        <a href="2-2休闲.htm" title="娱乐 搞笑 益智 休闲 点泡泡">休闲</a>
        <a href="2-5传奇.htm" title="龙族 休闲 修仙 王者 水月">传奇</a>
      </div>
      <div class="right">
      <p><span style=" display:block; width:300px; height:36px; background:#0080C0; color:white; font-size:20px; float:left; margin-left:80px;">
         <input type="text" placeholder="游戏名/游戏类别/游戏装备" 
         id="search" style="border:none; width:240px; height:30px; margin-top:3px;" />
         <a href="javascript:test()" style="margin-left:2px; margin-right:2px; text-decoration:none; color:#FFF;">搜索</a></span></p>
      </div>
</div>
<div class="container9">
     <div class="container10">
	        <div class="block5">
		         <ul id="navigationMenu">
                      <li><a href="index.htm" class="normalMenu">首页</a></li>
                      <li><a href="2-5传奇.htm" class="normalMenu">传奇系列</a></li>
                      <li><a href="2-5传奇.htm" class="normalMenu">魔幻武侠</a></li>
                      <li><a href="2-1女生.htm" class="normalMenu">剧情文字</a></li>
                      <li><a href="2-2休闲.htm" class="normalMenu">休闲放置</a></li>
                      <li><a href="2-4益智.htm"class="normalMenu">智能</a></li>
                      <li><a href="2-4益智.htm" class="normalMenu">益智烧脑</a></li>
                      <li><a href="2-3闯关.htm" class="normalMenu">赛车</a></li>
                      <li><a href="2-2休闲.htm" class="normalMenu">儿童</a></li>
                      <li><a href="2-3闯关.htm" class="normalMenu">策略</a></li>
                      <li><a href="index.htm" class="normalMenu">体育运动</a></li>
              </ul>
            </div>		
    </div>
     <div class="container2">
       <div class="block1">
       <ul>
       <li><span style="background:#35BDFF; padding:3px;color:#FFF;">网游</span> 
       <a href="3.1.1.htm">妖怪宝可萌</a> | 
       <a href="3.1.1.htm">荣耀与远征</a> | 
       <a href="3.1.1.htm">传奇</a> | 
       <a href="3.1.1.htm">仙剑奇侠传</a> | 
       <a href="3.1.1.htm">绝世神功</a></li>
       <li><span style="background:#FF8080; padding:3px;color:#FFF;">热门</span> 
       <a href="3.1.2.htm">红白机</a> | 
       <a href="3.1.2.htm">口袋妖怪</a> | 
       <a href="3.1.2.htm">游戏攻略</a> | 
       <a href="3.1.2.htm">新闻资讯</a></li>
       <li><span style="background:#35BDFF; padding:3px;color:#FFF;">休闲</span> 
       <a href="3.1.3.htm">拼图</a> | 
       <a href="3.1.3.htm">方块</a> | 
       <a href="3.1.3.htm">连连看</a> | 
       <a href="3.1.3.htm">梦道</a>| 
       <a href="3.1.3.htm">店长也疯狂</a>| 
       <a href="3.1.3.htm">益智闯关</a></li>
       <li><span style="background:#FF8080; padding:3px;color:#FFF;">女生</span> 
       <a href="3.1.4.htm">甜点恋人</a> | 
       <a href="3.1.4.htm">浅浅女王梦</a> | 
       <a href="3.1.4.htm">花儿消消乐</a> | 
       <a href="3.1.4.htm">幸运的小猫</a></li>
       <li><span style="background:#35BDFF; padding:3px;color:#FFF; margin-left:35px;">动作</span> 
       <a href="3.1.5.htm">乱斗堂3</a> | 
       <a href="3.1.5.htm">魔晶猎人</a> | 
       <a href="3.1.5.htm">闯关</a> | 
       <a href="3.1.5.htm">金庸侠客行</a></li>
       <li><span style="background:#FF8080; padding:3px;color:#FFF; margin-left:5px;">儿童</span> 
       <a href="3.1.1.htm">萌宠消消乐</a> | 
       <a href="3.1.1.htm">我要当首富2</a> | 
       <a href="3.1.1.htm">口袋之旅</a> | 
       <a href="3.1.1.htm">大富豪3</a> | 
       <a href="3.1.1.htm">做蛋糕</a></li>
       </ul>
       </div>
       <div><img src="img/i2.gif"/></div>
        <div style="text-align:left; margin-left:20px;"><h3>热门推荐</h3></div>
            <div class="container3">
                 <div class="block2">
                      <a href="3.1.1.htm"><span><img src="img/楚乔传.jpg" />楚乔传</span></a>
                      <a href="3.1.1.htm"><span><img src="img/凡人飞仙传.png" />凡人飞仙</span></a>
                      <a href="3.1.1.htm"><span><img src="img/公路追逐.jpg" />公路追逐</span></a>
                      <a href="3.1.1.htm"><span><img src="img/叫我猫主子.jpg" />我猫主子</span></a>
                      <a href="3.1.1.htm"><span><img src="img/金庸侠客传.png" />金庸侠客</span></a>
                      <a href="3.1.1.htm"><span><img src="img/轮回决.jpg" />轮回决</span></a>
                      <a href="3.1.1.htm"><span><img src="img/口袋妖怪大师.jpg" />口袋妖怪</span></a>
                      <a href="3.1.1.htm"><span><img src="img/龙族霸业.png" />龙族霸业</span></a>
                      <a href="3.1.1.htm"><span><img src="img/荣耀足球.png" />荣耀足球</span></a>
                      <a href="3.1.1.htm"><span><img src="img/神游记.png" />神游记</span></a>
                      <a href="3.1.1.htm"><span><img src="img/文字修真.png" />文字修真</span></a>
                      <a href="3.1.1.htm"><span><img src="img/小猪佩奇.jpg" />小猪佩奇</a></a>
                      <a href="3.1.1.htm"><span><img src="img/妖怪梦可宝.jpg" />梦可宝</a></a>
                      <a href="3.1.1.htm"><span><img src="img/楚乔传.jpg" />楚乔传</span></a>
                      <a href="3.1.1.htm"><span><img src="img/决战沙城.gif" />决战沙城</span></a>
                      <a href="3.1.1.htm"><span><img src="img/口袋妖怪大师.jpg" />口袋妖怪</span></a>
                      <a href="3.1.1.htm"><span><img src="img/龙族霸业.png" />龙族霸业</span></a>
                      <a href="3.1.1.htm"><span><img src="img/荣耀足球.png" />荣耀足球</span></a>
                      <a href="3.1.1.htm"><span><img src="img/凡人飞仙传.png" />凡人飞仙</span></a>
                      <a href="3.1.1.htm"><span><img src="img/叫我猫主子.jpg" />叫猫主子</span></a>
                      <a href="3.1.1.htm"><span><img src="img/齐天大圣.jpg" />齐天大圣</span></a>
                      <a href="3.1.1.htm"><span><img src="img/非人学院.jpg" />文字修真</span></a>
                </div>
          </div>
          <div style="text-align:left;margin-left:20px;"><h3>游戏专题</h3></div>
          <div class="container4">
          <div style="position:relative; float:left; margin-left:30px;">
               <a href="2-5传奇.htm"><img src="img/明星类小游戏合集.jpg" width="220px" height="150px;"/>
                   <div style="position:absolute; z-index:2; left:0px; top:120px; color:#FFF;">
                       <span style=" display:block; width:220px; height:30px; background-color: rgba(0,0,0,0.8); text-align:center;">
                            明星类小游戏合集</span></div></div></a>
          <div style="position:relative; float:left; margin-left:25px">
               <a href="2-5传奇.htm"><img src="img/星座小游戏合集.jpg" width="220px" height="150px;"/>
                   <div style="position:absolute; z-index:2; left:0px; top:120px; color:#FFF;">
                       <span style=" display:block; width:220px; height:30px; background-color: rgba(0,0,0,0.8); text-align:center;">
                            星座小游戏合集</span></div></div></a>
           <div style="position:relative; float:left; margin-left:25px">
               <a href="2-5传奇.htm"><img src="img/角色扮演类小游戏合集.jpg" width="220px" height="150px;"/>
                   <div style="position:absolute; z-index:2; left:0px; top:120px; color:#FFF;">
                       <span style=" display:block; width:220px; height:30px; background-color: rgba(0,0,0,0.8); text-align:center;">
                            角色扮演类小游戏合集</span></div></div></a>
            <div style="position:relative; float:left; margin-left:25px">
               <a href="2-5传奇.htm"><img src="img/喜羊羊与灰太狼小游戏专题.jpg" width="220px" height="150px;"/>
                   <div style="position:absolute; z-index:2; left:0px; top:120px; color:#FFF;">
                       <span style=" display:block; width:220px; height:30px; background-color: rgba(0,0,0,0.8); text-align:center;">
                            喜羊羊与灰太狼小游戏专题</span></div></div></a>
                            
    </div>
    <div class="container5">
    <div style="text-align:left; margin-left:20px;"><h3>游戏分类</h3></div>
                 <div class="block3">
                      <a href="2-1女生.htm"><span><img src="img/女生.jpg" />女生</span></a>
                      <a href="2-3闯关.htm"><span><img src="img/闯关.jpg" />闯关</span></a>
                      <a href="2-4益智.htm"><span><img src="img/益智.jpg" />益智</span></a>
                      <a href="2-2休闲.htm"><span><img src="img/休闲.jpg" />休闲</span></a>
                      <a href="2-5传奇.htm"><span><img src="img/传奇.jpg" />传奇</span></a></div></div>
    <div class="container6">
    <div style="text-align:left; margin-left:20px;"><h3>排行榜</h3></div>
      <table width="100%" border="1" class="tab1">
        <tr>
          <td width="30%"><span style="display:block; width:20px; height:20px; border:1px dashed #F00; text-align:center; margin-bottom:10px;">
          1</span> 
          <a href="3.1.1.htm">黄金矿工双人版</a></td>
          <td width="41%"><span style="display:block; width:20px; height:20px; border:1px dashed  #35BDFF; text-align:center;margin-bottom:10px;">
          4</span><a href="3.1.1.htm">挖掘机大挑战</a></td>
          <td width="29%"><span style="display:block; width:20px; height:20px; border:1px dashed  #35BDFF; text-align:center;margin-bottom:10px;">
          7</span><a href="3.1.1.htm">快打旋风</a></td>
        </tr>
        <tr>
          <td><span style="display:block; width:20px; height:20px; border:1px dashed  #0F0; text-align:center;margin-bottom:10px;">2</span> 
          <a href="3.1.1.htm">大鱼吃小鱼双人版</a></td>
          <td><span style="display:block; width:20px; height:20px; border:1px dashed  #35BDFF; text-align:center;margin-bottom:10px;">5</span>
          <a href="3.1.1.htm">森林冰火人</a></td>
          <td><span style="display:block; width:20px; height:20px; border:1px dashed  #35BDFF; text-align:center;margin-bottom:10px;">8</span>
          <a href="3.1.1.htm">喜羊羊卡丁车2</a></td>
        </tr>
        <tr>
          <td><span style="display:block; width:20px; height:20px; border:1px dashed  #00F; text-align:center;margin-bottom:10px;">3</span> 
          <a href="3.1.1.htm">闪翼双星无敌版</a></td>
          <td><span style="display:block; width:20px; height:20px; border:1px dashed  #35BDFF; text-align:center;margin-bottom:10px;">6</span> 
          <a href="3.1.1.htm">拳皇wing09</a></td>
          <td><span style="display:block; width:20px; height:20px; border:1px dashed #35BDFF;; text-align:center;margin-bottom:10px;">9</span> 
          <a href="3.1.1.htm">熊出没钓鱼</a></td>
        </tr>
      </table>
    </div>
  <div style="text-align:left;margin-left:20px;"><h3>游戏推荐</h3></div>
          <div class="container4">
          <div style="position:relative; float:left; margin-left:30px;">
               <a href="2-1女生.htm"><img src="img/火影忍者.gif" width="220px" height="150px;"/>
                   <div style="position:absolute; z-index:2; left:0px; top:120px; color:#FFF;">
                       <span style=" display:block; width:220px; height:30px; background-color: rgba(0,0,0,0.8); text-align:center;">
                            火影忍者</span></div></div></a>
          <div style="position:relative; float:left; margin-left:25px">
               <a href="2-1女生.htm"><img src="img/史上最贱游戏系列.gif" width="220px" height="150px;"/>
                   <div style="position:absolute; z-index:2; left:0px; top:120px; color:#FFF;">
                       <span style=" display:block; width:220px; height:30px; background-color: rgba(0,0,0,0.8); text-align:center;">
                           史上最贱游戏系列</span></div></div></a>
           <div style="position:relative; float:left; margin-left:25px">
               <a href="2-1女生.htm"><img src="img/萌猫来配.jpg" width="220px" height="150px;"/>
                   <div style="position:absolute; z-index:2; left:0px; top:120px; color:#FFF;">
                       <span style=" display:block; width:220px; height:30px; background-color: rgba(0,0,0,0.8); text-align:center;">
                            萌猫来配</span></div></div></a>
            <div style="position:relative; float:left; margin-left:25px">
               <a href="2-1女生.htm"><img src="img/最好玩的手机游戏.jpg" width="220px" height="150px;"/>
                   <div style="position:absolute; z-index:2; left:0px; top:120px; color:#FFF;">
                       <span style=" display:block; width:220px; height:30px; background-color: rgba(0,0,0,0.8); text-align:center;">
                            最好玩的手机游戏</span></div></div></a>
                            
    </div>
      <div style="text-align:left; margin-left:20px;"><h3>最新更新</h3></div>
      <div class="block4">
                      <a href="3.1.2.htm"><span><img src="img/楚乔传.jpg" />楚乔传</span></a>
                      <a href="3.1.2.htm"><span><img src="img/凡人飞仙传.png" />凡人飞仙</span></a>
                      <a href="3.1.2.htm"><span><img src="img/公路追逐.jpg" />公路追逐</span></a>
                      <a href="3.1.2.htm"><span><img src="img/叫我猫主子.jpg" />我猫主子</span></a>
                      <a href="3.1.2.htm"><span><img src="img/金庸侠客传.png" />金庸侠客</span></a>
                      <a href="3.1.2.htm"><span><img src="img/决战沙城.gif" />决战沙城</span></a>
                      <a href="3.1.2.htm"><span><img src="img/口袋妖怪大师.jpg" />口袋妖怪</span></a>
                      <a href="3.1.2.htm"><span><img src="img/龙族霸业.png" />龙族霸业</span></a>
                      <a href="3.1.2.htm"><span><img src="img/荣耀足球.png" />荣耀足球</span></a>
                      <a href="3.1.2.htm"><span><img src="img/神游记.png" />神游记</span></a>
                      <a href="3.1.2.htm"><span><img src="img/琅琊榜.jpg" />琅琊榜</span></a>
                      <a href="3.1.2.htm"><span><img src="img/小猪佩奇.jpg" />小猪佩奇</span></a>
                      <a href="3.1.2.htm"><span><img src="img/妖怪梦可宝.jpg" />梦可宝</span></a>
                      <a href="3.1.2.htm"><span><img src="img/黄金裁决.png" />黄金裁决</span></a>
                      <a href="3.1.2.htm"><span><img src="img/齐天大圣.jpg" />齐天大圣</span></a>
                      <a href="3.1.2.htm"><span><img src="img/轮回决.jpg" />轮回决</span></a>
                      <a href="3.1.2.htm"><span><img src="img/神谕.jpg" />神谕业</span></a>
                      <a href="3.1.2.htm"><span><img src="img/钟馗传说.jpg" />钟馗传说</span></a>
                      <a href="3.1.2.htm"><span><img src="img/非人学院.jpg" />非人学院</span></a>
                      <a href="3.1.2.htm"><span><img src="img/公路追逐.jpg" />公路追逐</span></a>
                      <a href="3.1.2.htm"><span><img src="img/我的海洋世界.jpg" />海洋世界</span></a>
                      <a href="3.1.2.htm"><span><img src="img/文字修真.png" />文字修真</span></a>
                </div></div>
 <div class="container7">
      <table width="100%" border="1" class="tab2">
        <tr>
          <td><ul>
                 <li><a href="2-2休闲.htm">2019第一桶金 《热血合击》元宝获取全解</a></li>
                 <li><a href="2-2休闲.htm">暗裔来袭《光明勇士》暗裔入侵玩法详解</a></li>
                 <li><a href="2-2休闲.htm">音符魔咒《幻想计划》钢琴镰刀瑟蕾希上线</a></li>
                 <li><a href="2-2休闲.htm">腊八到贺新年《姬魔恋战纪》彩蛋剧情</a></li>
                 <li><a href="2-2休闲.htm">四大角色来袭《RWBY》人物档案公开</a></li></ul></td>
          <td><ul>
                 <li><a href="2-4益智.htm">《螺旋英雄谭》火爆公测中 螺旋经典OP内田彩</a></li>
                 <li><a href="2-4益智.htm">孤高传说宇智波斑 S级传说之忍上线《火影忍者》</a></li>
                 <li><a href="2-4益智.htm">外表萌火力猛《君临之境》激萌萝莉通感者盘点</a></li>
                 <li><a href="2-4益智.htm">萝莉身傲娇心《姬魔恋战纪》张飞是个怎样的人？</a></li>
                 <li><a href="2-4益智.htm">今日苹果首发《机械世纪》开启全民沙盒时代</a></li></ul></td>
          <td><ul>
                 <li><a href="2-4益智.htm">空降TOP1？《非人学园》日韩版本上线好评如潮</a></li>
                 <li><a href="2-4益智.htm">开启你的羁绊《姬魔恋战纪》专注虐汪一百年</a></li>
                 <li><a href="2-4益智.htm">从星天监深处走出的少年《镇魔曲》新男主首曝</a></li>
                 <li><a href="2-4益智.htm">号令天下 玩转《热血合击》威名系统</a></li>
                 <li><a href="2-4益智.htm">探索开启《Fate/Grand Order》亚种特异点Ⅳ</a></li></ul></td>
        </tr>
      </table></div>
      <div style="background:#FFF; margin-top:360px;">
       <div class="container8">
      <div style="text-align:left; margin-left:20px;"><h3>友情链接</h3></div>
      <p><a href="#">18183手游网</a> | <a href="#">H5游戏</a> | <a href="#">18183手游论坛</a> | <a href="#">18183新游频道</a>
      | <a href="#">多玩游戏</a> | <a href="#">搞趣网</a> | <a href="#">4399手机游戏网</a> | <a href="#">爱拍手游视频站</a> | 
      <a href="#">4399在线玩</a> | <a href="#">啪嗒动漫</a> | </p>     
      <p><a href="#">最全手游排行榜</a> |<a href="#">手游排行榜</a> | <a href="#">苹果游戏</a> | <a href="#">浏览器家园</a> | 
      <a href="#">电脑玩手机游戏</a> |  <a href="#">网页游戏</a> | <a href="#">英雄联盟</a> | <a href="#">兔玩电竞</a> | 
      <a href="#">特玩发号</a> | <a href="#">17173逆战</a> | <a href="#">王者荣耀视频</a> |</p> 
      <p><a href="#">17173发号平台</a> | <a href="#">手游巴士</a> | <a href="#">快玩游戏</a> | <a href="#">07073H5游戏</a> | 
      <a href="#">英雄联盟视频</a> | <a href="#">美女小游戏</a> | <a href="#">玩游戏赚钱</a> | <a href="#">哒哒加速器</a> | 
      <a href="#">当乐手机游戏</a> | <a href="#">7724游戏</a> |</p> 
      <p><a href="#">VR游戏</a> | <a href="#">小皮手游网</a> | <a href="#">核弹头手游下载</a> | <a href="#">DNF</a> | <a href="#">魔兽世界</a> |      <a href="#">119手游排行榜</a> |  <a href="#">炉石传说</a> |  <a href="#">战锤全面战争</a> |  <a href="#">手游模拟器</a> |  
      <a href="#">1122小游戏</a> |      <a href="#">游戏试玩平台</a> |</p>
      </div> 
    </div>
  </div>
</div>
</div>
</div>
      <div class="footer">
      <p><a href="#">关于我们</a>|<a href="#">联系我们</a>|<a href="#">招贤纳士</a>|<a href="#">网站地图</a><br/> 
      Copyright@2018-2019QXLY.All.rights.received<br/>
      津网文【2018】1158-009号 津工cp备18003662号 增值电信业务经营许可证 津B2-20160027</p>
      </div>
    </div>
  </body>
</html>
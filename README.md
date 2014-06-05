<h1>jigsaw中文自然语言处理java包</h1>         
<h2>开发目的</h2>
<p>  
本项目目的在于构建一个标准化的NLP处理框架，提供标准API和企业级的实现。
 目前国内外有不少NLP实现包，包括中科院、复旦大学、斯坦福大学等学校和研究机构，都有自己的作品。
此外有些NLP研究人员也有自己的实现，如ansj等。
2012年本人在开发一个NLP相关项目时，需要寻找一些开源的实现来加快进度。
可是学校、研究院所提供的实现，算法先进，但是代码难懂，架构不清晰；
而爱好者提供的实现，bug多，算法比较初级。都很难达到企业级应用的要求。
为此，建立这个项目，希望NLP研究者和资深的程序员能够良好的结合起来，提供标准化的接口以及比较全面的算法实现，
特别是针对中文的自然语言处理实现。
</p>
内容简介
----------------------------------- 

目标使用者：
1. 针对语言专家，提供语料库开发接口。专家不用关心语料库将如何被使用，而专注于如何提升语料库的质量上。
2. 针对NLP算法专家，提供算法开发接口，调用所需要的语料库，实现标准API。 
3. 针对NLP用户，屏蔽算法实现细节和语料库，可以方便的通过API来调用NLP的算法库。提供常用的算法封装接口供调用。

针对这些目标使用者，系统也分为如下几个部分:
1. corpus-语料库；
2. algorithm - 算法库；
3. api - NLP接口；
4. plugins 插件，包括Lucene、springframework插件

开发计划
----------------------------------- 

第一阶段的开发计划，在2014年6月30日前完成0.2版本。

1. 中文分词框架和标准实现；

2. 关键字提取算法框架；

3. 文档摘要算法框架。

第二阶段开发计划，在2014年12月31日前推出0.3版本，待实现的内容需要征求大家意见。


联系方式
----------------------------------- 
如果要加入本项目，或者任何建议，请发邮件到shamphone@gmail.com 
  
# github-collections
collect to github repo 
use [like-on-github](https://github.com/willowj/like-on-github) modified from [Idnan](https://github.com/Idnan/like-on-github)
 
### _<**WINPC**>


 - ##### <**winpc**> [C - voidtools](https://www.voidtools.com/support/everything/sdk/c/)    2018/6/17 



 - ##### <**winpc**> [C - voidtools](https://www.voidtools.com/support/everything/sdk/c/)    2018/6/17 

### _<**LINUX TOOLS**>


 - ##### <**linux tools**> [junegunn/fzf: A command-line fuzzy finder](https://github.com/junegunn/fzf#arch-linux)    2018/6/17 
    - note:  



 - ##### <**linux tools**> [junegunn/fzf: A command-line fuzzy finder](https://github.com/junegunn/fzf#arch-linux)    2018/6/17 
    - note:  

### _<**DOCS**>


 - ##### <**DOCS**> [git命令大全](https://gist.github.com/guweigang/9848271)    2018/6/16 
    - note:  

### _<**PYTHON**>


 - ##### <**python**> [Python 中 import 的机制与实现 - Python - 伯乐在线](http://python.jobbole.com/82604/)    2018/6/16 
    - note:  import hook ,lazy import
    - > ```python
      > import sys
      > import imp
      >  
      > _lazy_modules = {}
      >  
      > class LazyModule():
      >     def __init__(self, name):
      >         self.name = name
      >  
      >     def __getattr__(self, attr):
      >         path = _lazy_modules[self.name]
      >         f, pathname, desc = imp.find_module(self.name, path)
      >  
      >         lf = sys.meta_path.pop()
      >         imp.load_module(self.name, f, pathname, desc)
      >         sys.meta_path.append(lf)
      >  
      >         self.__dict__ = sys.modules[self.name].__dict__
      >         return self.__dict__[attr]
      >  
      > class LazyFinder(object):
      >  
      >     def find_module(self, name, path):
      >         _lazy_modules[name] = path
      >         return self
      >  
      >     def load_module(self, name):
      >         return LazyModule(name)
      >  
      > sys.meta_path.append(LazyFinder())
      > ```

### _<**ONLINE COMPILE **>


 - ##### <**online compile **> [Compile and Execute C Online](http://www.compileonline.com/compile_c_online.php)    2018/6/16 
    - note:  

### _<**WINPC-TOOLS**>


 - ##### <**winpc-tools**> [zhongyang219/TrafficMonitor: 这是一个用于显示当前网速、CPU及内存利用率的桌面悬浮窗软件，并支持任务栏显示，支持更换皮肤。](https://github.com/zhongyang219/TrafficMonitor)    2018/6/16 
    - > Traffic Monitor是一款用于Windows平台的网速监控悬浮窗软件，可以显示当前网速、CPU及内存利用率，支持嵌入到任务栏显示，支持更换皮肤、历史流量统计等功能。

### _<**JQUERY**>


 - ##### <**jquery**> [jQuery获取Select选择的Text和 Value(转) - yaoshiyou - 博客园](https://www.cnblogs.com/yaoshiyou/archive/2010/08/24/1806939.html)    2018/6/15 
    - note: test4444
    - >     jQuery获取Select选择的Text和Value:
      > 语法解释：
      > 1. $("#select_id").change(function(){//code...});   //为Select添加事件，当选择其中一项时触发
      > 2. var checkText=$("#select_id").find("option:selected").text();  //获取Select选择的Text
      > 3. var checkValue=$("#select_id").val();  //获取Select选择的Value
      > 4. var checkIndex=$("#select_id ").get(0).selectedIndex;  //获取Select选择的索引值
      > 5. var maxIndex=$("#select_id option:last").attr("index");  //获取Select最大的索引值
      > jQuery设置Select选择的 Text和Value:

### _<**COLLECT**>


 - ##### <**collect**> [options input - 搜狗搜索](https://www.sogou.com/web?query=options+input)    2018/6/15 
    - note: test....
    - > 搜狗已为您找到约25,812条相关结果
      > 您是不是要搜索英文结果：options input
      >  javascript options input 的操作 - web - ITeye论坛
      > The input doesn't contain any classes. Did you specify the proper '-injars' options? Error: The output jar is empty. Did you specify the proper '-keep' options? <head> <meta http-equiv=...
      > www.iteye.com/topic... - 2006-12-1 - 快照



 - ##### <**collect**> [HTML Form Elements](https://www.w3schools.com/html/html_form_elements.asp)    2018/6/15 
    - note: test2222
    - > The <textarea> Element
      > The <textarea> element defines a multi-line input field (a text area):
      > 
      > Example



 - ##### <**collect**> [js获取鼠标选中的文字 - 荔枝龙眼 - 博客园](https://www.cnblogs.com/yigeqi/p/3988705.html)    2018/6/15 
    - note: test33333
    - > document.selection.createRange().text; IE9以下使用
      > 
      > window.getSelection().toString(); 其他浏览器使用



 - ##### <**collect**> [sindresorhus (Sindre Sorhus)](https://github.com/sindresorhus)    2018/6/15 
    - note: 萨迪克基本
      > 
    - > Pinned repositories 
      > 
      > avajs/ava
      > 🚀 Futuristic JavaScript test runner



 - ##### <**collect**> [jqury is hiden - Google 搜索](https://www.google.pl/search?ei=PcAjW4D7LbHJ0PEPrIq7kA4&q=jqury+is+hiden&oq=jqury+is+hiden&gs_l=psy-ab.12...0.0.3.392.0.0.0.0.0.0.0.0..0.0....0...1..64.psy-ab..0.0.0....0.QyPwB6CAfI4)    2018/6/15 
    - note: 
      >  



 - ##### <**collect**> [jqury is hiden - Google 搜索](https://www.google.pl/search?ei=PcAjW4D7LbHJ0PEPrIq7kA4&q=jqury+is+hiden&oq=jqury+is+hiden&gs_l=psy-ab.12...0.0.3.392.0.0.0.0.0.0.0.0..0.0....0...1..64.psy-ab..0.0.0....0.QyPwB6CAfI4)    2018/6/15 
    - note: 
      > 
      >  



 - ##### <**collect**> [erguotou520/electron-ssr: Shadowsocksr client using electron](https://github.com/erguotou520/electron-ssr)    2018/6/16 
    - note: 
      >  



 - ##### <**collect**> [C - voidtools](https://www.voidtools.com/support/everything/sdk/c/)    2018/6/17 



 - ##### <**collect**> [C - voidtools](https://www.voidtools.com/support/everything/sdk/c/)    2018/6/17 



 - ##### <**collect**> [C - voidtools](https://www.voidtools.com/support/everything/sdk/c/)    2018/6/17 


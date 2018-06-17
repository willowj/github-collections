# github-collections
collect to github repo 
use [like-on-github](https://github.com/willowj/like-on-github) modified from [Idnan](https://github.com/Idnan/like-on-github)
 

### _<**PY TOOLS**>


 - ##### <**py tools**> [pyenv/pyenv: Simple Python version management](https://github.com/pyenv/pyenv)    2018/6/18 

### _<**PY ASYNC**>


 - ##### <**py async**> [timofurrer/awesome-asyncio: A curated list of awesome Python asyncio frameworks, libraries, software and resources](https://github.com/timofurrer/awesome-asyncio)    2018/6/17 

### _<**LINUX TOOLS**>


 - ##### <**linux tools**> [junegunn/fzf: A command-line fuzzy finder](https://github.com/junegunn/fzf#arch-linux)    2018/6/17 
    - note:  



 - ##### <**linux tools**> [junegunn/fzf: A command-line fuzzy finder](https://github.com/junegunn/fzf#arch-linux)    2018/6/17 
    - note:  




 - ##### <**linux tools**> [Build instructions · cboxdoerfer/fsearch Wiki](https://github.com/cboxdoerfer/fsearch/wiki/Build-instructions)    2018/6/17 
    - note:  file search tool for unix like system
      > 


### _<**DOCS**>

 - ##### <**DOCS**> [git命令大全](https://gist.github.com/guweigang/9848271)    2018/6/16 
    - note:  



 - ##### <**docs**> [dabeaz/python-cookbook: Code samples from the "Python Cookbook, 3rd Edition", published by O'Reilly & Associates, May, 2013.](https://github.com/dabeaz/python-cookbook)    2018/6/18 



 - ##### <**docs**> [15.10 用Cython包装C代码 — python3-cookbook 2.0.0 文档](http://python3-cookbook-personal.readthedocs.io/zh_CN/latest/c15/p10_wrap_existing_c_code_with_cython.html)    2018/6/18 

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

### _<**ONLINE COMPILE**>

 - ##### <**online compile**> [Compile and Execute C Online](http://www.compileonline.com/compile_c_online.php)    2018/6/16 
    - note:  

### _<**WINPC-TOOLS**>

 - ##### <**winpc-tools**> [zhongyang219/TrafficMonitor: 这是一个用于显示当前网速、CPU及内存利用率的桌面悬浮窗软件，并支持任务栏显示，支持更换皮肤。](https://github.com/zhongyang219/TrafficMonitor)    2018/6/16 
    - > Traffic Monitor是一款用于Windows平台的网速监控悬浮窗软件，可以显示当前网速、CPU及内存利用率，支持嵌入到任务栏显示，支持更换皮肤、历史流量统计等功能。



 - ##### <**winpc-tools**> [C - voidtools](https://www.voidtools.com/support/everything/sdk/c/)    2018/6/17 
    - > Make sure to link to Everything32.lib or Everything64.lib.
      > Copy Everything32.dll or Everything64.dll to your programs executable directory.

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




 - ##### <**collect**> [erguotou520/electron-ssr: Shadowsocksr client using electron](https://github.com/erguotou520/electron-ssr)    2018/6/16 
    - note: 
      >  
 

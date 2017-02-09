# CSS2/3样式相关的问题

- [查询样式是否能使用网站](http://caniuse.com/#feat=flexbox)
- [阮一峰css技巧](http://www.ruanyifeng.com/blog/2010/03/css_cookbook.html)
- [《精通CSS 高级Web标准解决方案》](http://baike.baidu.com/link?url=5PsfJ3_QqBxoW9L0sYY6qN3LPHNOqKeatMYq8vswYVe5NUNmjHJvpMTbq96jmxnhD9YmHehDzCpK2_EBFoy1yY6t1i4QlzbLdYT_4sGS-TAiyDWeQCbOvSDCwk4hu295gX2dHimATw2OnxSONO34thnn4blaaqi9TIUanSh8dTQpa53UzETKlfY9VR9bguaSrOhomOEpkp48lQC0sEzItuek4mBXP-SgDHJ39_4y9M_)
# NEC样式规则
[NEC官网](http://nec.netease.com/standard/css-sort.html)

1. 重置（reset）和默认（base）（tags）：消除默认样式和浏览器差异，并设置部分标签的初始样式，以减少后面的重复劳动！你可以根据你的网站需求设置！
统一处理：建议在这个位置统一调用背景图（这里指多个布局或模块或元件共用的图）和清除浮动（这里指通用性较高的布局、模块、元件内的清除）等统一设置处理的样式！

2. 布局（grid）（.g-）：将页面分割为几个大块，通常有头部、主体、主栏、侧栏、尾部等！

3. 模块（module）（.m-）：通常是一个语义化的可以重复使用的较大的整体！比如导航、登录、注册、各种列表、评论、搜索等！

4. 元件（unit）（.u-）：通常是一个不可再分的较为小巧的个体，通常被重复用于各种模块中！比如按钮、输入框、loading、图标等！

5. 功能（function）（.f-）：为方便一些常用样式的使用，我们将这些使用率较高的样式剥离出来，按需使用，通常这些选择器具有固定样式表现，比如清除浮动等！不可滥用！

6. 皮肤（skin）（.s-）：如果你需要把皮肤型的样式抽离出来，通常为文字色、背景色（图）、边框色等，非换肤型网站通常只提取文字色！非换肤型网站不可滥用此类！

7. 状态（.z-）：为状态类样式加入前缀，统一标识，方便识别，她只能组合使用或作为后代出现（.u-ipt.z-dis{}，.m-list li.z-sel{}），具体详见命名规则的扩展相关项。

![image](https://cloud.githubusercontent.com/assets/18028533/21420589/8b3ec0ec-c869-11e6-8d25-38e85f22bbd3.png)

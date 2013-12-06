## Android Dev Libs——RTCommon

RTCommon以Library工程的方式开发，封装了一系列工具方法，包括类型转换、Http请求处理、网络状况验证、图片处理、SD卡操作、对SharedPreference及Toast的封装等，集成了下拉刷新、滑动菜单（SlidingMenu）等第三方控件，后期会持续更新并添加更多的组件，也欢迎大家修改、补充、做贡献！

---
RTCommon is an Android develop libs, encapsulate some common methods, including type convert, http handler, net check, image tools, SD card tools and so on. Otherwise, integrate some third libs just like SlidingMenu and PullToRefreash, welcome to fork and pull request.

#### Installation
1. Fork项目并Clone到本地并导入
2. 右击你的项目并选择Properties-Android-Library
3. 在Library栏目点击Add并添加RTCommon 
4. 完成上述步骤即可在你的工程中使用RTCommon中封装的工具类和第三方组件
5. 使用方法参考示例工程[RTCommonDemo](https://github.com/tangren03/RTCommonDemo)

---
1. Fork and clone RTCommon to your local
2. Right click your project and select Properties-Android
3. Click Add button to choose RTCommon in Library section, or you can import to lib.
4. [RTCommonDemo](https://github.com/tangren03/RTCommonDemo) will tell you how to use RTCommon

#### Structure
以下是工程包结构，分别封装了自定义的Activity及Adapter，另外在db包下对db4o对象形数据库进行了封装，在pulllistview包下对下拉刷新控件进行了封装，utils包下封装各种类型的工具方法，slidingmenu包下是对滑动菜单SlidingMenu的封装。

---
This is the structure of RTCommon

> - -com.ryantang.common.activity
- -com.ryantang.common.adapter
- -com.ryantang.common.db
- -com.ryantang.common.pulllistview
- -com.ryantang.common.utils
- -com.slidingmenu.lib
- -com.slidingmenu.lib.app

#### Notice
- RTCommon工程编码格式为UTF-8
- 工程完善度还有待提升，欢迎补充和修改

---
- RTCommon was encoded by UTF-8
- There is something to improve, welcome to pull request


#### Reference
- [SlidingMenu](https://github.com/jfeinstein10/SlidingMenu)
- [PullToRefreash-ListView](https://github.com/erikwt/PullToRefresh-ListView)
- [DB4O](http://www.db4o.com/)

# 原作者的脚本
- [Install From GitHub](https://github.com/FirefoxBar/userscript/raw/master/Tieba_Blocked_Detect/Tieba_Blocked_Detect.user.js)
- [Install From GreasyFork](https://greasyfork.org/zh-CN/scripts/383981)
# 源项目
* [Tieba_Blocked_Detect(贴吧贴子屏蔽检测)](https://github.com/FirefoxBar/userscript/tree/master/Tieba_Blocked_Detect)
# 作者已修复bug，推荐直接用作者的(屏蔽显示样式没有我的那么刺眼，如果仍需要的话，可以把这个"background: rgba(255, 0, 0, 0.05);"改成"background: rgba(255, 0, 0, 0.3);"https://github.com/FirefoxBar/userscript/issues/20)
# 安装
- [Install From GitHub](https://github.com/shitianshiwa/baidu-tieba-userscript/raw/master/%E8%B4%B4%E5%90%A7%E8%B4%B4%E5%AD%90%E5%B1%8F%E8%94%BD%E6%A3%80%E6%B5%8B/%E8%B4%B4%E5%90%A7%E8%B4%B4%E5%AD%90%E5%B1%8F%E8%94%BD%E6%A3%80%E6%B5%8B(%E9%9D%9E%E5%AE%98%E6%96%B9%E4%BF%AE%E6%94%B91)/%E8%B4%B4%E5%90%A7%E8%B4%B4%E5%AD%90%E5%B1%8F%E8%94%BD%E6%A3%80%E6%B5%8B(%E9%9D%9E%E5%AE%98%E6%96%B9%E4%BF%AE%E6%94%B91).user.js)
# 修改
* 无用户名的贴吧账号无法正常运行此脚本（2019-12-14,原作者已修复bug）
* 修改为只在各个贴吧的主页和主题贴里运行
* https://github.com/shitianshiwa/baidu-tieba-userscript/blob/master/%E8%B4%B4%E5%90%A7%E8%B4%B4%E5%AD%90%E5%B1%8F%E8%94%BD%E6%A3%80%E6%B5%8B/%E8%B4%B4%E5%90%A7%E8%B4%B4%E5%AD%90%E5%B1%8F%E8%94%BD%E6%A3%80%E6%B5%8B(%E9%9D%9E%E5%AE%98%E6%96%B9%E4%BF%AE%E6%94%B91)/%E8%B4%B4%E5%90%A7%E8%B4%B4%E5%AD%90%E5%B1%8F%E8%94%BD%E6%A3%80%E6%B5%8B(%E9%9D%9E%E5%AE%98%E6%96%B9%E4%BF%AE%E6%94%B91).user.js#L5
* https://github.com/shitianshiwa/baidu-tieba-userscript/blob/master/%E8%B4%B4%E5%90%A7%E8%B4%B4%E5%AD%90%E5%B1%8F%E8%94%BD%E6%A3%80%E6%B5%8B/%E8%B4%B4%E5%90%A7%E8%B4%B4%E5%AD%90%E5%B1%8F%E8%94%BD%E6%A3%80%E6%B5%8B(%E9%9D%9E%E5%AE%98%E6%96%B9%E4%BF%AE%E6%94%B91)/%E8%B4%B4%E5%90%A7%E8%B4%B4%E5%AD%90%E5%B1%8F%E8%94%BD%E6%A3%80%E6%B5%8B(%E9%9D%9E%E5%AE%98%E6%96%B9%E4%BF%AE%E6%94%B91).user.js#L6
* 修改了屏蔽显示样式，已避免特殊情况下，导致楼层错位（'position: absolute;'改为'position: relative;''）,加深了屏蔽颜色（2019-12-14,原作者已修复bug，颜色原样）
* https://github.com/shitianshiwa/baidu-tieba-userscript/blob/master/%E8%B4%B4%E5%90%A7%E8%B4%B4%E5%AD%90%E5%B1%8F%E8%94%BD%E6%A3%80%E6%B5%8B/%E8%B4%B4%E5%90%A7%E8%B4%B4%E5%AD%90%E5%B1%8F%E8%94%BD%E6%A3%80%E6%B5%8B(%E9%9D%9E%E5%AE%98%E6%96%B9%E4%BF%AE%E6%94%B91)/%E8%B4%B4%E5%90%A7%E8%B4%B4%E5%AD%90%E5%B1%8F%E8%94%BD%E6%A3%80%E6%B5%8B(%E9%9D%9E%E5%AE%98%E6%96%B9%E4%BF%AE%E6%94%B91).user.js#L165
* https://github.com/shitianshiwa/baidu-tieba-userscript/blob/master/%E8%B4%B4%E5%90%A7%E8%B4%B4%E5%AD%90%E5%B1%8F%E8%94%BD%E6%A3%80%E6%B5%8B/%E8%B4%B4%E5%90%A7%E8%B4%B4%E5%AD%90%E5%B1%8F%E8%94%BD%E6%A3%80%E6%B5%8B(%E9%9D%9E%E5%AE%98%E6%96%B9%E4%BF%AE%E6%94%B91)/%E8%B4%B4%E5%90%A7%E8%B4%B4%E5%AD%90%E5%B1%8F%E8%94%BD%E6%A3%80%E6%B5%8B(%E9%9D%9E%E5%AE%98%E6%96%B9%E4%BF%AE%E6%94%B91).user.js#L157
* 这个会消耗额外的流量，使用wap贴吧的api来判断贴子是否显示（只能判断自己的贴子是否被隐藏）
* 发主题贴或回贴后，屏蔽样式可能会消失，刷新贴吧即可（2019-12-14,原作者已修复bug）
* 发贴后可能会误判断，刷新一下贴吧应该可以解决（2019-12-14,原作者已修复bug）

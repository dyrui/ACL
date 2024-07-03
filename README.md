## ACL4SSR_Online_Full_Mannix.ini

规则转换 的远程配置：

https://github.com/dyrui/ACL/main/ACL_Online_Full.ini
---

### V3

扩展 APP 广告拦截规则，对某些影视/动漫 APP 有加速奇效：

https://raw.githubusercontent.com/zsokami/ACL4SSR/main/BanProgramAD1.list

附 hosts 文件（自动更新）：

https://raw.githubusercontent.com/zsokami/ACL4SSR/main/hosts

---

### V2

自带旗帜 emoji 添加逻辑，原名不包含旗帜 emoji 才添加，原名已包含旗帜 emoji 则不添加

**需去除订阅转换链接中的参数 `emoji=true/false` 才能生效**，参考例子：

`https://api.dler.io/sub?target=clash&udp=true&scv=true&config=https://raw.githubusercontent.com/zsokami/ACL4SSR/main/ACL4SSR_Online_Full_Mannix.ini&url={原订阅链接}`

---

⚠ 重要！每个组名的**空格**后面都添加了一个**隐藏字符 \u200d** 用于防止与节点重名，改名需谨慎

移除
- 📢 谷歌FCM
- Ⓜ️ 微软云盘
- Ⓜ️ 微软服务
- 🍎 苹果服务
- 📲 电报消息
- 🎶 网易音乐
- 🎮 游戏平台
- 📹 油管视频
- 🎥 奈飞视频
- 🌏 国内媒体
- 🌍 国外媒体
- 📺 巴哈姆特
- 🇰🇷 韩国节点
url-test
- 延迟测试链接 http://www.gstatic.com/generate_204 -> https://i.ytimg.com/generate_204
- 间隔时间 300秒 -> 15/30秒
- 容差 50/150毫秒 -> 100/300毫秒

📺 ‍B站 默认选择 🇨🇳 ‍中国

正则匹配大小写、简繁体，更好的匹配中转、IPLC节点

LocalAreaNetwork.list 使用 DIRECT

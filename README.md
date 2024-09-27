# ArknightsAppData

明日方舟CN-简中服部分文件数据。

与官方数据同步。<br/>
![Relative date](https://img.shields.io/date/1727424003?label=Gamedata&nbsp;Updated)&nbsp;&nbsp;&nbsp;![Relative date](https://img.shields.io/date/1726734090?label=Repositories&nbsp;Data&nbsp;Updated)

# 目前支持的
- 当前游戏内大部分文本弹窗提示
- 每次更新更改的文件下载包（dat）

后续可能会添加更多东西，看情况定

# 目录
## hgdata 
### string_map.txt
 游戏内部分字符映射
 
## hgDownload
 游戏更新文件

## torappu_index.txt
 游戏文件哈希数据，同时包括apk数据与补丁数据

## hot_update_list.json
 本地补丁资源列表
 
# 更新记录
 - Sep 9 分离APK数据和补丁数据，更改结构，下次更新删除无用文件（不再另外发布更新记录）
 - Jun 6 因为buff_template_holder在gamedata目录下也有一份，所以删除了此数据。推荐读取gamedata目录下的文件
 - Apr 18 添加每次更新时在HGDownload目录下生成的更新补丁列表
 - Jul 6 停机更新时先获取包体数据后获取补丁数据

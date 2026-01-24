# ArknightsAppData

明日方舟CN-简中服部分文件数据。

与官方数据同步。<br/>
![Relative date](https://img.shields.io/date/1769241595?label=Gamedata&nbsp;Updated)

# 目前支持的
- 当前游戏内大部分文本弹窗提示（I18N）
- 每次更新更改的补丁日志
- 游戏内部分内容的hub列表
- 部分游戏配置（CONFIG）
- 热更界面图片资源
- 部分内容的Prefab数据

# 未来计划
- 暂无


后续可能会添加更多东西，看情况定

# 目录

## hgdata 
 - config：游戏配置
 - premain：热更界面资源
 - i18n：部分游戏内文本提示
 - oth：HUBS
 
## hgDownload
 游戏更新补丁文件列表（以补丁版本为文件名）

## Prefabs
 干员、敌人、装置、召唤物的Prefab数据，由于上游仓库目前为私库，如需访问可以发Issue或在[此Issue](https://github.com/555me/ArknightsAppData/issues/4) 下申请。

## hot_update_list.json
 补丁资源列表，分别为安装包的资源（带有#0字符）和数据更新资源
 
# 更新记录
 - Aug 6：增添部分Prefab仓库跳转
 - Mar 13,2025： 增添活动配置＆热更界面资源，删除已更改打包格式的torappu_index文件
 - Oct 9,2024：增添部分图片hub数据，便于检查yj又增删了什么图片
 - Sep 9 分离APK数据和补丁数据，更改结构，下次更新删除无用文件（不再另外发布更新记录）
 - Jun 6 因为buff_template_holder在gamedata目录下也有一份，所以删除了此数据。推荐读取gamedata目录下的文件
 - Apr 18 添加每次更新时在HGDownload目录下生成的更新补丁列表
 - Jul 6,2023： 停机更新时先获取包体数据后获取补丁数据

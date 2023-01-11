# ArknightsAppData

明日方舟CN-简中服部分文件数据。

与官方数据同步。

# 目前支持的
- 所有Android目录下文件哈希及md5值
- 当前游戏内部分文本弹窗提示
- 游戏内绝大部分BUFF数据

后续可能会添加更多东西，看情况定

# 使用方法
## buffTemplate.txt
 根据干员/敌方/肉鸽buff代号找，代号后的字母数字组合为buff的位置，如s为skill（技能），t为talent（天赋），tr为trait（干员的基础能力），e为equip（模组）
 部分buff为通用buff，命名一般不带代号，所以要自己猜命名，也挺好猜的
 
## string_map.txt
 一般通过版本对比找东西。
 如果你要想知道特定的提示词，我觉得你还是去游戏找比较好
 
## torappu_index.txt
 所有安卓手机数据目录中"/com.hypergryph.arknights/files/AB/Android/"目录下的文件哈希及md5信息，如果有文件修改必定会更改哈希和md5值，可以据此判断有啥文件改了以及<del>看看有无搬公交车的情况</del>。
 

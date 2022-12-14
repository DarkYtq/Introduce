# 这个仓是个人近俩年作品集
1、山海 相关技术
（1）剧情编辑器


<img src="https://github.com/DarkYtq/Introduce/tree/master/Imgs/剧情编辑器.png" width="800" 
alt="剧情编辑器"/>
如图，支持小说文本转换为可视化的节点编辑器，可以自由组合搭配节点走向和游戏表现。

（2）MVC代码导出+读表存档代码导出
<img src="https://github.com/DarkYtq/Introduce/tree/master/Imgs/ViewExport.png" width="800" 
alt="ViewExport"/>
如图，可以快速填充Component的Reference，一键生成View和Controller脚本

<img src="https://github.com/DarkYtq/Introduce/tree/master/Imgs/ConfigExport.png" width="800" 
alt="ConfigExport"/>
如图，可以快速填充生成变量类型，一键生成读表、存档、Model脚本。


（3）战斗AI行为树

<img src="https://github.com/DarkYtq/Introduce/tree/master/Imgs/行为树.png" width="800" 
alt="行为树"/>
如果为消消乐战斗角色搭建行为树。

（4）数值策划配置
经验值曲线根据间隔生成配置表，角色根据六维总数、擅长数值和属性生成六维数值。游戏运行随机根据Rank分配装备，技能等。

（5）美术资源管理

<img src="https://github.com/DarkYtq/Introduce/tree/master/Imgs/美术资源管理.png" width="800" 
alt="美术资源管理"/>
根据美术文件夹一键生成映射表，每个美术资源都有唯一的resId，方便配置和游戏逻辑处理。

<img src="https://github.com/DarkYtq/Introduce/tree/master/Imgs/图集工具.png" width="800" 
alt="图集工具"/>
将大概率出现在同一个界面的图片进行图集打包，提供一键SpriteAtlas和批量修改Sprite属性功能。

---

2、SkyFalling 相关技术
（1）城市编辑器

<img src="https://github.com/DarkYtq/Introduce/tree/master/Imgs/城市生成器.png" width="800" 
alt="城市生成器"/>
根据GridFlow游戏里每个城市不一样的Seed，不一样的美术资源，生成独一无二的城市。

（2）建造系统

参考视频建造系统，可以建造房屋设施，种植药草，养殖小动物。

（3）大地图势力 随机角色、城市、事件

读取势力配置，根据每个城市随机角色数量，分配随机名字、六维数值、随机装备组合独一无二角色。

<img src="https://github.com/DarkYtq/Introduce/tree/master/Imgs/大地图角色.png" width="800" 
alt="大地图角色"/>
每个角色都有行为树管理， 国王根据势力分配不同城市的郡主，郡主分配武将进攻、采集资源、防守城市，普通武将做具体的行为。

（4）剧情编辑
也使用了山海类似的剧情编辑器。

（5）动态合批
每个势力的美术资源用ScriptObject文件管理，使用LowPloy保证每个势力同一个材质球，然后游戏运行中创建MaterialBlocks动态合批。

---

3、BombHappy 相关技术
（1）C#客户端+C#服务器
服务器和客户端使用相同的物理引擎，使用宏处理代码逻辑分离，同一份工程不同的Scene，可以快速迭代开发。

（2）QQ堂+类似喷射3染色机制
QQ堂的炸弹机制使用状态同步， 喷射3染色效果使用ShaderGraph。


---

4、BeatFire 相关技术
（1）根据音乐文件的音乐频率生成关卡。

---

5、其他个人爱好
（1）研究RPG的数值策划

（2）VR游戏（玩+开发）

（3）研究一些看起来好用的Unity插件

（4）PhotoShop 黑白形绘画

（5）学过半年水墨画

（6）Steam游戏+NS游戏+流行的手游

---

6、其他作品集合
链接：https://pan.baidu.com/s/1u6ZksFxl-YefWaA22Mu0uQ?pwd=7777 
提取码：7777 

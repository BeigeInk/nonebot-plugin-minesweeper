# nonebot-plugin-minesweeper

适用于 [Nonebot2](https://github.com/nonebot/nonebot2) 的 扫雷插件


### 安装

- 使用 nb-cli

```
nb plugin install nonebot_plugin_minesweeper
```

- 使用 pip

```
pip install nonebot_plugin_minesweeper
```


### 使用

**以下命令需要加[命令前缀](https://v2.nonebot.dev/docs/api/config#Config-command_start) (默认为`/`)，可自行设置为空**

```
@机器人 + 扫雷 / 扫雷初级 / 扫雷中级 / 扫雷高级
```

可使用 -r/--row ROW 、-c/--col COL 、-n/--num NUM 自定义行列数和雷数；

可使用 -s/--skin SKIN 指定皮肤，默认为 winxp；

使用 “挖开”+位置 来挖开方块，可同时指定多个位置；

使用 “标记”+位置 来标记方块，可同时指定多个位置；

位置为 字母+数字 的组合，如“A1”


或使用 `minesweeper` 指令：

```
minesweeper [-r --row ROW] [-c --col COL] [-n --num NUM] [-s --skin SKIN] [--show] [--stop] [--open POSITIONS] [--mark POSITIONS]
```


### 示例

<div align="left">
  <img src="" width="400" />
</div>


### 特别感谢

- [mzdluo123/MineSweeper](https://github.com/mzdluo123/MineSweeper) Mirai的扫雷小游戏
- [Minesweeper X](http://www.curtisbright.com/msx/) A minesweeper clone with extra features

# 这是一个用于保存路径点的Scarpet
## 用法
- 将sc文件放入`saves/world/script/`文件夹下
- 在minecraft里输入`/carpet setDefault scriptsAutoload`或在`saves/world/carpet.conf`里写下`scriptsAutoload`
- 重新加载存档

## 使用方法
- 输入`/waypoints add <名称> <x> <y> <z> <描述>` 添加一个路径点,其中<x,y,z>可以为相对坐标~,描述和<x,y,z>为选填
- 输入`/waypoints del <名称>` 删除一个路径点
- 输入`/waypoints list` 显示所有路径点
- 输入`/waypoints tp <名称>` 传送到一个路径点，如果你是生存模式，则不予传送
- `/waypoints dashboard` 暂时没有用处，待开发

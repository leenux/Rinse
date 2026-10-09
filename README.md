# Rinse Addon
This addon is very similar to Decursive, it helps with removing debuffs from friendly units. Rinse is optimized for memory usage and also utilizes [SuperWoW](https://github.com/balakethelock/SuperWoW), [nampower](https://github.com/pepopo978/nampower), [ClassicAPI](https://github.com/brues-code/ClassicAPI) and [UnitXP_SP3](https://github.com/allfoxwy/UnitXP_SP3) functions if you have these mods installed.<br>
You can use `/rinse` or `/run Rinse()` in a macro or make a key binding to cleanse without clicking inside GUI.

Other commands:<br>
`/rinse options` - open the options GUI to change settings<br>
`/rinse skip` - open the skip list GUI to add or remove units from the skip list<br>
`/rinse prio` - open the priority list GUI to add or remove units from the priority list<br>

![Rinse](https://github.com/user-attachments/assets/8ede3d8b-7dda-4ccb-96f4-2b69bbb13b05)

## Changelog / 更新日志

### Hide Header: force frame lock / 隐藏标题栏时强制锁定框架

**EN:** When the header is hidden (including on login if that state was already saved), the frame is automatically force-locked and mouse input on the main frame is disabled. This lets clicks pass through transparent areas so they no longer block interaction with the game world. While the header stays hidden, unlock is not allowed; show the header again to unlock and move the frame as usual.

**中文：** 隐藏标题栏（含登录时若已保存为隐藏状态）会自动强制锁定框架，并关闭主框架的鼠标响应，使透明区域可穿透点击，不再挡住对游戏世界的操作。标题栏保持隐藏时无法解锁；重新显示标题栏后可照常解锁并移动框架。

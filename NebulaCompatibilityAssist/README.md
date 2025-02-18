# Nebula Compatibility Assist

Nebula 0.8.14 hotfix:  

- Fix NRE error in `StationUIManager.UpdateStorage`.  
- Load dyson sphere when click on star view on the starmap.  
- Show the diff count of local & remote mod list in chat when client login.  

[Spreadsheet for Nebula compatible mods list](https://docs.google.com/spreadsheets/d/193h6sISVHSN_CX4N4XAm03pQYxNl-UfuN468o5ris1s)  
This mod tries to patch some mods to make them work better in Nebula Multiplayer Mod.  
DSP Belt Reverse Direction, MoreMegaStructure, TheyComeFromVoid, Dustbin are required to install on both client and host.  

<details>
<summary>Supported Mods List (click to expand)</summary>

### [AutoStationConfig](https://dsp.thunderstore.io/package/Pasukaru/AutoStationConfig/)
- Sync station configuration and drone, ship, warper count.   
- Note: AutoStationConfig v1.4.0 is broken in DSP0.9.27.  

### [Auxilaryfunction](https://dsp.thunderstore.io/package/blacksnipebiu/Auxilaryfunction/)
- Sync auto station config functions.  
- Sync planetary item fill (ships, fuel) functions.  

### [BlueprintTweaks](https://dsp.thunderstore.io/package/kremnev8/BlueprintTweaks/)
- Set `useFastDismantle` = false in config file to prevent host from crashing.  

### [Bottleneck](https://dsp.thunderstore.io/package/Semar/Bottleneck/)
- Fixed an error that occurred on the host when the client was using different proliferator settings.  

### [DSPFreeMechaCustom](https://dsp.thunderstore.io/package/appuns/DSPFreeMechaCustom/)
- Free mecha appearance now sync correctly.  

### [DSPMarker](https://dsp.thunderstore.io/package/appuns/DSPMarker/)
- Markers now sync when players click apply or delete button.  
- Fix red error when exiting game ([issue#8](https://github.com/appuns/DSPMarker/issues/8))   
- Fix icon didn't refresh when arriving another planet.  

### [DSPOptimizations](https://dsp.thunderstore.io/package/Selsion/DSPOptimizations/)
- Fix client crash when leaving a system.  

### [DSPStarMapMemo](https://dsp.thunderstore.io/package/appuns/DSPStarMapMemo/)
- Memo now sync when players add/remove icons, or finish editing text area.  

### [DSPTransportStat](https://dsp.thunderstore.io/package/IndexOutOfRange/DSPTransportStat/)
- Client can now see all ILS stations when chaning filter conditions.  
- Client can't open remote station window yet.  

### [Dustbin](https://dsp.thunderstore.io/package/soarqin/Dustbin/)
- Sync dustbin settings for storage box or tank.  
- Fix dustbin toggle position in client.  

### [FactoryLocator](https://dsp.thunderstore.io/package/starfi5h/FactoryLocator/)
- Client can now see info of remote planet (Require Host to install FactoryLocator too).   

### [LSTM](https://dsp.thunderstore.io/package/hetima/LSTM/)
- Client can now see all ILS stations when choosing system/global tab.  

### [MoreMegaStructure](https://dsp.thunderstore.io/package/jinxOAO/MoreMegaStructure/)
- Sync data when player change mega structure type in the editor.  
- Sync data when player change star assembler slider.  

### [PlanetFinder](https://dsp.thunderstore.io/package/hetima/PlanetFinder/)
- Client can now see vein amount and power status on planets not loaded yet. 
- The data is updated everytime client open the window.  

### [SplitterOverBelt](https://dsp.thunderstore.io/package/hetima/SplitterOverBelt/)
- Fix that splitters and pilers put by clients can't reconnect belts.  

### [TheyComeFromVoid](https://dsp.thunderstore.io/package/ckcz123/TheyComeFromVoid/) (WIP)
- Sync config changes: wave start, wave end, timer reduce, difficulty changes.  
- Sync building destoryed event.    
- Sync star cannon fire event.  
- Sync relic add/remove (control by host).  
- Sync enemy ship retarget/destroy/revive event.  
- Sync star fortress.  
- Sync droplet launch by other players.  
Client behavior changes:  
- The battle progress bar now represents (current enemies hp) / (total enemies hp).  
- Add remote planet cannons for factories not loaded yet.  
- Note: Process of battle (ships, droplet) does not synced, only the final results after battle are same. Expect enemies to disappear/reappear abruptly.   

</details>
  
----

# 联机mod扩充模组(热修补丁+兼容支援)

[联机兼容的模组列表](https://docs.google.com/spreadsheets/d/193h6sISVHSN_CX4N4XAm03pQYxNl-UfuN468o5ris1s)  
绿勾=无问题, 蓝勾=需两端皆安装, 红标=有严重冲突  
有些mod和联机模组Nebula multiplayer mod有冲突，可能造成红字错误或预期效果不正确。  
DSP Belt Reverse Direction、MoreMegaStructure、TheyComeFromVoid、Dustbin必须要伺服端和客户端都得安装。  
此模组提供以下mod的兼容支援, 主要是让主机和客户端显示的内容可以一致，或著修復建築不同步的問題:  

<details>
<summary>MOD列表 (点击展开)</summary>

### [AutoStationConfig](https://dsp.thunderstore.io/package/Pasukaru/AutoStationConfig/)
- 同步物流站自动配置  
- 注意：AutoStationConfigv1.4.0 与 游戏版本v0.9.27 不兼容  

### [Auxilaryfunction](https://dsp.thunderstore.io/package/blacksnipebiu/Auxilaryfunction/) [辅助多功能mod](https://www.bilibili.com/video/BV1SS4y1X75n)
- 同步物流站自动配置相关功能  
- 同步一键填充星球上的飞机飞船翘曲器、燃料  

### [BlueprintTweaks](https://dsp.thunderstore.io/package/kremnev8/BlueprintTweaks/)
- 在配置文件中设置 `useFastDismantle` = false 以防止主机崩溃。

### [Bottleneck](https://dsp.thunderstore.io/package/Semar/Bottleneck/)
- 修复客户端使用不同增产剂设定时在主机发生的错误  

### [DSPFreeMechaCustom](https://dsp.thunderstore.io/package/appuns/DSPFreeMechaCustom/)
- 同步免费的机甲外观  

### [DSPMarker](https://dsp.thunderstore.io/package/appuns/DSPMarker/)
- 同步地图标记  
- 修复离开游戏时的错误 ([issue#8](https://github.com/appuns/DSPMarker/issues/8))  
- 修复到达另一个星球标记没更新的bug  

### [DSPOptimizations](https://dsp.thunderstore.io/package/Selsion/DSPOptimizations/)
- 修复客户端离开星系会使游戏崩溃的错误  

### [DSPStarMapMemo](https://dsp.thunderstore.io/package/appuns/DSPStarMapMemo/)
- 同步星球註記  

### [DSPTransportStat](https://dsp.thunderstore.io/package/IndexOutOfRange/DSPTransportStat/)
- 让客户端显示所有星际物流塔的内容  
- 客户端目前无法打开非本地的物流塔  

### [Dustbin](https://dsp.thunderstore.io/package/soarqin/Dustbin/)
- 同步储物仓和储液罐的垃圾桶设置。  
- 修复客户端的垃圾桶勾选框位置。  

### [FactoryLocator](https://dsp.thunderstore.io/package/starfi5h/FactoryLocator/)
- 让客户端能显示远端星球的建物讯息(需求主机也安装mod)  

### [LSTM](https://dsp.thunderstore.io/package/hetima/LSTM/)
- 让客户端显示所有星际物流塔的内容  

### [MoreMegaStructure](https://dsp.thunderstore.io/package/jinxOAO/MoreMegaStructure/) 更多巨构建筑
- 当巨构类型或星际组装厂配方更改时同步资料  
- 修复客户端戴森球电力供给和需求不正确的问题  

### [PlanetFinder](https://dsp.thunderstore.io/package/hetima/PlanetFinder/)
- 让客户端能显示远端星球的资源储量和电力状态  

### [SplitterOverBelt](https://dsp.thunderstore.io/package/hetima/SplitterOverBelt/)
- 让客户端在传送带上放置分流器/集装机时,可以正确地重新连接传送带  

### [TheyComeFromVoid](https://dsp.thunderstore.io/package/ckcz123/TheyComeFromVoid/) [战斗mod-深空来敌](https://www.bilibili.com/video/BV1jR4y1F7t5)
- 测试中，若出现错误可尝试重连。  
- 同步配置：波次开始、波次结束、时间提前、难度改变。  
- 同步建筑破坏事件。
- 同步恒星炮开火事件。
- 同步遗物添加/删除（由主机控制）。  
- 同步敌舰转向/破坏/复活事件。  
- 同步恒星要塞配置。  
- 水滴机制重制: 同步水滴发射事件, 允许非本地星系水滴, 水滴在战斗结束后才会回收。  
- 战斗进度条: 客户端的进度条只会以敌舰血量的比例计算。  
- 新增远端炮塔以让客户端未载入的星球可以发射炮弹/火箭。  
- 注意：战斗过程（舰船，水滴）不会精准同步，只会同步最终结果。敌舰可能会突然消失或重新出现。  

</details>
  
----

<a href="https://www.flaticon.com/free-icons/puzzle" title="puzzle icons">Puzzle icons created by Freepik - Flaticon</a>
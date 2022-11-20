## 介紹 
這是一款策略類塔防遊戲，功能包含購買防禦塔、利用戰術在土地上擺設防禦塔、音量調整、爆炸特效等
## 實作 
用C++ & Allegro寫，有將近50個.cpp及.h檔，主要為Bullet.cpp(子彈功能)、Plane.cpp(我方功能)、Enemy.cpp(敵方功能)、Image.cpp(設定圖片)、start.cpp(開始畫面)、WinScene.cpp(勝利畫面)、LoseScene.cpp(結束畫面)
1. menu : 點選start進入setting
2. setting : 選擇stage 1或stage 2進入遊戲，且可以調整音量音量大小
3. play_stage_1 : 橘色土地為我方土地，提供我方設置防禦塔；藍色為敵方土地，為敵人行動路線，由左上角繞S型到右下角。遊戲初始會擁有150金幣，每打敗一位敵人即能獲得金幣，提供玩家購買四種不同功能防禦塔

![image](https://user-images.githubusercontent.com/56677419/202917163-8f3f5d10-5ef9-4fb0-af68-df1b84de28ea.png)

4. play_stage_2 : 所有土地皆為橘色，代表地圖上所有位置皆能設置防禦塔，不過也代表敵人能在地圖上所有位置出現。敵人從地圖左上角現身，以隨機方式往右下角移
5. win : 打敗所有敵人，生命值>0，即為勝利。按back返回setting
6. lose : 無法打敗所有敵人，生命值<0，即為失敗。按back返回setting
## 附件
主要code及遊戲畫面

# EKplates

## 簡單寫一下FAQ：

1.設定指令是什麼？

這個插件沒有遊戲內設定指令，沒有遊戲內選項，沒有遊戲內的圖形化介面(GUI)控制台，將來也不會有。所有的改動都要編輯Config.lua，如果你要求高度自定義，那就自己改ekplates.lua吧。

2.真的不考慮做一個GUI？

反正我說我不想加也有人機機歪歪，那......幹你老師恁爸不會啦。作者寫給自己用的東西幹麻貼合別人的習慣？

## 關於EKplates

Dawn是個神人，也曾經很高產，但軍團入侵時我真的以為他不更新了，於是有了這個。現在Infinity Plates仍在，而且代碼一如既往地精簡強大。

數字模式姓名版用了超過五年，以後大概也會一直用下去；本插件不提供售後，條形模式的bug修復也永遠不是最優先。

## 更新紀錄
  
* R1.6
  * 更新cvar和inset選項
  * 數字模式的個人資源現在總是在非隱藏狀態時顯示血量，不論是否滿血
  * 整理排版
  * 修正條形模式的光環圖示的錨點
  * 補充幾個控場法術
* R1.5
  * 增加四個CVAR
  * 數字模式的法力值改成百分比而非數值
* R1.4
  * 針對7.2.5 PTR的更新。暴雪超無聊，更名爆破副資源
* R1.3a
  * 快速修復：條形樣式的名字錯位。是的，我又不小心搞爆它了
* R1.3
  * 試著修復載具問題
  * 幹掉boss mod，保留友方只顯示名字的功能，但只在副本外生效
  * 因為太煩了，強制開啟敵方守護者和僕從姓名板
  * 加入m+易爆小球特殊染色
  * 修復數字模式的個人資源會以百分比顯示的問題
  * 現在可以單獨設定姓名板的最大顯示距離，預設45
  * 數字模式現在有施法「條」的選項了
  * 整理config註解
* R1.2
  * 加入點擊穿透選項
  * 幹掉友方非玩家姓名板，但是除了NPC以外，這些CVAR本來應該由用戶自己去開關，所以敵方的你們自己處理吧
  * 光環可以調整字體了
  * 試著幹掉dbm nameplate
  * 待修復: 載具bug
* R1.1
  * 修復增加隱藏姓名選項時捅的漏子會導致記憶體爆炸的問題
  * 強制套用修復掉幀的CVAR
  * 整理Config註解
* R1
  * 噱頭：第一個release

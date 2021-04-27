# 河海大學自動健康打卡 - GUI

## 截圖

![](https://github.com/Xiderowg/HHUHealthCheckinGUI/blob/master/image/formshot.png)

## 功能

* 定時打卡(10~20點)
* 自定義滯後(開始打卡)時間
* 打卡失敗自動重試
* 打卡成功郵件提示
* 縮小化到托盤

## 使用

開啟軟體，輸入學號和密碼，點選最小化按鈕縮小話到托盤，保持程式不退出程式將在每日10~20點之間定時打卡，若打卡不成功將每隔5分鐘重試，直至成功。  

若需要將打卡成功訊息傳送到郵箱中，請在郵箱一欄填寫合法的郵箱，程式使用郵箱伺服器是個小雞，不保證高可用性，若無必要請勿勾選，節約公共資源。

為避免集中在10點5分進行打卡導致郵件丟件，使用者現在可以選擇滯後時間來進行錯峰打卡。將滯後時間設定為X分鐘，程式將會在晚上6點X分開始嘗試打卡。


## 建議

為達到最好的使用體驗，可以選中exe檔案後，右鍵單擊，將此程式新增至開始選單，此後只需在開始選單即可啟動。

![](https://github.com/Xiderowg/HHUHealthCheckinGUI/blob/master/image/addToStartMenu.png)

![](https://github.com/Xiderowg/HHUHealthCheckinGUI/blob/master/image/StartMenuSample.png)


## 更新日誌

- 2020/08/09 完善了程式的異常捕捉機制，新增了滯後時間選項，錯峰傳送郵件避免高峰丟件
- 2020/11/25 新增了開機自啟功能，並對使用者之前的配置進行全部的儲存，以便下次使用（by Juicern）
- 2020/11/28 新增上次打卡之間的配置儲存，以及最佳化功能（by Juicern）

## 其他

遇到程式問題請移步issue，歡迎PR最佳化這個屎一樣的程式碼。

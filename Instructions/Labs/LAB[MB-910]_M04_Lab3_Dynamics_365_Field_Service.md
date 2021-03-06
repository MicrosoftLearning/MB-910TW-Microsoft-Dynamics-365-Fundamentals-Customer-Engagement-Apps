---
lab:
    title: '實驗 4.3： Dynamics 365 Field Service 總整實驗'
    module: '模組 4： 學習 Dynamics 365 Field Service 的基礎知識'
---

模組 4： 學習 Dynamics 365 Field Service 的基礎知識
========================

## 練習實驗 4.3 - Dynamics 365 Field Service 總整實驗

## 實驗情境

ABC 公司專門從事安全設備的製造、銷售、安裝和服務。他們的產品包含室內和室外監控攝影機、濕度和火災感應器、監控服務等項目。 

ABC 公司使用 Dynamics 365 應用程式，與其組織不同區域的所有客戶進行從銷售到服務的互動。 

**銷售和行銷**

ABC 公司透過鎖定目標的行銷活動，直接向住宅客戶行銷。該公司根據客戶所在的城市和其他因素來鎖定目標。行銷素材會透過電子郵件傳送，並根據他們與電子郵件的互動進行相應引導。 

雖然他們有些較小型產品會透過零售商售出，但大多數產品是由內部銷售人員直接售出給客戶。

在內部，他們將焦點放在兩個關鍵區域： 

- **住宅客戶：** 住宅客戶通常正在尋找個別元件，或要購買整個居家解決方案。這些銷售週期一般而言較短，來自社群媒體、網站、推薦或來自潛在客戶的直接連絡。由於住宅客戶通常更關注特定產品或較小型的安裝項目，因此他們的銷售週期通常會持續幾天或幾週。 

- **企業客戶：** 企業賣方將焦點放在需要更專業且能量身打造商務解決方案的客戶上。企業銷售通常透過連結溝通跨越多個位置，而且往往需要多重資源以完成專案。這些銷售週期通常更長，並且有更多移動零件。 

重要的是，ABC 公司的所有賣方在向客戶銷售產品時，無論他們專注於哪個區域，都擁有必要的工具、資源和指引。 

**系統安裝：**

對於購買的安全設備，安裝程序會因所售出之客戶類型而有所不同。 

- **住宅客戶：** 由於住宅安裝通常僅需要不到一天的時間，因此會由內部員工來完成。銷售完成後，系統會建立工單並排程識別的合格技術人員執行安裝。 

- **企業客戶：** 企業部署可能需要數個月時間，並需要專案經理來監督每日作業。這包含建立專案計劃、定義專案團隊和排程資源。 

**服務與支援：**

一旦安裝好系統後，ABC 公司便會提供售後支援。如果客戶有問題，他們則可以連絡客戶支援。有名專員嘗試要與客戶遠端合作來解決他們的問題。如果無法遠端解決他們的問題，支援專員則可以將問題向上呈報至工單，並由合格的現場技術人員加以排程和處理。 

## 目標

通常，ABC 公司會分派現場技術人員到現場，處理三個情境中的其中一個客戶項目。 

- 當購買新的安全性系統而且需要加以安裝時。

- 當支援中心專員無法遠端解決客戶問題時。

- 當客戶連絡人直接用來要求現場服務時。 

最近有名公司客戶 Active Transport, Inc. 連絡您，要求您支援關他們在安全系統上發生的攝影機問題。支援中心的技術人員無法遠端解決他們的問題，所以必須分派現場技術人員。在這個案例中，您要進行以下事項：

- 將案例記錄轉換成工單

- 排程工單

- 使用行動裝置應用程式將工單結案。 

## 實驗設定

  - **預估時間**： 45 分鐘

## 指示

## 練習 1：建立案例並向上呈報至工單 

### 工作 1：建立案例記錄

1. 如果尚未開啟，請開啟 **Dynamics 365 Field Service** 應用程式。 

2. 使用畫面左側的導覽，選取**案例**。 

3. 在**命令列**上，選取**新增**按鈕以建立新案例記錄。

4. 完成新潛在客戶記錄，如下所示：

	- **案例標題：** 攝影機故障

	- **客戶：** Best For You Organics Company

	- **來源：** 電話

	儲存記錄。

5. 選取 **Field Service** 索引標籤

6. 將 **[事件類型]** 欄位設為 **[攝影機故障]**。(建立新項目)

7. 在**命令列**上，選取**儲存後關閉**按鈕，以儲存後關閉案例記錄。 

 

### 工作 2：手動建立工單

我們稍後將回到您建立的案例記錄。下一步，我們來檢查如何手動建立工單記錄。 

 

1. 使用左側的瀏覽介面，選取**工單**。

2. 在 **[命令列]** 選取 **[新增]** 按鈕，以便建立新工單。

3. 完成工單詳細資料，如下所示：

	- **服務帳戶：** Margie's Travel

	**價目表**：Office 365 US (範例)

	- **工單類型：** 服務

	- **應課稅：** 否

	儲存記錄並指派 [主要事件類型]

	- **主要事件類型：** 展開傳送 (建立新項目)

4. 請記下工單號碼，以確保您稍後使用正確的工單。 

5. 選取**設定**索引標籤。

6. 將**服務領域**欄位設為 **WA**。

7. 在**偏好設定**下面，設定時間偏好設定，如下所示：

	- **承諾開始時間：** 今天上午 9:00

	- **承諾結束時間：** 今天上午 11:00

8. 選取**儲存後關閉**，以儲存您的變更並結束新的工單。

 

### 工作 3：從案例產生工單

產生工單的其他方式，即向上呈報案例記錄。在此範例中，我們將向上呈報剛建立的攝影機故障案例記錄。 

 

1. 使用左側的導覽，選取**案例**。 

2. 開啟您剛建立的**攝影機故障**案例。 

3. 在**命令列**上，選取**轉換成工單**按鈕。 

4. 工單建立完成後，選取彈出式畫面上的 **[確定]** 按鈕，以便檢視 [工單] 詳細資料。 

 

您的兩份新建工單都已準備好進行排程。 

## 練習 2：使用 Dynamics 365 Field Service 排程項目  

### 工作 1：直接從工單排程

1. 使用左側的導覽，選取**排程面板**。

2. 在畫面的右上角中，將**新排程面板**經驗設為**開啟**。 

3. 在 **[搜尋資源]** 查詢欄位中輸入「Aidan Knaggs」。 

4. 在需求面板中的畫面底部，選取**未排程的工單**。  (如果沒有顯示需求面板，選取畫面底部的箭頭以展開它。) 

5. 從案例記錄中找到您建立的 **「Munson's Pickles」** 工單。(請記住工單號碼)。 

6. 將 **「Munson's Pickles」** 記錄拖曳並放置在 Aiden 連絡人記錄的開放位置中。 

7. 有時候，您可能需要根據技術人員的時段衝突或其他項目來重新排程工單。這可透過分派人員利用排程面板來輕鬆完成。 

 

### 工作 2：使用排程面板來排程

1. 使用左側的導覽，選取**排程面板**。

2. 使用**搜尋資源**查詢欄位，輸入您的使用者帳戶名稱。(系統應會顯示您的資源記錄。)

3. 在需求面板中的畫面底部，選取**未排程的工單**。  (如果沒有顯示需求面板，選取畫面底部的箭頭以展開它。) 

4. 從案例記錄中找出您建立的 **Active Transport** 工單。(請記住工單號碼)。 

5. 將 **Active Transport** 記錄拖曳並放在您的使用者開放時段中。如果時段與客戶偏好的時段相符，則文字會顯示為綠色。

6. 有時候，您可能需要根據技術人員的時段衝突或其他項目來重新排程工單。這可透過分派人員利用排程面板來輕鬆完成。 

7. 選取排程面板 (位在資源名稱欄上方) 上的搜尋資源方塊，輸入 **「Brady」**，並找到今天稍後為 **「Brady Hannon」** 排程的工單。 

8. **以右鍵按一下**已排程的項目。在顯示的功能表中選取 **[替代資源]**。依序選取 [選取/搜尋] 方塊、資源記錄及 **[重新指派]**。

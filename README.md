# 電腦商城系統

- 項目使用技術：基於Springboot2 + mybatis + bootstrap4

- 項目功能 ：

①登錄、註冊、集成kaptcha驗證碼防止機器人，以及用戶管理(用戶信息的修改)

②分頁處理展示商品信息、支持通過模糊搜索查找相關商品

③購物車相關功能管理(如購物車商品的展示和結算)

④訂單管理頁面可以查看不同狀態訂單以及集成綠界金流支付

⑤收藏界面同樣實現分頁展示用戶收藏商品信息，以及加入收藏、取消收藏和加入購物車

⑥對全部業務方法使用aop攔截計算業務執行時間，為後續優化提供支持

###系統畫面預覽: 

1.登入畫面
![login](https://github.com/yaiiow159/computerstore/assets/39752246/99b02da7-82b4-4e23-a89f-62a85a594fbe) <br><br>

2.註冊畫面
![註冊畫面](https://github.com/yaiiow159/computerstore/assets/39752246/5f4b2af2-f3bb-43a9-94b2-1e39bd51945e) <br><br>

3.首頁畫面
![首頁畫面](https://github.com/yaiiow159/computerstore/assets/39752246/db752e76-fa9a-4ed1-87f8-26fcda1a6358) <br><br>

4.商品畫面 (可點選收藏以及購買)
![商品畫面](https://github.com/yaiiow159/computerstore/assets/39752246/ed7ed34f-709a-4b75-9985-69f88995aa5e) <br><br>

4.1 點選收藏後可進入收藏畫面查看 (可進行取消收藏以及加入購物車動作)
![收藏畫面](https://github.com/yaiiow159/computerstore/assets/39752246/eb3ec321-3beb-49af-a7cd-c50e1eec9821) <br><br>

4.2 購物車畫面 (包含刪除商品 顯示金額 以及顯示數量)
![購物車畫面](https://github.com/yaiiow159/computerstore/assets/39752246/b7b3958a-5037-450d-8296-532bb1aa5ed1)

###個人管理功能介紹 

上傳頭像:
![頭像上船功能](https://github.com/yaiiow159/computerstore/assets/39752246/30a13b7d-c541-44fb-b88b-efc3bdc2efd5) <br><br>

個人資料填寫: (會進行欄位校驗 不符合格式會出現錯誤提示)
![個人資料畫面](https://github.com/yaiiow159/computerstore/assets/39752246/c3a75875-47d1-482f-ae18-7f068206a55b) <br><br>

收貨地址畫面:
![收穫地址圖片](https://github.com/yaiiow159/computerstore/assets/39752246/6776225e-6988-45bc-9ae7-86f08e3762e5)




















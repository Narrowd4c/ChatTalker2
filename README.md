切版任務二ChatTalker
===
[ChatTalker連結]( https://narrowd4c.github.io/ChatTalker2/)
---
https://narrowd4c.github.io/ChatTalker2/

 ## 首頁
- [x] 1. header 的內容也可以嘗試使用 .wrap 限制寬度，可以在設計稿嘗試使用

- [x] 2. 「三大平台，我來搞定」區塊已經有設定 max-width，裡面的 li 寬度，可以使用 % 來設定，調整上會更有彈性.  
          [wrap .fanpage:30%](https://github.com/Narrowd4c/ChatTalker2/blob/main/scss/_index.scss#L71)
- [x] 3. 建議避免使用編號命名（如 .wrap2 .ball-2），因無法由編號了解用途，過一段時間再回頭看也會忘記設定編號的原因，因此建議可以改為加上通用樣式，或是改為語意命名.  
          [wrap2 => pricing-main,  ball-2 => ball-md](https://github.com/Narrowd4c/ChatTalker2/blob/main/scss/_index.scss#L29)
- [x] 4. .feature-card 也可以嘗試設定 box-shadow 樣式.  
          [box-shadow](https://github.com/Narrowd4c/ChatTalker2/blob/main/index.scss#L138)
- [x] 5. 「快速了解客戶輪廓 建立品牌流量池」這裡的文字在 PC 版可以調整為置左排列  
          [text-md-center](https://github.com/Narrowd4c/ChatTalker2/blob/main/index.html#L83)
- [x] 6. .recommend-card 在 PC 版可以設定卡片之間的間距   
          [margin-right:16](https://github.com/Narrowd4c/ChatTalker2/blob/main/scss/_index.scss#L160)
- [x] 7. 按鈕、連結、選單等等可點擊的地方都可以嘗試設定 hover 效果.  
          [opcity:0.8](https://github.com/Narrowd4c/ChatTalker2/blob/main/scss/_utility.scss#L141)
- [x] 8. 部分通用樣式如 w-969、w-909，只有使用在少數特定地方，建議就可以不需另外設定 class 可以和其他樣式寫在一起。  
          [w-969 ,w-909](https://github.com/Narrowd4c/ChatTalker2/blob/main/scss/_index.scss#L29) => pricing-main       


## 方案費用

- [x] 1.「彈性選擇，提供您選擇最適合的方案」區塊可以參考設計稿設定左右 padding，在行動版時整體內容看起來較不會太靠近裝置邊緣.   
         [padding:20. => padding:32](https://github.com/Narrowd4c/ChatTalker2/blob/main/pricing.html#L28)    
- [x] 2. 兩個 .plan-card 是同性質的內容，因此也可以使用 ul li 結構.  
         [ul>li](https://github.com/Narrowd4c/ChatTalker2/blob/main/pricing.html#L36)
- [x] 3. 常見問題選單的 icon 未正確顯示，.faq 可以設定垂直間距.  
         [.faq](https://github.com/Narrowd4c/ChatTalker2/blob/main/scss/_pricing.scss#L82)
- [ ] 4. 頁面縮小時背景圖片太大 預期效果：寬度改變 高度不變     
         [.img-banner](https://github.com/Narrowd4c/ChatTalker2/blob/main/scss/_pricing.scss#L136)

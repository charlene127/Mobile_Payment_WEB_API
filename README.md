# Mobile_Payment_WEB_API
專案-行動支付介接Web API

---部分內容涉及企業資訊安全，因而無法提供檔案或使用隱碼的方式呈現，敬請見諒。

一、專案目的:公司為提供民眾多元化醫療費用支付政策，與PI錢包、醫指付合作開發醫療費用行動支付介接。

二、功能概述:

1.查詢待繳費用 : 
  
  1.1.民眾開啟PI行動錢包APP，掃描繳費單上的條碼後，APP call Web API 查詢待繳費用。
  
  1.2.民眾開啟醫指付APP輸入基本資料並查詢，APP call Web API 查詢待繳費用。 

2.信用卡扣款前的帳務確認 : 
  
  提供行動支付方查詢當下費用狀態。
  
3.付款 :

  PI行動錢包APP/醫指付APP信用卡付款成功後， call Web API 傳入付款結果。
  
三、所負責的項目與使用的技術:

1.醫指付介接Web API : 利用 RESTful Web API以及AES加解密民眾資料，提供行動支付方醫療費用之查詢、確認、付款資料介接。

四、專案成果 : 協助完成PI錢包、醫指付醫療繳費行動支付介接，讓公司可提供民眾多元化繳費工具，改善民眾等候批價繳費時間。

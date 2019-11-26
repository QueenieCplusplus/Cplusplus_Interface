# Cplusplus_Interface
介面

什麼是介面？對應於兩個要作相互溝通的系統，介面可以作為其間共同使用的架構，好比 PC 與 Printer，抑或是 Client APP 與 Servcer APP，這也好比我們將我們使用者的意識與意圖，透過銀幕、鍵盤、滑鼠，並且透過程式碼及其編輯器，將相法轉換成電腦資訊。

舉例來說，設計公有介面：

    interface 由成員函數構成，均為程式設計師所寫。

    public 指的是此類別的程式碼。

    system interact with interface 是由此類別建構出的物件（即實例），能與介面互動。
 
>>>

互動方式

       system 透過 public Func 與 interface 的 private member 互動
       實例        介面（類別公有函數）           類別（私有）物件

>>>

資料的隱藏

              private member 是不允許 User 對其做直接存取的
              
>>

更新資料方法

            類別僅允許使用者即實例透過介面即類別公有函數更新存取類別私有物件
              
              

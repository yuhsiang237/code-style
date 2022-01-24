# Code Style
在這篇中記錄一些寫C#時常見的Code Style。  
只要是支援物件導向的語言基本上也能通用。  

## 常見變數命名規則
在此紀錄常見的程式碼命名規則，讓撰寫時具有一致性、好判斷。

<table>
  <tr>
    <td>項次</td>
    <td>項目</td>
    <td>命名方式</td>
    <td>範例</td>
  </tr>
  <tr>
    <td>1</td>
    <td>類別命名</td>
    <td>名詞+抽象類別名稱</td>
    <td>APIContext、DBContext、ISelectionService、PeopleHandler、MemberTypeEnum</td>
   </tr>
     <tr>
    <td>2</td>
    <td>函式命名前綴</td>
    <td>
      [CRUD]<br>
      建立:Create<br>
      擷取:Search(頁面或定義為搜尋時)、Get(直接抓回特定資料)、Find(從集合中去找資料)<br>
      修改:Update<br>
      刪除:Delete<br>
      [額外]<br>
      狀態判斷:Is<br>
      編碼轉換:Convert<br>
      載入檔案:Load<br>
      顯示隱藏:Show、Hide<br>
      事件:On<br>
      批次:Batch<br>
     </td>
     <td>
      [CRUD]<br>
      建立:CreateMember<br>
      擷取:SearchMember、GetMember、FindMember<br>
      修改:UpdateMember<br>
      刪除:DeleteMember<br>
      [額外]<br>
      狀態判斷:IsMember<br>
      編碼轉換:ConvertMember<br>
      載入檔案:LoadMember<br>
      顯示隱藏:ShowMember、HideMember<br>
      事件:OnClick<br>
      批次:BatchCreateMember<br>
   </td>
   </tr>
   <tr>
    <td>3</td>
    <td>介面命名</td>
    <td>I+類別名稱</td>
    <td>IShapeFactory</td>
   </tr>
   <tr>
    <td>4</td>
    <td>常數</td>
    <td>全大寫</td>
    <td>static readonly double PI = 3.14159;</td>
   </tr>
  <tr>
    <td>5</td>
    <td>
      變數
    </td>
    <td>
      指在函式裡面的變數，採用CamelCase<br>
      [常見]<br>
      布林:is、has<br>
      大小:min、max<br></td>
    <td>
      isName、minDepth、maxDepth
    </td>
   </tr>
  <tr>
    <td>6</td>
    <td>
      類別Field、Properity
    </td>
    <td>
      Field:僅類別內部使用，以_開頭。<br>
      Properity:外部存取，大寫駝峰<br>
    <td>
      <b>Field:</b><br>
      private _name;<br>
      <b>Properity:</b><br>
      public Name {get;set;}<br>
    </td>
   </tr>
   <tr>
    <td>7</td>
    <td>
      泛型
    </td>
    <td>
      T+集合名稱
    <td>
      List<T> TList1
    </td>
   </tr>
</table>

參考資料:https://igouist.github.io/post/2020/07/code-style/


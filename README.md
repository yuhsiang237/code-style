# name-rule
在這repo中記錄常見變數命名的名稱

<table>
  <tr>
    <td>項次</td>
    <td>項目</td>
    <td>命名方式</td>
    <td>範例</td>
  <tr>
  <tr>
    <td>1</td>
    <td>類別Class命名</td>
    <td>名詞+抽象類別名稱</td>
    <td>APIContext、DBContext、ISelectionService、PeopleHandler</td>
   <tr>
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
   </td>
   
</table>



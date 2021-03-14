## Feb 18, 2021
### IDEA plugin 「Spring Assistant」
1. 原開發者已經停止維護，目前IDEA Community edtion 2020.3 無法使用
    + [Spring Assistant IDEA Marketplace](https://plugins.jetbrains.com/plugin/10229-spring-assistant)
    + [Spring Assistant Github](https://github.com/1tontech/intellij-spring-assistant)
    
    ![image](https://github.com/CaliforniaChronic/pics/blob/main/spring-assistant-error-01.png)
    
2. 在IDEA 免費版中application.yml 無法自動補全。不方便使用，也無法測試到自定義starter metadata description 提示運作是否正確
3. 有開發者fork 修復問題，待觀察(經測試功能可用)
    + [eltonsandre/intellij-spring-assistant](https://github.com/eltonsandre/intellij-spring-assistant)

### Eclipse Navigator view is deprecated 
>  reference: [Why is eclipse removing the navigator view?](https://stackoverflow.com/questions/60962386/why-is-eclipse-removing-the-navigator-view)

透過調整Project Explorer 即可以像Navigator View 顯示相同資訊 
1. 打開Project Explorer View，點擊Project Explorer tab 列的Select and deselect filters(漏斗圖案)，或是從View Menu(垂直的那三個小點) 打開選Filters and Customization

![image](https://github.com/CaliforniaChronic/pics/blob/main/Eclipse%20Navigator%20view%20is%20deprecated-01.png)

2. 在"Pre-set filters" 頁箋取消"Java output folders" 選項

![image](https://github.com/CaliforniaChronic/pics/blob/main/Eclipse%20Navigator%20view%20is%20deprecated-02.png)

3. 在"Content" 頁箋取消"Java Elements" 選項

![image](https://github.com/CaliforniaChronic/pics/blob/main/Eclipse%20Navigator%20view%20is%20deprecated-03.png)

這樣子就可以了，但是因為還想看引用的Libraries 資訊，故第3 點保留

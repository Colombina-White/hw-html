1. 關鍵技術：使用 CSS 的 @media 查詢語法。

2. 判斷基準：以瀏覽器視窗的 寬度 (Viewport Width) 作為判斷依據。

3. 具體邏輯：

    當寬度 大於 768px 時，CSS 會套用預設樣式，將 .mobile-view 設為 display: none。

    當寬度 小於或等於 768px 時，媒體查詢觸發，將 .desktop-view 隱藏 (display: none)，並將 .mobile-view 設為 display: block 呈現。

4. 切換功能：手機版額外加入了簡單的 JavaScript showContent 函式，透過修改 DOM 元素的 display 屬性來達成「個人簡介」與「興趣專長」的頁籤切換。
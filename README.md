# jsproxy-material

因為 jsProxy 長期沒有維護, 項目已經存在一些問題, 比如說

- 界面過於原始
- 網站列表中大多數已經無法訪問
- google 會以機器人為由 ban 掉訪客

於是就有了 jsproxy-material.

## Demo

[Demo Site: jsproxy.justin.education](https://jsproxy.justin.education)

以上站點是我通過 CF-Workers + CF-Pages 搭建的, 牆內訪問速度在可接受範圍內.

## 界面美化

> jsProxy

![jsProxy](https://i0.wp.com/justin.education/wp-content/uploads/2021/06/2021060211250751.png?w=1320&ssl=1)

> jsProxy Material

![jsProxy-material](https://i2.wp.com/justin.education/wp-content/uploads/2021/06/2021060211280928.png?w=1320&ssl=1)

## 功能改進

- Material 設計
- 將默認搜索引擎改為 Duckduckgo
- 響應性設計
- 採用 Fontawesome 字體替代網站圖標
- 暗黑模式

**關於 jsProxy 不能保存 cookies, 登錄網站之類的問題, 本項目並沒有解決!**
個人認為 jsProxy 的定位一直是一個 Web2.0 的代理工具, 可以用來看 BBC News, 不適合用來看 Twitter. 因為本人技術有限, 本項目只是改進了原 jsProxy 的體驗, 說白了就是多寫了幾行前端代碼, 並不能解決其餘問題. 如果要尋找可以登錄 telegram、twitter 的代理, 我推薦 [siteProxy](https://github.com/netptop/siteproxy)!

## 如何部署!

1. 參考[原jsproxy](https://github.com/EtherDream/jsproxy/tree/master/cf-worker), 完成部署
2. 將 ASSET_URL 改為 `https://github.com/EtherDream/jsproxy/tree/master/cf-worker`
3. Boom! 配置完成了!

當然你也可以 Clone 此 Repo, 代碼在 gh-pages 分支.

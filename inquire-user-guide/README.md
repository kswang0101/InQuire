# Gitbook

## Theme-default

Gitbook 的預設主題在使用 nginx reverse proxy 下會有問題，因此必須使用修改過的版本。 於 book.json 中的 plugin 指定使用修改過後的主題，但單純這樣做並不會產生主題檔案，目前使用手動方式編譯：

1. 執行 `gitbook install`
2. 到 `./node_modules/gitbook-plugin-theme-default` 目錄下，執行 `npm run prepublish`
3. 執行完成產生 `_assets` 目錄後，便可以執行 `gitbook serve`


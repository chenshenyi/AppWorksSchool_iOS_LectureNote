# How to Contribute

## 推薦文字編輯器 VSCode

[VSCode](https://code.visualstudio.com/) 是一款開源的文字編輯器，支援多種程式語言，並且有豐富的擴充功能，可以安裝 Markdown 的擴充功能，並且有預覽功能，可以即時看到 Markdown 的效果。

- [快速教學](https://ithelp.ithome.com.tw/articles/10290897)
- 推薦安裝的擴充功能
  - Markdown Preview Enhanced
  - Markdown Preview Github Styling
  - Markdown Preview Mermaid Support
  - Markdown Table
  - markdownlint
  - MdTableEditor
  - Mermaid Markdown Syntax Highlighting

## 操作流程

- 先確認已經有設定 `git config`

```bash
git config --global user.name "你的名字"
git config --global user.email "你的 email"
```

- 進入 [GitHub 專案頁面](https://github.com/chenshenyi/AppWorksSchool_iOS_LectureNote)，點選右上角的 `Fork`，將專案複製到自己的帳號下。
- 打開 VSCode
  - 在Start Page 點選 `Clone Git Repository`
  - 點選 `Clone from GitHub`
  - 點選剛剛 fork 的專案
  - 選擇儲存位置，完成後會自動開啟專案。
- 在 VSCode 中依照資料夾分類添加 `.md` 檔案，並且在檔案中寫入內容。
- 寫完後在側邊欄找到 `Source Control`
  - 點選 `+`，將檔案加入暫存區。
  - 輸入 commit message
  - 點選 `✓ Commit`，完成 commit。
  - 再點選  `Sync Changes`，將 commit 推送到 GitHub。
  - 完成後即可在 GitHub 上看到剛剛的 commit。
- 進入 [GitHub 專案pull request頁面](https://github.com/chenshenyi/AppWorksSchool_iOS_LectureNote/pulls)
  - 點選 `New pull request`
  - 點選 `compare across forks`
  - 將 `head repository` 設定為自己的專案
  - 點選 `Create pull request`
  - 輸入標題與內容
  - 點選 `Create pull request`
  - 完成後即可在 GitHub 上看到剛剛的 pull request。

## Markdown 語法

- 教學：[Markdown 語法說明](https://markdown.tw/)
- 進階者可學習 [mermaid](https://mermaid.js.org/intro/) 繪製流程圖。

### Cheat Sheet

- `#` - 標題，`#` 越多字體越小，最多六個 `#`。
- `>` - 引用。
- `-` - 無序清單。
- `1.` - 有序清單。
- `` `...` ``-  單行程式碼。
- `` ```...``` `` - 多行程式碼。
- `*...*` - 斜體。
- `**...**` - 粗體。
- `***...***` - 粗斜體。
- `[Text](URL)` - 連結，`[]` 內為顯示文字，`()` 為連結。
- `![Text](URL)` - 圖片，`[]` 內為顯示文字，`()` 為圖片連結。

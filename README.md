# Xcode-Config

## CodeSnippets
將 `*.codesnippet` 檔案複製到以下路徑：
```
~/Library/Developer/Xcode/UserData/CodeSnippets/
```
說明：[編輯CodeSnippets](#編輯CodeSnippets)

## FontAndColorThemes
將 `*.xccolortheme` 檔案複製到以下路徑：
```
~/Library/Developer/Xcode/UserData/FontAndColorThemes/
```

## KeyBindings
將 `*.idekeybindings` 檔案複製到以下路徑：
```
~/Library/Developer/Xcode/UserData/KeyBindings
```

---

## 編輯CodeSnippets
![https://example.com/images/logo.png](https://github.com/finaltenke/Xcode-Config/blob/main/attachments/demo%20code%20snippets.png)
`&lt;` 表示為 `<`

`&gt;` 表示為 `>` 

---

# Xcode-Templates
xcode 檔案模組

## Templates
將 `*.xctemplate` 檔案複製到以下路徑：
```
~/Library/Developer/Xcode/Templates
```

---
# 腳本
將本地檔案（Xcode配置檔）同步到Git檔案
```
python3 scripts/sync-to-git.py
```

將Git檔案同步到本地檔案（Xcode配置檔）
```
python3 scripts/sync-to-local.py
```
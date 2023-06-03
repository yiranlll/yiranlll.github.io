---
title: "從零開始打造習慣的小狼毫輸入法"
date: 2022-09-02T10:30:28+08:00
draft: true
---

感謝 https://blog.moposx.me/2021/06/05/update-weasel-manually/，本文在其基礎上增加鏈接、具體操作。

1. 更新librime

2. 更新OpenCC

* 轉換庫
無需重新編譯；Download

* 轉換配置和詞典

3. 更新rime-prelude

4. 更新默認配置方案

我只用到luna-pinyin和terra-pinyin（後者用於帶調雙拼輸入法），分別去repo更新文件。注：務必更新此項，否則一定會遇到只能打出擡卻打不出抬字的情況

5. 更新rime-essay

6. 添加語言模型

7. 添加雙拼輸入法並修改
* 開啓語言模型

* 修改
https://github.com/rime/rime-double-pinyin/pull/8

8. 添加emoji支持

https://github.com/rime/rime-emoji

* 修改tips
* 添加至方案

9. 添加詞典

9. 自定義按鍵

10. 自定義皮膚

11. 自定義漢字
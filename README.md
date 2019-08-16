# 自然碼粵拼

配方： ℞ **redchenjs/rime-zijinmaa**

AUR： [rime-zijinmaa](https://aur.archlinux.org/packages/rime-zijinmaa)

[Rime](https://rime.im) 粵語簡拼輸入方案

[香港語言學會粵語拼音方案](https://zh.wikipedia.org/wiki/%E9%A6%99%E6%B8%AF%E8%AA%9E%E8%A8%80%E5%AD%B8%E5%AD%B8%E6%9C%83%E7%B2%B5%E8%AA%9E%E6%8B%BC%E9%9F%B3%E6%96%B9%E6%A1%88)

## 說明

* 本方案借鑑自“自然碼雙拼”（漢語拼音雙拼方案），採用26鍵字母+5鍵數字（67890）佈局，不影響數字鍵（12345）選字。
* 本方案中非入聲字兩鍵輸入，入聲字（-p，-t，-k）三鍵輸入，零聲母字一鍵或者兩鍵輸入（類似“自然碼雙拼”）。
* 本方案支持首字母簡拼及完整拼音提示（僅供參考，多音字註音可能有誤），不支持聲調輸入。
* 本方案可用漢語拼音（使用“\`”鍵）來反查字音。

## 依賴

* [粵語拼音](https://github.com/rime/rime-cantonese)：粵音字、詞庫
* [朙月拼音](https://github.com/rime/rime-luna-pinyin)：拼音反查

## 安裝

[東風破](https://github.com/rime/plum) 安裝口令：
```
bash rime-install redchenjs/rime-zijinmaa
```

授權條款：見 [LICENSE](LICENSE)

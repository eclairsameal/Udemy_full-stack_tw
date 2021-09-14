# html

[html lang=""](https://www.w3schools.com/tags/ref_language_codes.asp)

推薦
[MDN](https://developer.mozilla.org/zh-CN/)

[w3schools](https://www.w3schools.com/tags/att_meta_charset.asp)

## head

[head tags 大全](https://htmlhead.dev/)

## bady

### a - 超連結

```htmlembedded=
<a href="https://bang-dream.bushimo.jp/about/">BanG Dream!（バンドリ!）公式サイト</a>
```

在 head 裡設定 base 可以決定網頁開啟的模式

[<base>: The Document Base URL element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/base)

```htmlembedded=
<base target="_blank"/>
```

### img - 顯示圖片

```htmlembedded=
<img src="./bgd_all.png" alt="bgd image" />
```

alt: 當找不到圖時會顯示設定的說明文字

#### File Path

Absolute: 絕對

Relative: 相對

### 列表

- ul : unordered list(無序清單)

- ol : ordered list(有序清單)

### table - 表格

colspan:擴展 column

rowspan:擴展 row

讓別人方便分辨
thand
tbady
tfoot

## Form

```htmlembedded=
<form action="" method="">
```

method 預設是 get

- get: url 會顯示輸入的資料
- post: url 不會顯示輸入的資料

```htmlembedded=
    <label for="name">Name:</label>
    <input id="name" type="text" name="InputName" />
```

label 跟 input 是成對的，for 跟 id 設成一樣可以方便使用者選取。

name: 將輸入值傳到後台

![](https://i.imgur.com/aEn4oPE.png)

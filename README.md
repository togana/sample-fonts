# sample-fonts

Adobe Fonts と Google Fonts の `font-weight` フォールバック挙動を目視で確認するためのページです。

- Adobe Fonts は **500 / 700** のみ読み込み
- Google Fonts (Noto Sans JP) は **400 / 600** のみ読み込み
- `font-synthesis: none` でブラウザによる合成を抑止

ブラウザの [近接ウェイト代替ルール](https://developer.mozilla.org/ja/docs/Web/CSS/Reference/Properties/font-weight#%E5%A4%AA%E3%81%95%E3%81%AE%E4%BB%A3%E6%9B%BF) により、たとえば `font-weight: 400` 指定時に Adobe 側は 500 にフォールバックする、といった挙動を確認できます。

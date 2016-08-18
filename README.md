# Vazir-Code-Font
A Persian (Farsi) Monospaced Font

<p dir="rtl">
فونت فارسی وزیرکد از نوع Monospaced یا تک فاصله ترکیب شده با فونت Inconsolata
<br />

<a href="http://rastikerdar.github.io/vazir-code-font/">نمایش فونت</a> <br />
<a href="https://github.com/rastikerdar/vazir-code-font/releases">صفحه دریافت (دانلود) بسته فونت شامل فایل های ttf,woff,eot</a> <br />

با تشکر از برنامه <a href="https://fontforge.github.io">FontForge</a><br />

بر مبنای <a href="http://rastikerdar.github.io/vazir-font/">فونت وزیر</a>

</p>


<h1 dir="rtl">
طریقه استفاده در صفحات وب:
</h1>

<p dir="rtl">
کد زیر را در قسمت style یا فایل css وارد نمایید:
</p>


```css
@font-face {
  font-family: Vazir Code;
  src: url('Vazir-Code.eot');
  src: url('Vazir-Code.eot?#iefix') format('embedded-opentype'),
       url('Vazir-Code.woff') format('woff'),
       url('Vazir-Code.ttf') format('truetype');
  font-weight: normal;
}

pre, code {
  font-family: 'Vazir Code', monospaced;
}
```

## Install

Grab the [latest release](https://github.com/rastikerdar/vazir-code-font/releases/latest) file.

Or you can get it on bower:

```
bower install vazir-code-font --save
```

Or [RawGit](https://rawgit.com) CDN:

```html
<link href="https://cdn.rawgit.com/rastikerdar/vazir-code-font/v[X.Y.Z]/dist/font-face.css" rel="stylesheet" type="text/css" />
```

Replace [X.Y.Z] with the latest version (e.g. 1.0.0) and integrate the font into your CSS:

```
font-family: 'Vazir Code', monospaced;
```

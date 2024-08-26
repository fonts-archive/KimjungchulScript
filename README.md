# 김정철손글씨

[배포처 바로가기](http://font.junglim.com/#fontdown)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Kimjungchul Script`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/KimjungchulScript/KimjungchulScript.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/KimjungchulScript/KimjungchulScript.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Kimjungchul Script';
    font-weight: 300;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/KimjungchulScript/KimjungchulScript-Light.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KimjungchulScript/KimjungchulScript-Light.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KimjungchulScript/KimjungchulScript-Light.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KimjungchulScript/KimjungchulScript-Light.ttf') format('truetype');
}
@font-face {
    font-family: 'Kimjungchul Script';
    font-weight: 400;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/KimjungchulScript/KimjungchulScript-Regular.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KimjungchulScript/KimjungchulScript-Regular.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KimjungchulScript/KimjungchulScript-Regular.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KimjungchulScript/KimjungchulScript-Regular.ttf') format('truetype');
}
@font-face {
    font-family: 'Kimjungchul Script';
    font-weight: 700;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/KimjungchulScript/KimjungchulScript-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KimjungchulScript/KimjungchulScript-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KimjungchulScript/KimjungchulScript-Bold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KimjungchulScript/KimjungchulScript-Bold.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/KimjungchulScript/subsets/KimjungchulScript-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/KimjungchulScript/subsets/KimjungchulScript-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "Kimjungchul Script", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
김정철 서체는 개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공, 상업적인 목적을 포함하여 다양한 용도로 사용이 가능합니다. 향후 유료전환을 통한 분쟁의 가능성 또한 없습니다.  

김정철 서체는 본 저작권 안내와 라이선스 전문을 포함해서 다른 소프트웨어와 번들하거나 자유롭게 재배포가 가능합니다. 단, 김정철 서체 자체, 혹은 김정철 서체를 2차 가공한 서체 등을 유료로 판매하는 것은 금지합니다. 이와 같은 유료 판매 시 본 정책 및 저작권법 위반으로 법적인 책임을 질 수 있습니다.  

김정철 서체 라이선스 전문을 포함하기 어려울 경우, 김정철 서체의 출처 표기를 권장합니다. 
김정철 서체를 사용한 인쇄물, 광고물(온라인 포함)의 이미지는 ㈜정림건축의 프로모션을 위해 활용될 수 있습니다. 이를 원치 않는 사용자는 언제든지 ㈜정림건축에 요청하실 수 있습니다. - 문의: 정림건축 대표전화 02_708_8600  

본 라이선스는 상기 조건 중 일부라도 부합되지 않으면 무효가 될 수 있으며, 이는 라이선스를 통한서체 무료 제공 등의 배포 조건이 모두 무효가 됨을 의미합니다.  

어떠한 경우에도 정립건축은 본 폰트 소프트웨어의 사용 또는 이의 사용 불가, 그 밖에 폰트 소프트웨어의 취급과 관련하여 발생하는 모든 계약, 불법행위 혹은 기타 다른 일로 발생하는 일반적, 특수적, 간접적, 부차적 혹은 필연적 손해를 포함하는 소송, 손해, 여타 책임에 대한 의무를 가지지 않습니다.
```

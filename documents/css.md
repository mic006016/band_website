# CSS
## layout

## font
- color: 폰트 색상
  - red, green, darkgreen, #ff0000
- font-family: **글골**
- font-family: "sans-serif(고딕), serif(명조)";
```css
.my-font {
  font-family: "sans-serif";
  font-family: "serif";
  font-family: "pretendard";
}
```
- font-size: 폰트 크기(px, em, rem, vw, vh ...)
- font-weight: 폰트 굵기(normal, bold, bolder ..., 100, 200)
- font-style: normal, italic
- line-height: 줄간(높이)
- letter-spacing: 자간

## inherit(상속)
- font관련은 기본 상속된다.
- text-align: 
- 사이즈, 디자인과 관련된 것(margin, padding, border, background-color)은 상속되지 않는다.

## size
- px
- em
- rem
- vw(반응형때)
- vh(반응형때)
- **width와 height가 주어진 태그에 margin, padding, border를 주면 그 값은 width와 height에 포함되지 않는다**
- margin, height에는 auto나 %가 적용되지 않는다.

## design
- border: 1px solid #f00;
- background-color: #0f0;
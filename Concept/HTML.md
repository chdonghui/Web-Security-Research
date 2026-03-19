# What is HTML?
HTML은 Hyper Text Markup Language의 약자입니다. 텍스트에 링크를 포함하며, 태그나 기호를 통해 정보를 기록할 수 있습니다. 컴퓨터는 이를 해석해서 표현합니다.

### Hyper Text
다른 텍스트에 링크를 포함하는 텍스트입니다. 이 용어는 1965년경 Ted Nelson에 의해 만들어졌습니다.

### Markup Language
마크업 언어는 웹페이지의 구조나 형식을 정의하는데 사용됩니다. 특정한 태그나 기호를 통해서 지시사항이나 정보를 기록합니다. 기록된 정보는 컴퓨터가 해석하여 이를 표시합니다.

## HTML 요소(Element)의 구조 및 형태
![](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Basic_HTML_syntax/grumpy-cat-small.png)

위 그림에서 `<p>`는 여는 태그입니다. 또한, `</p>`는 닫는 태그입니다. `/`가 닫는 역할을 수행합니다. 태그 안에 있는 정보는 `Content`라고 하고 하나의 태그 덩어리를 `Element`라고 합니다.


## 대표적인 HTML 태그
### 링크 태그 `<a>`
대표적인 이미지 태그에는 `<a>` 태그가 있습니다.`href` 속성으로 해당 페이지로 이동할 수 있습니다. 또한 태그 안의 `Content`를 클릭 시 `href`로 설정한 페이지로 이동합니다.

```html
<a href="https://example.com">Website</a>
```
### 이미지 태그 `<img>`
`arc`는 필수이며, 이미지의 경로를 지정합니다. `alt`는 필수는 아니며, 이미지와 텍스트를 설명합니다. 하나의 태그에 닫는 태그까지 포함된 것이 특징입니다.
```html
<img src="이미지 주소" alt="대체 텍스트" />
```

# Reference
- mdn.2026.03.19 Accessed."HTML 시작하기".MDN Web Docs.[URL](https://developer.mozilla.org/ko/docs/Learn_web_development/Core/Structuring_content/Basic_HTML_syntax)
- mdn.2026.03.19 Accessed."Hypertext (하이퍼텍스트)".MDN Web Docs.[URL](https://developer.mozilla.org/ko/docs/Glossary/Hypertext)
- 전학성.2025.10.07 Updated."마크업(Markup)이란 무엇인가?".Wikidocs "AI로 경영하라".[URL](https://wikidocs.net/301895)
- mdn.2026.03.19 Accessed."`<a>`".MDN Web Docs.[URL](https://developer.mozilla.org/ko/docs/Web/HTML/Reference/Elements/a)
- mdn.2026.03.19 Accessed."`<img>`".MDN Web Docs.[URL](https://developer.mozilla.org/ko/docs/Web/HTML/Reference/Elements/img)


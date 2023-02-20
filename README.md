<h1 align='center'>📚 CSS BASIC SYNTAX 📚</h1>

<details><summary><h4>refer</h4></summary>

- [**MDN Web Docs**](https://developer.mozilla.org/ko/)

- [**W3Schools**](https://www.w3schools.com/)

- [**Flexbox Froggy**](https://flexboxfroggy.com/#ko)

- [**1분코딩 (Flex)**](https://studiomeal.com/archives/197)

- [**1분코딩 (Grid)**](https://studiomeal.com/archives/533)

</details>

---

## 📖 CSS

- **CSS란 무엇인가**
  - **정의**
    - **C**ascading **S**tyle **S**heet
    - html 등 마크업 언어로 작성된 문서가 표현되는 방법을 설정하는 스타일 시트 언어
  
  - **`HTML`, `Java Script` 와의 상관관계**
    - `HTML` : 설계도
    - `CSS` : 디자인
    - `Java Script` : 기능

- **구성요소**
  - **선언부**
    - **선택자(selector)**
    
      - 스타일을 적용할 범위를 특정하는 문자
      - id, class, 태그, general 순으로 우선하여 적용됨
  
  - **구현부**
    - **속성(property)**
      - 선택자를 통해 선택된 범위에 대하여 적용하고자 하는 속성
      - `height` (높이), `width` (넓이), `background-color` (배경색), `font-size` (글자 크기) 등
  
    - **값(value)**
      - 선택자를 통해 선택된 범위에 대하여 적용하고자 하는 속성의 구체적인 값
      - `background-color` 의 경우 `red` , `yellow` , `blue` 등

---

## ✅ Selecting & Inheritance

<details><summary><h4>Reference Style</h4></summary>

- **정의**
  - 적용할 스타일을 작성한 코드를 html에서 참조하는 방식
  - inline, internal, external 순으로 우선하여 적용됨
  
- **inline style**
  - html 태그의 `style` 속성값에 css 코드를 작성하는 방식
    
          <p style="property: value;property: value;">
            
            ...
            
          </p>
  
- **internal style**
  - html 문서 `<head>` 태그의 하위 태그 `<style>` 에 css 코드를 작성하는 방식
    
          <head>
            
            ...
              
            <style>
              selector {
                property: value;
                property: value;
              }
            </style>
              
            ...
              
          </head>
  
- **external style**
  - 외부 문서 `*.css` 에 css 코드를 작성하는 방식
  - html 문서 `<head>` 태그의 하위 태그 `<link>` 를 통해 해당 문서를 참조함 
           
          <head>
              
            ...
              
            <link rel="해당 html과 참조할 문서의 상관관계 명시" href="참조할 문서의 경로" />
              
            ...
            
          </head>

</details>

<details><summary><h4>Selector</h4></summary>
  
- **`id` 선택자**
  - html 태그의 속성 `id` 의 값을 통해 특정함
  - 통상적으로는 하나의 항목만 스타일을 적용할 때 사용함
  - 통상적으로는 속성값을 재사용하지 않음
  - css 코드에서는 `#idValue` 로 표현함
  
        #idValue {
          property: value;
          property: value;
        }
  
- **`class` 선택자**
  - html 태그의 속성 `class` 의 값을 통해 특정함
  - 태그가 동일하지 않은 여러 항목에 동일한 스타일을 적용할 때 사용함
  - css 코드에서는 `.classValue` 로 표현함

        .classValue {
          property: value;
          property: value;
        }  
  
- **태그 선택자**
  - html 태그를 통해 특정함
  - css 코드에서는 해당 태그명으로 표현함

        tagName {
          property: value;
          property: value;
        }  
  
- **general 선택자**
  - html 전체를 특정함
  - css 코드에서는 `*` 으로 표현함
  
        * {
          property: value;
          property: value;
        }  

</details>

<details><summary><h4>Inheritance</h4></summary>

</details>

---

## 🎁 Box Model
  
<details><summary><h4>Inline vs Block</h4></summary>

</details>
  
<details><summary><h4>Size</h4></summary>

</details>
  
<details><summary><h4>Blank & Border</h4></summary>

</details>

---

## 📱 LayOut
  
<details><summary><h4>layout property</h4></summary>

</details>
  
---
  
## 💬 etc

<details><summary><h4>Table</h4></summary>

</details>  
  
<details><summary><h4>Font</h4></summary>

</details>

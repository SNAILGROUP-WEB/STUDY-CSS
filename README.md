<h1 align='center'>π CSS BASIC SYNTAX π</h1>

<details><summary><h4>refer</h4></summary>

- [**MDN Web Docs**](https://developer.mozilla.org/ko/)

- [**W3Schools**](https://www.w3schools.com/)

- [**Flexbox Froggy**](https://flexboxfroggy.com/#ko)

- [**1λΆμ½λ© (Flex)**](https://studiomeal.com/archives/197)

- [**1λΆμ½λ© (Grid)**](https://studiomeal.com/archives/533)

</details>

---

## π CSS

- **CSSλ λ¬΄μμΈκ°**
  - **μ μ**
    - **C**ascading **S**tyle **S**heet
    - html λ± λ§ν¬μ μΈμ΄λ‘ μμ±λ λ¬Έμκ° ννλλ λ°©λ²μ μ€μ νλ μ€νμΌ μνΈ μΈμ΄
  
  - **`HTML`, `Java Script` μμ μκ΄κ΄κ³**
    - `HTML` : μ€κ³λ
    - `CSS` : λμμΈ
    - `Java Script` : κΈ°λ₯

- **κ΅¬μ±μμ**
  - **μ μΈλΆ**
    - **μ νμ(selector)**
    
      - μ€νμΌμ μ μ©ν  λ²μλ₯Ό νΉμ νλ λ¬Έμ
      - id, class, νκ·Έ, general μμΌλ‘ μ°μ νμ¬ μ μ©λ¨
  
  - **κ΅¬νλΆ**
    - **μμ±(property)**
      - μ νμλ₯Ό ν΅ν΄ μ νλ λ²μμ λνμ¬ μ μ©νκ³ μ νλ μμ±
      - `height` (λμ΄), `width` (λμ΄), `background-color` (λ°°κ²½μ), `font-size` (κΈμ ν¬κΈ°) λ±
  
    - **κ°(value)**
      - μ νμλ₯Ό ν΅ν΄ μ νλ λ²μμ λνμ¬ μ μ©νκ³ μ νλ μμ±μ κ΅¬μ²΄μ μΈ κ°
      - `background-color` μ κ²½μ° `red` , `yellow` , `blue` λ±

---

## β Selecting & Inheritance

<details><summary><h4>Reference Style</h4></summary>

- **μ μ**
  - μ μ©ν  μ€νμΌμ μμ±ν μ½λλ₯Ό htmlμμ μ°Έμ‘°νλ λ°©μ
  - inline, internal, external μμΌλ‘ μ°μ νμ¬ μ μ©λ¨
  
- **inline style**
  - html νκ·Έμ `style` μμ±κ°μ css μ½λλ₯Ό μμ±νλ λ°©μ
    
          <p style="property: value;property: value;">
            
            ...
            
          </p>
  
- **internal style**
  - html λ¬Έμ `<head>` νκ·Έμ νμ νκ·Έ `<style>` μ css μ½λλ₯Ό μμ±νλ λ°©μ
    
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
  - μΈλΆ λ¬Έμ `*.css` μ css μ½λλ₯Ό μμ±νλ λ°©μ
  - html λ¬Έμ `<head>` νκ·Έμ νμ νκ·Έ `<link>` λ₯Ό ν΅ν΄ ν΄λΉ λ¬Έμλ₯Ό μ°Έμ‘°ν¨ 
           
          <head>
              
            ...
              
            <link rel="ν΄λΉ htmlκ³Ό μ°Έμ‘°ν  λ¬Έμμ μκ΄κ΄κ³ λͺμ" href="μ°Έμ‘°ν  λ¬Έμμ κ²½λ‘" />
              
            ...
            
          </head>

</details>

<details><summary><h4>Selector</h4></summary>
  
- **`id` μ νμ**
  - html νκ·Έμ μμ± `id` μ κ°μ ν΅ν΄ νΉμ ν¨
  - ν΅μμ μΌλ‘λ νλμ ν­λͺ©λ§ μ€νμΌμ μ μ©ν  λ μ¬μ©ν¨
  - ν΅μμ μΌλ‘λ μμ±κ°μ μ¬μ¬μ©νμ§ μμ
  - css μ½λμμλ `#idValue` λ‘ ννν¨
  
        #idValue {
          property: value;
          property: value;
        }
  
- **`class` μ νμ**
  - html νκ·Έμ μμ± `class` μ κ°μ ν΅ν΄ νΉμ ν¨
  - νκ·Έκ° λμΌνμ§ μμ μ¬λ¬ ν­λͺ©μ λμΌν μ€νμΌμ μ μ©ν  λ μ¬μ©ν¨
  - css μ½λμμλ `.classValue` λ‘ ννν¨

        .classValue {
          property: value;
          property: value;
        }  
  
- **νκ·Έ μ νμ**
  - html νκ·Έλ₯Ό ν΅ν΄ νΉμ ν¨
  - css μ½λμμλ ν΄λΉ νκ·ΈλͺμΌλ‘ ννν¨

        tagName {
          property: value;
          property: value;
        }  
  
- **general μ νμ**
  - html μ μ²΄λ₯Ό νΉμ ν¨
  - css μ½λμμλ `*` μΌλ‘ ννν¨
  
        * {
          property: value;
          property: value;
        }  

</details>

<details><summary><h4>Inheritance</h4></summary>

</details>

---

## π Box Model
  
<details><summary><h4>Inline vs Block</h4></summary>

</details>
  
<details><summary><h4>Size</h4></summary>

</details>
  
<details><summary><h4>Blank & Border</h4></summary>

</details>

---

## π± LayOut
  
<details><summary><h4>layout property</h4></summary>

</details>
  
---
  
## π¬ etc

<details><summary><h4>Table</h4></summary>

</details>  
  
<details><summary><h4>Font</h4></summary>

</details>

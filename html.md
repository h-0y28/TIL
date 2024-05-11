
# **HTML?(HyperText Markup Language)**

- 웹 페이지의 구조를 정의하는 마크업 언어

### 구조

- **여는 태그(Opening Tag)**: 요소의 시작 **`<tag>`**
- **내용(Content)**: 요소의 실제 내용
- **닫는 태그(Closing Tag)**: 요소의 끝 **`</tag>`**
- ex)
```html```
    ```html
    <p>hello</p>
    ```
### 속성

- **속성(Attribute)**: 요소에 대한 추가 정보를 제공
- **속성 값(Attribute Value)**: 따옴표로 둘러싸여 있음
- ex)
```html```
    ```html
    <a href="https://www.example.com">Example</a>
    ```

![alt text](image-12.png)

### **문서 구조**

- **`<!DOCTYPE html>`**: 문서의 타입 정의
- **`<html>`**: 전체 HTML 문서를 감싸는 루트 요소
- **`<head>`**: 문서의 메타데이터를 포함
- **`<title>`**: 문서의 제목을 정의
- **`<body>`**: 문서의 본문을 포함

- ex)
```html```
    ```
    <!DOCTYPE html>
    <html>
    <head>
        <title>My HTML</title>
    </head>
    <body>
        <h1>Hello, World!</h1>
        <p>This is a paragraph</p>
    </body>
    </html>
    ```
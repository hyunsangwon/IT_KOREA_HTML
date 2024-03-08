1. block
    - width, height값을 통해 크기를 지정할 수 있다.
    - 별도의 값을 주지 않을 경우 width는 100%가 된다.(margin auto 적용)
    - 세로 배치
        - h1 ~ h6
        - ul,li
        - div, p, form
2. line
    - 별도의 width, height 값을 설정해도 무시.
    - 태그 내부에 내용만큼(자식 크기) 공간을 차지(margin auto 미적용)
    - 가로 배치
        - img, a, span, br
        - select, input, button

3. 선택자
    - 태그 선택자
        ```html
        p{
            font-size : 32px;
        }
        ```
    - class 선택자
         ```html
        .container{
            font-size : 32px;
        }
        ```
    - id 선택자
        ```html
        #container{

        }
        ```
    - 속성 선택자
        ```html
        input[type="password"] {
            /*input*/
        }
        ```
    - 가상 클래스 선택자
        ```html
        div:hover {
            /*커서가 올라가 있는 div 요소*/
        }
        ```
    - 구조 선택자
        ```html
        div:nth-child(1) {
            /*첫번째 자식인 요소를 선택합니다.*/
        }
        ```
4. padding, margin
    - padding : border와 contents 여백 조절
    - margin : border와 border 여백 조절
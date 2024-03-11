0. style 적용 법
    - 인라인
    - style 태그
    - css파일 분리
    
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

3. 크기
    - vw, vh
    - %
    - px
    - em, rem

4. 선택자
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
5. padding, margin
    - padding : border와 contents 여백 조절
    - margin : border와 border 여백 조절
    - 2문제 정도
    
6. position
    - static
    - relative
    - absolute
    - fixed
    - sticky : 스크롤하지 않을 때는 static position 동작, 스크롤할 때는 fixed positon 동작

7. flex
    - container
    - item

8. F12(개발자 도구) 활용법
### 수업 방향

1. 1교시 padding&margin -> position
2. 2교시 Flex
3. 클론코딩 or 문제

#### docs

- https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- flex 틀에주는 css, 아이템에 주는 css
- no-wrap(default), wrap, wrap-reverse
- align-item (normal, center, start, end, stretch)
- justify-content

#### 수업내용

static은 요소를 문서 흐름에 따라 배치합니다. 이것은 기본 값입니다.

```css
div {
  position: static;
}
```

relative는 요소를 자기 자신의 기본 위치(static인 경우)를 기준으로 이동시킵니다. 다른 요소에게는 영향을 미치지 않습니다.

```css
div {
    position: relative;
    top: 10px; /_ 위로 10px 이동 _/
    left: 20px; /_ 왼쪽으로 20px 이동 _/
    }
```

absolute는 요소를 가장 가까운 부모 요소 중 position이 relative, absolute, 또는 fixed인 요소를 기준으로 배치합니다. 부모 중에 해당하는 조상이 없다면 문서(body)를 기준으로 합니다.

```css
div {
  position: absolute;
  top: 30px;
  left: 50px;
}
```

fixed는 요소를 뷰포트(브라우저 창)를 기준으로 배치합니다. 스크롤이 되어도 화면에 고정됩니다.

```css
div {
  position: fixed;
  bottom: 0;
  right: 0;
}
```

sticky는 요소를 부모 요소 중 스크롤되기 전까지는 relative로 취급하고, 스크롤이 특정 위치에 도달하면 fixed처럼 동작하게 만듭니다.

```css
div {
  position: sticky;
  top: 0;
}
```

이러한 position 값들을 적절히 사용하면 웹페이지의 레이아웃을 더 유연하게 설계할 수 있습니다.

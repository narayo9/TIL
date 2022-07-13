# css scroll snap이란 무엇이고, 쓰지 말아야 할 이유


## css scroll snap
- 공식 문서: https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-snap-type
- 흔히 말하는, 딱딱 걸리는 스크롤
  - 주로 [full page scroll page](https://alvarotrigo.com/fullPage/ko/)나 carousel 등에 사용됨.

## why not to use

논점 1. content가 viewport보다 클 때 애매하다.

- https://alvarotrigo.com/blog/why-not-to-use-css-scroll-snap/

논점 2. controlled components를 만들기 어려움.

- https://stackoverflow.com/a/57533033
- scroll position을 watch하는 방식으로 사용.


## 결론

쓸만할 듯. 언급된 edge case 들만 아니라면 꽤 쓸만하고. [caniuse](https://caniuse.com/?search=scroll-snap-type)도 꽤 올라왔다.

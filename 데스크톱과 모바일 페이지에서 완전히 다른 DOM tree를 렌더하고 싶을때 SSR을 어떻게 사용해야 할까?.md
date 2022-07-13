# 데스크톱과 모바일 페이지에서 완전히 다른 DOM tree를 렌더하고 싶을때 SSR을 어떻게 사용해야 할까?

[thread](https://github.com/vercel/next.js/discussions/13356)

1. SSG시 모든 DOM을 렌더하고 media query를 이용해 바꾸는 방법
2. SSG시 null을 렌더하고 CSR / js로 detection 하는 방법

- 스레드의 결론: 완전한 정답은 없지만, 2. 불필요한 최적화일 수 있다.
- CSR이 반드시 가장 무거운 작업은 아니다.
- 일반적으로 1의 first meaningful paint가 더 무거울 것이다.
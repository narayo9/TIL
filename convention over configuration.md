# Convention over configuration

- 과거 rails가 채택하면서 많은 가치를 얻게 만들었던 꽤 오래된 개념이다.
  - 기본 설정값을 충분히 잘 제공해 configure할 필요를 없게 만드는 것.
  - 가령 모델명은 PascalCase로 사용하고, 이에 대응되는 db 테이블 명을 snake_case로 지정함으로써 이를 설정하는 많은 코드를 지울 수 있다.

- 현대에는 zero config라는 용어를 더 많이 쓰는 듯.
  - https://vercel.com/blog/zero-config

- 자유도를 낮게 만들 수 있다. 프론트엔드에서는 특히 중복, 길어지는 코드가 실제 비즈니스 로직과 더 잘 맞고, 엣지 케이스를 잘 대응할 수 있는 경우가 생긴다고 생각.
## bundle의 사이즈를 줄이려면 어떻게 해야하나요??

### default import 를 사용합니다.

default import 와 global import 했을 때 가져오는 파일 사이즈가 다릅니다.

### Code Split

바로 가져올 필요가 없는 코드는 dynamic import 로 변경을 합니다. chunk loading을 비동기적으로 실행하여 필요할 때만 불러와 bundle size를 줄일 수 있습니다.

## 크기가 큰 library 를 대체하는 방법도 있다.

번틀 사이즈 분석하는ㄴ 라이브러리가 있는데 이름은 생각은 나지 않지만 bundle-analyzer 인가 암튼 그거를 사용하여 번들 사이즈를 분석을 합니다.
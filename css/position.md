## position을 어떻게 사용하나요?

> position 속성은 HTML 문서 상에서 요소가 배치되는 방식을 결정합니다.

## position: static

> position 속성을 별도로 지정을 해주지 않으면 기본값인 static 이 적용이 됩니다. position 속성이 static인 요소는 HTML 문서 상에서 원래 있어야하는 위치에 배치됩니다.

## position: relative

> position 속성을 relative 로 설정하게 되면, 요소를 원래 위치에서 벗어나게 배치할 수 있게 됩니다. 다시 말해, 요소를 원래 위치를 기준으로 상대적으로 배치해준다고 생각하면 이해가 쉽습니다.

## position: absolute

> position 속성이 absolute 일 때 해당 요소는 배치 기준을 자신이 아닌 상위 요소에서 찾습니다.position 속송이 static이 아닌 첫번째 상위 요소가 해당 요소의 배치 기준으로 설정되는데요. 만약에 해당 요소 상위에 position 속성이 static이 아닌 요소가 없다면, DOM 트리에 최상위에 있는 body 요소가 배치 기준이 됩니다.

## context API 에 대해 설명해주세요.

Context API를 이용하면 단계마다 일일이 props를 넘겨주지 않고도 컴포넌트 안에서 전역적으로 데이터를 공유할수 있습니다.

단점으로는 context api 에서 상태값을 변경하면, provider 로 감싼 모든 자식 컴포넌트들이 리렌더링됩니다. 해결책으로는 useMemo를 통해 Provider의 value props를 메모이제이션 하는 방법 등이 있습니다.
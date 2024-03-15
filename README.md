# React + Vite Context

컴포넌트간의 데이터를 전달하는 또 다른 방법
기존의 Props가 가지고 있던 단점을 해결할 수 있음

Props 단점
Props는 부모 -> 자식 으로만 데이터를 전달할 수 있었음<br>
부모 -> 자식1 -> 자식2 일때 부모에서 자식2로 바로 Props 전달 불가능

부모요소 밑에 자식 밑에 자식 밑에 자식 밑에... <-- 이런경우를 Props Drilling 이라고 함

React Context => Props Drilling 문제 해결

Context = 데이터 보관소(객체)


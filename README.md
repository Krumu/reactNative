# reactNative


### 난관1 : checkbox 기능구현


목표: hook의 state를 이용하여 각 카테고리에 해당하는 checkbox의 기능을 구현하기
문제: 다른 체크박스를 체크하면 체크했었던 체크박스가 체크가 풀리는 현상이 발생

문제 발생이유: 밤이 늦어서 자고일어나서 확인

해결방법: state와 setState 개념을 완벽히 이해(https://www.youtube.com/watch?v=CowLAnmhxMY)

현재 겪고 있는 문제:

1. 분명 ios에서도 지원하는 checkbox tool인데, ios에서는 오류가 남
2. 각각의 카테고리의 우선순위를 변경하기위해서 draggable tool을 이용해야하는데 예시가 이해되지않음(https://www.npmjs.com/package/react-native-draggable-flatlist)
->  이해하기위해서 typescript공부를 해야함

다음 목표:
1. 전체선택 체크박스를 선택하면 모든 요소들의 체크박스가 체크되는 기능 구현
2. 하나의 요소라도 체크박스가 해제되면 전체선택 체크박스의 체크가 해제되는 기능 구현
3. 네비게이션바 없애기

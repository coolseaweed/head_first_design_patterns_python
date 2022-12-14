
## 반복자 & 컴포지트 패턴 핵심정리

- 반복자를 사용하면 내부 구조를 드러내지 않으면서도 클라이언트가 컬렉션 안에 들어있는 모든 원소에 접근하도록 할 수 있다.

- 반복자 패턴을 사용하면 집합체를 대상으로 하는 반복 작업을 별도의 객체로 캡슐화 할 수 있다.

- 반복자 패턴을 사용하면 컬렉션에 있는 모든 데이터를 대상으로 반복 작업을 하는 역할을 컬렉션에서 분리할 수 있다.

- 반복자 패턴을 쓰면 반복 작업에 똑같은 인터페이스를 적용할 수 있으므로 집합체에 있는 객체를 활용하는 코드를 만들 때 다형성을 활용할 수 있다.

- 한 클래스에는 될 수 있으면 한가지 역할만 부여하는 것이 좋다.

- 컴포지트 패턴은 개별 객체와 복합 객체를 모두 담아 둘 수 있는 구조를 제공한다.

- 컴포지트 패턴을 사용하면 클라이언트가 개별 객체와 복합 객체를 똑같은 방법으로 다룰 수 있다.

- 복합 구조에 들어있는 것을 구성요소라고 부른다. 구성 요소에는 복합 객체와 잎 객체가 있다.

- 컴포지트 패턴을 적용할 때는 여러 가지 장단점을 고려해야한다. 상황에 따라 투명성과 안정성 사이에서 균형을 찾아야 한다.



## 테스트
```
python chapter_09/iterator/main.py
python chapter_09/composite/main.py
```

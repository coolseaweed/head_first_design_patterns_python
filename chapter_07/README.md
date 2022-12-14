
## 어댑터 & 퍼사드 패턴 핵심정리

- 기존 클래스를 사용하려고 하는데 인터페이스가 맞지 않으면 어댑터를 쓰면 된다.

- 큰 인터페이스와 여러 인터페이스를 단순하게 바꾸거나 통합해야 하면 퍼사드를 쓰면 된다.

- 어댑터는 인터페이스를 클라이언트에서 원하는 인터페이스로 바꾸는 역할을 한다.

- 퍼사드는 클라이언트를 복잡한 서브시스템과 분리하는 역할을 한다.

- 어댑터를 구현할 때는 타깃 인터페이스의 크기와 구조에 따라 코딩해야 할 분량이 결정된다.

- 퍼사드 패턴에서는 서브시스템으로 퍼사드를 만들고 진짜 작업은 서브클래스에 맡긴다.

- 어댑터패턴에는 객체 어댑터 패턴과 클래스 어댑터 패턴이 있다. 클래스 어댑터를 쓰려면 다중 상속이 가능해야 한다.

- 한 서브시스템에 퍼사드를 여러개 만들어도 된다.

- 어댑터는 객체를 감싸서 인터페이스를 바꾸는 용도로, 데코레이터는 객체를 감싸서 새로운 행동을 추가하는 용도로, 퍼사드는 일련의 객체를 감싸서 단순하게 만드는 용도로 쓴다.



## 테스트
```
python chapter_07/adapter/main.py
python chapter_07/facade/main.py
```

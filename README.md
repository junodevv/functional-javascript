# functional-javascript
인프런 | 함수형 프로그래밍과 JavaScript ES6 + 응용 강의 정리 및 실습 레포지토리

## 강의 링크
 - [인프런, 함수형 프로그래밍과 Javascript ES6+ 응용편, 유인동님](https://www.inflearn.com/course/함수형_ES6_응용편)

<details markdown="1">
    <summary>강의 목록</summary>

1. 이터러블 프로그래밍 혹은 리스트 프로세싱 (Lisp)
    1. 들어가며
    2. 홀수 n개 더하기
    3. if를 filter로
    4. 값 변화 후 변수 할당을 map으로
    5. break를 take로
    6. 축약 및 합산을 reduce로
    7. while을 range로
    8. 효과를 each로 구분
    9. 추억의 별 그리기
    10. 추억의 구구단
2. 명령형 습관 지우기 - 만능 reduce? No!
    1. reduce + 복잡한 함수 + acc 보다 map + 간단한 함수 + reduce
    2. reduce 하나 보다 map + filter + reduce
    3. query, queryToObject
3. 안전한 합성에 대해
    1. map으로 합성하기
    2. find 대신 L.filter 써보기
4. 객체를 이터러블 프로그래밍으로 다루기
    1. values
    2. entries
    3. keys
    4. 어떠한 값이든 이터러블 프로그래밍으로 다루기
    5. object
    6. mapObject
    7. pick
    8. indexBy
    9. indexBy 된 값을 filter 하기
5. 객체지향과 함께 사용하기 - 사용자 정의 객체를 이터러블 프로그래밍으로
    1. Map, Set, NodeList
    2. Model, Collection 클래스 만들어서 이터러블 프로토콜 지원하기
    3. Product, Products - 메서드를 함수형으로 구현하기
6. 시간을 이터러블로 다루기
    1. range와 take의 재해석
    2. takeWhile, takeUntil
    3. 자동차 경주 - 할 일들을 이터러블(리스트)로 바라보기
    4. 아임포트 결제 누락 처리 스케쥴러 - API 설명
    5. 아임포트 결제 누락 처리 스케쥴러 - 결제된 내역 가져오기
    6. 아임포트 결제 누락 처리 스케쥴러 - 가맹점 DB의 주문서 가져오기
    7. 아임포트 결제 누락 처리 스케쥴러 - 비교 후 결제 취소 API 실행하기
    8. 아임포트 결제 누락 처리 스케쥴러 - 반복 실행하기
7. 프론트엔드에서 함수형/이터러블/동시성 프로그래밍
    1. ES6 템플릿 리터럴 활용
    2. 이미지 목록 그리기
    3. 아이템 지우기
    4. 커스텀 confirm 창과 Promise
    5. 클래스를 대신 함수로 하는 추상화
    6. 이미지 동시성 다루기
    7. 동시성 부하 조절
    8. 고차 함수로 더 작게 나누어 재사용성 높이기 - 데이터형 없애기
    9. 상위 스코프 변수를 사용하는 함수와 아닌 함수들 쪼개기
    10. DOM을 다루는 고차 함수
</details>


### 참고
- fx.js: 지식공유자분께서 만든 라이브러리, ES6에 최적화된 함수들이 정의되어있다.
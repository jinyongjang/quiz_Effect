# Quiz Effects
-------------------------------

![quizEffects 썸네일이미지](/img/quiz-site.PNG)

##### 여러가지 유형의 퀴즈페이지(주관식, 객관식, 문제 차례대로, 여러개 ...)를 만들었습니다.
##### CBT유형은 json 형식으로 시험문제를 저장하여 불러와 문제를 출력했습니다.

### 완성된 site 주소 : [QuizEffects][quizlink]
[quizlink]: https://jinyongjang.github.io/web2023/javascript/quiz/quizEffect07.html

------------------------------
## 사용 스택
- json 형식의 데이터를 fetch로 불러와 출력했습니다.
- javascript의 push와 join메서드를 사용했습니다.
- html, css 를 사용하여 기본적인 페이지를 구성했습니다.

-----------------------------------
## JSON
JSON(JavaScript Object Notation)은 데이터를 저장하거나 전송할 때 자주 사용되는 경량의 데이터 교환 형식입니다. 사람이 읽고 쓰기 쉽고, 기계가 파싱하고 생성하기도 쉽습니다.

JSON은 두 가지 구조를 기본으로 합니다:

- 이름/값 쌍의 집합 (예: { "name":"John", "age":30, "city":"New York" })
- 값의 순서화된 리스트 (배열) (예: ["apple", "banana", "cherry"])

JSON은 자바스크립트의 객체 리터럴 문법을 기반으로 하지만, 자바스크립트 전용이 아닙니다. 많은 프로그래밍 언어에서 JSON 포맷의 데이터를 읽고 쓸 수 있는 기능을 제공합니다.

일반적으로 JSON은 서버와 클라이언트, 또는 서버와 서버 간에 데이터를 주고받을 때 사용되며, 대부분의 웹 API에서도 기본 데이터 형식으로 사용됩니다.
JSON은 XML 등 다른 데이터 교환 형식에 비해 가볍고 코드로 다루기 간편하여 많이 사용되고 있습니다.

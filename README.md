# Clone the Momentum

> [모멘텀](https://momentumdash.com/)을 클론한 본 프로젝트는 NomadCoders를 참고하여 만들었습니다.
> https://academy.nomadcoders.co/courses/category/KR

---

#### 개발 환경
- Vanilla Javascript(ECMAScript6)
- Tomcat(9.0.14.0)
- Intellij IDEA

크롬의 인기 확장프로그램인 Momentum을 클론한 프로젝트이며, **Vanilla Javascript** 공부를 목적으로 둡니다.

---

#### 기능
- LocalStorage를 사용하여 데이터를 get, set 하기



```
let storage = localStorage;
 
storage.setItem('item','value');
 
storage.getItem('item'); // value
 
storage.item; // value
```

- setInterval() 함수를 사용하여 실시간 Time 보여주기
- [OpenWeatherMap API](https://openweathermap.org/)를 사용한 날씨(온도) 가져오기

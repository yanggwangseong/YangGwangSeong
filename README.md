<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:000428,100:004e92&height=200&section=header&text=GwangSeongYang&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Hello%20World&descAlignY=60&descSize=20&descColor=d1d1e9" width="100%" />

  <a href="https://github.com/devxb/gitanimals">
    <img src="https://render.gitanimals.org/farms/{yanggwangseong}" width="600" />
  </a>
</div>



![snake gif](https://github.com/yanggwangseong/yanggwangseong/blob/output/github-contribution-grid-snake.svg)

# GwangSeong Yang 👋



[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=YangGwangSeong&layout=compact&theme=radical)](https://github.com/YangGwangSeong/github-readme-stats)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=YangGwangSeong&show_icons=true&theme=radical)

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=soawn83)](https://solved.ac/soawn83/)



## About 🙋‍♀️
<!--
- Life
일상 생활에서 겪고 있는 문제를 
- 개발 방법론
개인적으로 생각하는 priority
1. Performance-Driven Development(PDD)
  - CPU Intensive
  - I/O Intensive
  - Memory
    - heap memory
    - GC
    - page fault
    - Locality
  - event-loop
  - disk
    - IOPS (Input/Output Operations Per Second)
  - CPU context switching 
  - Network
    - 지연
    - 패킷손실
    - 종단간 처리율
  - Database
    - 인덱스 
    - 쿼리 최적화
  - 라이브러리 동작원리와 문제 추적 최적화
    - 필수 라이브러리들을 사용하고자 하는 기능에 대해서 동작 원리와 이슈가 있다면 해당 이슈를 추적 하고 최적화 합니다.
    - AWS-SDK-JS (O)
    - multer와 s3 (O)
    - TypeORM (O)
    - typeorm-extension (O)
    - mysql2 (O)
    - @nestjs/jwt, jsonwebtoken (O)
    - NestJS
    - class-transformer
    - class-validator
    - 기술을 도입하기 위한 Node.js에서는 보통 커뮤니티 라이브러리를 많이 사용하는데 
    - 예를 들면 Redis 도입을 위해 ioredis 라이브러리를 사용하는데 공식문서에서 추천 한다고 무조건 사용 하는것은 다른 side-effect를 가져온다.
    - 그래서 라이브러리를 도입하거나 선택 할 때 공식문서에서 추천 하는것을 선택하되 동작 원리와 과정을 이해하고 어떤 부분에서 문제가 발생하는지와 최적화 방법에 대해서 고민하고 도입해야한다.
2. TDD, BDD, DDD
   - 1번 PDD가 어느정도 time-point가 고원지대(Plateau)를 형성하게 되면 자유롭게 TDD, BDD, DDD를 섞을 수 있다.
   - 즉, PDD가 숙달된 상태에서 TDD를 진행 하는 것이다.
3. Architecture
   - REST 원칙 중 Layered system만 만족 시키는것을 목적에 둔다.
   - Layered Archietecture를 통해서 OOP 핵심 요소인 OCP를 만족하는 추상화와 객체의 역할, 책임, 협력, 메세지 등을 기반으로 작성한다.
   - OCP를 만족하는 컴파일 의존성과 런타임 의존성이 다르게 추상화를 해두었다면 헥사고날 아키텍쳐든 클린 아키텍쳐든 변경 하는데 큰 어려움이 없게 만드는게 핵심이다.
   - 또한 이러한 추상화는 ORM이 바뀌어도 OCP를 만족 해야한다.
   - 객체의 역할, 책임, 협력, 메세지등을 기반으로 OOP으로 작성 하였다면 service 레이어를 usecase로 바꾸거나 usecase를 추상화 했을 때 어려움이 없어야 한다.
4. OOP
   - 객체라는것을 클래스라고 생각하는 고정관념에서 벗어나야 한다.
   - 절차지향과 객체지향에 대해서 이해해야 한다.
     - OOP로 하고 있는줄 알았는데 실제로 절자지향일 수 있다.
   - 상속,합성,믹스인에 대해서 이해
     - 상속, 합성, 믹스인에 대해서 특징과 차이점에 대해서 이해해야 한다.
     - 상속의 안티패턴에 대해서 이해해야 하고 개선하기 위해서 합성을 어떻게 써야 하는지 이해해야 한다.
   - OOP SOLID를 암기하듯이 이해하면 안된다.
     - 예를들어 OCP는 개방 폐쇄의 원칙입니다! 이런식으로 이해하게 되면 해당 원칙을 코딩 할때 굉장히 힘들다.
     - 나는 런타임 의존성과 컴파일 의존성이 다를 때 OCP를 만족한다고 이해하고 실제로 이렇게 적용 했을때 폐쇄 즉, 다른 코드를 수정하지 않을 수 있었다.
   - 디자인 패턴
     - 디자인 패턴이라는것을 특정 정의와 해당 분류에 대해서 집착해서 작성 하면 안된다.
     - 디자인 패턴이 왜 등장 했는지 주목 해보면 결국 어떻게 객체를 효율적으로 작성하고 누구나 이해할 수 있는 정형화된 스팩을 정의해서 다른 개발자과의 소통이 목적이라고 생각한다.
     - https://refactoring.guru/ko/design-patterns 해당 유명한 너구리 사이트의 디자인패턴으로 개념정도만 이해하는게 좋다고 생각한다.
     - 무수히 많은 디자인 패턴들을 공부하면서 이걸 언제 어떻게 사용 해야 되는지 생각 해보는것도 좋은 방법일 수 있지만 실제 업무에서 해당 디자인 패턴들을 바로 떠올리는것은 쉽지 않다.
     - 개인적인 나의 생각으로는 자신이 사용하는 언어의 프레임워크나 라이브러리들의 코드들을 참고하면 이러한 고급 개발자들이 왜 이러한 패턴을 썼는지 이때 이런걸 써야 하는구나라는 감이 조금씩 생기는것 같다.
5. Observability
   - 프로덕션 레벨에서 가장 중요하다.
***

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fyanggwangseong%2Fhit-counter&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

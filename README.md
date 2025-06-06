# 5주차 미션: Next-Netflix 🎬🍿

## 서론

안녕하세요, 프론트 운영진 **지민재**입니다! 🩷🥰

이번 주부터는 새 프로젝트인 **Netflix 클론코딩**을 진행합니다! 

이번 미션에서는 **Next.js**를 활용해 **SSR(Server Side Rendering)** 을 직접 경험해보고, 주어진 **Figma 디자인**을 활용해 스타일링 하는 방법을 이해하는 것을 목표로 합니다.

또한 이번 주부터는 프론트 페어와 함께하는 첫 과제인 만큼, 팀별로 미리 **호흡**을 맞춰볼 수 있는 좋은 기회가 될 것 같습니다.

그럼 이번 과제도 모두 파이팅입니다!!!! 🔥🔥

## 미션

### **⭐ 미션 목표**

- Next.js 사용법을 공부해봅니다.
- Figma로 주어지는 디자인으로 스타일링 하는 방식에 익숙해집니다.
- Git을 이용한 협업 방식에 익숙해집니다.
- 프론트엔드와 백엔드 시스템에 대한 흐름을 이해합니다.

### 📅 기한

> 2025년 5월 10일 토요일 (기한 엄수)
> 

### **✅ 필수 요건**

- [결과화면](https://next-netflix-18th-2.vercel.app)의 랜딩 페이지와 메인 페이지를 구현합니다.
- [Figma](https://www.figma.com/file/UqdXDovIczt1Gl0IjknHQf/Netflix?node-id=0%3A1)의 디자인을 그대로 구현합니다.
- Open api를 사용해서 데이터 패칭을 진행합니다. (ex. [themoviedb API](https://developers.themoviedb.org/3/getting-started/introduction))
- `yarn`, `yarn berry`, `npm`, `pnpm`등 패키지 매니저를 직접 선택해 Next.js를 세팅해 봅니다.

### 👍🏻 선택 요건

- SSR(Server Side Rendering)을 적용해서 구현합니다.
- 웹 폰트를 사용합니다.
- 반응형을 고려합니다.

### 🔑 Key Question

- React 18 버전의 변경점에 대해 설명해주세요. (+ 19 버전에 대한 추가 설명도 좋습니다.)
    - 서버 컴포넌트와 클라이언트 컴포넌트
    - lazy loading과 Suspense 컴포넌트
    - automatic batching, 동시성 모드 등 추가적으로 더 설명해주셔도 됩니다!
- nextJS 13 이후의 app routing 방식의 특징과 기능에 대해 설명해주세요.
    - 13 이전의 page routing과의 디렉터리 구성 변화
    - nextJS가 백엔드 시스템을 녹여내는 방법
    - 패러랠, 인터셉팅 라우트란 무엇인가?
    - nextJS에서 SSR, SSG를 구현하는 방법
- 전반적인 협업 과정에 대해 알려주세요. 👏🏻

---

### **🔗 링크 및 참고자료**

- [useCallback과 React.Memo를 이용한 렌더링 최적화](https://velog.io/@yejinh/useCallback%EA%B3%BC-React.Memo%EC%9D%84-%ED%86%B5%ED%95%9C-%EB%A0%8C%EB%8D%94%EB%A7%81-%EC%B5%9C%EC%A0%81%ED%99%94)
- [성능 최적화](https://ui.toast.com/fe-guide/ko_PERFORMANCE)
- [React 18의 새로운 기능](https://www.youtube.com/watch?v=7mkQi0TlJQo)
- [react 서버 컴포넌트가 해결하는 문제들 in kakao 기술 블로그](https://tech.kakaopay.com/post/react-server-components/)
- [vercel의 배포 방식](https://www.youtube.com/watch?v=8q-jCvLWwKc&t=11s)
- [랜딩페이지 영상](https://lottiefiles.com/kr/)
- [Next.js Docs](https://beta.nextjs.org/docs)
- [Next.js 13에서 변한 것들](https://velog.io/@hang_kem_0531/Next.js-13%EC%9D%B4-%EB%82%98%EC%99%80%EB%B2%84%EB%A0%B8%EB%8B%A4)
- [Next.js 14에서 변한 것들](https://velog.io/@lee_1124/Next.js-14-%EC%97%85%EB%8D%B0%EC%9D%B4%ED%8A%B8)
- [Git 협업 가이드](https://velog.io/@jinuku/Git-%ED%98%91%EC%97%85-%EA%B0%80%EC%9D%B4%EB%93%9C)
- [디자이너와 개발자가 협업하기 위한 피그마 기본 기능](https://chingguhl.tistory.com/entry/%EA%B0%9C%EB%B0%9C%EC%9E%90%EA%B0%80-%EA%BC%AD-%EC%95%8C%EC%95%84%EC%95%BC-%ED%95%A0-%ED%94%BC%EA%B7%B8%EB%A7%88-10%EA%B0%80%EC%A7%80-%EA%B8%B0%EB%8A%A5-%EB%94%94%EC%9E%90%EC%9D%B4%EB%84%88%EC%99%80-%EA%B0%9C%EB%B0%9C%EC%9E%90%EA%B0%80-%ED%98%91%EC%97%85%ED%95%98%EA%B8%B0-%EC%9C%84%ED%95%9C-%ED%94%BC%EA%B7%B8%EB%A7%88-%EA%B8%B0%EB%B3%B8-%EA%B8%B0%EB%8A%A5)
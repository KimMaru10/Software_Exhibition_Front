
## 👥<img width="541" alt="스크린샷 2023-11-02 오후 1 36 53" src="https://github.com/user-attachments/assets/be478a32-a1dd-427b-9bae-c1e4bafe388d">
프로젝트 팀 구성

- 프론트엔드 팀 2명
- 백엔드 팀 2명
- 게임 팀 1명
- 총 4명

> 저는 해당 프로젝트에서 프론트엔드 개발자로 프로젝트에 참여하였습니다.
> 

## ✍🏻프로젝트 개요

- 프로젝트 명 : 림딩동
- 프로젝트 목적 : 저희 학교에 있는 중앙동아리를 홍보하는 목적으로 개발하였습니다.

## 🤔개발 배경

- 기존에 학교에 있는 동아리 페이지가 있었지만 제대로 관리가 안되어 있다는걸 알게 되었고, 동아리에서 동아리를 홍보하는게 힘들다는 문제점이 있었습니다. 이러한 문제점을 파악하여, 학교내에 있는 동아리를 홍보하는 웹사이트를 기획 해보았습니다.

## 🛠️개발 도구 선정

- 프론트엔드 팀 : 리엑트 프레임워크
- 백엔드 팀 : Spring 부트
- UX/UI : Figma
- DB : MySQL

## ✏️기획단계

> 팀원들과 필요한 페이지에 대해 논의를 진행하였고 이논의를 토대로 웹페이지를 구성하는데 필요한 요소들을 결정 할 수 있었습니다.
> 

논의를 바탕으로 구체화된 내용을 간략히 정리해 보았습니다. 

- 동아리 소개 : 교내 중앙동아리를 분과별로 나누어 슬라이드를 통해 동아리를 확인 할 수 있다.  슬라이드 되는  동아리를 클릭하면 동아리에 대한 상세 정보를 확인 할 수 있습니다.
- 동아리 추천 페이지 : 몇가지 질문을 통해 사용자에게 맞는 동아리를 추천 해줍니다.
- 동아리방 찾기 : 내가 궁금한 동아리의 동방을 찾을 수 있습니다.

### 🎨디자인 및 페이지 구성

논의 한 내용을 토대로 Figma 페이지에 대한 디자인과 기능을 구체화해 나갔습니다. 

![스크린샷 2023-11-03 오후 2.32.00.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/28e61d31-5355-4c81-9bec-9a3e2642524e/13b2ca67-4da9-46e7-903b-cbe14168a478/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-11-03_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_2.32.00.png)

## ⚙️프로젝트 주요 기능 소개

> 메인 페이지
> 
- 메인페이지에는 이 웹사이트에서 할 수 있는 기능들을 소개 하는 페이지를 제작해 보았습니다.
- 메인 페이지에서는 애니메이션을 다양하게 활용하여 사용자에 눈을 즐겁게 하기 위해 노력했습니다.
- 처음 화면이 렌더링 되면 메인 모델이 나타나고 스크롤 이벤트를 만들어 스크롤을 내리면 애니메이션이 발생하도록 하였습니다.

[화면 기록 2023-11-03 오후 2.37.59.mov](https://prod-files-secure.s3.us-west-2.amazonaws.com/28e61d31-5355-4c81-9bec-9a3e2642524e/34d859a5-ead3-453a-9c9e-f6231c4bee30/%E1%84%92%E1%85%AA%E1%84%86%E1%85%A7%E1%86%AB_%E1%84%80%E1%85%B5%E1%84%85%E1%85%A9%E1%86%A8_2023-11-03_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_2.37.59.mov)

> 만든이들 페이지
> 
- 만든이들 페이지는 저희 개발자가 어떤 목적으로 개발 하게 되었는지, 그리고 어떤 기대효과가 있는지를 정리하여 개발스토리를 제작해보았습니다.
- 멤버소개를 통해 개발자가 맡은 역할과 간단한 소개를 넣어 보았습니다.

[화면 기록 2023-11-03 오후 2.47.19.mov](https://prod-files-secure.s3.us-west-2.amazonaws.com/28e61d31-5355-4c81-9bec-9a3e2642524e/a71875c8-f0da-48d4-b744-f7c0849974f9/%E1%84%92%E1%85%AA%E1%84%86%E1%85%A7%E1%86%AB_%E1%84%80%E1%85%B5%E1%84%85%E1%85%A9%E1%86%A8_2023-11-03_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_2.47.19.mov)

> 동아리 소개 페이지
> 
- 동아리소개에서는 저희 학교 중앙동아리에 매력를 어필 할 수 있는 페이지입니다.
- 각 분과 별로 나눠져 있어 동아리 궁금한 동아리를 찾기가 쉽습니다.
- 슬라이드를 클릭하게 되며, 해당 동아리에 활동 정보를 상세하게 확인하여, 동아리 가입이 고민 되시는 분들이 참고 하기 좋습니다.

![스크린샷 2023-11-07 오후 9.14.07.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/28e61d31-5355-4c81-9bec-9a3e2642524e/7b886daf-fb25-4375-b894-c34f94bfc658/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-11-07_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9.14.07.png)

![스크린샷 2023-11-07 오후 9.14.28.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/28e61d31-5355-4c81-9bec-9a3e2642524e/cc20161c-89e3-4fb4-aefd-1cf8c1e336f9/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-11-07_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9.14.28.png)

> 동아리방 찾기 페이지
> 
- 동아리방 찾기 페이지에서는 WebGL를 사용하여 Unity로 저희 학교내에서 동아리방을 찾아 다닐 수 있는 게임을 만들어 웹에서 작동 할 수 있게 하였습니다.
- 동아리방을 찾고 그 동아리방에 들어가게 되면 무슨 동아리의 방인지 확인 할 수 있습니다.

![스크린샷 2023-11-07 오후 9.14.50.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/28e61d31-5355-4c81-9bec-9a3e2642524e/b25fe1af-a0ce-4a99-b0ff-8116f17df01d/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-11-07_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9.14.50.png)

> 내게 맞는 동아리 찾기 페이지
> 
- 내게 맞는 동아리 찾기 페이지는 몇가지 질문을 통해 사용자에게 맞는 동아리를 찾아주는 페이지입니다.
- 질문을 끝낸 후에는 가장 어울리는 동아리와 그와 비슷한 동아리 또는 2 번째로 어울리는 동아리를 추천합니다.

![스크린샷 2023-11-07 오후 9.12.36.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/28e61d31-5355-4c81-9bec-9a3e2642524e/3379353b-c4c1-495e-8f3d-ca98722e6a79/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-11-07_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9.12.36.png)

![스크린샷 2023-11-07 오후 9.12.54.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/28e61d31-5355-4c81-9bec-9a3e2642524e/c09827c2-34e8-42cb-a163-c0491a48ccc9/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-11-07_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9.12.54.png)

![스크린샷 2023-11-07 오후 9.13.57.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/28e61d31-5355-4c81-9bec-9a3e2642524e/eb5fd4b5-ccc8-4de2-9ef2-648cda178619/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-11-07_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9.13.57.png)

## ⛳ 시연 영상

[KakaoTalk_Video_2023-11-07-18-06-34.mp4](https://prod-files-secure.s3.us-west-2.amazonaws.com/28e61d31-5355-4c81-9bec-9a3e2642524e/9c23739d-9541-4160-9bf8-52e9cf2ea961/KakaoTalk_Video_2023-11-07-18-06-34.mp4)

[GitHub - Team-Tag/Software_Exhibition_Front: 소프트웨어 전시회 <프론트엔드>](https://github.com/Team-Tag/Software_Exhibition_Front)

## 💬느낀점

프로젝트를 통해 얻은 경험을 정리하자면, 정보 수집과 협조의 중요성을 강조할 수 있습니다. 초기에 동아리 정보 수집에 어려움을 겪었지만, 끈기와 노력으로 다수의 동아리의 협조를 얻어내어 프로젝트를 성공적으로 마무리할 수 있었습니다. 또한, 기술적인 측면에서는 React 프레임워크의 사용을 통해 새로운 기술 스택을 익히고, Vue와의 비교를 통해 각각의 장단점을 이해하는 기회가 있었습니다. 이러한 경험들은 지식과 능력을 향상시키는 데 도움이 되었고, 미래 프로젝트에 적용할 수 있는 가치 있는 경험으로 남았습니다.

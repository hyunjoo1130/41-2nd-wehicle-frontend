<img src="https://user-images.githubusercontent.com/58460131/218261481-0d0bd198-d172-449a-abc8-aa2a770d1630.jpg"></img>
- 입찰 시스템을 통한 거래 중개 사이트(KREAM 사이트 기반)를 모델링한 프로젝트입니다.
- Product : 실시간 중고차 거래
</br>

# 🗓️ 개발 기간

- 23.01.30~23.02.10 (2주)
  
</br>

# 🔥 TEAM
### Team Name : Wehicle 🚙
FE: 김진우(PM), 오현주, 박정은 <br />
BE: 김승수(PM), 김가은

<br />

# ⚒️ 기술 스택

### 프론트엔드

|JavaScript|React|Styled</br>Component|esLint|Prettier|
| :--: | :--: | :--: | :--: | :--: |
| <img src="https://techstack-generator.vercel.app/js-icon.svg" alt="icon" width="65" height="65" /> | <img src="https://techstack-generator.vercel.app/react-icon.svg" alt="icon" width="65" height="65" /> | <img src="https://styled-components.com/logo.png" width="65" height="65" /></div> | <img src="https://techstack-generator.vercel.app/eslint-icon.svg" alt="icon" width="65" height="65" /> | <img src="https://techstack-generator.vercel.app/prettier-icon.svg" alt="icon" width="65" height="65" /> |

</br>

# 👥 협업 툴

<div>
<img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=Git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/>
<img src="https://img.shields.io/badge/Slack-4A154B?style=flat&logo=Slack&logoColor=white"/>
<img src="https://img.shields.io/badge/Trello-0052CC?style=flat&logo=Trello&logoColor=white"/>
<img src="https://img.shields.io/badge/Notion-000000?style=flat&logo=Notion&logoColor=white"/>
<img src="https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=Figma&logoColor=white"/>
<img src="https://img.shields.io/badge/VSCode-007ACC?style=flat&logo=Visual Studio Code&logoColor=white"/>
</div>

</br>

| <img width="513" alt="스크린샷 2023-01-08 오후 5 23 04" src="https://user-images.githubusercontent.com/90304025/218025670-a0045604-7a87-4b8d-95de-dd464eddb6bb.png"> | <img width="1406" alt="스크린샷 2023-01-08 오후 5 24 05" src="https://user-images.githubusercontent.com/90304025/218025098-5d88c582-37c6-42ed-9511-a828d9acaef7.png"> | <img width="513" alt="스크린샷 2023-02-12 오후 6 33 05" src="https://user-images.githubusercontent.com/58460131/218303374-afc2dba8-295a-4e96-82ef-15a96c2f5f60.png"> |
|:-:|:-:|:-:|

</br>

# 🖥️ 데모 영상
<a href="https://youtu.be/YxTH82veYOk">🔗 Wehicle 데모영상 </a>

</br>

# 🪩 DB 모델링

![WEHICLE ERD](https://user-images.githubusercontent.com/112741645/218115431-883c5007-6ffe-49c8-876a-e76df3db2a22.jpg)

<br>

# 👩🏻‍💻 내가 맡은 페이지 및 기능들

## 메인페이지
### 캐러셀 기능
- useRef hooks 사용하여 배너사진이 들어가있는 태그에 접근하여 translateX로 스타일 컨트롤
- useState 로 해당 배너사진 태그들에 임의의 숫자를 지정하여 관리

### 페이지네이션 기능
- 쿼리스트링으로 들어갈 offset은 useState로, limit은 상수변수로 관리하여 가공하여 렌더링
- 그러나 새로고침시 쿼리스트링이 남아있기에, 새로고침시 초기 limit 데이터들만 렌더링 될 수 있도록 새로고침용 useEffect fetch 따로 설정
- 상품데이터를 클릭 시, 상세페이지로 넘어갈 수 있게 navigate 사용하여 동적라우팅

### 조건부 렌더링
- 고정된 offset, limit 으로 쿼리스트링 활용
- 태그에 속성을 주어, 해당 태그의 속성값과 일치/불일치 조건문으로 해당 데이터를 따로따로 받아 렌더링

</br>

## 입찰하기, 구매하기 모달창
### 입찰하기 모달창
- 레이아웃 구현
- 입찰 완료 alert 
### 구매하기 모달창
- 구매하기 버튼 누를 시 useNavigate를 사용하여 결제페이지로 이동할 수 있게 구현
- 상세페이지에서 받은 데이터들을 props로 모달창으로 재전달 받아 필요한 정보들만 가공하여 렌더링

</br>

## 판매하기 페이지
- 레이아웃 구현
- 이미지 업로드 구현 위해, input type file 에 label 태그를 감싸 디자인 커스터마이징
- 이미지 미리보기 기능 구현, FileReader 기능으로 이미지 url을 저장한 뒤, 이벤트 발생 시 보여줄 수 있도록 구현
- 날짜 선택 기능 구현, react-datepicker 라이브러리 사용하여 캘린더 기능 구현
- 입력하는 숫자가 천단위에 맞게 콤마가 찍히게 하기 위해, replaceAll 메서드와 toLocaleString('Ko-KR')로 입력값을 가공하여 실시간 변환 구현
- 레이아웃 구현

<br />

## 푸터
- 레이아웃 구현
- 상수데이터, map() 활용

</br>



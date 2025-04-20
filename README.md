# Online-Shopping-Mall(Full Stack E-commerce)

React, Node.js, Express, MySQL을 기반으로 **풀스택으로 구현한 온라인 쇼핑몰** 입니다. <br/>
실시간 상품 검색, 관리자용 대시보드, 장바구니 CRUD, 페이지네이션 등을 구현하였습니다. <br/>
<br/>
(아래 이미지를 **클릭**하시면 **큰 화면**으로 보실 수 있습니다.)<br/>
<br/>
<img src="https://github.com/user-attachments/assets/1b621014-112e-4b6c-852b-1bdf0dee9449" width="800" style="border: 2px solid red; border-radius: 8px;"/>

## 🔗 Live Demo <br/>
👉 [쇼핑몰 둘러보기](https://shoppingmall-myungwan.netlify.app/) <br/>
<br/>

## 📂 Repositories <br/>
- [🖥️ Frontend Repository](https://github.com/MyungWanPark/shopping-mall-frontend) <br/>
- [🔙 Backend Repository](https://github.com/MyungWanPark/shopping-mall-backend) <br/>
<br/>

## 🛠️ Tech Stack

### 🖥️ Frontend
- **Framework**: React
- **Language**: TypeScript
- **UI Library**: MUI
- **Routing**: React Router Dom
- **State Management**: Redux
- **Network State Management**: TanStack Query (React Query)
- **Styling**: Tailwind CSS
- **Charting**: ApexCharts

### 🧠 Backend
- **Runtime**: Node.js with Express
- **Language**: TypeScript
- **Database**: MySQL with Sequelize ORM
- **Authentication**: OAuth2 (Kakao), JWT
- **Architecture**: MVC, RESTful API

### ☁️ Deployment
- **Frontend**: Netlify
- **Backend**: CloudType
- **Database**: CloudType (MySQL)
<br/>

## 🚀 Key Features

### 👤 사용자 인증 & 권한
- **소셜 로그인 (OAuth2)** – 카카오 계정을 이용한 소셜 로그인 구현  
- **JWT 기반 인증** – 자체 회원가입 및 로그인, 토큰 기반 사용자 인증 처리  
- **비회원 장바구니 지원** – Redux와 LocalStorage를 활용해 로그인 없이도 장바구니 사용 가능  

### 🛍️ 상품 조회 및 생성
- **상품 목록 & 상세 페이지** – 상품 소개, 옵션 선택, 장바구니 추가  
- **상품 등록 기능** – 새로운 상품을 등록할 수 있는 관리자용 UI 및 API 구현  
- **카테고리별 상품 조회** – 남성, 여성, 가방 등 카테고리별 필터링 지원  
- **실시간 상품 검색** – 키워드 입력 시 관련 상품을 실시간으로 필터링  

### 🛒 장바구니 기능
- **장바구니 CRUD** – 장바구니 추가, 상품 수량 변경, 삭제, 총 금액 계산 등 관리 기능  
- **실시간 UI 동기화** – 장바구니 변경 시 네비게이션 바의 아이콘 숫자를 즉시 업데이트

### 📊 관리자 대시보드 & 시각화
- **매출 및 통계 시각화** – 기간별 매출, Top 5 인기 상품, 신규 유저 수 등 데이터 시각화  
- **ApexChart 기반 차트 구성**

### ⚡ 성능 & 사용자 경험 개선
- **Lazy Loading** – 초기 렌더링 속도를 개선하기 위해 코드 분할 적용  
- **React Query 캐싱** – 중복 네트워크 요청 방지 및 빠른 데이터 조회
- **Pagination** – 많은 양의 상품 데이터를 페이지 단위로 분할해 클라이언트 렌더링 속도 개선 및 서버/부하 감소  
- **Skeleton UI** – 로딩 시간 동안 사용자 피로감을 줄이기 위한 Skeleton 화면 제공  
- **반응형 UI** – 데스크탑, 태블릿, 모바일 환경에 최적화된 반응형 레이아웃  
<br/>


## 💻 Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/MyungWanPark/shopping-mall-frontend.git
git clone https://github.com/MyungWanPark/shopping-mall-backend.git
```

### 2️⃣ Install dependencies
```bash
cd shopping-mall-frontend
npm install
cd shopping-mall-backend
npm install
```

### 3️⃣ Run the application(개발 환경, .env 파일 필요)

### Frontend
```bash
npm run start
```
개발 모드 환경: http://localhost:3000

### Backend
```bash
npm run build
npm run start:dev
```

개발 모드 환경: http://localhost:8080
<br/>
<br/>

## 🏗️ 향후 개선 사항
- ⭐ 결제 기능 구현
- ⭐ 위시리스트, 리뷰 기능 구현
- ⭐ 알림 기능 구현
<br/>

## 📬 Contact & Feedback
👨‍💻 **Developer**: 박명완 <br/>
📧 **Email**: mywanpark@gmail.com <br/>

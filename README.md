# Online-Shopping-Mall(Full Stack E-commerce)

React, Node.js, Express, MySQL을 활용한 **풀스택으로 구현한 온라인 쇼핑몰** 입니다. <br/>
실시간 상품 검색, 데이터 시각화, 장바구니 CRUD, 페이지네이션 등을 구현하였습니다. <br/>
<br/>

![Image](https://github.com/user-attachments/assets/2057422a-3b02-4dbc-8aff-9db9e3d0e29d)

## 🔗 Live Demo <br/>
👉 [쇼핑몰 둘러보기](https://shoppingmall-myungwan.netlify.app/) <br/>
<br/>

## 📂 Repositories <br/>
- [🖥️ Frontend Repository](https://github.com/MyungWanPark/shopping-mall-frontend) <br/>
- [🔙 Backend Repository](https://github.com/MyungWanPark/shopping-mall-backend) <br/>
<br/>

## 🚀 Key Features
✔ **사용자 인증** – OAuth2를 활용한 소셜 로그인(카카오), JWT를 이용한 회원가입/로그인 <br/>
✔ **실시간 상품 검색** - 검색창에 키워드 입력시, 연관된 상품을 실시간으로 조회, 연관된 상품 검색 <br/>
✔ **데이터 시각화** - 기간별 매출액, Top 5 상품, 신규 유저 수 등을 차트로 시각화한 대시보드 <br/>
✔ **장바구니** - 장바구니에 추가한 상품을 관리, 수량 변경 및 상품 삭제, 총 금액 조회 기능 <br/>
✔ **비로그인 상태에서 장바구니 관리** - Redux, LocalStorage를 활용해 비로그인 상태에서 장바구니 저장 및 관리 <br/>
✔ **실시간 UI 동기화** - 장바구니에 상품 추가 및 삭제 시, 네비게이션 바의 장바구니 아이콘 숫자를 즉시 동기화 <br/>
✔ **Pagination** - 상품의 갯수가 10개 이상인 경우, 페이지 단위로 상품 조회 기능 <br/>
✔ **상품 상세 페이지** - 상품에 대한 자세한 소개, 상품 별 옵션 설정, 장바구니 추가 기능 <br/>
✔ **상품 등록** - 새로운 상품 등록 기능 <br/>
✔ **Skeleton UI** - 상품 로딩 시 Skeleton UI를 활용해 대기 시간동안 사용자 경험 향상 <br/>
✔ **카테고리별 상품 조회** - 남성, 여성, 가방 등 카테고리별 상품 조회 기능 <br/>
✔ **반응형 UI** - 데스크탑, 테블릿, 모바일 환경을 고려한 반응형 UI <br/>
✔ **데이터 패칭 최적화** - TanStack Query을 활용한 데이터 패칭 및 캐싱. 데이터 갱신을 활용한 즉각적 UI 동기화 <br/>
<br/>

## 🛠️ Tech Stack

### Frontend
- **✨ UI** - React, MUI <br/>
- **📃 Language** - TypeScript  <br/>
- **⚛️ 네비게이션** - React Router Dom  <br/>
- **🌐 전역 상태 관리** - Redux  <br/>
- **🎯 네트워크 상태 관리** - Tanstack Query  <br/>
- **🎨 스타일링** - Tailwind CSS <br/> 
- **📊 차트 라이브러리** - Apex Chart <br/>

### Backend
- **🌏 서버** - Node.js with Express
- **📃 Language** - TypeScript  <br/>
- **🗄️ Database** - MySQL, Sequelize ORM
- **🔑 사용자 인증** - OAuth2 with Kakao, JWT
- **🧱 MVC architecture**
- **📡 RESTful API**

### Deployment
- **🚀 Frontend** - Netlify
- **🖥️ Backend** - CloudType
- **🗄️ DB** - CloudType
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

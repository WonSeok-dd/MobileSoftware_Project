# MobileSoftware_Project
2021-2 모바일 소프트웨어 학기말 프로젝트<br/><br />

### YouTube 요약 영상 링크
https://www.youtube.com/watch?v=FuKpaxK-lV4

### 기능 설명

> ### 주어진 기능 구현
> #### 1. 상품리스트화면에서 상품리스트 출력(총 15개 : 침대-5개, 책상-5개, 의자-5개)
> 
> #### 2. 상품리스트화면에서 상품 클릭시 상품상세정보 보여주기
>   - 2-1 상품 사진 (ViewPager를 통해 상품당 3개 이미지를 밀면서 확인)
>   - 2-2 상품 가격 
>   - 2-3 상품 설명
>   - 2-4 상품 제조회사의 웹사이트 ('클릭시 웹사이트 이동')버튼클릭시 웹뷰를 통해 웹사이트 이동)
>
> #### 3. 고객센터 기능
>   - 고객센터 버튼클릭시 다음과 같은 고객센터화면이동
>   - 3-1 고객센터 전화번호 및 연결
>   - 3-2 고객센터 이메일 보내기
>   - 3-3 고객센터 지도상에서 위치 보여주기

> ### 추가 기능 구현
> #### 1. 로그인/회원가입 기능
>   #### 1-1 회원가입 기능: 
>      - 아이디,비밀번호,이름을 모두 입력을 안할시 alertDialog로 메시지
>      - 아이디가 이미 존재할시 alertDialog로 메시지
>      - 위 조건을 모두 만족하면 회원가입 되었다는 toast메시지로 알려주면서 로그인화면으로 이동 
>      - 초기화 버튼 클릭시 입력한 내용 초기화
>   #### 1-2 로그인 기능 :
>      - 아이디,비밀번호를 모두 입력을 안할시 alertDialog로 메시지
>      - 회원가입한 아이디,비밀번호로 올바르게 입력 안할시 alertDialog로 메시지
>      - 위 조건을 모두 만족하면 로그인하면서 상품리스트화면으로 이동
>      - 상품리스트화면으로 이동했다면 로그인한 계정의 이름을 상단에 ~님 환영합니다 TextView로 확인
>
> #### 2. 검색 기능
>       - 상품리스트화면에서 상품검색창에 상품이름으로 검색시 상품리스트변화
>
> #### 3. 항목별 출력 기능
>       - 상품리스트화면에서 스피너를 통해 선택한 항목으로 상품리스트변화
>
> #### 4. 장바구니 기능
>       - 상품리스트화면에서 해당상품의 장바구니추가 버튼클릭시 alertDialog로 메시지
>         뜨면서 장바구니 배열에 담음
>       - 상품리스트화면에서 장바구니 버튼클릭시 장바구니화면으로 이동하면서 담았던 상품의 이름들 확인(중복저장 가능) 
>
> #### 5. 애니메이션 기능
>       - 상품리스트화면에서 리사이클러뷰 애니메이션 추가
>       - 장바구니화면에서 리사이클러뷰 애니메이션 추가




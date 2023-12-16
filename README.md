# BlogProject
Spring + 게시판(블로그) 프로젝트
<br>
<br>

## 🖥프로젝트 소개
우리가 일반적으로 사용하는 게시판(블로그)를 Spring으로 구현하였다.


## 🕰개발 기간
- 2023.11.29 ~ 2023.12.09


### 👤멤버 구성
- 조원: 김상훈
  - 백엔드
    - 메인 화면 - 게시글 목록(글 제목, 내용 미리보기, 이미지 썸네일), 프로필 배경 사진 선택
    - 게시글 상세 화면 - DB에 등록, 폰트 크기 선택, 파일 추가 
    - 페이징
  
    
- 조원: 이주영
  - 프론트엔드 전체
    - 메인 화면 - 마이 페이지, 로그인 페이지, 게시글 목록, 카테고리, 검색창
    - 회원가입
    - 게시글 상세 화면 - 게시글, 댓글

    
- 조원: 장혜민
  - 백엔드
    - 메인 화면 - 카테고리(카테고리 선택 시 해당 카테고리의 글만 정렬), 검색창
 

### ⚙ 개발 환경
- Spring
- Java
- HTML
- CSS
   

## 📌 주요 기능
### ① 메인 화면
#### ⓐ 프로필
  - 로그인 화면
    ![login](https://github.com/JooYeong-Lee/BlogProject/assets/100755494/badfd0ef-e517-42e2-ac24-29a02d332f34)
    - 로그인이 되어있지 않은 상태라면 로그인 화면과 회원가입 페이지로 이동할 수 있는 태그를 표시
  - 프로필 화면
    ![main](https://github.com/JooYeong-Lee/BlogProject/assets/100755494/84c41d4c-b110-4638-bd22-69f63e807361)
    - 아이디와 한줄 소개를 표시
      - 아이디와 한줄소개 옆 수정 버튼을 통해 아이디와 한줄소개 수정 가능 - 아이디는 중복확인 거침
    - 좌측 맨 위 카메라 버튼을 통해 배경 사진 변경 가능
    - 우측 맨 위 로그아웃 버튼을 통해 로그아웃 가능
    - 우측 맨 아래 글 쓰기 버튼을 통해 게시글 작성 가능
      
#### ⓑ 게시글 목록
  ![imglist](https://github.com/JooYeong-Lee/BlogProject/assets/100755494/2bdcd192-7682-4913-9487-51f5cbbc575f)
  - 한 개의 게시글에 제목, 내용 미리보기, 선택한 이미지 썸네일을 표시
    
#### ⓒ 카테고리
  ![category](https://github.com/JooYeong-Lee/BlogProject/assets/100755494/7a603f86-1b2a-4480-a63e-d2cb36581782)
  - 헤더의 카테고리 버튼을 통해 카테고리 목록 확인 가능

    
  ![category1](https://github.com/JooYeong-Lee/BlogProject/assets/100755494/774cda3d-25c9-4512-90ec-73e7ba815ef9)
  - 카테고리를 선택하면 해당 카테고리에 속해있는 게시글이 정렬됨
    
#### ⓓ 검색창
  ![search](https://github.com/JooYeong-Lee/BlogProject/assets/100755494/9b34bbcd-5794-4f77-b983-ea43229a8ad8)
  - 헤더의 검색창 버튼을 통해 검색 가능


  ![search1](https://github.com/JooYeong-Lee/BlogProject/assets/100755494/a341432b-4b91-477b-81f6-7a7a6f86cb67)
  - 찾고자 하는 게시글의 제목을 입력하면, 사용자가 입력한 문자열이 제목에 포함된 모든 게시글들이 정렬됨
     
    
### ② 글쓰기
  ![write](https://github.com/JooYeong-Lee/BlogProject/assets/100755494/1bc23f30-a6a9-4f4f-8869-abe347e0f3f3)
  - 제목, 게시글에 들어갈 내용 입력
  - 카테고리 선택 - 미선택시 게시 불가
  - 사진 선택 가능
  - 글씨 크기 선택 가능


### ③게시글 상세
  ![post](https://github.com/JooYeong-Lee/BlogProject/assets/100755494/069bfc03-fc3f-4569-a675-6fc783eebb45)
  - 글 상세 내용 확인 가능
  - 댓글 달기 가능


### ④ 회원가입
  ![signup](https://github.com/JooYeong-Lee/BlogProject/assets/100755494/f467c4f5-b367-497c-bb8f-1d1d1b81f4c7)
  - 아이디, 비밀번호를 입력 받음
  - 아이디 중복확인, 비밀번호 확인을 거친 후 회원가입 진행

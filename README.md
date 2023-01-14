# 🌙 HoneyDream
> 22.10.14 ~ 12.30 / 허니드림 / AWS클라우드 기반 자바개발 과정 제 1차 프로젝트  
> 팀 구성원: 김현수, 나슬기, 박선영, 신현지, 최현주, 한규영, 한승주
<br/>

## 📖 주제: 수면카페 예약 플랫폼
<div align="center">

<img alt="허니드림 소개 이미지" src="https://user-images.githubusercontent.com/73747247/212490244-4f944c4b-8aa7-4afb-a1a6-b3a43ee5aa73.jpg" width="100%"/>

</div>

### 프로젝트 목적
+ 브랜드, 업태와 상관 없이 양질의 숙면을 제공할 수 있는 공간에대한 공유
+ 공유된 공간을 바로 예약 및 결제할 수 있는 기능 제공
+ 협업중심 프로젝트에 대한 선행 체험
<br/>

## 🛠 사용언어 및 개발 환경
<div align="center">
<img alt="Java 11" src ="https://img.shields.io/badge/☕ Java 11-007396?&style=for-the-badge"/> <img alt="Jsp" src ="https://img.shields.io/badge/☕ Jsp-de6c18?&style=for-the-badge"/> <img alt="Html5" src ="https://img.shields.io/badge/HTML5-E34F26?&style=for-the-badge&logo=HTML5&logoColor=white"/> <img alt="Css3" src ="https://img.shields.io/badge/CSS3-1572B6?&style=for-the-badge&logo=CSS3&logoColor=white"/> <img alt="Javascript" src ="https://img.shields.io/badge/JavaScript ES6-F7DF1E?&style=for-the-badge&logo=JavaScript&logoColor=black"/> <img alt="jQuery" src ="https://img.shields.io/badge/jQuery 3-0769AD?&style=for-the-badge&logo=jQuery&logoColor=white"/>
<img alt="Oracle" src ="https://img.shields.io/badge/Oracle-F80000?&style=for-the-badge&logo=Oracle&logoColor=white"/>
<img alt="Apache Tomcat" src ="https://img.shields.io/badge/Apache Tomcat 11-F8DC75?&style=for-the-badge&logo=Apache Tomcat&logoColor=black"/>
<br/>
<img alt="Spring" src ="https://img.shields.io/badge/Spring 5-6DB33F?&style=for-the-badge&logo=Spring&logoColor=white"/> <img alt="Mybatis" src ="https://img.shields.io/badge/Mybatis-000000?&style=for-the-badge&logo=Twitter&logoColor=white"/> <img alt="eGovFrame 4" src ="https://img.shields.io/badge/eGovFrame 4-004fbb?&style=for-the-badge"/> <img alt="Font Awesome 6" src ="https://img.shields.io/badge/Font Awesome 6-528DD7?&style=for-the-badge&logo=Font Awesome&logoColor=white"/> <img alt="Apache Maven" src ="https://img.shields.io/badge/Apache Maven-C71A36?&style=for-the-badge&logo=Apache Maven&logoColor=white"/>
</div>
<br/>

## 🗃 프로젝트 구조
### 유스케이스 다이어그램
<table>
    <tr>
        <th width="25%">비회원</th>
        <th width="25%">회원</th>
        <th width="25%">사업주</th>
        <th width="25%">관리자</th>
    </tr>
    <tr>
        <td><img alt="유스케이스 비회원 이미지" src="https://user-images.githubusercontent.com/73747247/212493390-c2ee2244-bb24-4e0e-9186-da4710860be5.png"/></td>
        <td><img alt="유스케이스 회원 이미지" src="https://user-images.githubusercontent.com/73747247/212493380-8a987c99-6419-41cc-9bc2-552ff4c5fb23.png"/></td>
        <td><img alt="유스케이스 사업주 이미지" src="https://user-images.githubusercontent.com/73747247/212492995-1f9fb0e2-bb24-434f-9230-bdaa01aea820.png"/></td>
        <td><img alt="유스케이스 관리자 이미지" src="https://user-images.githubusercontent.com/73747247/212492999-be59f34c-7a06-4ef9-a178-372fa0ca873a.png"/></td>
    </tr>
</table>

### ER 다이어그램
<img alt="ER 다이어그램 이미지" src="https://user-images.githubusercontent.com/73747247/212492926-cb3841af-604d-4e27-bbb5-33cf1e42c13c.png" width="100%"/>
<br/>

## 🖥 미리보기
<table>
    <tr>
        <th width="50%" colspan="2"><img alt="핵심" src ="https://img.shields.io/badge/핵심-ff0000?&?style=flat-square&logo=Pinboard&logoColor=white"/> <br/> 주문 및 예약</th>
        <th width="50%">모바일 레이아웃</th>
    </tr>
    <tr>
        <td colspan="2"><img alt="주문 및 예약 이미지" src="https://user-images.githubusercontent.com/73747247/212500161-710929bd-483d-4711-9829-5a91147af70e.gif"/></td>
        <td align="center"><img alt="모바일 이미지" src="https://user-images.githubusercontent.com/73747247/212500123-f0cb670d-ca86-4d7b-81b8-f1c0e9585a89.gif"/></td>
    </tr>
    <tr>
        <th width="33.33%">메인 레이아웃</th>
        <th width="33.33%">관리자 레이아웃</th>
        <th width="33.33%">회원가입/로그인</th>
    </tr>
    <tr>
        <td><img alt="메인 이미지" src="https://user-images.githubusercontent.com/73747247/212499566-e94af281-618b-4994-b063-d6563b1ba71f.gif"/></td>
        <td><img alt="관리자 이미지" src="https://user-images.githubusercontent.com/73747247/212500120-3f2a706a-064b-46cf-875a-e22d2332d106.gif"/></td>
        <td><img alt="회원가입/로그인 이미지" src="https://user-images.githubusercontent.com/73747247/212500151-327ff245-6c17-437f-85ec-8371086c8f47.gif"/></td>
    </tr>
    <tr>
        <th width="33.33%">계정정보 찾기</th>
        <th width="33.33%">회원정보 수정</th>
        <th width="50%">찜</th>
    </tr>
    <tr>
        <td><img alt="계정정보 찾기 이미지" src="https://user-images.githubusercontent.com/73747247/212500159-ca77cf3a-189f-42b3-8c0a-e83c5f1fe9cf.gif"/></td>
        <td><img alt="회원정보 수정 이미지" src="https://user-images.githubusercontent.com/73747247/212500160-5861affe-180b-4a6f-a870-868f6ad2b602.gif"/></td>
        <td><img alt="찜 이미지" src="https://user-images.githubusercontent.com/73747247/212500162-88e59b68-3dde-48f1-a86c-60dda7d9f18e.gif"/></td>
    </tr>
    <tr>
        <th width="33.33%">카페등록</th>
        <th width="33.33%">업주예약관리</th>
        <th width="33.33%">정산정보관리</th>
    </tr>
    <tr>
        <td><img alt="카페등록 이미지" src="https://user-images.githubusercontent.com/73747247/212500163-8af169a4-0b0b-4d93-9e2c-e26d37e568bb.gif"/></td>
        <td><img alt="업주예약관리 이미지" src="https://user-images.githubusercontent.com/73747247/212500164-a28d2aec-41f5-42c9-b430-cdb258c4295d.gif"/></td>
        <td><img alt="정산정보관리 이미지" src="https://user-images.githubusercontent.com/73747247/212500165-08d9d170-466b-488b-8fee-7390e76881cf.gif"/></td>
    </tr>
    <tr>
        <th width="33.33%">고객센터</th>
        <th width="33.33%">관리자 공지관리</th>
        <th width="33.33%">관리자 FAQ</th>
    </tr>
    <tr>
        <td><img alt="고객센터 이미지" src="https://user-images.githubusercontent.com/73747247/212500166-c2ddd4ec-f012-4f1a-bb09-6fa5c550c73c.gif"/></td>
        <td><img alt="관리자 공지관리 이미지" src="https://user-images.githubusercontent.com/73747247/212500168-24b2abd5-0ebc-470a-be44-c7bef35583a0.gif"/></td>
        <td><img alt="관리자 FAQ 이미지" src="https://user-images.githubusercontent.com/73747247/212500169-c88aa5e9-e3d3-4552-afde-5c172e8d87f6.gif"/></td>
    </tr>
    <tr>
        <th width="33.33%">관리자 QNA</th>
        <th width="33.33%">관리자 회원정보관리</th>
        <th width="33.33%">관리자 리뷰관리</th>
    </tr>
    <tr>
        <td><img alt="관리자 QNA 이미지" src="https://user-images.githubusercontent.com/73747247/212500170-7d827c2c-5a95-42b8-9f9e-acfe8c9fb429.gif"/></td>
        <td><img alt="관리자 회원정보관리 이미지" src="https://user-images.githubusercontent.com/73747247/212500167-50082de5-a4ff-4269-91d4-e6605b184a91.gif"/></td>
        <td><img alt="관리자 리뷰관리 이미지" src="https://user-images.githubusercontent.com/73747247/212500171-867c94f9-58f1-4046-bcee-bff463836fe1.gif"/></td>
    </tr>
</table>
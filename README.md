# e-commerce-portfolio-front



E-commerce website
: Shopping mall ( to study Angular and Springboot ) 

for more info about this project, please refer to the below link to the e-commerce-portfolio-backend

이 페이지는 E-COMMERCE 웹쇼핑몰 프론트 소스코드입니다. 

다음의 링크는 백엔드 코드+ 기능과 제작 (스프링부트, 앵귤러, REST API), 학습과정을 정리하였습니다. 
: https://github.com/triptocode/e-commerce-portfolio-backend





본 프로젝트 주요기능은 아래와 같이 대략적으로 확인가능합니다.
About Project
E-commerce 온라인 쇼핑몰 웹 구축 (21.12.15~12.31)
개인 프로젝트 / 풀스택 ( Angular & Java SpringBoot)

사용된 기술 ( 언어, 프레임워크, 툴)
프론트: ,, ,, 
백엔드: ,  ( using  and  )
개발툴: IntelliJ, VScode, Maven, npm, git

backend link:
https://github.com/triptocode/e-commerce-portfolio-backend

frontend link:
https://github.com/triptocode/e-commerce-portfolio-front.git

중요기능 상세설명 링크 ( 각 기능 구현 과정 및 자세한 설명은 각 링크 참조 ):
메뉴카테고리 : 하드코딩없이 Rest API 활용, category id로 동적 호출하여 표현
https://www.notion.so/id-Rest-API-5acc33e877cf49629527d1347a8b6686
상품 메인화면구현 : product-box로 상품정보를 묶고, 앵귤러반복문(ngFor)활용해 상품 모두출력 각 카테고리에 해당하는 상품 route설정
https://www.notion.so/product-box-ngFor-route-0379d7e88bfc42e5914b3e2da29b8739
상품 검색창 구현: Spring Data REST 와 Spring Data JPA에서 제공하는 쿼리 메서드 findBy 활용
https://www.notion.so/findBy-9e459a69166d4a83abd16a3010853fdf
쇼핑카트 기능 구현 1 : 상품추가버튼 클릭시 상단의 쇼핑카트에 가격, 수량 반영되도록 한다.
https://www.notion.so/1-562a7da393de4d11b52f75d662799712
쇼핑카트 기능 구현 2 : 쇼핑카트에 담긴 상품의 수량 증감, 삭제 기능구현
https://www.notion.so/2-5012efa38d894a5fab872d58b6b06ad8
주용기능 몇가지 요약화면
쇼핑카트
1상품추가버튼클릭시 쇼핑카트변화

image

2 쇼핑카트담긴 상품 증감삭제
Add to cart 버튼클릭시 addToCart 메서드 실행하는 button 기능 구현
image

handler 메서드 클릭시, ProductListComponent가 업데이트 되도록 한다.
image

카테고리 메뉴 - rest api, 카테고리 id 로 동적 구현
image
image

상품 검색창 기능구현
pring Data REST 와 Spring Data JPA는 쿼리 methods findBy 활용한 백엔드 코딩
image

/findByNameContaining?name=키워드 (입력하면 관련 제품이 검색되어 출력된다. )

아래 백엔드코드 구현 : url에 findby키워드로 Beginner. Python 등을 입력하면 키워드와 관련된 제품 결과 출력 예: /findByNameContaining?name=Beginner

image

image

이커머스 웹 프로젝트 각 기능별 화면, 코드 설명 정리목록
https://www.notion.so/E-Commerce-Website-Angular-Java-Spring-Boot-09b4f47cb59e4a51b1e76aef782e6d5a

########################################## 감사합니다 ######################################

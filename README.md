# 📉 내일은 최저가 - BE

<p align="center">
  <img width=100% src="https://github.com/SHIN1501020/testReadMe/assets/72782380/0c88557d-9be6-44fe-9088-652f9f5336c0">
  <img width=100% src="https://github.com/SHIN1501020/testReadMe/assets/72782380/71f9d046-a4c5-4758-9053-de0289713867">
  <img width=100% src="https://github.com/SHIN1501020/testReadMe/assets/72782380/0e202311-7d8b-4e68-a939-f629f178ceca">
</p>

> [내일은 최저가]는 쿠팡에서 애플 제품들의 가격 변동을 스크래핑해 차트로 시각화하고 최적의 구매 타이밍에 소비자에게 카카오 알림톡을 제공하는 서비스입니다.
> * 쿠팡에서 존재하는 애플 제품 전체 조회 서비스
> * 쿠팡 애플 제품 정보 람다 서버리스 스크래핑
> * 애플 제품의 가격 변동 데이터를 이용한 차트 시각화 서비스
> * 제품의 최저가 변동시 카카오 알림톡 서비스






## 주요 기능 



1. 메인페이지
   * 애플 제품에 관련해 카테고리별 조회를 할 수 있습니다.
   * 애플 제품에 관련해 검색을 할 수 있습니다.



2. 상세페이지
   * 제품의 가격 변동을 시각화해 차트로 볼 수 있습니다.
   * 특정 제품을 알림 설정하고 최저가로 변동시 알림을 받을 수 있습니다.


  
3. 매거진
   * 매거진을 통해 애플 제품과 관련된 기사들을 확인할 수 있습니다.
   * 특정 매거진에 대해 좋아요 설정을 하고 좋아요한 매거진을 조회할 수 있습니다.



4. 마이페이지 및 로그인 정보
   * 카카오 로그인과 로그아웃 기능으로 페이지에 접근이 쉽습니다.
   * 회원정보 수정과 탈퇴가 가능합니다.



5. 스크래핑 및 파트너스 기능
   * Puppeteer AWS lambda 함수 배포를 통한 쿠팡 애플 상품 자동 스크래핑
   * 쿠팡 파트너스 API를 통해 쿠팡에서 구매가 발생하면 구매금액에 대한 커미션 금액을 받습니다.

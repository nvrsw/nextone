---
title: 회사 소개

# View Mode (1 = List, 2 = Compact, 3 = Card)
view: 2

# Optional header image (relative to `static/img/` folder).
cascade:
  header:
    image: "solution-header.jpg"
---

## 인사말

(주)넥스톤 방문을 환영합니다.

(주)넥스톤은 CCTV, 전광판, 전산 업무 분야의 제품생산공급 및 서비스를 제공하는 ICT 전문기업입니다. 정보통신 분야의 풍부한 기술과 실무경험을 가진 전문가들로 구성되어 믿을 수 있는 품질과 고객관리에 최선을 다하고 있습니다.

㈜넥스톤은 취약계층인 장애인에게 안정적인 일자리를 제공하여 사회적, 경제적 가치 공유를 추구하고 있습니다. 준비된 제품을 구매함으로 저희와 함께 해주심을 진심으로 감사드리며 (주)넥스톤은 긍정적인 노력으로 답할 것을 약속드립니다.

감사합니다.

**넥스톤 임직원 일동**

## 기업 현황 / 연혁 {#history}

### 현황

 | 
-: | --
**법인** | 주식회사 넥스톤
**대표이사** | 이광구
**전화** | 02-6675-3630 / 팩스 02-6675-3632
**사업자등록번호** | 590-81-02247
**법인등록번호** | 110111-8151253
**정보통신공사업 면허번호** | 제203581호
**업태** | 제조업 / 건설업 / 도소매 / 서비스
**종목** | 영상감시장치, 전광판, 정보통신공사업, 전산업무
**주소** | 서울 구로구 디지털로29길 38, 에이스테크노타워3차 209, 211호
**홈페이지** | http://www.nextone.co.kr
**인증현황** | 장애인기업, (장애인표준사업장), 창업기업 

### 연혁

 | 
-: | --
**2022.03** | 공장등록
**2022.02** | 정보통신공사업 등록, 장애인기업 확인, 소기업 확인, 소프트웨어사업자신고, 경쟁입찰참가등록
**2022.01** | ㈜넥스톤 법인설립

## 인증서 {#certificates}

종류 | 다운로드
---- | --------
사업자등록증 | [넥스톤_사업자등록증.pdf](넥스톤_사업자등록증.pdf)
장애인기업 확인서 | [넥스톤_장애인기업확인서.pdf](넥스톤_장애인기업확인서.pdf)
소기업 소상공인 확인서 | [넥스톤_소기업소상공인확인서.pdf](넥스톤_소기업소상공인확인서.pdf)
정보통신공사업등록증 | [넥스톤_정보통신공사업등록증.pdf](넥스톤_정보통신공사업등록증.pdf)
창업기업 확인서 | [넥스톤_창업기업확인서.pdf](넥스톤_창업기업확인서.pdf)
소프트웨어사업자 일반 현황 관리확인서 | [넥스톤_소프트웨어사업자일반현황관리확인서.pdf](넥스톤_소프트웨어사업자일반현황관리확인서.pdf)

## 사업 실적 {#results}

 | 
-- | --
 |

## 오시는 길 {#contact}

<script type="text/javascript" src="//dapi.kakao.com/v2/maps/sdk.js?appkey=b38d90863b5a02a908e28cc28dccf318"></script>
<div id="company-map" style="width:100%; height:500px"></div>
<script>
  var container = document.getElementById('company-map');
  var options = {
    center: new kakao.maps.LatLng(37.4844101022522, 126.893265600121),
    level: 4,
    mapTypeId : kakao.maps.MapTypeId.ROADMAP
  };
  var map = new kakao.maps.Map(container, options);
  var mapTypeControl = new kakao.maps.MapTypeControl();
  map.addControl(mapTypeControl, kakao.maps.ControlPosition.TOPRIGHT);	
  var zoomControl = new kakao.maps.ZoomControl();
  map.addControl(zoomControl, kakao.maps.ControlPosition.RIGHT);
  var marker = new kakao.maps.Marker({
    position: map.getCenter(),
    title: '{{< param "company_address" >}}',
    clickable: true
  });
  marker.setMap(map);
  kakao.maps.event.addListener(marker, 'click', function() {
    window.open('https://map.kakao.com/link/map/12939518');
  });
</script>
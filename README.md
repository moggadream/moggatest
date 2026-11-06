# 아이 집공부 AR 놀이 자료 — 시장성·경쟁사·벤치마킹 보고서

- 작성일: 2026-11-04 조사, 2026-11-06 정리
- 대상 사업: 유니티·모바일 AR 경험으로 만드는 "휴대폰을 비추면 움직이는 아이 집공부 인쇄 자료" 해외(영어권) 판매
- 근거 문서: `비즈니스모델-유니티-개발모바일-AR-경험으로-만드는-아이-집공부-AR-놀이-자료-해외-2026-11-03.md`

---

## 한 줄 결론

**시장성은 있다. 다만 "앱 설치 없이 QR로 바로 보는 AR"이어야 이길 수 있다.**
인쇄 학습 자료 시장은 이미 크고 검증돼 있으며, 그 안에서 'AR 인쇄 자료'를 파는 판매자는 아직 1~2명 수준이다. 가장 큰 위험은 무료 앱(Quiver)과 부모가 앱을 설치해야 하는 번거로움이다.

---

## 1. 시장성

### 1-1. 좋은 신호

| 항목 | 내용 | 이 사업에 주는 의미 |
|---|---|---|
| 미국 홈스쿨 성장 | 2024~25학년도 평균 4.9% 성장, 코로나 이전(약 2%)의 약 3배. 홈스쿨 학생 약 340만~400만 명 추정 | 집에서 쓸 학습·놀이 자료를 사는 사람이 늘고 있음 |
| 인쇄 자료 판매 수익 사례 | 유치원 교사 1명이 디지털 자료 400여 종으로 연 12만5천 달러 이상. TPT에서 누적 100만 달러 넘게 번 교사 300명 이상(2022 기준) | 인쇄 자료는 개인 판매자가 돈을 버는 검증된 시장 |
| 가격 근거 ($9) | 거의 같은 상품(공룡 학습지 + AR, 앱 설치 없음, 4~8세)이 Gumroad에서 **$9.99** | 계획한 단품 $9는 시장 가격대 |
| 구독 근거 ($6) | 인쇄 STEM 자료 구독(Little Bins)이 월 $7~12 | 계획한 월 구독 $6은 오히려 저렴한 편 |
| AR 교육 시장 | AR·VR 교육 시장 2025년 약 155억~170억 달러 추정(보고서마다 범위 다름, 유아 단독 수치는 없음) | 방향성 참고용. 직접 매출 근거로 쓰지 말 것 |

### 1-2. 주의할 점

1. **무료 경쟁자.** Quiver 앱은 무료이며 AR 색칠 도안이 350장 이상이다. "색칠하면 움직인다"만으로는 돈을 받기 어렵다. → **"집공부 목적 + 연령별 난이도 + 20분짜리 놀이 구성"**을 앞에 내세워야 한다.
2. **앱 설치가 걸림돌.** 경쟁 제품 대부분은 앱을 깔아야 한다. QR을 찍으면 바로 열리는 **웹 AR**이 사실상 필수.
   - 유니티(AR Foundation)로 만들면 앱 설치가 필요해 이 장점이 사라진다. 웹 AR은 주로 자바스크립트로 만든다. 3D 모델·애니메이션 제작 실력은 그대로 쓸 수 있다.
   - 웹 AR 서비스로 많이 쓰던 **8th Wall은 2026년 2월 28일 신규 작업 종료, 2027년 2월 28일 호스팅 종료**. 엔진은 오픈소스(MIT)로 공개됐으므로 직접 올려 쓰거나 다른 서비스(ARLOOPA, Kivicube, ZapWorks, Blippar 등)를 써야 한다. 오픈소스 이미지 인식 라이브러리(MindAR 등)도 후보.
3. **3~4세는 휴대폰을 잘 못 든다.** 어린아이는 기기를 가만히 들고 있기 어렵다는 리뷰가 있다. → 3~4세 묶음은 **부모가 비추고 아이는 화면을 터치**하는 방식으로 설계.
4. **판매 수수료.** TPT는 무료 판매자 몫 50%, 연 $59.95 유료 회원은 80%. 2단계 매출 목표(52만 원)는 수수료를 뺀 금액으로 다시 계산할 것.
5. **시장 규모 수치는 신뢰도가 낮다.** 홈스쿨 인쇄 자료 시장만 따로 잰 최근 보고서는 찾지 못했다(가장 가까운 수치는 2014년 '보충 디지털 교재 시장 약 9억 달러').

---

## 2. 경쟁사 분석

| 구분 | 경쟁사 | 형태·가격 | 나와 다른 점 |
|---|---|---|---|
| 해외·직접 | **MaryMariiARt** (엣시) | 미로·색칠·점잇기 인쇄물 + QR로 AR | 가장 비슷한 판매자. 연령별 묶음·구독은 확인되지 않음 |
| 해외·직접 | **공룡 AR 학습지** (Gumroad) | $9.99, 4~8세, 앱 설치 없음 | 가격·형태 거의 같음. 주제 1개뿐 |
| 해외·간접 | **Quiver** (QuiverVision) | 무료 앱(인앱 결제) + 도안 350장 이상, 학교용 유료판(Quiver Education) | 가장 큰 무료 경쟁자. 놀이·학습 구성보다 색칠 중심. 전용 도안만 인식 |
| 해외·간접 | **Octagon Studio 4D+** | 실물 AR 카드(동물·우주·알파벳 등 26장), 약 $15 | 실물 상품이라 배송 필요. 4세 이상 |
| 해외·간접 | **Borble AR Cards** | 3~7세 색칠 카드 + 앱, 2026년 1월 출시 | 신생. 연령대가 나와 같음 |
| 국내 | **컬러팝업** | AR 컬러링북 출판사, 웅진북센 통해 서점 유통 | 종이책 형태 |
| 국내 | **모닝글로리** | AR 컬러링북 2종(동물·공룡), 안드로이드 전용 앱 | 문구 대기업, 실물 책 |
| 국내 | **비상교육 AR영어 / 웅진씽크빅 AR Science** | 교재에 딸린 AR 앱 | 대형 교육사의 교재 부가 기능 |

**정리**
- 국내는 대형 출판사·문구사가 **종이책**으로 하고 있고, 해외 인쇄 자료 장터에는 **개인 판매자 1~2명** 수준. 해외로 방향을 돌린 판단이 맞다.
- **"연령별 묶음 + 매달 오는 구독 + 앱 설치 없음"을 함께 갖춘 판매자는 찾지 못했다.** 이 조합이 비어 있는 자리다.

---

## 3. 학습·벤치마킹용 SNS 채널 3개

### ① Busy Toddler (인스타그램 @busytoddler) — 놀이 콘텐츠 → 유료 자료 흐름
- 엄마 한 명이 2015년 시작한 놀이 아이디어 계정, 팔로워 240만 명 이상.
- 무료 놀이 영상으로 사람을 모은 뒤 유료 PDF 커리큘럼(Playing Preschool, 2.5~5세)을 판매.
- **볼 것:** 짧은 영상 구성, 영상 문구, 판매 링크 위치. 로드맵의 "아이 반응 영상 → 판매 페이지" 흐름과 같다.

### ② Little Bins for Little Hands — 구독 상품 짜는 법
- 인쇄 STEM 자료를 월 구독으로 판매, 구독자 20만 명 이상, 12년 이상 운영.
- 월간·연간·평생 요금 + 매달 새 과학·미술 계획 + 상점 20% 할인.
- **볼 것:** 요금 구성, 가입 안내 페이지. 3·4단계(구독 $6, 내 판매 사이트)의 견본.

### ③ MaryMariiARt (엣시 상점) — 직접 경쟁자
- 형태가 1~2단계 상품과 거의 같다.
- **볼 것:** 상품명, 대표 사진, "QR 찍는 법" 안내, 후기 수. 이것보다 한 단계 위로 만들면 된다.

> ⚠️ MaryMariiARt와 Little Bins의 인스타그램·틱톡 계정, 엣시 판매량은 웹 검색으로 확인되지 않았다. 각 사이트의 SNS 링크와 상점 페이지에서 직접 확인할 것.

---

## 4. 바로 할 일

1. **기술 검증 먼저:** 1단계 자료를 만들기 전에, 앱 설치 없이 QR로 열리는 웹 AR 그림 1개를 만든다. 아이폰·안드로이드 2대에서 잘 열리면 가장 큰 기술 위험은 넘긴 것.
2. **차별점 문구 정하기:** "Quiver는 색칠, 나는 20분짜리 집공부 놀이 + 연령별 난이도 + 앱 설치 없음".
3. **경쟁 상점 직접 확인:** MaryMariiARt·Gumroad 공룡 키트의 후기 수, 대표 사진, 설명 문구를 캡처해 두고 내 상품 페이지와 비교.
4. **수수료 반영:** 2단계 목표 매출을 판매 장터 수수료를 뺀 금액으로 다시 잡기.

---

## 출처

**시장**
- [Johns Hopkins — 홈스쿨 성장](https://education.jhu.edu/edpolicy/?p=1793)
- [Reason — 홈스쿨 역대 최고](https://reason.com/2025/11/19/homeschooling-hits-record-numbers/printer)
- [The Tilt — 인쇄 자료 판매 교사 사례](https://www.thetilt.com/?p=45587)
- [TPT 거래 연구](https://spencergreenhalgh.com/research/2020-koehler-et-al-tpt/)
- [Marketplace — 보충 디지털 교재 시장(2014)](https://www.marketplace.org/2014/12/12/teachers-needs-drive-growing-online-marketplace/)
- [MarketsandMarkets — AR·VR 교육 시장](https://www.marketsandmarkets.com/Market-Reports/virtual-classroom-market-203811025.html)
- [GII — AR·VR 교육 시장](https://www.giiresearch.com/report/sky1897336-augmented-virtual-reality-education-market-size.html)

**경쟁사**
- [MaryMariiARt 보도자료](https://business.mammothtimes.com/mammothtimes/article/getnews-2025-5-7-marymariiart-childrens-printable-activities-come-to-life-with-ar) · [엣시 상점](https://www.etsy.com/shop/marymariiart)
- [Gumroad 공룡 AR 학습지](https://quirksheets.gumroad.com/l/quirksheets)
- [Quiver 앱](https://quivervision.com/products/apps) · [Common Sense 리뷰](https://www.commonsense.org/education/reviews/quiver-3d-coloring-app)
- [Octagon Animal 4D+](https://www.desertcart.co.uk/products/48910104-animal-4d.md)
- [Borble AR Cards](https://www.producthunt.com/p/borble-ar-cards)
- [컬러팝업](https://nextunicorn.kr/content/9f6c29fa96311185) · [모닝글로리](https://www.ajunews.com/view/20230106155226910) · [비상교육 AR영어](https://apps.apple.com/us/app/-/id1356441187) · [웅진 AR Science](https://www.asiae.co.kr/en/article/2021011514212683405)

**기술**
- [Road to VR — 8th Wall 오픈소스 전환](https://www.roadtovr.com/niantic-webar-platform-8th-wall-open-source/)
- [Niantic — 8th Wall 종료 일정](https://info.nianticspatial.com/blog/next-chapter)

**벤치마킹 채널**
- [Busy Toddler](https://busytoddler.com/easy-indoor-activity-list/)
- [Little Bins Club](https://members.littlebinsforlittlehands.com/littlebins-club/) · [요금 페이지](https://littlebinsforlittlehands.com/little-bins-club)

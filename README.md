# 우연의 과학통계학 — 2장 통계적 추정

**박사·하루(조수)·초파리 연구원·주판봇** 네 캐릭터가 진행하는 인터랙티브 통계 해설 시리즈의 2장입니다.
표본 한 줌으로 모집단을 말하는 법 — 점추정과 신뢰구간에서 시작해 정규·t·χ²·F 분포, 표본분포와 자유도, 실습과 종합을 거쳐 100문항 모의고사로 마무리합니다.
서버나 설치 없이 브라우저에서 바로 열리는 정적 HTML이라 GitHub Pages에 그대로 올릴 수 있습니다.

**사이트 주소:** https://adminmrobo.github.io/statistics_note_ch04_statistical-estimation/

## 해설 페이지

| 번호 | 제목 | 다루는 개념 | 대결 | 파일 |
|---|---|---|---|---|
| 2.1.a | 점추정과 신뢰구간 | 모수·통계량, 점추정, 표본평균의 분포, 표준오차, 신뢰구간의 뜻 | 초파리 승 | [`2-1a_point_interval.html`](2-1a_point_interval.html) |
| 2.1.b | 신뢰구간 실습 | 봉인된 모집단으로 95·99% 구간 1,000번 채점, 내 CSV 열기 | 초파리 승 | [`2-1b_ci_practice.html`](2-1b_ci_practice.html) |
| 2.2 | 정규분포에서 신뢰구간 사례까지 | 정규분포, 표준화·z표, 중심극한정리, 평균의 z·t 구간, 비율 구간, 표본 크기 | 주판봇 승 | [`2-2_normal_distribution.html`](2-2_normal_distribution.html) |
| 2.3 | t·카이제곱·F 분포 | t분포, χ²분포와 분산 구간, F분포와 분산 비 | 초파리 승 | [`2-3_t_chi_f.html`](2-3_t_chi_f.html) |
| 2.4 | 표본분포와 모비율 | 가능한 모든 표본, 표본평균 확률, 유한 모집단 보정, 표본비율 | 주판봇 승 | [`2-4_sampling_distribution.html`](2-4_sampling_distribution.html) |
| 2.5 | 표본 크기와 자유도 | 자유도, n과 n − 1, 베셀 보정, 자유도가 쓰이는 곳 | 조건부 | [`2-5_degrees_of_freedom.html`](2-5_degrees_of_freedom.html) |
| 2.6 | 신뢰구간 코드 복습 | 코드의 흔한 실수, 표본 크기와 폭, 시계열에 구간을 쓰면 안 되는 이유 | 무승부 | [`2-6_ci_code_review.html`](2-6_ci_code_review.html) |
| 2.7 | 맥주 효모와 t분포 | 고셋의 소표본 문제, n별 적중률, 효모 t 구간 계산기 | 주판봇 승 | [`2-7_beer_yeast_t.html`](2-7_beer_yeast_t.html) |
| 2.8 | 의료 데이터 실습 | 변수별 95% 구간, 남녀 차이 구간(Welch), 기준값 비율, 다중 비교 | 주판봇 승 | [`2-8_medical_data.html`](2-8_medical_data.html) |
| 2.9 | 신뢰구간 추정 종합 | 분포 고르기 마법사, z·t·χ²·F 구간, 구간에서 의사결정까지 | 조건부 | [`2-9_ci_synthesis.html`](2-9_ci_synthesis.html) |
| 2.10 | 모의·연습문제 퀴즈 | 100문항(객관식 50·OX 25·단답 25), 전체 50문제·묶음별 20문제 | — | [`2-10_mock_exam.html`](2-10_mock_exam.html) |

2.2는 정규분포(a)·z표와 중심극한정리(b)·평균의 신뢰구간 사례(c)·비율의 신뢰구간 사례(d)를 한 페이지로 묶었습니다.

## 2.10 모의고사

- **모드:** 전체 모의고사 50문제(다섯 묶음에서 객관식 5·단답 3·OX 2씩) 또는 묶음별 20문제 — A 점추정과 신뢰구간 · B 정규분포·중심극한정리·비율 · C t·χ²·F 분포 · D 표본분포와 자유도 · E 실습과 종합
- 매번 무작위로 뽑고 보기 순서도 섞음. 타이머(객관식 40초·OX 20초·단답 60초)와 효과음은 켜고 끌 수 있음
- 단답식은 답을 떠올린 뒤 정답을 보고 스스로 채점
- 문항마다 해설과 **다시 읽을 페이지 위치 링크**, 결과 화면에 묶음별 막대와 틀린 문항 다시 보기
- 키보드: 객관식 1~4, OX는 O/X, 다음 문제 Enter
- 인쇄용: [`pdfs/mock-exam-ch2.pdf`](pdfs/mock-exam-ch2.pdf) (50문항 → 정답표 → 해설)

## 폴더 구조

```
.
├── index.html                        # 2장 목차 (사이트 첫 화면)
├── 2-1a_point_interval.html          # 2.1.a ~ 2.9 해설 페이지 — 각각 그림·데이터를 모두 품은 단일 파일
├── 2-1b_ci_practice.html
├── 2-2_normal_distribution.html
├── 2-3_t_chi_f.html
├── 2-4_sampling_distribution.html
├── 2-5_degrees_of_freedom.html
├── 2-6_ci_code_review.html
├── 2-7_beer_yeast_t.html
├── 2-8_medical_data.html
├── 2-9_ci_synthesis.html
├── 2-10_mock_exam.html               # 2.10 모의·연습문제 퀴즈 게임
├── data/
│   ├── ch4_scores400.csv             # 2.1.b·2.6 실습 파일 (성적 400명)
│   ├── death.csv                     # 2.1.b·2.6 실습 파일 (사망 나이 21,458명)
│   └── simulated_patient_data.csv    # 2.8 실습 파일 (가상 환자 1,000명)
├── pdfs/
│   └── mock-exam-ch2.pdf             # 인쇄용 모의고사
├── assets/
│   ├── thumb_2_*.png                 # 목차 카드 썸네일 (600×400)
│   ├── og_2_*.png                    # 링크 공유 미리보기 (1200×630)
│   └── characters/                   # 목차 등장인물 카드용 표정 4장 (WebP)
├── production/                       # 제작 문서 (사이트에서 링크하지 않음)
│   ├── IMG_00_index.md               # 이미지 명세서 · 외부 의뢰 프롬프트
│   └── KG_00_registry.json           # 시리즈 지식 그래프 등록부 v0.4
├── .nojekyll                         # Jekyll 처리 끄기
└── README.md
```

## GitHub Pages로 공개하기

1. GitHub에서 저장소 `statistics_note_ch04_statistical-estimation`을 만든다(Public).
2. 이 폴더의 파일을 모두 저장소 맨 위(root)에 올린다.
   ```bash
   git init
   git add .
   git commit -m "우연의 과학통계학 2장 통계적 추정: 2.1.a~2.10"
   git branch -M main
   git remote add origin https://github.com/adminmrobo/statistics_note_ch04_statistical-estimation.git
   git push -u origin main
   ```
   웹에서 올릴 때는 **Add file → Upload files**로 폴더째 끌어다 놓는다. 점으로 시작하는 `.nojekyll`이 빠지지 않았는지 확인한다.
3. **Settings → Pages**에서 **Source: Deploy from a branch**, **Branch: `main` / `/ (root)`**를 고르고 저장한다.
4. 1~2분 뒤 위 사이트 주소에서 목차가 열린다.

> 페이지 안의 주소(공유 미리보기 `og:image`, 인용 주소, `page_meta.json`의 `url`)는 모두 위 저장소 이름을 기준으로 적혀 있다. **저장소 이름을 바꾸면** 각 HTML에서 `statistics_note_ch04_statistical-estimation`을 새 이름으로 일괄 바꾼다. GitHub Pages 주소는 대소문자를 구분한다.
>
> 기존 저장소(예: `statistics_note_ch04_Statistical-Estimation_01_a`)의 내용을 이 저장소로 교체하는 경우, 옛 파일을 지운 뒤 이 폴더 전체를 올린다.

## 로컬에서 보기

`index.html`을 더블클릭하면 된다. 페이지끼리의 링크(목차 ↔ 각 페이지 ↔ 이전·다음, 모의고사 해설 링크)는 같은 폴더 안의 상대 경로라 그대로 동작한다. 인터넷이 끊기면 글꼴만 시스템 글꼴로 바뀐다.

## 페이지 안에 든 것

- 개념 사다리와 칸마다 직접 만지는 시뮬레이션·계산기(시드 고정 설명용 모형)
- 초파리 연구원 vs 주판봇 대결 — 결과는 페이지 안 계산으로 정해짐 (초파리 3 · 주판봇 4 · 조건부 2 · 무승부 1)
- "한 번 더 짚어 보기" 상자 — 계산·해석에서 헷갈리기 쉬운 점을 정리한 부분
- 확인 퀴즈 69문항(페이지 안) + 모의고사 100문항, 용어 말풍선, 읽은 곳·퀴즈 진행 도우미
- 지식 색인(검색·관계 그래프)과 온톨로지·서지 꾸러미(JSON-LD, Turtle, CSV, CSL-JSON, BibTeX, RIS를 ZIP으로 내려받기)
- 실습 파일을 페이지 안에 그대로 넣어 계산: 2.1.b·2.6 — 중간고사 성적 400명(`data/ch4_scores400.csv`)과 유명인 사망 나이 21,458명(`data/death.csv`, 실제 데이터인 [Kaggle Celebrity Deaths](https://www.kaggle.com/datasets/hugodarwood/celebrity-deaths) 2006~2016에서 추정 대상인 나이 열만 뽑은 파일, 이용 조건은 원본을 따름) · 2.8 — 가상 환자 1,000명(`data/simulated_patient_data.csv`)
- 2.1.b·2.8은 **내 CSV 열기**로 다른 파일을 열어 같은 계산을 해 볼 수 있음
- 외부 스크립트·브라우저 저장소를 쓰지 않음. 외부 요청은 Google Fonts 글꼴 하나

## 출처와 크레딧

- 글·구성: 안상선 ((주)M-Robo 대표) · AI 보조 제작
- 캐릭터 그림: [adminmrobo/fruitfly-lab-expressions](https://github.com/adminmrobo/fruitfly-lab-expressions)
- 각 페이지의 참고 자료(Neyman 1937, Student 1908, 분포·신뢰구간 문서, R·SciPy 함수 문서)는 페이지 맨 아래 출처 표와 꾸러미의 `references.*` 파일에 있다.
- 수치 예제(회사·제품·환자 등)는 수업용 예시값이며 실제 기업·개인의 자료가 아니다.

## 이 시리즈 인용하기

안상선 (2026). 우연의 과학통계학 — 2장 통계적 추정. https://adminmrobo.github.io/statistics_note_ch04_statistical-estimation/

## 라이선스

(정해지면 적는다. 글·코드와 캐릭터 그림의 라이선스를 따로 적는 것을 권한다.)

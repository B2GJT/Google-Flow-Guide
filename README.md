# Google Flow 사용법 가이드

## 개요

Google ImageFX / Whisk가 Google Flow로 통합됨에 따라, 기존 노션페이지 형태로 배포하던 사용법 안내 자료를 수강생 가독성 향상을 위해 웹 페이지로 전환한 프로젝트입니다.

- **대상:** Gemini와 Google AI 기반 이미지·영상 생성 (Chapter 2. Google Labs 제대로 쓰기) 과정 수강생
- **목적:** 노션페이지 배포 방식의 한계를 벗어나 언제 어디서나 URL로 접근 가능한 가이드 제공
- **기준 버전:** Google Flow (26년 5월 19일 기준)
- **특이사항:** Google Flow UI 업데이트 시 스크린샷 및 내용 수정이 필요할 수 있습니다.

---

## 페이지 구성

단계별 흐름에 따라 스크린샷과 함께 안내합니다.

| 단계 | 내용 |
|------|------|
| 1 | Google Flow 로그인 하기 |
| 2 | Google Flow 메뉴 소개 |
| 3 | Google Flow 에서 이미지 생성하기 |
| 4-1 | 영상 생성하기 — 이미지(에셋)를 동영상으로 |
| 4-2 | 영상 생성하기 — 프레임을 동영상으로 |
| 5 | 생성한 영상/이미지 확인, 수정하기 |

- **디자인:** Mintlify 스타일 기반 단일 HTML 파일 (외부 프레임워크 없음)
- **구조:** 상단 네비바 + 좌측 목차 사이드바 + 본문

---

## 파일 구조

```
Google-Flow-Guide/
├── google-flow-guide.html            # 가이드 본문
├── images01_login.png                # Step 1 - Google Flow 로그인 화면
├── images02_menu.png                 # Step 2 - 메인 메뉴 구성 화면
├── images03_image_gen.png            # Step 3 - 이미지 생성 환경 설정 화면
├── images03b_image_edit.png          # Step 3 - 이미지 수정([+] 버튼) 화면
├── images04a_video_asset_setting.png # Step 4-1 - 동영상(에셋) 설정 화면
├── images04a_video_asset_prompt.png  # Step 4-1 - 에셋 선택 후 프롬프트 화면
├── images04b_video_frame_setting.png # Step 4-2 - 동영상(프레임) 설정 화면
├── images04b_video_frame_prompt.png  # Step 4-2 - 프레임 설정 후 프롬프트 화면
├── images05a_review.png              # Step 5 - 생성 결과 확인 화면
├── images05b_history.png             # Step 5 - 수정 기록 목록 화면
└── images05c_edit_options.png        # Step 5 - 영상 수정 옵션 화면
```

---

## 수강생 배포 방법

GitHub Pages를 통해 URL을 생성하고 수강생에게 공유합니다.

### 수강생 공유 URL

```
https://b2gjt.github.io/Google-Flow-Guide/google-flow-guide.html
```

---

## 업데이트 방법

스크린샷 교체나 내용 수정이 필요한 경우:

- **이미지 교체:** 해당 이미지 파일을 같은 이름으로 덮어쓴 후 push
- **본문 내용 수정:** `google-flow-guide.html` 수정 후 push
- push 후 수 분 내에 배포 URL에 자동 반영됩니다.
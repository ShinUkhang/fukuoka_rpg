# 후쿠오카 RPG — 규슈국제대학 부속고등학교

40년째 이어지는 자매교류를 배경으로 한 탑다운 픽셀 RPG 게임.
한국 교환학생이 되어 하카타역에서 출발 → 다자이후텐만구 → 나카스 야타이 →
고쿠라성 → 모지코 레트로를 거쳐 규슈국제대학 부속고등학교에 도착한다.

- 한국어 / 日本語 / English 3개 언어
- 4곳의 그림 퀴즈 (실제 사진 보고 맞히기)
- 퀴즈 정답 시 실제 사진 수집
- 학교 가는 길 할머니 간식 이벤트 (오뎅 / 니쿠만 / 아마자케 중 1개, +30점)
- 로컬 명예의 전당, 모바일 방향 패드, WebAudio 효과음
- 사진 5종 HTML 내장 (base64) — 인터넷 없이 실행 가능
- 맵 디테일: 고쿠라성 해자, 나카스 강변, 하카타역·모지코역 역무원, 성의 다이묘, 텐만구 참배객

## 실행

`index.html`을 브라우저로 열면 바로 실행된다. (단일 파일, 외부 의존성 없음)

## 사진 출처 · 라이선스

| 사진 | 출처 | 라이선스 | 촬영자 |
|---|---|---|---|
| 다자이후텐만구 본전 | Wikimedia Commons — `File:Dazaifu Tenmangu Shrine Honden (Main Prayer Hall).jpg` | CC BY-SA 4.0 | ScribblingGeek |
| 나카스 야타이 | Wikimedia Commons — `File:Nakasu Yatai Stalls (19979437930).jpg` | CC BY 2.0 | Yoshikazu TAKADA |
| 고쿠라성 | Wikimedia Commons — `File:Kokura Castle.jpg` | CC BY 4.0 | Stjepko Krehula |
| 모지코역 | Wikimedia Commons — `File:Mojiko Station 20221023-2.jpg` | CC BY-SA 4.0 | Suicasmo |
| 규슈국제대학 부속고등학교 | 학교 공식 사이트 https://www.kif.ed.jp/ (`lib/images/history_image007.jpg`) | 학교 공식 사이트 게재 사진 (자매교류 교육용 사용, 출처 표기) | — |

## 테스트

- Node DOM 스텁 하네스: 164개 체크 PASS (`/tmp/fk_test.js`)
- 실제 Chromium 헤드리스 렌더링 확인: 타이틀(한/일), 6개 장소, 대화창, 사진 퀴즈 — 콘솔 오류 없음

# 자산 출처 · Asset provenance

내방핏에 들어가는 그림·소리·영상·모델의 출처. 공개 저장소에 올리기 전에 이 표와 대조.
Where Naebangfit's images, sounds, videos and models come from. Checked against this list before anything is published.

## 앱 · App (`index.html`, `media/`)

| 자산 · Asset | 출처 · Source | 비고 · Notes |
|---|---|---|
| 앱 코드, 화면 디자인, 로고(핏), 사이트 아이콘 · App code, UI design, logo, site icons | 직접 제작 · Original | |
| 가구 3D (침대, 책상, 의자 등) · Furniture 3D | 직접 제작, three.js 코드로 그림 · Original, drawn in three.js code | |
| 리그·휠·퀵릴리즈·모니터암·라이트바 등 3D 모델 (`NM`) · Rig, wheel, quick release, monitor arm, light bar models | 직접 제작, CadQuery로 모델링 · Original, modelled in CadQuery | 실제 제품은 크기·비율만 참고. 로고·각인·고유 버튼 배치 없음 · Real products used for size and proportion only; no logos, engravings or distinctive button layouts |
| 프로파일 리그 키트 (`RD`) · Profile rig kits | 제작자의 SketchUp 모델을 바탕으로 다시 만듦 · Rebuilt from the author's own SketchUp models | 범용 알루미늄 프로파일 (40×40, 40×120 등) · Generic aluminium profiles |
| 주행 영상 (`media/day_*`, `night_*`, `nbf_drive.mp4`, `shot.jpg`) · Driving footage | 직접 렌더링: 가상 서킷 v3, 자체 콕핏·차량, 광고판 NAEBANGFIT · Original renders: virtual circuit v3, own cockpit and car | 실제 서킷 레이아웃·차량 디자인·로고 없음 · No real circuit layouts, car designs or logos |
| └ 하늘(HDRI)·바닥 텍스처 · Sky (HDRI), ground textures | Poly Haven, ambientCG | CC0 |
| └ 나무 · Trees | EZ-Tree로 생성 · Generated with EZ-Tree | MIT. 렌더링에만 사용, 배포 안 함 · Used for rendering only, not distributed |
| └ 엔진 소리 · Engine sound | Sonniss #GameAudioGDC 2020 번들 녹음을 잘라 RPM에 맞춰 섞음 · Cut and mixed from the Sonniss #GameAudioGDC 2020 bundle | 로열티 프리, 표기 의무 없음. 원본 재배포·AI 학습 금지 → 원본 wav는 저장소에 없음 · Royalty free, no credit required; originals may not be redistributed or used for AI training, so the source wavs are not in this repository |
| 주행 데이터 (`NBF_TEL`: 기어·RPM·핸들) · Driving data (gear, RPM, steering) | 직접 만든 주행 시뮬레이션에서 생성 · From our own driving simulation | |
| 변속 클릭 소리 (`SHIFT_WAV`) · Shift click | 제작자가 직접 녹음 · Recorded by the author | |
| 그 밖의 효과음 · Other sound effects | Web Audio로 합성 · Synthesised with Web Audio | |
| 아이콘 대부분 · Most icons | Phosphor Icons (regular) | MIT, THIRD_PARTY_NOTICES.md |
| 리그 카드·스피커·화면 밝기 아이콘 · Rig card, speaker, brightness icons | 직접 제작 · Original | |
| 글꼴 NBF Sans · Font | Pretendard 1.309 서브셋, 이름 변경 · Pretendard 1.309 subset, renamed | SIL OFL 1.1, THIRD_PARTY_NOTICES.md |
| 갤러리 예시 그림, 링크 미리보기 그림 (`docs/og-*`) · Gallery example pictures, link preview images | 앱 화면을 직접 렌더링 · Rendered from the app | |
| 대형 쇼룸 장식: 차 모형(GT·LMP, `CARS`·`CARLIV`), 레이스 슈트·헬멧, 병 라벨, 공구, 굿즈, 타이밍 보드, 로고 · Big Screen Hall props: car models, race suits and helmets, bottle labels, tools, merch, timing board, logo | 직접 제작 (차는 주행 영상용 자체 모델을 줄인 것) · Original (the cars are our own footage models, reduced) | 팀·스폰서·술·드라이버 이름은 모두 가상 (APEXLINE, VELOCE OIL, PODIUM, LATEBRAKER 등). 실제 브랜드·로고·사람 없음 · Every team, sponsor, drink and driver name is made up; no real brands, logos or people |
| 대형 모니터 (42"~65")·대형 스탠드 · Large monitors and the large stand | 직접 제작 · Original | 시판 TV·스탠드의 치수·무게만 참고, 제품 모양·이름 없음 · Only the sizes and weights of TVs and stands on the market were consulted; no product shapes or names |

## 영상 · Videos (`media/guide/`)

| 자산 · Asset | 출처 · Source | 비고 · Notes |
|---|---|---|
| 사용법 영상, 소개 영상, 1.8.0 쇼룸 영상, 시작 화면 배경 · How-to videos, intro video, 1.8.0 showroom video, start screen loop | 내방핏 앱을 직접 촬영·편집 · Recorded and edited from the app | 영어판(`-en`)은 영어 버전 앱으로 따로 촬영 · The English cuts (`-en`) were recorded from the English app |
| 자막 글꼴 · Caption font | Pretendard | OFL은 글꼴로 만든 그림·영상에 제한 없음 · The OFL places no limits on images or video made with the font |
| 소개 영상 · 1.8.0 쇼룸 영상 음악 · Intro and 1.8.0 showroom video music | “Inspired” Kevin MacLeod (incompetech.com) | CC BY 4.0, 편집. 영상을 올리는 곳(설명란 등)에도 같은 표기 · Edited; the same credit goes wherever the video is posted |
| 클릭·효과음 · Clicks and effects | 직접 합성 · Synthesised | |

## 앱과 저장소에서 뺀 것 · Removed from the app and repository

- 예전 iRacing 주행 녹화 영상과 캡처: 앱에서 모두 내림, 저장소에 없음 · Earlier iRacing recordings and captures: removed from the app, never in this repository
- 리그·휠 원본 DAE 메시: 다른 사람이 만든 3D 파일이라 미사용, 직접 모델링한 것으로 교체 · Third-party DAE meshes for rigs and wheels: not used, replaced with our own models
- Sonniss 원본 녹음(wav): 섞은 결과만 영상·앱에 포함 · Sonniss source recordings: only the mixed result is in the videos and app
- 영상 작업 파일(프레임 이미지, 촬영 로그), 테스트·패치 스크립트, 백업 html · Video work files, test and patch scripts, backup html

## 외부 링크 · External links

- dansuzuki FOV 계산기: 링크만 · dansuzuki FOV calculator: link only

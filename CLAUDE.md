# Metal Bunny

크롬 금속 토끼 마스코트 3D 웹페이지 (Three.js, 파일 하나: index.html).
배포: https://legondmonsterball-byte.github.io/metal-bunny/

## 구조
- index.html 하나에 전부. three@0.169.0을 jsdelivr에서 불러옴, 빌드 없음.
- 모양은 코드로 만듦: 머리(볼살 넣은 타원구), 몸(Lathe), 귀(매 프레임 다시 만드는 휘는 튜브 + 스프링 물리).
- 반사는 코드로 만든 스튜디오 HDR, 긁힘은 캔버스 roughness 텍스처.
- 설정(색·귀·표정·이펙트·회전)은 localStorage에 저장.

## 조작
드래그 회전, 탭 = 점프+^^ 표정+반짝이, 귀 탭 = 귀 튕김+놀람. ←/→ 회전, 스페이스 = 탭.

## 프리셋
METALS(색 8종), EARS(Perky/Flop/Lop/Swept), FACES(Happy/Wink/Wow/Sleepy/Love) 객체만 고치면 됨.

## 진행상황
- 2026-10-12 첫 버전 완성·배포 (Opus, effort high)

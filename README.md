# 록맨 X 레거시 컬렉션 1 한글패치

Mega Man X Legacy Collection (Nintendo Switch, 01005C60086BE000) 한글패치입니다.
록맨 X1~X4 의 **일본판(Japanese edition)** 을 한국어로 바꿉니다. 미국판(English edition)은 그대로입니다.

> **⚠ 게임을 고른 화면에서 Y 버튼으로 왼쪽 위 표시를 「Japanese edition」에 맞춘 뒤 시작해야 한국어로 나옵니다.**
> 판은 게임마다 따로 기억되므로 X1·X2·X3·X4 각각 한 번씩 바꿔 주세요.

## 필요한 것

| 항목 | 값 |
|---|---|
| 본편 | 01005C60086BE000 **v0** (업데이트 없음) |
| 실행 파일 빌드 ID | EAD37D36ABD7C4C8CE166564F4A4A7FB |

업데이트를 설치해 실행 파일이 바뀌면 실행 파일 패치(.ips)가 적용되지 않아 X1~X3 이 일본어로 나오고 X4 대사가 깨집니다.

## 설치

### 스위치 (Atmosphere)
`RXLC1_KR_v0.9.0_atmosphere.zip` 을 SD 카드 루트에 풉니다.
- `atmosphere/contents/01005C60086BE000/romfs/...` (X4 대사·글꼴·그림·동영상)
- `atmosphere/exefs_patches/RXLC1_KoreanPatch/EAD37D36ABD7C4C8CE166564F4A4A7FB.ips` (X1~X3 롬·X4 대사 출력기)

### 에뮬레이터 (Eden / yuzu 계열, Ryujinx)
`RXLC1_KR_v0.9.0_emulator.zip` 을 풀면 나오는 `KoreanPatch` 폴더를 게임의 모드 폴더에 넣습니다.
- Eden / yuzu 계열: `load/01005C60086BE000/KoreanPatch/{romfs,exefs}`
- Ryujinx: `mods/contents/01005C60086BE000/KoreanPatch/{romfs,exefs}`

## 한글화 범위

- **록맨 X · X2 · X3**: 일본판 롬의 대사·오프닝 문장 등
- **록맨 X4**: 대사(엑스·제로), 무기 선택 화면 무기 이름, 엔딩 크레딧, 제로 기술 이름 그림, 애니메이션 동영상 9개 한글 자막

컬렉션 메뉴(런처)·박물관·X 챌린지는 바꾸지 않았습니다(본체 언어 그대로).

## 알려진 점

- 에뮬레이터(Eden)에서 X1~X3 오프닝, X4 첫 대사·무기 화면·첫 동영상만 확인한 **시험판**입니다. **스위치 실기는 확인하지 못했습니다.**
- 깨지거나 일본어가 남은 화면을 알려 주세요.

## 내려받기

[Releases](https://github.com/Einbroch/Rockman-X-Legacy-Collection1/releases) 에서 `RXLC1_KR_v0.9.0_atmosphere.zip`(스위치) 또는 `RXLC1_KR_v0.9.0_emulator.zip`(에뮬레이터)을 받으세요.
게임 파일(롬·NSP)은 포함하지 않습니다. 본인이 가진 정품 게임에 적용하세요.

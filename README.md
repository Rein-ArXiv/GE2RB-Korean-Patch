# GOD EATER 2 Rage Burst 한국어 패치 (비공식)

Steam판 GOD EATER 2 Rage Burst의 비공식 한국어 패치입니다.

- 대사 · 컷씬 자막 · 무전 · UI · 아이템 · 스킬 · 불릿 · 튜토리얼 등 게임 내 텍스트 전반 한국어화
- 원본 게임 파일을 포함하지 않는 **바이너리 델타 패치** 방식 (다운로드 약 16MB)
- 원클릭 적용 / 원클릭 복원

## 다운로드

➡ **[Releases](https://github.com/Rein-ArXiv/GE2RB-Korean-Patch/releases/latest)** 에서 `GE2RB_KO_Patch_vX.X.zip` 을 받으세요.

## 요구 사항

- Steam판 GOD EATER 2 Rage Burst (현재 최신 빌드, **순정 상태**)
- 게임 설치 드라이브에 약 11GB의 임시 여유 공간 (원본 자동 백업용)
- 다른 모드/패치가 적용돼 있다면 먼저 Steam 무결성 검사로 순정으로 되돌려 주세요

## 적용 방법

1. 압축을 풀어 나온 `GE2RB_KO_Patch_vX.X` 폴더를 **게임 설치 폴더 안에** 넣습니다.
   - 기본 경로: `C:\Program Files (x86)\Steam\steamapps\common\GOD EATER 2 Rage Burst`
   - Steam 라이브러리 → 게임 우클릭 → 관리 → 로컬 파일 보기
2. 폴더 안의 **`apply_patch.bat`** 을 실행합니다.
   - 순정 확인 → 원본 백업 → 패치 → 검증 순서로 자동 진행됩니다.
   - 파일이 커서(11GB) 단계마다 몇 분씩 걸립니다. 멈춘 것처럼 보여도 기다려 주세요.
3. `한국어 패치 적용 완료!` 가 표시되면 게임을 실행하세요.

## 되돌리기

- 폴더 안의 **`restore_vanilla.bat`** 실행 (적용 시 만든 백업으로 즉시 복원)
- 또는 Steam 무결성 검사 (속성 → 설치된 파일 → 게임 파일 무결성 검사)

## 자주 묻는 질문

**Q. "data.qpck 가 순정이 아닙니다" 라고 나옵니다.**
게임 파일이 수정된 상태입니다. Steam 무결성 검사 후 다시 적용하세요.

**Q. 게임이 업데이트되면요?**
패치가 풀리거나 적용이 거부됩니다. 패치 업데이트를 기다려 주세요. 엉뚱한 파일 위에 덮어쓰는 사고를 막기 위한 해시 검증 설계입니다.

**Q. 백업 파일(`*.vanilla`)은 지워도 되나요?**
지우면 `되돌리기.bat` 를 쓸 수 없습니다. Steam 무결성 검사로는 언제든 복원 가능하므로, 공간이 급하면 지워도 됩니다.

**Q. 세이브는 호환되나요?**
네. 텍스트만 교체하므로 기존 세이브를 그대로 사용하며, 되돌려도 세이브는 유지됩니다.

**Q. 이전 버전에서 바로 업데이트할 수 있나요?**
아니요. `restore_vanilla.bat` 또는 Steam 무결성 검사로 순정 상태를 만든 뒤 최신 버전을 적용하세요.

## v1.1

- 결과 화면·안내 팝업 등 `bin_patch.qpck`의 영어 그림자 사본 한국어화
- 여성용 장비명 조합 단어 71개 영문 잔존 수정
- 최신 대사·용어·어체·불릿·UI 교정본 반영
- v1.0 패키지에서 누락됐던 `hpatchz.exe` 포함
- `data.qpck`, `bin.qpck`, `bin_patch.qpck`을 모두 해시 검증·패치·복원

## 알려진 사항

- 타이틀 화면의 NEW GAME / CONTINUE 메뉴와 일부 로고성 대형 문구는 의도적으로 영어를 유지했습니다.
- 오역·어색한 문장은 [Issues](https://github.com/Rein-ArXiv/GE2RB-Korean-Patch/issues) 로 제보해 주세요. 다음 버전에 반영합니다.

## 안내

- 본 패치는 팬 제작 비공식 패치이며, BANDAI NAMCO Entertainment 및 개발사와 무관합니다.
- 게임 본편을 소유한 계정에서만 사용해 주세요. 패치 파일에는 게임 원본 데이터가 포함되어 있지 않습니다.
- 델타 적용 도구로 [HDiffPatch](https://github.com/sisong/HDiffPatch) (MIT License) 의 `hpatchz` 를 동봉합니다.
- 사용으로 인한 문제의 책임은 사용자 본인에게 있습니다.

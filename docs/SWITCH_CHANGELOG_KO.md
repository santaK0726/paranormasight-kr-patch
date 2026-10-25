## PARANORMASIGHT 한국어 패치 v0.1.3-Switch.1 — Switch1.2 / 미검수

Nintendo Switch 본편 `01006E5019C5A000` + 업데이트 **1.2(131072)** 대상입니다.
일본어 원문 기반 번역이며 English 언어 슬롯에 적용합니다. PCv0.1.3의 번역·폰트·이미지 수정을 이식했습니다.

### 다운로드와 생성
Assets의 **PARANORMASIGHT_KR_Switch_v0.1.3-Switch.1_20261026.zip**을 받아 압축을 풀고 `PARANORMASIGHT_KR_Switch_Generator.exe`를 실행하세요.

이 공개 꾸러미는 **원본1.2 RomFS가 필요한 차분 생성기**입니다. NSP/NCA·완전한 게임 자산·키·원문 추출·세이브를 제공하지 않습니다. Windows10/11 x64(.NET Framework4.8)에서 모드를 생성하며 Python/인터넷/키 파일 입력은 필요 없습니다.

1. 본인 게임의 업데이트1.2가 합쳐진 원본 RomFS를 준비합니다. Eden에서는 한글 모드를 끄고 Update1.2를 활성화한 뒤 게임 우클릭 → Dump RomFS로 전체를 덤프할 수 있습니다.
2. 생성기에서 원본 `Data` 폴더와 새 출력 위치를 선택하고 Eden/실기/모두 중 필요한 환경을 선택합니다.
3. **Eden:** 생성된 `Eden/PARANORMASIGHT_KR_Switch_test001` 폴더를 게임의 Open Mod Data Location에 복사합니다. 제목ID 폴더 바로 아래에 romfs/exefs만 풀면 모드가 목록에 안 뜹니다. 게임 속성에서 모드와 Update1.2를 각각 활성화합니다.
4. **실기 Atmosphère:** 생성된 `Atmosphere/atmosphere` 폴더를 SD 카드 루트에 복사합니다. 게임은 종료하고 같은 게임의 다른 번역 모드와 중복 적용하지 마세요.
5. 게임 언어를 한국어(English 슬롯)로 선택합니다. 제거는 이 모드의 파일만 치우며 세이브는 변경하지 않습니다.

### 확인 범위
2026-10-26 사용자가 Eden용과 실기용이 잘 동작하는 것으로 보고했습니다. 공개 생성기를 실제 실행해 양쪽 모드의8자산과 입력 IPS를 재구성했고, 사용자가 시험한 파일과 SHA256이 같음을 확인했습니다. 지원하지 않는/이미 패치된 원본은 거부합니다.

전체 완주·사람의 전 구간 번역 검수 완료를 뜻하지 않습니다. PC 전용 긴 이름 자동 폭 조절·긴 자료 동적 배치·이름 마크업 보조 코드는 미이식이며, 해당 표시 문제가 남을 수 있습니다. AI를 활용한 미검수 팬 패치로 pre-release 배포합니다.

PC판과 파일/설치 방식이 다릅니다. [기존 PC v0.1.3](https://github.com/santaK0726/paranormasight-kr-patch/releases/tag/v0.1.3)은 그대로 유지됩니다.

ZIP SHA256: `e7cb59d17d8b78b828907daf00b8e298a84bd9ddb0ada451d64738458ca4260b`
배포글: https://cafe.naver.com/hansicgu/37692

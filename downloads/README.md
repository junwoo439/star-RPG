# StarRPG 1.5.0 Eclipse 다운로드

[StarRPG 1.5.0 Eclipse 프로젝트 ZIP 다운로드](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v1.5.0/downloads/StarRPG-1.5.0-Eclipse.zip)

Minecraft 1.21.1 / NeoForge 21.1.235 / Java 21. 안쪽 StarRPG_Mod 폴더를 Gradle 프로젝트로 가져와 StarRPG Client를 실행합니다.

- 월드 5단계에서 개체 3/4/5단계가 섞여 등장. 개체별 차이 저장, 기존 몬스터는 한 번 새 규칙으로 이전.
- 좀비 추가 능력치 보정 25% 감소, 최고 단계 지급 방어구 2~3부위와 혼합 재질, 지급 무기 철검·인챈트 최대 I. 원래 장비/주운 장비는 보존.
- 적 처치 골드, 사망 후 유지되는 UUID 지갑, 온라인 송금, `/starrpg shop` 재료 상점.
- 별가루 20G / 별조각 200G / 일반 룬 120G. 잔액·인벤토리 공간 검증 후 일괄 결제·지급.
- `/starrpg mods`로 실제 모드 로드 여부 확인.

**외부 모드 설치 상태:** 이 ZIP에 외부 모드 JAR은 없습니다. Mowzie's Mobs/GeckoLib은 기존 파일을 run-client/mods에 유지하세요. Twilight Forest는 install-adventure-mods.bat으로 설치하도록 도구와 보스 태그를 준비했지만, 클라우드 네트워크 정책 차단으로 실제 다운로드/통합 실행은 완료하지 못했습니다. Ice and Fire는 호환 공식 빌드를 확인하지 못해 제외했습니다. 자세한 내용은 MODS-1.5.md를 확인하세요.

기존 프로젝트와 월드를 백업하고 TESTING-1.5.md를 따르세요. 기존 프로젝트를 갱신할 때 run-client를 보존하면 월드와 추가 모드가 유지됩니다.

빌드, NeoForge GameTest 65개, Eclipse 실행 구성/클라이언트 준비 통과. 외부 모드 설치 도구는 가짜 배포 파일로 다운로드 검증·백업·반복 설치·실패 시 보존을 검사했습니다. 실제 Windows 화면/외부 모드팩 실행을 검증한 것은 아닙니다. 앞서 평가만 요청한 직업·무기 액티브·전면 인챈트 제거는 이번에 구현하지 않았습니다.

---

## 이전 버전

# StarRPG 1.4.0 Eclipse 다운로드

[StarRPG 1.4.0 Eclipse 프로젝트 ZIP 다운로드](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v1.4.0/downloads/StarRPG-1.4.0-Eclipse.zip)

Minecraft 1.21.1 / NeoForge 21.1.235 / JDK 21. Eclipse에서 **StarRPG Client → 싱글플레이**로 실행합니다.

- 일반 룬 9개 → 희귀 룬 1개. 별조각 불필요. 희귀 이상 승급 조합은 유지.
- 방어구 80종: 각 부위/등급마다 4개 후보 중 하나를 각인. 동급 재각인 지원, 기존 각인 보존, 버튼에 마우스를 올려 후보 확인.
- 활·석궁·삼지창 룬 60종과 강화 지원. 발사 무기 데이터, 충전량, 재사용 시간, 광역 상한 적용. 석궁 폭죽은 제외.
- 새 무기: 별빛 단검(빠른 공격·후방 보너스), 별철 전투 망치(느린 강타·일시 방어 감소). 조합·강화·검/도끼 룬·인챈트·전용 아이콘 포함.
- 전체 룬 180종. 서브 직업은 추가하지 않았습니다.

기존 프로젝트를 백업하고 ZIP 안 TESTING-1.4.md의 적용 순서를 따르세요. 새로 가져올 때는 바깥 폴더가 아니라 build.gradle이 있는 StarRPG_Mod를 Existing Gradle Project로 선택합니다. run-client를 유지하면 기존 월드와 추가 모드가 남습니다.

빌드, 자동 GameTest 55개, Eclipse 실행 설정/클라이언트 준비 통과. 실제 Windows Eclipse 화면과 무기 모델·장시간 전투감·외부 모드팩 호환은 PC에서 확인해야 합니다.

---

## 이전 버전

# StarRPG 1.3.0 Eclipse 다운로드

[StarRPG 1.3.0 Eclipse 프로젝트 ZIP 다운로드](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v1.3.0/downloads/StarRPG-1.3.0-Eclipse.zip)

Minecraft 1.21.1 / NeoForge 21.1.235 / JDK 21. Eclipse에서 **StarRPG Client → 싱글플레이**로 실행합니다.

- 방어구 4부위 × 5등급 룬: 정화, 투사체 방어, 밀쳐짐/갈고리 저항, 질주 속도.
- 월드 2단계부터 냉기 화살 스켈레톤, 독 도약 거미.
- 룬 각인 도구 조합법 책 해금, 설명, 각인창 Shift+클릭/툴팁.
- 각인 도구 및 5등급 룬 아이콘 교체. 생성 원본은 art/generated, 게임용 투명 64×64 텍스처 포함.
- 서브 직업은 구현하지 않았으며 PROFESSIONS-IDEAS.md에 평가와 추가 제안을 담았습니다.

기존 프로젝트에 적용하는 방법과 테스트 순서는 ZIP 안 TESTING-1.3.md를 참고하세요. 기존 프로젝트를 백업하고 run-client 폴더를 유지하면 월드와 추가 모드가 남습니다.

빌드, 자동 GameTest 38개, Eclipse 실행 설정/클라이언트 준비 통과. 실제 Windows Eclipse 화면과 전투감·외부 모드팩 호환은 PC에서 확인해야 합니다.

---

## 이전 버전

# StarRPG 1.2.0 Eclipse 다운로드

[StarRPG 1.2.0 Eclipse 프로젝트 ZIP 다운로드](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v1.2.0/downloads/StarRPG-1.2.0-Eclipse.zip)

Minecraft 1.21.1 / NeoForge 21.1.235 / JDK 21.

- 월드 공통 누적 생존 시간 60분마다 난이도 1단계 상승, 최대 5단계. 빈 서버·크리에이티브만 접속한 경우 정지.
- 좀비의 단계별 방어구·인챈트 무기·낚싯대 공격. 갈고리는 1초 예고 후 발사하며 벽/회피/쿨타임/연속 당김 보호 적용.
- 강화 투구 야간투시의 만료 깜빡임 수정.

ZIP 안 `TESTING-1.2.md`에 기존 Eclipse 프로젝트 적용 방법과 테스트 명령어가 있습니다. 새 프로젝트로 가져오는 방법은 `ECLIPSE.md`를 참고하세요. 기존 프로젝트와 월드는 백업하고 적용하세요. 실행은 기존처럼 **StarRPG Client → 싱글플레이**입니다.

테스트 월드에서 `/starrpg worldtier 3` 또는 `/starrpg worldtier 5`로 바로 비교하고 `/starrpg difficulty`로 상태를 확인할 수 있습니다. 단계 명령은 월드 진행 시계도 변경합니다.

빌드, 자동 GameTest 28개, Eclipse 실행 설정 생성/클라이언트 준비 통과. Windows Eclipse의 실제 화면, 낚싯줄 렌더링 및 외부 모드팩 전투감은 사용자 PC에서 확인해야 합니다.

---

## 이전 버전

# StarRPG 1.1.0 다운로드

## Eclipse에서 실행하기

[Eclipse용 프로젝트 ZIP 다운로드](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v1.1.0/downloads/StarRPG-1.1.0-Eclipse.zip)

수정된 소스와 Gradle wrapper, Eclipse 실행 안내를 포함합니다. ZIP을 새 폴더에 풀고 Eclipse에서 `File > Import > Gradle > Existing Gradle Project`로 `StarRPG_Mod` 폴더를 가져오세요. Gradle JVM은 JDK 21을 사용합니다. 동기화가 끝나면 `Run > Run Configurations > Java Application > StarRPG Client`를 실행하고 게임에서 싱글플레이를 선택하세요. 별도 서버 실행은 필요하지 않습니다.

자세한 순서와 문제 해결은 ZIP 안의 `ECLIPSE.md`를 참고하세요. 최초 실행에는 의존성을 받을 인터넷 연결이 필요합니다. 게임 데이터는 `run-client/`에 저장됩니다. 추가 모드 JAR과 기존 월드는 포함하지 않았습니다.

빌드, 클라이언트 실행 준비, Eclipse 실행 설정 생성 확인 완료. Windows Eclipse에서 게임 창을 직접 여는 검증은 수행하지 않았습니다.

## 기존 mods 폴더에 설치하기

[설치용 ZIP 다운로드](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v1.1.0/downloads/StarRPG-1.1.0.zip)

Minecraft 1.21.1 / NeoForge 21.1.235 / Java 21용입니다.

ZIP을 풀고 클라이언트와 서버의 mods 폴더에서 기존 StarRPG JAR을 새 JAR로 교체하세요. 두 버전을 동시에 설치하지 마세요. 월드는 먼저 백업하세요.

기존 이름 기반 강화 장비는 관리자가 확인한 뒤 `/starrpg setlevel 숫자`로 이전해야 합니다. 상세 변경 사항은 ZIP 안의 BALANCE.md에 있습니다.

빌드 및 게임 테스트 19개 통과. 전체 외부 모드팩과 온라인 로그인은 별도 검증이 필요합니다.

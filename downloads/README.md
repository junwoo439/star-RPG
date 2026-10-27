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

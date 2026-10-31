# StarRPG 2.4.0 Eclipse 다운로드

[**2.4.0 Eclipse 프로젝트 ZIP 다운로드**](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v2.4.0/downloads/StarRPG-2.4.0-Eclipse.zip)

[실제 게임: 용 근접 모습](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v2.4.0/downloads/StarRPG-2.4.0-Dragon-Closeup.png) · [용과 히드라](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v2.4.0/downloads/StarRPG-2.4.0-Dragons.png) · [휴머노이드와 리치](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v2.4.0/downloads/StarRPG-2.4.0-Humanoids.png) · [공격 범위 예고](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v2.4.0/downloads/StarRPG-2.4.0-Telegraphs.png)

- **몬스터 53종 / 보스 19종:** 야수, 아인종, 언데드, 드래곤/파충류, 악마/천상계, 정령/거인, 골렘 계열. 종족별 크기·색상·관절 모델과 공격 유형을 추가했습니다. 용의 턱·이빨·뿔·날개막·분절 꼬리, 몬스터별 비늘·털·갑옷·뼈·돌 재질을 새로 제작했습니다.
- **자연 출현 + 소환:** 지정 바이옴과 월드 단계에 따라 출현합니다. 보스 소환 계약서는 웅크리기+우클릭으로 대상을 바꾸고 바닥 우클릭으로 사용합니다. 가까운 보스 중복 출현을 제한합니다. 금속룡과 천상계는 중립입니다.
- **읽고 대응하는 전투:** 약공격은 약하게, 강공격은 긴 준비 동작과 바닥 예고 후 높은 피해/짧은 스턴. 금색은 패링 가능, 빨간색은 회피 대상입니다. 방향 고정·벽 차단·공격 후 빈틈·연속 스턴 방지를 적용했습니다.
- **V 패링:** 근접 무기/방패로 정면 타격을 맞춰 방어하면 적이 경직됩니다. 2초 안에 충전 공격으로 반격하면 1회 +25% 피해. 성공 창 0.25초, 재사용 1.2초입니다.
- **기존 성장/보상 연동:** 월드 N−2~N 단계, 무한 성장, 보스 골드/별 가루/룬 보상. 기존 무기·직업·강화·룬·상점 기능도 포함합니다.

**실행:** 새 폴더에 압축 해제 → 내부 `StarRPG_Mod/setup-eclipse.bat` 또는 `setup-adventure-eclipse.bat` → Eclipse Existing Gradle Project → Gradle Refresh/F5 → **StarRPG Client** → 싱글플레이. JDK 21이 필요하며 별도 서버 실행은 필요 없습니다.

**검증:** Twilight Forest·Mowzie·GeckoLib과 함께 GameTest **191개 통과**. 실제 클라이언트에서 53종 렌더러 로드 및 대표 모델·공격 예고를 확인했습니다. Windows Eclipse GUI와 다인 전투의 체감/성능은 사용 환경에서 확인해 주세요.

이번 몬스터는 직접 만든 23종 관절형 모델과 새로 그린 16종 재질 아틀라스를 사용합니다. 용과 날개 달린 종족의 AI는 지상 전투용입니다. 비행 보스전·전용 던전·다단계 페이즈와 외부 모드의 모든 공격에 대한 패링은 포함하지 않습니다. Ice and Fire를 설치한 업데이트는 아닙니다.

전체 수정 소스·Gradle/Eclipse 설정·게임 리소스를 포함합니다. 월드·캐시·개발자 스크린샷은 ZIP에서 제외합니다. 기존 월드를 보관하고 `TESTING-2.4.md` 순서로 확인하세요. `BALANCE-2.4.md`와 `BESTIARY-2.4.csv`에 수치·지역·보스 소환 조합법이 있습니다. 함께 플레이할 때는 양쪽 모두 2.4.0을 사용하세요.

<!-- END 2.4.0 -->
# StarRPG 2.3.0 Eclipse 다운로드

[**2.3.0 Eclipse 프로젝트 ZIP 다운로드**](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v2.3.0/downloads/StarRPG-2.3.0-Eclipse.zip)

[실제 게임: 얼음 궁극기](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v2.3.0/downloads/StarRPG-2.3.0-Ice-Ultimate.png) · [양손 건틀릿](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v2.3.0/downloads/StarRPG-2.3.0-Gauntlets.png) · [장창 자세](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v2.3.0/downloads/StarRPG-2.3.0-Spear.png) · [단검 궤적](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v2.3.0/downloads/StarRPG-2.3.0-Dagger-Trail.png)

[지팡이 6종 렌더러 미리보기](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v2.3.0/downloads/StarRPG-2.3.0-Staffs.png)

- **커스텀 이펙트 표시 오류 수정:** 카메라 월드 좌표를 거리로 오인하던 계산을 수정했습니다. 높은 고도/먼 좌표에서도 가까운 마법진과 무기 궤적이 보입니다.
- **무기별 3D 궤적:** 가늘어지는 참격, 관통 찌르기, 주먹 충격 고리, 망치 파동, 낫의 회전 베기, 투사체 꼬리를 추가했습니다. 원소 궁극기는 준비 고리와 대형 형상, 광주/나선/방사형 충격을 함께 표시합니다.
- **양손 전투:** 건틀릿 아이템 1개로 양손 착용과 좌우 교대 타격을 표시합니다. R은 실제 시간차 3연타입니다. 장창은 양손 잡기와 찌르기를 표시합니다. 보조 손에 다른 물건이 있으면 한손 표시로 돌아갑니다.
- **13개 직업:** 일반 마법사→화염술사, 사제→광휘술사, 수호자→전사. 기존 기록은 높은 값을 보존하며 자동 이전에는 비용이나 강화 초기화가 없습니다. 빛의 홀은 기존 룬을 보존하는 호환 무기로 남습니다.
- **원소별 지팡이 6종:** 새 원화, 별도 아이템/조합법, 해당 원소 직업 제한, 지팡이 룬과 무한 강화 지원.
- **전직의 실제 기능:** 관통·도탄·파쇄·추가타·회복·원소 연계. G는 기존 능력에 6초/최대 3회 강화 타격을 추가합니다. 전직 5/10/15회에서 발전합니다.
- **직접 직업 변경 시 +0:** 500 G 결제가 성공하면 소지한 이전 직업 무기만 초기화합니다. 다른 원소 무기·룬·내구도·같은 직업 전직은 유지합니다. +25 사냥 성능, 기본 마크 무기 외형, 기존 강화/룬/경제 시스템도 유지합니다.

**실행:** 새 폴더에 압축 해제 → `StarRPG_Mod/setup-adventure-eclipse.bat` 또는 `setup-eclipse.bat` → Eclipse Existing Gradle Project → Gradle Refresh/F5 → **StarRPG Client** → 싱글플레이. JDK 21이 필요합니다. 별도 서버를 실행할 필요가 없습니다.

**검증:** Twilight Forest·Mowzie·GeckoLib과 함께 GameTest **174개 통과**. 실제 클라이언트의 별도 테스트 월드에서 1/3인칭, 좌우 주손, 보조 손 횃불, 고도 Y=181의 커스텀 이펙트를 확인했습니다. Windows Eclipse GUI와 다인 PvP의 체감/성능은 별도 확인이 필요합니다.

전체 소스·Gradle/Eclipse 설정·게임 텍스처를 포함하며 월드, 캐시, 원화 사본, 개발자 스크린샷은 ZIP에서 제외합니다. 기존 월드는 보관하세요. `BALANCE-2.3.md`, `TESTING-2.3.md`에 수치·조합법·이전 규칙·테스트 순서가 있습니다. 함께 플레이할 때는 양쪽 모두 2.3.0을 사용하세요.

<!-- END 2.3.0 -->
# StarRPG 2.2.0 Eclipse 다운로드

[**2.2.0 Eclipse 프로젝트 ZIP 다운로드**](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v2.2.0/downloads/StarRPG-2.2.0-Eclipse.zip)

[새 이펙트 렌더러 미리보기](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v2.2.0/downloads/StarRPG-2.2.0-Effects.png) · [무기 잡는 위치 미리보기](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v2.2.0/downloads/StarRPG-2.2.0-Grips.png)

- **무기 자세 개선:** 9개 직업 무기에 개별 손잡이 위치·크기·각도, 1/3인칭 양손 표시를 적용하고 옆면 두께를 추가했습니다. 건틀릿은 손에 한 개를 표시합니다. Minecraft 기본 무기 외형은 유지합니다.
- **새로 그린 효과 16종:** 마법진·번개·얼음 결정·회오리·광주·화염·물보라·암석·영혼 날개·방패·타격·치유 등의 투명 그림을 회전/확대/소멸시키며 모든 마법 계열과 다른 직업의 능력에 연결했습니다.
- **직업 변경 초기화:** 변경 확정과 500 G 결제 성공 시 인벤토리·보조 손의 이전 직업 무기 전부 +0. 메뉴 커서와 판매 칸의 소지 무기도 포함합니다. 룬·이름·내구도와 다른 직업 장비는 유지합니다. 최초 선택·미리보기·같은 직업의 전직·거절된 변경에는 적용하지 않습니다. 상세 화면과 확정 버튼에 초기화 안내를 표시합니다.
- +25 사냥 성능, 16개 직업, 무한 강화·전직·몬스터 난이도, 기존 룬은 2.1 기준을 유지합니다.

**실행:** 새 폴더에 압축 해제 → StarRPG_Mod의 `setup-adventure-eclipse.bat` → Eclipse Existing Gradle Project → Gradle Refresh/F5 → **StarRPG Client**. JDK 21이 필요합니다. 추가 모드 없이 실행하려면 `setup-eclipse.bat`을 사용하세요. 기존 월드는 보관하세요.

**검증:** Twilight Forest·Mowzie·GeckoLib과 함께 GameTest **163개 통과**. 실제 클라이언트에서 아이템 표시 변환과 새 이펙트 렌더러 미리보기를 확인했습니다. 화면의 십자는 손 기준 위치를 나타내는 검증 표식이며 게임에는 표시하지 않습니다. Windows Eclipse GUI·실제 손/시야에서의 체감·다인 전투 성능은 별도 플레이 확인이 필요합니다.

전체 소스·Gradle 설정·게임 텍스처를 포함합니다. 실행에 불필요한 `art/` 원화 사본과 과거 검증 스크린샷은 ZIP에서 제외했습니다. `BALANCE-2.2.md`, `TESTING-2.2.md`에 수치와 확인 순서가 있습니다. 함께 플레이하는 클라이언트와 서버는 같은 2.2.0을 사용하세요.

---

# StarRPG 2.1.0 Eclipse 다운로드

[**2.1.0 Eclipse 프로젝트 ZIP 다운로드**](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v2.1.0/downloads/StarRPG-2.1.0-Eclipse.zip)

[실제 클라이언트 미리보기: 기본 외형 복원·직업 무기·속성 마법 문양](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v2.1.0/downloads/StarRPG-2.1.0-Art.png)

- **강화 피해 상향:** +25 직업 무기는 기본 설정의 난이도 5 좀비·스켈레톤·거미·크리퍼를 충전 공격/완충 화살/마법 공격 한 번으로 처치하도록 검증했습니다. 고급 장비·보스·더 높은 난이도는 별도입니다.
- **직업 총 16개:** 기존 마법사 유지 + 화염술사·해류술사·빙결술사·대지술사·암흑술사·광휘술사. 기존 별의 지팡이를 쓰며 직업별 주문·효과·전직 재료가 다릅니다.
- **룬 없이 직업 무기 고유 효과:** 단검·장창·대검·사수 화살 출혈, 낫·대검·홀·어둠/빛 마법의 흡혈/회복, 망치·방패검 약화, 건틀릿 둔화 등. 실제 피해 기반 회복·재사용 제한을 적용했습니다.
- **기본 Minecraft 무기 외형 복원:** 검·도끼·활·석궁·삼지창. 자체 직업 무기 그림은 유지합니다.
- 모든 마법의 회전 문양·속성별 발사/충돌/보조 연출과 다른 직업의 무기 연출을 강화했습니다.
- 기존 +5/10/15/20/25 무기 해금·Shift+R, 무한 강화·전직·몬스터 난이도를 유지합니다.

**실행:** 반드시 새 폴더에 압축 해제 → StarRPG_Mod의 `setup-adventure-eclipse.bat` → Eclipse Existing Gradle Project → Gradle Refresh/F5 → **StarRPG Client**. JDK 21이 필요합니다. 추가 모드 없이 실행하려면 `setup-eclipse.bat`을 사용하세요. 2.0 폴더에 덮어쓰면 삭제된 기본 무기 외형 파일이 남을 수 있습니다. 기존 월드는 보관하세요.

**빠른 확인:** Shift+H → 직업 탭의 ◀/▶로 두 페이지 탐색 → 이름 클릭은 미리보기, 확정 버튼으로 선택. 새 마법사는 둘째 페이지에 있습니다. 무기를 들고 `/starrpg setlevel 25` 후 충전 공격/우클릭 마법/R/Shift+R을 비교하세요.

**검증:** Twilight Forest·Mowzie·GeckoLib과 함께 자동 GameTest **156개 통과**. 실제 클라이언트에서 기본 무기 복원과 9개 직업 무기 모델·7개 마법 계열 회전 문양을 확인했습니다. 화면은 렌더러 미리보기이며 Windows Eclipse GUI·실제 다인 전투 체감은 별도 확인이 필요합니다. 상세 수치와 테스트 순서는 `BALANCE-2.1.md`, `TESTING-2.1.md`에 있습니다. 함께 플레이하는 클라이언트와 서버는 같은 2.1.0을 사용하세요.

---

# StarRPG 2.0.0 Eclipse 다운로드

[**2.0.0 Eclipse 프로젝트 ZIP 다운로드**](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v2.0.0/downloads/StarRPG-2.0.0-Eclipse.zip)

[실제 Minecraft 렌더러에서 확인한 무기 그림·마법진](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v2.0.0/downloads/StarRPG-2.0.0-Art.png)

- **무기 14계열의 새 그림**을 게임에 적용했습니다. 무기마다 색과 실루엣이 다르며 별도 리소스팩이 필요 없습니다.
- 기존 R·마법·투척에 회전 마법진과 베기 문양, 새 각성기에 삼중 마법진·광선·충격파 연출을 추가했습니다.
- **무기 강화 +5·10·15·20·25**를 기준으로 패시브/각성 능력을 해금합니다. 직업 전직 횟수와 별개입니다.
- **+15: Shift+R 각성기**, +20·25: 무기별 능력 발전. 쿨타임은 무기·직업을 바꿔도 공유합니다.
- 입문 검·도끼는 +10 유지 및 +5·10 패시브. 전문 무기의 강화 자체는 무한이며, 이번 능력 해금은 +25까지입니다.
- 기존 직업 10개·룬 400개·경제·무한 월드 난이도를 유지합니다.

**실행:** 새 폴더에 압축 해제 → StarRPG_Mod의 `setup-adventure-eclipse.bat` → Eclipse Existing Gradle Project로 가져오기 → Gradle Refresh/F5 → **StarRPG Client**. JDK 21이 필요합니다. 추가 모드 없이 실행하려면 `setup-eclipse.bat`을 사용하세요. 기존 프로젝트와 월드는 보관하세요.

**빠른 테스트:** 직업 확정 → 해당 무기 장착 → `/starrpg setlevel 15` → **Shift+R**. +20·25도 같은 방식으로 확인하세요. 활은 화살, 지팡이는 마나가 필요합니다. 모든 해금 내용은 아이템 설명과 `WEAPON-UNLOCKS-2.0.csv`에서 확인할 수 있습니다.

**검증:** Twilight Forest·Mowzie·GeckoLib과 함께 GameTest **145개 통과**, 빌드 및 Eclipse 실행 설정 생성 성공. 실제 Minecraft 클라이언트 미리보기에서 무기 14계열과 회전 문양 표시를 확인했습니다. Windows Eclipse GUI와 다인 전투 체감은 별도 플레이 확인이 필요합니다.

수치·조합·이전 버전 호환은 `BALANCE-2.0.md`, 확인 순서는 `TESTING-2.0.md`에 있습니다. 함께 플레이하는 클라이언트와 서버는 같은 2.0.0을 사용하세요.

---

# StarRPG 1.9.0 Eclipse 다운로드

[**1.9.0 Eclipse 프로젝트 ZIP 다운로드**](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v1.9.0/downloads/StarRPG-1.9.0-Eclipse.zip)

[실제 게임에서 확인한 신규 무기 화면](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v1.9.0/downloads/StarRPG-1.9.0-Weapons.png)

- **직업 10개:** 전사·척후병·사수·마법사·대장장이·광전사·사제·사신·격투가·수호자. 신규 무기 6종 및 조합법. 망치 전용 능력은 대장장이로 이동.
- **직업 메뉴:** 이름 클릭은 설명 미리보기. 별도의 확정 버튼으로 선택합니다.
- **5·10·15회 전직**에 추가 효과 해금, 이후 매 5회 능력치 성장. 1차가 최초 선택이므로 6·11·16차에 해금됩니다.
- **전문 무기 무한 강화:** 확률 감소·실패 보정, 단계 하락과 강화 파괴 없음. 일반 검·도끼와 방어구는 +10 유지.
- **월드 난이도 상한 해제**, N−2~N 몬스터 혼합 유지. 22개 특성 계열, 로드된 몬스터 100종 분류. 추가 능력은 예고·쿨타임·연속 제어 방지 적용.
- 마법 보스바/메뉴에 실제 쿨타임, **23품목 생존 상점** 추가.

**실행:** ZIP을 새 폴더에 풀고 StarRPG_Mod의 `setup-adventure-eclipse.bat` → Eclipse Existing Gradle Project로 가져오기 → Gradle Refresh/F5 → **StarRPG Client**. JDK 21 필요. 추가 모드 없이 실행하려면 `setup-eclipse.bat`을 사용하세요. 기존 프로젝트·월드는 보관하세요.

`BALANCE-1.9.md`에 직업별 능력·조합법·수치, `TESTING-1.9.md`에 테스트 순서가 있습니다. 기존 400개 룬과 기본 인챈트 제거 정책은 유지합니다. 전투 중 일반 내구도 소모는 유지합니다.

**검증:** 외부 Twilight Forest·Mowzie·GeckoLib과 함께 GameTest 133개 통과, 빌드/Eclipse 실행 설정 생성 성공. 실제 Linux Minecraft 클라이언트에서 신규 무기 6종과 지팡이 모델을 확인했습니다. Windows Eclipse GUI와 실제 다인 PvP 체감은 별도 확인이 필요합니다.

---

# StarRPG 1.8.0 Eclipse 다운로드

[StarRPG 1.8.0 Eclipse 프로젝트 ZIP 다운로드](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v1.8.0/downloads/StarRPG-1.8.0-Eclipse.zip)

[실제 Minecraft 클라이언트에서 확인한 지팡이 화면](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v1.8.0/downloads/StarRPG-1.8.0-Staff.png)

- 지팡이 투명 현상 수정. 금·자수정·석영 3D 모델을 실제 클라이언트에서 확인했습니다. 별도 리소스팩은 필요 없습니다.
- 마법 탄환·궤적·폭발·유성 예고 연출 확대, 마나 바의 ‘지팡이를 드세요’ 안내 제거.
- 10개 장비 유형 × 5등급 × 각 8종 = **400개 룬 효과**. 지팡이 룬 추가.
- 일반 룬 결과 **일반 70% / 희귀 25% / 에픽 4.9% / 레전더리 0.1%**. 다른 등급도 교차 추첨하며 재각인 시 등급 하락이 가능합니다.
- 활 4속성을 룬 효과에 통합하고 Shift+H의 별도 부여 메뉴 제거. 기존 별도 활 속성은 다음 재각인까지 유지합니다.
- **인챈트 테이블 우클릭으로 장비 강화**. 별가루·별조각 재료와 기존 강화 단계/실패 보정 유지.
- 주민의 기본 인챈트 책 거래를 별가루 거래로 전환하고 장비 거래에서 기본 인챈트 제거.
- 전직 화면에 직업 카드·아이콘·진행 막대·재료 조건 추가. 단검 근접 사거리 2.3칸.
- 기본 구매 가격 별가루 **40 G**, 별조각 **400 G**, 일반 룬 120 G.

**실행:** 기존 프로젝트/월드 백업 → 압축 안 StarRPG_Mod에서 setup-adventure-eclipse.bat → Eclipse의 Existing Gradle Project로 가져오기 → Gradle Refresh/F5 → StarRPG Client. JDK 21이 필요하며, 추가 모드 없이 실행할 때는 setup-eclipse.bat을 사용합니다.

전체 확률·수치는 BALANCE-1.8.md, 400개 효과 목록은 RUNE-EFFECTS-1.8.csv, 테스트 순서는 TESTING-1.8.md를 확인하세요. 기존 무한 전직·귀환 단검·마법·골드 경제 기능을 포함합니다.

**자동 테스트 120개 통과**, 빌드·Eclipse 준비 성공. 실제 Linux 클라이언트에서 지팡이 모델 36개 면과 화면 표시를 확인했습니다. Windows Eclipse·실제 다인 PvP·모든 화면 해상도는 별도 플레이 확인이 필요합니다.

외부 모드는 검증된 Twilight Forest 4.8.3802 / Mowzie 1.8.2 / GeckoLib 4.9.2 설치 도구로 다운로드합니다. Ice and Fire는 호환 공식 빌드가 없어 제외했습니다. 생활직은 보류했습니다.

---

## 이전 버전

# StarRPG 1.7.0 Eclipse 다운로드

[StarRPG 1.7.0 Eclipse 프로젝트 ZIP 다운로드](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v1.7.0/downloads/StarRPG-1.7.0-Eclipse.zip)

- 전사=검·망치, 척후병=단검, 사수=활·석궁, 마법사=새 별의 지팡이. 다른 직업 무기는 일반 공격만 허용하고 전용 능력·보너스를 제한합니다.
- 직업마다 다른 전투 실적과 재료를 요구하며, 3차 이후도 계속 전직합니다. XP·실적·재료·골드를 소모하고 능력치 증가량은 완만해집니다. 기존 직업·차수·XP는 유지됩니다.
- 단검이 회전하며 날아간 뒤 자동 귀환합니다. 강화·룬·내구도를 유지한 실제 아이템을 돌려주며, 인벤토리가 가득 차면 발밑에 떨어집니다.
- 지팡이 3D 모델, 마나 보스바, 마나탄·화염구·회복·유성 낙하, 강화된 직업 G 능력.
- 검기·망치 충격음·대형 화살 나선 궤적·석궁 발사 연출. 기존 상점·판매·골드·활 전용 4속성·몬스터 규칙 유지.

**실행:** 기존 프로젝트/월드 백업 → 압축 안 StarRPG_Mod에서 setup-adventure-eclipse.bat 실행 → Eclipse의 Existing Gradle Project로 가져오기 → Gradle Refresh/F5 → StarRPG Client 실행. JDK 21이 필요합니다. 추가 모드 없이 실행하려면 setup-eclipse.bat을 사용합니다.

**조작:** Shift+H 메뉴, R 무기 스킬, G 직업 능력. 단검 우클릭은 투척. 지팡이 우클릭은 선택 주문, Shift+우클릭은 주문 변경입니다.

상세 수치·조합법은 BALANCE-1.7.md, 테스트 순서는 TESTING-1.7.md, 전체 2,061종 판매 기준가는 SELL-PRICES-1.7.csv에 있습니다.

외부 모드 3종을 함께 로드한 **자동 테스트 105개 통과**, 빌드·Eclipse 실행 구성 생성 성공. Windows 화면·다인 PvP는 직접 확인하지 못했습니다. 기본 인챈트 제거는 기존처럼 켜져 있으므로 원본 월드를 보관하세요.

Twilight Forest 4.8.3802 / Mowzie 1.8.2 / GeckoLib 4.9.2 설치 도구 포함. 외부 JAR은 공식 배포처에서 다운로드합니다. Ice and Fire는 호환 공식 빌드가 없어 제외했습니다. 생활직은 보류했습니다.

---

## 이전 버전

# StarRPG 1.6.0 Eclipse 다운로드

[StarRPG 1.6.0 Eclipse 프로젝트 ZIP 다운로드](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v1.6.0/downloads/StarRPG-1.6.0-Eclipse.zip)

- **Shift+H:** 강화 재료 상점, 아이템 판매, 직업·전직, 활 속성 메뉴.
- **R:** 단검 삼연격 / 망치 충격파 / 대형 화살 / 석궁 5초 고정 사격. 단검 우클릭은 실제 투척·회수.
- **G:** 전사·척후병·사수·마법사 능력. 2차·3차 전직과 직업별 성장 저장.
- 얼음·전기·어둠·빛 신규 속성은 활에만 적용. 골드는 보스바 표시.
- 바닐라 1,332종을 포함한 현재 아이템 2,060종의 판매 기준가와 내구도 감액. 전체 CSV 가격표 포함.
- 기본 인챈트 차단·기존 장비 인챈트 제거. StarRPG 강화·룬 유지. **기존 월드는 먼저 백업하세요.**

ZIP 안쪽 **StarRPG_Mod**에서 `setup-adventure-eclipse.bat` 실행 → Eclipse의 Existing Gradle Project로 가져오기 → Gradle Refresh/F5 → **StarRPG Client** 실행. JDK 21이 필요합니다. StarRPG만 사용할 때는 `setup-eclipse.bat`을 실행하세요.

Minecraft 1.21.1 / NeoForge 21.1.235. Twilight Forest 4.8.3802, Mowzie 1.8.2, GeckoLib 4.9.2의 기존 검증된 설치 도구를 포함합니다. JAR은 공식 배포처에서 다운로드합니다. Ice and Fire는 호환 공식 빌드가 없어 제외했습니다. 생활직·무한 전직은 보류했습니다.

**자동 테스트 89개 통과**, 빌드·Eclipse 실행 구성 생성 성공. Windows 화면과 실제 다인 PvP는 직접 검증하지 못했습니다. 상세 수치는 BALANCE-1.6.md, 테스트 순서는 TESTING-1.6.md, 전체 가격은 SELL-PRICES-1.6.csv에 있습니다.

---

## 이전 버전

# StarRPG 1.5.1 Eclipse 다운로드

[StarRPG 1.5.1 Eclipse 프로젝트 ZIP 다운로드](https://github.com/junwoo439/star-RPG/raw/refs/heads/downloads-v1.5.1/downloads/StarRPG-1.5.1-Eclipse.zip)

**외부 모드 설치 수정·검증 완료:** Twilight Forest 4.8.3802 + Mowzie's Mobs 1.8.2 + GeckoLib 4.9.2.
기존 1.5.0 설치 도구의 잘못된 Twilight Forest 주소를 공식 Maven 배포처로 수정했습니다. 세 모드 파일을 실제로 다운로드·검증·설치하고, 함께 로드한 환경에서 자동 테스트 **68개가 통과**했습니다. 보스 등록·태그·능력치·골드/재료 보상도 확인했습니다. Windows 화면·보스 AI 전체·장시간 탐험까지 검증한 것은 아닙니다.

1. 기존 프로젝트/월드를 백업하고 ZIP 안쪽 **StarRPG_Mod** 폴더를 엽니다.
2. **setup-adventure-eclipse.bat**을 실행합니다. Java 21과 인터넷이 필요합니다. 외부 모드 JAR 약 64 MB를 공식 배포처에서 내려받고 Eclipse 실행 준비를 합니다.
3. Eclipse에 안쪽 폴더를 Existing Gradle Project로 가져온 뒤 **StarRPG Client**를 실행합니다. 이미 가져온 프로젝트라면 Gradle Refresh와 F5를 실행합니다.
4. 게임에서 `/starrpg mods`로 로드 상태, `/starrpg shop`으로 재료 상점을 확인합니다.

Minecraft 1.21.1 / NeoForge 21.1.235 유지. 1.5.0의 몬스터 단계 분포·좀비 약화·골드 경제 기능을 포함합니다. JAR 파일 자체는 ZIP에 묶지 않고 검증한 URL·버전·SHA-512를 고정한 설치 도구를 제공합니다. 같은 모드의 이전 JAR은 백업하며 월드와 다른 모드는 보존합니다.

**Ice and Fire는 공식 배포 버전에 1.21.1이 없어 제외**했습니다. 설치/검증 범위는 MODS-1.5.1.md, 플레이 확인 순서는 TESTING-1.5.1.md를 참고하세요.

---

## 이전 버전

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

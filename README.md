# My Health Log 다운로드와 사용 안내

날짜별 건강·운동·복약·검사와 병원 일정을 기록하는 Android 앱입니다.

**현재 개정판: 3.21.2+66 · 2026-11-25**

## 설치 파일 받기

**[앱 설치 파일 받기](https://github.com/mydunalove-sena/my-health-log-releases/releases/download/v3.21.2-20261125/MyHealthLog-3.21.2%2B66-update.apk)**

- [이번 개정판 다운로드 페이지](https://github.com/mydunalove-sena/my-health-log-releases/releases/tag/v3.21.2-20261125)
- [항상 최신 배포 확인하기](https://github.com/mydunalove-sena/my-health-log-releases/releases/latest)
- [파일 확인값 받기](https://github.com/mydunalove-sena/my-health-log-releases/releases/download/v3.21.2-20261125/SHA256SUMS.txt)

GitHub 로그인 없이 받을 수 있습니다. `.apk`가 앱 설치 파일입니다. Releases의 `Source code (zip)`은 설치 파일이 아닙니다.

Android7.0 이상에서 사용할 수 있습니다. 아이폰용 설치 파일과 Google Play 설치본은 제공하지 않습니다.

## 매뉴얼

| 안내 | 웹에서 읽기 | PDF 받기 |
|---|---|---|
| 실제 설치 화면6장으로 따라 하기 | [설치 안내](INSTALL.md) | [큰 글씨 설치 안내](https://github.com/mydunalove-sena/my-health-log-releases/releases/download/v3.21.2-20261125/Installation-Guide-ko.pdf) |
| 건강·운동·복약·검사·일정·통계·백업 | [앱 사용 안내](USER_GUIDE.md) | [앱 사용 매뉴얼](https://github.com/mydunalove-sena/my-health-log-releases/releases/download/v3.21.2-20261125/User-Guide-ko.pdf) |

설치 사진의3.17.1 파일명은 과거 예시입니다. 이번 파일은 **MyHealthLog-3.21.2+66-update.apk**입니다. 사용 안내의 앱 화면은 합성 자료로 만든 예시이며 개인 기록이 아닙니다.

## 이번에 달라진 점

- 모델·양식에 따른 인식 차이 때문에 **체중 사진·인바디 캡처 OCR 버튼을 숨겼습니다.** 체중은 **건강 → 일상 기록**에서 직접 입력합니다.
- 기존 체중·다른 건강 기록과 통계는 유지됩니다. 처방·검사·병원 일정의 사진 입력은 계속 사용할 수 있습니다.
- 백업·조회 실패·삭제 안내와 큰 수의 검사 그래프 처리를 보완했습니다. 남은 극단값 조건과 미검증 범위는 [변경 내용과 알려진 제한](RELEASE_NOTES_2026-11-25.md)에 적었습니다.
- 두 갤럭시(SM-S918N·SM-F936N)에 같은 APK를 설치하고 기존 기록14영역과 설정 보존을 확인했습니다.

## 기존 앱을 쓰고 있다면

1. **홈 → 데이터 관리 → 백업 파일 저장**으로 새 백업을 보관하세요.
2. 기존 앱을 지우지 말고 이번 APK를 열어 업데이트하세요.
3. 설치 후 예전 기록과 설정이 보이는지 확인하세요.

앱 버전 숫자는 이전 배포와 같은3.21.2+66입니다. **2026-11-25 개정 배포**와 아래 확인값으로 구분하세요. 이전 배포는 이력으로 보존합니다.

APK SHA-256: `c4f123835f6e282dcc8160f8cc0b68fd969eaad2e3dc5af9035309a778cde649`

백업에는 개인 건강정보가 들어 있고 암호화되어 있지 않습니다. 본인만 보관하고 공개 게시글에 올리지 마세요. 설치 문제는 [도움 요청 안내](INSTALL.md#10-도움이-필요하면-앱을-지우기-전에-문의하세요)를 확인하세요.

이 공개 저장소에는 배포 안내·승인된 설치 예시·합성 앱 화면만 보관합니다. 앱 소스는 비공개로 관리합니다.

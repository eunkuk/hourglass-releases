# Hourglass 배포

Hourglass 데스크톱 앱(macOS·Windows)의 설치 파일과 자동 업데이트 매니페스트를 올리는 저장소입니다.
소스 코드는 포함하지 않습니다.

- 최신 설치 파일: [Releases](https://github.com/eunkuk/hourglass-releases/releases/latest)
  - macOS: `Hourglass_<버전>_universal.dmg`
  - Windows: `Hourglass_<버전>_x64-setup.exe`
- 설치된 앱은 **설정 → 연결 → 앱 업데이트**에서 새 버전을 확인하고 설치합니다.
- `latest.json`과 `.sig` 파일은 앱의 자동 업데이트가 읽는 매니페스트와 서명입니다.

앱은 Apple 서명·공증과 Windows 코드 서명을 하지 않으므로 첫 설치 때 OS 경고를 지나야 합니다.

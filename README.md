# RSP QR/바코드 스캐너

QR코드와 바코드를 스캔하여 결과를 복사·공유하고, CSV 파일로 기록을 누적하는 Android 앱입니다.

## 다운로드

[![APK 다운로드](https://img.shields.io/badge/APK-Download-blue?style=for-the-badge&logo=android)](https://github.com/seatoskymee/APK_QrBarScanner-Release/releases/latest/download/RSPQrBarScanner_latest.apk)

> 위 버튼을 클릭하면 최신 APK를 바로 다운로드할 수 있습니다.

## 주요 기능

- QR코드 및 각종 바코드 스캔 (Code128, EAN-13/8, UPC-A/E, ITF, Aztec, PDF417 등)
- 스캔 후 바코드 종류·속성 자동 분석 표시 (QR 내용 유형, EAN-13 국가 코드 등)
- 결과 복사(클립보드) → 카카오톡·메시지에 붙여넣기
- 결과 공유 → 카카오톡·이메일 등으로 바로 전송
- ZPL 생성 → 스캔한 바코드와 동일한 ZPL 코드 생성 및 화면 렌더링 (오프라인)
- 스캔 기록 자동 누적 (rsp_scan_YYYYMMDD.csv)
- 디버그 로그 기록 (debuglog/rsp_scan_YYYYMMDD.log)
- 우측 상단 ··· 메뉴: CSV 내보내기 / 디버그 로그 / 도움말 (버전 확인 포함)

## 사용 방법

1. APK를 다운로드하여 설치합니다.
2. **[스캔 시작]** 버튼을 탭합니다.
3. QR코드 또는 바코드를 카메라에 비춰주세요. 화면 터치로 초점 조정 가능.
4. 스캔된 값과 바코드 속성이 화면에 표시됩니다.
5. **[복사]** 또는 **[공유/전송]** 버튼으로 값을 활용하세요.
6. **[ZPL 생성하기]** 버튼으로 동일한 바코드를 ZPL 형식으로 생성하고 화면에 그릴 수 있습니다.

## 지원 환경

- Android 7.0 (API 24) 이상
- 카메라 권한 필요

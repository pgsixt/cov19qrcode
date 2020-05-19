qrcode2webhook
===============
## QR코드(또는 NFC) + 구글시트를 이용한 출입대장 만들기

*개요: 인쇄된 큐알코드 스캔 -> 본 프로젝트 페이지 (scan_qrcode.html) -> ifttt.com의 웹훅실행 -> 구글시트에 연락처 추가 -> 결과 출력 qr_result.html*

준비과정 대로 하시면 출입대장을 쉽게 하실 수 있습니다.

준비
____

1. ifttt에서 webhook만들기
웹훅(webhook)은 일종의 방아쇠라 할 수 있습니다. 총알이 나갈 방아쇠를 준비해야 합니다. 
ifttt.com 은 여러 서비스 등을 엮어서 자동화하는 사이트입니다. ifttt.com에서 회원가입을 하신 후, 
https://ifttt.com/applets/328574p-qr-code-scan-to-vote

connect 버튼을 누르면, 설정 부분으로 넘어가게 됩니다.


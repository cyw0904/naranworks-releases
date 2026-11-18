# 나란웍스(NaranWorks) — 설치 파일

외국인 직원이 있는 작은 회사를 위한 그룹웨어 "나란웍스"의 **설치 파일 배포 저장소**입니다(프로그램 소스는 여기에 없습니다).

## 받기

- 최신 버전: [Releases](https://github.com/cyw0904/naranworks-releases/releases/latest) 에서 `NaranWorks-Setup-x.y.z.exe`
- 설치 방법: 같은 Release 의 `NaranWorks_InstallManual_ko.pdf`(설치 매뉴얼)

## 설치(요약)

1. 늘 켜 두는 Windows 10/11(64비트) PC 에서 설치 파일을 실행합니다. Windows 'PC 보호' 창이 뜨면 **추가 정보 → 실행**.
2. 마침 → 브라우저의 **처음 설정**(회사 이름·관리자) → 로그인 → 관리자 2단계 인증 → **시작하기** 점검표를 따라 준비를 마칩니다.
3. 이미 설치한 회사는 새 설치 파일을 실행하면 데이터·설정은 그대로 새 버전으로 바뀝니다(관리 > 시스템 관리에 새 버전 알림).

## 파일 확인

Release 설명의 SHA-256 과 받은 파일이 같은지 확인하세요(PowerShell: `Get-FileHash .\NaranWorks-Setup-1.0.0.exe`).

사용 조건은 판매자와 맺은 사용권 계약을 따릅니다. 문의: 판매처(크몽 등)의 판매자 문의.

## 새 판 올리기(판매자)

`releases/vX.Y.Z/`(설치 파일·`update.json`·`NOTES.md`·매뉴얼 PDF)를 넣고 main 에 push 하면 워크플로가 가장 높은 판으로 Release 를 만든다(태그도). 같은 판을 다시 올리면 그 Release 를 지우고 새로 만든다.

# DALBIT LYRIC Generator

이미지·영상, 음원, SRT·LRC 자막을 조합해 YouTube 리릭 비디오와 Shorts를 만드는 Windows 프로그램입니다.

프로그램 파일은 저장소의 **Releases**에서 내려받을 수 있습니다. 이 저장소에는 배포 파일과 안내만 제공하며, 소스코드와 라이선스 발급 도구는 포함하지 않습니다.

## 다운로드

| 버전 | 용도 | 다운로드 |
| --- | --- | --- |
| FREE | 한 장의 이미지와 SRT 자막으로 1080p 리릭 비디오 제작 | [최신 FREE 다운로드](https://github.com/dalbit-it/DALBIT-LYRIC-Generator-Releases/releases/latest/download/DALBIT-LYRIC-Generator-FREE.zip) |
| PRO | 여러 미디어, SRT·LRC, 커스텀 편집, 플레이리스트, 최대 4K 출력 | [최신 PRO 다운로드](https://github.com/dalbit-it/DALBIT-LYRIC-Generator-Releases/releases/latest/download/DALBIT-LYRIC-Generator-PRO.zip) |

PRO는 별도로 발급받은 PC용 라이선스 파일이 있어야 실행할 수 있습니다.

## 설치 및 실행

1. 원하는 버전의 ZIP을 내려받습니다.
2. ZIP 안에서 바로 실행하지 말고 원하는 폴더에 전체 압축을 해제합니다.
3. `DALBIT LYRIC Generator FREE.exe` 또는 `DALBIT LYRIC Generator PRO.exe`를 실행합니다.
4. PRO는 첫 실행 화면의 라이선스 요청 코드를 판매자에게 전달하고, 발급받은 라이선스 파일을 등록합니다.

EXE, `runtime`, `_internal`, `licenses` 폴더를 분리하거나 수정·삭제하지 마세요. PRO의 `package-integrity.json`도 같은 위치에 있어야 합니다.

## 지원 환경

- Windows 10/11 64-bit
- 가로 16:9 및 세로 9:16
- 30fps · H.264 · AAC
- FREE: Full HD 1080p
- PRO: 720p, 1080p, 2K QHD, 4K UHD

영상 생성은 주로 CPU를 사용합니다. 일반적인 작업은 16GB RAM과 1080p 출력을 권장하며, 2K·4K 작업은 32GB RAM과 충분한 SSD 여유 공간을 권장합니다.

## 파일 무결성 확인

각 ZIP과 함께 제공되는 `.sha256` 파일의 값을 비교하면 다운로드 파일이 변경되거나 손상되지 않았는지 확인할 수 있습니다.

PowerShell 예시:

```powershell
Get-FileHash -Algorithm SHA256 .\DALBIT-LYRIC-Generator-PRO.zip
```

## 문의

- 홈페이지: https://dalbit-it.vercel.app/lyric-generator
- 이메일: dalbit.it@gmail.com

## 이용 안내

프로그램과 배포 파일의 무단 복제·재배포·판매, 라이선스 및 기기 인증 우회는 허용되지 않습니다. 자세한 이용 조건과 제3자 라이선스는 각 ZIP 안의 `LICENSE.txt`와 `licenses` 폴더를 확인하세요.


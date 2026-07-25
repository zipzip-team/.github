# zipzip-team

`zipzip-team`은 여러 기기에 흩어진 사진을 더 쉽게 찾고, 분류하고, 함께 다시 볼 수 있도록 돕는 **ZIPZIP** 서비스를 만드는 팀입니다.

이 저장소는 조직 공통 설정을 관리합니다. GitHub 조직 페이지에 표시되는 소개와 구성원 정보는 [profile/README.md](profile/README.md)에 있습니다.

## ZIPZIP은 어떤 서비스인가요?

서브폰이나 카메라로 찍은 사진이 메인 사진 보관함에 섞이면, 원하는 사진을 다시 찾고 정리하기가 어렵습니다. ZIPZIP은 사진 메타데이터를 바탕으로 사진을 인덱싱하고, 날짜·장소·촬영 기기 기준의 탐색과 공유 앨범 경험을 제공합니다.

## 저장소 안내

| 저장소 | 역할 | 공개 여부 |
| --- | --- | --- |
| [zipzip-iOS](https://github.com/zipzip-team/zipzip-iOS) | 사진 탐색·정리 경험을 제공하는 iOS 앱 | 공개 |
| [zipzip-server](https://github.com/zipzip-team/zipzip-server) | 인증, 공유 그룹·앨범·사진 메타데이터, API를 제공하는 Spring 서버 | 공개 |
| [zipzip-server-config](https://github.com/zipzip-team/zipzip-server-config) | 서버 실행에 필요한 비공개 설정을 관리하는 서브모듈 | 비공개 |
| [zipzip-photobooth](https://github.com/zipzip-team/zipzip-photobooth) | macOS 기반 포토부스 도구 | 공개 |
| [zipzip-team.github.io](https://github.com/zipzip-team/zipzip-team.github.io) | 팀 또는 서비스 소개를 위한 정적 웹 사이트 | 공개 |

각 저장소의 설치 방법, 실행 환경, API·도메인 설계는 해당 저장소의 README와 `docs/`를 기준으로 확인합니다. 특히 서버를 실행할 때는 비공개 설정 저장소 접근 권한이 필요합니다.

## 문의

프로젝트 관련 문의와 접근 권한 요청은 팀 리드 또는 해당 도메인 담당자에게 전달해 주세요. 조직 구성원과 역할은 [조직 프로필](profile/README.md)에서 확인할 수 있습니다.

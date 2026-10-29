# iTshirt03 — 오픈소스SW응용 Git 실습

교재의 Git/GitHub 실습 파일, 커밋 이력, SourceTree GUI 조작 기록을 모은 저장소입니다.

## 학교에서 완성된 결과 받기

**[학교용 완성 ZIP 다운로드](https://github.com/ysw1104-Hub/iTshirt03/raw/refs/heads/school-download-20261029/school-download/SW-Git-Complete-20261029.zip)**

이 ZIP은 `iTshirt-cat`과 `iTshirt-oct`의 **`.git` 이력까지** 포함합니다. 압축을 전부 풀면 실습 파일, 두 저장소의 이력, 실행 기록, 실제 화면 캡처, 핵심 정리와 확인 스크립트를 함께 볼 수 있습니다.

GitHub의 일반 **Code → Download ZIP**에는 `.git` 이력이 없습니다. 이력이 포함된 두 실습 폴더를 받으려면 위의 별도 학교용 ZIP을 사용합니다.

한 저장소만 새로 받을 때는 다음 명령을 사용합니다.

```sh
git clone https://github.com/ysw1104-Hub/iTshirt03.git iTshirt-school
```

학교 PC의 Git·VS Code·SourceTree 설치, 본인 계정 로그인과 SourceTree의 **Add로 새 폴더 경로 등록**은 PC별 환경 설정입니다. 파일 작성과 실습 커밋을 다시 만드는 과정은 필요하지 않습니다.

## 교재 실습 파일

| 파일 | 내용 |
|---|---|
| [README.txt](README.txt) | 쇼핑몰 설명과 개발자 목록 |
| [tshirt-list.md](tshirt-list.md) | GitHub·파이썬 티셔츠 목록 |
| [feature-list.md](feature-list.md) | 티셔츠 판매·구매 기능 목록 |

고양이·문어는 한 사용자가 두 로컬 폴더로 역할을 나눠 연습한 교재 속 이름입니다.

## 커밋과 실제 GUI 조작

| 커밋 | 작업 |
|---|---|
| `c94f465` | 사이트 설명 추가 |
| `78cf9c8` | 설명 업데이트 |
| `d8d4e82` | 개발자 목록 추가, 다른 폴더에서 push·pull |
| `dddbd43` | 티셔츠·기능 목록 추가 |
| `3dba257` | VS Code에서 목록 형식 정리 후 **SourceTree 버튼으로 스테이징·커밋·Push** |

마지막 GUI 실습은 기능 목록을 먼저 스테이징하고 티셔츠 목록도 추가한 뒤 커밋했습니다. Push 후 `main`과 `origin/main`이 같은 커밋을 가리키는 것을 확인했습니다. 네 번째 커밋까지의 이력도 그대로 보존했습니다.

GitHub OAuth 본인 인증도 완료했고, SourceTree의 **Remote**에서 `ysw1104-Hub` 계정과 `iTshirt03` 저장소가 표시되는 것을 확인했습니다. 실제 인증 성공 및 원격 목록 화면은 캡처 12~13번에 보관했습니다.

- [실습 실행 기록](실습자료/실습기록.txt)
- [최종 확인 결과](실습자료/실습결과_확인.txt)
- [교재 사진 범위 대조표](실습자료/교재_범위대조표.txt)
- [Git 핵심 정리](실습자료/Git_핵심정리.txt)
- [실제 화면 캡처](실습자료/화면확인)

SourceTree의 개인 로그인 토큰과 PC별 프로그램 설정은 배포 파일에 포함하지 않습니다. Git 이력과 실습 증거는 학교용 ZIP과 이 저장소에 보관합니다.

# SpecialProject_2026

## 프로젝트 개요

**SpecialProject_2026**은 Unreal Engine을 기반으로 제작하는 프로젝트입니다.
프로젝트의 기획, 개발, 테스트 및 유지보수 과정을 체계적으로 관리하는 것을 목표로 합니다.

## 주요 정보

| 항목       | 내용                        |
| -------- | ------------------------- |
| 프로젝트명    | SpecialProject_2026       |
| 프로젝트 시작일 | 2026년 7월 5일               |
| 개발 엔진    | Unreal Engine 5.8.0       |
| 개발 상태    | 개발 진행 중                   |
| 개발자      | muffinhead03                  |
| 사용자      | 프로젝트 참여자 및 테스트 사용자        |
| 프로젝트 유형  | Unreal Engine 기반 프로젝트     |
| 저장소 용도   | 소스 코드, 설정 파일 및 프로젝트 문서 관리 |

## 개발 환경

* **Engine:** Unreal Engine 5.8.0
* **Version Control:** Git / GitHub
* **Primary Language:** C++ / Blueprint
* **Target Platform:** 추후 확정
* **Development Status:** In Development

## 프로젝트 목표

이 프로젝트의 주요 목표는 다음과 같습니다.

* Unreal Engine 5.8.0을 활용한 프로젝트 개발
* 안정적이고 확장 가능한 프로젝트 구조 구축
* Blueprint와 C++를 활용한 기능 구현
* Git 및 GitHub를 이용한 버전 관리
* 개발 문서와 변경 내역의 지속적인 관리
* 테스트 및 최적화를 통한 프로젝트 완성도 향상

## 프로젝트 구조

```text
SpecialProject_2026/
├── Config/          # 프로젝트 설정 파일
├── Content/         # 에셋, 맵, 블루프린트 등 콘텐츠
├── Source/          # C++ 소스 코드
├── Plugins/         # 프로젝트 플러그인
├── Scripts/         # 자동화 및 보조 스크립트
├── Docs/            # 프로젝트 문서
├── .gitignore       # Git 추적 제외 설정
└── README.md        # 프로젝트 소개 문서
```

## 사용자

본 프로젝트의 주요 사용자는 다음과 같습니다.

* 프로젝트 개발자
* 프로젝트 기획자
* 내부 테스트 사용자
* 협업 참여자
* 최종 사용자

사용자 권한과 역할은 프로젝트 진행 상황에 따라 추가로 정의될 수 있습니다.

## 개발자

### SG JEONG

* 프로젝트 기획 및 관리
* Unreal Engine 프로젝트 개발
* Blueprint 및 C++ 기능 구현
* GitHub 저장소 관리
* 프로젝트 테스트 및 최적화
* 프로젝트 문서 작성 및 유지보수

## 설치 및 실행

### 1. 저장소 복제

```bash
git clone <repository-url>
```

### 2. 프로젝트 폴더로 이동

```bash
cd SpecialProject_2026
```

### 3. 프로젝트 실행

`SpecialProject_2026.uproject` 파일을 Unreal Engine 5.8.0으로 실행합니다.

필요한 경우 `.uproject` 파일을 마우스 오른쪽 버튼으로 클릭한 후 Unreal Engine 버전을 5.8.0으로 지정합니다.

### 4. C++ 프로젝트 빌드

C++ 코드가 포함된 경우 프로젝트 파일을 생성한 후 Visual Studio 또는 사용 중인 개발 환경에서 빌드합니다.

```text
Generate Visual Studio project files
```

빌드가 완료되면 Unreal Editor에서 프로젝트를 실행합니다.

## Git 관리 주의사항

Unreal Engine 프로젝트에서 자동으로 생성되는 캐시, 빌드 결과물 및 임시 파일은 GitHub에 업로드하지 않습니다.

대표적인 제외 대상은 다음과 같습니다.

```gitignore
Binaries/
DerivedDataCache/
Intermediate/
Saved/
.vs/
*.sln
```

대용량 에셋을 저장소에서 관리해야 하는 경우 Git LFS 사용을 검토합니다.

## 버전 관리 규칙

커밋 메시지는 변경 내용을 이해하기 쉽도록 작성합니다.

```text
feat: 새로운 기능 추가
fix: 오류 수정
docs: 문서 수정
refactor: 코드 구조 개선
test: 테스트 코드 추가 및 수정
chore: 설정 및 기타 작업
```

예시:

```text
feat: 플레이어 이동 기능 추가
fix: 캐릭터 충돌 오류 수정
docs: README 프로젝트 정보 업데이트
```

## 개발 일정

| 날짜         | 내용         |
| ---------- | ---------- |
| 2026-07-05 | 프로젝트 시작    |
| 추후 업데이트    | 기본 프로젝트 설정 |
| 추후 업데이트    | 주요 기능 개발   |
| 추후 업데이트    | 테스트 및 최적화  |
| 추후 업데이트    | 프로젝트 배포    |

## 진행 상태

* [x] 프로젝트 생성
* [x] GitHub 저장소 생성
* [x] 기본 프로젝트 환경 설정
* [ ] 핵심 시스템 구현
* [ ] UI 및 사용자 기능 구현
* [ ] 테스트 및 버그 수정
* [ ] 성능 최적화
* [ ] 최종 빌드 및 배포

## 라이선스

현재 본 프로젝트의 라이선스는 별도로 지정되지 않았습니다.

프로젝트 소스 코드와 에셋의 사용, 복제, 수정 및 배포는 개발자의 사전 허가 없이 제한될 수 있습니다.

## 문의

프로젝트 관련 문의, 오류 제보 및 개선 요청은 GitHub Issues를 통해 등록합니다.

---

**SpecialProject_2026**
Started on **July 5, 2026**
Developed with **Unreal Engine 5.8.0**

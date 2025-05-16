## 📌 브랜치 안내

- `refactor/main`: 현재 보고 계신 포트폴리오용 브랜치입니다. 기존 팀 프로젝트를 기반으로 구조 개선, 보안 보완, 기능 추가 등을 진행하였습니다.
- `main`: 팀 프로젝트 기간동안 개발한 당시의 결과물이 저장된 브랜치입니다. 초기 버전을 참고하고 싶으신 분은 해당 브랜치를 참고해주세요.

---

## PR 요청 템플릿 (리뷰어 2명 선정)

```
## 📌 PR 요약
> 이번 PR에서 작업한 핵심 변경사항을 간단히 작성해주세요.

- 예시: 회원가입 기능 구현 (User 엔티티 + AuthController 추가)

---

## ⚒️ 작업 및 변경 내용 상세
> 어떤 작업을 했는지, 어떤 파일이 변경되었는지 구체적으로 작성해주세요.

- User.java, UserService.java, AuthController.java 파일 추가
- 회원가입 요청/응답 DTO 작성
- Spring Security 기본 설정 (SecurityConfig.java) 수정

---

## 🔥 리뷰 요청 포인트
> 리뷰어가 집중해서 봐야 할 부분이나, 확신이 없는 코드가 있으면 알려주세요.

- 비밀번호 암호화 로직 적절한지 확인 요청
- 에러 핸들링 방식 리뷰 요청

```

### 커밋 컨벤션

| 타입 | 의미 | 예시 |
|:----|:----|:----|
| feat | 새로운 기능 추가 | feat: 회원가입 API 구현 |
| fix | 버그 수정 | fix: 로그인 실패 시 에러 반환 수정 |
| docs | 문서 수정 (README, 주석 등) | docs: ERD 다이어그램 추가 |
| style | 코드 스타일 수정 (세미콜론, 들여쓰기 등) | style: 코딩 컨벤션 적용 |
| refactor | 리팩토링 (기능 변경 없이 구조 개선) | refactor: UserService 로직 정리 |
| test | 테스트 코드 추가/수정 | test: UserService 단위 테스트 추가 |
| chore | 기타 잡다한 작업 (빌드 설정 등) | chore: .gitignore 파일 업데이트 |
| perf | 성능 개선 | perf: 쿼리 최적화 처리 |


---

### 브랜치 구조(개별 브랜치 - 파트 브랜치 - dev - main)

![스크린샷 2025-04-29 102516](https://github.com/user-attachments/assets/a97102e9-30f8-415e-9d0e-36ef242fa0cc)
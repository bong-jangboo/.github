# Bong-Jangboo 2.0

> 이 프로젝트는 [2024-PKNU-capstone](https://github.com/2024-PKNU-capstone)의 원작을 기반으로 리팩토링 및 고도화된 버전입니다.  
> 기존의 봉장부 프로젝트를 계승하여 유지보수성과 확장성을 고려한 **구조 개선, 기능 확장, CI/CD 자동화** 등을 진행하고 있습니다.  
> **프론트엔드 영역은 UI/UX 재설계와 함께 완전히 새롭게 구축**되었습니다.

Bong-Jangboo는 학생 단체 회계 관리를 자동화하기 위한 시스템입니다.

은행 API, 영수증 OCR, 장부 결재 프로세스 등을 통합하여, 회계/총무 업무를 간소화하고 투명하게 관리할 수 있도록 지원합니다.
![image](https://github.com/user-attachments/assets/92549c1e-a82e-4810-9ea1-f6fa54ddc178)

---

## 🚀 프로젝트 특징

- OAuth 기반 오픈뱅킹 연동 (계좌 조회, 거래내역 확인)
- S3 기반 영수증 이미지 업로드
- OCR을 활용한 자동 영수증 처리
- 장부 등록 및 결재 승인 워크플로우
- 회장 → 부회장/총무/학생 권한 체계 및 위임 기능

---

## 🙏 Credits & 원작자

이 프로젝트는 2024년 캡스톤디자인 프로젝트인 [`bong-jangboo`](https://github.com/2024-PKNU-capstone)를 기반으로 리팩토링 및 고도화한 버전입니다.  
초기 설계 및 개발에 기여해주신 전 팀원 분들께 감사드립니다.

➡️ [원작 contributors 보기](https://github.com/2024-PKNU-capstone/backend/graphs/contributors)

---

## 👥 팀원 및 역할

| 💻 백엔드 | 🎨 프론트엔드 |
|:--:|:--:|
| **정채원** | **임성균** |
| Spring Boot, DB, CI/CD<br>[@chaewonjeong](https://github.com/chaewonjeong) | React, UI/UX<br>[@kimfrontend](https://github.com/kimfrontend) |

---

## 📚 위키

<p>
  <a href="https://github.com/bong-jangboo/backend/wiki">
  💻 <strong>백엔드 위키 바로가기</strong>
</a>&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://github.com/your-org/bong-jangboo/wiki/Frontend">
  🎨 <strong>프론트엔드 위키 바로가기</strong>
</a>
</p>

프로젝트에 대한 심화 문서와 협업 가이드입니다.

- [프로젝트 구조 및 모듈 설명](https://github.com/your-org/bong-jangboo/wiki/Project-Structure)
- [API 명세서 (Swagger)](https://your-deployment-url/swagger-ui/index.html)
- [ERD 및 데이터베이스 모델링](https://github.com/your-org/bong-jangboo/wiki/ERD)
- [CI/CD 파이프라인 구성](https://github.com/your-org/bong-jangboo/wiki/CI-CD-Guide)
- [브랜치 전략 및 커밋 컨벤션](https://github.com/your-org/bong-jangboo/wiki/Git-Workflow)
- [이슈 템플릿 및 PR 작성 가이드](https://github.com/your-org/bong-jangboo/wiki/Issue-PR-Guide)
- [초기 개발 환경 세팅 가이드](https://github.com/your-org/bong-jangboo/wiki/Dev-Setup)
- [프론트엔드 상태관리 구조 및 라우팅 전략](https://github.com/your-org/bong-jangboo/wiki/Frontend-State-Routing)
- [컴포넌트 설계 및 디자인 시스템](https://github.com/your-org/bong-jangboo/wiki/Frontend-Design)

---

> 각각의 백엔드 및 프론트엔드 코드는 다음 레포에서 관리되고 있습니다:
>
> - 🔗 [Backend Repository](https://github.com/bong-jangboo/backend)
> - 🔗 [Frontend Repository](https://github.com/bong-jangboo/frontend-demo)

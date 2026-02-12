# 🚀 최승훈 | Full-Stack Developer

> **"비즈니스 로직의 안정성과 웹 성능 최적화를 통해 사용자 가치를 증명하는 개발자입니다."**
> 
> [현대이지웰] Java 풀스택 개발자 아카데미 과정을 통해 이커머스 서비스의 전 과정을 경험했습니다. <br>특히 **JPA를 활용한 데이터 설계**와 **이미지 처리 최적화**를 통해 서비스의 완성도를 높인 경험이 있습니다.

### 🛠 Tech Stack
- **Backend:** `Java 21`, `Spring Boot 3`, `Spring Security`, `Spring Data JPA`
- **Frontend:** `React 19`, `JavaScript (ES6+)`, `Styled Components`, `JSP/JSTL`
- **Database:** `Oracle Database (19c)`
- **Infra & DevOps:** `Jenkins`, `Docker`, `Git/GitHub`

---

### 💻 Main Projects

#### 1. Coco Shopping Mall (Team Project)
**사용자 피부 타입 기반 뷰티 커머스 플랫폼**
- **담당 역할:** 상품 도메인 및 관리자 시스템 기능 구현
- **핵심 기여:**
    - **웹 성능 최적화:** `Thumbnailator` 라이브러리를 활용하여 상품 이미지 업로드 시 리사이징 및 WebP 변환 로직을 구현함으로써 **초기 로딩 속도 개선 및 서버 저장 효율성 증대**
    - **상품 관리 시스템:** 카테고리별 상품 필터링, 검색, 다중 이미지 CRUD 등 상품 운영에 필요한 핵심 백오피스 기능 구축
    - **서비스 안정성 대응:** 관리자 권한 미달 시 발생하는 예외 상황을 인지하고, 사용자 경험을 위해 **HTTP 403(Forbidden) 등 커스텀 에러 페이지 연동 및 예외 처리 가이드라인 적용**

#### 2. Shopping Mall Mini Project (Personal Project)
**Spring Data JPA 기반 사용자 맞춤형 이커머스 시스템**
- **주요 성과:**
    - **데이터 정합성 보장:** 주문 트랜잭션 내에서 실시간 재고 확인 및 부족 시 예외(`RuntimeException`) 처리를 통해 **재고 데이터의 신뢰도 확보**
    - **JPA 연관관계 설계:** Entity 간의 복잡한 관계를 직접 설계하고 관리하며 효율적인 데이터 접근 계층 구축
    - **보안 강화:** `BCryptPasswordEncoder`를 적용한 비밀번호 암호화 및 인터셉터를 활용한 비인가 사용자 접근 차단

---

### 📈 Technical Troubleshootings
- **이미지 경로 최적화:** 로컬과 배포 환경의 경로 구분자 차이 문제를 `application.properties` 설정 분리와 `WebMvcConfig`의 리소스 핸들러 매핑을 통해 해결
- **JPA 순환 참조 해결:** Entity를 API로 직접 반환할 때 발생하는 무한 루프 문제를 방지하기 위해 목적별 **DTO**를 설계하여 응답 데이터 최적화
- **데이터 무결성 유지:** 다수 상품 주문 시 일부 재고가 부족할 경우 발생할 수 있는 데이터 불일치 위험을 `@Transactional` 롤백 설계를 통해 차단

---

### 🎓 Education
- **[현대이지웰] Java 풀스택 개발자 아카데미 (2025.06 ~ 2025.12):**
    - 반응형 웹 디자인 개발 및 웹 프레임워크 활용 능력 습득
    - 이미지 및 코드 관리를 통한 웹 성능 최적화 실무 경험 습득

### 📫 Contact & Links
- **Email:** [hun03d@gmail.com](mailto:hun03d@gmail.com)
- **Blog:** [티스토리 주소](https://bugbite.tistory.com/)

# 안녕하세요, 송채린입니다 👋

> **눈에 보이는 상태가 아니라, 실제로 무슨 일이 일어나는지를 확인하는 클라우드 보안 개발자입니다.**

클라우드 네이티브 환경의 보안에 관심이 많습니다. 커널 수준의 이벤트 수집부터 백엔드 파이프라인까지, 데이터가 흐르는 전 구간을 다루며 시스템을 표면이 아닌 실제 동작으로 이해하는 것을 중요하게 여깁니다.

---

## 🛠 기술 스택

**Language**
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Cloud / Infra**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Security / Observability**
![eBPF](https://img.shields.io/badge/eBPF-FF6600?style=flat-square&logo=linux&logoColor=white)
![Tetragon](https://img.shields.io/badge/Tetragon-5E6AD2?style=flat-square)

**Database**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

---

## 🚀 대표 프로젝트

### VARA — 쿠버네티스 환경 클라우드 네이티브 보안 플랫폼 (CNAPP)

> 고객 EKS 환경에 읽기 전용 에이전트를 심어 커널·클러스터·클라우드 데이터를 수집하고, 침해가 어디까지 번질지를 확률적으로 계산해 "어디부터 막아야 하는가"를 제시하는 클라우드 네이티브 보안 플랫폼

🔗 **[Team VARA Organization](https://github.com/TEAM-VARA)**
📅 2026.04 ~ 2026.07 | 👤 인프라 / 백엔드 인프라 담당 (5인 팀)

**담당한 일**
- AWS EKS 환경 구축 및 커널·클러스터·클라우드 3개 층위 데이터를 수집하는 읽기 전용 에이전트 3종(K8s API, eBPF, AWS API) 개발
- eBPF(Tetragon) 기반 에이전트로 프로세스·네트워크 이벤트 실시간 수집 — `tcp_sendmsg` 후킹으로 kube-proxy NAT 이후의 실제 Pod IP 확보
- 커널 이벤트 수집부터 백엔드 파이프라인까지 데이터 전 구간 설계
- 2단계 판정(watchlist → 룰셋) 기반 런타임 이상탐지 구현, 컨테이너 부팅 노이즈를 시점 기반으로 걸러 오탐 제거
- 침해 전파 반경(blast radius)을 도달 확률 모델(Dijkstra 최대확률경로)로 정량화

**기술 스택**: Go(Gin, client-go, AWS SDK v2), Python, Kubernetes, Docker, Tetragon/eBPF, PostgreSQL, Redis, AWS(EKS, EC2, VPC)

<img width="1920" height="2032" alt="vara_전체_아키텍처" src="https://github.com/user-attachments/assets/4da6e148-4107-4060-b9cb-e56769a18849" />


<!-- [ ] 여유되면: 아키텍처 다이어그램 이미지 추가하면 훨씬 좋음 -->
<!-- [ ] 여유되면: 데모 스크린샷이나 GIF 추가 -->

---

## 🏆 자격증 & 교육

- **NCP** (NAVER Cloud Platform Certified Professional) · 2026.01
- **NCA** (NAVER Cloud Platform Certified Associate) · 2025.07
- **네이버클라우드 아카데미** 1기 & Advanced 과정 수료 · 2025~2026
- **KISA S-개발자** (최정예 보안SW 개발자 양성과정) 수료 · 2026

---

## 📫 Contact

- Email: scr226@naver.com

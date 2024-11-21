# OSCP(Offensive Security Certified Professional) 스터디 가이드

이 리포지토리는 **OSCP(Offensive Security Certified Professional)** 자격증을 준비하는 분들을 위한 학습 자료와 실습 예제를 제공합니다. 해킹 및 침투 테스트 능력을 향상시키기 위한 다양한 자료를 확인할 수 있습니다.

---

## 📘 OSCP 자격증 소개

**OSCP**는 Offensive Security에서 제공하는 실무 중심의 침투 테스트 자격증입니다. 이는 실습 기반 시험으로, 해킹 기법과 침투 테스트 방법론에 대한 숙련된 이해가 필요합니다.

### 시험 정보
- **시험 시간:** 24시간 (보고서 제출 포함 48시간)
- **시험 형식:** 실습 기반 (다양한 머신 해킹)
- **합격 조건:** 최소 70점 (최대 100점)
- **시험 주제:**
  - 정보 수집 및 스캐닝
  - 취약점 분석
  - 네트워크 및 애플리케이션 공격
  - 권한 상승
  - 리눅스 및 윈도우 시스템 익스플로잇

공식 정보는 [OSCP Certification Page](https://www.offensive-security.com/pwk-oscp/)에서 확인하세요.

---

## 📋 리포지토리 구조

이 리포지토리는 다음과 같은 구조로 구성되어 있습니다:


---

## 🛠 사전 준비

시작하기 전에 다음을 준비하세요:
- **Kali Linux** 설치 및 설정
- 기본 네트워크 및 리눅스 명령어 지식
- Metasploit, Burp Suite, Nmap 등 해킹 도구 사용법 이해
- Hack The Box(HTB), TryHackMe(THM)와 같은 플랫폼에서 실습 경험

---

## 🔍 학습 주제 및 자료

### 1. 정보 수집 및 스캐닝
- Nmap, Netcat 활용
- 기본 네트워크 스캐닝 및 맵핑
- 서비스 및 버전 정보 수집

### 2. 취약점 분석
- Exploit-DB에서 익스플로잇 검색
- CVE 및 취약점 분석
- Nessus, OpenVAS 활용

### 3. 네트워크 및 애플리케이션 공격
- 웹 애플리케이션 취약점 분석 (SQLi, XSS 등)
- FTP, SMB, SSH 공격 기법
- Hydra를 사용한 브루트포싱

### 4. 권한 상승
- 리눅스 및 윈도우 권한 상승 기법
- SUID, Scheduled Task 활용
- Kernel Exploit

### 5. 후속 공격 및 유지
- 리버스 셸, 바인드 셸 활용
- 퍼시스턴스 유지
- 로그 삭제 및 포렌식 회피

---

## 🚀 시작하기

1. **리포지토리 클론**
   ```bash
   git clone https://github.com/yourusername/oscp-study-guide.git
   cd oscp-study-guide



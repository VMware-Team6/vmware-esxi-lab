# vmware-esxi-lab  
<br>

## 📂 목차
1. 👥 **팀 소개**
2. 📝 **기획**  
      - 프로젝트 개요  
      - 목적  
      - 프로젝트 진행 과정 요약  
3. 🛠 **개발 환경**
4. 🏗 **아키텍처**
5. 🔍 **프로젝트 수행**  
      - Server  
      - Host  
      - vCenter  

<br><br>

## 👥 팀 소개
<br><br>

## 📝 기획

### 1️⃣ 프로젝트 개요 📌  
본 프로젝트는 **VMware의 핵심 기술을 실습하며 가상화 환경을 설계, 구축, 운영하는 능력을 배양하는 것**을 목표로 합니다.  
ESXi, vCenter, 네트워크 가상화(vSwitch), 스토리지 연동(TrueNAS), 그리고 **고가용성(HA, DRS, vMotion)까지 실습**하여 **기업 환경에서의 가상화 솔루션 운영 역량을 향상**할 수 있도록 구성되었습니다.

<br>

### 2️⃣ 목적 🎯  
- ✅ **VMware 기반 가상화 환경의 기본 개념 및 실무 적용 능력 향상**
- ✅ **서버 및 네트워크 가상화에 대한 심층적인 이해**
- ✅ **스토리지 연동을 통한 가상 머신의 효율적 운영 능력 습득**
- ✅ **vMotion을 활용한 VM 무중단 마이그레이션 및 운영 실습**
- ✅ **DRS 및 HA를 통한 리소스 자동화 및 장애 대응 역량 강화**

<br>

### 3️⃣ 프로젝트 진행 과정 요약 🔄  
#### 🖥 **Server**
- ESXi 설치
- Local Datastore, vCenter, TrueNAS 설치
- Windows VM: DNS, NTP, FTP 설정
- 가상 네트워크 구성

#### 🏢 **Host**
- ESXi 2개 설치
- NTP Client 설정

#### 🎛 **vCenter**
- DataCenter, Cluster 생성
- Host ESXi 추가
- 사용자 생성, permission 설정
- TrueNAS 연결 설정

<br><br>

## 🛠 개발 환경  
| 항목              | 내용 |
|------------------|-----------------------------------------------------|
| **🖥 가상화 플랫폼** | VMware ESXi, vCenter Server Appliance (VCSA) |
| **💻 호스트 장비**  | 물리 서버 및 개별 ESXi 호스트(노트북) |
| **🌐 네트워크 구성** | vSwitch, 가상 네트워크, VLAN 설정 |
| **🗄 스토리지**     | TrueNAS (iSCSI/NFS 연동) |
| **📦 VM 운영 체제**  | AWS Linux, Windows 2022 Server |

<br><br>

## 🏗 아키텍처  
<img src="https://github.com/user-attachments/assets/a6616e14-cf42-4517-b700-3bb0d3144541" width="800"/> <br>
<img src="https://github.com/user-attachments/assets/363fea6e-04ba-4afd-9542-fa2587a0afb0" width="800"/> <br>

<br><br>

## 🔍 프로젝트 수행  
### 1️⃣ 🖥 Server  

<br>

### 2️⃣ 🏢 Host  

<br>

### 3️⃣ 🎛 vCenter  

<br>





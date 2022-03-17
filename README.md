# PIMS
## 사내 프로젝트 정보 관리 시스템

### ※ 프로젝트 개요
> PIMS  (project informaion manage system) 
> : 사내 프로젝트 정보 관리 시스템
  
### ○ Requirements Specification
#### - 사용자
> 1. 현재 사내에서 어떤 프로젝트들이 진행되고 있고 인력이 어떻게 배치되어 있는지 확인 할 수 있다.
> 2. 프로젝트 진행 중 이슈 발생 시 팀원 또는 원하는 구성원에게 이슈를 공유하고 피드백을 받는다.
> 3. 프로젝트 후 해당 프로젝트에 대해 평가하고 사용한 기술들을 전사로 공유 할 수 있다.
> 4. 개인 사내 프로필을 만들어 자기가 사용할 수 있는 기술들을 명세하고 그 척도를 수치화 하여 경영진의 인력 배치 효율을 높인다.
> 5. 인사평가의 개념이 아닌 팀원간의 실질적 개발 능력을 평가할 수 있다.
> 6. 프로젝트에 관한 문제 발생 시 경영진에게 직접적으로 요구할 수 있는 비공개 게시판을 제공한다.

#### - 관리자
> 1. 현재 사내에서 진행 중인 모든 프로젝트를 등록, 관리하며 직접적인 인력 배치를 할 수 있다.
> 2. 고객사의 정보를 관리 할 수 있다.
> 3. 사원들의 프로필, 경력과 개발능력평가 그리고 공공데이터를 활용한 현재 IT 업계 기준으로 사원의 연봉을 추천해준다. 
> 3. 프로젝트와 관련한 재무 관리 기능을 제공한다.

### ○Architecture 
![pims msa architecture](https://user-images.githubusercontent.com/63697029/158719736-e05d5470-fca7-4acc-9424-0333c4b07e83.jpg)
> 초기 모든 도메인이 MAIN application에 집중 되어 있지만 향후 MSA 방식의 설계를 지향합니다.


### ○ERD CLOUD (현재 설계중)
- https://www.erdcloud.com/d/xijrsTX8Bchwhvo3B


# Version 1.6.4


## 신규 추가/개선 기능

각 MicroService에 대한 기능 안정화 BugFix 적용

|서비스|버전   |
|---   |---    |
| console     		| 1.6.4.2       |
| console-api     	| 1.6.4.5      |
| identity     		|  1.6.4.1     |
| secret     		|  1.6.4     |
| repository     	| 1.6.4      |
| plugin     		|  1.6.4     |
| config     		|  1.6.4     |
| inventory     	| 1.6.4      |
| monitoring     	| 1.6.4      |
| statistics     	| 1.6.4      |
| billing     		| 1.6.4      |
| power-scheduler     	| 1.6.4       |
| supervisor     	| 1.6.4      |

## Plugin 
SpaceONE v1.6.4 에 호환되는 플러그인 버전을 안내 드립니다. 
기능에 이상이 있는 경우 아래의 버전으로 플러그인 최신 업데이트가 필요 합니다.

### 호환 플러그인 리스트

|추가여부|plugin 종류|Provider|플러그인 이름|버전|
|:---:|---|:---:|:---:|:---:|
|-|identity.Auth|oAuth|google-oauth2|v1.1|
|-|inventory.Collector|aws|aws-trusted-advisor|v1.2|
|Updated|inventory.Collector|aws|aws-ec2|v1.10|
|Updated|inventory.Collector|aws|aws-cloud-service|v1.8.2|
|Updated|inventory.Collector|aws|aws-power-state|v1.5.1|
|-|inventory.Collector|aws|aws-personal-health-dashboard|v1.1|
|Updated|inventory.Collector|google cloud|google-cloud-compute|v1.2.5|
|Updated|inventory.Collector|google cloud|google-cloud-services|v1.1.9|
|Updated|inventory.Collector|google cloud|google-cloud-power-state|v1.1.2|
|Updated|inventory.Collector|azure|azure-vm|v1.2.1|
|Updated|inventory.Collector|azure|azure-cloud-services|v1.1.1|
|Updated|inventory.Collector|azure|azure-power-state|v1.0|
|Updated|inventory.Collector|spaceone|monitoring-metric-collector|v1.1|
|Updated|monitoring.DataSource|aws|aws-cloudwatch|v1.1|
|Updated|monitoring.DataSource|google cloud|google-cloud-stackdriver|v1.0.3|
|-|monitoring.DataSource|aws|azure-monitor|v1.0|
|-|power_scheduler.Controller|aws|aws-power-scheduler-controller|v1.4.4|
|-|power_scheduler.Controller|google cloud|google-cloud-power-controller|v1.1.2|
|-|billing.DataSource|hyperbilling|aws-hyperbilling|v1.0.2|


## Hotfix Update
|일자|Micro Service|Version|변경사항|
|---|:---:|:---:|:---:|
|2021.03.10|console|1.6.4.3|Not applied search filter issue fixed |
|2021.03.10|repository|1.6.4.1|Authorization failing error fixed|
|2021.03.10|console|1.6.4.4|Service Account Creation Failed fixed|
|2021.03.12|console-api|1.6.4.6|Project tree error fixed|



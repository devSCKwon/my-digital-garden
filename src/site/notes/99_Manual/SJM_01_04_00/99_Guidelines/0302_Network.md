---
{"dg-publish":true,"permalink":"/99-manual/sjm-01-04-00/99-guidelines/0302-network/","title":"22.3.2 네트워크보안지침","tags":["정보보안관리규정","보안","기술적보안","네트워크보안"],"noteIcon":"","created":"","updated":""}
---

### 1. 개요
1. ##### 목적
	1. 본 지침서는 사내 네트워크 구성 및 외부 네트워크와 연결시 요구되는 정보보호의 수준을 향상시킴으로써 안정적인 네트워크 인프라를 운영하는데 목적을 둔다. 
2. ##### 적용범위
	1. 사내 네트워크 및 인터넷과 같은 외부와 연결되는 모든 네트워크를 그 적용범위로 하며, 그 시스템을 직접 관리, 운영하는 담당자들을 대상으로 한다. 
3. ##### 용어 정의 
	1. 인터넷 구간
		1. 인터넷 관련 서비스를 목적으로 불특정 다수의 접속을 허용한다. 
	2. DMZ 구간 
		1. 서비스를 목적으로 하는 네트워크로 불특정 다수의 접속을 허용한다. 
		2. 외부의 불량 침입으로 인한 서비스의 장애를 최소화 하기 위하여 서버별 port 단위로 접근통제를 하여야 하며 취약한 포트(FTP, Telnet 등)은 Source와 Destination 별 포트관리를 해야 한다. 
	3. 내부 네트워크 구간
		1. 외부로부터의 침입에 대비한 접근차단시스템이 운영되어야 한다. 
		2. 업무용 이외나 보안상 취약한 포트가 있을 경우 차단한다.
	4. ==NTP 서버==
		1. ==NTP(Network Time Protocol) 서버는 시간 동기화를 위해 사용되는 서버로, NTP 서버를 통해 동기화되는 시간 정보의 범위는 해당 NTP 서버의 네트워크 범위 내의 모든 장비들에게 적용한다.==
4. ##### 책임 및 권한
	1. 전사보안책임자
		1. 네트워크 시스템 전반에 대한 관리 책임을 가진다.  
		2. 네트워크 보안 관리가 수행되도록 감독할 책임을 가진다. 
		3. 시스템 도입 및 철수에 대한 승인과 책임을 가진다. 
	2. 기술보안담당자
		1. 네트워크 장비의 보안취약점을 점검하여 네트워크 운영담당자에게 보안 개선을 지시한다. 
		2. 보안사고 발생 시 사고대응을 하며, 보안책임자에게 보고한다.
	3. 네트워크 운영담당자
		1. 기술보안담당자와 겸임할 수 있다. 
		2. 네트워크 장비의 모니터링 성능관리, 장애, 변경관리를 수행한다. 
		3. 신규 장비 도입 발생 시 장비검토, 설치계획을 수립한다. 
		4. 취약점 발견시 기술보안담당자 및 보안책임자에게 보고 후 조치한다. 
		5. 보안사고 발생시 사고대응을 하며, 보안책임자 및 필요시 대표이사에게 보고한다.
### 2. 네트워크 시스템 운영
1. ##### 시스템 도입 및 설치
	1. 네트워크의 변경, 증설 등 환경의 변화에 따라 네트워크 시스템의 도입, 폐기 요구가 있는지 모니터링 하여야 하며, 적절한 도입 시기를 파악 한다. 
	2. 시스템 도입시, 서류상의 비교검토를 하며, 필요시 BMT(Bench Marking Test)를 통한 결과를 장비의 선정 기준으로 삼는다. 
	3. 기존 네트워크 장비와의 연동을 위한 보안성 검토를 수행해야 한다.  
	4. 네트워크 구성형태에 따른 위험을 사전 분석 및 평가해야 한다. 
	5. 시스템은 물리적 보안이 되어 있는 통제구역에 설치되어야 한다. 단, 사용자 시스템과 직접 연결이 되는 네트워크 Switch, 무선AP 등은 그 특성에 따라 일반구역에 설치 가능하다.
	6. 설치 후 자산관리 목록을 갱신하며, 결과를 보안책임자에게 보고한다.
	7. 외부 네트워크와 내부 네트워크의 접점 구간에는 방화벽이나 IPS 등 접근차단시스템이 운영되어야 한다. 
	8. ==설치된 네트워크는 지정된 NTP(Network Time Protocol) 서버를 통하여 해당 NTP 서버의 네트워크 범위 내의 모든 장비와 동기화되어야 한다.==
2. ##### 시스템 보안설정
	1. 장비의 관리자 선정, 기본ID 삭제, 기본 비밀번호 변경, 기술적 보안의 구성 점검 등을 하여야 한다. 
	2. 네트워크 장비에 대한 접근권한은 주기적으로 점검하고, 변동 사항 발생 시 보안책임자에게 보고하여야 한다. 
	3. 장비 접속은 콘솔을 통하는 것을 원칙으로 하고, 운영 및 모니터링을 위한 원격접속이 필요할 경우 운영자 단말기를 지정하여 운영한다. 
	4. 네트워크 장비에 원격접속 시 세션타임아웃을 구성하여 접속하여야 한다. 
	5. 설치 되는 장비의 시간을 동기화하여 무결성을 보장하여야 한다. 
	6. Data, Voice 장비는 장비 별로 기본 보안설정을 정의하고, 적용하여야 한다.
	7. 사내에 인가된 신뢰하는 소스를 통해서만 시간동기화를 사용한다. 악성 시간 소스에 의해 네트워크의 시간 기준 변경을 방지한다.
3. ##### 시스템 운영
	1. 네트워크 장비 및 통신회선에 대해 최소 일 1회 이상 모니터링을 하여 장애에 대비하여야 한다.
	2. ==ACL(Access Control List)을 이용한 접근통제를 할 때는 보안취약점 및 변경내역에 대한 검토를 한 후, 네트워크 운영담당자가 적용한다.== 
	3. 시스템 변경 발생시 계획서 및 완료사항을 보안책임자에게 보고하여야 한다. 
	4. 시스템 장애시 신속한 업무 복구를 위해 구성정보를 6개월 마다 백업을 하여야 하며, 정보는 1년 동안 보관하여야 한다.
	5. 시스템 구성정보 변동사항 발생시 백업을 하여야 하며, 정보는 1년 동안 보관하여야 한다.
	6. 장애 발생시 신속한 대응을 하여야 하며, 보안책임자에게 보고하여야 한다.
	7. 네트워크 장비에 대한 장애 방지를 위하여 주기적으로 장비의 점검을 실시하고, 그 결과를 보안책임자에게 보고하고, 문제점은 조치를 취하여야 한다. 
	8. 모니터링 도구를 이용하여 서비스중인 회선에 대한 트래픽 용량과 장비에 대하여 사용률을 모니터링하고, 매월 정기점검 보고서를 작성하여 전사보안책임자에게 제출한다.
4. ##### 시스템 폐기
	1. 시스템의 매각이나 폐기를 위하여 반출 전에 초기화 명령어나 버튼 등을 활용하여, 내부의 라우팅, 비밀번호 등의 설정정보를 초기화하여야 한다.   
### 3. 네트워크 관리 통제 
1. #####  네트워크 연결, 설치, 변경에 따른 승인
	1. 네트워크 신규 접속, 변경, 해지 작업은 승인을 득한 후 진행되어야 한다.
	2. 사설/공인 IP의 관리는 네트워크 운영담당자가 관리하며, 승인을 득한 후 신규 부여 및 회수/변경 등의 업무를 진행한다. 필요에 따라 선 작업 후 보고 할 수 있다. 
2. ##### 네트워크 구성 정보 관리 
	1. 허가 없이 네트워크의 구성도, 주소, 구성환경, 관련 시스템 정보 등을 무단으로 유출하여서는 안 되고, 외부로 공개되는 자료는 민감한 내용(IP등)을 삭제한 후 공개한다. 
	2. 네트워크 구성도, 현황 자료, 네트워크 주소할당자료 등 네트워크 관련 모든 자료는 인가된 자만이 접근 가능하도록 안전하게 보관한다.
3. ##### 네트워크 소프트웨어 보안관리 
	1. 장비의 펌웨어, 운영체제의 각종 버그 또는 보안 홀을 예방하기 위하여 네트워크 장비의 보안관련 패치나 권고안이 발표되는 것을 지속적으로 모니터링하며 보안 패치 적용여부를 검토 후 적용한다. 
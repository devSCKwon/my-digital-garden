---
{"dg-publish":true,"permalink":"/99-manual/sjm-01-04-00/99-guidelines/0303-system/","title":"22.3.3 시스템보안지침","tags":["정보보안관리규정","보안","기술적보안","시스템보안"],"noteIcon":"","created":"","updated":""}
---

### 1. 개요
1. ##### 목적
	1. 본 지침서는 서버시스템의 도입, 설치, 운영, 폐기 등의 업무 수행 시 시스템의 안전한 관리를 위해 준수해야 할 업무절차를 정의함으로써 불법 사용을 방지하고, 자산을 보호하는데 그 목적을 둔다. 
2. ##### 적용범위
	1. 사내 운영되고 있는 모든 서버 등 하드웨어 및 응용시스템, 데이터베이스 등 소프트웨어와 이런 자산을 이용해 업무를 수행하는 모든 사용자들을 대상으로 한다. 
3. ##### 용어 정의
	1. 시스템
		1. 서버, 저장장치 등의 하드웨어와 응용시스템, 데이터베이스 등의 소프트웨어를 총칭한다. 
	2. 응용프로그램
		1. 일상의 업무를 전산 프로그램화한 어플리케이션 프로그램과 상용화된 소프트웨어를 의미한다. 
	3. 데이터베이스
		1. 컴퓨터에 수록한 수많은 자료들을 쉽고 빠르게 추가, 수정, 삭제할 수 있도록 해주는 소프트웨어로서 데이터베이스 내의 정보를 검색하거나, 데이터베이스에 정보를 저장 및 관리하기 편리하고 효율적인 환경을 제공하는 시스템을 의미한다. 
	4. 무결성
		1. 데이터의 정밀성, 정확성을 의미하며, 데이터베이스에 저장된 값을 정확하게 유지하는 것을 의미한다. 
4. ##### 책임 및 권한
	1. 전사보안책임자
		1. 서버시스템에 대한 도입 및 운영, 폐기에 대한 승인과 전반적인 관리책임을 가진다. 
		2. 본 규칙에 따라 서버시스템의 보안 관리가 수행될 수 있도록 감독할 책임을 가진다.  
	2. 기술보안담당자
		1. 서버시스템의 설치 및 운영, 폐기에 따른 보안 이행여부를 점검한다. 
		2. 본 지침을 수정할 필요가 있다고 판단되는 경우 수정 후 전사보안책임자의 승인을 받는다. 
	3. 시스템운영담당자
		1. 기술보안담당자와 겸임할 수 있다. 
		2. 본 지침에 따라 서버시스템운영 및 장애처리업무를 수행한다.
		3. 시스템의 효율적 보안관리를 위해 필요한 자원을 요청할 수 있다. 
### 2. 시스템 운영
1. ##### 도입 및 설치
	1. 시스템 담당자는 반기 1회 이상 시스템 성능을 점검하여 도입 또는 폐기 여부를 검토하여야 한다. 
	2. 새로운 서버시스템을 도입할 때 필요 시 BMT를 실시하고 도입 목적에 맞는 용량과 성능에 따라 도입을 결정한다. 
	3. 시스템 설치 계획을 수립하고, 보안성 검토 및 승인을 받아 시스템을 설치한다. 
	4. 시스템은 물리적 보안이 되어 있는 통제구역에 설치되어야 한다. 
	5. 설치 후 자산관리 목록을 갱신하며, 결과를 전사보안책임자에게 보고한다. 
2. ##### 운영
	1. 시스템의 처리속도 및 용량을 주기적으로 점검하여야 한다. 
	2. 시스템 접근권한의 변동 사항을 주기적으로 점검하여 전사보안책임자에게 보고한다. 
	3. 시스템 장애 시 신속한 업무 복구를 위해 OS 및 DB에 대한 백업을 주기적으로 수행하여야 하며, 수행결과여부를 기록관리하여야 한다.
	4. 시스템 공급업체의 보안관련 패치나 권고안 발생 시 적용여부 검토 후 주요정보를 백업하고, 보안패치를 적용하여야 한다. 
	5. 하드웨어 및 운영체제상의 결함으로 인한 시스템의 문제발생에 대비하여 적절한 유지보수를 수행하여야 한다.
3. ##### 폐기
	1. 시스템 폐기요구 발생 시 승인 후 폐기 처리한다. 
	2. 저장장치는 별도 폐기하여야 하며, 디가우저, 천공장치 등을 사용하여 정보가 복구되지 않게 폐기해야 한다. 
	3. 폐기 완료 후 자산관리 목록을 갱신하여야 한다.
### 3. 시스템 보안
1. ##### 시스템 설치시 보안설정
	1. 3.1.1	시스템의 관리자를 선정하여야 한다. 
	2. 3.1.2	비인가 접근이나 정보유출 등을 방지하기 위해 적절한 보안시스템을 갖추어야 한다.
	3. 3.1.3	시스템 설치시 제공되는 기본계정 중 불필요한 계정은 삭제되어야 한다. 
	4. 3.1.4	시스템 설치시 제공되는 패스워드는 변경되어야 한다. 
	5. 3.1.5	불필요한 서비스는 중지하여야 한다.
	6. 3.1.6	시간을 동기화하여 무결성을 보장하여야 한다. 
2. ##### 시스템 운영시 보안설정
	1. 중요 업무 시스템은 개발, 테스트 및 운영시스템으로 분리 운영되어야 한다. 
	2. 비밀, 민감한 정보는 전송 시 암호화되어야 한다. 
	3. 개인정보 DB 내 민감한 정보에 대해서는 반드시 암호화하여 저장하여야 한다.
	4. 패스워드, 생체정보 등 본인임을 인증하는 정보에 대해서는 복호화되지 않도록 일방향 암호화하여 저장한다.
	5. ==화면보호기는 10분 이하로 설정하고 패스워드를 지정한다.==
	6. 중요 업무 시스템은 로그인 성공 시 직전 로그인 정보가 화면에 표시되어야 한다.
	7. 데이터베이스, 소스코드, 운영체제, 응용프로그램 등 모든 시스템에 대한 접근통제가 적용되어야 한다.
	8. 시스템을 일정기간 미사용 시 자동로그오프나 세션중단기능이 설정되어야 한다. 
	9. 보안관련 이벤트 로그 및 시스템 접근로그는 3년 이상 보관한다.
	10. 임시적 외부 개발자나 용역업체 직원이 프로그램 개발, 변경에 참여하는 경우 제한된 방법 및 승인에 의하여 접속을 허용하도록 한다.
	11. 시스템에 대한 주기적인 취약점 점검 및 조치가 이루어져야 한다. 
3. ##### 사용자 계정 관리
	1. 사용자 계정의 등록, 변경, 삭제는 공식적인 절차에 의거 수행되어야 하고, 계정의 등록, 변경, 삭제의 시행 이력은 관리되어야 한다. 
	2. 유지보수, 장애처리 등의 목적으로 임시 발급된 계정은 업무 종료 즉시 삭제되어야 한다. 
	3. 공용ID는 사용하지 않아야 하며, 모든 사용자는 유일한 계정이 부여되어야 한다. 
	4. 계정이 생성되면 사용자 확인 후 전달되어야 하며, 사용자는 최초 로그인 후 초기 패스워드를 변경하여야 한다. 
	5. 사용자의 퇴직 등 계정삭제 사유 발생 시 24시간 이내 권한이 삭제되어야 한다. 
	6. 서버시스템 관리자는 주기적으로 계정 발급 및 로그인 현황을 검토하여야 한다.
	7. 시스템 접근로그는 최소 반기 1회 검토하여 퇴직자 계정 사용 여부, 계정도용에 대한 위험성이 분석되어야 한다. 
4. ##### ==패스워드 관리==
	1. ==패스워드의 길이는 최소 8자리 이상 숫자, 영문자, 특수기호를 포함==하여 생성되어야 한다. 
	2. 패스워드에는 쉽게 추측할 수 있는 정보가 포함되지 않도록 한다. (예: 아이디와 동일한 패스워드, 규칙적인 문자/숫자, 사용자 이름, 사번 등)
	3. ==사용자가 패스워드를 사용할 수 있는 최대 기간은 90일로 제한==되어야 한다. 
	4. ==직전 패스워드는 재사용이 불가==해야 한다.
	5. ==연속 5회(단 시스템 중요도에 따라 횟수 조정 가능) 입력 오류 시 해당 계정은 잠금 상태==가 되어야 하며, 관리자는 사용자 확인 후 계정잠금해제 및 패스워드를 초기화 해야 한다.
	6. 패스워드는 일방향 암호화된 형태로 저장되어야 하며, 화면상에 읽을 수 없는 형태로 표시되어야 한다. 
5. ##### 변경통제
	1. 서버, 저장장치 및 기타 하드웨어 변경통제 
		1. 패치적용이나 시스템 파라미터(IP, 환경설정 값 등) 변경발생 시 타당성 검토 및 테스트를 수행한다. 
		2. 주요정보 백업을 수행한 후 적용하고 그 기록을 보고한다. 
	2. 데이터베이스 변경통제 
		1. 패치적용이나 시스템 파라미터 변경발생 시 타당성 검토 후 테스트를 수행한다.
		2. 현재 설정값 백업 후 적용하고 그 기록을 보고한다. 
	3. 응용프로그램 변경통제 
		1. 응용프로그램 변경 및 적용은 공식적인 절차에 의거 수행되어야 한다.
		2. 변경 완료 시 해당 응용프로그램과 적용하고자 하는 운영환경이 회사가 정한 보안 정책을 준수하고 있는지 보안성을 검토하여야 하며, 충분한 기능 검증 테스트를 수행하고 승인을 득한 후 운영환경으로 이관되어야 한다. 
		3. 주민등록번호, 계좌번호 등 개인정보 및 중요정보를 테스트 데이터로 사용할 경우에는 실 데이터를 변환해서 사용하여야 한다. 
		4. 응용프로그램 개발도 위와 같은 절차를 적용한다. 
6. ##### 백업 및 매체관리
	1. 시스템 담당자는 시스템 장애 시 신속한 업무복구를 위하여 백업을 수행하여야 한다.
	2. 백업은 시스템의 완전 소실의 경우에도 복구 가능한 수준으로 이루어져야 한다. 
	3. 백업매체는 비인가자가 접근할 수 없는 격리된 장소 및 화재 등 재난에도 망실되지 않는 장소에 보관하여야 한다. 
	4. 백업매체의 폐기 시에는 정보를 복구할 수 없게 폐기해야 하며, 관련 로그는 기록관리 및 그 결과를 보고하여야 한다. 
	5. 시스템의 장애 시에는 백업매체를 사용하여 신속하게 복구하여야 한다. 
7. ##### 유지보수
	1. 공급사의 권장서비스 기간과 설명서에 따라 정비, 보수하여야 한다.
	2. 유지보수 서비스는 인가된 직원에 의해 시행되어야 하며, 유지 보수 작업 내역을 기록하여야 한다.
	3. 모든 보수내역과 의심되는 결함은 기록되어야 한다. 
	4. 시스템 개발 및 유지보수는 규정된 절차에 따라 인가자에 의해 수행되어야 시스템 담당자는 유지보수 시에 동석하여야 한다.
	5. 시스템 담당자는 지속적으로 시스템의 취약성 정보를 수집하고, 해당 취약성에 대한 대응책을 수립, 적용하여야 한다.
8. 용량 및 성능 관리
	1. 시스템 담당자는 시스템을 점검하고, 매월 정기 점검 보고서를 작성하여 부서장에게 보고하여야 한다.
9. 보안패치
	1. 시스템 담당자는 시스템 별 보안취약점을 확인하고, 타당성 검토 및 테스트를 수행한 후 패치를 수행한다
	2. 시스템 별 보안패치 목록, 보안패치 작업일 등 패치적용 현황을 관리한다.
10. 장비 반출
	1. 반출하기 위해서는 사전에 반출 승인권자의 승인을 받아야 한다.
	2. 자산의 반입 및 반출 시 해당 기록을 유지하여야 한다.
11. 용도변경 및 폐기
	1. 서버 담당자는 해당 서버의 용도 변경 시 서버에 저장되어 있는 정보를 삭제해야 하며 장비의 프로파일을 작성, 갱신 및 유지해야 한다.
	2. 시스템 폐기요구 발생 시 승인 후 폐기 처리한다.
	3. 완료 후 자산관리 목록을 갱신하여야 한다.
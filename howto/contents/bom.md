# 3.1 BOM \(Bill of Materials\)

{% tabs %}
{% tab title="OpenChain Specification \(한국어\)" %}
### 3.1 BOM

공급 대상 소프트웨어를 구성하는 각 오픈소스 컴포넌트\(및 식별된 라이선스\)를 포함하는 BOM을 작성하고 관리하는 프로세스가 있다.

#### 입증 자료:

 3.1.1 공급 대상 소프트웨어를 구성하는 오픈소스 컴포넌트 모음에 대한 정보를 식별, 추적, 검토, 승인 및 보관하는 문서화된 절차  
 3.1.2 공급 대상 소프트웨어에 대해 문서화된 절차가 적절히 준수되었음을 입증하는 오픈소스 컴포넌트 기록.
{% endtab %}

{% tab title="OpenChain Specification \(English\)" %}
### 3.1 Bill of Materials

A process exists for creating and managing a bill of materials that includes each Open Source component \(and its Identified Licenses\) from which the Supplied Software is comprised.

#### Verification Material\(s\):

 3.1.1 A documented procedure for identifying, tracking, reviewing, approving, and archiving information about the collection of Open Source components from which the Supplied Software is comprised.  
 3.1.2 Open Source component records for the Supplied Software that demonstrates the documented procedure was properly followed.
{% endtab %}
{% endtabs %}

오픈소스 컴플라이언스 활동의 가장 기본은 바로 공급 대상 소프트웨어에 포함된 오픈소스 현황을 파악하는 것이다. 공급 대상 소프트웨어에 포함된 오픈소스와 그 라이선스를 식별하여 그 정보를 담고있는 BOM을 작성하고 관리하는 프로세스를 구축해야 한다. 공급 대상 소프트웨어마다 어떤 오픈소스가 포함되어 있는지 알고 있어야 소프트웨어를 배포할 때 각 라이선스가 요구하는 의무 사항을 준수할 수 있기 때문이다. 모든 오픈소스는 배포 대상 소프트웨어에 통합하기 전에 검토 및 승인되어야 한다. 오픈소스의 기능, 품질 뿐만 아니라 출처, 라이선스 요건을 충족하는지 검토가 되야 한다. 이를 위해 검토 요청 → 리뷰 → 승인 과정이 필요하다. \[부록 02\]에서는 기업의 오픈소스 컴플라이언스를 위한 프로세스 전과정에 대해 설명하고 있다. 식별부터 등록까지의 과정을 통해 BOM을 작성하고 관리하게 된다.

{% page-ref page="../../appendix/process.md" %}

공급 대상 소프트웨어에 포함된 오픈소스 목록은 문서화하여 보관해야 한다. Eclipse 재단에서 후원하는 오픈소스 프로젝트인 SW360\(https://projects.eclipse.org/proposals/ sw360\)은 공급 대상 소프트웨어별로 포함하고 있는 오픈소스 목록을 트래킹할 수 있는 기능을 제공한다. SW360 사용 방법은 \[부록 03\]을 참고할 수 있다.

{% page-ref page="../../appendix/tools/" %}

오픈소스 컴플라이언스 프로세스의 모든 과정과 결과는 문서화가 되어야 한다. 이메일을 사용하는 것 보다는 Jira, Bugzilla 등의 이슈 트래킹 시스템을 이용하는 것이 이러한 과정을 효율적으로 문서화 할 수 있다.


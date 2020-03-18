# 3.2 라이선스 컴플라이언스

{% tabs %}
{% tab title="OpenChain Specification 2.0 \(한국어\)" %}
### 3.2 라이선스 컴플라이언스

프로그램은 공급 대상 소프트웨어에 대해 소프트웨어 공급 담당자가 접하게 되는 일반적인 오픈소스 사용 사례를 관리할 수 있어야 하며, 다음과 같은 사례가 포함될 수 있다\(이 목록이 완전한 것은 아니며, 모든 사용 사례가 적용되어야 하는 것은 아니다\).:

- 바이너리 형태로 배포;  
 - 소스 형태로 배포;  
 - Copyleft 의무를 발생시킬 수 있는 다른 오픈소스와 통합;  
 - 수정한 오픈소스를 포함;  
 - 공급 대상 소프트웨어 내에서 상호 작용하는 다른 컴포넌트와 호환되지 않는 라이선스 하의 오픈소스 또는 기타 소프트웨어를 포함; - 저작자 표시 요건이 있는 오픈소스를 포함.

#### 입증 자료:

 3.2.1 공급 대상 소프트웨어의 오픈소스 컴포넌트에 대해 일반적인 오픈소스 라이선스 사용 사례를 처리하기 위한 문서화된 절차.
{% endtab %}

{% tab title="OpenChain Specification 2.0 \(English\)" %}
### 3.2 License Compliance

The Program must be capable of managing common Open Source license use cases encountered by Software Staff for Supplied Software, which may include the following use cases \(note that the list is neither exhaustive, nor may all of the use cases apply\):

- distributed in binary form;  
 - distributed in source form;  
 - integrated with other Open Source such that it may trigger copyleft obligations;  
 - contains modified Open Source;  
 - contains Open Source or other software under an incompatible license interacting with other components within the Supplied Software; and/or - contains Open Source with attribution requirements.

#### Verification Material\(s\):

 A documented procedure for handling the common Open Source license use cases for the Open Source components of the Supplied Software.
{% endtab %}
{% endtabs %}

오픈소스 라이선스를 제대로 준수하기 위해서는 오픈소스 라이선스 별로 요구하는 사항에 대해 정확히 알고 있어야 한다. 개별 소프트웨어 개발자가 이를 일일이 파악하는 것은 어렵기 때문에 오픈소스 책임자는 자주 사용되는 오픈소스 라이선스 들에 대해 일반적인 사용 사례별 요구사항/주의사항을 정리하여 회사 내부에 공유하는 것이 좋다. 오픈소스 책임자는 자주 사용되는 오픈소스 라이선스별로 일반적인 사용 사례에 대한 의무 요약 자료를 제공한다. 오픈소스 라이선스에 대한 일반적인 가이드와 라이선스 의무 요약 자료는 NIPA에서 제공하는“공개SW 라이선스 가이드”를 참고할 수 있다. \([https://www.oss.kr/oss\_license](https://www.oss.kr/oss_license)\) \[부록 2\] 오픈소스 컴플라이언스 프로세스 \(예시\)의 오픈소스 컴플라이언스 프로세스의 식별, 검사, 문제해결, 리뷰, 승인 단계를 통해 공급 대상 소프트웨어의 오픈소스 컴포넌트에 대해 일반적인 오픈소스 라이선스 사용 사례를 처리할 수 있다.

{% page-ref page="../../appendix/process.md" %}

식별 및 검사 단계에서는 소스코드 스캔 도구를 사용할 수 있다. 소스코드 스캔 도구는 무료로 사용할 수 있는 오픈소스 기반 도구부터 상용 도구까지 다양하게 있다. 각 도구들은 특장점 들이 있지만 어떤 하나도 모든 문제를 해결할 수 있는 완벽한 기능을 제공하지 않는다. 따라서 기업은 제품의 특성과 요구사항에 맞는 적합한 도구를 선택해야 한다. 많은 기업들이 이러한 자동화된 소스 코드 스캔 도구와 수동 검토를 병행하여 이용한다. Linux Foundation의 FOSSology Project는 오픈소스로 공개된 소스 코드 스캔 도구로서 기업들이 손쉽게 무료로 사용할 수 있다. 사용 방법은 \[부록 03\] 오픈소스도구 \(FOSSology, SW360\) 참고할 수 있다.

{% page-ref page="../../appendix/tools/" %}


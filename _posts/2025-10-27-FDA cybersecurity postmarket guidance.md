---
title:  "[FDA] Postmarket Management of Cybersecurity in Medical Devices (번역 포함)"
last_modified_at: 2025-10-27 15:22:57 ## ctrl+shift=I
categories: 
  - guidance
tags:
  - guidance
  - regulatory
  - cybersecurity
toc: true
toc_sticky: true
toc_label: "Table of Contents"
---
**Postmarket Management of Cybersecurity in Medical Devices**

Document issued on December 28, 2016.
The draft of this document was issued on January 22, 2016.

**의료기기의 사이버보안에 대한 시판 후 관리**

문서 발행일: 2016년 12월 28일
본 문서의 초안 발행일: 2016년 1월 22일

# I. Introduction

The Food and Drug Administration (FDA) is issuing this guidance to inform industry and FDA staff of the Agency's recommendations for managing postmarket cybersecurity vulnerabilities for marketed and distributed medical devices. In addition to the specific recommendations contained in this guidance, manufacturers are encouraged to address cybersecurity throughout the product lifecycle, including during the design, development, production, distribution, deployment and maintenance of the device.[^1] A growing number of medical devices are designed to be networked to facilitate patient care. Networked medical devices, like other networked computer systems, incorporate software that may be vulnerable to cybersecurity threats. The exploitation of vulnerabilities may represent a risk to health and typically requires continual maintenance throughout the product life cycle to assure an adequate degree of protection against such exploits. Proactively addressing cybersecurity risks in medical devices reduces the overall risk to health.

This guidance clarifies FDA's postmarket recommendations and emphasizes that manufacturers should monitor, identify, and address cybersecurity vulnerabilities and exploits as part of their postmarket management of medical devices. This guidance establishes a risk-based framework for assessing when changes to medical devices for cybersecurity vulnerabilities require reporting to the Agency and outlines circumstances in which FDA does not intend to enforce reporting requirements under 21 CFR part 806. 21 CFR part 806 requires device manufacturers or importers to report promptly to FDA certain actions concerning device corrections and removals. However, the majority of actions taken by manufacturers to address cybersecurity vulnerabilities and exploits, referred to as "cybersecurity routine updates and patches," are generally considered to be a type of device enhancement[^2] for which the FDA does not require advance notification or reporting under 21 CFR part 806. For a small subset of actions taken by manufacturers to correct device cybersecurity vulnerabilities and exploits that may pose a risk to health, the FDA would require medical device manufacturers to notify the Agency.[^3] Risks to health posed by the device may result in patient harm. This guidance recommends how to assess whether the risk[^4] of patient harm is sufficiently controlled or uncontrolled. This assessment is based on an evaluation of the likelihood of exploit, the impact of exploitation on the device's safety and essential performance,[^5] and the severity of patient harm if exploited.

This document is not intended to provide guidance on reporting to FDA when a device has or may have caused or contributed to a death or serious injury as required by section 519 of the Federal Food, Drug, and Cosmetic Act (FD&C Act) and the Medical Device Reporting (MDR) Regulation in 21 CFR part 803. For an explanation of the current reporting and recordkeeping requirements applicable to manufacturers of medical devices, please refer to the [Medical Device Reporting for Manufacturers Guidance](http://www.fda.gov/MedicalDevices/DeviceRegulationandGuidance/GuidanceDocuments/UCM359566).

For the current edition of the FDA-recognized standard(s) referenced in this document, see the [FDA Recognized Consensus Standards Database](http://www.accessdata.fda.gov/scripts/cdrh/cfdocs/cfStandards/search.cfm) Web site.

FDA's guidance documents, including this final guidance, do not establish legally enforceable responsibilities. Instead, guidances describe the Agency's current thinking on a topic and should be viewed only as recommendations, unless specific regulatory or statutory requirements are cited. The use of the word should in Agency guidance means that something is suggested or recommended, but not required.

[^1]: See FDA Guidance titled ["Content of Premarket Submissions for Management of Cybersecurity in Medical Devices"](http://www.fda.gov/MedicalDevices/DeviceRegulationandGuidance/GuidanceDocuments/UCM356190) ["의료기기의 사이버보안 관리를 위한 시판 전 제출 내용"](http://www.fda.gov/MedicalDevices/DeviceRegulationandGuidance/GuidanceDocuments/UCM356190)이라는 제목의 FDA 지침 참조

[^2]: See FDA Guidance titled: ["Distinguishing Medical Device Recalls from Medical Device Enhancements"](http://www.fda.gov/downloads/MedicalDevices/DeviceRegulationandGuidance/GuidanceDocuments/UCM418469.pdf). ["의료기기 회수와 의료기기 개선의 구별"](http://www.fda.gov/downloads/MedicalDevices/DeviceRegulationandGuidance/GuidanceDocuments/UCM418469.pdf)이라는 제목의 FDA 지침 참조

[^3]: See 21 CFR 806.10. 21 CFR 806.10 참조

[^4]: ANSI/AAMI/ISO 14971: 2007/(R)2010: Medical Devices – Application of Risk Management to Medical Devices, section 2.16 – definition of risk. ANSI/AAMI/ISO 14971: 2007/(R)2010: 의료기기 – 의료기기에 대한 위험관리 적용, 섹션 2.16 – 위험의 정의

[^5]: ANSI/AAMI ES60601-1:2005/(R)2012 and A1:2012, C1:2009/(R)2012 and A2:2010/(R)2012 (Consolidated Text) Medical electrical equipment— Part 1: General requirements for basic safety and essential performance (IEC 60601-1:2005, MOD), section 3.27 defines "Essential Performance" as performance of a clinical function, other than that related to basic safety, where loss or degradation beyond the limits specified by the manufacturer results in an unacceptable risk." ANSI/AAMI ES60601-1:2005/(R)2012 및 A1:2012, C1:2009/(R)2012 및 A2:2010/(R)2012 (통합 텍스트) 의료 전기 장비 - 파트 1: 기본 안전 및 필수 성능에 대한 일반 요구사항 (IEC 60601-1:2005, MOD), 섹션 3.27은 "필수 성능"을 기본 안전과 관련된 것 이외의 임상 기능 수행으로 정의하며, 제조업체가 지정한 한계를 초과한 손실 또는 저하가 수용할 수 없는 위험을 초래하는 경우를 말한다.

# I. 서론

식품의약국(FDA)은 시판 및 유통 중인 의료기기의 시판 후 사이버보안 취약점 관리에 대한 기관의 권고사항을 산업계와 FDA 직원에게 알리기 위해 본 지침을 발행한다. 본 지침에 포함된 구체적인 권고사항 외에도, 제조업체는 기기의 설계, 개발, 생산, 유통, 배치 및 유지보수를 포함한 제품 수명주기 전반에 걸쳐 사이버보안을 다루도록 권장된다.[^1] 점점 더 많은 의료기기가 환자 치료를 용이하게 하기 위해 네트워크로 연결되도록 설계되고 있다. 네트워크로 연결된 의료기기는 다른 네트워크 컴퓨터 시스템과 마찬가지로 사이버보안 위협에 취약할 수 있는 소프트웨어를 포함한다. 취약점의 악용은 건강에 대한 위험을 나타낼 수 있으며, 일반적으로 이러한 악용에 대한 적절한 수준의 보호를 보장하기 위해 제품 수명주기 전반에 걸친 지속적인 유지보수가 필요하다. 의료기기의 사이버보안 위험을 사전에 다루는 것은 건강에 대한 전반적인 위험을 감소시킨다.

본 지침은 FDA의 시판 후 권고사항을 명확히 하며, 제조업체가 의료기기의 시판 후 관리의 일환으로 사이버보안 취약점과 악용을 모니터링, 식별 및 해결해야 함을 강조한다. 본 지침은 사이버보안 취약점에 대한 의료기기 변경사항이 기관에 보고를 요구하는 시기를 평가하기 위한 위험 기반 프레임워크를 수립하고, FDA가 21 CFR part 806에 따른 보고 요건을 시행하지 않을 상황을 설명한다. 21 CFR part 806은 기기 제조업체 또는 수입업체가 기기 시정 및 회수와 관련된 특정 조치를 FDA에 즉시 보고하도록 요구한다. 그러나 "사이버보안 정기 업데이트 및 패치"라고 하는 사이버보안 취약점과 악용을 해결하기 위해 제조업체가 취하는 대부분의 조치는 일반적으로 FDA가 21 CFR part 806에 따라 사전 통지 또는 보고를 요구하지 않는 일종의 기기 개선[^2]으로 간주된다. 건강에 위험을 초래할 수 있는 기기 사이버보안 취약점과 악용을 시정하기 위해 제조업체가 취하는 일부 조치의 경우, FDA는 의료기기 제조업체가 기관에 통지할 것을 요구한다.[^3] 기기로 인한 건강 위험은 환자 위해를 초래할 수 있다. 본 지침은 환자 위해의 위험[^4]이 충분히 통제되었는지 또는 통제되지 않았는지를 평가하는 방법을 권고한다. 이 평가는 악용 가능성, 악용이 기기의 안전성 및 필수 성능에 미치는 영향,[^5] 그리고 악용 시 환자 위해의 심각도에 대한 평가를 기반으로 한다.

본 문서는 연방 식품, 의약품 및 화장품법(FD&C Act) 제519조 및 21 CFR part 803의 의료기기 보고(MDR) 규정에서 요구하는 바와 같이, 기기가 사망 또는 중상을 초래했거나 초래했을 수 있는 경우 FDA에 보고하는 것에 대한 지침을 제공하기 위한 것이 아니다. 의료기기 제조업체에 적용되는 현행 보고 및 기록 보관 요건에 대한 설명은 [의료기기 보고 제조업체 지침](http://www.fda.gov/MedicalDevices/DeviceRegulationandGuidance/GuidanceDocuments/UCM359566)을 참조하기 바란다.

본 문서에서 참조된 FDA 인정 표준의 현행판은 [FDA 인정 합의 표준 데이터베이스](http://www.accessdata.fda.gov/scripts/cdrh/cfdocs/cfStandards/search.cfm) 웹사이트를 참조하기 바란다.

본 최종 지침을 포함한 FDA의 지침 문서는 법적으로 강제할 수 있는 책임을 확립하지 않는다. 대신, 지침은 주제에 대한 기관의 현재 생각을 설명하며 특정 규제 또는 법적 요건이 인용되지 않는 한 권고사항으로만 간주되어야 한다. 기관 지침에서 "should"라는 단어의 사용은 무언가가 제안되거나 권장되지만 요구되지는 않음을 의미한다.

# II. Background

On February 19, 2013, the President issued Executive Order 13636 – Improving Critical Infrastructure Cybersecurity ([EO 13636](https://www.gpo.gov/fdsys/pkg/FR-2013-02-19/pdf/2013-03915.pdf)), which recognized that resilient infrastructure is essential to preserving national security, economic stability, and public health and safety in the United States. EO 13636 states that cyber threats to national security are among the most serious, and that stakeholders must enhance the cybersecurity and resilience of critical infrastructure. This includes the Healthcare and Public Health Critical Infrastructure Sector (HPH Sector). Furthermore, Presidential Policy Directive 21 – Critical Infrastructure Security and Resilience ([PPD-21](https://www.whitehouse.gov/the-press-office/2013/02/12/presidential-policy-directive-critical-infrastructure-security-and-resil)) issued on February 12, 2013 tasks Federal Government entities to strengthen the security and resilience of critical infrastructure against physical and cyber threats such that these efforts reduce vulnerabilities, minimize consequences, and identify and disrupt threats. PPD-21 encourages all public and private stakeholders to share responsibility in achieving these outcomes.

In recognition of the shared responsibility for cybersecurity, the security industry has established resources including standards, guidelines, best practices and frameworks for stakeholders to adopt a culture of cybersecurity risk management. Best practices include collaboratively assessing cybersecurity intelligence information for risks to device functionality and clinical risk. FDA believes that, in alignment with EO 13636 and PPD-21, public and private stakeholders should collaborate to leverage available resources and tools to establish a common understanding that assesses risks for identified vulnerabilities in medical devices among the information technology community, healthcare delivery organizations (HDOs), the clinical user community, and the medical device community. These collaborations can lead to the consistent assessment and mitigation of cybersecurity threats and vulnerabilities, and their impact on medical devices, ultimately reducing potential risk of patient harm.

Cybersecurity risk management is a shared responsibility among stakeholders including the medical device manufacturer, the user, the Information Technology (IT) system integrator, Health IT developers, and an array of IT vendors that provide products that are not regulated by the FDA. FDA seeks to encourage collaboration among stakeholders by clarifying, for those stakeholders it regulates, recommendations associated with mitigating cybersecurity threats to device functionality and device users.

As stated in the FDA guidance document titled "[Content of Premarket Submissions for Management of Cybersecurity in Medical Devices](http://www.fda.gov/MedicalDevices/DeviceRegulationandGuidance/GuidanceDocuments/UCM356190)," when manufacturers consider cybersecurity during the design phases of the medical device lifecycle, the resulting impact is a more proactive and robust mitigation of cybersecurity risks. Similarly, a proactive and risk-based approach to the postmarket phase for medical devices, through engaging in cybersecurity information sharing and monitoring, promoting "good cyber hygiene" through routine device cyber maintenance, assessing postmarket information, employing a risk-based approach to characterizing vulnerabilities, and timely implementation of necessary actions can further mitigate emerging cybersecurity risks and reduce the impact to patients.

To further aid manufacturers in managing their cybersecurity risk, the Agency encourages the use and adoption of the voluntary "Framework for Improving Critical Infrastructure Cybersecurity" that has been developed by the National Institute of Standards and Technology (NIST) with collective input from other government agencies and the private sector.

Critical to the adoption of a proactive, rather than reactive, postmarket cybersecurity approach is the sharing of cyber risk information and intelligence within the medical device community. This information sharing can enhance management of individual cybersecurity vulnerabilities and provide advance cyber threat information to additional relevant stakeholders to manage and enhance cybersecurity in the medical device community and HPH Sector.

Executive Order 13691 – Promoting Private Sector Cybersecurity Information Sharing ([EO 13691](https://www.whitehouse.gov/the-press-office/2015/02/13/executive-order-promoting-private-sector-cybersecurity-information-shari)), released on February 13, 2015, encourages the development of Information Sharing Analysis Organizations (ISAOs), to serve as focal points for cybersecurity information sharing and collaboration within the private sector as well as between the private sector and government. EO 13691 also mandates that the ISAO "…protects the privacy and civil liberties of individuals, that preserves business confidentiality, and that safeguards the information being shared…." ISAOs gather and analyze critical infrastructure information in order to better understand cybersecurity problems and interdependencies, communicate or disclose critical infrastructure information to help prevent, detect, mitigate, or recover from the effects of cyber threats, or voluntarily disseminate critical infrastructure information to its members or others involved in the detection and response to cybersecurity issues.[^6]

The [ISAOs](https://www.dhs.gov/isao) are intended to be: Inclusive (groups from any and all sectors, both non-profit and for-profit, expert or novice, should be able to participate in an ISAO); Actionable (groups will receive useful and practical cybersecurity risk, threat indicator, and incident information via automated, real-time mechanisms if they choose to participate in an ISAO); Transparent (groups interested in an ISAO model will have adequate understanding of how that model operates and if it meets their needs); and Trusted (participants in an ISAO can request that their information be treated as [Protected Critical Infrastructure Information](https://www.dhs.gov/pcii-program). Such information is shielded from any release otherwise required by the Freedom of Information Act or State Sunshine Laws and is exempt from regulatory use and civil litigation if the information satisfies the requirements of the Critical Infrastructure Information Act of 2002 (6 U.S.C. §§ 131 et seq.)).

The FDA Center for Devices and Radiological Health has entered into a Memorandum of Understanding with one such ISAO, the National Health Information Sharing & Analysis Center, (NH-ISAC)[^7] in order to assist in the creation of an environment that fosters stakeholder collaboration and communication, and encourages the sharing of information about cybersecurity threats and vulnerabilities that may affect the safety, effectiveness, integrity, and security of the medical devices and the surrounding Health IT infrastructure.

The Agency wishes to promote collaboration among the medical device and Health IT community to develop a shared understanding of the risks posed by cybersecurity vulnerabilities to medical devices and foster the development of a shared understanding of risk assessment to enable stakeholders to consistently and efficiently assess patient safety and public health risks associated with identified cybersecurity vulnerabilities and take timely, appropriate action to mitigate the risks. This approach will also enable stakeholders to provide timely situational awareness to the HPH community and take efforts to preemptively address the cybersecurity vulnerability through appropriate mitigation and/or remediation before it impacts the safety, effectiveness, integrity or security of medical devices and the Health IT infrastructure.

The Agency considers voluntary participation in an ISAO a critical component of a medical device manufacturer's comprehensive proactive approach to management of postmarket cybersecurity threats and vulnerabilities and a significant step towards assuring the ongoing safety and effectiveness of marketed medical devices. For companies that actively participate in such a program, and follow other recommendations in this guidance, the Agency does not intend to enforce certain reporting requirements of the Federal Food, Drug, and Cosmetic Act (FD&C Act) (see Section VII).

More information about active participation in an ISAO can be found in Section IX.

[^6]: See Homeland Security Act (https://www.dhs.gov/xlibrary/assets/hr_5005_enr.pdf), 6 U.S.C. § 212 (2002). 국토안보법(https://www.dhs.gov/xlibrary/assets/hr_5005_enr.pdf), 6 U.S.C. § 212 (2002) 참조

[^7]: See Memorandum of Understanding between the National Health Information Sharing & Analysis Center, Inc. (NH-ISAC), The Medical Device Innovation, Safety and Security Consortium (MDISS), and the U.S. Food and Drug Administration Center for Devices and Radiological Health (http://www.fda.gov/AboutFDA/PartnershipsCollaborations/MemorandaofUnderstandingMOUs/DomesticMOUs/ucm524376.htm). 국가 보건 정보공유분석센터(NH-ISAC), 의료기기 혁신, 안전 및 보안 컨소시엄(MDISS), 그리고 미국 식품의약국 의료기기 및 방사선보건센터 간의 양해각서(http://www.fda.gov/AboutFDA/PartnershipsCollaborations/MemorandaofUnderstandingMOUs/DomesticMOUs/ucm524376.htm) 참조

# II. 배경

2013년 2월 19일, 대통령은 행정명령 13636 - 중요 기반시설 사이버보안 개선([EO 13636](https://www.gpo.gov/fdsys/pkg/FR-2013-02-19/pdf/2013-03915.pdf))을 발표하였으며, 이는 탄력적인 기반시설이 미국의 국가 안보, 경제 안정성, 공중 보건 및 안전을 보존하는 데 필수적임을 인정하였다. EO 13636은 국가 안보에 대한 사이버 위협이 가장 심각한 것 중 하나이며, 이해관계자들이 중요 기반시설의 사이버보안과 탄력성을 강화해야 한다고 명시하고 있다. 이는 의료 및 공중보건 중요 기반시설 부문(HPH Sector)을 포함한다. 또한, 2013년 2월 12일 발표된 대통령 정책 지침 21 - 중요 기반시설 보안 및 탄력성([PPD-21](https://www.whitehouse.gov/the-press-office/2013/02/12/presidential-policy-directive-critical-infrastructure-security-and-resil))은 연방 정부 기관들에게 물리적 및 사이버 위협에 대한 중요 기반시설의 보안과 탄력성을 강화하여 이러한 노력이 취약점을 감소시키고, 결과를 최소화하며, 위협을 식별하고 차단하도록 과업을 부여한다. PPD-21은 모든 공공 및 민간 이해관계자들이 이러한 결과 달성에 대한 책임을 공유하도록 장려한다.

사이버보안에 대한 공동 책임을 인정하여, 보안 산업은 이해관계자들이 사이버보안 위험 관리 문화를 채택할 수 있도록 표준, 지침, 모범 사례 및 프레임워크를 포함한 자원을 구축하였다. 모범 사례에는 기기 기능 및 임상 위험에 대한 사이버보안 정보를 협력적으로 평가하는 것이 포함된다. FDA는 EO 13636 및 PPD-21에 부합하여, 공공 및 민간 이해관계자들이 협력하여 이용 가능한 자원과 도구를 활용함으로써 정보기술 커뮤니티, 의료제공기관(HDO), 임상 사용자 커뮤니티 및 의료기기 커뮤니티 간에 의료기기의 식별된 취약점에 대한 위험을 평가하는 공통된 이해를 구축해야 한다고 믿는다. 이러한 협력은 사이버보안 위협과 취약점, 그리고 의료기기에 대한 그 영향에 대한 일관된 평가 및 완화로 이어질 수 있으며, 궁극적으로 환자 위해의 잠재적 위험을 감소시킨다.

사이버보안 위험 관리는 의료기기 제조업체, 사용자, 정보기술(IT) 시스템 통합업체, 보건 IT 개발자, 그리고 FDA가 규제하지 않는 제품을 제공하는 다양한 IT 공급업체를 포함한 이해관계자들 간의 공동 책임이다. FDA는 규제 대상 이해관계자들에게 기기 기능 및 기기 사용자에 대한 사이버보안 위협 완화와 관련된 권고사항을 명확히 함으로써 이해관계자 간 협력을 장려하고자 한다.

"[의료기기의 사이버보안 관리를 위한 시판 전 제출 내용](http://www.fda.gov/MedicalDevices/DeviceRegulationandGuidance/GuidanceDocuments/UCM356190)"이라는 제목의 FDA 지침 문서에 명시된 바와 같이, 제조업체가 의료기기 수명주기의 설계 단계에서 사이버보안을 고려할 때, 그 결과는 사이버보안 위험에 대한 보다 사전예방적이고 강력한 완화가 된다. 마찬가지로, 사이버보안 정보 공유 및 모니터링에 참여하고, 정기적인 기기 사이버 유지보수를 통해 "좋은 사이버 위생"을 촉진하며, 시판 후 정보를 평가하고, 취약점 특성화에 위험 기반 접근법을 사용하며, 필요한 조치를 적시에 이행함으로써 의료기기의 시판 후 단계에 대한 사전예방적이고 위험 기반의 접근법은 신흥 사이버보안 위험을 더욱 완화하고 환자에 대한 영향을 감소시킬 수 있다.

제조업체의 사이버보안 위험 관리를 더욱 지원하기 위해, 기관은 다른 정부 기관 및 민간 부문의 공동 의견을 통해 국립표준기술연구소(NIST)가 개발한 자발적 "[중요 기반시설 사이버보안 개선을 위한 프레임워크](https://www.nist.gov/sites/default/files/documents/cyberframework/cybersecurity-framework-021214.pdf)"의 사용 및 채택을 권장한다.

사후 대응적이 아닌 사전예방적 시판 후 사이버보안 접근법의 채택에 중요한 것은 의료기기 커뮤니티 내에서 사이버 위험 정보 및 인텔리전스를 공유하는 것이다. 이러한 정보 공유는 개별 사이버보안 취약점의 관리를 향상시키고 추가적인 관련 이해관계자들에게 사전 사이버 위협 정보를 제공하여 의료기기 커뮤니티 및 HPH 부문의 사이버보안을 관리하고 강화할 수 있다.

2015년 2월 13일 발표된 행정명령 13691 - 민간 부문 사이버보안 정보 공유 촉진([EO 13691](https://www.whitehouse.gov/the-press-office/2015/02/13/executive-order-promoting-private-sector-cybersecurity-information-shari))은 민간 부문 내에서 그리고 민간 부문과 정부 간의 사이버보안 정보 공유 및 협력의 중심점 역할을 하는 정보공유분석기구(ISAO)의 개발을 장려한다. EO 13691은 또한 ISAO가 "개인의 프라이버시와 시민적 자유를 보호하고, 사업 기밀성을 보존하며, 공유되는 정보를 보호해야 한다"고 규정한다. ISAO는 사이버보안 문제 및 상호의존성을 더 잘 이해하기 위해 중요 기반시설 정보를 수집하고 분석하며, 사이버 위협의 영향을 예방, 탐지, 완화 또는 복구하는 데 도움이 되도록 중요 기반시설 정보를 전달 또는 공개하거나, 사이버보안 문제의 탐지 및 대응에 관여하는 회원 또는 기타 사람들에게 중요 기반시설 정보를 자발적으로 배포한다.[^6]

[ISAO](https://www.dhs.gov/isao)는 다음과 같이 되도록 의도된다: 포괄적(비영리 및 영리, 전문가 또는 초보자를 포함한 모든 부문의 그룹이 ISAO에 참여할 수 있어야 함); 실행 가능(그룹은 ISAO에 참여하기로 선택하면 자동화된 실시간 메커니즘을 통해 유용하고 실용적인 사이버보안 위험, 위협 지표 및 사고 정보를 받게 됨); 투명(ISAO 모델에 관심 있는 그룹은 해당 모델이 어떻게 작동하는지 그리고 그것이 그들의 필요를 충족하는지 적절히 이해할 것임); 그리고 신뢰(ISAO 참가자는 자신의 정보가 [보호 중요 기반시설 정보](https://www.dhs.gov/pcii-program)로 취급되도록 요청할 수 있음. 그러한 정보는 정보자유법 또는 주 공개법에 의해 달리 요구되는 공개로부터 보호되며, 정보가 2002년 중요 기반시설 정보법(6 U.S.C. §§ 131 et seq.)의 요건을 충족하는 경우 규제 사용 및 민사 소송에서 면제됨).

FDA 의료기기 및 방사선보건센터는 이러한 ISAO 중 하나인 국가 보건 정보공유분석센터(NH-ISAC)[^7]와 양해각서를 체결하여 이해관계자 협력 및 커뮤니케이션을 촉진하고, 의료기기 및 주변 보건 IT 기반시설의 안전성, 유효성, 완전성 및 보안에 영향을 미칠 수 있는 사이버보안 위협 및 취약점에 대한 정보 공유를 장려하는 환경 조성을 지원한다.

기관은 의료기기 및 보건 IT 커뮤니티 간의 협력을 촉진하여 의료기기에 대한 사이버보안 취약점이 제기하는 위험에 대한 공통된 이해를 개발하고, 이해관계자들이 식별된 사이버보안 취약점과 관련된 환자 안전 및 공중 보건 위험을 일관되고 효율적으로 평가하고 위험을 완화하기 위한 적시의 적절한 조치를 취할 수 있도록 위험 평가에 대한 공통된 이해의 개발을 촉진하고자 한다. 이 접근법은 또한 이해관계자들이 HPH 커뮤니티에 적시 상황 인식을 제공하고, 의료기기 및 보건 IT 기반시설의 안전성, 유효성, 완전성 또는 보안에 영향을 미치기 전에 적절한 완화 및/또는 시정을 통해 사이버보안 취약점을 사전에 해결하기 위한 노력을 취하도록 할 것이다.

기관은 ISAO에 대한 자발적 참여를 시판 후 사이버보안 위협 및 취약점 관리에 대한 의료기기 제조업체의 포괄적 사전예방적 접근법의 중요한 구성요소이며 시판된 의료기기의 지속적인 안전성 및 유효성을 보장하기 위한 중요한 단계로 간주한다. 이러한 프로그램에 적극적으로 참여하고 본 지침의 다른 권고사항을 따르는 회사의 경우, 기관은 연방 식품, 의약품 및 화장품법(FD&C Act)의 특정 보고 요건을 시행하지 않을 것이다(섹션 VII 참조).

ISAO에 대한 적극적 참여에 대한 추가 정보는 섹션 IX에서 찾을 수 있다.

# III. Scope

This guidance applies to any marketed and distributed medical device including: 1) medical devices that contain software (including firmware) or programmable logic; and 2) software that is a medical device,[^8] including mobile medical applications.[^9] In addition, this guidance applies to medical devices that are considered part of an interoperable[^10] system and to "legacy devices," i.e., devices that are already on the market or in use.

This guidance supplements the information addressed in the FDA guidance document titled ["Cybersecurity for Networked Medical Devices Containing Off-the-Shelf (OTS) Software"](http://www.fda.gov/MedicalDevices/DeviceRegulationandGuidance/GuidanceDocuments/ucm077812.htm).

This guidance does not apply to investigational devices.[^11]

[^8]: Under section 201(h) of the FD&C Act, device is defined as "an instrument, apparatus, implement, machine, contrivance, implant, in vitro reagent, or other similar related article, including a component part or accessory which is . . . intended for use in the diagnosis of disease or other conditions, or in the cure, mitigation, treatment, or prevention of disease, in man or other animals, or intended to affect the structure or any function of the body of man or other animals, and which does not achieve any of its primary intended purposes through chemical action within or on the body of man or other animals." In addition, please note that the International Medical Device Regulators Forum (IMDRF) Software as a Medical Device (SaMD) December 9, 2013, section 5.1 defines "Software as a Medical Device" as software intended to be used for one or more medical purposes that perform these purposes without being part of a hardware medical device (http://www.imdrf.org/docs/imdrf/final/technical/imdrf-tech-131209-samd-key-definitions-140901.pdf).

[^9]: See FDA Guidance: ["Mobile Medical Applications"](http://www.fda.gov/downloads/MedicalDevices/.../UCM263366.pdf). FDA 지침: ["모바일 의료 애플리케이션"](http://www.fda.gov/downloads/MedicalDevices/.../UCM263366.pdf) 참조.

[^10]: See FDA Guidance ["Design Considerations and Pre-market Submission Recommendations for Interoperable Medical Devices"](http://www.fda.gov/downloads/MedicalDevices/DeviceRegulationandGuidance/GuidanceDocuments/UCM482649). FDA 지침 ["상호운용 가능한 의료기기에 대한 설계 고려사항 및 시판 전 제출 권고사항"](http://www.fda.gov/downloads/MedicalDevices/DeviceRegulationandGuidance/GuidanceDocuments/UCM482649) 참조.

[^11]: Manufacturers may also consider applying the cybersecurity principles described in this guidance as appropriate to Investigational Device Exemption submissions and to devices exempt from premarket review. 제조업체는 또한 본 지침에 설명된 사이버보안 원칙을 임상시험용 기기 면제 제출 및 시판 전 검토가 면제된 기기에 적절하게 적용하는 것을 고려할 수 있다.

# III. 적용범위

본 지침은 다음을 포함하여 시판 및 유통되는 모든 의료기기에 적용된다: 1) 소프트웨어(펌웨어 포함) 또는 프로그래머블 로직을 포함하는 의료기기; 그리고 2) 모바일 의료 애플리케이션을 포함하여 의료기기인 소프트웨어.[^8],[^9] 또한, 본 지침은 상호운용 가능한[^10] 시스템의 일부로 간주되는 의료기기 및 "레거시 기기", 즉 이미 시장에 출시되었거나 사용 중인 기기에 적용된다.

본 지침은 ["상용 소프트웨어(OTS)를 포함하는 네트워크 의료기기의 사이버보안"](http://www.fda.gov/MedicalDevices/DeviceRegulationandGuidance/GuidanceDocuments/ucm077812.htm)이라는 제목의 FDA 지침 문서에서 다루는 정보를 보완한다.

본 지침은 임상시험용 기기에는 적용되지 않는다.[^11]

[^8]: Under section 201(h) of the FD&C Act, device is defined as "an instrument, apparatus, implement, machine, contrivance, implant, in vitro reagent, or other similar related article, including a component part or accessory which is . . . intended for use in the diagnosis of disease or other conditions, or in the cure, mitigation, treatment, or prevention of disease, in man or other animals, or intended to affect the structure or any function of the body of man or other animals, and which does not achieve any of its primary intended purposes through chemical action within or on the body of man or other animals." In addition, please note that the International Medical Device Regulators Forum (IMDRF) Software as a Medical Device (SaMD) December 9, 2013, section 5.1 defines "Software as a Medical Device" as software intended to be used for one or more medical purposes that perform these purposes without being part of a hardware medical device (http://www.imdrf.org/docs/imdrf/final/technical/imdrf-tech-131209-samd-key-definitions-140901.pdf). FD&C Act 제201(h)조에 따르면, 기기는 "사람 또는 다른 동물의 질병 또는 기타 상태의 진단, 또는 사람 또는 다른 동물의 질병의 치료, 완화, 치료 또는 예방에 사용하거나, 사람 또는 다른 동물의 신체 구조 또는 기능에 영향을 미치도록 의도되고, 사람 또는 다른 동물의 신체 내부 또는 표면에서의 화학적 작용을 통해 주된 의도된 목적을 달성하지 않는 구성 부품 또는 부속품을 포함한 기구, 장치, 도구, 기계, 장치물, 이식물, 시험관 시약 또는 기타 유사한 관련 물품"으로 정의된다. 또한, 국제의료기기규제당국포럼(IMDRF) 의료기기로서의 소프트웨어(SaMD) 2013년 12월 9일, 섹션 5.1은 "의료기기로서의 소프트웨어"를 하드웨어 의료기기의 일부가 되지 않고 이러한 목적을 수행하는 하나 이상의 의료 목적으로 사용되도록 의도된 소프트웨어로 정의한다(http://www.imdrf.org/docs/imdrf/final/technical/imdrf-tech-131209-samd-key-definitions-140901.pdf).

# IV. Definitions
For the purposes of this guidance, the following definitions are used:

## A. Compensating Controls
A cybersecurity compensating control is a safeguard or countermeasure deployed, in lieu of, or in the absence of controls designed in by a device manufacturer. These controls are external to the device design, configurable in the field, employed by a user, and provide supplementary or comparable cyber protection for a medical device.[^12] For example, a manufacturer's assessment of a cybersecurity vulnerability determines that unauthorized access to a networked medical device will most likely impact the device's safety or essential performance. However, the manufacturer determines that the device can safely and effectively operate without access to the host network, in this case the hospital network. The manufacturer instructs users to configure the network to remove the ability of unauthorized/unintended access to the device from the hospital network. This type of counter measure is an example of a compensating control.

## B. Controlled Risk
Controlled risk is present when there is sufficiently low (acceptable) residual risk of patient harm due to a device's particular cybersecurity vulnerability.

## C. Cybersecurity Routine Updates and Patches
Cybersecurity "routine updates and patches" are changes to a device to increase device security and/or remediate only those vulnerabilities associated with controlled risk of patient harm. These types of changes are not to reduce uncontrolled risk of patient harm, and therefore not to reduce a risk to health or to correct a violation of the FD&C Act. They include any regularly scheduled security updates or patches to a device, including upgrades to the software, firmware, programmable logic, hardware, or security of a device to increase device security, as well as updates or patches to address vulnerabilities associated with controlled risk performed earlier than their regularly scheduled deployment cycle even if they are distributed to multiple units. Cybersecurity routine updates and patches are generally considered to be a type of device enhancement that may be applied to vulnerabilities associated with controlled risk and is not considered a repair. Cybersecurity routine updates and patches may also include changes to product labeling, including the instructions for use, to strengthen cybersecurity through increased end-user education and use of best practices. Because "cybersecurity routine updates and patches are generally considered to be device enhancements, manufacturers are generally not required to report these updates and patches as corrections under 21 CFR part 806. See Section VII for more details on reporting requirements for vulnerabilities with controlled risk. Security updates made to remediate vulnerabilities associated with a reasonable probability that use of, or exposure to, the product will cause serious adverse health consequences or death are not considered to be cybersecurity routine updates or patches.

## D. Cybersecurity Signal
A cybersecurity signal is any information which indicates the potential for, or confirmation of, a cybersecurity vulnerability or exploit that affects, or could affect a medical device. A cybersecurity signal could originate from traditional information sources such as internal investigations, postmarket surveillance, or complaints, and/or security-centric sources such as CERTS (Computer/Cyber, Emergency Response/Readiness Teams), such as [ICS-CERT](https://ics-cert.us-cert.gov/),[^13] ISAOs,[^14] threat indicators, and security researchers. Signals may be identified within the HPH Sector. They may also originate in another critical infrastructure sector (e.g., defense, financial) but have the potential to impact medical device cybersecurity.

## E. Exploit
An exploit is an instance where a vulnerability or vulnerabilities have been exercised (accidently or intentionally) by a threat and could impact the safety or essential performance of a medical device or use a medical device as a vector to compromise a connected device or system.

## F. Patient Harm
Harm[^15] is the physical injury or damage to the health of people, or damage to property or the environment. Patient harm is defined as physical injury or damage to the health of patients, including death. Risks to health posed by the device may result in patient harm. This guidance outlines the assessment of whether the risk[^16] of patient harm is sufficiently controlled or uncontrolled. This assessment is based on an evaluation of the likelihood of exploit, the impact of exploitation on the device's safety and essential performance, and the severity of patient harm if exploited (see section VI).

Other harms, such as loss of confidential information, including compromise of protected health information (PHI), are not considered "patient harms" for the purposes of this guidance. Nevertheless, the FDA recommends that manufacturers consider protecting the confidentiality of such information as part of their overall comprehensive risk management program. Although protecting the confidentiality of PHI is beyond the scope of this document, it should be noted that manufacturers and/or other entities, depending on the facts and circumstances, may be obligated to protect the confidentiality, integrity and availability of PHI throughout the product life cycle, including disposal, in accordance with applicable federal and state laws, including the Health Information Portability and Accountability Act (HIPAA).[^17] Changes to a device that are made solely to address loss of confidentiality are typically considered to be device enhancements.

## G. Remediation
Remediation is any action(s) taken to reduce an uncontrolled risk of patient harm posed by a device cybersecurity vulnerability to an acceptable level. Remediation actions may include complete solutions to remove a cybersecurity vulnerability from a medical device or compensating controls that adequately mitigate the risk (e.g., notification to customers and the user community identifying a control the user can implement). An example of remediation is a notification to the customers and the user community that discloses the vulnerability, the impact to the device, the potential for patient harm, and provides a strategy to reduce the risk of patient harm to an acceptable and controlled level. If the customer notification does not provide a strategy to reduce the risk of patient harm to an acceptable and controlled level, then the remediation is considered incomplete.

## H. Threat
Threat is any circumstance or event with the potential to adversely impact the device, organizational operations (including mission, functions, image, or reputation), organizational assets, individuals, or other organizations through an information system via unauthorized access, destruction, disclosure, modification of information, and/or denial of service.[^18] Threats exercise vulnerabilities, which may impact the safety or essential performance of the device.

## I. Threat Modeling
Threat modeling is a methodology for optimizing Network/Application/Internet Security by identifying objectives and vulnerabilities, and then defining countermeasures to prevent, or mitigate the effects of, threats to the system.[^19] For medical devices, threat modeling can be used to strengthen security by identifying vulnerabilities and threats to a particular product, products in a product line, or from the organization's supply chain that can cause patient harm.

## J. Uncontrolled Risk
Uncontrolled risk is present when there is unacceptable residual risk of patient harm due to inadequate compensating controls and risk mitigations.

## K. Vulnerability
A vulnerability is a weakness in an information system, system security procedures, internal controls, human behavior, or implementation that could be exploited by a threat.

[^12]: This definition is adapted from NIST Special Publication "Assessing Security and Privacy Controls in Federal Information Systems and Organizations," NIST SP 800-53A Rev. 4. 이 정의는 NIST 특별 간행물 "연방 정보 시스템 및 조직의 보안 및 프라이버시 통제 평가", NIST SP 800-53A Rev. 4에서 각색되었다.

[^13]: ICS-CERT - Industrial Control Systems Cyber Emergency Response Team ICS-CERT - 산업제어시스템 사이버 긴급대응팀

[^14]: See Department of Homeland Security, "Frequently Asked Questions about Information Sharing and Analysis Organizations (ISAOs)." 국토안보부, "정보공유분석기구(ISAO)에 대한 자주 묻는 질문" 참조.

[^15]: ANSI/AAMI/ISO 14971: 2007/(R)2010: Medical Devices – Application of Risk Management to Medical Devices, section 2.2 – definition of harm. ANSI/AAMI/ISO 14971: 2007/(R)2010: 의료기기 – 의료기기에 대한 위험관리 적용, 섹션 2.2 – 위해의 정의.

[^16]: ANSI/AAMI/ISO 14971: 2007/(R)2010: Medical Devices – Application of Risk Management to Medical Devices, section 2.16 – definition of risk. ANSI/AAMI/ISO 14971: 2007/(R)2010: 의료기기 – 의료기기에 대한 위험관리 적용, 섹션 2.16 – 위험의 정의.

[^17]: The HHS Office for Civil Rights enforces the Health Insurance Portability and Accountability Act (HIPAA) Privacy Rule, which protects the privacy of individually identifiable health information that covered entities or their business associates create, receive, maintain, or transmit; the HIPAA Security Rule, which sets national standards for the security of electronic protected health information; the HIPAA Breach Notification Rule, which requires covered entities and business associates to provide notification following a breach of unsecured protected health information; and the confidentiality provisions of the Patient Safety Rule, which protect identifiable information being used to analyze patient safety events and improve patient safety. See Health information Privacy at: http://www.hhs.gov/ocr/privacy/index.html. HHS 시민권 사무국은 대상 기관 또는 비즈니스 제휴사가 생성, 수신, 유지 또는 전송하는 개별 식별 가능한 건강 정보의 프라이버시를 보호하는 건강보험 이동 및 책임에 관한 법(HIPAA) 프라이버시 규칙; 전자 보호 건강 정보의 보안에 대한 국가 표준을 설정하는 HIPAA 보안 규칙; 보안되지 않은 보호 건강 정보의 침해 후 대상 기관 및 비즈니스 제휴사가 통지를 제공하도록 요구하는 HIPAA 침해 통지 규칙; 그리고 환자 안전 사건을 분석하고 환자 안전을 개선하는 데 사용되는 식별 가능한 정보를 보호하는 환자 안전 규칙의 기밀 유지 조항을 시행한다. 건강 정보 프라이버시 참조: http://www.hhs.gov/ocr/privacy/index.html.

[^18]: NIST SP 800-53; SP 800-53A; SP 800-27; SP 800-60; SP 800-37; CNSSI-4009. Note: Adapted from NIST definition (SP 800-53). NIST SP 800-53; SP 800-53A; SP 800-27; SP 800-60; SP 800-37; CNSSI-4009. 참고: NIST 정의(SP 800-53)에서 각색됨.

[^19]: See "Threat Modeling" as defined in the [Open Web Application Security Project (OWASP)](https://www.owasp.org/index.php/Category:Threat_Modeling). [공개 웹 애플리케이션 보안 프로젝트(OWASP)](https://www.owasp.org/index.php/Category:Threat_Modeling)에 정의된 "위협 모델링" 참조.

# IV. 정의
본 지침의 목적상, 다음 정의가 사용된다:

## A. 보상 통제
사이버보안 보상 통제는 기기 제조업체가 설계한 통제를 대신하거나 부재 시 배치되는 안전장치 또는 대응책이다. 이러한 통제는 기기 설계의 외부에 있으며, 현장에서 구성 가능하고, 사용자가 사용하며, 의료기기에 대한 보완적이거나 유사한 사이버 보호를 제공한다.[^12] 예를 들어, 사이버보안 취약점에 대한 제조업체의 평가 결과 네트워크 의료기기에 대한 무단 접근이 기기의 안전성 또는 필수 성능에 영향을 미칠 가능성이 가장 높다고 판단된다. 그러나 제조업체는 기기가 호스트 네트워크, 이 경우 병원 네트워크에 접근하지 않고도 안전하고 효과적으로 작동할 수 있다고 판단한다. 제조업체는 사용자에게 병원 네트워크로부터 기기에 대한 무단/의도하지 않은 접근 능력을 제거하도록 네트워크를 구성하도록 지시한다. 이러한 유형의 대응책은 보상 통제의 예이다.

## B. 통제된 위험
통제된 위험은 기기의 특정 사이버보안 취약점으로 인한 환자 위해의 잔여 위험이 충분히 낮은(수용 가능한) 경우에 존재한다.

## C. 사이버보안 정기 업데이트 및 패치
사이버보안 "정기 업데이트 및 패치"는 기기 보안을 강화하고/하거나 환자 위해의 통제된 위험과 관련된 취약점만을 시정하기 위한 기기 변경이다. 이러한 유형의 변경은 환자 위해의 통제되지 않은 위험을 감소시키기 위한 것이 아니므로, 건강에 대한 위험을 감소시키거나 FD&C Act 위반을 시정하기 위한 것이 아니다. 여기에는 기기 보안을 강화하기 위한 기기의 소프트웨어, 펌웨어, 프로그래머블 로직, 하드웨어 또는 보안에 대한 업그레이드를 포함한 정기적으로 예정된 보안 업데이트 또는 패치, 그리고 여러 단위에 배포되더라도 정기적으로 예정된 배포 주기보다 빨리 수행되는 통제된 위험과 관련된 취약점을 해결하기 위한 업데이트 또는 패치가 포함된다. 사이버보안 정기 업데이트 및 패치는 일반적으로 통제된 위험과 관련된 취약점에 적용될 수 있는 일종의 기기 개선으로 간주되며 수리로 간주되지 않는다. 사이버보안 정기 업데이트 및 패치는 또한 최종 사용자 교육 증대 및 모범 사례 사용을 통해 사이버보안을 강화하기 위한 사용 지침을 포함한 제품 라벨 변경을 포함할 수 있다. 사이버보안 정기 업데이트 및 패치는 일반적으로 기기 개선으로 간주되기 때문에, 제조업체는 일반적으로 이러한 업데이트 및 패치를 21 CFR part 806에 따라 시정으로 보고할 필요가 없다. 통제된 위험이 있는 취약점에 대한 보고 요건에 대한 자세한 내용은 섹션 VII을 참조하기 바란다. 제품의 사용 또는 노출이 심각한 건강상의 부작용 또는 사망을 초래할 합리적인 가능성이 있는 취약점을 시정하기 위해 이루어진 보안 업데이트는 사이버보안 정기 업데이트 또는 패치로 간주되지 않는다.

## D. 사이버보안 신호
사이버보안 신호는 의료기기에 영향을 미치거나 영향을 미칠 수 있는 사이버보안 취약점 또는 악용의 잠재성 또는 확인을 나타내는 모든 정보이다. 사이버보안 신호는 내부 조사, 시판 후 감시 또는 불만과 같은 전통적인 정보원 및/또는 [ICS-CERT](https://ics-cert.us-cert.gov/),[^13] ISAO,[^14] 위협 지표 및 보안 연구원과 같은 CERT(컴퓨터/사이버, 긴급 대응/준비 팀)와 같은 보안 중심 출처에서 발생할 수 있다. 신호는 HPH 부문 내에서 식별될 수 있다. 또한 다른 중요 기반시설 부문(예: 국방, 금융)에서 발생할 수도 있지만 의료기기 사이버보안에 영향을 미칠 가능성이 있다.

## E. 악용
악용은 취약점이 위협에 의해 (우발적으로 또는 의도적으로) 행사되어 의료기기의 안전성 또는 필수 성능에 영향을 미치거나 연결된 기기 또는 시스템을 손상시키는 벡터로 의료기기를 사용할 수 있는 경우이다.

## F. 환자 위해
위해[^15]는 사람의 건강에 대한 신체적 상해 또는 손상, 또는 재산이나 환경에 대한 손상이다. 환자 위해는 사망을 포함한 환자의 건강에 대한 신체적 상해 또는 손상으로 정의된다. 기기로 인한 건강 위험은 환자 위해를 초래할 수 있다. 본 지침은 환자 위해의 위험[^16]이 충분히 통제되었는지 또는 통제되지 않았는지에 대한 평가를 설명한다. 이 평가는 악용 가능성, 악용이 기기의 안전성 및 필수 성능에 미치는 영향, 그리고 악용 시 환자 위해의 심각도에 대한 평가를 기반으로 한다(섹션 VI 참조).

보호 건강 정보(PHI)의 손상을 포함한 기밀 정보의 손실과 같은 기타 위해는 본 지침의 목적상 "환자 위해"로 간주되지 않는다. 그럼에도 불구하고, FDA는 제조업체가 전반적인 포괄적 위험 관리 프로그램의 일환으로 그러한 정보의 기밀성 보호를 고려할 것을 권장한다. PHI의 기밀성 보호는 본 문서의 범위를 벗어나지만, 사실과 상황에 따라 제조업체 및/또는 기타 기관은 건강정보 이동 및 책임에 관한 법(HIPAA)을 포함한 적용 가능한 연방 및 주 법률에 따라 폐기를 포함한 제품 수명주기 전반에 걸쳐 PHI의 기밀성, 무결성 및 가용성을 보호해야 할 의무가 있을 수 있음을 유의해야 한다.[^17] 기밀성 손실만을 해결하기 위해 이루어진 기기 변경은 일반적으로 기기 개선으로 간주된다.

## G. 시정
시정은 기기 사이버보안 취약점으로 인한 통제되지 않은 환자 위해의 위험을 수용 가능한 수준으로 감소시키기 위해 취하는 모든 조치이다. 시정 조치에는 의료기기에서 사이버보안 취약점을 제거하기 위한 완전한 솔루션 또는 위험을 적절히 완화하는 보상 통제(예: 고객 및 사용자 커뮤니티에 사용자가 구현할 수 있는 통제를 식별하는 통지)가 포함될 수 있다. 시정의 예는 취약점, 기기에 대한 영향, 환자 위해의 가능성을 공개하고 환자 위해의 위험을 수용 가능하고 통제된 수준으로 감소시키기 위한 전략을 제공하는 고객 및 사용자 커뮤니티에 대한 통지이다. 고객 통지가 환자 위해의 위험을 수용 가능하고 통제된 수준으로 감소시키기 위한 전략을 제공하지 않으면, 시정은 불완전한 것으로 간주된다.

## H. 위협
위협은 무단 접근, 파괴, 공개, 정보 변경 및/또는 서비스 거부를 통해 정보 시스템을 통해 기기, 조직 운영(임무, 기능, 이미지 또는 평판 포함), 조직 자산, 개인 또는 기타 조직에 부정적인 영향을 미칠 가능성이 있는 모든 상황 또는 사건이다.[^18] 위협은 취약점을 행사하며, 이는 기기의 안전성 또는 필수 성능에 영향을 미칠 수 있다.

## I. 위협 모델링
위협 모델링은 목표와 취약점을 식별한 다음 시스템에 대한 위협을 예방하거나 완화하기 위한 대응책을 정의함으로써 네트워크/애플리케이션/인터넷 보안을 최적화하기 위한 방법론이다.[^19] 의료기기의 경우, 위협 모델링은 환자 위해를 초래할 수 있는 특정 제품, 제품 라인의 제품 또는 조직의 공급망에 대한 취약점과 위협을 식별함으로써 보안을 강화하는 데 사용될 수 있다.

## J. 통제되지 않은 위험
통제되지 않은 위험은 부적절한 보상 통제 및 위험 완화로 인해 환자 위해의 수용할 수 없는 잔여 위험이 존재하는 경우에 존재한다.

## K. 취약점
취약점은 위협에 의해 악용될 수 있는 정보 시스템, 시스템 보안 절차, 내부 통제, 인간 행동 또는 구현의 약점이다.


# V. General Principles
FDA recognizes that medical device cybersecurity is a shared responsibility among stakeholders including health care facilities, patients, providers, and manufacturers of medical devices. Failure to maintain cybersecurity can result in compromised device functionality, loss of data (medical or personal) availability or integrity, or exposure of other connected devices or networks to security threats. This in turn may have the potential to result in patient illness, injury or death.

Effective cybersecurity risk management is intended to reduce the risk to patients by decreasing the likelihood that device functionality is intentionally or unintentionally compromised by inadequate cybersecurity. An effective cybersecurity risk management program should incorporate both premarket and postmarket lifecycle phases and address cybersecurity from medical device conception to obsolescence It is recommended that manufacturers apply the [NIST Framework for Improving Critical Infrastructure Cybersecurity](https://www.nist.gov/sites/default/files/documents/cyberframework/cybersecurity-framework-021214.pdf) (i.e., Identify, Protect, Detect, Respond and Recover) in the development and implementation of their comprehensive cybersecurity programs. Alignment of the NIST Framework for Improving Critical Infrastructure Cybersecurity five core functions to management of cybersecurity in medical devices is discussed in the Appendix in greater detail.

## A. Premarket Considerations
The FDA guidance document titled ["Content of Premarket Submissions for Management of Cybersecurity in Medical Devices"](http://www.fda.gov/downloads/MedicalDevices/DeviceRegulationandGuidance/GuidanceDocuments/UCM356190.pdf) clarifies recommendations for manufacturers to address cybersecurity during the design and development of the medical device, as this can result in more robust and efficient mitigation of patient risks. Manufacturers should establish design inputs for their device related to cybersecurity, and establish a cybersecurity vulnerability and management approach as part of the software validation and risk analysis that is required by 21 CFR 820.30(g). The approach should appropriately address the following elements:

- Identification of assets, threats, and vulnerabilities;
- Assessment of the impact of threats and vulnerabilities on device functionality and end users/patients;
- Assessment of the likelihood of a threat and of a vulnerability being exploited;
- Determination of risk levels and suitable mitigation strategies;
- Assessment of residual risk and risk acceptance criteria.

## B. Postmarket Considerations
Because cybersecurity risks to medical devices are continually evolving, it is not possible to completely mitigate risks through premarket controls alone. Therefore, it is essential that manufacturers implement comprehensive cybersecurity risk management programs and documentation consistent with the Quality System Regulation (21 CFR part 820), including but not limited to complaint handling (21 CFR 820.198), quality audit (21 CFR 820.22), corrective and preventive action (21 CFR 820.100), software validation and risk analysis (21 CFR 820.30(g)) and servicing (21 CFR 820.200).

Cybersecurity risk management programs should emphasize addressing vulnerabilities which may permit the unauthorized access, modification, misuse or denial of use, or the unauthorized use of information that is stored, accessed, or transferred from a medical device to an external recipient, and may result in patient harm. Manufacturers should respond in a timely fashion to address identified vulnerabilities. Critical components of such a program include:

- Monitoring cybersecurity information sources for identification and detection of cybersecurity vulnerabilities and risk;
- Maintaining robust software lifecycle processes that include mechanisms for:
  - monitoring third party software components for new vulnerabilities throughout the device's total product lifecycle;
  - design verification and validation for software updates and patches that are used to remediate vulnerabilities, including those related to Off-the-shelf software;
- Understanding, assessing and detecting presence and impact of a vulnerability;
- Establishing and communicating processes for vulnerability intake and handling
  - Note: The FDA has recognized ISO/IEC 30111:2013: Information Technology – Security Techniques – Vulnerability Handling Processes;
- Using threat modeling to clearly define how to maintain safety and essential performance of a device by developing mitigations that protect, respond and recover from the cybersecurity risk;
- Adopting a coordinated vulnerability disclosure policy and practice. The FDA has recognized ISO/IEC 29147:2014: Information Technology – Security Techniques – Vulnerability Disclosure which may be a useful resource for manufacturers; and
- Deploying mitigations that address cybersecurity risk early and prior to exploitation.

Postmarket cybersecurity information may originate from an array of sources including independent security researchers, in-house testing, suppliers of software or hardware technology, health care facilities, and information sharing and analysis organizations. It is strongly recommended that manufacturers participate in an ISAO that shares vulnerabilities and threats that impact medical devices. Sharing and dissemination of cybersecurity information and intelligence pertaining to vulnerabilities and threats across multiple sectors is integral to a successful postmarket cybersecurity surveillance program.

To manage postmarket cybersecurity risks for medical devices, a company should have a structured and systematic approach to risk management and quality management systems consistent with 21 CFR part 820. For example, such a program should include:

- Methods to identify, characterize, and assess a cybersecurity vulnerability.
- Methods to analyze, detect, and assess threat sources. For example:
  - A cybersecurity vulnerability might impact all of the medical devices in a manufacturer's portfolio based on how their products are developed; or
  - A cybersecurity vulnerability could exist vertically (i.e., within the components of a device) which can be introduced at any point in the supply chain for a medical device manufacturing process.

It is recommended as part of a manufacturer's cybersecurity risk management program that the manufacturer incorporate elements consistent with the [NIST Framework for Improving Critical Infrastructure Cybersecurity](https://www.nist.gov/sites/default/files/documents/cyberframework/cybersecurity-framework-021214.pdf) (i.e., Identify, Protect, Detect, Respond, and Recover).

FDA recognizes that medical devices and the surrounding network infrastructure cannot be completely secured. Design, architecture, technology, and software development environment choices may result in the inadvertent incorporation of vulnerabilities. The presence of a vulnerability does not necessarily trigger patient harm concerns. Rather it is the impact of the vulnerability on the safety and essential performance of the device which may present a risk of patient harm. Vulnerabilities that do not appear to currently present a risk of patient harm should be assessed by the manufacturer for future impact.

## C. Maintaining Safety and Essential Performance
Compromise of safety or essential performance of a device can result in patient harm and may require intervention to prevent patient harm.

Manufacturers should define, as part of the comprehensive cybersecurity risk management, the safety and essential performance of their device, the resulting severity of patient harm if compromised, and the risk acceptance criteria. These steps allow manufacturers to triage vulnerabilities for remediation (see Section VI for additional information on risk assessments).

Threat modeling is important in understanding and assessing the exploitability of a device vulnerability and potential for patient harm. Threat modeling can also be used in determining whether a proposed or implemented remediation can provide assurance that the risk of patient harm due to a cybersecurity vulnerability is reasonably controlled. Importantly, acceptable mitigations will vary depending upon the severity of patient harm that may result from exploitation of a vulnerability affecting the device. For example, a cybersecurity vulnerability affecting the temperature reading of a thermometer may have different risks than a cybersecurity vulnerability affecting the dosage of an insulin infusion pump because of the severity of patient harm.

# V. 일반 원칙

FDA는 의료기기 사이버보안이 의료 시설, 환자, 의료 제공자 및 의료기기 제조업체를 포함한 이해관계자들 간의 공동 책임임을 인정한다. 사이버보안을 유지하지 못하면 기기 기능이 손상되거나, 데이터(의료 또는 개인) 가용성 또는 무결성이 손실되거나, 연결된 다른 기기 또는 네트워크가 보안 위협에 노출될 수 있다. 이는 결과적으로 환자의 질병, 부상 또는 사망을 초래할 가능성이 있다.

효과적인 사이버보안 위험 관리는 부적절한 사이버보안으로 인해 기기 기능이 의도적으로 또는 의도하지 않게 손상될 가능성을 감소시킴으로써 환자에 대한 위험을 줄이기 위한 것이다. 효과적인 사이버보안 위험 관리 프로그램은 시판 전 및 시판 후 수명주기 단계를 모두 포함해야 하며 의료기기 개념부터 노후화까지 사이버보안을 다루어야 한다. 제조업체는 포괄적인 사이버보안 프로그램의 개발 및 구현에 있어 [중요 기반시설 사이버보안 개선을 위한 NIST 프레임워크](https://www.nist.gov/sites/default/files/documents/cyberframework/cybersecurity-framework-021214.pdf)(즉, 식별, 보호, 탐지, 대응 및 복구)를 적용할 것을 권장한다. 중요 기반시설 사이버보안 개선을 위한 NIST 프레임워크의 다섯 가지 핵심 기능과 의료기기 사이버보안 관리의 연계는 부록에서 더 자세히 논의된다.

## A. 시판 전 고려사항

["의료기기의 사이버보안 관리를 위한 시판 전 제출 내용"](http://www.fda.gov/downloads/MedicalDevices/DeviceRegulationandGuidance/GuidanceDocuments/UCM356190.pdf)이라는 제목의 FDA 지침 문서는 의료기기의 설계 및 개발 중에 사이버보안을 다루기 위한 제조업체의 권고사항을 명확히 하는데, 이는 환자 위험에 대한 보다 강력하고 효율적인 완화를 가져올 수 있기 때문이다. 제조업체는 사이버보안과 관련된 기기의 설계 입력을 수립해야 하며, 21 CFR 820.30(g)에서 요구하는 소프트웨어 검증 및 위험 분석의 일환으로 사이버보안 취약점 및 관리 접근법을 수립해야 한다. 이 접근법은 다음 요소들을 적절히 다루어야 한다:

- 자산, 위협 및 취약점의 식별;
- 위협 및 취약점이 기기 기능 및 최종 사용자/환자에 미치는 영향 평가;
- 위협 및 취약점이 악용될 가능성 평가;
- 위험 수준 및 적절한 완화 전략 결정;
- 잔여 위험 및 위험 수용 기준 평가.

## B. 시판 후 고려사항

의료기기에 대한 사이버보안 위험이 지속적으로 진화하고 있기 때문에, 시판 전 통제만으로 위험을 완전히 완화하는 것은 불가능하다. 따라서 제조업체는 불만 처리(21 CFR 820.198), 품질 감사(21 CFR 820.22), 시정 및 예방 조치(21 CFR 820.100), 소프트웨어 검증 및 위험 분석(21 CFR 820.30(g)) 및 서비스(21 CFR 820.200)를 포함하되 이에 국한되지 않는 품질 시스템 규정(21 CFR part 820)과 일치하는 포괄적인 사이버보안 위험 관리 프로그램 및 문서를 구현하는 것이 필수적이다.

사이버보안 위험 관리 프로그램은 의료기기에서 외부 수신자로 저장, 액세스 또는 전송되는 정보의 무단 액세스, 변경, 오용 또는 사용 거부, 또는 무단 사용을 허용할 수 있고 환자 위해를 초래할 수 있는 취약점을 해결하는 데 중점을 두어야 한다. 제조업체는 식별된 취약점을 해결하기 위해 적시에 대응해야 한다. 이러한 프로그램의 중요한 구성요소는 다음을 포함한다:

- 사이버보안 취약점 및 위험의 식별 및 탐지를 위한 사이버보안 정보원 모니터링;
- 다음을 위한 메커니즘을 포함하는 강력한 소프트웨어 수명주기 프로세스 유지:
  - 기기의 전체 제품 수명주기 동안 제3자 소프트웨어 구성요소의 새로운 취약점 모니터링;
  - 상용 소프트웨어와 관련된 것을 포함하여 취약점을 시정하는 데 사용되는 소프트웨어 업데이트 및 패치에 대한 설계 검증 및 검증;
- 취약점의 존재 및 영향 이해, 평가 및 탐지;
- 취약점 접수 및 처리 프로세스 수립 및 전달
  - 참고: FDA는 ISO/IEC 30111:2013: 정보기술 – 보안 기술 – 취약점 처리 프로세스를 인정하였다;
- 사이버보안 위험으로부터 보호, 대응 및 복구하는 완화책을 개발함으로써 기기의 안전성 및 필수 성능을 유지하는 방법을 명확히 정의하기 위한 위협 모델링 사용;
- 조정된 취약점 공개 정책 및 실무 채택. FDA는 제조업체에게 유용한 자원이 될 수 있는 ISO/IEC 29147:2014: 정보기술 – 보안 기술 – 취약점 공개를 인정하였다; 그리고
- 악용 이전에 조기에 사이버보안 위험을 해결하는 완화책 배포.

시판 후 사이버보안 정보는 독립 보안 연구원, 사내 테스트, 소프트웨어 또는 하드웨어 기술 공급업체, 의료 시설, 그리고 정보 공유 및 분석 조직을 포함한 다양한 출처에서 발생할 수 있다. 제조업체가 의료기기에 영향을 미치는 취약점과 위협을 공유하는 ISAO에 참여할 것을 강력히 권장한다. 여러 부문에 걸쳐 취약점 및 위협과 관련된 사이버보안 정보 및 인텔리전스의 공유 및 배포는 성공적인 시판 후 사이버보안 감시 프로그램에 필수적이다.

의료기기에 대한 시판 후 사이버보안 위험을 관리하기 위해, 회사는 21 CFR part 820과 일치하는 위험 관리 및 품질 관리 시스템에 대한 구조화되고 체계적인 접근법을 가져야 한다. 예를 들어, 이러한 프로그램은 다음을 포함해야 한다:

- 사이버보안 취약점을 식별, 특성화 및 평가하는 방법.
- 위협 출처를 분석, 탐지 및 평가하는 방법. 예를 들어:
  - 사이버보안 취약점은 제품 개발 방식에 따라 제조업체의 포트폴리오에 있는 모든 의료기기에 영향을 미칠 수 있다; 또는
  - 사이버보안 취약점은 의료기기 제조 프로세스의 공급망의 어느 시점에서든 도입될 수 있는 수직적으로(즉, 기기의 구성요소 내에서) 존재할 수 있다.

제조업체의 사이버보안 위험 관리 프로그램의 일환으로 제조업체가 [중요 기반시설 사이버보안 개선을 위한 NIST 프레임워크](https://www.nist.gov/sites/default/files/documents/cyberframework/cybersecurity-framework-021214.pdf)(즉, 식별, 보호, 탐지, 대응 및 복구)와 일치하는 요소를 통합할 것을 권장한다.

FDA는 의료기기와 주변 네트워크 기반시설이 완전히 보호될 수 없음을 인정한다. 설계, 아키텍처, 기술 및 소프트웨어 개발 환경 선택은 의도하지 않게 취약점을 포함시킬 수 있다. 취약점의 존재가 반드시 환자 위해 우려를 촉발하는 것은 아니다. 오히려 환자 위해의 위험을 제시할 수 있는 것은 기기의 안전성 및 필수 성능에 대한 취약점의 영향이다. 현재 환자 위해의 위험을 제시하지 않는 것으로 보이는 취약점은 제조업체가 향후 영향에 대해 평가해야 한다.

## C. 안전성 및 필수 성능 유지

기기의 안전성 또는 필수 성능의 손상은 환자 위해를 초래할 수 있으며 환자 위해를 예방하기 위한 개입이 필요할 수 있다.

제조업체는 포괄적인 사이버보안 위험 관리의 일환으로 기기의 안전성 및 필수 성능, 손상된 경우 결과적으로 발생하는 환자 위해의 심각도, 그리고 위험 수용 기준을 정의해야 한다. 이러한 단계는 제조업체가 시정을 위해 취약점을 분류할 수 있게 한다(위험 평가에 대한 추가 정보는 섹션 VI 참조).

위협 모델링은 기기 취약점의 악용 가능성과 환자 위해의 가능성을 이해하고 평가하는 데 중요하다. 위협 모델링은 또한 제안되거나 구현된 시정이 사이버보안 취약점으로 인한 환자 위해의 위험이 합리적으로 통제된다는 보장을 제공할 수 있는지를 결정하는 데 사용될 수 있다. 중요하게도, 수용 가능한 완화책은 기기에 영향을 미치는 취약점의 악용으로 인해 발생할 수 있는 환자 위해의 심각도에 따라 달라질 것이다. 예를 들어, 온도계의 온도 판독에 영향을 미치는 사이버보안 취약점은 환자 위해의 심각도로 인해 인슐린 주입 펌프의 투여량에 영향을 미치는 사이버보안 취약점과는 다른 위험을 가질 수 있다.

# VI. Medical Device Cybersecurity Risk Management
As part of their risk management process consistent with 21 CFR part 820, a manufacturer should establish, document, and maintain throughout the medical device lifecycle an ongoing process for identifying hazards associated with the cybersecurity of a medical device, estimating and evaluating the associated risks, controlling these risks, and monitoring the effectiveness of the controls. This process should include risk analysis, risk evaluation, risk control, and incorporation of production and post-production information. Elements identified in the Appendix of this guidance should be included as part of the manufacturer's cybersecurity risk management program to support an effective risk management process. Manufacturers should have a defined process to systematically conduct a risk evaluation and determine whether a cybersecurity vulnerability affecting a medical device presents an acceptable or unacceptable risk. It is not possible to describe all hazards, associated risks, and/or controls associated with medical device cybersecurity vulnerabilities in this guidance. It is also not possible to describe all scenarios where risk is controlled or uncontrolled. Rather, FDA recommends that manufacturers define and document their process for objectively assessing the cybersecurity risk for their device(s).

As outlined below, it is recommended that such a process focus on assessing the risk of patient harm by considering:

1) The exploitability of the cybersecurity vulnerability, and
2) The severity of patient harm if the vulnerability were to be exploited.

Such analysis should also incorporate consideration of compensating controls and risk mitigations.

## A. Assessing Exploitability of the Cybersecurity Vulnerability
Manufacturers should have a process for assessing the exploitability of a cybersecurity vulnerability. In many cases, estimating the probability of a cybersecurity exploit is very difficult due to factors such as; complexity of exploitation, availability of exploits, and exploit toolkits. In the absence of data on the probability of the occurrence of harm, conventional medical device risk management approaches suggest using a "reasonable worst-case estimate" or setting the default value of the probability to one. While these approaches are acceptable, FDA suggests that manufacturers instead consider using a cybersecurity vulnerability assessment tool or similar scoring system for rating vulnerabilities and determining the need for and urgency of the response.

One such tool, the ["Common Vulnerability Scoring System," Version 3.0](https://www.first.org/cvss/specification-document), for example, provides numerical ratings corresponding to high, medium and low by incorporating a number of factors in assessing exploitability including:[^20]

- Attack Vector (physical, local, adjacent, network)
- Attack Complexity (high, low)
- Privileges Required (none, low, high)
- User Interaction (none, required)
- Scope (changed, unchanged)
- Confidentiality Impact (high, low, none)
- Integrity Impact (none, low, high)
- Availability Impact (high, low, none)
- Exploit Code Maturity (high, functional, proof-of-concept, unproven)
- Remediation Level (unavailable, work-around, temporary fix, official fix, not defined)
- Report Confidence (confirmed, reasonable, unknown, not defined)

In using any vulnerability scoring system (or tool), weighting of the individual factors that contribute to the composite score should be carefully considered.

Other resources that may aid in the triage of vulnerabilities are: AAMI TIR57: Principles for medical device security – Risk management,[^21] IEC 80001: Application of risk management for IT Networks incorporating medical devices,[^22] the [National Vulnerability Database](https://nvd.nist.gov/)[^23] (NVD), the [Common Vulnerabilities and Exposures](https://cve.mitre.org/)[^24] (CVE), [Common Weakness Enumeration](http://cwe.mitre.org/index.html)[^25] (CWE), [Common Weakness Scoring System](http://cwe.mitre.org/cwss/cwss_v1.0.1.html)[^26] (CWSS), [Common Attack Pattern Enumeration and Classification](http://capec.mitre.org/)[^27] (CAPEC), [Common Configuration Enumeration](https://nvd.nist.gov/cce/index.cfm)[^28] (CCE) [Common Platform Enumeration](https://nvd.nist.gov/cpe.cfm)[^29] (CPE).

## B. Assessing Severity of Patient Harm
Manufacturers should also have a process for assessing the severity of patient harm, if the cybersecurity vulnerability were to be exploited. While there are many potentially acceptable approaches for conducting this type of analysis, one such approach may be based on qualitative severity levels as described in ANSI/AAMI/ISO 14971: 2007/(R)2010: Medical Devices – Application of Risk Management to Medical Devices:

| Common Term | Possible Description |
|-------------|---------------------|
| Negligible | Inconvenience or temporary discomfort |
| Minor | Results in temporary injury or impairment not requiring professional medical intervention |
| Serious | Results in injury or impairment requiring professional medical intervention |
| Critical | Results in permanent impairment or life-threatening injury |
| Catastrophic | Results in patient death |

## C. Evaluation of Risk of Patient Harm
A key purpose of conducting the cyber-vulnerability risk assessment is to evaluate whether the risk of patient harm is controlled (acceptable) or uncontrolled (unacceptable). One method of assessing the acceptability of risk involves using a matrix with combinations of "exploitability" and "severity of patient harm" to determine whether the risk of patient harm is controlled or uncontrolled. A manufacturer can then conduct assessments of the exploitability and severity of patient harm and then use such a matrix to assess the risk of patient harm for the identified cybersecurity vulnerabilities.

For risks that remain uncontrolled, additional remediation should be implemented.

The following figure is an example matrix that shows a possible approach to evaluate the relationship between exploitability and patient harm. It can be used to assess the risk of patient harm from a cybersecurity vulnerability as controlled or uncontrolled. While in some cases the evaluation will yield a definite determination that the situation is controlled or uncontrolled, it is possible that in other situations this determination may not be as distinct. Nevertheless, in all cases, FDA recommends that manufacturers make a binary determination that a vulnerability is either controlled or uncontrolled using an established process that is tailored to the product, its safety and essential performance, and the situation. Risk mitigations, including compensating controls, should be implemented when necessary to bring the residual risk to an acceptable level.

**Figure – Evaluation of Risk of Patient Harm.** The figure shows the relationship between exploitability and severity of patient harm, and can be used to assess the risk of patient harm from a cybersecurity vulnerability. The figure can be used to categorize the risk of patient harm as controlled or uncontrolled. (그림추가)

[^20]: For a full description of each factor, see ["Common Vulnerability Scoring System," Version 3.0: Specification Document](https://www.first.org/cvss/specification-document). 각 요인에 대한 전체 설명은 ["공통 취약점 점수 시스템", 버전 3.0: 사양 문서](https://www.first.org/cvss/specification-document) 참조.

[^21]: AAMI TIR57: Principles for medical device security—Risk management - See more at: http://www.aami.org/productspublications/ProductDetail.aspx?ItemNumber=3729#sthash.CqfSLyu9.dpuf AAMI TIR57: 의료기기 보안 원칙 - 위험 관리 - 자세한 내용은 http://www.aami.org/productspublications/ProductDetail.aspx?ItemNumber=3729#sthash.CqfSLyu9.dpuf 참조

[^22]: IEC/TR 80001-2-1:2012 Application of risk management for IT-networks incorporating medical devices IEC/TR 80001-2-1:2012 의료기기를 통합한 IT 네트워크에 대한 위험 관리 적용

[^23]: [National Vulnerability Database (NVD)](https://nvd.nist.gov/). [국가 취약점 데이터베이스 (NVD)](https://nvd.nist.gov/).

[^24]: [Common Vulnerabilities and Exposures (CVE)](https://cve.mitre.org/). [공통 취약점 및 노출 (CVE)](https://cve.mitre.org/).

[^25]: [Common Weakness Enumeration (CWE)](http://cwe.mitre.org/index.html). [공통 약점 열거 (CWE)](http://cwe.mitre.org/index.html).

[^26]: [Common Weakness Scoring System (CWSS)](http://cwe.mitre.org/cwss/cwss_v1.0.1.html). [공통 약점 점수 시스템 (CWSS)](http://cwe.mitre.org/cwss/cwss_v1.0.1.html).

[^27]: [Common Attack Pattern Enumeration and Classification (CAPEC)](http://capec.mitre.org/). [공통 공격 패턴 열거 및 분류 (CAPEC)](http://capec.mitre.org/).

[^28]: [Common Configuration Enumeration (CCE)](https://nvd.nist.gov/cce/index.cfm). [공통 구성 열거 (CCE)](https://nvd.nist.gov/cce/index.cfm).

[^29]: [Common Platform Enumeration (CPE)](https://nvd.nist.gov/cpe.cfm). [공통 플랫폼 열거 (CPE)](https://nvd.nist.gov/cpe.cfm).

# VI. 의료기기 사이버보안 위험 관리
21 CFR part 820과 일치하는 위험 관리 프로세스의 일환으로, 제조업체는 의료기기 수명주기 전반에 걸쳐 의료기기의 사이버보안과 관련된 위험요인을 식별하고, 관련 위험을 추정 및 평가하며, 이러한 위험을 통제하고, 통제의 효과성을 모니터링하기 위한 지속적인 프로세스를 수립, 문서화 및 유지해야 한다. 이 프로세스는 위험 분석, 위험 평가, 위험 통제, 그리고 생산 및 생산 후 정보의 통합을 포함해야 한다. 본 지침의 부록에서 식별된 요소들은 효과적인 위험 관리 프로세스를 지원하기 위해 제조업체의 사이버보안 위험 관리 프로그램의 일부로 포함되어야 한다. 제조업체는 위험 평가를 체계적으로 수행하고 의료기기에 영향을 미치는 사이버보안 취약점이 수용 가능한 위험인지 수용 불가능한 위험인지를 결정하기 위한 정의된 프로세스를 가져야 한다. 본 지침에서 의료기기 사이버보안 취약점과 관련된 모든 위험요인, 관련 위험 및/또는 통제를 설명하는 것은 불가능하다. 또한 위험이 통제되거나 통제되지 않는 모든 시나리오를 설명하는 것도 불가능하다. 오히려, FDA는 제조업체가 자신의 기기에 대한 사이버보안 위험을 객관적으로 평가하기 위한 프로세스를 정의하고 문서화할 것을 권장한다.

아래에 설명된 바와 같이, 이러한 프로세스는 다음을 고려하여 환자 위해의 위험을 평가하는 데 중점을 두는 것이 권장된다:

1) 사이버보안 취약점의 악용 가능성, 그리고
2) 취약점이 악용될 경우 환자 위해의 심각도.

이러한 분석은 또한 보상 통제 및 위험 완화에 대한 고려를 통합해야 한다.

## A. 사이버보안 취약점의 악용 가능성 평가
제조업체는 사이버보안 취약점의 악용 가능성을 평가하기 위한 프로세스를 가져야 한다. 많은 경우, 악용의 복잡성, 악용의 가용성 및 악용 툴킷과 같은 요인으로 인해 사이버보안 악용의 확률을 추정하는 것은 매우 어렵다. 위해 발생 확률에 대한 데이터가 없는 경우, 기존의 의료기기 위험 관리 접근법은 "합리적인 최악의 시나리오 추정"을 사용하거나 확률의 기본값을 1로 설정할 것을 제안한다. 이러한 접근법도 수용 가능하지만, FDA는 제조업체가 대신 취약점을 평가하고 대응의 필요성 및 긴급성을 결정하기 위해 사이버보안 취약점 평가 도구 또는 유사한 점수 시스템을 사용하는 것을 고려할 것을 제안한다.

예를 들어, 그러한 도구 중 하나인 ["공통 취약점 점수 시스템", 버전 3.0](https://www.first.org/cvss/specification-document)은 다음을 포함한 악용 가능성 평가에 여러 요인을 통합하여 높음, 중간 및 낮음에 해당하는 수치 등급을 제공한다:[^20]

- 공격 벡터(물리적, 로컬, 인접, 네트워크)
- 공격 복잡성(높음, 낮음)
- 필요한 권한(없음, 낮음, 높음)
- 사용자 상호작용(없음, 필요)
- 범위(변경됨, 변경되지 않음)
- 기밀성 영향(높음, 낮음, 없음)
- 무결성 영향(없음, 낮음, 높음)
- 가용성 영향(높음, 낮음, 없음)
- 악용 코드 성숙도(높음, 기능적, 개념 증명, 입증되지 않음)
- 시정 수준(불가능, 임시방편, 임시 수정, 공식 수정, 정의되지 않음)
- 보고 신뢰도(확인됨, 합리적, 알 수 없음, 정의되지 않음)

취약점 점수 시스템(또는 도구)을 사용할 때, 복합 점수에 기여하는 개별 요인의 가중치를 신중히 고려해야 한다.

취약점 분류에 도움이 될 수 있는 기타 자원은 다음과 같다: AAMI TIR57: 의료기기 보안 원칙 – 위험 관리,[^21] IEC 80001: 의료기기를 통합한 IT 네트워크에 대한 위험 관리 적용,[^22] [국가 취약점 데이터베이스](https://nvd.nist.gov/)[^23] (NVD), [공통 취약점 및 노출](https://cve.mitre.org/)[^24] (CVE), [공통 약점 열거](http://cwe.mitre.org/index.html)[^25] (CWE), [공통 약점 점수 시스템](http://cwe.mitre.org/cwss/cwss_v1.0.1.html)[^26] (CWSS), [공통 공격 패턴 열거 및 분류](http://capec.mitre.org/)[^27] (CAPEC), [공통 구성 열거](https://nvd.nist.gov/cce/index.cfm)[^28] (CCE), [공통 플랫폼 열거](https://nvd.nist.gov/cpe.cfm)[^29] (CPE).

## B. 환자 위해의 심각도 평가
제조업체는 또한 사이버보안 취약점이 악용될 경우 환자 위해의 심각도를 평가하기 위한 프로세스를 가져야 한다. 이러한 유형의 분석을 수행하기 위한 잠재적으로 수용 가능한 많은 접근법이 있지만, 그러한 접근법 중 하나는 ANSI/AAMI/ISO 14971: 2007/(R)2010: 의료기기 – 의료기기에 대한 위험관리 적용에 설명된 질적 심각도 수준을 기반으로 할 수 있다:

| 일반 용어 | 가능한 설명 |
|-------------|---------------------|
| 무시할 만한 | 불편 또는 일시적 불편함 |
| 경미한 | 전문적인 의료 개입이 필요하지 않은 일시적 상해 또는 손상을 초래 |
| 심각한 | 전문적인 의료 개입이 필요한 상해 또는 손상을 초래 |
| 중대한 | 영구적 손상 또는 생명을 위협하는 상해를 초래 |
| 치명적 | 환자 사망을 초래 |

## C. 환자 위해의 위험 평가
사이버 취약점 위험 평가를 수행하는 주요 목적은 환자 위해의 위험이 통제되었는지(수용 가능) 또는 통제되지 않았는지(수용 불가능)를 평가하는 것이다. 위험의 수용 가능성을 평가하는 한 가지 방법은 환자 위해의 위험이 통제되었는지 또는 통제되지 않았는지를 결정하기 위해 "악용 가능성"과 "환자 위해의 심각도"의 조합으로 매트릭스를 사용하는 것이다. 제조업체는 악용 가능성과 환자 위해의 심각도에 대한 평가를 수행한 다음 이러한 매트릭스를 사용하여 식별된 사이버보안 취약점에 대한 환자 위해의 위험을 평가할 수 있다.

통제되지 않은 상태로 남아 있는 위험에 대해서는 추가 시정이 구현되어야 한다.

다음 그림은 악용 가능성과 환자 위해 간의 관계를 평가하는 가능한 접근법을 보여주는 예시 매트릭스이다. 이는 사이버보안 취약점으로 인한 환자 위해의 위험을 통제되거나 통제되지 않은 것으로 평가하는 데 사용될 수 있다. 일부 경우에는 평가가 상황이 통제되거나 통제되지 않았다는 명확한 결정을 산출하지만, 다른 상황에서는 이 결정이 명확하지 않을 수 있다. 그럼에도 불구하고, 모든 경우에 FDA는 제조업체가 제품, 그 안전성 및 필수 성능, 그리고 상황에 맞춰진 확립된 프로세스를 사용하여 취약점이 통제되거나 통제되지 않았다는 이진 결정을 내릴 것을 권장한다. 보상 통제를 포함한 위험 완화는 잔여 위험을 수용 가능한 수준으로 가져오기 위해 필요할 때 구현되어야 한다.

**그림 – 환자 위해의 위험 평가.** 이 그림은 악용 가능성과 환자 위해의 심각도 간의 관계를 보여주며, 사이버보안 취약점으로 인한 환자 위해의 위험을 평가하는 데 사용될 수 있다. 이 그림은 환자 위해의 위험을 통제되거나 통제되지 않은 것으로 분류하는 데 사용될 수 있다. (그림추가)

# VII. Remediating and Reporting Cybersecurity Vulnerabilities
Based on the vulnerability assessment described in the previous section, the exploitability of an identified vulnerability and its severity of patient harm can help determine the risk of patient harm and can be categorized as either "controlled" (acceptable residual risk) or "uncontrolled" (unacceptable residual risk). When determining how to manage a cybersecurity vulnerability, manufacturers should incorporate already implemented compensating controls and risk mitigations into their risk assessment.

FDA encourages efficient, timely and ongoing cybersecurity risk management for marketed devices by manufacturers. For cybersecurity routine updates and patches, the FDA will, typically, not need to conduct premarket review to clear or approve the medical device software changes.[^30] In addition, manufacturers should:

- Adopt a coordinated vulnerability disclosure policy and practice that includes acknowledging receipt of the initial vulnerability report to the vulnerability submitter;[^31],[^32]
- Proactively practice good cyber hygiene, reassess risk assessments regularly, and seek opportunities to reduce cybersecurity risks even when residual risk is acceptable;
- Remediate cybersecurity vulnerabilities to reduce the risk of patient harm to an acceptable level;
- Conduct appropriate software validation under 21 CFR 820.30(g) to assure that any implemented remediation effectively mitigates the target vulnerability without unintentionally creating exposure to other risks;
- Properly document the methods and controls used in the design, manufacture, packaging, labeling, storage, installation and servicing of all finished devices as required by 21 CFR part 820;
- Identify and implement compensating controls to adequately mitigate the cybersecurity vulnerability risk, especially when new device design controls[^33] may not be feasible or immediately practicable. In addition, manufacturers should consider the level of knowledge and expertise needed to properly implement the recommended control;
- Provide users with relevant information on recommended device and compensating controls and residual cybersecurity risks so that they can take appropriate steps to mitigate the risk and make informed decisions regarding device use; and
- Recognize that some changes made to strengthen device security might also significantly affect other device functionality (e.g., use of a different operating system) and assess the scope of change to determine if additional premarket or postmarket regulatory actions are appropriate.

In addition to the general recommendations described above, Sections VII.A and VII.B. below clarify specific recommendations for managing controlled and uncontrolled risks of patient harm.[^34] While FDA recognizes that multi-stakeholder engagement is necessary to fully address cybersecurity risks, the examples provided in the controlled risk and uncontrolled risk sections below clarify FDA's regulatory expectations for medical device manufacturers.

## A. Controlled Risk of Patient Harm
Controlled risk is present when there is sufficiently low (acceptable) residual risk of patient harm due to the vulnerability.

Manufacturers are encouraged to proactively promote good cyber hygiene and reduce cybersecurity risks even when residual risk is acceptable. The following are recommendations for changes or compensating control actions taken to address vulnerabilities associated with controlled risk:

- Changes to a device that are made solely to strengthen cybersecurity are typically considered device enhancements,[^35] which may include cybersecurity routine updates and patches, and are generally not required to be reported, under 21 CFR part 806.
- Even when risks are controlled, manufacturers may wish to deploy an additional control(s) as part of a "defense-in-depth" strategy. Typically, these changes would be considered a cybersecurity routine update or patch, a type of device enhancement;
- Device changes made solely to address a vulnerability that, if exploited, could lead to compromise of PHI, would typically be considered a cybersecurity routine update or patch;
- For premarket approval (PMA) devices with periodic reporting requirements under 21 CFR 814.84, newly acquired information concerning cybersecurity vulnerabilities and device changes made as part of cybersecurity routine updates and patches should be reported to FDA in a periodic (annual) report. See Section VIII for recommended content to include in the periodic report.

*Examples of Vulnerabilities Associated with Controlled Risk and their Management:*

- A device manufacturer receives a user complaint that a gas blood analyzer has been infected with malware and there was concern that the malware may alter the data on the device. The outcome of a manufacturer investigation and impact assessment confirms the presence of malware and finds that the malware does not result in the manipulation of unencrypted data stored and flowing through the device. The device's safety and essential performance is not impacted by the malware and the manufacturer's risk assessment determines that the risk of patient harm due to the vulnerability is controlled. The device manufacturer communicates to users on how to remove the malware and decides to develop a defense-in-depth strategy; these changes would be considered a cybersecurity routine update and patch, a type of device enhancement.

- A researcher publicly discloses exploit code for a four year old vulnerability in commercial off-the-shelf database software. The vulnerable version of the software is in a percentage of the manufacturer's installed base and in two separate product lines including a multi-analyte chemistry analyzer. The manufacturer determines that the vulnerability is the result of a misconfigured database setting and could allow an unauthorized user to view patient health information in the database. The vulnerability does not permit the unauthorized user the ability to edit data in the database. Thus, the manufacturer determines the vulnerability has acceptable and controlled risk of patient harm. The manufacturer notifies their customers and the user community of the issue, details the secure configuration setting, and documents the effectiveness of the cybersecurity routine update for the configuration setting.

- A device manufacturer is notified of an open, unused communication port by the U.S. Department of Homeland Security Industrial Control Systems-Cyber Emergency Response Team (ICS-CERT). Subsequent analyses show that a design feature of the device prevents unauthorized remote firmware download onto the device. The threat is mitigated substantially by the need for physical access due to this device feature and the residual risk of patient harm is considered "acceptable." The manufacturer takes steps to further enhance the device's security by taking steps to close the unused communication port(s) and provide adequate communication to device users (e.g., user facilities) to facilitate the patch. If the manufacturer closes the open communication ports, the change would be considered a cybersecurity routine update or patch, a type of device enhancement. The change does not require reporting under 21 CFR part 806 (see the ["Distinguishing Medical Device Recalls from Medical Enhancements Guidance"](http://www.fda.gov/downloads/medicaldevices/deviceregulationandguidance/guidancedocuments/ucm418469.pdf) for additional clarity of reporting requirements and recommendations for device enhancements).

- A device manufacturer receives a user complaint that a recent security software scan of the PC component of a class III medical device has indicated that the PC is infected with malware. The outcome of a manufacturer investigation and impact assessment confirms the presence of malware and that the primary purpose of the malware is to collect internet browsing information. The manufacturer also determines that the malware has actively collected browsing information, but that the device's safety and essential performance is not and would not be impacted by such collection. The manufacturer's risk assessment determines that the risk of patient harm due to the vulnerability is controlled. Since the risk of patient harm is controlled, the manufacturer can update the product and it will be considered a cybersecurity routine update or patch. In this case, the manufacturer does not need to report this software update to the FDA in accordance with 21 CFR 806.10. Because the device is a class III device, the manufacturer should report the changes to the FDA in its periodic (annual) report required for holders of an approved PMA under 21 CFR 814.84.

## B. Uncontrolled Risk to Safety and Essential Performance
Uncontrolled risk is present when there is unacceptable residual risk of patient harm due to insufficient risk mitigations and compensating controls. In assessing risk, manufacturers should consider the exploitability of the vulnerability and the severity of patient harm if exploited. If the risk of patient harm is assessed as uncontrolled, additional risk control measures should be applied.

Manufacturers should remediate uncontrolled risks as quickly as possible. The following are recommendations for changes or compensating control actions to address vulnerabilities associated with uncontrolled risk:

- Manufacturers should remediate the vulnerabilities to reduce the risk of patient harm to an acceptable level;
- While fixing the vulnerability may not be feasible or immediately practicable, manufacturers should identify and implement risk mitigations and compensating controls to adequately mitigate the risk;
- Customers and the user community should be provided with relevant information on recommended controls and residual cybersecurity risks so that they can take appropriate steps to mitigate the risk and make informed decisions regarding device use;
- Manufacturers must report these vulnerabilities to the FDA according to 21 CFR part 806, unless reported under 21 CFR parts 803 or 1004.[^36] However, the FDA does not intend to enforce reporting requirements under 21 CFR part 806 for specific vulnerabilities with uncontrolled risk when the following circumstances are met:

  1) There are no known serious adverse events or deaths associated with the vulnerability;

  2) As soon as possible but no later than 30 days after learning of the vulnerability, the manufacturer communicates with its customers and user community regarding the vulnerability, identifies interim compensating controls, and develops a remediation plan to bring the residual risk to an acceptable level. Controls should not introduce more risk to the device's safety and essential performance than the original vulnerability. The manufacturer must document[^37] the timeline rationale for its remediation plan.[^38] The customer communication should, at minimum:
     - a. Describe the vulnerability including an impact assessment based on the manufacturer's current understanding,
     - b. State that manufacturer's efforts are underway to address the risk of patient harm as expeditiously as possible,
     - c. Describe compensating controls, if any, and
     - d. State that the manufacturer is working to fix the vulnerability, or provide a defense-in-depth strategy to reduce the probability of exploit and/or severity of harm, and will communicate regarding the availability of a fix in the future.

  3) As soon as possible but no later than 60 days after learning of the vulnerability, the manufacturer fixes the vulnerability, validates the change, and distributes the deployable fix to its customers and user community such that the residual risk is brought down to an acceptable level. In some circumstances, a compensating control could produce a long-term solution provided the risk of patient harm is brought to an acceptable level. Controls should not introduce more risk to the device's safety and essential performance than the original vulnerability. Additionally, the manufacturer should follow-up with end-users as needed beyond the initial 60 day period;[^39]

  4) The manufacturer actively participates as a member of an ISAO that shares vulnerabilities and threats that impact medical devices, such as NH-ISAC (see section IX) and provides the ISAO with any customer communications upon notification of its customers;

- Remediation of devices with annual reporting requirements (e.g., class III devices) should be included in the annual report;
- The manufacturer should evaluate the device changes to assess the need to submit a premarket submission (e.g., PMA supplement,[^40] 510(k), etc.) to the FDA;
- For PMA devices with periodic reporting requirements under 21 CFR 814.84, information concerning cybersecurity vulnerabilities, and the device changes and compensating controls implemented in response to this information should be reported to FDA in a periodic (annual) report. See Section VIII for recommended content to include in the periodic report.

In the absence of remediation, a device with uncontrolled risk of patient harm may be considered to have a reasonable probability that use of, or exposure to, the product will cause serious adverse health consequences or death. The product may be considered in violation of the FD&C Act and subject to enforcement or other action.

*Examples of Vulnerabilities Associated with Uncontrolled Risk of Patient Harm That Must Be Remediated and Response Actions:*

- A manufacturer is made aware of open, unused communication ports. The manufacturer acknowledges receipt of the vulnerability report to the submitter/identifier and subsequent analysis determines that the device's designed-in features do not prevent a threat from downloading unauthorized firmware onto the device, which could be used to compromise the device's safety and essential performance. Although there are no reported serious adverse events or deaths associated with the vulnerability, the risk assessment concludes the risk of patient harm is uncontrolled. The manufacturer communicates with its customers, the ISAO, and user community regarding the vulnerability, identifies and implements interim compensating controls, develops a remediation plan, and notifies users within 30 days of becoming aware of the vulnerability. Furthermore, within 60 days of becoming aware of the vulnerability, the manufacturer develops a more permanent solution/fix (in this case a software update to close the unused communication port(s)), validates the change, distributes the deployable fix or work around to its customers, and implements all other aspects of its remediation plan. If the manufacturer actively participates as a member of an ISAO and shares information about the vulnerability within the ISAO, FDA does not intend to enforce compliance with the reporting requirements in 21 CFR part 806. For class III devices, the manufacturer does submit a summary of the remediation as part of its periodic (annual) report to FDA.

- A manufacturer becomes aware of a vulnerability via a researcher that its class III medical device (e.g., implantable defibrillator, pacemaker, etc.) can be reprogrammed by an unauthorized user. If exploited, this vulnerability could result in permanent impairment, a life-threatening injury, or death. The manufacturer is not aware that the vulnerability has been exploited and determines that the vulnerability is related to a hardcoded password. The risk assessment concludes that the exploitability of the vulnerability is moderate and the risk of patient harm is uncontrolled. The manufacturer notifies appropriate stakeholders, and distributes a validated emergency patch within 60 days. The manufacturer does not actively participate as a member of an ISAO and therefore reports this action to the FDA under 21 CFR 806.10.

- A vulnerability known to the security community, yet unknown to a medical device manufacturer, is incorporated into a class II device during development. Following clearance, the manufacturer becomes aware of the vulnerability and determines that the device continues to meet its specifications, and that no device malfunctions or patient injuries have been reported. There is no evidence that the identified vulnerability has been exploited. However, it was determined that the vulnerability introduced a new failure mode to the device that impacts its essential performance, and the device's design controls do not mitigate the risk. The manufacturer conducts a risk assessment and determines that without additional mitigations, the risk of patient harm is uncontrolled. Since the manufacturer does not currently have a software update to mitigate the impact of this vulnerability on the device's essential performance, within 30 days of learning of the vulnerability the manufacturer notifies its customers, the ISAO, and user community of the cybersecurity risk and instructs them to disconnect the device from the hospital network to prevent unauthorized access to the device. The company's risk assessment concludes that the risk of patient harm is controlled with this additional mitigation. The manufacturer determines that removal of the device from the network is not a viable long-term solution and distributes a patch within 60 days of learning of the vulnerability. If the company is an active participating member of an ISAO, FDA does not intend to enforce compliance with the reporting requirement under 21 CFR part 806.

- A hospital reports that a patient was harmed after a medical device failed to perform as intended. A manufacturer investigation determines that the medical device malfunctioned as a result of exploitation of a previously unknown vulnerability in its proprietary software. The outcome of the manufacturer's investigation and impact assessment determines that the exploit indirectly impacts the device's safety and essential performance and may have contributed to a patient death. The manufacturer files a report in accordance with reporting requirements under 21 CFR part 803. The manufacturer also determines the device would be likely to cause or contribute to a serious injury or death if the malfunction were to recur; therefore, the manufacturer notifies its customers and user community, develops a validated emergency patch and files a report in accordance with 21 CFR 806.10 to notify FDA.

[^30]: Premarket notification (510(k)) would be required for countermeasures that would be considered significant changes or modifications to a device's design, components, method of manufacture or intended use (See 21 CFR 807.81(a)(3)). 기기의 설계, 구성요소, 제조 방법 또는 의도된 사용에 대한 중대한 변경 또는 수정으로 간주되는 대응책의 경우 시판 전 통지(510(k))가 요구된다(21 CFR 807.81(a)(3) 참조).

[^31]: ISO/IEC 29147:2014: Information Technology – Security Techniques – Vulnerability Disclosure which may be a useful resource for manufacturers. ISO/IEC 29147:2014: 정보기술 – 보안 기술 – 취약점 공개는 제조업체에게 유용한 자원이 될 수 있다.

[^32]: ISO/IEC 30111:2013: Information Technology – Security Techniques – Vulnerability Handling Processes. ISO/IEC 30111:2013: 정보기술 – 보안 기술 – 취약점 처리 프로세스.

[^33]: See 21 CFR part 820.30(g) Design controls 21 CFR part 820.30(g) 설계 통제 참조

[^34]: Please note that manufacturers and user facilities may have additional reporting requirements from sources other than FDA. 제조업체 및 사용자 시설은 FDA 이외의 출처로부터 추가 보고 요건이 있을 수 있음을 유의하기 바란다.

[^35]: See FDA guidance titled ["Distinguishing Medical Device Recalls from Medical Device Enhancements"](http://www.fda.gov/downloads/MedicalDevices/DeviceRegulationandGuidance/GuidanceDocuments/UCM418469.pdf) ["의료기기 회수와 의료기기 개선의 구별"](http://www.fda.gov/downloads/MedicalDevices/DeviceRegulationandGuidance/GuidanceDocuments/UCM418469.pdf)이라는 제목의 FDA 지침 참조

[^36]: See 21 CFR 806.10(f). 21 CFR 806.10(f) 참조.

[^37]: See 21 CFR 820.100 Corrective action and preventive action. 21 CFR 820.100 시정 조치 및 예방 조치 참조.

[^38]: See 21 CFR 7.42 Recall strategy for elements of a remediation plan 시정 계획의 요소에 대한 회수 전략은 21 CFR 7.42 참조

[^39]: See 21 CFR 7 (b)(3) – Effectiveness checks. 21 CFR 7 (b)(3) – 효과성 점검 참조.

[^40]: See 21 CFR 814.39, see also FDA webpage titled, ["PMA Supplements and Amendments"](http://www.fda.gov/MedicalDevices/DeviceRegulationandGuidance/HowtoMarketYourDevice/PremarketSubmissions/PremarketApprovalPMA/ucm050467.htm). 21 CFR 814.39 참조, ["PMA 보충 및 수정"](http://www.fda.gov/MedicalDevices/DeviceRegulationandGuidance/HowtoMarketYourDevice/PremarketSubmissions/PremarketApprovalPMA/ucm050467.htm)이라는 제목의 FDA 웹페이지도 참조.

# VII. 사이버보안 취약점의 시정 및 보고

이전 섹션에서 설명한 취약점 평가를 기반으로, 식별된 취약점의 악용 가능성과 환자 위해의 심각도는 환자 위해의 위험을 결정하는 데 도움이 될 수 있으며 "통제됨"(수용 가능한 잔여 위험) 또는 "통제되지 않음"(수용 불가능한 잔여 위험)으로 분류될 수 있다. 사이버보안 취약점을 관리하는 방법을 결정할 때, 제조업체는 이미 구현된 보상 통제 및 위험 완화를 위험 평가에 통합해야 한다.

FDA는 제조업체가 시판된 기기에 대한 효율적이고 적시적이며 지속적인 사이버보안 위험 관리를 수행할 것을 권장한다. 사이버보안 정기 업데이트 및 패치의 경우, FDA는 일반적으로 의료기기 소프트웨어 변경을 허가하거나 승인하기 위해 시판 전 검토를 수행할 필요가 없다.[^30] 또한, 제조업체는 다음을 수행해야 한다:

- 취약점 제출자에게 초기 취약점 보고서의 수령을 확인하는 것을 포함하는 조정된 취약점 공개 정책 및 실무 채택;[^31],[^32]
- 사전예방적으로 좋은 사이버 위생을 실천하고, 위험 평가를 정기적으로 재평가하며, 잔여 위험이 수용 가능한 경우에도 사이버보안 위험을 줄일 기회를 모색;
- 환자 위해의 위험을 수용 가능한 수준으로 감소시키기 위해 사이버보안 취약점 시정;
- 구현된 시정이 의도하지 않게 다른 위험에 대한 노출을 생성하지 않으면서 대상 취약점을 효과적으로 완화하도록 보장하기 위해 21 CFR 820.30(g)에 따른 적절한 소프트웨어 검증 수행;
- 21 CFR part 820에서 요구하는 바와 같이 모든 완제품의 설계, 제조, 포장, 라벨링, 보관, 설치 및 서비스에 사용되는 방법 및 통제를 적절히 문서화;
- 새로운 기기 설계 통제[^33]가 실현 가능하지 않거나 즉시 실행 가능하지 않은 경우 특히 사이버보안 취약점 위험을 적절히 완화하기 위한 보상 통제를 식별하고 구현. 또한, 제조업체는 권장 통제를 적절히 구현하는 데 필요한 지식 및 전문성 수준을 고려해야 한다;
- 사용자가 위험을 완화하기 위한 적절한 조치를 취하고 기기 사용에 관한 정보에 입각한 결정을 내릴 수 있도록 권장 기기 및 보상 통제와 잔여 사이버보안 위험에 대한 관련 정보를 사용자에게 제공; 그리고
- 기기 보안을 강화하기 위해 이루어진 일부 변경이 다른 기기 기능에도 상당한 영향을 미칠 수 있음(예: 다른 운영 체제 사용)을 인식하고 추가 시판 전 또는 시판 후 규제 조치가 적절한지 판단하기 위해 변경 범위를 평가.

위에 설명된 일반 권고사항 외에도, 아래 섹션 VII.A 및 VII.B는 환자 위해의 통제된 위험과 통제되지 않은 위험을 관리하기 위한 구체적인 권고사항을 명확히 한다.[^34] FDA는 사이버보안 위험을 완전히 해결하기 위해서는 다중 이해관계자의 참여가 필요함을 인식하지만, 아래 통제된 위험 및 통제되지 않은 위험 섹션에서 제공되는 예시는 의료기기 제조업체에 대한 FDA의 규제 기대치를 명확히 한다.

## A. 환자 위해의 통제된 위험

통제된 위험은 취약점으로 인한 환자 위해의 잔여 위험이 충분히 낮은(수용 가능한) 경우에 존재한다.

제조업체는 잔여 위험이 수용 가능한 경우에도 사전예방적으로 좋은 사이버 위생을 촉진하고 사이버보안 위험을 줄이도록 권장된다. 다음은 통제된 위험과 관련된 취약점을 해결하기 위해 취한 변경 또는 보상 통제 조치에 대한 권고사항이다:

- 사이버보안을 강화하기 위해서만 이루어진 기기 변경은 일반적으로 기기 개선으로 간주되며,[^35] 여기에는 사이버보안 정기 업데이트 및 패치가 포함될 수 있고, 일반적으로 21 CFR part 806에 따라 보고할 필요가 없다.
- 위험이 통제된 경우에도 제조업체는 "심층 방어" 전략의 일환으로 추가 통제를 배포하기를 원할 수 있다. 일반적으로 이러한 변경은 사이버보안 정기 업데이트 또는 패치, 즉 일종의 기기 개선으로 간주된다;
- 악용될 경우 PHI의 손상으로 이어질 수 있는 취약점을 해결하기 위해서만 이루어진 기기 변경은 일반적으로 사이버보안 정기 업데이트 또는 패치로 간주된다;
- 21 CFR 814.84에 따른 정기 보고 요건이 있는 시판 전 승인(PMA) 기기의 경우, 사이버보안 취약점에 관한 새로 획득한 정보 및 사이버보안 정기 업데이트 및 패치의 일환으로 이루어진 기기 변경은 정기(연간) 보고서로 FDA에 보고되어야 한다. 정기 보고서에 포함할 권장 내용은 섹션 VIII을 참조하기 바란다.

**통제된 위험과 관련된 취약점 및 그 관리의 예:**

- 기기 제조업체가 가스 혈액 분석기가 악성코드에 감염되었고 악성코드가 기기의 데이터를 변경할 수 있다는 우려가 있다는 사용자 불만을 접수한다. 제조업체 조사 및 영향 평가의 결과 악성코드의 존재를 확인하고 악성코드가 기기를 통해 저장 및 흐르는 암호화되지 않은 데이터의 조작을 초래하지 않음을 발견한다. 기기의 안전성 및 필수 성능은 악성코드의 영향을 받지 않으며 제조업체의 위험 평가는 취약점으로 인한 환자 위해의 위험이 통제된다고 결정한다. 기기 제조업체는 사용자에게 악성코드를 제거하는 방법을 전달하고 심층 방어 전략을 개발하기로 결정한다; 이러한 변경은 사이버보안 정기 업데이트 및 패치, 즉 일종의 기기 개선으로 간주된다.

- 연구원이 상용 데이터베이스 소프트웨어의 4년 된 취약점에 대한 악용 코드를 공개적으로 공개한다. 취약한 버전의 소프트웨어는 제조업체의 설치 기반의 일부와 다중 분석 화학 분석기를 포함한 두 개의 별도 제품 라인에 있다. 제조업체는 취약점이 잘못 구성된 데이터베이스 설정의 결과이며 무단 사용자가 데이터베이스의 환자 건강 정보를 볼 수 있도록 허용할 수 있다고 판단한다. 취약점은 무단 사용자에게 데이터베이스의 데이터를 편집할 수 있는 능력을 허용하지 않는다. 따라서 제조업체는 취약점이 수용 가능하고 통제된 환자 위해의 위험을 가지고 있다고 판단한다. 제조업체는 고객 및 사용자 커뮤니티에 문제를 통지하고, 안전한 구성 설정을 자세히 설명하며, 구성 설정에 대한 사이버보안 정기 업데이트의 효과를 문서화한다.

- 기기 제조업체가 미국 국토안보부 산업제어시스템-사이버 긴급대응팀(ICS-CERT)으로부터 열려 있는 미사용 통신 포트에 대한 통지를 받는다. 후속 분석은 기기의 설계 기능이 기기에 대한 무단 원격 펌웨어 다운로드를 방지함을 보여준다. 이 기기 기능으로 인해 물리적 접근이 필요하기 때문에 위협이 상당히 완화되며 환자 위해의 잔여 위험은 "수용 가능"한 것으로 간주된다. 제조업체는 미사용 통신 포트를 닫고 패치를 용이하게 하기 위해 기기 사용자(예: 사용자 시설)에게 적절한 커뮤니케이션을 제공하는 조치를 취하여 기기의 보안을 더욱 강화한다. 제조업체가 열려 있는 통신 포트를 닫으면, 변경은 사이버보안 정기 업데이트 또는 패치, 즉 일종의 기기 개선으로 간주된다. 변경은 21 CFR part 806에 따른 보고를 필요로 하지 않는다(보고 요건 및 기기 개선에 대한 권고사항의 추가 명확성을 위해 ["의료기기 회수와 의료기기 개선의 구별 지침"](http://www.fda.gov/downloads/medicaldevices/deviceregulationandguidance/guidancedocuments/ucm418469.pdf) 참조).

- 기기 제조업체가 클래스 III 의료기기의 PC 구성요소에 대한 최근 보안 소프트웨어 스캔이 PC가 악성코드에 감염되었음을 나타냈다는 사용자 불만을 접수한다. 제조업체 조사 및 영향 평가의 결과 악성코드의 존재를 확인하고 악성코드의 주요 목적이 인터넷 브라우징 정보를 수집하는 것임을 확인한다. 제조업체는 또한 악성코드가 브라우징 정보를 적극적으로 수집했지만, 기기의 안전성 및 필수 성능은 그러한 수집에 의해 영향을 받지 않으며 영향을 받지 않을 것이라고 판단한다. 제조업체의 위험 평가는 취약점으로 인한 환자 위해의 위험이 통제된다고 결정한다. 환자 위해의 위험이 통제되기 때문에, 제조업체는 제품을 업데이트할 수 있으며 이는 사이버보안 정기 업데이트 또는 패치로 간주된다. 이 경우, 제조업체는 21 CFR 806.10에 따라 이 소프트웨어 업데이트를 FDA에 보고할 필요가 없다. 기기가 클래스 III 기기이기 때문에, 제조업체는 21 CFR 814.84에 따라 승인된 PMA 보유자에게 요구되는 정기(연간) 보고서에서 FDA에 변경사항을 보고해야 한다.

## B. 안전성 및 필수 성능에 대한 통제되지 않은 위험

통제되지 않은 위험은 불충분한 위험 완화 및 보상 통제로 인해 환자 위해의 수용 불가능한 잔여 위험이 존재하는 경우에 존재한다. 위험을 평가할 때, 제조업체는 취약점의 악용 가능성과 악용될 경우 환자 위해의 심각도를 고려해야 한다. 환자 위해의 위험이 통제되지 않은 것으로 평가되면, 추가 위험 통제 조치가 적용되어야 한다.

제조업체는 통제되지 않은 위험을 가능한 한 신속하게 시정해야 한다. 다음은 통제되지 않은 위험과 관련된 취약점을 해결하기 위한 변경 또는 보상 통제 조치에 대한 권고사항이다:

- 제조업체는 환자 위해의 위험을 수용 가능한 수준으로 감소시키기 위해 취약점을 시정해야 한다;
- 취약점을 수정하는 것이 실현 가능하지 않거나 즉시 실행 가능하지 않을 수 있지만, 제조업체는 위험을 적절히 완화하기 위한 위험 완화 및 보상 통제를 식별하고 구현해야 한다;
- 고객 및 사용자 커뮤니티에게 권장 통제 및 잔여 사이버보안 위험에 대한 관련 정보를 제공하여 위험을 완화하기 위한 적절한 조치를 취하고 기기 사용에 관한 정보에 입각한 결정을 내릴 수 있도록 해야 한다;
- 제조업체는 21 CFR parts 803 또는 1004에 따라 보고된 경우를 제외하고 21 CFR part 806에 따라 이러한 취약점을 FDA에 보고해야 한다.[^36] 그러나 FDA는 다음 상황이 충족되는 경우 통제되지 않은 위험이 있는 특정 취약점에 대해 21 CFR part 806에 따른 보고 요건을 시행하지 않을 것이다:

  1) 취약점과 관련된 알려진 중대한 이상 사건 또는 사망이 없다;

  2) 취약점을 인지한 후 가능한 한 빨리 그러나 30일 이내에, 제조업체는 취약점에 관해 고객 및 사용자 커뮤니티와 커뮤니케이션하고, 잠정 보상 통제를 식별하며, 잔여 위험을 수용 가능한 수준으로 가져오기 위한 시정 계획을 개발한다. 통제는 원래 취약점보다 기기의 안전성 및 필수 성능에 더 많은 위험을 도입해서는 안 된다. 제조업체는 시정 계획에 대한 일정 근거를 문서화해야 한다.[^37] 고객 커뮤니케이션은 최소한 다음을 포함해야 한다:[^38]
     a. 제조업체의 현재 이해를 기반으로 한 영향 평가를 포함한 취약점 설명,
     b. 제조업체가 환자 위해의 위험을 가능한 한 신속하게 해결하기 위해 노력하고 있다는 진술,
     c. 있는 경우 보상 통제에 대한 설명, 그리고
     d. 제조업체가 취약점을 수정하기 위해 작업 중이거나, 악용 확률 및/또는 위해의 심각도를 줄이기 위한 심층 방어 전략을 제공하고 있으며, 향후 수정의 가용성에 관해 커뮤니케이션할 것이라는 진술.

  3) 취약점을 인지한 후 가능한 한 빨리 그러나 60일 이내에, 제조업체는 취약점을 수정하고, 변경을 검증하며, 잔여 위험이 수용 가능한 수준으로 낮아지도록 배포 가능한 수정을 고객 및 사용자 커뮤니티에 배포한다. 일부 상황에서는 환자 위해의 위험이 수용 가능한 수준으로 가져와지는 경우 보상 통제가 장기 솔루션을 생성할 수 있다. 통제는 원래 취약점보다 기기의 안전성 및 필수 성능에 더 많은 위험을 도입해서는 안 된다. 또한, 제조업체는 초기 60일 기간을 넘어 필요에 따라 최종 사용자와 후속 조치를 취해야 한다;[^39]

  4) 제조업체는 NH-ISAC과 같이 의료기기에 영향을 미치는 취약점과 위협을 공유하는 ISAO의 회원으로 적극적으로 참여하고(섹션 IX 참조) 고객에게 통지할 때 ISAO에 모든 고객 커뮤니케이션을 제공한다;

- 연간 보고 요건이 있는 기기(예: 클래스 III 기기)의 시정은 연간 보고서에 포함되어야 한다;
- 제조업체는 기기 변경을 평가하여 FDA에 시판 전 제출(예: PMA 보충,[^40] 510(k) 등)을 제출할 필요성을 평가해야 한다;
- 21 CFR 814.84에 따른 정기 보고 요건이 있는 PMA 기기의 경우, 사이버보안 취약점에 관한 정보, 그리고 이 정보에 대응하여 구현된 기기 변경 및 보상 통제는 정기(연간) 보고서로 FDA에 보고되어야 한다. 정기 보고서에 포함할 권장 내용은 섹션 VIII을 참조하기 바란다.

시정이 없는 경우, 환자 위해의 통제되지 않은 위험이 있는 기기는 제품의 사용 또는 노출이 심각한 건강상의 부작용 또는 사망을 초래할 합리적인 가능성이 있는 것으로 간주될 수 있다. 제품은 FD&C Act 위반으로 간주되어 시행 또는 기타 조치의 대상이 될 수 있다.

**시정되어야 하는 환자 위해의 통제되지 않은 위험과 관련된 취약점 및 대응 조치의 예:**

- 제조업체가 열려 있는 미사용 통신 포트에 대해 인지하게 된다. 제조업체는 제출자/식별자에게 취약점 보고서 수령을 확인하고 후속 분석 결과 기기의 내장 기능이 기기의 안전성 및 필수 성능을 손상시키는 데 사용될 수 있는 무단 펌웨어를 기기에 다운로드하는 위협을 방지하지 못한다고 판단한다. 취약점과 관련된 보고된 중대한 이상 사건 또는 사망이 없지만, 위험 평가는 환자 위해의 위험이 통제되지 않는다고 결론 내린다. 제조업체는 취약점에 관해 고객, ISAO 및 사용자 커뮤니티와 커뮤니케이션하고, 잠정 보상 통제를 식별하고 구현하며, 시정 계획을 개발하고, 취약점을 인지한 후 30일 이내에 사용자에게 통지한다. 또한, 취약점을 인지한 후 60일 이내에, 제조업체는 보다 영구적인 솔루션/수정(이 경우 미사용 통신 포트를 닫는 소프트웨어 업데이트)을 개발하고, 변경을 검증하며, 배포 가능한 수정 또는 임시방편을 고객에게 배포하고, 시정 계획의 모든 다른 측면을 구현한다. 제조업체가 ISAO의 회원으로 적극적으로 참여하고 ISAO 내에서 취약점에 대한 정보를 공유하는 경우, FDA는 21 CFR part 806의 보고 요건에 대한 준수를 시행하지 않을 것이다. 클래스 III 기기의 경우, 제조업체는 FDA에 대한 정기(연간) 보고서의 일부로 시정의 요약을 제출한다.

- 제조업체가 연구원을 통해 클래스 III 의료기기(예: 이식형 제세동기, 심박조율기 등)가 무단 사용자에 의해 재프로그래밍될 수 있는 취약점을 인지하게 된다. 악용될 경우, 이 취약점은 영구적 손상, 생명을 위협하는 상해 또는 사망을 초래할 수 있다. 제조업체는 취약점이 악용되었다는 것을 인지하지 못하며 취약점이 하드코딩된 비밀번호와 관련이 있다고 판단한다. 위험 평가는 취약점의 악용 가능성이 중간이고 환자 위해의 위험이 통제되지 않는다고 결론 내린다. 제조업체는 적절한 이해관계자에게 통지하고 60일 이내에 검증된 긴급 패치를 배포한다. 제조업체는 ISAO의 회원으로 적극적으로 참여하지 않으므로 21 CFR 806.10에 따라 FDA에 이 조치를 보고한다.

- 보안 커뮤니티에는 알려져 있지만 의료기기 제조업체에게는 알려지지 않은 취약점이 개발 중 클래스 II 기기에 통합된다. 허가 후, 제조업체는 취약점을 인지하게 되고 기기가 계속해서 사양을 충족하며 기기 오작동이나 환자 부상이 보고되지 않았다고 판단한다. 식별된 취약점이 악용되었다는 증거는 없다. 그러나 취약점이 기기의 필수 성능에 영향을 미치는 새로운 고장 모드를 도입했으며 기기의 설계 통제가 위험을 완화하지 못한다고 판단되었다. 제조업체는 위험 평가를 수행하고 추가 완화 없이 환자 위해의 위험이 통제되지 않는다고 판단한다. 제조업체가 현재 기기의 필수 성능에 대한 이 취약점의 영향을 완화하기 위한 소프트웨어 업데이트를 가지고 있지 않기 때문에, 취약점을 인지한 후 30일 이내에 제조업체는 고객, ISAO 및 사용자 커뮤니티에 사이버보안 위험을 통지하고 기기에 대한 무단 접근을 방지하기 위해 병원 네트워크에서 기기를 분리하도록 지시한다. 회사의 위험 평가는 이 추가 완화로 환자 위해의 위험이 통제된다고 결론 내린다. 제조업체는 네트워크에서 기기를 제거하는 것이 실행 가능한 장기 솔루션이 아니라고 판단하고 취약점을 인지한 후 60일 이내에 패치를 배포한다. 회사가 ISAO의 적극적으로 참여하는 회원인 경우, FDA는 21 CFR part 806에 따른 보고 요건에 대한 준수를 시행하지 않을 것이다.

- 병원이 의료기기가 의도한 대로 수행하지 못한 후 환자가 위해를 입었다고 보고한다. 제조업체 조사는 의료기기가 독점 소프트웨어의 이전에 알려지지 않은 취약점의 악용 결과로 오작동했다고 판단한다. 제조업체의 조사 및 영향 평가의 결과는 악용이 기기의 안전성 및 필수 성능에 간접적으로 영향을 미치며 환자 사망에 기여했을 수 있다고 판단한다. 제조업체는 21 CFR part 803의 보고 요건에 따라 보고서를 제출한다. 제조업체는 또한 오작동이 재발하는 경우 기기가 중대한 상해 또는 사망을 초래하거나 기여할 가능성이 있다고 판단한다; 따라서 제조업체는 고객 및 사용자 커뮤니티에 통지하고, 검증된 긴급 패치를 개발하며, FDA에 통지하기 위해 21 CFR 806.10에 따라 보고서를 제출한다.

# VIII. Recommended Content to Include in PMA Periodic Reports
For PMA devices with periodic reporting requirements under 21 CFR 814.84, information concerning cybersecurity vulnerabilities, and device changes and compensating controls implemented in response to this information should be reported to FDA in a periodic (annual) report.

It is recommended that the following information be provided for changes and compensating controls implemented for the device:

- A brief description of the vulnerability prompting the change including how the firm became aware of the vulnerability;
- A summary of the conclusions of the firm's risk assessment including whether the risk of patient harm was controlled or uncontrolled;
- A description of the change(s) made, including a comparison to the previously approved version of the device;
- The rationale for making the change;
- Reference to other submissions/devices that were modified in response to this same vulnerability;
- Identification of event(s) related to the rationale/reason for the change (e.g., MDR number(s), recall number);
- Unique Device Identification (UDI)[^41] should be included, if available;
- A link to an [ICS-CERT advisory](https://ics-cert.us-cert.gov/advisories) or other government or ISAO alert, if applicable;
- All distributed customer notifications;
- The date and name of the ISAO to which the vulnerability was reported, if any; and
- Reference to other relevant submission (PMA Supplement,[^42] 30-Day Notice, 806 report, etc.), if any, or the scientific and/or regulatory basis for concluding that the change did not require a submission/report.

[^41]: See the web page titled ["Unique Device Identification – UDI"](http://www.fda.gov/MedicalDevices/DeviceRegulationandGuidance/UniqueDeviceIdentification/) for more information 자세한 정보는 ["고유기기식별 – UDI"](http://www.fda.gov/MedicalDevices/DeviceRegulationandGuidance/UniqueDeviceIdentification/)라는 제목의 웹페이지 참조

[^42]: See 21 CFR 814.39. 21 CFR 814.39 참조.

# VIII. PMA 정기 보고서에 포함할 권장 내용

21 CFR 814.84에 따른 정기 보고 요건이 있는 PMA 기기의 경우, 사이버보안 취약점에 관한 정보, 그리고 이 정보에 대응하여 구현된 기기 변경 및 보상 통제는 정기(연간) 보고서로 FDA에 보고되어야 한다.

기기에 대해 구현된 변경 및 보상 통제에 대해 다음 정보를 제공할 것을 권장한다:

- 회사가 취약점을 인지하게 된 방법을 포함하여 변경을 촉발한 취약점에 대한 간략한 설명;
- 환자 위해의 위험이 통제되었는지 또는 통제되지 않았는지를 포함한 회사의 위험 평가 결론의 요약;
- 이전에 승인된 기기 버전과의 비교를 포함하여 이루어진 변경 사항의 설명;
- 변경을 수행한 근거;
- 동일한 취약점에 대응하여 수정된 다른 제출/기기에 대한 참조;
- 변경의 근거/이유와 관련된 사건 식별(예: MDR 번호, 회수 번호);
- 고유기기식별(UDI)[^41]은 가능한 경우 포함되어야 한다;
- 해당되는 경우 [ICS-CERT 권고](https://ics-cert.us-cert.gov/advisories) 또는 기타 정부 또는 ISAO 경보에 대한 링크;
- 배포된 모든 고객 통지;
- 취약점이 보고된 ISAO의 날짜 및 이름(있는 경우); 그리고
- 다른 관련 제출(PMA 보충,[^42] 30일 통지, 806 보고서 등)에 대한 참조(있는 경우), 또는 변경이 제출/보고를 요구하지 않는다고 결론 내린 과학적 및/또는 규제적 근거.

# IX. Criteria for Defining Active Participation by a Manufacturer in an ISAO

Active participation by a manufacturer in an ISAO can assist the company, the medical device community and the HPH Sector by proactively addressing cybersecurity vulnerabilities and minimizing exploits through the timely deployment of risk control measures including communication and coordination with patients and users.

FDA intends to consider the following in determining whether a manufacturer is an active participant in an ISAO:

1. The manufacturer is a member of an ISAO that shares vulnerabilities and threats that impact medical devices;
2. The ISAO has documented policies pertaining to participant agreements, business processes, operating procedures, and privacy protections;
3. The manufacturer shares vulnerability information with the ISAO, including any customer communications pertaining to cybersecurity vulnerabilities; and
4. The manufacturer has documented processes for assessing and responding to vulnerability and threat intelligence information received from the ISAO. This information should be traceable to medical device risk assessments, countermeasure solutions, and mitigations.

Manufacturers that wish to be considered by FDA to be active participants in an ISAO are recommended to maintain objective evidence documenting that they meet the four criteria above.

# IX. ISAO에서 제조업체의 적극적 참여를 정의하는 기준

ISAO에서 제조업체의 적극적 참여는 환자 및 사용자와의 커뮤니케이션 및 조정을 포함한 위험 통제 조치의 적시 배포를 통해 사이버보안 취약점을 사전예방적으로 해결하고 악용을 최소화함으로써 회사, 의료기기 커뮤니티 및 HPH 부문을 지원할 수 있다.

FDA는 제조업체가 ISAO의 적극적 참여자인지를 결정할 때 다음을 고려할 것이다:

1. 제조업체는 의료기기에 영향을 미치는 취약점과 위협을 공유하는 ISAO의 회원이다;
2. ISAO는 참가자 합의, 비즈니스 프로세스, 운영 절차 및 프라이버시 보호와 관련된 문서화된 정책을 보유하고 있다;
3. 제조업체는 사이버보안 취약점과 관련된 모든 고객 커뮤니케이션을 포함하여 취약점 정보를 ISAO와 공유한다; 그리고
4. 제조업체는 ISAO로부터 받은 취약점 및 위협 인텔리전스 정보를 평가하고 대응하기 위한 문서화된 프로세스를 보유하고 있다. 이 정보는 의료기기 위험 평가, 대응책 솔루션 및 완화에 추적 가능해야 한다.

FDA가 ISAO의 적극적 참여자로 간주되기를 원하는 제조업체는 위의 네 가지 기준을 충족한다는 것을 문서화하는 객관적 증거를 유지할 것을 권장한다.

# X. Appendix: Elements of an Effective Postmarket Cybersecurity Program
It is recommended that the following elements, consistent with the [NIST Framework for Improving Critical Infrastructure Cybersecurity](https://www.nist.gov/sites/default/files/documents/cyberframework/cybersecurity-framework-021214.pdf) (i.e., Identify, Protect, Detect, Respond, and Recover), be included as part of a manufacturer's cybersecurity risk management program.

## A. Identify

### i. Maintaining Safety and Essential Performance
Compromise of safety or essential performance of a device can result in patient harm and may require intervention to prevent patient harm.

Manufacturers should define, as part of their comprehensive cybersecurity risk management plan, the safety and essential performance of their device, the resulting severity of patient harm if compromised, and the risk acceptance criteria. These steps allow manufacturers to triage vulnerabilities for remediation (see Section VI for additional information on risk assessments).

Threat modeling is important to understanding and assessing the exploitability of a device vulnerability and its potential for patient harm. Threat modeling can also be used in determining whether a proposed or implemented remediation can provide assurance that the risk of patient harm due to a cybersecurity vulnerability is reasonably controlled. Importantly, acceptable mitigations will vary depending upon the severity of patient harm that may result from exploitation of a vulnerability affecting the device. For example, a cybersecurity vulnerability affecting the temperature reading of a thermometer may have different risks than a cybersecurity vulnerability affecting the dosage of an insulin infusion pump because of the severity of patient harm.

### ii. Identification of Cybersecurity Signals
Manufacturers are required to analyze complaints, returned product, service records, and other sources of quality data to identify existing and potential causes of nonconforming product or other quality problems (21 CFR 820.100). Manufacturers are encouraged to actively identify cybersecurity signals that might affect their product, and engage with the sources that report them. It is important to recognize that signals can originate from sources familiar to the medical device workspace such as internal investigations, post market surveillance and or/complaints. It is also important to recognize that cybersecurity signals may originate from cybersecurity-centric sources such as Cyber Emergency Response Teams (CERTS), ISAOs, security researchers, or from other critical infrastructure sectors such as the Defense or Financial Sectors. Irrespective of the originating source, a clear, consistent and reproducible process for intake and handling of vulnerability information should be established and implemented by the manufacturer. FDA has recognized ISO/IEC 29147:2014, Information Technology - Security Techniques - Vulnerability Disclosure and ISO/IEC 30111:2013: Information Technology – Security Techniques – Vulnerability Handling Processes that may be useful resources for manufacturers. Manufacturers should develop strategies to enhance their ability to detect signals (e.g., participating in an ISAO for medical devices). Manufacturers can also enhance their postmarket detection of cybersecurity risks by incorporating detection mechanisms into their device design and device features to increase the detectability of attacks and permit forensically sound evidence capture.

## B. Protect/Detect

### i. Vulnerability Characterization and Assessment
The FDA recommends that manufacturers characterize and assess identified vulnerabilities because it will provide information that will aid manufacturers to triage remediation activities. When characterizing the exploitability of a vulnerability, the manufacturer should consider factors such as remote exploitability, attack complexity, threat privileges, actions required by the user, exploit code maturity, and report confidence. Scoring systems such as the ["Common Vulnerability Scoring System" (CVSS)](https://www.first.org/cvss/calculator/3.0)[^43] provide a consistent framework for assessing exploitability by quantifying the impact of the factors that influence exploitability. See Section VI for additional guidance on vulnerability risk assessment.

### ii. Risk Analysis and Threat Modeling
The FDA recommends that manufacturers conduct cybersecurity risk analyses that include threat modeling for each of their devices and to update those analyses over time. Risk analyses and threat modeling should aim to triage vulnerabilities for timely remediation. Threat modeling is a procedure for optimizing Network/Application/Internet Security by identifying objectives and vulnerabilities, and then defining countermeasures to prevent, or mitigate the effects of, threats to the system. Threat modeling provides traditional risk management and failure mode analysis paradigms, and a framework to assess threats from active adversaries/malicious use. For each vulnerability, a summary report should be produced that concisely summarizes the risk analysis and threat modeling information. Due to the cyclical nature of the analyses, the information should be traceable to related documentation.

### iii. Analysis of Threat Sources[^44]
The FDA recommends manufacturers to analyze possible threat sources. A threat source is defined as the intent and method targeted at the intentional exploitation of a vulnerability or a situation and method that may accidentally trigger a vulnerability.[^45] Analysis of threat sources, as part of risk analysis and threat modeling provides a framework for risk introduced by an active adversary. Therefore, characterization of threat sources will be advantageous to manufacturers in accessing risks not covered by traditional failure mode analysis methods.

### iv. Incorporation of Threat Detection Capabilities
Medical devices may not be capable of detecting threat activity and may be reliant on network monitoring. Manufacturers should consider the incorporation of design features that establish or enhance the ability of the device to detect and produce forensically sound postmarket evidence capture in the event of an attack. This information may assist the manufacturer in assessing and remediating identified risks.

### v. Impact Assessment on All Devices

The FDA recommends that manufacturers have a process to assess the impact of a cybersecurity signal horizontally (i.e., across all medical devices within the manufacturer's product portfolio and sometimes referred to as variant analyses) and vertically (i.e., determine if there is an impact on specific components within the device). A signal may identify a vulnerability in one device, and that same vulnerability may impact other devices including those in development, or those not yet cleared, approved or marketed. Therefore, it will be advantageous to manufacturers to conduct analyses for cybersecurity signals such that expended detection resources have the widest impact.

## C. Protect/Respond/Recover

### i. Compensating Controls Assessment (Detect/Respond)
The FDA recommends that manufacturers implement device-based features, i.e. device design controls,[^46] as a primary mechanism to mitigate the risk of patient harm. Manufacturers should assess and provide users with compensating controls such that the risk of patient harm is further mitigated. In total, these efforts represent a defense-in-depth strategy for medical device cybersecurity. Section VII describes recommendations for remediating and reporting identified cybersecurity vulnerabilities, including the development, implementation and user notification concerning fixes. Manufacturers should also adopt a coordinated vulnerability disclosure policy and practice that includes acknowledging receipt of the vulnerability to the vulnerability submitter within a specified time frame.[^47],[^48] The FDA has recognized ISO/IEC 29147:2014: Information Technology – Security Techniques – Vulnerability Disclosure that may be a useful resource for manufacturers.

## D. Risk Mitigation of Safety and Essential Performance
Once the preceding information has been assessed and characterized, manufacturers should determine if the risk of patient harm presented by the vulnerability are adequately controlled by existing device features and/or manufacturer defined compensating controls (i.e., residual risk levels are acceptable). Actions taken should reflect the magnitude of the problem and align with the risks encountered. Manufacturers should also include an evaluation of residual risk, benefit/risk, and risk introduced by the remediation. Manufacturers should design their devices to ensure that risks inherent in remediation are properly mitigated including ensuring that the remediation is adequate and validated, that the device designs incorporate mechanisms for secure and timely updates.

Changes made for vulnerabilities of controlled risk are generally considered device enhancements, not recalls. Cybersecurity routine updates and patches are generally considered a type of device enhancement.

[^43]: ["Common Vulnerability Scoring System," Version 3.0, Scoring Calculator](https://www.first.org/cvss/calculator/3.0). ["공통 취약점 점수 시스템", 버전 3.0, 점수 계산기](https://www.first.org/cvss/calculator/3.0).

[^44]: National Institute of Standards and Technology, ["Guide for Conducting Risk Assessments," NIST Special Publication 800-30 Revision 1](http://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-30r1.pdf). 국립표준기술연구소, ["위험 평가 수행 지침", NIST 특별 간행물 800-30 개정판 1](http://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-30r1.pdf).

[^45]: National Institute of Standards and Technology, "Security and Privacy Controls for Federal Information Systems and Organizations," NIST Special Publication 800-53, Revision 4, Appendix B (http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r4.pdf). 국립표준기술연구소, "연방 정보 시스템 및 조직을 위한 보안 및 프라이버시 통제", NIST 특별 간행물 800-53, 개정판 4, 부록 B (http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r4.pdf).

[^46]: See 21 CFR 820.30(g). 21 CFR 820.30(g) 참조.

[^47]: The FDA has recognized ISO/IEC 29147:2014: Information Technology – Security Techniques – Vulnerability Disclosure FDA는 ISO/IEC 29147:2014: 정보기술 – 보안 기술 – 취약점 공개를 인정하였다.

[^48]: ISO/IEC 30111:2013: Information Technology – Security Techniques – Vulnerability Handling Processes ISO/IEC 30111:2013: 정보기술 – 보안 기술 – 취약점 처리 프로세스

# X. 부록: 효과적인 시판 후 사이버보안 프로그램의 요소

[중요 기반시설 사이버보안 개선을 위한 NIST 프레임워크](https://www.nist.gov/sites/default/files/documents/cyberframework/cybersecurity-framework-021214.pdf)(즉, 식별, 보호, 탐지, 대응 및 복구)와 일치하는 다음 요소들이 제조업체의 사이버보안 위험 관리 프로그램의 일부로 포함될 것을 권장한다.

## A. 식별

### i. 안전성 및 필수 성능 유지

기기의 안전성 또는 필수 성능의 손상은 환자 위해를 초래할 수 있으며 환자 위해를 예방하기 위한 개입이 필요할 수 있다.

제조업체는 포괄적인 사이버보안 위험 관리 계획의 일환으로 기기의 안전성 및 필수 성능, 손상된 경우 결과적으로 발생하는 환자 위해의 심각도, 그리고 위험 수용 기준을 정의해야 한다. 이러한 단계는 제조업체가 시정을 위해 취약점을 분류할 수 있게 한다(위험 평가에 대한 추가 정보는 섹션 VI 참조).

위협 모델링은 기기 취약점의 악용 가능성과 환자 위해의 가능성을 이해하고 평가하는 데 중요하다. 위협 모델링은 또한 제안되거나 구현된 시정이 사이버보안 취약점으로 인한 환자 위해의 위험이 합리적으로 통제된다는 보장을 제공할 수 있는지를 결정하는 데 사용될 수 있다. 중요하게도, 수용 가능한 완화책은 기기에 영향을 미치는 취약점의 악용으로 인해 발생할 수 있는 환자 위해의 심각도에 따라 달라질 것이다. 예를 들어, 온도계의 온도 판독에 영향을 미치는 사이버보안 취약점은 환자 위해의 심각도로 인해 인슐린 주입 펌프의 투여량에 영향을 미치는 사이버보안 취약점과는 다른 위험을 가질 수 있다.

### ii. 사이버보안 신호의 식별

제조업체는 부적합 제품 또는 기타 품질 문제의 기존 및 잠재적 원인을 식별하기 위해 불만, 반품, 서비스 기록 및 기타 품질 데이터 출처를 분석해야 한다(21 CFR 820.100). 제조업체는 자사 제품에 영향을 미칠 수 있는 사이버보안 신호를 적극적으로 식별하고 이를 보고하는 출처와 소통하도록 권장된다. 신호가 내부 조사, 시판 후 감시 및/또는 불만과 같이 의료기기 작업 공간에 익숙한 출처에서 발생할 수 있음을 인식하는 것이 중요하다. 또한 사이버보안 신호가 사이버 긴급대응팀(CERT), ISAO, 보안 연구원 또는 국방이나 금융 부문과 같은 다른 중요 기반시설 부문과 같은 사이버보안 중심 출처에서 발생할 수 있음을 인식하는 것도 중요하다. 발생 출처와 관계없이, 취약점 정보의 접수 및 처리를 위한 명확하고 일관되며 재현 가능한 프로세스가 제조업체에 의해 수립되고 구현되어야 한다. FDA는 제조업체에게 유용한 자원이 될 수 있는 ISO/IEC 29147:2014, 정보기술 - 보안 기술 - 취약점 공개 및 ISO/IEC 30111:2013: 정보기술 – 보안 기술 – 취약점 처리 프로세스를 인정하였다. 제조업체는 신호를 탐지하는 능력을 향상시키기 위한 전략을 개발해야 한다(예: 의료기기용 ISAO에 참여). 제조업체는 또한 공격의 탐지 가능성을 높이고 법의학적으로 건전한 증거 수집을 가능하게 하기 위해 기기 설계 및 기기 기능에 탐지 메커니즘을 통합함으로써 사이버보안 위험에 대한 시판 후 탐지를 향상시킬 수 있다.

## B. 보호/탐지

### i. 취약점 특성화 및 평가

FDA는 제조업체가 식별된 취약점을 특성화하고 평가할 것을 권장하는데, 이는 제조업체가 시정 활동을 분류하는 데 도움이 되는 정보를 제공할 것이기 때문이다. 취약점의 악용 가능성을 특성화할 때, 제조업체는 원격 악용 가능성, 공격 복잡성, 위협 권한, 사용자가 요구하는 조치, 악용 코드 성숙도 및 보고 신뢰도와 같은 요인을 고려해야 한다. ["공통 취약점 점수 시스템"(CVSS)](https://www.first.org/cvss/calculator/3.0)[^43]와 같은 점수 시스템은 악용 가능성에 영향을 미치는 요인의 영향을 정량화함으로써 악용 가능성을 평가하기 위한 일관된 프레임워크를 제공한다. 취약점 위험 평가에 대한 추가 지침은 섹션 VI를 참조하기 바란다.

### ii. 위험 분석 및 위협 모델링

FDA는 제조업체가 각 기기에 대해 위협 모델링을 포함하는 사이버보안 위험 분석을 수행하고 시간이 지남에 따라 이러한 분석을 업데이트할 것을 권장한다. 위험 분석 및 위협 모델링은 적시 시정을 위해 취약점을 분류하는 것을 목표로 해야 한다. 위협 모델링은 목표와 취약점을 식별한 다음 시스템에 대한 위협을 예방하거나 완화하기 위한 대응책을 정의함으로써 네트워크/애플리케이션/인터넷 보안을 최적화하기 위한 절차이다. 위협 모델링은 전통적인 위험 관리 및 고장 모드 분석 패러다임, 그리고 적극적인 적대자/악의적 사용으로부터의 위협을 평가하기 위한 프레임워크를 제공한다. 각 취약점에 대해 위험 분석 및 위협 모델링 정보를 간결하게 요약하는 요약 보고서가 작성되어야 한다. 분석의 순환적 특성으로 인해, 정보는 관련 문서에 추적 가능해야 한다.

### iii. 위협 출처 분석[^44]

FDA는 제조업체가 가능한 위협 출처를 분석할 것을 권장한다. 위협 출처는 취약점의 의도적 악용을 목표로 하는 의도 및 방법 또는 우발적으로 취약점을 촉발할 수 있는 상황 및 방법으로 정의된다.[^45] 위험 분석 및 위협 모델링의 일환으로서 위협 출처 분석은 적극적인 적대자에 의해 도입되는 위험에 대한 프레임워크를 제공한다. 따라서 위협 출처의 특성화는 전통적인 고장 모드 분석 방법으로 다루어지지 않는 위험에 접근하는 데 제조업체에게 유리할 것이다.

### iv. 위협 탐지 기능의 통합

의료기기는 위협 활동을 탐지할 수 없고 네트워크 모니터링에 의존할 수 있다. 제조업체는 공격 발생 시 기기가 법의학적으로 건전한 시판 후 증거 수집을 탐지하고 생성하는 능력을 확립하거나 향상시키는 설계 기능의 통합을 고려해야 한다. 이 정보는 제조업체가 식별된 위험을 평가하고 시정하는 데 도움이 될 수 있다.

### v. 모든 기기에 대한 영향 평가

FDA는 제조업체가 사이버보안 신호의 영향을 수평적으로(즉, 제조업체의 제품 포트폴리오 내 모든 의료기기에 걸쳐, 때때로 변형 분석이라고 함) 및 수직적으로(즉, 기기 내 특정 구성요소에 영향이 있는지 판단) 평가하는 프로세스를 갖출 것을 권장한다. 신호는 한 기기에서 취약점을 식별할 수 있으며, 동일한 취약점이 개발 중인 기기 또는 아직 허가, 승인 또는 시판되지 않은 기기를 포함한 다른 기기에 영향을 미칠 수 있다. 따라서 제조업체가 사이버보안 신호에 대한 분석을 수행하여 지출된 탐지 자원이 가장 넓은 영향을 미치도록 하는 것이 유리할 것이다.

## C. 보호/대응/복구

### i. 보상 통제 평가(탐지/대응)

FDA는 제조업체가 환자 위해의 위험을 완화하는 주요 메커니즘으로 기기 기반 기능, 즉 기기 설계 통제를[^46] 구현할 것을 권장한다. 제조업체는 환자 위해의 위험이 더욱 완화되도록 보상 통제를 평가하고 사용자에게 제공해야 한다. 전체적으로 이러한 노력은 의료기기 사이버보안을 위한 심층 방어 전략을 나타낸다. 섹션 VII은 수정의 개발, 구현 및 사용자 통지를 포함하여 식별된 사이버보안 취약점을 시정하고 보고하기 위한 권고사항을 설명한다. 제조업체는 또한 지정된 기간 내에 취약점 제출자에게 취약점 수령을 확인하는 것을 포함하는 조정된 취약점 공개 정책 및 실무를 채택해야 한다.[^47],[^48] FDA는 제조업체에게 유용한 자원이 될 수 있는 ISO/IEC 29147:2014: 정보기술 – 보안 기술 – 취약점 공개를 인정하였다.

## D. 안전성 및 필수 성능의 위험 완화

앞서 언급한 정보가 평가되고 특성화되면, 제조업체는 취약점이 제시하는 환자 위해의 위험이 기존 기기 기능 및/또는 제조업체가 정의한 보상 통제에 의해 적절히 통제되는지(즉, 잔여 위험 수준이 수용 가능한지) 판단해야 한다. 취한 조치는 문제의 규모를 반영해야 하며 직면한 위험과 일치해야 한다. 제조업체는 또한 잔여 위험, 편익/위험, 그리고 시정에 의해 도입되는 위험에 대한 평가를 포함해야 한다. 제조업체는 시정에 내재된 위험이 적절히 완화되도록 기기를 설계해야 하며, 여기에는 시정이 적절하고 검증되었는지 확인하고, 기기 설계가 안전하고 적시적인 업데이트를 위한 메커니즘을 통합하도록 보장하는 것이 포함된다.

통제된 위험의 취약점에 대해 이루어진 변경은 일반적으로 회수가 아닌 기기 개선으로 간주된다. 사이버보안 정기 업데이트 및 패치는 일반적으로 일종의 기기 개선으로 간주된다.
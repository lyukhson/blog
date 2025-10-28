---
title:  "[FDA] Cybersecurity in Medical Devices: Quality System Considerations and Content of Premarket Submissions (번역 포함)"
last_modified_at: 2025-10-27 14:29:55 ## ctrl+shift=I
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
**Cybersecurity in Medical Devices: Quality System Considerations and Content of Premarket Submissions**

Document issued on June 27, 2025.

A draft select update to this document was issued on March 13, 2024.

This document supersedes “Cybersecurity in Medical Devices: Quality System Considerations and Content of Premarket Submissions,” issued September 27, 2023.

의료기기의 사이버보안: 품질 시스템 고려사항 및 시판 전 제출 내용
문서 발행일: 2025년 6월 27일

초안 일부 업데이트 발행일: 2024년 3월 13일
본 문서는 2023년 9월 27일에 발행된 "의료기기의 사이버보안: 품질 시스템 고려사항 및 시판 전 제출 내용"을 대체합니다.

# I. Introduction
With the increasing integration of wireless, Internet- and network-connected capabilities, portable media (e.g., USB or CD), and the frequent electronic exchange of medical device-related health information and other information, the need for robust cybersecurity controls to ensure medical device safety and effectiveness has become more important.

In addition, cybersecurity threats to the healthcare sector have become more frequent and more severe, carrying increased potential for clinical impact. Cyber incidents have rendered medical devices and hospital networks inoperable, disrupting the delivery of patient care across healthcare facilities in the U.S. and globally. Such cyber incidents and exploits may lead to patient harm as a result of clinical hazards, such as delay in diagnoses and/or treatment.

Increased connectivity has resulted in individual devices operating as single elements of larger medical device systems. These systems can include healthcare facility networks, other devices, and software update servers, among other interconnected components. Consequently, without adequate cybersecurity considerations across all aspects of these systems, a cybersecurity threat can compromise the safety and/or effectiveness of a device by compromising the functionality of any asset in the system. As a result, ensuring device safety and effectiveness includes adequate device cybersecurity, as well as its security as part of the larger system.

For the current edition of the FDA-recognized consensus standard(s) referenced in this document, see the [FDA Recognized Consensus Standards Database](https://www.accessdata.fda.gov/scripts/cdrh/cfdocs/cfstandards/search.cfm). For more information regarding use of consensus standards in regulatory submissions, please refer to the FDA guidance titled "[Appropriate Use of Voluntary Consensus Standards in Premarket Submissions for Medical Devices](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/appropriate-use-voluntary-consensus-standards-premarket-submissions-medical-devices)" and "[Standards Development and the Use of Standards in Regulatory Submissions Reviewed in the Center for Biologics Evaluation and Research](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/standards-development-and-use-standards-regulatory-submissions-reviewed-center-biologics-evaluation)."

In general, FDA's guidance documents do not establish legally enforceable responsibilities. Instead, guidances describe the Agency's current thinking on a topic and should be viewed only as recommendations, unless specific regulatory or statutory requirements are cited. The use of the word should in Agency guidances means that something is suggested or recommended, but not required.

# I. 서론

무선, 인터넷 및 네트워크 연결 기능, 휴대용 매체(예: USB 또는 CD)의 통합이 증가하고, 의료기기 관련 건강 정보 및 기타 정보의 전자적 교환이 빈번해짐에 따라, 의료기기의 안전성과 효과성을 보장하기 위한 강력한 사이버보안 통제의 필요성이 더욱 중요해졌습니다.

또한, 의료 분야에 대한 사이버보안 위협은 더욱 빈번하고 심각해지고 있으며, 임상적 영향의 가능성도 증가하고 있습니다. 사이버 사고는 의료기기와 병원 네트워크를 작동 불능 상태로 만들어, 미국 및 전 세계 의료 시설에서 환자 치료 제공을 중단시켰습니다. 이러한 사이버 사고 및 악용은 진단 및/또는 치료 지연과 같은 임상적 위험의 결과로 환자에게 해를 끼칠 수 있습니다.

연결성의 증가로 인해 개별 기기는 더 큰 의료기기 시스템의 단일 요소로 작동하게 되었습니다. 이러한 시스템에는 의료 시설 네트워크, 다른 기기, 소프트웨어 업데이트 서버 등 상호 연결된 구성요소들이 포함될 수 있습니다. 결과적으로, 이러한 시스템의 모든 측면에서 적절한 사이버보안 고려사항이 없다면, 사이버보안 위협은 시스템 내 모든 자산의 기능을 손상시켜 기기의 안전성 및/또는 효과성을 손상시킬 수 있습니다. 따라서 기기의 안전성과 효과성을 보장하는 것은 적절한 기기 사이버보안뿐만 아니라 더 큰 시스템의 일부로서의 보안을 포함합니다.

본 문서에서 참조된 FDA 인정 합의 표준의 현재 버전은 [FDA 인정 합의 표준 데이터베이스](https://www.accessdata.fda.gov/scripts/cdrh/cfdocs/cfstandards/search.cfm)를 참조하십시오. 규제 제출에서 합의 표준 사용에 관한 자세한 정보는 "[의료기기 시판 전 제출에서 자발적 합의 표준의 적절한 사용](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/appropriate-use-voluntary-consensus-standards-premarket-submissions-medical-devices)" 및 "[생물학적 제제 평가 연구 센터에서 검토하는 규제 제출에서의 표준 개발 및 표준 사용](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/standards-development-and-use-standards-regulatory-submissions-reviewed-center-biologics-evaluation)" 제목의 FDA 가이던스를 참조하십시오.

일반적으로 FDA의 가이던스 문서는 법적으로 강제할 수 있는 책임을 규정하지 않습니다. 대신, 가이던스는 특정 주제에 대한 FDA의 현재 입장을 설명하며, 특정 규제 또는 법적 요구사항이 인용되지 않는 한 권장사항으로만 간주되어야 합니다. FDA 가이던스에서 "should"라는 단어의 사용은 무언가가 제안되거나 권장되지만 필수는 아님을 의미합니다.

# II. Scope
This guidance is applicable to devices with cybersecurity considerations, including but not limited to devices that include a device software function[^1] or that contain software (including firmware) or programmable logic. The guidance is not limited to devices that are network-enabled or contain other connected capabilities. This guidance describes recommendations regarding the cybersecurity information to be submitted for devices under the following premarket submission types, when submitted to the Center for Devices and Radiological Health (CDRH) or the Center for Biologics Evaluation and Research (CBER):

- Premarket Notification (510(k)) submissions;
- De Novo requests;
- Premarket Approval Applications (PMAs) and PMA supplements;
- Product Development Protocols (PDPs);
- Investigational Device Exemption (IDE) submissions;
- Humanitarian Device Exemption (HDE) submissions;
- Biologics License Application (BLA) submissions; and
- Investigational New Drug (IND) submissions.

Furthermore, this guidance applies to all types of devices within the meaning of section 201(h) of the FD&C Act, including devices that meet the definition of a biological product under section 351 of the [Public Health Service Act](https://www.govinfo.gov/content/pkg/USCODE-2011-title42/pdf/USCODE-2011-title42-chap6A-subchapII-partF-subpart1.pdf), whether or not they require a premarket submission. Therefore, the recommendations in this guidance also apply to devices for which a premarket submission is not required (e.g., for 510(k)-exempt devices). This guidance also applies to cyber devices, as defined in section 524B of the FD&C Act, which are a subset of devices.

Generally, the recommendations in this guidance apply to the device constituent part of a combination product[^2] (such as drug-device and biologic-device combination products) when the device constituent part presents cybersecurity considerations,[^3] including but not limited to devices that include a device software function or that contain software (including firmware) or programmable logic. For more information, contact the FDA review division that will have the lead review for the combination product.[^4]

As IDE submissions have a different benefit-risk threshold and are not marketing authorizations, specific recommendations for IDE submission documentation are provided in Appendix 3. Additionally, Appendix 5 contains terminology used throughout the guidance.

[^1]: For the purposes of this guidance, "device software function" means a software function that meets the definition of a device in section 201(h) of the Federal Food, Drug, and Cosmetic Act (FD&C Act). For the purposes of this guidance, the term "function" is a distinct purpose of the product, which could be the intended use or a subset of the intended use of the product. For more information, see FDA's guidance "[Multiple Function Device Products: Policy and Considerations](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/multiple-function-device-products-policy-and-considerations)." 본 가이던스의 목적상, "기기 소프트웨어 기능"은 연방 식품, 의약품 및 화장품법(FD&C법) 201(h)조의 기기 정의를 충족하는 소프트웨어 기능을 의미합니다. 본 가이던스의 목적상, "기능"이라는 용어는 제품의 의도된 사용 또는 제품의 의도된 사용의 하위 집합이 될 수 있는 제품의 명확한 목적을 의미합니다. 자세한 정보는 FDA의 가이던스 "[다기능 의료기기 제품: 정책 및 고려사항](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/multiple-function-device-products-policy-and-considerations)"을 참조하십시오.

[^2]: 21 CFR 3.2(e).

[^3]: 21 CFR 4.2.

[^4]: This guidance has been prepared by CDRH and CBER, in consultation with the Center for Drug Evaluation and Research (CDER) and the Office of Combination Products (OCP). 본 가이던스는 의약품 평가 연구 센터(CDER) 및 복합 제품 사무소(OCP)와 협의하여 CDRH와 CBER에서 작성되었습니다.

# II. 적용 범위

본 가이던스는 사이버보안 고려사항이 있는 기기에 적용되며, 여기에는 기기 소프트웨어 기능[^1]을 포함하는 기기 또는 소프트웨어(펌웨어 포함) 또는 프로그래밍 가능한 로직을 포함하는 기기가 포함되나 이에 국한되지 않습니다. 본 가이던스는 네트워크 연결이 가능하거나 기타 연결 기능을 포함하는 기기에만 국한되지 않습니다. 본 가이던스는 의료기기 및 방사선 보건 센터(CDRH) 또는 생물학적 제제 평가 연구 센터(CBER)에 제출되는 다음의 시판 전 제출 유형에 대한 사이버보안 정보 제출 권장사항을 설명합니다:

- 시판 전 신고(510(k)) 제출;
- De Novo 요청;
- 시판 전 승인 신청서(PMA) 및 PMA 보완;
- 제품 개발 프로토콜(PDP);
- 임상시험용 의료기기 면제(IDE) 제출;
- 인도주의적 의료기기 면제(HDE) 제출;
- 생물의약품 허가 신청(BLA) 제출; 그리고
- 임상시험용 신약(IND) 제출.

또한, 본 가이던스는 FD&C법 201(h)조의 의미 내에서 모든 유형의 기기에 적용되며, 여기에는 [공중보건서비스법](https://www.govinfo.gov/content/pkg/USCODE-2011-title42/pdf/USCODE-2011-title42-chap6A-subchapII-partF-subpart1.pdf) 351조에 따른 생물학적 제제의 정의를 충족하는 기기도 포함되며, 시판 전 제출이 필요한지 여부와 관계없이 적용됩니다. 따라서 본 가이던스의 권장사항은 시판 전 제출이 필요하지 않은 기기(예: 510(k) 면제 기기)에도 적용됩니다. 본 가이던스는 또한 FD&C법 524B조에 정의된 사이버 기기(cyber devices)에도 적용되며, 이는 기기의 하위 집합입니다.

일반적으로 본 가이던스의 권장사항은 복합 제품[^2](예: 의약품-기기 및 생물학적 제제-기기 복합 제품)의 기기 구성 부분이 사이버보안 고려사항을 제시하는 경우[^3] 해당 기기 구성 부분에 적용되며, 여기에는 기기 소프트웨어 기능을 포함하거나 소프트웨어(펌웨어 포함) 또는 프로그래밍 가능한 로직을 포함하는 기기가 포함되나 이에 국한되지 않습니다. 자세한 정보는 복합 제품에 대한 주요 심사를 담당할 FDA 심사 부서에 문의하시기 바랍니다.[^4]

IDE 제출은 다른 이익-위험 임계값을 가지며 시판 허가가 아니므로, IDE 제출 문서에 대한 구체적인 권장사항은 부록 3에 제공됩니다. 또한, 부록 5에는 가이던스 전반에 걸쳐 사용되는 용어가 포함되어 있습니다.

# III. Background
FDA recognizes that medical device cybersecurity is a shared responsibility among interested parties throughout the use environment of the medical device system, including healthcare facilities, patients, healthcare providers, and manufacturers of medical devices. For the purposes of this guidance, the term "medical device system" includes the device and systems—such as healthcare facility networks, other devices, and software update servers—to which it is connected.

Events across the healthcare sector have stressed the importance of cybersecurity to patient safety. The WannaCry[^5] ransomware[^6] affected hospital systems and medical devices across the globe. Vulnerabilities identified in commonly used third-party components, like URGENT/11[^7] and SweynTooth,[^8] have led to potential safety concerns across a broad range of devices that are used in various clinical specialties. In 2020, a ransomware attack on a German hospital highlighted the potential impacts due to delayed patient care when a cybersecurity attack forced patients to be diverted to another hospital.[^9]

FDA issued a final cybersecurity guidance addressing premarket expectations in 2014 "Content of Premarket Submissions for Management of Cybersecurity in Medical Devices," and the complementary guidance "[Postmarket Management of Cybersecurity in Medical Devices](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/postmarket-management-cybersecurity-medical-devices)," hereafter referred to as the "Postmarket Cybersecurity Guidance," in 2016. However, the rapidly evolving landscape, an increased understanding of emerging threats, and the need for capable deployment of mitigations throughout the total product lifecycle (TPLC) warrants an updated, iterative approach to device cybersecurity. The changes since the 2014 guidance are intended to further emphasize the importance of ensuring that devices are designed securely, are designed to be capable of mitigating emerging cybersecurity risks throughout the TPLC, and to more clearly outline FDA's recommendations for premarket submission information to address cybersecurity concerns.

One way these TPLC considerations for devices can be achieved is through the implementation and adoption of a Secure Product Development Framework (SPDF).[^10] An SPDF, as described in this guidance, is a set of processes that reduces the number and severity of vulnerabilities in products throughout the device lifecycle. Examples of such frameworks exist in many sectors, including the medical device sector.

Risk management for device manufacturers is the essential systematic practice of identifying, analyzing, evaluating, controlling, and monitoring risk throughout the product lifecycle to ensure that the devices they manufacture are safe and effective. The Quality System (QS) regulation in 21 CFR Part 820 explicitly addresses risk management activities in 21 CFR 820.30(g). FDA issued a final rule[^11] amending the device current good manufacturing practice (CGMP) requirements of the Quality System (QS) Regulation under 21 CFR 820 to align more closely with the international consensus standard for Quality Management Systems for medical devices used by many other regulatory authorities around the world, and the final rule incorporates risk management throughout its requirements.[^12]

The recommendations contained in this guidance are intended to supplement FDA's [Postmarket Cybersecurity Guidance](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/postmarket-management-cybersecurity-medical-devices), and "[Content of Premarket Submissions for Device Software Functions](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/content-premarket-submissions-device-software-functions)," hereafter referred to as the "Premarket Software Guidance." This guidance replaces the 2014 final guidance "Content of Premarket Submissions for Management of Cybersecurity in Medical Devices."

The recommendations in this guidance also generally align with or expand upon the recommendations in the Pre-Market Considerations for Medical Device Cybersecurity section of the International Medical Device Regulators Forum (IMDRF) final guidance "[Principles and Practices for Medical Device Cybersecurity](http://www.imdrf.org/documents/documents.asp)," issued in March 2020.

Additionally, section 3305 of the Food and Drug Omnibus Reform Act of 2022 ("FDORA"), enacted on December 29, 2022, added section 524B "Ensuring Cybersecurity of Medical Devices" to the FD&C Act. Effective March 29, 2023, with respect to premarket submissions for "cyber devices," section 524B(a) provides that sponsors must include information to ensure the device meets the cybersecurity requirements under section 524B(b).[^13] Under section 524B(a) of the FD&C Act, a person who submits a 510(k), PMA, PDP, De Novo, or HDE for a device that meets the definition of a cyber device, as defined under section 524B(c), is required to submit information to ensure that cyber devices meet the cybersecurity requirements under section 524B(b).[^14] Section 524B(c) of the FD&C Act defines "cyber device" as a device that "(1) includes software validated, installed, or authorized by the sponsor as a device or in a device; (2) has the ability to connect to the internet; and (3) contains any such technological characteristics validated, installed, or authorized by the sponsor that could be vulnerable to cybersecurity threats" (see Section VII.B for more information on the term "cyber device"). The recommendations in this guidance are intended to help manufacturers meet their obligations under section 524B of the FD&C Act.

# III. 배경

FDA는 의료기기 사이버보안이 의료 시설, 환자, 의료 서비스 제공자, 의료기기 제조업체를 포함한 의료기기 시스템의 사용 환경 전반에 걸친 이해관계자들 간의 공동 책임임을 인식하고 있습니다. 본 가이던스의 목적상, "의료기기 시스템"이라는 용어는 기기 및 이와 연결된 시스템(예: 의료 시설 네트워크, 다른 기기, 소프트웨어 업데이트 서버 등)을 포함합니다.

의료 분야 전반의 사건들은 환자 안전에 대한 사이버보안의 중요성을 강조해 왔습니다. WannaCry[^5] 랜섬웨어[^6]는 전 세계의 병원 시스템과 의료기기에 영향을 미쳤습니다. URGENT/11[^7] 및 SweynTooth[^8]와 같이 일반적으로 사용되는 타사 구성요소에서 식별된 취약점은 다양한 임상 전문 분야에서 사용되는 광범위한 기기에 걸쳐 잠재적인 안전 문제를 야기했습니다. 2020년 독일 병원에 대한 랜섬웨어 공격은 사이버보안 공격으로 인해 환자를 다른 병원으로 이송해야 했을 때 지연된 환자 치료로 인한 잠재적 영향을 강조했습니다.[^9]

FDA는 2014년 시판 전 기대사항을 다루는 최종 사이버보안 가이던스 "의료기기의 사이버보안 관리를 위한 시판 전 제출 내용"과 2016년 보완적인 가이던스인 "[의료기기의 사이버보안에 대한 시판 후 관리](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/postmarket-management-cybersecurity-medical-devices)"(이하 "시판 후 사이버보안 가이던스"라 함)를 발행했습니다. 그러나 빠르게 진화하는 환경, 새로운 위협에 대한 이해 증가, 그리고 전체 제품 수명주기(TPLC) 전반에 걸친 완화조치의 효과적인 배치 필요성은 기기 사이버보안에 대한 업데이트되고 반복적인 접근 방식을 필요로 합니다. 2014년 가이던스 이후의 변경사항은 기기가 안전하게 설계되고, TPLC 전반에 걸쳐 새로운 사이버보안 위험을 완화할 수 있도록 설계되며, 사이버보안 우려사항을 해결하기 위한 시판 전 제출 정보에 대한 FDA의 권장사항을 더 명확하게 설명하는 것의 중요성을 더욱 강조하기 위한 것입니다.

기기에 대한 이러한 TPLC 고려사항을 달성할 수 있는 한 가지 방법은 보안 제품 개발 프레임워크(SPDF)의 구현 및 채택입니다.[^10] 본 가이던스에 설명된 SPDF는 기기 수명주기 전반에 걸쳐 제품의 취약점 수와 심각도를 줄이는 일련의 프로세스입니다. 이러한 프레임워크의 예는 의료기기 분야를 포함한 많은 분야에 존재합니다.

기기 제조업체에 대한 위험 관리는 제조하는 기기가 안전하고 효과적임을 보장하기 위해 제품 수명주기 전반에 걸쳐 위험을 식별, 분석, 평가, 통제 및 모니터링하는 필수적인 체계적 관행입니다. 21 CFR Part 820의 품질 시스템(QS) 규정은 21 CFR 820.30(g)에서 위험 관리 활동을 명시적으로 다루고 있습니다. FDA는 21 CFR 820에 따른 품질 시스템(QS) 규정의 기기 현행 우수 제조 관리 기준(CGMP) 요구사항을 수정하여 전 세계 많은 다른 규제 당국이 사용하는 의료기기 품질 관리 시스템에 대한 국제 합의 표준과 더 밀접하게 일치시키는 최종 규칙[^11]을 발행했으며, 최종 규칙은 그 요구사항 전반에 걸쳐 위험 관리를 통합합니다.[^12]

본 가이던스에 포함된 권장사항은 FDA의 [시판 후 사이버보안 가이던스](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/postmarket-management-cybersecurity-medical-devices) 및 "[기기 소프트웨어 기능에 대한 시판 전 제출 내용](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/content-premarket-submissions-device-software-functions)"(이하 "시판 전 소프트웨어 가이던스"라 함)을 보완하기 위한 것입니다. 본 가이던스는 2014년 최종 가이던스 "의료기기의 사이버보안 관리를 위한 시판 전 제출 내용"을 대체합니다.

본 가이던스의 권장사항은 또한 2020년 3월에 발행된 국제 의료기기 규제 당국 포럼(IMDRF) 최종 가이던스 "[의료기기 사이버보안을 위한 원칙 및 관행](http://www.imdrf.org/documents/documents.asp)"의 의료기기 사이버보안에 대한 시판 전 고려사항 섹션의 권장사항과 일반적으로 일치하거나 확장합니다.

또한, 2022년 12월 29일에 제정된 2022년 식품 및 의약품 종합 개혁법("FDORA")의 섹션 3305는 FD&C법에 524B조 "의료기기의 사이버보안 보장"을 추가했습니다. 2023년 3월 29일부터 "사이버 기기"에 대한 시판 전 제출과 관련하여, 524B(a)조는 스폰서가 기기가 524B(b)조에 따른 사이버보안 요구사항을 충족함을 보장하는 정보를 포함해야 한다고 규정합니다.[^13] FD&C법 524B(a)조에 따라, 524B(c)조에 정의된 사이버 기기의 정의를 충족하는 기기에 대해 510(k), PMA, PDP, De Novo 또는 HDE를 제출하는 자는 사이버 기기가 524B(b)조에 따른 사이버보안 요구사항을 충족함을 보장하는 정보를 제출해야 합니다.[^14] FD&C법 524B(c)조는 "사이버 기기"를 "(1) 스폰서에 의해 기기로서 또는 기기 내에서 검증, 설치 또는 승인된 소프트웨어를 포함하고; (2) 인터넷에 연결할 수 있는 능력이 있으며; (3) 사이버보안 위협에 취약할 수 있는 스폰서에 의해 검증, 설치 또는 승인된 기술적 특성을 포함하는" 기기로 정의합니다("사이버 기기"라는 용어에 대한 자세한 정보는 섹션 VII.B 참조). 본 가이던스의 권장사항은 제조업체가 FD&C법 524B조에 따른 의무를 충족하도록 돕기 위한 것입니다.

[^5]: For more information on the WannaCry Ransomware attack, see [Indicators Associated With WannaCry Ransomware](https://www.cisa.gov/news-events/alerts/2017/05/12/indicators-associated-wannacry-ransomware). WannaCry 랜섬웨어 공격에 대한 자세한 정보는 [WannaCry 랜섬웨어 관련 지표](https://www.cisa.gov/news-events/alerts/2017/05/12/indicators-associated-wannacry-ransomware)를 참조하십시오.

[^6]: For the purposes of this guidance, we consider "ransomware" an ever-evolving form of malware designed to encrypt files on a device, rendering any files and the systems that rely on them unusable. This definition is cited from the Cybersecurity & Infrastructure Security Agency's (CISA's) webpage [Ransomware 101](https://www.cisa.gov/stopransomware). 본 가이던스의 목적상, "랜섬웨어"는 기기의 파일을 암호화하여 모든 파일과 이에 의존하는 시스템을 사용할 수 없게 만들도록 설계된 끊임없이 진화하는 형태의 악성 소프트웨어로 간주합니다. 이 정의는 사이버보안 및 인프라 보안국(CISA)의 웹페이지 [랜섬웨어 101](https://www.cisa.gov/stopransomware)에서 인용되었습니다.

[^7]: For more information, see [FDA's Cybersecurity webpage](https://www.fda.gov/medical-devices/digital-health-center-excellence/cybersecurity). 자세한 정보는 [FDA의 사이버보안 웹페이지](https://www.fda.gov/medical-devices/digital-health-center-excellence/cybersecurity)를 참조하십시오.

[^8]: For more information, see FDA's [SweynTooth Cybersecurity Vulnerabilities May Affect Certain Medical Devices: FDA Safety Communication](https://www.fda.gov/medical-devices/safety-communications/sweyntooth-cybersecurity-vulnerabilities-may-affect-certain-medical-devices-fda-safety-communication). 자세한 정보는 FDA의 [SweynTooth 사이버보안 취약점이 특정 의료기기에 영향을 미칠 수 있음: FDA 안전성 통신](https://www.fda.gov/medical-devices/safety-communications/sweyntooth-cybersecurity-vulnerabilities-may-affect-certain-medical-devices-fda-safety-communication)을 참조하십시오.

[^9]: For more information on the German hospital ransomware attack, see [The untold story of a cyberattack, a hospital and a dying woman](https://www.wired.com/story/ransomware-hospital-death-germany/). 독일 병원 랜섬웨어 공격에 대한 자세한 정보는 [사이버 공격, 병원, 그리고 죽어가는 여성의 알려지지 않은 이야기](https://www.wired.com/story/ransomware-hospital-death-germany/)를 참조하십시오.

[^10]: See Appendix 5, Terminology. 부록 5, 용어를 참조하십시오.

[^11]: See [89 FR 7496](https://www.federalregister.gov/documents/2024/02/02/2024-02011/medical-devices-quality-system-regulation-amendments). [89 FR 7496](https://www.federalregister.gov/documents/2024/02/02/2024-02011/medical-devices-quality-system-regulation-amendments)을 참조하십시오.

[^12]: See 89 FR 7496 at 7505. On February 2, 2024, FDA issued a final rule amending the device Quality System Regulation, 21 CFR Part 820, to align more closely with international consensus standards for devices (89 FR 7496). This final rule will take effect on February 2, 2026. Once in effect, this rule will withdraw the majority of the current requirements in Part 820 and instead incorporate by reference the 2016 edition of the International Organization for Standardization (ISO) 13485, Medical devices - Quality management systems – Requirements for regulatory purposes, in Part 820. As stated in the final rule, the requirements in ISO 13485 are, when taken in totality, substantially similar to the requirements of the current Part 820, providing a similar level of assurance in a firm's quality management system and ability to consistently manufacture devices that are safe and effective and otherwise in compliance with the FD&C Act. When the final rule takes effect, FDA will also update this guidance, including the references to provisions in Part 820 in this guidance to be consistent with the rule. 89 FR 7496의 7505를 참조하십시오. 2024년 2월 2일, FDA는 기기에 대한 국제 합의 표준과 더 밀접하게 일치하도록 기기 품질 시스템 규정인 21 CFR Part 820을 수정하는 최종 규칙을 발행했습니다(89 FR 7496). 이 최종 규칙은 2026년 2월 2일에 발효됩니다. 발효되면, 이 규칙은 Part 820의 현재 요구사항의 대부분을 철회하고 대신 국제표준화기구(ISO) 13485, 의료기기 - 품질 관리 시스템 - 규제 목적을 위한 요구사항의 2016년 판을 Part 820에 참조로 통합합니다. 최종 규칙에 명시된 바와 같이, ISO 13485의 요구사항은 전체적으로 볼 때 현재 Part 820의 요구사항과 실질적으로 유사하며, 기업의 품질 관리 시스템과 안전하고 효과적이며 FD&C법을 준수하는 기기를 일관되게 제조할 수 있는 능력에 대해 유사한 수준의 보증을 제공합니다. 최종 규칙이 발효되면, FDA는 규칙과 일관되도록 본 가이던스의 Part 820 조항에 대한 참조를 포함하여 본 가이던스도 업데이트할 것입니다.

[^13]: While section 524B(b)(4) of the FD&C Act authorizes FDA to promulgate additional cybersecurity requirements via regulation, FDA is not required to promulgate a regulation to elaborate on the new requirements specified in section 524B of the FD&C Act. FD&C법 524B(b)(4)조는 FDA가 규정을 통해 추가적인 사이버보안 요구사항을 공포할 수 있는 권한을 부여하지만, FDA는 FD&C법 524B조에 명시된 새로운 요구사항을 상세히 설명하기 위해 규정을 공포할 필요는 없습니다.

[^14]: In addition to the cybersecurity requirements set forth in section 524B(b) of the FD&C Act, section 524B(b)(4) of the FD&C Act requires cyber device manufacturers to comply with any other such requirements FDA sets forth in regulations "to demonstrate reasonable assurance that the device and related systems are cybersecure." FD&C법 524B(b)조에 명시된 사이버보안 요구사항 외에도, FD&C법 524B(b)(4)조는 사이버 기기 제조업체가 "기기 및 관련 시스템이 사이버 보안이 확보되었다는 합리적인 보증을 입증하기 위해" FDA가 규정으로 정하는 기타 요구사항을 준수하도록 요구합니다.

# IV. General Principles
This section provides general principles for device cybersecurity relevant to device manufacturers. The principles in this guidance are important to the improvement of device cybersecurity and, when followed, are expected to have a positive impact on the safety and effectiveness of the device. The recommendations in this guidance cover all relevant cybersecurity considerations that may affect device safety and effectiveness, including but not limited to software, hardware, and firmware.

## A. Cybersecurity is Part of Device Safety and the Quality System Regulation
Device manufacturers must establish and follow quality systems to help ensure that their products consistently meet applicable requirements and specifications. The quality systems requirements are found in the QS regulation in 21 CFR Part 820. Depending on the device, QS requirements may be relevant at the premarket stage, postmarket stage,[^15] or both.

In the premarket context, in order to demonstrate a reasonable assurance of safety and effectiveness for certain devices with cybersecurity risks, documentation outputs related to the ongoing requirements of the QS regulation may be one source of documentation to include as part of the premarket submission.[^16] This guidance is intended to explain how such documentation that may be relevant for QS regulation compliance can also be used to show how a sponsor or manufacturer is addressing cybersecurity considerations relevant to a device. For example, 21 CFR 820.30(a) requires that for all classes of devices automated with software, a manufacturer must establish and maintain procedures to control the design of the device in order to ensure that specified design requirements are met ("design controls"). As part of design controls, a manufacturer must "establish and maintain procedures for validating the device design," which "shall include software validation and risk analysis, where appropriate" (21 CFR 820.30(g)). As part of the software validation and risk analysis required by 21 CFR 820.30(g), software device manufacturers may need to establish cybersecurity risk management and validation processes, where appropriate. See also FDA's guidance titled "[Content of Premarket Submissions for Device Software Functions](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/guidance-content-premarket-submissions-software-contained-medical-devices)."

Software validation and risk management are key elements of cybersecurity analyses and demonstrating whether a device has a reasonable assurance of safety and effectiveness. FDA requires manufacturers to implement development processes that account for and address software risks throughout the design and development process as part of design controls, as discussed in FDA's regulations regarding design control, which may include cybersecurity considerations.[^17] For example, these processes should address the identification of security risks, the design requirements for how the risks will be controlled, and the evidence that the controls function as designed and are effective in their environment of use for ensuring adequate security.

### 1. A Secure Product Development Framework (SPDF) may be one way to satisfy the QS regulation
Cybersecurity threats have the potential to exploit one or more vulnerabilities that could lead to patient harm. The greater the number of vulnerabilities that exist and/or are identified over time in a system in which a device operates, the easier a threat can compromise the safety and effectiveness of the medical device. An SPDF is a set of processes that help identify and reduce the number and severity of vulnerabilities in products. An SPDF encompasses all aspects of a product's lifecycle, including design, development, release, support, and decommission. Additionally, using SPDF processes during device design may prevent the need to re-engineer the device when connectivity-based features are added after marketing and distribution, or when vulnerabilities resulting in uncontrolled risks are discovered. An SPDF can be integrated with existing processes for product and software development, risk management, and the quality system at large.

Using an SPDF is one approach to help ensure that the QS regulation is met. Because of its benefits in helping comply with the QS regulation and cybersecurity, FDA encourages manufacturers to use an SPDF, but other approaches might also satisfy the QS regulation.

## B. Designing for Security
When reviewing premarket submissions, FDA intends to assess device cybersecurity based on a number of factors, including, but not limited to, the device's ability to provide and implement the security objectives below throughout the device architecture. The security objectives below generally may apply broadly to devices within the scope of this guidance, including, but not limited to, devices containing artificial intelligence (AI) and cloud-based services.

**Security Objectives:**
- Authenticity, which includes integrity;
- Authorization;
- Availability;
- Confidentiality; and
- Secure and timely updatability and patchability.

Premarket submissions should include information that describes how the above security objectives are addressed by and integrated into the device design. The extent to which security requirements, architecture, supply chain, and implementation are needed to meet these objectives will depend on but may not be limited to:

- The device's intended use, indications for use, and reasonably foreseeable misuse;
- The presence and functionality of its electronic data interfaces;
- Its intended and actual environment of use;[^18]
- The risks presented by cybersecurity vulnerabilities;
- The exploitability of the vulnerabilities; and
- The risk of patient harm due to vulnerability exploitation.

SPDF processes aim to reduce the number and severity of vulnerabilities and thereby reduce the exploitability of a medical device system and the associated risk of patient harm. Because exploitation of known vulnerabilities or weak cybersecurity controls should be considered reasonably foreseeable failure modes for medical device systems, these factors should be addressed in the device design.[^19] One of the key benefits of using an SPDF is that a medical device system is more likely to be secure by design, such that the device is designed from the outset to be secure within its system and/or network of use throughout the device lifecycle.

## C. Transparency
A lack of cybersecurity information, such as information necessary to integrate the device into the use environment, as well as information needed by users to maintain the medical device system's cybersecurity over the device lifecycle, has the potential to affect the safety and effectiveness of a device. In order to address these concerns, it is important for device users to have access to information pertaining to the device's cybersecurity controls, potential risks to the medical device system, and other relevant information. For example:

- A failure to disclose all of the communication interfaces or third-party software could fail to convey potential sources of risks;
- Insufficient information pertaining to whether a device has known but not disclosed cybersecurity vulnerabilities or risks may be relevant to determining whether a device's safety or effectiveness could be degraded; and/or
- Labeling that does not include sufficient information to explain how to securely configure or update the device may limit the ability of end users to appropriately manage and protect the medical device system.

This information and other relevant information are important in helping users understand a medical device system's resilience to cybersecurity threats, the threats that it may be exposed to, and how those threats may be prevented or mitigated. Without it, cybersecurity risks could be undisclosed, inappropriately identified, or inappropriately responded to, among other potential impacts, which could lead to compromises in device safety and effectiveness.

FDA believes that the cybersecurity information discussed in this guidance is important for the safe and effective use of devices and should be included in device labeling, as discussed below in Section VI.

## D. Submission Documentation
Device cybersecurity design and documentation are expected to scale with the cybersecurity risk of that device. Manufacturers should take into account the larger system in which the device may be used. For example, a cybersecurity risk assessment performed on a simple, non-connected thermometer may conclude that the risks are limited, and therefore such a device needs only a limited security architecture (i.e., addressing only device hardware and software) and few security controls based on the technical characteristics and design of the device. However, if a thermometer is used in a safety-critical control loop, or is connected to networks or other devices, then the cybersecurity risks for the device are considered to be greater and more substantial design controls should result. Submitters should consider including in premarket submissions to FDA documentation generated from those design controls used during the development of a device with cybersecurity risks as a way to demonstrate reasonable assurance of safety and effectiveness. This guidance identifies the cybersecurity information FDA recommends to help support a premarket submission for devices within the scope of this guidance, including but not limited to cyber devices.[^20]

As cybersecurity is part of device safety and effectiveness, cybersecurity controls established during premarket development should also take into consideration the intended and actual use environment (see Section IV.B). Cybersecurity risks evolve over time and as a result, the effectiveness of cybersecurity controls may degrade as new risks, threats, and attack methods emerge. In the 510(k) context, FDA evaluates the cybersecurity information submitted and the protections the cybersecurity controls provide in demonstrating substantial equivalence (see section 513(i) of the FD&C Act and 21 CFR 807.100(b)(2)(ii)(B)).[^21]

In addition, inadequate cybersecurity information in the device labeling may cause a device to be misbranded under section 502(f) of the FD&C Act if its labeling does not bear adequate directions for use or under section 502(j) of the FD&C Act because it is dangerous to health when used in the manner recommended or suggested in the labeling, among other possible violations. For cyber devices, failure to comply with any requirement under section 524B(b)(2) of the FD&C Act (relating to ensuring device cybersecurity) is considered a prohibited act under section 301(q) of the FD&C Act.

This guidance recommends cybersecurity information be included in submissions based on cybersecurity risks, not on any other criteria or level of risk/concern established in a separate FDA guidance (e.g., the risk-based approach in the [Premarket Software Guidance](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/guidance-content-premarket-submissions-software-contained-medical-devices) to help determine a device's Documentation Level). For example, a device that is determined to have a greater software risk may only have a small cybersecurity risk due to how the device is designed. Likewise, a device with a smaller software risk may have a significant cybersecurity risk. Therefore, the recommendations in this guidance regarding information to be submitted to FDA are intended to address the cybersecurity risk, as assessed by the cybersecurity risk assessment during development of a device, and are expected to scale based on the cybersecurity risk. The premarket submission documentation recommendations throughout this guidance apply to all premarket submissions and are intended to be used to support FDA's assessment of a device's safety and effectiveness.

For cyber devices, some of the information recommended in this guidance may help manufacturers meet their obligations for what is required to be in premarket submissions under section 524B of the FD&C Act.

# IV. 일반 원칙

본 섹션은 기기 제조업체와 관련된 기기 사이버보안에 대한 일반 원칙을 제공합니다. 본 가이던스의 원칙은 기기 사이버보안 개선에 중요하며, 준수될 경우 기기의 안전성과 효과성에 긍정적인 영향을 미칠 것으로 예상됩니다. 본 가이던스의 권장사항은 소프트웨어, 하드웨어 및 펌웨어를 포함하되 이에 국한되지 않는 기기의 안전성과 효과성에 영향을 미칠 수 있는 모든 관련 사이버보안 고려사항을 다룹니다.

## A. 사이버보안은 기기 안전성 및 품질 시스템 규정의 일부임

기기 제조업체는 제품이 적용 가능한 요구사항 및 사양을 지속적으로 충족하도록 돕기 위해 품질 시스템을 수립하고 따라야 합니다. 품질 시스템 요구사항은 21 CFR Part 820의 QS 규정에 명시되어 있습니다. 기기에 따라 QS 요구사항은 시판 전 단계, 시판 후 단계[^15] 또는 둘 다에 관련될 수 있습니다.

시판 전 맥락에서, 사이버보안 위험이 있는 특정 기기에 대한 안전성과 효과성의 합리적인 보증을 입증하기 위해, QS 규정의 지속적인 요구사항과 관련된 문서 산출물이 시판 전 제출의 일부로 포함될 문서의 한 출처가 될 수 있습니다.[^16] 본 가이던스는 QS 규정 준수와 관련될 수 있는 이러한 문서가 스폰서 또는 제조업체가 기기와 관련된 사이버보안 고려사항을 어떻게 다루고 있는지 보여주는 데 어떻게 사용될 수 있는지 설명하기 위한 것입니다. 예를 들어, 21 CFR 820.30(a)는 소프트웨어로 자동화된 모든 등급의 기기에 대해 제조업체가 명시된 설계 요구사항이 충족되도록 기기의 설계를 통제하는 절차를 수립하고 유지해야 한다고 요구합니다("설계 통제"). 설계 통제의 일부로, 제조업체는 "기기 설계를 검증하기 위한 절차를 수립하고 유지해야" 하며, 이는 "적절한 경우 소프트웨어 검증 및 위험 분석을 포함해야" 합니다(21 CFR 820.30(g)). 21 CFR 820.30(g)에서 요구하는 소프트웨어 검증 및 위험 분석의 일부로, 소프트웨어 기기 제조업체는 적절한 경우 사이버보안 위험 관리 및 검증 프로세스를 수립해야 할 수 있습니다. FDA의 "[기기 소프트웨어 기능에 대한 시판 전 제출 내용](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/guidance-content-premarket-submissions-software-contained-medical-devices)" 제목의 가이던스도 참조하십시오.

소프트웨어 검증 및 위험 관리는 사이버보안 분석의 핵심 요소이며 기기가 안전성과 효과성의 합리적인 보증을 가지고 있는지 입증하는 데 중요합니다. FDA는 제조업체가 설계 통제의 일부로 설계 및 개발 프로세스 전반에 걸쳐 소프트웨어 위험을 고려하고 해결하는 개발 프로세스를 구현하도록 요구하며, 이는 사이버보안 고려사항을 포함할 수 있습니다.[^17] 예를 들어, 이러한 프로세스는 보안 위험의 식별, 위험이 통제되는 방법에 대한 설계 요구사항, 그리고 통제가 설계된 대로 기능하고 적절한 보안을 보장하기 위한 사용 환경에서 효과적이라는 증거를 다루어야 합니다.

### 1. 보안 제품 개발 프레임워크(SPDF)는 QS 규정을 충족하는 한 가지 방법일 수 있음

사이버보안 위협은 환자에게 해를 끼칠 수 있는 하나 이상의 취약점을 악용할 가능성이 있습니다. 기기가 작동하는 시스템에 존재하거나 시간이 지남에 따라 식별되는 취약점의 수가 많을수록 위협이 의료기기의 안전성과 효과성을 손상시키기가 더 쉬워집니다. SPDF는 제품의 취약점 수와 심각도를 식별하고 줄이는 데 도움이 되는 일련의 프로세스입니다. SPDF는 설계, 개발, 출시, 지원 및 폐기를 포함한 제품 수명주기의 모든 측면을 포괄합니다. 또한, 기기 설계 중에 SPDF 프로세스를 사용하면 마케팅 및 유통 후 연결성 기반 기능이 추가되거나 통제되지 않은 위험을 초래하는 취약점이 발견될 때 기기를 재설계할 필요성을 방지할 수 있습니다. SPDF는 제품 및 소프트웨어 개발, 위험 관리, 그리고 전체 품질 시스템을 위한 기존 프로세스와 통합될 수 있습니다.

SPDF를 사용하는 것은 QS 규정이 충족되도록 돕는 한 가지 접근 방식입니다. QS 규정 및 사이버보안 준수를 돕는 이점 때문에, FDA는 제조업체가 SPDF를 사용할 것을 권장하지만, 다른 접근 방식도 QS 규정을 충족할 수 있습니다.

## B. 보안을 위한 설계

시판 전 제출을 검토할 때, FDA는 기기 아키텍처 전반에 걸쳐 아래의 보안 목표를 제공하고 구현하는 기기의 능력을 포함하되 이에 국한되지 않는 여러 요소를 기반으로 기기 사이버보안을 평가할 것입니다. 아래의 보안 목표는 일반적으로 인공지능(AI) 및 클라우드 기반 서비스를 포함하는 기기를 포함하되 이에 국한되지 않는 본 가이던스의 범위 내 기기에 광범위하게 적용될 수 있습니다.

**보안 목표:**
- 무결성을 포함하는 진정성(Authenticity);
- 권한 부여(Authorization);
- 가용성(Availability);
- 기밀성(Confidentiality); 그리고
- 안전하고 시기적절한 업데이트 가능성 및 패치 가능성.

시판 전 제출에는 위의 보안 목표가 기기 설계에 의해 어떻게 다루어지고 통합되는지를 설명하는 정보가 포함되어야 합니다. 이러한 목표를 충족하기 위해 필요한 보안 요구사항, 아키텍처, 공급망 및 구현의 범위는 다음 사항에 따라 달라지지만 이에 국한되지 않을 수 있습니다:

- 기기의 의도된 사용, 사용 적응증 및 합리적으로 예견 가능한 오용;
- 전자 데이터 인터페이스의 존재 및 기능;
- 의도된 및 실제 사용 환경;[^18]
- 사이버보안 취약점이 제시하는 위험;
- 취약점의 악용 가능성; 그리고
- 취약점 악용으로 인한 환자 피해 위험.

SPDF 프로세스는 취약점의 수와 심각도를 줄이고 이로써 의료기기 시스템의 악용 가능성과 관련된 환자 피해 위험을 줄이는 것을 목표로 합니다. 알려진 취약점 또는 약한 사이버보안 통제의 악용은 의료기기 시스템에 대해 합리적으로 예견 가능한 고장 모드로 간주되어야 하므로, 이러한 요소는 기기 설계에서 다루어져야 합니다.[^19] SPDF를 사용하는 주요 이점 중 하나는 의료기기 시스템이 기기 수명주기 전반에 걸쳐 시스템 및/또는 사용 네트워크 내에서 안전하도록 처음부터 설계되는 보안을 고려한 설계(secure by design)일 가능성이 더 높다는 것입니다.

## C. 투명성

기기를 사용 환경에 통합하는 데 필요한 정보와 기기 수명주기 동안 의료기기 시스템의 사이버보안을 유지하기 위해 사용자가 필요로 하는 정보와 같은 사이버보안 정보의 부족은 기기의 안전성과 효과성에 영향을 미칠 가능성이 있습니다. 이러한 우려사항을 해결하기 위해, 기기 사용자가 기기의 사이버보안 통제, 의료기기 시스템에 대한 잠재적 위험 및 기타 관련 정보에 대한 정보에 접근할 수 있는 것이 중요합니다. 예를 들어:

- 모든 통신 인터페이스 또는 타사 소프트웨어를 공개하지 않으면 잠재적 위험 출처를 전달하지 못할 수 있습니다;
- 기기가 알려졌지만 공개되지 않은 사이버보안 취약점 또는 위험을 가지고 있는지에 대한 불충분한 정보는 기기의 안전성 또는 효과성이 저하될 수 있는지 여부를 결정하는 데 관련될 수 있습니다; 그리고/또는
- 기기를 안전하게 구성하거나 업데이트하는 방법을 설명하는 충분한 정보가 포함되지 않은 라벨링은 최종 사용자가 의료기기 시스템을 적절하게 관리하고 보호할 수 있는 능력을 제한할 수 있습니다.

이 정보 및 기타 관련 정보는 사용자가 의료기기 시스템의 사이버보안 위협에 대한 복원력, 노출될 수 있는 위협, 그리고 이러한 위협이 어떻게 예방되거나 완화될 수 있는지를 이해하는 데 중요합니다. 이것이 없으면 사이버보안 위험이 공개되지 않거나, 부적절하게 식별되거나, 부적절하게 대응될 수 있으며, 이는 기기의 안전성과 효과성의 손상을 초래할 수 있는 기타 잠재적 영향 중 하나입니다.

FDA는 본 가이던스에서 논의된 사이버보안 정보가 기기의 안전하고 효과적인 사용에 중요하며 아래 섹션 VI에서 논의된 바와 같이 기기 라벨링에 포함되어야 한다고 믿습니다.

## D. 제출 문서

기기 사이버보안 설계 및 문서화는 해당 기기의 사이버보안 위험에 따라 확장될 것으로 예상됩니다. 제조업체는 기기가 사용될 수 있는 더 큰 시스템을 고려해야 합니다. 예를 들어, 간단한 비연결 온도계에 대해 수행된 사이버보안 위험 평가는 위험이 제한적이라고 결론지을 수 있으며, 따라서 이러한 기기는 기기의 기술적 특성 및 설계를 기반으로 제한된 보안 아키텍처(즉, 기기 하드웨어 및 소프트웨어만 다룸)와 몇 가지 보안 통제만 필요로 합니다. 그러나 온도계가 안전 중요 제어 루프에서 사용되거나 네트워크 또는 다른 기기에 연결된 경우, 기기에 대한 사이버보안 위험은 더 크다고 간주되며 더 실질적인 설계 통제가 결과되어야 합니다. 제출자는 안전성과 효과성의 합리적인 보증을 입증하는 방법으로 사이버보안 위험이 있는 기기 개발 중에 사용된 설계 통제로부터 생성된 문서를 FDA에 대한 시판 전 제출에 포함하는 것을 고려해야 합니다. 본 가이던스는 사이버 기기를 포함하되 이에 국한되지 않는 본 가이던스의 범위 내 기기에 대한 시판 전 제출을 지원하기 위해 FDA가 권장하는 사이버보안 정보를 식별합니다.[^20]

사이버보안은 기기 안전성 및 효과성의 일부이므로, 시판 전 개발 중에 수립된 사이버보안 통제는 의도된 및 실제 사용 환경도 고려해야 합니다(섹션 IV.B 참조). 사이버보안 위험은 시간이 지남에 따라 진화하며, 그 결과 새로운 위험, 위협 및 공격 방법이 나타남에 따라 사이버보안 통제의 효과성이 저하될 수 있습니다. 510(k) 맥락에서, FDA는 제출된 사이버보안 정보와 사이버보안 통제가 실질적 동등성을 입증하는 데 제공하는 보호를 평가합니다(FD&C법 513(i)조 및 21 CFR 807.100(b)(2)(ii)(B) 참조).[^21]

또한, 기기 라벨링의 부적절한 사이버보안 정보는 라벨링에 적절한 사용 지침이 없는 경우 FD&C법 502(f)조에 따라 또는 라벨링에서 권장되거나 제안된 방식으로 사용될 때 건강에 위험한 경우 FD&C법 502(j)조에 따라 기기가 부정 표시(misbranded)되게 할 수 있으며, 기타 가능한 위반 중에서도 그러합니다. 사이버 기기의 경우, FD&C법 524B(b)(2)조의 요구사항(기기 사이버보안 보장과 관련)을 준수하지 않는 것은 FD&C법 301(q)조에 따른 금지 행위로 간주됩니다.

본 가이던스는 별도의 FDA 가이던스에서 설정된 다른 기준 또는 위험/우려 수준(예: [시판 전 소프트웨어 가이던스](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/guidance-content-premarket-submissions-software-contained-medical-devices)의 위험 기반 접근 방식으로 기기의 문서화 수준 결정을 돕는 것)이 아닌 사이버보안 위험을 기반으로 제출에 포함될 사이버보안 정보를 권장합니다. 예를 들어, 더 큰 소프트웨어 위험이 있다고 결정된 기기는 기기가 설계된 방식으로 인해 작은 사이버보안 위험만 가질 수 있습니다. 마찬가지로, 더 작은 소프트웨어 위험이 있는 기기는 상당한 사이버보안 위험을 가질 수 있습니다. 따라서, FDA에 제출될 정보에 관한 본 가이던스의 권장사항은 기기 개발 중 사이버보안 위험 평가에 의해 평가된 사이버보안 위험을 다루기 위한 것이며, 사이버보안 위험에 따라 확장될 것으로 예상됩니다. 본 가이던스 전반의 시판 전 제출 문서 권장사항은 모든 시판 전 제출에 적용되며, 기기의 안전성과 효과성에 대한 FDA의 평가를 지원하는 데 사용되도록 의도되었습니다.

사이버 기기의 경우, 본 가이던스에서 권장되는 정보 중 일부는 제조업체가 FD&C법 524B조에 따라 시판 전 제출에 포함되어야 하는 사항에 대한 의무를 충족하는 데 도움이 될 수 있습니다.

[^15]: In the postmarket context, design controls may also be important to ensure medical device cybersecurity and maintain medical device safety and effectiveness. FDA recommends that device manufacturers implement comprehensive cybersecurity risk management programs and documentation consistent with the QS regulation, including but not limited to complaint handling (21 CFR 820.198), quality audit (21 CFR 820.22), corrective and preventive action (21 CFR 820.100), software validation and risk analysis (21 CFR 820.30(g)), and servicing (21 CFR 820.200). 시판 후 맥락에서, 설계 통제는 의료기기 사이버보안을 보장하고 의료기기 안전성과 효과성을 유지하는 데도 중요할 수 있습니다. FDA는 기기 제조업체가 불만 처리(21 CFR 820.198), 품질 감사(21 CFR 820.22), 시정 및 예방 조치(21 CFR 820.100), 소프트웨어 검증 및 위험 분석(21 CFR 820.30(g)), 그리고 서비스 제공(21 CFR 820.200)을 포함하되 이에 국한되지 않는 QS 규정과 일치하는 포괄적인 사이버보안 위험 관리 프로그램 및 문서를 구현할 것을 권장합니다.

[^16]: The recommendations in this guidance are not intended to suggest that FDA will evaluate an applicant's compliance with the QS regulation as part of its premarket submission under section 510(k) of the FD&C Act in our determination of a device's substantial equivalence, as this is not a requirement for such decision under section 513(i) of the FD&C Act. This guidance is intended to explain how FDA evaluates the performance of device cybersecurity and the cybersecurity outputs of activities that are part and parcel of QS regulation compliance, and explain how the QS regulation can be leveraged to demonstrate these performance outputs. 본 가이던스의 권장사항은 FDA가 기기의 실질적 동등성 결정에서 FD&C법 510(k)조에 따른 시판 전 제출의 일부로 신청자의 QS 규정 준수를 평가할 것임을 시사하기 위한 것이 아니며, 이는 FD&C법 513(i)조에 따른 그러한 결정에 대한 요구사항이 아닙니다. 본 가이던스는 FDA가 기기 사이버보안의 성능과 QS 규정 준수의 일부인 활동의 사이버보안 산출물을 어떻게 평가하는지 설명하고, QS 규정이 이러한 성능 산출물을 입증하기 위해 어떻게 활용될 수 있는지 설명하기 위한 것입니다.

[^17]: See 21 CFR 820.30. 21 CFR 820.30을 참조하십시오.

[^18]: Manufacturers may not be able to account for all potential environments of use, but should consider the range of use environments and ensure the risks are identified and controlled for the worst-case environments of use (e.g., least secure expected network configuration(s)). 제조업체는 모든 잠재적 사용 환경을 설명할 수 없을 수 있지만, 사용 환경의 범위를 고려하고 최악의 사용 환경(예: 가장 안전하지 않은 예상 네트워크 구성)에 대해 위험이 식별되고 통제되도록 보장해야 합니다.

[^19]: For more information on reasonably foreseeable misuse, see the IMDRF final guidance "[Principles and Practices for Medical Device Cybersecurity](https://www.imdrf.org/sites/default/files/docs/imdrf/final/technical/imdrf-tech-200318-pp-mdc-n60.pdf)." 합리적으로 예견 가능한 오용에 대한 자세한 정보는 IMDRF 최종 가이던스 "[의료기기 사이버보안을 위한 원칙 및 관행](https://www.imdrf.org/sites/default/files/docs/imdrf/final/technical/imdrf-tech-200318-pp-mdc-n60.pdf)"을 참조하십시오.

[^20]: As previously discussed, section 524B of the FD&C Act requires the submission of certain documentation for cyber devices. See Section VII of this guidance for more information on cyber devices. 앞서 논의한 바와 같이, FD&C법 524B조는 사이버 기기에 대한 특정 문서의 제출을 요구합니다. 사이버 기기에 대한 자세한 정보는 본 가이던스의 섹션 VII을 참조하십시오.

[^21]: For more information regarding the substantial equivalence review standard, please refer to FDA's guidance, "[The 510(k) Program: Evaluating Substantial Equivalence in Premarket Notifications [510(k)]](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/510k-program-evaluating-substantial-equivalence-premarket-notifications-510k)." 실질적 동등성 검토 기준에 관한 자세한 정보는 FDA의 가이던스 "[510(k) 프로그램: 시판 전 신고[510(k)]에서 실질적 동등성 평가](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/510k-program-evaluating-substantial-equivalence-premarket-notifications-510k)"를 참조하십시오.

# V. Using an SPDF to Manage Cybersecurity Risks
The documentation recommended in this guidance is based on FDA's experience evaluating the safety and effectiveness of devices with cybersecurity vulnerabilities. However, sponsors may use alternative approaches and provide different documentation so long as their approach and documentation satisfy premarket submission requirements in applicable statutory provisions and regulations. The increasingly interconnected nature of medical devices has demonstrated the importance of addressing cybersecurity risks associated with device connectivity in device design because of the effects on safety and effectiveness.[^22] Cybersecurity risks to the medical device or to the larger medical device system can be reasonably controlled through using an SPDF.

The primary goal of using an SPDF is to manufacture and maintain safe and effective devices. From a security standpoint, these are also trustworthy and resilient devices. These devices can then be managed (e.g., installed, configured, updated, review of device logs) through the device design and associated labeling by the device manufacturers and/or users (e.g., patients, healthcare facilities). For healthcare facilities, these devices can also be managed within their own cybersecurity risk management frameworks, such as the National Institute of Standards and Technology (NIST) Framework for Improving Critical Infrastructure Cybersecurity, generally referred to as the [NIST Cybersecurity Framework or NIST CSF](https://www.nist.gov/cyberframework).[^23]

FDA recommends that manufacturers use device design processes such as those described in the QS regulation to support secure product development and maintenance. To preserve flexibility for manufacturers, manufacturers may use other existing frameworks that satisfy the QS regulation and align with FDA's recommendations for using an SPDF. Possible frameworks to consider include, but are not limited to, the medical device-specific framework that can be found in the Medical Device and Health IT Joint Security Plan (JSP2)[^24] and IEC 81001-5-1. Frameworks from other sectors may also comply with the QS regulations, like the framework provided in ANSI/ISA 62443-4-1 Security for industrial automation and control systems Part 4-1: Product security development life-cycle requirements.[^25]

The following subsections provide recommendations for using SPDF processes that FDA believes provide important considerations for the development of devices that are safe and effective, how these processes can complement the QS regulation, and the documentation FDA recommends manufacturers provide for review as part of premarket submissions. These recommendations may be helpful for manufacturers of cyber devices that must "design, develop, and maintain processes and procedures to provide a reasonable assurance that the device and related systems are cybersecure . . ." pursuant to section 524B(b)(2) of the FD&C Act (see Section VII.C.2). The information in these sections does not represent a complete SPDF. For more information on SPDFs, see earlier in Section V. In addition, FDA does not recommend that manufacturers discontinue existing, effective processes.

## A. Security Risk Management
To fully account for cybersecurity risks in medical device systems, the safety and security risks of each device should be assessed within the context of the larger system in which the device operates. In the context of cybersecurity, security risk management processes are critical because, given the evolving nature of cybersecurity threats and risks, no device is, or can be, completely secure. Security risk management should be an integrated part of a manufacturer's entire quality system, addressed throughout the TPLC.[^26] The quality system processes entail the technical, personnel, and management practices, among others, that manufacturers use to manage potential risks to their devices and ensure that their devices are, and once on the market, remain, safe and effective, which includes security.

Performing security risk management is distinct from performing safety risk management as described in ISO 14971. The distinction in the performance of these processes is due to the fact that in the security context versus the safety context, the scope of possible harm and the risk assessment factors may be different. Also, while safety risk management focuses on physical injury, damage to property or the environment, or delay and/or denial of care due to device or system unavailability, security risk management may include risks that can result in indirect or direct patient harm. Additionally, risks that are outside of FDA's assessment of safety and effectiveness, such as those related to business or reputational risks, may also exist.

The scope and objective of a security risk management process, in conjunction with other SPDF processes (e.g., security testing), is to expose how threats, through vulnerabilities, can manifest patient harm and other potential risks. These processes should also ensure that risk control measures for one type of risk assessment do not inadvertently introduce new risks in the other. For example, AAMI TIR57 and ANSI/AAMI SW96 detail how the security and safety risk management processes should interface to ensure all risks are adequately assessed.[^27] FDA recommends that security risk management processes, as detailed in the QS regulation,[^28] be established or incorporated into those that already exist, and should address the manufacturer's design, manufacturing, and distribution processes, as well as updates across the TPLC. The processes in the QS regulation which may be relevant in this context include, but are not limited to design controls (21 CFR 820.30), validation of production processes (21 CFR 820.70), and corrective and preventive actions (21 CFR 820.100) to ensure both safety and security risks are adequately addressed. For completeness in performing risk analyses under 21 CFR 820.30(g), FDA recommends that device manufacturers conduct both a safety risk assessment and a separate, accompanying security risk assessment to ensure a more comprehensive identification and management of patient safety risks.

A device should be designed to eliminate or mitigate known vulnerabilities. For marketed devices, if comprehensive design mitigations are not possible, compensating controls should be considered. For all devices, when any known vulnerabilities are only partially mitigated or unmitigated by the device design, they should be assessed as reasonably foreseeable risks in the risk assessment and be assessed for additional control measures or risk transfer[^29] to the user/operator, or, if necessary, the patient. Risk transfer, if appropriate, should only occur when all relevant risk information is known, assessed, and appropriately communicated to users and includes risks inherited from the supply chain as well as how risk transfer will be handled when the device or manufacturer-controlled assets of the medical device system reach end of support and end of life and whether or how the user is able to take on that role (e.g., if the user may be a patient).

To document the security risk management activities for a medical device system, FDA recommends that manufacturers generate a security risk management plan and report such as that described in AAMI TIR57 and ANSI/AAMI SW96.[^30] Manufacturers should include their security risk management reports—including the outputs of their security risk management processes—in their premarket submissions to help demonstrate the safety and effectiveness of the device. A security risk management report, such as that described in AAMI TIR57 and ANSI/AAMI SW96, should be sufficient to support the security risk management process aspect of demonstrating a reasonable assurance of safety and effectiveness. Such report should include the documentation elements for the system threat modeling, cybersecurity risk assessment, Software Bill of Materials (SBOM), component support information, vulnerability assessments, and unresolved anomaly assessment(s) described in the sections below.[^31] In the subsections below, we discuss FDA's recommendations regarding the scope and/or content of specific security risk management documentation elements.

In addition to containing the documentation elements listed above, the security risk management report should:

- Summarize the risk evaluation methods and processes,
- Detail the residual risk conclusion from the security risk assessment,
- Detail the risk mitigation activities undertaken as part of a manufacturer's risk management processes, and
- Provide traceability between the threat model, cybersecurity risk assessment, SBOM, and testing documentation as discussed later in this guidance as well as other relevant cybersecurity risk management documentation.

### 1. Threat Modeling
Threat modeling includes a process for identifying security objectives, risks, and vulnerabilities across the medical device system, and then defining countermeasures to prevent, mitigate, monitor, or respond to the effects of threats to the medical device system throughout its lifecycle. It is foundational for optimizing system, product, network, application, and connection security when applied appropriately and comprehensively.

With respect to security risk management, and in order to identify appropriate security risks and controls for the medical device system, FDA recommends that threat modeling be performed to inform and support the risk analysis activities. As part of the risk assessment, FDA recommends threat modeling be performed throughout the design process and be inclusive of all medical device system elements.

The threat model should:

- Identify medical device system risks and mitigations as well as inform the pre- and post-mitigation risks considered as part of the cybersecurity risk assessment;
- State any assumptions about the medical device system or environment of use (e.g., hospital networks are inherently hostile, therefore manufacturers are recommended to assume that an adversary controls the network with the ability to alter, drop, and replay packets); and
- Capture cybersecurity risks introduced through the supply chain, manufacturing, deployment, interoperation with other devices, maintenance/update activities, and decommission activities that might otherwise be overlooked in a traditional safety risk assessment process.

FDA recommends that premarket submissions include threat modeling documentation to demonstrate how the medical device system has been analyzed to identify potential security risks that could impact safety and effectiveness. There are a number of methodologies and/or combinations of methods for threat modeling that manufacturers may choose to use.[^32] Rationale for the methodology(ies) selected should be provided with the threat modeling documentation. Additional recommendations on how threat modeling documentation should be submitted to FDA are discussed in Section V.B below.

Threat modeling activities can be performed and/or reviewed during design reviews. FDA recommends that threat modeling documentation include sufficient information on threat modeling activities performed by the manufacturer to assess and review the security features built into the device such that they holistically evaluate the device and the system in which the device operates, for the safety and effectiveness of the device.

### 2. Cybersecurity Risk Assessment
As a part of security risk management, security risks and controls should be assessed for residual risks as part of a cybersecurity risk assessment. Effective security risk assessments address the fact that cybersecurity-related failures can occur either intentionally or unintentionally. Accordingly, cybersecurity risks are difficult to predict, meaning that it is not possible to assess and quantify the likelihood of an incident occurring based on historical data or modeling (also known as a "probabilistic manner"). This non-probabilistic approach is not the fundamental approach performed in safety risk management under ISO 14971 and further underscores why safety and security risk management are distinct but connected processes. Instead, security risk assessment processes focus on exploitability, or the ability to exploit vulnerabilities present within a device and/or system. FDA recommends that manufacturers assess identified risks according to the level of risk posed from the device and the system in which it operates. Additional discussion on exploitability assessments for the security risk assessment can be found in FDA's Postmarket Cybersecurity Guidance.

The premarket assessment of exploitability of a cybersecurity risk may be different from the exploitability assessment of a vulnerability discovered postmarket. In these instances, a premarket exploitability assessment could either assume a worst-case assessment and implement appropriate controls, or provide a justification for a reasonable exploitability assessment of the risk throughout the TPLC and how the risk is controlled.

Acceptance criteria for cybersecurity risks should carefully consider the TPLC of the medical device system, as it might be more difficult to mitigate cybersecurity issues once the device is marketed. As discussed above in Sections IV.B and V.A, known vulnerabilities should be assessed as reasonably foreseeable risks. The cybersecurity risk assessment for vulnerabilities identified during cybersecurity testing should also consider the TPLC of the device as the exploitability of the vulnerability is likely to increase over the device lifecycle. If a penetration tester, for example, was able to exploit a vulnerability, the ability of a threat actor to exploit that vulnerability is likely to increase over the device lifecycle. Furthermore, vulnerabilities identified in [CISA's Known Exploited Vulnerabilities Catalog](https://www.cisa.gov/known-exploited-vulnerabilities-catalog) should be designed out of the device, as they are already being exploited and expose the medical device system and users to the risk.

FDA recommends that the cybersecurity risk assessment provided in premarket submissions capture the risks and controls identified from the threat model. The methods used for scoring the risk pre- and post-mitigation and the associated acceptance criteria as well as the method for transferring security risks into the safety risk assessment process should also be provided as part of the premarket submission.

### 3. Interoperability Considerations
Interoperability is an important consideration when assessing the cybersecurity of the end-to-end medical device system. As identified in FDA's guidance "[Design Considerations and Pre-market Submission Recommendations for Interoperable Medical Devices](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/design-considerations-and-pre-market-submission-recommendations-interoperable-medical-devices)," hereafter referred to as the "Interoperability Guidance," interoperable medical devices have the ability to exchange and use information through an electronic interface with another medical or nonmedical product, system, or device.

As part of a medical device system, a device may have cybersecurity considerations from interoperable functionality, including but not limited to interfaces with:

- Other medical devices and accessories;
- "Other functions" as identified in FDA's guidance "[Multiple Function Device Products: Policy and Considerations](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/multiple-function-device-products-policy-and-considerations);"
- Healthcare infrastructure (e.g., network, Electronic Medical Records, medical imaging systems); and
- General-purpose computing platforms.

While cybersecurity controls may increase the complexity of interfaces to allow for interoperability, when properly implemented, the cybersecurity controls can help ensure that these capabilities remain safe and effective. Cybersecurity controls should be used as a means to allow for the safe and effective exchange and use of information. Additionally, cybersecurity controls should not be intended to prohibit a user from accessing their device data.

When common technology and communication protocols are used to enable interoperability (e.g., Bluetooth, Bluetooth Low Energy, network protocols), device manufacturers should assess whether added security controls beneath such communication are needed to ensure the safety and effectiveness of the device (e.g., added security controls beneath Bluetooth Low Energy to protect against risks if vulnerabilities in the Bluetooth Low Energy protocol or supporting technology are discovered).

In addition to the recommendations in the [Interoperability Guidance](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/design-considerations-and-pre-market-submission-recommendations-interoperable-medical-devices), manufacturers should consider the appropriate cybersecurity risks and controls associated with the interoperability capabilities and document these considerations as recommended throughout this guidance.

### 4. Third-Party Software Components
As discussed in FDA's guidance "[Off-The-Shelf (OTS) Software Use in Medical Devices](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/shelf-ots-software-use-medical-devices)," medical devices commonly include third-party software components,[^33] including off-the-shelf and open source software. When these components are incorporated, security risks of the software components should become factors of the overall medical device system risk management processes and documentation.

As part of demonstrating compliance with design controls under 21 CFR 820.30(g), and to support supply chain risk management processes, all software, including those developed by the device manufacturer ("proprietary software") or obtained from third parties, should be assessed for cybersecurity risk. Device manufacturers should document all software components of a device and address or otherwise mitigate risks associated with these software components.

In addition, under 21 CFR 820.50, a manufacturer must put in place processes and controls to ensure that its suppliers conform to the manufacturer's requirements. Such information is documented in the Design History File, required by 21 CFR 820.30(j), and Device Master Record, required by 21 CFR 820.181. This documentation demonstrates the device's overall compliance with the QS regulation, as well as that the third-party components meet specifications established for the device. Security risk assessments that include analyses and considerations of cybersecurity risks that may exist in or be introduced by third-party software and the software supply chain may help demonstrate that manufacturers have adequately ensured such compliance and documented such history.

Software is updated over time to provide additional features, address security concerns, and otherwise be maintained. These changes may introduce new considerations or risks that must be accounted for as part of risk management. As a result, device manufacturers should establish and maintain custodial control of device source code (the original "copy" of the software) throughout the lifecycle of a device as part of configuration management.[^34] This may be accomplished through different methods, such as source code escrow or source code backups, among others.[^35]

Manufacturers may not have control of source code due to licensing restrictions, terms of supplier agreements, or other challenges. While source code is not required to be provided in premarket submissions, manufacturers should include plans for how third-party software components could be updated or replaced if support ends or other software issues arise in premarket submissions. The device manufacturer should also provide users with whatever information they may need in the device labeling to allow them to manage risks associated with the software components, including known vulnerabilities, configuration specifications, and other relevant security and risk management considerations.

One tool to help manage supply chain risk as well as clearly identify and track the software incorporated into a device is an SBOM, as described below.

#### (a) Software Bill of Materials (SBOM)
An SBOM can aid in the management of cybersecurity risks that exist throughout the software stack. A robust SBOM includes both the device manufacturer-developed components and third-party components, including purchased/licensed software and open-source software, and the upstream software dependencies that are required/depended upon by proprietary, purchased/licensed, and open-source software.

An SBOM helps facilitate risk management processes by providing a mechanism to identify devices and the systems in which they operate that might be affected by vulnerabilities in the software components, both during development when software is being chosen as a component and after it has been placed into the market throughout all other phases of a product's life.[^36] Because vulnerability management is a critical part of a device's security risk management processes, an SBOM or an equivalent capability should be maintained as part of the device's configuration management, be regularly updated to reflect any changes to the software in marketed devices, and should support documentation, such as the types detailed in 21 CFR 820.30(j) (Design History File) and 820.181 (Device Master Record).

To assist FDA's assessment of the device risks and associated impacts on safety and effectiveness related to cybersecurity, FDA recommends that premarket submissions include SBOM documentation as outlined below. For cyber devices, an SBOM is required (see section 524B(b)(3) of the FD&C Act and Section VII.C.3 of this guidance). SBOMs can also be an important tool for transparency with users of potential risks as part of labeling as addressed later in Section VI.

#### (b) Documentation Supporting Software Bill of Materials
FDA's guidance document "[Off-The-Shelf (OTS) Software Use in Medical Devices](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/shelf-ots-software-use-medical-devices)" describes information that should be provided in premarket submissions for software components for which a manufacturer cannot claim complete software lifecycle control. In addition to the information recommended in that guidance, manufacturers should provide machine-readable SBOMs consistent with the minimum elements (also referred to as "baseline attributes") identified in the October 2021 National Telecommunications and Information Administration (NTIA) Multistakeholder Process on Software Component Transparency document "[Framing Software Component Transparency: Establishing a Common Software Bill of Materials (SBOM)](https://www.ntia.gov/files/ntia/publications/sbom_minimum_elements_report.pdf)."

In addition to the minimum elements identified by NTIA, for each software component contained within the SBOM, manufacturers should include in the premarket submission:

- The software level of support provided through monitoring and maintenance from the software component manufacturer (e.g., the software is actively maintained, no longer maintained, abandoned); and
- The software component's end-of-support date.

When provided, manufacturers may choose to provide these additional elements as part of the SBOM, or they may provide it separately, such as in an addendum. Industry-accepted formats of SBOMs are encouraged.

If a manufacturer is unable to provide the SBOM information to FDA, the manufacturer should provide a justification for why the information cannot be included in the premarket submission.

As part of the premarket submission, manufacturers should also identify all known vulnerabilities associated with the device and the software components, including those identified in [CISA's Known Exploited Vulnerabilities Catalog](https://www.cisa.gov/known-exploited-vulnerabilities-catalog). For each known vulnerability, manufacturers should describe how the vulnerabilities were discovered to demonstrate whether the assessment methods were sufficiently robust. For components with known vulnerabilities, device manufacturers should provide in premarket submissions:

- A safety and security risk assessment of each known vulnerability (including device and system impacts); and
- Details of applicable safety and security risk controls to address the vulnerability. If risk controls include compensating controls, those should be described in an appropriate level of detail.

For additional information and discussion regarding proprietary and third-party components, see Section V.B.2, Security Architecture Views, below.

### 5. Security Assessment of Unresolved Anomalies
FDA's [Premarket Software Guidance](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/guidance-content-premarket-submissions-software-contained-medical-devices) recommends that device manufacturers provide a list of software anomalies that exist in a product at the time of submission. For each anomaly, FDA recommends that device manufacturers conduct an evaluation of the anomaly's impact on the device's safety and effectiveness, and consult the Premarket Software Guidance to assess the associated documentation recommended for inclusion in such device's premarket submission.

Some anomalies discovered during development or testing may have security implications and may also be considered vulnerabilities. As a part of ensuring a complete security risk assessment under 21 CFR Part 820.30(g), the assessment for impacts to safety and effectiveness may include an assessment for the potential security impacts of anomalies. The assessment should also include consideration of any present Common Weakness Enumeration (CWE) categories.[^37]

For example, a clinical user may inadvertently reveal the presence of a previously unknown software anomaly during normal use, where the impact of the anomaly might occur sporadically and be assessed to be acceptable from a software risk perspective. Conversely, a threat might seek out these types of anomalies, and identify means to exploit them in order to manifest the anomaly's impact continuously, which could significantly impact the acceptability of the risk when compared to an anomaly assessment that didn't include security considerations.

The criteria and rationales for addressing the resulting anomalies with security impacts should be provided as part of documentation in the premarket submission.

### 6. TPLC Security Risk Management
Cybersecurity risks may continue to be identified throughout the device's TPLC. Manufacturers should ensure they have appropriate resources to identify, assess, and mitigate cybersecurity vulnerabilities as they are identified throughout the supported device lifecycle.

As part of using an SPDF, manufacturers should update their security risk management documentation as new information becomes available, such as when new threats, vulnerabilities, assets, or adverse impacts are discovered during development and after the device is released. When maintained throughout the device lifecycle, this documentation (e.g., threat modeling, cybersecurity risk assessment) can be used to quickly identify vulnerability impacts once a device is released and, when appropriate, to support timely corrective and preventive action activities described in 21 CFR 820.100.

Over the service life of a device, FDA recommends that the risk management documentation account for any differences in the risk management for fielded devices (e.g., marketed devices or devices no longer marketed but still in use). For example, if an update is not applied automatically for all fielded devices, then there will likely be different risk profiles for differing software configurations of the device. FDA recommends that vulnerabilities be assessed for any differing impacts for all fielded versions to ensure patient risks are being accurately assessed.

Additional information as to whether a new premarket submission (e.g., PMA, PMA supplement, or 510(k)) or 21 CFR Part 806 reporting is needed based on postmarket vulnerabilities and general postmarket cybersecurity risk management is discussed in the Postmarket Cybersecurity Guidance.

To demonstrate the effectiveness of a manufacturer's processes, FDA recommends that a manufacturer track and record the measures and metrics below,[^38] and provide them in premarket submissions and PMA annual reports (21 CFR 814.84), when available.[^39] Selecting appropriate measures and metrics for the processes that define an SPDF is important to ensure that device design appropriately addresses cybersecurity in compliance with the QS regulation. At a minimum, FDA recommends tracking the following measures and metrics, or those that provide equivalent information:

- Percentage of identified vulnerabilities that are updated or patched (defect density);
- Duration from vulnerability identification to when it is updated or patched; and
- Duration from when an update or patch is available to complete implementation in devices deployed in the field, to the extent known.

Averages of the above measures should be provided if multiple vulnerabilities are identified and addressed. These averages may be provided over multiple time frames based on volume or in response to process or procedure changes to increase efficiencies of these measures over time.

## B. Security Architecture
Manufacturers are responsible for identifying cybersecurity risks in their devices and the systems in which they expect those devices to operate, and implementing the appropriate controls to mitigate those risks. These risks may include those introduced by device reliance on hospital networks, cloud infrastructure, or "other functions" (as defined in FDA's guidance "[Multiple Function Device Products: Policy and Considerations](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/multiple-function-device-products-policy-and-considerations)"), for example. A security architecture, like a system architecture, defines the system and all end-to-end connections into and/or out of the system. A security architecture definition process[^40] includes both high-level definitions of the devices and/or systems that interact, and detailed information on the implementations for how those interactions occur and are secured. It contains information that demonstrates that the risks considered during the risk management process are adequately controlled, which, in turn, supports the demonstration of the safety and effectiveness of the medical device system.

Under 21 CFR 820.30(b), a manufacturer must establish and maintain plans that describe or reference the design and development activities and define responsibility for implementation. Such plans must be reviewed, updated, and approved as design and development evolves (21 CFR 820.30(b)). Under 21 CFR 820.30(c), a manufacturer must establish and maintain procedures to ensure that the design requirements relating to a device are appropriate and address the intended use of the device, including the needs of the user and patient. Under 21 CFR 820.30(d), a manufacturer must establish and maintain procedures for defining and documenting design output in terms that allow an adequate evaluation of conformance to design input requirements. 21 CFR 820.30(d) also states that design output procedures shall contain or make reference to acceptance criteria and shall ensure that those design outputs that are essential for the proper functioning of the device are identified.

FDA recommends that these plans and procedures include design processes, design requirements, and acceptance criteria for the security architecture of the device such that they holistically address the cybersecurity considerations for the device and the system in which the device operates. FDA recommends that all medical devices provide and enforce the security objectives in Section IV, above, but recognizes that implementations to address the security objectives may vary.

FDA recommends that premarket submissions include documentation on the security architecture. The objective in providing security architecture information in premarket submissions is to provide to FDA the security context and trust-boundaries of the medical device system in terms of the interfaces, interconnections, and interactions that the medical device system has with external entities. The details of these elements enable the identification of the parts of the medical device system in or through which incidents might occur. These details help to provide a sufficient understanding of the system such that FDA can evaluate adequacy of the architecture itself as it relates to safety and effectiveness.

Manufacturers should analyze the entire system to understand the full environment and context in which the device is expected to operate. The security architecture should include a consideration of system-level risks, including but not limited to risks related to the supply chain (e.g., to ensure the device remains free of malware, or vulnerabilities inherited from upstream dependencies such as third-party software, among others), design, production, and deployment (i.e., into a connected/networked environment).

FDA recommends that this architecture information take the form of "views," and that these views be provided during premarket submissions to demonstrate safety and effectiveness.[^41] If the documentation identified in this section already exists in other risk management documentation, FDA does not expect manufacturers to separate out this information into new document(s); such documentation can be provided and the submission can reference the relevant sections.

Below, FDA outlines the recommended security controls and ways to document the resultant security architecture in premarket submissions through specific Security Architecture Views.

### 1. Implementation of Security Controls
FDA considers the way in which a device addresses cybersecurity risks and the way in which the device responds when exposed to cybersecurity threats as functions of the device design. Effective cybersecurity relies upon security being "built in" to a device, and not "bolted on" after the device is designed. FDA recommends that device manufacturers' design processes include design inputs for cybersecurity controls.[^42] Under 21 CFR 820.30(c), a manufacturer must establish and maintain procedures to ensure that the design requirements relating to a device are appropriate and address the intended use of the device, including the needs of the user and patient. Under 21 CFR 820.30(d), a manufacturer must establish and maintain procedures for defining and documenting design output in terms that allow an adequate evaluation of conformance to design input requirements. These output procedures shall contain or make reference to acceptance criteria and shall ensure that those design outputs that are essential for the proper functioning of the device are identified.

FDA recommends that these procedures include design requirements and acceptance criteria for the security features built into the device such that they holistically address the cybersecurity considerations for the device and the system in which the device operates.

Security controls allow manufacturers to achieve the security objectives outlined in Section IV and are an integral part of an SPDF. FDA recommends that an adequate set of security controls should include, but not necessarily be limited to, controls from the following categories:

- Authentication;
- Authorization;
- Cryptography;
- Code, Data, and Execution Integrity;
- Confidentiality;
- Event Detection and Logging;
- Resiliency and Recovery; and
- Updatability and Patchability.

For each of the security control categories above, specific control recommendations and implementation guidance to avoid common pitfalls are detailed in Appendix 1.

Implementation of security controls should be applied across the system architecture using risk-based determinations associated with the subject connections and devices. Without adequate security controls across the medical device system—which include management, technical, and operational controls—there is no reasonable assurance of safety and effectiveness. Additionally, deficiencies in the design of selected security controls or the implementation of those controls can have dramatic impacts on a device's ability to demonstrate or maintain its safety and effectiveness.

FDA recommends the requirements and acceptance criteria for each of the above categories be provided in premarket submissions to demonstrate safety and effectiveness. Manufacturers should submit documentation in their premarket submissions demonstrating that the security controls for the categories above, and further detailed in the recommendations in Appendix 1, have (1) been implemented, and (2) been tested in order to validate that they were effectively implemented. For more information on cybersecurity testing, see Section V.C, below.

Manufacturers may include the demonstration of security controls that are comparable or in addition to those described in Appendix 1 in their premarket submissions. If using alternate controls that are not described in this document, manufacturers should provide documentation and tracing of specific design features and security controls to the associated risks in order to demonstrate that they provide appropriate levels of safety and effectiveness. As cybersecurity design controls are established early in the development phase, FDA recommends that device manufacturers utilize the FDA Q-submission process to discuss design considerations for cybersecurity risk management throughout the device lifecycle with the agency.[^43] Additional information on premarket documentation recommendations for design controls are discussed in the Security Architecture Views section below.

### 2. Security Architecture Views
In addition to the design control requirements,[^44] 21 CFR 820.100 requires that manufacturers establish and maintain procedures for implementing corrective and preventive action, which must include, among other things, requirements for analyzing quality data to identify existing and potential causes of quality problems. FDA recommends that manufacturers develop and maintain security architecture view documentation as a part of the process for the design, development, and maintenance of the medical device system. If corrective and preventive actions are identified, these views can be used to help identify impacted functionality and solutions that address the risks.

FDA recommends that premarket submissions include the architecture views described in this section. These architecture views can contribute to the demonstration of safety and effectiveness in premarket submissions by illustrating how the controls to address cybersecurity risks have been applied to the medical device system.

The security architecture may be expressed at different levels of abstraction and with different scopes or views.[^45] The number and extent of the architecture views provided in the submission depends on the attack surface(s) identified through threat modeling and risk assessments for the medical device system. These views can therefore be an effective way to provide threat modeling information to FDA and will naturally scale the documentation provided with the cybersecurity risk of the device.

FDA recommends providing, at minimum, the following types of views in premarket submissions:

- Global System View;
- Multi-Patient Harm View;
- Updateability/Patchability View; and
- Security Use Case View(s).

Documenting these views in premarket submissions should include both diagrams and explanatory text. These diagrams and explanatory text should contain sufficient details to permit an understanding of how the assets within the medical device system function holistically within the associated implementation details. For the security architecture views, manufacturers should follow the recommendations outlined in Appendix 2 when determining the level of detail to include in premarket submissions.

These security architecture views should:

- Identify security-relevant medical device system elements and their interfaces;
- Define security context, domains, boundaries, critical user roles, and external interfaces of the medical device system;
- Align the architecture with (a) the medical device system security objectives and requirements, (b) security design characteristics in order to address the identified threats; and
- Establish traceability of architecture elements to user and medical device system security requirements. Such traceability should exist throughout the cybersecurity risk management documentation.

If a particular view sufficiently captures the risks of another view identified above, we do not expect manufacturers to duplicate documentation. Similarly, if threat modeling documentation sufficiently captures the view, we do not expect manufacturers to duplicate documentation. Additionally, if one of the views listed above is not appropriate, manufacturers should instead provide an explanation for why the view is not included in the premarket submission.

The extent of these security views in a premarket submission is expected to scale based on the architecture and potential cybersecurity risk posed to the device. For example, medical device systems with network and/or cloud access would be expected to have more Security Use Case Views than a medical device system that has only a USB interface.

#### (a) Global System View
A global system view should describe the overall medical device system, including the device itself and all internal and external connections. For interconnected and networked devices, this view should identify all interconnected elements, including any software update infrastructure(s), healthcare facility network impacts, intermediary connections or devices, cloud connections, and patient home network impact.

Depending on the complexity of the medical device system, it may not be feasible to include all data flow specifics in a singular global system view. Additional views can be provided that detail the communication specifics as recommended in Appendix 2 and do not need to be duplicated if captured in one of the other types of views detailed below.

#### (b) Multi-Patient Harm View
When devices are capable of connecting (wired or wirelessly) to another medical or non-medical product, to a network, or to the Internet, there is the possibility that multiple devices can be compromised simultaneously. Because of that connectivity, if a device is compromised, or if a non-device function (i.e., any function that does not fall within section 201(h) of the FD&C Act) that could impact the device function is compromised, the device may introduce a safety risk to patients through security risk. This may change the device's functionality. For example, a non-device function could be hacked to perform a device function and ultimately harm patients.

Depending on the device risk and use environment, a multiple-device compromise may have severe impacts for multiple patients, either through impact to the device itself and/or to healthcare facility operations (e.g., multiparameter bedside monitors all restarting at once, leaving all monitors connected to the same network no longer monitoring patient vitals and staffing levels not able to monitor all patient vitals).

FDA recommends that manufacturers address how their device(s) and the system(s) in which they operate defend against and/or respond to attacks with the potential to harm multiple patients in a multi-patient harm view. This view should include the information recommended in Appendix 2. These risks, once identified, may also need to be assessed differently in the accompanying cybersecurity risk assessment due to the different nature of the risk.

#### (c) Updatability and Patchability View
With the need to provide timely, reliable updates to devices in order to address emerging cybersecurity risks throughout the TPLC of the device, FDA recommends manufacturers provide an updateability and patchability view. This view should describe the end-to-end process that permits software updates and patches to be provided (i.e., deployed) to the device, and should include detailed information as recommended in Appendix 2.

For example, if a device manufacturer intends to push software from a software update server to an in-clinic cardiac implant programmer, "end-to-end" means the path from the update server to the in-clinic programmer that programs the implanted device. The software update path will likely include traversing technology that the device manufacturer does not control, and therefore the device design should provide for the protection of the end-to-end path and take into account any additional cybersecurity risk created or posed by those non-manufacturer-controlled technologies.

#### (d) Security Use Case Views
In addition to the views identified above, security use case views should also be provided. Security use cases should be included for all medical device system functionality through which a security compromise could impact the safety or effectiveness of the device. These security use cases should cover various operational states of elements in the medical device system (e.g., power on, standby, transition states) and assess clinical functionality states of the medical device system (e.g., programming, alarming, delivering therapy, send/receive data, reporting diagnostic results).

The number of security use cases that should be assessed will scale with the cybersecurity complexity and risk of the device. Each view should include detailed information as recommended in Appendix 2. For use cases identified that share the same security assessment, the associated diagrams and explanatory text can describe the multiple use cases covered by the view in lieu of providing duplicative information in multiple places. For example, programming commands and sending/receiving device data may share the same communication protocol and therefore may not exhibit differences between the security views for both scenarios, despite having different clinical risk assessments.

## C. Cybersecurity Testing
As with other areas of product development, testing is used to demonstrate the effectiveness of design controls. While software development and cybersecurity are closely related disciplines, cybersecurity controls require testing beyond standard software verification and validation activities to demonstrate the effectiveness of the controls in a proper security context to therefore demonstrate that the device has a reasonable assurance of safety and effectiveness.

Under 21 CFR 820.30(f), a manufacturer must establish and maintain procedures for verifying the device design. Such verification shall confirm that the design output meets the design input requirements. Under 21 CFR 820.30(g), a manufacturer must establish and maintain procedures for validating its device design. Such design validation shall include software validation and risk analysis, where appropriate. FDA recommends verification and validation include sufficient testing performed by the manufacturer on the cybersecurity of the medical device system through which the manufacturer verifies and validates their inputs and outputs, as appropriate.

Security testing documentation and any associated reports or assessments should be submitted in the premarket submission. FDA recommends that the following types of testing, among others, be considered for inclusion in the submission:

- Security requirements;
  - Manufacturers should provide evidence that each design input requirement was implemented successfully.
  - Manufacturers should provide evidence of their boundary analysis and rationale for their boundary assumptions.
- Threat mitigation;
  - Manufacturers should provide details and evidence of testing that demonstrates effective risk control measures according to the threat models provided in the global system, multi-patient harm, updatability and patchability, and security use case views.
  - Manufacturers should ensure the adequacy of each cybersecurity risk control (e.g., security effectiveness in enforcing the specified security policy, performance for maximum traffic conditions, stability, and reliability, as appropriate).
- Vulnerability Testing (such as section 9.4 of ANSI/ISA 62443-4-1); and
  - Manufacturers should provide details and evidence[^46] of the following testing and analyses:
    - Abuse or misuse cases, malformed and unexpected inputs;
      - Robustness.
      - Fuzz testing.
    - Attack surface analysis;
    - Vulnerability chaining;
    - Closed box testing of known vulnerability scanning;
    - Software composition analysis of binary executable files; and
    - Static and dynamic code analysis, including testing for credentials that are "hardcoded," default, easily guessed, and easily compromised.
- Penetration testing.
  - The testing should identify and characterize security-related issues via tests that focus on discovering and exploiting security vulnerabilities in the product. Penetration test reports should be provided and include the following elements:
    - Independence and technical expertise of testers;
    - Scope of testing;
    - Duration of testing;
    - Testing methods employed; and
    - Test results, findings, and observations.

Device manufacturers should indicate in the test reports by whom the testing was performed (e.g., independent internal testers, external testers) and what level of independence those responsible for testing devices have from the developers responsible for designing devices. In some cases, it may be necessary to use third parties to ensure an appropriate level of independence between the two groups, such that vulnerabilities or other issues revealed during testing are appropriately addressed. For any third-party test reports, manufacturers should provide the original third-party report. For all testing, manufacturers should provide their assessment of any findings including rationales for not implementing or deferring any findings to future releases.

As discussed in Sections V.A.2 and V.A.3 above, vulnerabilities and anomalies identified during testing should be assessed for their security impacts as part of the security risk management process. In non-security software testing, a benefit analysis of a discovered defect may lead to the conclusion that an anomaly does not need to be fixed, as its impact on medical device system functionality may be small or unlikely. Conversely, in security testing, the exploitability of an anomaly may necessitate that it is mitigated because of the greater, and different type of, harm that it could facilitate.

For issues that will be addressed in future releases (i.e., remediation deferred for a future software release because current risk was assessed to be acceptable), the premarket submission should contain plans for those releases. Such plans should include the vulnerabilities that future software releases will address, anticipated timelines for release, whether devices released in the interim will receive those updates, and how long it will take the update to reach the devices.

There are numerous authoritative resources for outlining security testing that may partially fulfill the testing outlined above.[^47]

FDA recommends that cybersecurity testing should occur throughout the SPDF. Security testing early in development can ensure that security issues are addressed prior to impacting release timelines and can prevent the need to redesign or re-engineer the device. After release, cybersecurity testing should be performed at regular intervals commensurate with the risk (e.g., annually) to ensure that potential vulnerabilities are identified and able to be addressed prior to their ability to be exploited.

[^22]: An example of this is discussed in FDA's 2023 safety communication [Cybersecurity Vulnerabilities in Certain Illumina MiSeqDx Instruments](https://www.fda.gov/medical-devices/safety-communications/cybersecurity-vulnerabilities-certain-illumina-miseqdx-instruments-fda-safety-communication). 이것의 예는 FDA의 2023년 안전성 통신 [특정 Illumina MiSeqDx 기기의 사이버보안 취약점](https://www.fda.gov/medical-devices/safety-communications/cybersecurity-vulnerabilities-certain-illumina-miseqdx-instruments-fda-safety-communication)에서 논의됩니다.

[^23]: For additional information on frameworks and guidance for managing cybersecurity, see the NIST Framework for Improving Critical Infrastructure Cybersecurity (aka NIST Cybersecurity Framework) and NIST SP 800-171, Protecting Controlled Unclassified Information in Nonfederal Systems and Organizations. 사이버보안 관리를 위한 프레임워크 및 가이던스에 대한 추가 정보는 중요 인프라 사이버보안 개선을 위한 NIST 프레임워크(NIST 사이버보안 프레임워크) 및 NIST SP 800-171, 비연방 시스템 및 조직에서 통제된 비분류 정보 보호를 참조하십시오.

[^24]: NEMA/MITA HN 1-2023, Medical Device and Health IT Joint Security Plan version 2 (JSP2). https://www.nema.org/standards/view/medical-device-and-health-it-joint-security-plan NEMA/MITA HN 1-2023, 의료기기 및 보건 IT 공동 보안 계획 버전 2(JSP2). https://www.nema.org/standards/view/medical-device-and-health-it-joint-security-plan

[^25]: For additional information, FDA has published two consensus standards recognition documents regarding ANSI/ISA 62443-4-1, Security for industrial automation and control systems Part 4-1: Product security development life-cycle requirements, and ANSI/ISA 62443-4-2, Security for industrial automation and control systems Part 4-2: Technical security requirements for IACS components available on the [FDA Recognized Consensus Standards Database](https://www.accessdata.fda.gov/scripts/cdrh/cfdocs/cfstandards/search.cfm). 추가 정보로, FDA는 ANSI/ISA 62443-4-1, 산업 자동화 및 제어 시스템을 위한 보안 파트 4-1: 제품 보안 개발 수명주기 요구사항 및 ANSI/ISA 62443-4-2, 산업 자동화 및 제어 시스템을 위한 보안 파트 4-2: IACS 구성요소에 대한 기술 보안 요구사항에 관한 두 개의 합의 표준 인정 문서를 발행했으며 [FDA 인정 합의 표준 데이터베이스](https://www.accessdata.fda.gov/scripts/cdrh/cfdocs/cfstandards/search.cfm)에서 이용할 수 있습니다.

[^26]: 21 CFR 820.30(g) requires manufacturers to "establish and maintain procedures for validating the device design," which "shall include software validation and risk analysis, where appropriate." 21 CFR 820.30(g)는 제조업체가 "기기 설계를 검증하기 위한 절차를 수립하고 유지"하도록 요구하며, 이는 "적절한 경우 소프트웨어 검증 및 위험 분석을 포함해야" 합니다.

[^27]: AAMI TIR57, Principles for medical device security – Risk management, ANSI/AAMI SW96, Standard for medical device security – Security risk management for device manufacturers. https://doi.org/10.2345/9781570208621.ch1 AAMI TIR57, 의료기기 보안을 위한 원칙 – 위험 관리, ANSI/AAMI SW96, 의료기기 보안 표준 – 기기 제조업체를 위한 보안 위험 관리. https://doi.org/10.2345/9781570208621.ch1

[^28]: See 21 CFR 820.30(g). 21 CFR 820.30(g)를 참조하십시오.

[^29]: In the cybersecurity context, risk transfer is the act of communicating and documenting a risk that will be controlled by another party (user or operator of the device). One example is that a control is implemented by setting a password, and the risk is transferred to the user to implement the control. 사이버보안 맥락에서, 위험 전가는 다른 당사자(기기의 사용자 또는 운영자)에 의해 통제될 위험을 전달하고 문서화하는 행위입니다. 한 가지 예는 비밀번호 설정에 의해 통제가 구현되고, 통제를 구현하기 위해 위험이 사용자에게 전가되는 것입니다.

[^30]: Details on the content for security risk management plans and reports beyond those specifically identified can be found in AAMI TIR57 Principles for medical device security—Risk management and ANSI/AAMI SW96 Standard for medical device security - Security risk management for device manufacturers. https://doi.org/10.2345/9781570208621.ch1 구체적으로 식별된 것 이외의 보안 위험 관리 계획 및 보고서의 내용에 대한 세부사항은 AAMI TIR57 의료기기 보안을 위한 원칙—위험 관리 및 ANSI/AAMI SW96 의료기기 보안 표준 - 기기 제조업체를 위한 보안 위험 관리에서 찾을 수 있습니다. https://doi.org/10.2345/9781570208621.ch1

[^31]: While security architecture is likely captured as a component of the security risk management process, it is discussed separately for the purposes of this guidance due to the level of detail recommended to be provided by manufacturers in order to facilitate FDA review of the safety and effectiveness of the device. 보안 아키텍처는 보안 위험 관리 프로세스의 구성요소로 포착될 가능성이 높지만, 기기의 안전성과 효과성에 대한 FDA 검토를 용이하게 하기 위해 제조업체가 제공할 것이 권장되는 세부 수준으로 인해 본 가이던스의 목적상 별도로 논의됩니다.

[^32]: The [MDIC/MITRE Playbook for Threat Modeling Medical Devices](https://mdic.org/resource/threat-modeling-playbook/) is an educational resource that discusses the threat modeling process, different threat modeling techniques, and provides fictional medical device examples. [MDIC/MITRE 의료기기 위협 모델링 플레이북](https://mdic.org/resource/threat-modeling-playbook/)은 위협 모델링 프로세스, 다양한 위협 모델링 기술을 논의하고 가상의 의료기기 예를 제공하는 교육 자료입니다.

[^33]: The use of "component" in this guidance is consistent with the definition in 21 CFR 820.3. 본 가이던스에서 "구성요소"의 사용은 21 CFR 820.3의 정의와 일치합니다.

[^34]: While some suppliers may not grant access to source code, manufacturers may consider adding to their purchasing controls acquisition of the source code should the purchased software reach end of support or end of life from the supplier earlier than the intended end of support or end of life of the medical device. 일부 공급업체는 소스 코드에 대한 액세스를 허용하지 않을 수 있지만, 제조업체는 구매한 소프트웨어가 의료기기의 의도된 지원 종료 또는 수명 종료보다 먼저 공급업체로부터 지원 종료 또는 수명 종료에 도달하는 경우 소스 코드 획득을 구매 통제에 추가하는 것을 고려할 수 있습니다.

[^35]: Source code escrow involves depositing a copy of a relevant piece of software's source code (and related technical components and documentation) with an independent third party ("escrow agent"). Source code backup involves storing (and updating as needed) a separate copy of the source code. 소스 코드 에스크로는 관련 소프트웨어의 소스 코드(및 관련 기술 구성요소 및 문서) 사본을 독립적인 제3자("에스크로 에이전트")에게 예치하는 것을 포함합니다. 소스 코드 백업은 소스 코드의 별도 사본을 저장(및 필요에 따라 업데이트)하는 것을 포함합니다.

[^36]: For additional information, see the Department of Commerce National Telecommunications and Information Administration's multi-stakeholder process for software transparency available on the following website [NTIA Software Component Transparency](https://www.ntia.gov/page/software-bill-materials). 추가 정보는 다음 웹사이트에서 이용할 수 있는 상무부 국가 통신 정보 관리국의 소프트웨어 투명성을 위한 다자간 이해관계자 프로세스를 참조하십시오 [NTIA 소프트웨어 구성요소 투명성](https://www.ntia.gov/page/software-bill-materials).

[^37]: Examples of SW91 defect classification mapped to CWE can be found in Annex D of AAMI SW91 Classification of Defects in Health Software. For additional information on CWE categories, see [CWE Common Weakness Enumeration](https://cwe.mitre.org/). CWE에 매핑된 SW91 결함 분류의 예는 AAMI SW91 건강 소프트웨어의 결함 분류의 부록 D에서 찾을 수 있습니다. CWE 범주에 대한 추가 정보는 [CWE Common Weakness Enumeration](https://cwe.mitre.org/)을 참조하십시오.

[^38]: The measures and metrics provided are examples; alternative or additional measures and metrics may also be considered and reported. 제공된 측정 및 메트릭은 예시입니다; 대체 또는 추가 측정 및 메트릭도 고려되고 보고될 수 있습니다.

[^39]: If a manufacturer has not marketed prior versions or the premarket submission does not pertain to a marketed product (e.g., PMA supplement), FDA acknowledges that these measures and metrics might not be available, but recommends that manufacturers include these as part of their risk management plan and SPDF processes. 제조업체가 이전 버전을 시판하지 않았거나 시판 전 제출이 시판된 제품(예: PMA 보완)과 관련이 없는 경우, FDA는 이러한 측정 및 메트릭이 이용 가능하지 않을 수 있음을 인정하지만, 제조업체가 이를 위험 관리 계획 및 SPDF 프로세스의 일부로 포함할 것을 권장합니다.

[^40]: NIST 800-160 vol. 1 rev. 1, Engineering Trustworthy Secure Systems states that security architecture definition process generates a set of representative security views of the system architecture to inform the selection of an appropriate security architecture. The process also ascertains vulnerability and susceptibility to disruptions, hazards, and threats. For additional information, see [NIST 800-160 vol. 1 rev. 1](https://doi.org/10.6028/NIST.SP.800-160v1r1). NIST 800-160 vol. 1 rev. 1, 신뢰할 수 있는 보안 시스템 엔지니어링은 보안 아키텍처 정의 프로세스가 적절한 보안 아키텍처 선택을 알리기 위해 시스템 아키텍처의 대표적인 보안 뷰 세트를 생성한다고 명시합니다. 이 프로세스는 또한 중단, 위험 및 위협에 대한 취약성 및 감수성을 확인합니다. 추가 정보는 [NIST 800-160 vol. 1 rev. 1](https://doi.org/10.6028/NIST.SP.800-160v1r1)을 참조하십시오.

[^41]: Views are discussed in more detail in the following subsections and Appendix 2. 뷰는 다음 하위 섹션 및 부록 2에서 더 자세히 논의됩니다.

[^42]: There are useful frameworks to use in the generation of these design inputs including the OWASP Security by design principles, AAMI/ISA-62443-4-1, as well as medical device specific frameworks including the Hippocratic Oath for Connected Medical Devices, Building Code for Medical Device Software Security, and IEC 81001-5-1. For a specific implementation of the OWASP Security by design principles, see the [Medical Device and Health IT Joint Security Plan version 2 (JSP2)](https://www.nema.org/standards/view/medical-device-and-health-it-joint-security-plan). 이러한 설계 입력을 생성하는 데 사용할 유용한 프레임워크에는 OWASP 보안 설계 원칙, AAMI/ISA-62443-4-1뿐만 아니라 연결된 의료기기를 위한 히포크라테스 선서, 의료기기 소프트웨어 보안을 위한 구축 코드 및 IEC 81001-5-1을 포함한 의료기기 특정 프레임워크가 포함됩니다. OWASP 보안 설계 원칙의 구체적인 구현은 [의료기기 및 보건 IT 공동 보안 계획 버전 2(JSP2)](https://www.nema.org/standards/view/medical-device-and-health-it-joint-security-plan)를 참조하십시오.

[^43]: For more information, see FDA's guidance "[Requests for Feedback and Meetings for Medical Device Submissions: The Q-Submission Program](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/requests-feedback-and-meetings-medical-device-submissions-q-submission-program)." 자세한 정보는 FDA의 가이던스 "[의료기기 제출에 대한 피드백 및 회의 요청: Q-제출 프로그램](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/requests-feedback-and-meetings-medical-device-submissions-q-submission-program)"을 참조하십시오.

[^44]: See [21 CFR 820.30](https://www.ecfr.gov/current/title-21/section-820.30). [21 CFR 820.30](https://www.ecfr.gov/current/title-21/section-820.30)을 참조하십시오.

[^45]: Architecture view is defined by NIST 800-160 vol. 1 rev. 1 as "A work product expressing the architecture of a system from the perspective of specific system concerns." https://doi.org/10.6028/NIST.SP.800-160v1r1 아키텍처 뷰는 NIST 800-160 vol. 1 rev. 1에서 "특정 시스템 우려사항의 관점에서 시스템의 아키텍처를 표현하는 작업 산출물"로 정의됩니다. https://doi.org/10.6028/NIST.SP.800-160v1r1

[^46]: For any testing tools or software used, the details provided may include, but may not be limited to, the name of the tool, version information as applicable, and any settings or configuration options for the tools used. 사용된 모든 테스트 도구 또는 소프트웨어에 대해, 제공되는 세부사항에는 도구의 이름, 해당되는 경우 버전 정보, 사용된 도구에 대한 설정 또는 구성 옵션이 포함될 수 있지만 이에 국한되지 않습니다.

[^47]: The following standards may partially meet the security testing recommendations: ANSI/UL 2900 Software Cybersecurity for Network-Connectable Products, ANSI/ISA 62443-4-1 Security for industrial automation and control systems Part 4-1: Product security development life-cycle requirements, in addition to IEC 81001-5-1. Additional standards may also meet or partially meet the testing recommendations outlined in this section. 다음 표준은 보안 테스트 권장사항을 부분적으로 충족할 수 있습니다: ANSI/UL 2900 네트워크 연결 가능 제품을 위한 소프트웨어 사이버보안, ANSI/ISA 62443-4-1 산업 자동화 및 제어 시스템을 위한 보안 파트 4-1: 제품 보안 개발 수명주기 요구사항, 그리고 IEC 81001-5-1. 추가 표준도 이 섹션에 설명된 테스트 권장사항을 충족하거나 부분적으로 충족할 수 있습니다.

# V. SPDF를 사용한 사이버보안 위험 관리
본 가이던스에서 권장하는 문서는 사이버보안 취약점이 있는 기기의 안전성과 효과성을 평가한 FDA의 경험을 기반으로 합니다. 그러나 스폰서는 적용 가능한 법적 조항 및 규정의 시판 전 제출 요구사항을 충족하는 한 대체 접근 방식을 사용하고 다른 문서를 제공할 수 있습니다. 의료기기의 점점 더 상호 연결되는 특성은 안전성과 효과성에 미치는 영향 때문에 기기 설계에서 기기 연결성과 관련된 사이버보안 위험을 다루는 것의 중요성을 입증했습니다.[^22] 의료기기 또는 더 큰 의료기기 시스템에 대한 사이버보안 위험은 SPDF를 사용하여 합리적으로 통제될 수 있습니다.

SPDF를 사용하는 주요 목표는 안전하고 효과적인 기기를 제조하고 유지하는 것입니다. 보안 관점에서 볼 때, 이것은 또한 신뢰할 수 있고 복원력이 있는 기기입니다. 이러한 기기는 기기 제조업체 및/또는 사용자(예: 환자, 의료 시설)가 기기 설계 및 관련 라벨링을 통해 관리(예: 설치, 구성, 업데이트, 기기 로그 검토)할 수 있습니다. 의료 시설의 경우, 이러한 기기는 일반적으로 [NIST 사이버보안 프레임워크 또는 NIST CSF](https://www.nist.gov/cyberframework)로 불리는 국립 표준 기술 연구소(NIST) 중요 인프라 사이버보안 개선 프레임워크와 같은 자체 사이버보안 위험 관리 프레임워크 내에서 관리될 수도 있습니다.[^23]

FDA는 제조업체가 안전한 제품 개발 및 유지를 지원하기 위해 QS 규정에 설명된 것과 같은 기기 설계 프로세스를 사용할 것을 권장합니다. 제조업체를 위한 유연성을 보존하기 위해, 제조업체는 QS 규정을 충족하고 SPDF 사용에 대한 FDA의 권장사항과 일치하는 다른 기존 프레임워크를 사용할 수 있습니다. 고려할 수 있는 프레임워크에는 의료기기 및 보건 IT 공동 보안 계획(JSP2)[^24] 및 IEC 81001-5-1에서 찾을 수 있는 의료기기 특정 프레임워크가 포함되지만 이에 국한되지 않습니다. ANSI/ISA 62443-4-1 산업 자동화 및 제어 시스템을 위한 보안 파트 4-1: 제품 보안 개발 수명주기 요구사항에 제공된 프레임워크와 같이 다른 분야의 프레임워크도 QS 규정을 준수할 수 있습니다.[^25]

다음 하위 섹션은 FDA가 안전하고 효과적인 기기 개발을 위해 중요한 고려사항을 제공한다고 믿는 SPDF 프로세스 사용에 대한 권장사항, 이러한 프로세스가 QS 규정을 어떻게 보완할 수 있는지, 그리고 FDA가 제조업체가 시판 전 제출의 일부로 검토를 위해 제공할 것을 권장하는 문서를 제공합니다. 이러한 권장사항은 FD&C법 524B(b)(2)조에 따라 "기기 및 관련 시스템이 사이버 보안을 확보한다는 합리적인 보증을 제공하기 위해 프로세스 및 절차를 설계, 개발 및 유지해야" 하는 사이버 기기 제조업체에게 유용할 수 있습니다(섹션 VII.C.2 참조). 이 섹션의 정보는 완전한 SPDF를 나타내지 않습니다. SPDF에 대한 자세한 정보는 섹션 V의 앞부분을 참조하십시오. 또한 FDA는 제조업체가 기존의 효과적인 프로세스를 중단할 것을 권장하지 않습니다.

## A. 보안 위험 관리
의료기기 시스템의 사이버보안 위험을 완전히 설명하려면, 각 기기의 안전 및 보안 위험이 기기가 작동하는 더 큰 시스템의 맥락 내에서 평가되어야 합니다. 사이버보안의 맥락에서, 사이버보안 위협과 위험의 진화하는 특성을 고려할 때 어떤 기기도 완전히 안전하지 않거나 안전할 수 없기 때문에 보안 위험 관리 프로세스는 매우 중요합니다. 보안 위험 관리는 TPLC 전반에 걸쳐 다루어지는 제조업체의 전체 품질 시스템의 통합된 부분이어야 합니다.[^26] 품질 시스템 프로세스는 제조업체가 기기에 대한 잠재적 위험을 관리하고 기기가 안전하고 효과적이며, 시장에 출시된 후에도 보안을 포함하여 안전하고 효과적으로 유지되도록 보장하기 위해 사용하는 기술적, 인력 및 관리 관행 등을 수반합니다.

보안 위험 관리 수행은 ISO 14971에 설명된 안전 위험 관리 수행과 구별됩니다. 이러한 프로세스 수행의 구별은 보안 맥락 대 안전 맥락에서 가능한 피해의 범위와 위험 평가 요소가 다를 수 있다는 사실 때문입니다. 또한, 안전 위험 관리는 기기 또는 시스템 이용 불가능으로 인한 물리적 상해, 재산 또는 환경에 대한 손상, 또는 치료 지연 및/또는 거부에 초점을 맞추는 반면, 보안 위험 관리는 간접적 또는 직접적 환자 피해를 초래할 수 있는 위험을 포함할 수 있습니다. 또한, 비즈니스 또는 평판 위험과 관련된 것과 같이 FDA의 안전성 및 효과성 평가 범위 밖의 위험도 존재할 수 있습니다.

다른 SPDF 프로세스(예: 보안 테스트)와 함께 보안 위험 관리 프로세스의 범위와 목표는 취약점을 통한 위협이 환자 피해 및 기타 잠재적 위험을 어떻게 나타낼 수 있는지 밝히는 것입니다. 이러한 프로세스는 또한 한 가지 유형의 위험 평가에 대한 위험 통제 조치가 다른 유형의 새로운 위험을 부주의하게 도입하지 않도록 보장해야 합니다. 예를 들어, AAMI TIR57 및 ANSI/AAMI SW96는 모든 위험이 적절하게 평가되도록 보안 및 안전 위험 관리 프로세스가 어떻게 인터페이스해야 하는지 자세히 설명합니다.[^27] FDA는 QS 규정[^28]에 자세히 설명된 대로 보안 위험 관리 프로세스가 수립되거나 이미 존재하는 프로세스에 통합될 것을 권장하며, 제조업체의 설계, 제조 및 유통 프로세스뿐만 아니라 TPLC 전반의 업데이트를 다루어야 합니다. 이 맥락에서 관련될 수 있는 QS 규정의 프로세스에는 안전 및 보안 위험이 모두 적절하게 다루어지도록 설계 통제(21 CFR 820.30), 생산 프로세스 검증(21 CFR 820.70), 시정 및 예방 조치(21 CFR 820.100)가 포함되지만 이에 국한되지 않습니다. 21 CFR 820.30(g)에 따른 위험 분석 수행의 완전성을 위해, FDA는 기기 제조업체가 환자 안전 위험의 보다 포괄적인 식별 및 관리를 보장하기 위해 안전 위험 평가와 별도의 동반되는 보안 위험 평가를 모두 수행할 것을 권장합니다.

기기는 알려진 취약점을 제거하거나 완화하도록 설계되어야 합니다. 시판된 기기의 경우, 포괄적인 설계 완화가 불가능하면 보상 통제를 고려해야 합니다. 모든 기기에 대해, 알려진 취약점이 기기 설계에 의해 부분적으로만 완화되거나 완화되지 않은 경우, 위험 평가에서 합리적으로 예견 가능한 위험으로 평가되어야 하며 추가 통제 조치 또는 사용자/운영자에 대한 위험 전가[^29]를 위해, 또는 필요한 경우 환자에 대해 평가되어야 합니다. 위험 전가는 적절한 경우, 모든 관련 위험 정보가 알려지고 평가되며 사용자에게 적절하게 전달될 때만 발생해야 하며, 공급망에서 상속된 위험뿐만 아니라 기기 또는 의료기기 시스템의 제조업체 통제 자산이 지원 종료 및 수명 종료에 도달할 때 위험 전가가 어떻게 처리될 것인지, 그리고 사용자가 그 역할을 맡을 수 있는지 여부 또는 방법(예: 사용자가 환자일 수 있는 경우)을 포함합니다.

의료기기 시스템에 대한 보안 위험 관리 활동을 문서화하기 위해, FDA는 제조업체가 AAMI TIR57 및 ANSI/AAMI SW96에 설명된 것과 같은 보안 위험 관리 계획 및 보고서를 생성할 것을 권장합니다.[^30] 제조업체는 기기의 안전성과 효과성을 입증하는 데 도움이 되도록 보안 위험 관리 프로세스의 산출물을 포함한 보안 위험 관리 보고서를 시판 전 제출에 포함해야 합니다. AAMI TIR57 및 ANSI/AAMI SW96에 설명된 것과 같은 보안 위험 관리 보고서는 안전성과 효과성의 합리적인 보증을 입증하는 보안 위험 관리 프로세스 측면을 지원하기에 충분해야 합니다. 이러한 보고서는 아래 섹션에서 설명하는 시스템 위협 모델링, 사이버보안 위험 평가, 소프트웨어 구성 요소 목록(SBOM), 구성요소 지원 정보, 취약점 평가 및 미해결 이상 평가에 대한 문서 요소를 포함해야 합니다.[^31] 아래의 하위 섹션에서는 특정 보안 위험 관리 문서 요소의 범위 및/또는 내용에 관한 FDA의 권장사항을 논의합니다.

위에 나열된 문서 요소를 포함하는 것 외에도, 보안 위험 관리 보고서는 다음을 포함해야 합니다:

- 위험 평가 방법 및 프로세스 요약,
- 보안 위험 평가로부터의 잔여 위험 결론 상세 설명,
- 제조업체의 위험 관리 프로세스의 일부로 수행된 위험 완화 활동 상세 설명, 그리고
- 본 가이던스 후반부에서 논의되는 위협 모델, 사이버보안 위험 평가, SBOM 및 테스트 문서뿐만 아니라 기타 관련 사이버보안 위험 관리 문서 간의 추적 가능성 제공.

### 1. 위협 모델링
위협 모델링에는 의료기기 시스템 전반에 걸쳐 보안 목표, 위험 및 취약점을 식별한 다음, 수명주기 동안 의료기기 시스템에 대한 위협의 영향을 예방, 완화, 모니터링 또는 대응하기 위한 대응책을 정의하는 프로세스가 포함됩니다. 적절하고 포괄적으로 적용될 때 시스템, 제품, 네트워크, 애플리케이션 및 연결 보안을 최적화하는 기초입니다.

보안 위험 관리와 관련하여, 그리고 의료기기 시스템에 대한 적절한 보안 위험 및 통제를 식별하기 위해, FDA는 위협 모델링이 위험 분석 활동을 알리고 지원하기 위해 수행될 것을 권장합니다. 위험 평가의 일부로, FDA는 위협 모델링이 설계 프로세스 전반에 걸쳐 수행되고 모든 의료기기 시스템 요소를 포함할 것을 권장합니다.

위협 모델은 다음을 포함해야 합니다:

- 의료기기 시스템 위험 및 완화 조치를 식별하고 사이버보안 위험 평가의 일부로 고려되는 완화 전 및 완화 후 위험을 알림;
- 의료기기 시스템 또는 사용 환경에 대한 가정을 명시(예: 병원 네트워크는 본질적으로 적대적이므로, 제조업체는 공격자가 패킷을 변경, 삭제 및 재생할 수 있는 능력을 가진 네트워크를 통제한다고 가정하는 것이 권장됨); 그리고
- 공급망, 제조, 배포, 다른 기기와의 상호 운용, 유지보수/업데이트 활동 및 폐기 활동을 통해 도입되어 전통적인 안전 위험 평가 프로세스에서 간과될 수 있는 사이버보안 위험 포착.

FDA는 시판 전 제출에 안전성과 효과성에 영향을 미칠 수 있는 잠재적 보안 위험을 식별하기 위해 의료기기 시스템이 어떻게 분석되었는지 입증하는 위협 모델링 문서를 포함할 것을 권장합니다. 제조업체가 사용하도록 선택할 수 있는 위협 모델링을 위한 여러 방법론 및/또는 방법의 조합이 있습니다.[^32] 선택된 방법론에 대한 근거는 위협 모델링 문서와 함께 제공되어야 합니다. 위협 모델링 문서가 FDA에 어떻게 제출되어야 하는지에 대한 추가 권장사항은 아래 섹션 V.B에서 논의됩니다.

위협 모델링 활동은 설계 검토 중에 수행 및/또는 검토될 수 있습니다. FDA는 위협 모델링 문서가 기기의 안전성과 효과성을 위해 기기 및 기기가 작동하는 시스템을 전체적으로 평가할 수 있도록 기기에 내장된 보안 기능을 평가하고 검토하기 위해 제조업체가 수행한 위협 모델링 활동에 대한 충분한 정보를 포함할 것을 권장합니다.

### 2. 사이버보안 위험 평가
보안 위험 관리의 일부로, 보안 위험 및 통제는 사이버보안 위험 평가의 일부로 잔여 위험에 대해 평가되어야 합니다. 효과적인 보안 위험 평가는 사이버보안 관련 고장이 의도적으로 또는 비의도적으로 발생할 수 있다는 사실을 다룹니다. 따라서 사이버보안 위험은 예측하기 어려우며, 이는 과거 데이터 또는 모델링("확률적 방식"이라고도 함)을 기반으로 사고 발생 가능성을 평가하고 정량화하는 것이 불가능함을 의미합니다. 이러한 비확률적 접근 방식은 ISO 14971에 따른 안전 위험 관리에서 수행되는 기본 접근 방식이 아니며, 안전 및 보안 위험 관리가 구별되지만 연결된 프로세스인 이유를 더욱 강조합니다. 대신, 보안 위험 평가 프로세스는 악용 가능성, 즉 기기 및/또는 시스템 내에 존재하는 취약점을 악용할 수 있는 능력에 초점을 맞춥니다. FDA는 제조업체가 기기 및 기기가 작동하는 시스템에서 제기되는 위험 수준에 따라 식별된 위험을 평가할 것을 권장합니다. 보안 위험 평가를 위한 악용 가능성 평가에 대한 추가 논의는 FDA의 시판 후 사이버보안 가이던스에서 찾을 수 있습니다.

사이버보안 위험의 시판 전 악용 가능성 평가는 시판 후 발견된 취약점의 악용 가능성 평가와 다를 수 있습니다. 이러한 경우, 시판 전 악용 가능성 평가는 최악의 경우 평가를 가정하고 적절한 통제를 구현하거나, TPLC 전반에 걸친 위험의 합리적인 악용 가능성 평가 및 위험이 통제되는 방법에 대한 정당화를 제공할 수 있습니다.

사이버보안 위험에 대한 수용 기준은 기기가 시판된 후 사이버보안 문제를 완화하기가 더 어려울 수 있으므로 의료기기 시스템의 TPLC를 신중하게 고려해야 합니다. 위의 섹션 IV.B 및 V.A에서 논의한 바와 같이, 알려진 취약점은 합리적으로 예견 가능한 위험으로 평가되어야 합니다. 사이버보안 테스트 중에 식별된 취약점에 대한 사이버보안 위험 평가는 취약점의 악용 가능성이 기기 수명주기 동안 증가할 가능성이 있으므로 기기의 TPLC도 고려해야 합니다. 예를 들어, 침투 테스터가 취약점을 악용할 수 있었다면, 위협 행위자가 해당 취약점을 악용할 수 있는 능력은 기기 수명주기 동안 증가할 가능성이 높습니다. 또한, [CISA의 알려진 악용된 취약점 카탈로그](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)에서 식별된 취약점은 이미 악용되고 있으며 의료기기 시스템 및 사용자를 위험에 노출시키므로 기기 설계에서 제거되어야 합니다.

FDA는 시판 전 제출에 제공되는 사이버보안 위험 평가가 위협 모델에서 식별된 위험 및 통제를 포착할 것을 권장합니다. 완화 전후 위험 평가에 사용된 방법 및 관련 수용 기준뿐만 아니라 보안 위험을 안전 위험 평가 프로세스로 전환하는 방법도 시판 전 제출의 일부로 제공되어야 합니다.

### 3. 상호 운용성 고려사항
상호 운용성은 엔드투엔드 의료기기 시스템의 사이버보안을 평가할 때 중요한 고려사항입니다. FDA의 가이던스 "[상호 운용 가능한 의료기기를 위한 설계 고려사항 및 시판 전 제출 권장사항](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/design-considerations-and-pre-market-submission-recommendations-interoperable-medical-devices)"(이하 "상호 운용성 가이던스"라 함)에서 식별된 바와 같이, 상호 운용 가능한 의료기기는 다른 의료 또는 비의료 제품, 시스템 또는 기기와 전자 인터페이스를 통해 정보를 교환하고 사용할 수 있는 능력을 가지고 있습니다.

의료기기 시스템의 일부로서, 기기는 다음을 포함하되 이에 국한되지 않는 인터페이스를 포함한 상호 운용 가능한 기능으로부터 사이버보안 고려사항을 가질 수 있습니다:

- 다른 의료기기 및 액세서리;
- FDA의 가이던스 "[다기능 의료기기 제품: 정책 및 고려사항](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/multiple-function-device-products-policy-and-considerations)"에서 식별된 "기타 기능";
- 의료 인프라(예: 네트워크, 전자 의무 기록, 의료 영상 시스템); 그리고
- 범용 컴퓨팅 플랫폼.

사이버보안 통제는 상호 운용성을 허용하기 위한 인터페이스의 복잡성을 증가시킬 수 있지만, 적절하게 구현되면 사이버보안 통제는 이러한 기능이 안전하고 효과적으로 유지되도록 보장하는 데 도움이 될 수 있습니다. 사이버보안 통제는 정보의 안전하고 효과적인 교환 및 사용을 허용하는 수단으로 사용되어야 합니다. 또한, 사이버보안 통제는 사용자가 자신의 기기 데이터에 접근하는 것을 금지하기 위한 것이어서는 안 됩니다.

상호 운용성을 가능하게 하기 위해 공통 기술 및 통신 프로토콜이 사용되는 경우(예: 블루투스, 블루투스 저에너지, 네트워크 프로토콜), 기기 제조업체는 기기의 안전성과 효과성을 보장하기 위해 이러한 통신 하위에 추가된 보안 통제가 필요한지 평가해야 합니다(예: 블루투스 저에너지 프로토콜 또는 지원 기술에서 취약점이 발견될 경우 위험을 방지하기 위해 블루투스 저에너지 하위에 추가된 보안 통제).

[상호 운용성 가이던스](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/design-considerations-and-pre-market-submission-recommendations-interoperable-medical-devices)의 권장사항 외에도, 제조업체는 상호 운용성 기능과 관련된 적절한 사이버보안 위험 및 통제를 고려해야 하며 본 가이던스 전반에 걸쳐 권장되는 대로 이러한 고려사항을 문서화해야 합니다.

### 4. 타사 소프트웨어 구성요소
FDA의 가이던스 "[의료기기에서 상용(OTS) 소프트웨어 사용](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/shelf-ots-software-use-medical-devices)"에서 논의된 바와 같이, 의료기기는 일반적으로 상용 및 오픈 소스 소프트웨어를 포함한 타사 소프트웨어 구성요소[^33]를 포함합니다. 이러한 구성요소가 통합될 때, 소프트웨어 구성요소의 보안 위험은 전체 의료기기 시스템 위험 관리 프로세스 및 문서의 요소가 되어야 합니다.

21 CFR 820.30(g)에 따른 설계 통제 준수를 입증하고 공급망 위험 관리 프로세스를 지원하기 위해, 기기 제조업체가 개발한 소프트웨어("독점 소프트웨어") 또는 타사로부터 획득한 소프트웨어를 포함한 모든 소프트웨어는 사이버보안 위험에 대해 평가되어야 합니다. 기기 제조업체는 기기의 모든 소프트웨어 구성요소를 문서화하고 이러한 소프트웨어 구성요소와 관련된 위험을 해결하거나 완화해야 합니다.

또한, 21 CFR 820.50에 따라, 제조업체는 공급업체가 제조업체의 요구사항을 준수하도록 보장하기 위한 프로세스 및 통제를 마련해야 합니다. 이러한 정보는 21 CFR 820.30(j)에서 요구하는 설계 이력 파일과 21 CFR 820.181에서 요구하는 기기 마스터 기록에 문서화됩니다. 이 문서는 기기의 QS 규정에 대한 전반적인 준수뿐만 아니라 타사 구성요소가 기기에 대해 설정된 사양을 충족함을 입증합니다. 타사 소프트웨어 및 소프트웨어 공급망에 존재하거나 도입될 수 있는 사이버보안 위험에 대한 분석 및 고려사항을 포함하는 보안 위험 평가는 제조업체가 이러한 준수를 적절하게 보장하고 이러한 이력을 문서화했음을 입증하는 데 도움이 될 수 있습니다.

소프트웨어는 추가 기능을 제공하고, 보안 문제를 해결하며, 그 외 유지 관리되기 위해 시간이 지남에 따라 업데이트됩니다. 이러한 변경사항은 위험 관리의 일부로 고려되어야 하는 새로운 고려사항 또는 위험을 도입할 수 있습니다. 결과적으로, 기기 제조업체는 구성 관리의 일부로 기기 수명주기 동안 기기 소스 코드(소프트웨어의 원본 "사본")에 대한 관리 통제를 수립하고 유지해야 합니다.[^34] 이는 소스 코드 에스크로 또는 소스 코드 백업 등 다양한 방법을 통해 달성될 수 있습니다.[^35]

제조업체는 라이선스 제한, 공급업체 계약 조건 또는 기타 문제로 인해 소스 코드를 통제하지 못할 수 있습니다. 소스 코드는 시판 전 제출에 제공될 필요는 없지만, 제조업체는 지원이 종료되거나 기타 소프트웨어 문제가 발생할 경우 타사 소프트웨어 구성요소를 어떻게 업데이트하거나 교체할 수 있는지에 대한 계획을 시판 전 제출에 포함해야 합니다. 기기 제조업체는 또한 알려진 취약점, 구성 사양 및 기타 관련 보안 및 위험 관리 고려사항을 포함하여 소프트웨어 구성요소와 관련된 위험을 관리할 수 있도록 사용자가 필요로 할 수 있는 모든 정보를 기기 라벨링에 제공해야 합니다.

공급망 위험 관리를 돕고 기기에 통합된 소프트웨어를 명확하게 식별하고 추적하는 데 도움이 되는 한 가지 도구는 아래에 설명된 SBOM입니다.

#### (a) 소프트웨어 구성 요소 목록(SBOM)
SBOM은 소프트웨어 스택 전반에 존재하는 사이버보안 위험의 관리를 지원할 수 있습니다. 강력한 SBOM에는 기기 제조업체가 개발한 구성요소와 타사 구성요소가 모두 포함되며, 여기에는 구매/라이선스된 소프트웨어 및 오픈 소스 소프트웨어뿐만 아니라 독점, 구매/라이선스 및 오픈 소스 소프트웨어에서 요구/의존하는 업스트림 소프트웨어 종속성이 포함됩니다.

SBOM은 소프트웨어가 구성요소로 선택되는 개발 중과 제품 수명의 다른 모든 단계에 걸쳐 시장에 출시된 후 모두에서 소프트웨어 구성요소의 취약점에 의해 영향을 받을 수 있는 기기 및 기기가 작동하는 시스템을 식별하는 메커니즘을 제공함으로써 위험 관리 프로세스를 용이하게 하는 데 도움이 됩니다.[^36] 취약점 관리는 기기의 보안 위험 관리 프로세스의 중요한 부분이므로, SBOM 또는 이에 상응하는 기능은 기기의 구성 관리의 일부로 유지되어야 하고, 시판된 기기의 소프트웨어 변경사항을 반영하기 위해 정기적으로 업데이트되어야 하며, 21 CFR 820.30(j)(설계 이력 파일) 및 820.181(기기 마스터 기록)에 자세히 설명된 유형과 같은 문서를 지원해야 합니다.

사이버보안과 관련된 기기 위험 및 안전성과 효과성에 미치는 관련 영향에 대한 FDA의 평가를 지원하기 위해, FDA는 시판 전 제출에 아래에 설명된 대로 SBOM 문서를 포함할 것을 권장합니다. 사이버 기기의 경우, SBOM은 필수입니다(FD&C법 524B(b)(3)조 및 본 가이던스의 섹션 VII.C.3 참조). SBOM은 또한 나중에 섹션 VI에서 다루는 라벨링의 일부로 잠재적 위험에 대한 사용자와의 투명성을 위한 중요한 도구가 될 수 있습니다.

#### (b) 소프트웨어 구성 요소 목록을 지원하는 문서
FDA의 가이던스 문서 "[의료기기에서 상용(OTS) 소프트웨어 사용](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/shelf-ots-software-use-medical-devices)"은 제조업체가 완전한 소프트웨어 수명주기 통제를 주장할 수 없는 소프트웨어 구성요소에 대해 시판 전 제출에 제공되어야 하는 정보를 설명합니다. 해당 가이던스에서 권장하는 정보 외에도, 제조업체는 2021년 10월 국가 통신 정보 관리국(NTIA) 소프트웨어 구성요소 투명성에 관한 다자간 이해관계자 프로세스 문서 "[소프트웨어 구성요소 투명성 프레이밍: 공통 소프트웨어 구성 요소 목록(SBOM) 수립](https://www.ntia.gov/files/ntia/publications/sbom_minimum_elements_report.pdf)"에서 식별된 최소 요소("기준 속성"이라고도 함)와 일치하는 기계 판독 가능한 SBOM을 제공해야 합니다.

NTIA에서 식별한 최소 요소 외에도, SBOM에 포함된 각 소프트웨어 구성요소에 대해 제조업체는 시판 전 제출에 다음을 포함해야 합니다:

- 소프트웨어 구성요소 제조업체의 모니터링 및 유지보수를 통해 제공되는 소프트웨어 지원 수준(예: 소프트웨어가 적극적으로 유지 관리됨, 더 이상 유지 관리되지 않음, 중단됨); 그리고
- 소프트웨어 구성요소의 지원 종료 날짜.

제공되는 경우, 제조업체는 이러한 추가 요소를 SBOM의 일부로 제공하거나 부록과 같이 별도로 제공할 수 있습니다. 산업계에서 인정하는 SBOM 형식이 권장됩니다.

제조업체가 FDA에 SBOM 정보를 제공할 수 없는 경우, 제조업체는 시판 전 제출에 정보가 포함될 수 없는 이유에 대한 정당화를 제공해야 합니다.

시판 전 제출의 일부로, 제조업체는 또한 [CISA의 알려진 악용된 취약점 카탈로그](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)에서 식별된 것을 포함하여 기기 및 소프트웨어 구성요소와 관련된 모든 알려진 취약점을 식별해야 합니다. 각 알려진 취약점에 대해, 제조업체는 평가 방법이 충분히 견고했는지 입증하기 위해 취약점이 어떻게 발견되었는지 설명해야 합니다. 알려진 취약점이 있는 구성요소의 경우, 기기 제조업체는 시판 전 제출에 다음을 제공해야 합니다:

- 각 알려진 취약점에 대한 안전 및 보안 위험 평가(기기 및 시스템 영향 포함); 그리고
- 취약점을 해결하기 위한 적용 가능한 안전 및 보안 위험 통제의 세부사항. 위험 통제에 보상 통제가 포함되는 경우, 적절한 수준의 세부사항으로 설명되어야 합니다.

독점 및 타사 구성요소와 관련된 추가 정보 및 논의는 아래 섹션 V.B.2, 보안 아키텍처 뷰를 참조하십시오.

### 5. 미해결 이상의 보안 평가
FDA의 [시판 전 소프트웨어 가이던스](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/guidance-content-premarket-submissions-software-contained-medical-devices)는 기기 제조업체가 제출 시점에 제품에 존재하는 소프트웨어 이상 목록을 제공할 것을 권장합니다. 각 이상에 대해, FDA는 기기 제조업체가 이상이 기기의 안전성과 효과성에 미치는 영향을 평가하고, 해당 기기의 시판 전 제출에 포함할 것이 권장되는 관련 문서를 평가하기 위해 시판 전 소프트웨어 가이던스를 참조할 것을 권장합니다.

개발 또는 테스트 중에 발견된 일부 이상은 보안 영향을 가질 수 있으며 취약점으로도 간주될 수 있습니다. 21 CFR Part 820.30(g)에 따른 완전한 보안 위험 평가를 보장하는 일부로, 안전성과 효과성에 미치는 영향에 대한 평가는 이상의 잠재적 보안 영향에 대한 평가를 포함할 수 있습니다. 평가는 또한 존재하는 모든 일반적 약점 열거(CWE) 범주의 고려를 포함해야 합니다.[^37]

예를 들어, 임상 사용자는 정상 사용 중에 이전에 알려지지 않은 소프트웨어 이상의 존재를 부주의하게 드러낼 수 있으며, 이상의 영향은 산발적으로 발생할 수 있고 소프트웨어 위험 관점에서 허용 가능한 것으로 평가될 수 있습니다. 반대로, 위협은 이러한 유형의 이상을 찾아내고 이상의 영향을 지속적으로 나타내기 위해 이를 악용하는 수단을 식별할 수 있으며, 이는 보안 고려사항을 포함하지 않은 이상 평가와 비교할 때 위험의 허용 가능성에 상당한 영향을 미칠 수 있습니다.

보안 영향이 있는 결과적 이상을 다루기 위한 기준 및 근거는 시판 전 제출의 문서 일부로 제공되어야 합니다.

### 6. TPLC 보안 위험 관리
사이버보안 위험은 기기의 TPLC 전반에 걸쳐 계속 식별될 수 있습니다. 제조업체는 지원되는 기기 수명주기 전반에 걸쳐 식별되는 사이버보안 취약점을 식별, 평가 및 완화할 적절한 자원을 확보해야 합니다.

SPDF를 사용하는 일부로, 제조업체는 개발 중 및 기기가 출시된 후 새로운 위협, 취약점, 자산 또는 부정적 영향이 발견될 때와 같이 새로운 정보가 이용 가능해질 때 보안 위험 관리 문서를 업데이트해야 합니다. 기기 수명주기 전반에 걸쳐 유지될 때, 이 문서(예: 위협 모델링, 사이버보안 위험 평가)는 기기가 출시되면 취약점 영향을 신속하게 식별하고, 적절한 경우 21 CFR 820.100에 설명된 시기적절한 시정 및 예방 조치 활동을 지원하는 데 사용될 수 있습니다.

기기의 서비스 수명 동안, FDA는 위험 관리 문서가 배치된 기기(예: 시판된 기기 또는 더 이상 시판되지 않지만 여전히 사용 중인 기기)에 대한 위험 관리의 차이를 설명할 것을 권장합니다. 예를 들어, 모든 배치된 기기에 대해 업데이트가 자동으로 적용되지 않는 경우, 기기의 서로 다른 소프트웨어 구성에 대해 서로 다른 위험 프로필이 있을 가능성이 높습니다. FDA는 환자 위험이 정확하게 평가되도록 모든 배치된 버전에 대해 서로 다른 영향에 대해 취약점이 평가될 것을 권장합니다.

시판 후 취약점 및 일반적인 시판 후 사이버보안 위험 관리를 기반으로 새로운 시판 전 제출(예: PMA, PMA 보완 또는 510(k)) 또는 21 CFR Part 806 보고가 필요한지 여부에 대한 추가 정보는 시판 후 사이버보안 가이던스에서 논의됩니다.

제조업체 프로세스의 효과성을 입증하기 위해, FDA는 제조업체가 아래의 측정 및 메트릭을 추적 및 기록하고[^38], 이용 가능한 경우 시판 전 제출 및 PMA 연간 보고서(21 CFR 814.84)에 제공할 것을 권장합니다.[^39] SPDF를 정의하는 프로세스에 대한 적절한 측정 및 메트릭을 선택하는 것은 기기 설계가 QS 규정을 준수하여 사이버보안을 적절하게 다루도록 보장하는 데 중요합니다. 최소한, FDA는 다음 측정 및 메트릭 또는 동등한 정보를 제공하는 것을 추적할 것을 권장합니다:

- 업데이트되거나 패치된 식별된 취약점의 백분율(결함 밀도);
- 취약점 식별부터 업데이트되거나 패치될 때까지의 기간; 그리고
- 업데이트 또는 패치가 이용 가능한 때부터 현장에 배치된 기기에서 완전히 구현될 때까지의 기간(알려진 범위 내에서).

위의 측정의 평균은 여러 취약점이 식별되고 해결되는 경우 제공되어야 합니다. 이러한 평균은 볼륨을 기반으로 여러 시간 프레임에 걸쳐 제공되거나 시간이 지남에 따라 이러한 측정의 효율성을 높이기 위한 프로세스 또는 절차 변경에 대응하여 제공될 수 있습니다.

## B. 보안 아키텍처
제조업체는 자신의 기기 및 해당 기기가 작동할 것으로 예상되는 시스템의 사이버보안 위험을 식별하고, 이러한 위험을 완화하기 위한 적절한 통제를 구현할 책임이 있습니다. 이러한 위험에는 예를 들어 병원 네트워크, 클라우드 인프라 또는 "기타 기능"(FDA의 가이던스 "[다기능 의료기기 제품: 정책 및 고려사항](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/multiple-function-device-products-policy-and-considerations)"에 정의된 대로)에 대한 기기 의존성으로 도입된 것들이 포함될 수 있습니다. 시스템 아키텍처와 마찬가지로 보안 아키텍처는 시스템과 시스템으로의 및/또는 시스템 밖으로의 모든 엔드투엔드 연결을 정의합니다. 보안 아키텍처 정의 프로세스[^40]는 상호 작용하는 기기 및/또는 시스템의 상위 수준 정의와 이러한 상호 작용이 발생하고 보안되는 방법에 대한 구현의 상세한 정보를 모두 포함합니다. 이는 위험 관리 프로세스 중에 고려된 위험이 적절하게 통제되고 있음을 입증하는 정보를 포함하며, 이는 결과적으로 의료기기 시스템의 안전성과 효과성 입증을 지원합니다.

21 CFR 820.30(b)에 따라, 제조업체는 설계 및 개발 활동을 설명하거나 참조하고 구현에 대한 책임을 정의하는 계획을 수립하고 유지해야 합니다. 이러한 계획은 설계 및 개발이 진화함에 따라 검토, 업데이트 및 승인되어야 합니다(21 CFR 820.30(b)). 21 CFR 820.30(c)에 따라, 제조업체는 기기와 관련된 설계 요구사항이 적절하고 사용자 및 환자의 필요를 포함하여 기기의 의도된 사용을 다루도록 보장하는 절차를 수립하고 유지해야 합니다. 21 CFR 820.30(d)에 따라, 제조업체는 설계 입력 요구사항에 대한 적합성의 적절한 평가를 허용하는 용어로 설계 출력을 정의하고 문서화하는 절차를 수립하고 유지해야 합니다. 21 CFR 820.30(d)는 또한 설계 출력 절차가 수용 기준을 포함하거나 참조해야 하며 기기의 적절한 기능을 위해 필수적인 설계 출력이 식별되도록 보장해야 한다고 명시합니다.

FDA는 이러한 계획 및 절차가 기기 및 기기가 작동하는 시스템에 대한 사이버보안 고려사항을 전체적으로 다루도록 기기의 보안 아키텍처에 대한 설계 프로세스, 설계 요구사항 및 수용 기준을 포함할 것을 권장합니다. FDA는 모든 의료기기가 위의 섹션 IV에 있는 보안 목표를 제공하고 시행할 것을 권장하지만, 보안 목표를 다루기 위한 구현은 다를 수 있음을 인식합니다.

FDA는 시판 전 제출에 보안 아키텍처에 대한 문서를 포함할 것을 권장합니다. 시판 전 제출에서 보안 아키텍처 정보를 제공하는 목적은 의료기기 시스템이 외부 엔티티와 갖는 인터페이스, 상호 연결 및 상호 작용의 관점에서 의료기기 시스템의 보안 컨텍스트 및 신뢰 경계를 FDA에 제공하는 것입니다. 이러한 요소의 세부사항은 사고가 발생할 수 있는 의료기기 시스템의 부분을 식별할 수 있게 합니다. 이러한 세부사항은 FDA가 안전성과 효과성과 관련하여 아키텍처 자체의 적절성을 평가할 수 있도록 시스템에 대한 충분한 이해를 제공하는 데 도움이 됩니다.

제조업체는 기기가 작동할 것으로 예상되는 전체 환경 및 컨텍스트를 이해하기 위해 전체 시스템을 분석해야 합니다. 보안 아키텍처는 공급망과 관련된 위험(예: 기기가 악성 소프트웨어로부터 자유롭게 유지되거나 타사 소프트웨어와 같은 업스트림 종속성으로부터 상속된 취약점 등), 설계, 생산 및 배포(즉, 연결된/네트워크화된 환경으로)를 포함하되 이에 국한되지 않는 시스템 수준 위험의 고려를 포함해야 합니다.

FDA는 이 아키텍처 정보가 "뷰"의 형태를 취하고, 이러한 뷰가 안전성과 효과성을 입증하기 위해 시판 전 제출 중에 제공될 것을 권장합니다.[^41] 이 섹션에서 식별된 문서가 이미 다른 위험 관리 문서에 존재하는 경우, FDA는 제조업체가 이 정보를 새로운 문서로 분리할 것을 기대하지 않습니다; 이러한 문서는 제공될 수 있으며 제출은 관련 섹션을 참조할 수 있습니다.

아래에서 FDA는 특정 보안 아키텍처 뷰를 통해 시판 전 제출에서 권장되는 보안 통제 및 결과 보안 아키텍처를 문서화하는 방법을 설명합니다.

### 1. 보안 통제 구현
FDA는 기기가 사이버보안 위험을 다루는 방식과 기기가 사이버보안 위협에 노출될 때 대응하는 방식을 기기 설계의 기능으로 간주합니다. 효과적인 사이버보안은 보안이 기기에 "내장"되는 것에 의존하며, 기기가 설계된 후에 "덧붙여지는" 것이 아닙니다. FDA는 기기 제조업체의 설계 프로세스가 사이버보안 통제에 대한 설계 입력을 포함할 것을 권장합니다.[^42] 21 CFR 820.30(c)에 따라, 제조업체는 기기와 관련된 설계 요구사항이 적절하고 사용자 및 환자의 필요를 포함하여 기기의 의도된 사용을 다루도록 보장하는 절차를 수립하고 유지해야 합니다. 21 CFR 820.30(d)에 따라, 제조업체는 설계 입력 요구사항에 대한 적합성의 적절한 평가를 허용하는 용어로 설계 출력을 정의하고 문서화하는 절차를 수립하고 유지해야 합니다. 이러한 출력 절차는 수용 기준을 포함하거나 참조해야 하며 기기의 적절한 기능을 위해 필수적인 설계 출력이 식별되도록 보장해야 합니다.

FDA는 이러한 절차가 기기 및 기기가 작동하는 시스템에 대한 사이버보안 고려사항을 전체적으로 다루도록 기기에 내장된 보안 기능에 대한 설계 요구사항 및 수용 기준을 포함할 것을 권장합니다.

보안 통제는 제조업체가 섹션 IV에 설명된 보안 목표를 달성할 수 있게 하며 SPDF의 필수 부분입니다. FDA는 적절한 보안 통제 세트가 다음 범주의 통제를 포함하되 반드시 이에 국한되지 않아야 함을 권장합니다:

- 인증(Authentication);
- 권한 부여(Authorization);
- 암호화(Cryptography);
- 코드, 데이터 및 실행 무결성(Code, Data, and Execution Integrity);
- 기밀성(Confidentiality);
- 이벤트 탐지 및 로깅(Event Detection and Logging);
- 복원력 및 복구(Resiliency and Recovery); 그리고
- 업데이트 가능성 및 패치 가능성(Updatability and Patchability).

위의 각 보안 통제 범주에 대해, 일반적인 함정을 피하기 위한 특정 통제 권장사항 및 구현 지침이 부록 1에 자세히 설명되어 있습니다.

보안 통제의 구현은 해당 연결 및 기기와 관련된 위험 기반 결정을 사용하여 시스템 아키텍처 전반에 적용되어야 합니다. 관리적, 기술적 및 운영적 통제를 포함하는 의료기기 시스템 전반에 걸친 적절한 보안 통제 없이는 안전성과 효과성의 합리적인 보증이 없습니다. 또한, 선택된 보안 통제의 설계 또는 이러한 통제의 구현에서의 결함은 기기가 안전성과 효과성을 입증하거나 유지하는 능력에 극적인 영향을 미칠 수 있습니다.

FDA는 안전성과 효과성을 입증하기 위해 위의 각 범주에 대한 요구사항 및 수용 기준이 시판 전 제출에 제공될 것을 권장합니다. 제조업체는 부록 1의 권장사항에 더 자세히 설명된 위의 범주에 대한 보안 통제가 (1) 구현되었으며, (2) 효과적으로 구현되었음을 검증하기 위해 테스트되었음을 입증하는 문서를 시판 전 제출에 제출해야 합니다. 사이버보안 테스트에 대한 자세한 정보는 아래 섹션 V.C를 참조하십시오.

제조업체는 시판 전 제출에 부록 1에 설명된 것과 비교 가능하거나 추가적인 보안 통제의 입증을 포함할 수 있습니다. 본 문서에 설명되지 않은 대체 통제를 사용하는 경우, 제조업체는 적절한 수준의 안전성과 효과성을 제공함을 입증하기 위해 특정 설계 기능 및 보안 통제를 관련 위험에 추적하는 문서를 제공해야 합니다. 사이버보안 설계 통제는 개발 단계 초기에 수립되므로, FDA는 기기 제조업체가 기기 수명주기 동안 사이버보안 위험 관리에 대한 설계 고려사항을 기관과 논의하기 위해 FDA Q-제출 프로세스를 활용할 것을 권장합니다.[^43] 설계 통제에 대한 시판 전 문서 권장사항에 대한 추가 정보는 아래 보안 아키텍처 뷰 섹션에서 논의됩니다.

### 2. 보안 아키텍처 뷰
설계 통제 요구사항[^44] 외에도, 21 CFR 820.100은 제조업체가 시정 및 예방 조치를 구현하기 위한 절차를 수립하고 유지할 것을 요구하며, 이는 무엇보다도 품질 문제의 기존 및 잠재적 원인을 식별하기 위한 품질 데이터 분석 요구사항을 포함해야 합니다. FDA는 제조업체가 의료기기 시스템의 설계, 개발 및 유지보수 프로세스의 일부로 보안 아키텍처 뷰 문서를 개발하고 유지할 것을 권장합니다. 시정 및 예방 조치가 식별되는 경우, 이러한 뷰는 영향을 받는 기능과 위험을 다루는 솔루션을 식별하는 데 도움이 될 수 있습니다.

FDA는 시판 전 제출에 이 섹션에서 설명하는 아키텍처 뷰를 포함할 것을 권장합니다. 이러한 아키텍처 뷰는 사이버보안 위험을 다루기 위한 통제가 의료기기 시스템에 어떻게 적용되었는지 보여줌으로써 시판 전 제출에서 안전성과 효과성 입증에 기여할 수 있습니다.

보안 아키텍처는 다양한 추상화 수준과 다양한 범위 또는 뷰로 표현될 수 있습니다.[^45] 제출에 제공되는 아키텍처 뷰의 수와 범위는 의료기기 시스템에 대한 위협 모델링 및 위험 평가를 통해 식별된 공격 표면에 따라 달라집니다. 따라서 이러한 뷰는 FDA에 위협 모델링 정보를 제공하는 효과적인 방법이 될 수 있으며 기기의 사이버보안 위험에 따라 제공되는 문서를 자연스럽게 확장할 것입니다.

FDA는 시판 전 제출에 최소한 다음 유형의 뷰를 제공할 것을 권장합니다:

- 글로벌 시스템 뷰(Global System View);
- 다중 환자 피해 뷰(Multi-Patient Harm View);
- 업데이트 가능성/패치 가능성 뷰(Updateability/Patchability View); 그리고
- 보안 사용 사례 뷰(Security Use Case View(s)).

시판 전 제출에 이러한 뷰를 문서화하는 것은 다이어그램과 설명 텍스트를 모두 포함해야 합니다. 이러한 다이어그램과 설명 텍스트는 의료기기 시스템 내의 자산이 관련 구현 세부사항 내에서 전체적으로 어떻게 기능하는지 이해할 수 있도록 충분한 세부사항을 포함해야 합니다. 보안 아키텍처 뷰의 경우, 제조업체는 시판 전 제출에 포함할 세부 수준을 결정할 때 부록 2에 설명된 권장사항을 따라야 합니다.

이러한 보안 아키텍처 뷰는 다음을 수행해야 합니다:

- 보안 관련 의료기기 시스템 요소 및 그 인터페이스 식별;
- 의료기기 시스템의 보안 컨텍스트, 도메인, 경계, 중요 사용자 역할 및 외부 인터페이스 정의;
- 아키텍처를 (a) 의료기기 시스템 보안 목표 및 요구사항, (b) 식별된 위협을 다루기 위한 보안 설계 특성과 정렬; 그리고
- 아키텍처 요소와 사용자 및 의료기기 시스템 보안 요구사항 간의 추적 가능성 수립. 이러한 추적 가능성은 사이버보안 위험 관리 문서 전반에 걸쳐 존재해야 합니다.

특정 뷰가 위에서 식별된 다른 뷰의 위험을 충분히 포착하는 경우, 제조업체가 문서를 중복으로 작성할 것을 기대하지 않습니다. 마찬가지로, 위협 모델링 문서가 뷰를 충분히 포착하는 경우, 제조업체가 문서를 중복으로 작성할 것을 기대하지 않습니다. 또한, 위에 나열된 뷰 중 하나가 적절하지 않은 경우, 제조업체는 대신 해당 뷰가 시판 전 제출에 포함되지 않은 이유에 대한 설명을 제공해야 합니다.

시판 전 제출에서 이러한 보안 뷰의 범위는 아키텍처 및 기기에 제기되는 잠재적 사이버보안 위험을 기반으로 확장될 것으로 예상됩니다. 예를 들어, 네트워크 및/또는 클라우드 액세스가 있는 의료기기 시스템은 USB 인터페이스만 있는 의료기기 시스템보다 더 많은 보안 사용 사례 뷰를 가질 것으로 예상됩니다.

#### (a) 글로벌 시스템 뷰
글로벌 시스템 뷰는 기기 자체 및 모든 내부 및 외부 연결을 포함한 전체 의료기기 시스템을 설명해야 합니다. 상호 연결되고 네트워크화된 기기의 경우, 이 뷰는 소프트웨어 업데이트 인프라, 의료 시설 네트워크 영향, 중간 연결 또는 기기, 클라우드 연결 및 환자 가정 네트워크 영향을 포함한 모든 상호 연결된 요소를 식별해야 합니다.

의료기기 시스템의 복잡성에 따라, 단일 글로벌 시스템 뷰에 모든 데이터 흐름 세부사항을 포함하는 것이 실현 가능하지 않을 수 있습니다. 부록 2에서 권장하는 대로 통신 세부사항을 상세히 설명하는 추가 뷰가 제공될 수 있으며, 아래에 상세히 설명된 다른 유형의 뷰 중 하나에 포착된 경우 중복될 필요가 없습니다.

#### (b) 다중 환자 피해 뷰
기기가 다른 의료 또는 비의료 제품에, 네트워크에 또는 인터넷에 (유선 또는 무선으로) 연결할 수 있는 경우, 여러 기기가 동시에 손상될 가능성이 있습니다. 이러한 연결성으로 인해, 기기가 손상되거나 기기 기능에 영향을 미칠 수 있는 비기기 기능(즉, FD&C법 201(h)조에 해당하지 않는 모든 기능)이 손상되는 경우, 기기는 보안 위험을 통해 환자에게 안전 위험을 도입할 수 있습니다. 이는 기기의 기능을 변경할 수 있습니다. 예를 들어, 비기기 기능이 해킹되어 기기 기능을 수행하고 궁극적으로 환자에게 해를 끼칠 수 있습니다.

기기 위험 및 사용 환경에 따라, 다중 기기 손상은 기기 자체 및/또는 의료 시설 운영에 대한 영향을 통해 여러 환자에게 심각한 영향을 미칠 수 있습니다(예: 모든 다중 매개변수 침상 모니터가 한 번에 재시작되어 동일한 네트워크에 연결된 모든 모니터가 더 이상 환자 활력 징후를 모니터링하지 않고 인력 수준이 모든 환자 활력 징후를 모니터링할 수 없게 됨).

FDA는 제조업체가 다중 환자 피해 뷰에서 여러 환자에게 해를 끼칠 가능성이 있는 공격에 대해 기기 및 기기가 작동하는 시스템이 어떻게 방어하고/또는 대응하는지 다룰 것을 권장합니다. 이 뷰는 부록 2에서 권장하는 정보를 포함해야 합니다. 일단 식별되면, 이러한 위험은 위험의 다른 특성으로 인해 동반되는 사이버보안 위험 평가에서 다르게 평가되어야 할 수도 있습니다.

#### (c) 업데이트 가능성 및 패치 가능성 뷰
기기의 TPLC 전반에 걸쳐 새로운 사이버보안 위험을 해결하기 위해 기기에 시기적절하고 신뢰할 수 있는 업데이트를 제공해야 하는 필요성과 함께, FDA는 제조업체가 업데이트 가능성 및 패치 가능성 뷰를 제공할 것을 권장합니다. 이 뷰는 소프트웨어 업데이트 및 패치가 기기에 제공(즉, 배포)될 수 있도록 하는 엔드투엔드 프로세스를 설명해야 하며, 부록 2에서 권장하는 대로 상세한 정보를 포함해야 합니다.

예를 들어, 기기 제조업체가 소프트웨어 업데이트 서버에서 클리닉 내 심장 임플란트 프로그래머로 소프트웨어를 푸시하려는 경우, "엔드투엔드"는 업데이트 서버에서 임플란트된 기기를 프로그래밍하는 클리닉 내 프로그래머까지의 경로를 의미합니다. 소프트웨어 업데이트 경로는 기기 제조업체가 통제하지 않는 기술을 통과할 가능성이 높으므로, 기기 설계는 엔드투엔드 경로의 보호를 제공하고 제조업체가 통제하지 않는 기술에 의해 생성되거나 제기되는 추가 사이버보안 위험을 고려해야 합니다.

#### (d) 보안 사용 사례 뷰
위에서 식별된 뷰 외에도, 보안 사용 사례 뷰도 제공되어야 합니다. 보안 사용 사례는 보안 손상이 기기의 안전성 또는 효과성에 영향을 미칠 수 있는 모든 의료기기 시스템 기능에 대해 포함되어야 합니다. 이러한 보안 사용 사례는 의료기기 시스템의 요소의 다양한 작동 상태(예: 전원 켜기, 대기, 전환 상태)를 다루어야 하며 의료기기 시스템의 임상 기능 상태(예: 프로그래밍, 알람, 치료 제공, 데이터 송수신, 진단 결과 보고)를 평가해야 합니다.

평가되어야 하는 보안 사용 사례의 수는 기기의 사이버보안 복잡성 및 위험에 따라 확장될 것입니다. 각 뷰는 부록 2에서 권장하는 대로 상세한 정보를 포함해야 합니다. 동일한 보안 평가를 공유하는 것으로 식별된 사용 사례의 경우, 관련 다이어그램 및 설명 텍스트는 여러 곳에 중복 정보를 제공하는 대신 뷰에서 다루는 여러 사용 사례를 설명할 수 있습니다. 예를 들어, 프로그래밍 명령과 기기 데이터 송수신은 동일한 통신 프로토콜을 공유할 수 있으므로 임상 위험 평가가 다름에도 불구하고 두 시나리오에 대한 보안 뷰 간에 차이를 나타내지 않을 수 있습니다.

## C. 사이버보안 테스트
제품 개발의 다른 영역과 마찬가지로, 테스트는 설계 통제의 효과성을 입증하는 데 사용됩니다. 소프트웨어 개발과 사이버보안은 밀접하게 관련된 분야이지만, 사이버보안 통제는 적절한 보안 컨텍스트에서 통제의 효과성을 입증하고 따라서 기기가 안전성과 효과성의 합리적인 보증을 가지고 있음을 입증하기 위해 표준 소프트웨어 검증 및 타당성 확인 활동을 넘어서는 테스트가 필요합니다.

21 CFR 820.30(f)에 따라, 제조업체는 기기 설계를 검증하기 위한 절차를 수립하고 유지해야 합니다. 이러한 검증은 설계 출력이 설계 입력 요구사항을 충족함을 확인해야 합니다. 21 CFR 820.30(g)에 따라, 제조업체는 기기 설계를 타당성 확인하기 위한 절차를 수립하고 유지해야 합니다. 이러한 설계 타당성 확인은 적절한 경우 소프트웨어 타당성 확인 및 위험 분석을 포함해야 합니다. FDA는 검증 및 타당성 확인이 제조업체가 적절하게 입력 및 출력을 검증하고 타당성을 확인하는 의료기기 시스템의 사이버보안에 대해 제조업체가 수행하는 충분한 테스트를 포함할 것을 권장합니다.

보안 테스트 문서 및 관련 보고서 또는 평가는 시판 전 제출에 제출되어야 합니다. FDA는 무엇보다도 다음 유형의 테스트가 제출에 포함되는 것을 고려할 것을 권장합니다:

- 보안 요구사항;
  - 제조업체는 각 설계 입력 요구사항이 성공적으로 구현되었다는 증거를 제공해야 합니다.
  - 제조업체는 경계 분석 및 경계 가정에 대한 근거의 증거를 제공해야 합니다.
- 위협 완화;
  - 제조업체는 글로벌 시스템, 다중 환자 피해, 업데이트 가능성 및 패치 가능성, 그리고 보안 사용 사례 뷰에서 제공된 위협 모델에 따른 효과적인 위험 통제 조치를 입증하는 테스트의 세부사항 및 증거를 제공해야 합니다.
  - 제조업체는 각 사이버보안 위험 통제의 적절성(예: 지정된 보안 정책을 시행하는 보안 효과성, 최대 트래픽 조건에 대한 성능, 안정성 및 신뢰성, 적절한 경우)을 보장해야 합니다.
- 취약점 테스트(예: ANSI/ISA 62443-4-1의 섹션 9.4); 그리고
  - 제조업체는 다음 테스트 및 분석의 세부사항 및 증거[^46]를 제공해야 합니다:
    - 남용 또는 오용 사례, 잘못된 형식 및 예상치 못한 입력;
      - 견고성.
      - 퍼즈 테스트.
    - 공격 표면 분석;
    - 취약점 체이닝;
    - 알려진 취약점 스캐닝의 블랙박스 테스트;
    - 바이너리 실행 파일의 소프트웨어 구성 분석; 그리고
    - "하드코딩된", 기본, 쉽게 추측 가능하고 쉽게 손상되는 자격 증명에 대한 테스트를 포함한 정적 및 동적 코드 분석.
- 침투 테스트.
  - 테스트는 제품의 보안 취약점을 발견하고 악용하는 데 초점을 맞춘 테스트를 통해 보안 관련 문제를 식별하고 특성화해야 합니다. 침투 테스트 보고서는 제공되어야 하며 다음 요소를 포함해야 합니다:
    - 테스터의 독립성 및 기술 전문성;
    - 테스트 범위;
    - 테스트 기간;
    - 사용된 테스트 방법; 그리고
    - 테스트 결과, 발견 사항 및 관찰 사항.

기기 제조업체는 테스트 보고서에서 누가 테스트를 수행했는지(예: 독립적인 내부 테스터, 외부 테스터) 그리고 기기 테스트를 담당하는 사람들이 기기 설계를 담당하는 개발자로부터 어느 정도의 독립성을 가지고 있는지 명시해야 합니다. 경우에 따라, 테스트 중에 드러난 취약점 또는 기타 문제가 적절하게 해결되도록 두 그룹 간에 적절한 수준의 독립성을 보장하기 위해 제3자를 사용하는 것이 필요할 수 있습니다. 모든 제3자 테스트 보고서의 경우, 제조업체는 원본 제3자 보고서를 제공해야 합니다. 모든 테스트에 대해, 제조업체는 향후 릴리스로 발견 사항을 구현하지 않거나 연기하는 근거를 포함한 모든 발견 사항에 대한 평가를 제공해야 합니다.

위의 섹션 V.A.2 및 V.A.3에서 논의된 바와 같이, 테스트 중에 식별된 취약점 및 이상은 보안 위험 관리 프로세스의 일부로 보안 영향에 대해 평가되어야 합니다. 비보안 소프트웨어 테스트에서, 발견된 결함의 이익 분석은 의료기기 시스템 기능에 미치는 영향이 작거나 가능성이 낮을 수 있으므로 이상을 수정할 필요가 없다는 결론으로 이어질 수 있습니다. 반대로, 보안 테스트에서는 이상의 악용 가능성이 그것이 촉진할 수 있는 더 크고 다른 유형의 피해 때문에 완화되어야 할 필요가 있을 수 있습니다.

향후 릴리스에서 해결될 문제(즉, 현재 위험이 허용 가능한 것으로 평가되었기 때문에 향후 소프트웨어 릴리스를 위해 개선이 연기된 경우)의 경우, 시판 전 제출에는 해당 릴리스에 대한 계획이 포함되어야 합니다. 이러한 계획에는 향후 소프트웨어 릴리스가 다룰 취약점, 릴리스에 대한 예상 일정, 중간에 릴리스된 기기가 해당 업데이트를 받을 것인지, 그리고 업데이트가 기기에 도달하는 데 얼마나 걸릴지가 포함되어야 합니다.

위에 설명된 테스트를 부분적으로 충족할 수 있는 보안 테스트를 개괄하는 수많은 권위 있는 리소스가 있습니다.[^47]

FDA는 사이버보안 테스트가 SPDF 전반에 걸쳐 발생해야 한다고 권장합니다. 개발 초기의 보안 테스트는 보안 문제가 릴리스 일정에 영향을 미치기 전에 해결되도록 보장할 수 있으며 기기를 재설계하거나 재개발할 필요를 방지할 수 있습니다. 릴리스 후, 사이버보안 테스트는 잠재적 취약점이 식별되고 악용되기 전에 해결될 수 있도록 위험에 비례하는 정기적인 간격(예: 연간)으로 수행되어야 합니다.

# VI. Cybersecurity Transparency
Cybersecurity transparency is critical to ensure safe and effective use and integration of devices and systems.[^48] This transparency can be conveyed through both device labeling and the establishment of manufacturer vulnerability management plans. However, different types of users (e.g., manufacturers, servicers, patients) will have different abilities to take on a mitigation role, and the need for actions to ensure continued cybersecurity should be appropriate for the type of user. Manufacturers of cyber devices should consider the recommendations in this section as they "design, develop, and maintain processes and procedures to provide a reasonable assurance that the device and related systems are cybersecure . . ." (section 524B(b)(2) of the FD&C Act; see Section VII.C.2).

## A. Labeling Recommendations for Devices with Cybersecurity Risks
FDA regulates device labeling in several ways. For example, section 502(f) of the FD&C Act requires that labeling include adequate directions for use. Under section 502(a)(1) of the FD&C Act, a medical device is deemed misbranded if its labeling is false or misleading in any particular.

For devices with cybersecurity risks, informing users of relevant security information may be an effective way to comply with labeling requirements relating to such risks. FDA also believes that informing users of security information through labeling may be an important part of design and development activities to help mitigate cybersecurity risks and help ensure the continued safety and effectiveness of the device. Therefore, when drafting labeling for inclusion in a premarket submission, a manufacturer should consider all applicable labeling requirements and how informing users through labeling may be an effective way to manage cybersecurity risks and/or to ensure the safe and effective use of the device. Any risks transferred to the user should be detailed and considered for inclusion as tasks during usability testing (e.g., human factors testing)[^49] to ensure that the type of user has the capability to take appropriate actions to manage those risks.

The recommendations below aim to communicate to users the relevant device security information that may enable their own ongoing security posture, thereby helping ensure a device remains safe and effective throughout its lifecycle. The depth of detail, the exact location in the labeling for specific types of information (e.g., operator's manual, security implementation guide), and the method to provide this information should account for the intended user of the information. Instructions to manage cybersecurity risks should be understandable to the intended audience, which might include patients or caregivers with limited technical knowledge. The manufacturer may wish to employ methods to ensure certain information is available only to the user, and if it does so through an online portal, should ensure that users have up-to-date links that contain accurate information.[^50]

The following are examples of information that may be included in labeling to communicate relevant security information to users:[^51]

- Device instructions and product specifications related to recommended cybersecurity controls appropriate for the intended use environment (e.g., anti-malware software, use of a firewall, password requirements).
- Sufficiently detailed diagrams for users that allow recommended cybersecurity controls to be implemented.
- A list of network ports and other interfaces that are expected to receive and/or send data. This list should include a description of port functionality and indicate whether the ports are incoming, outgoing, or both, along with approved destination end-points.
- Specific guidance to users regarding supporting infrastructure requirements so that the device can operate as intended (e.g., minimum networking requirements, supported encryption interfaces). Where appropriate, such guidance should include technical instructions to permit secure network deployment and servicing, and instructions for users on how to respond upon detection of a cybersecurity vulnerability or incident.
- An SBOM as specified in Section V.A.4 or in accordance with an industry accepted format to effectively manage their assets, to understand the potential impact of identified vulnerabilities to the medical device system, and to deploy countermeasures to maintain the device's safety and effectiveness. Manufacturers should provide or make available SBOM information to users on a continuous basis. If an online portal is used, manufacturers should ensure that users have up-to-date links that contain accurate information. The SBOM should be in a machine-readable format.
- A description of systematic procedures for users to download version-identifiable manufacturer-authorized software and firmware, including a description of how users will know when software is available.
- A description of how the design enables the device to respond when anomalous conditions are detected (i.e., security events). This should include notification to the user and logging of relevant information. Security event types could be configuration changes, network anomalies, login attempts, or anomalous traffic (e.g., send requests to unknown entities).
- A high-level description of the device features that protect critical functionality (e.g., backup mode, disabling ports/communications).
- A description of backup and restore features and procedures to restore authenticated configurations.
- A description of methods for retention and recovery of device configuration by an authenticated authorized user.
- A description of the secure configuration of shipped devices, instructions for user-configurable changes, and identification of user-configurable changes that could increase security risk for the medical device system. Secure configurations may include end point protections such as anti-malware, firewall/firewall rules, allow lists, deny lists, security event parameters, logging parameters, and physical security detection, and resetting of credentials, among others.
- Where appropriate for the intended use environment, a description of how forensic evidence is captured, including but not limited to any log files kept for a security event. Log file descriptions should include how, where, and in what format the log file is located, stored, recycled, archived, and how it could be consumed by automated analysis software (e.g., Intrusion Detection System (IDS) or Security Information and Event Management (SIEM)).
- Information, if known or anticipated, concerning device cybersecurity (including components) end of support and end of life. At the end of support, a manufacturer may no longer be able to reasonably provide security patches or software updates. If the device remains in service following the end of support, the manufacturer should have a pre-established and pre-communicated process for transferring the risks highlighting that the cybersecurity risks for end-users can be expected to increase over time.
- Information on securely decommissioning devices by sanitizing the product of sensitive, confidential, and proprietary data and software.

A revision-controlled, [Manufacturer Disclosure Statement for Medical Device Security (MDS2)](https://www.nema.org/standards/view/manufacturer-disclosure-statement-for-medical-device-security) and Customer Security Documentation as outlined in the [Medical Device and Health IT Joint Security Plan version 2 (JSP2)](https://healthsectorcouncil.org/jsp2/) may address a number of the above recommendations.

## B. Cybersecurity Management Plans

Recognizing that cybersecurity risks evolve as technology evolves throughout a device's TPLC, FDA recommends that manufacturers establish a plan for how they will identify and communicate to the relevant parties the vulnerabilities that are identified after releasing the device in accordance with the 21 CFR 820.100 and 21 CFR Part 806, as appropriate. This plan can also support security risk management processes that are described throughout the QS regulation.

FDA recommends that manufacturers submit their cybersecurity management plans as part of their premarket submissions so that FDA can assess whether the manufacturer has sufficiently addressed how to maintain the safety and effectiveness of the device after marketing authorization is achieved. For cyber devices, "a plan to monitor, identify, and address, as appropriate, in a reasonable time, postmarket cybersecurity vulnerabilities and exploits, including coordinated vulnerability disclosure and related procedures" is required (see section 524B(b)(1) of the FD&C Act and Section VII.C.1 of this guidance).

Cybersecurity management plans should include the following elements:

- Personnel responsible;
- Sources, methods, and frequency for monitoring and identifying vulnerabilities (e.g., researchers, NIST national vulnerability database (NIST NVD), third-party software manufacturers);
- Identify and address vulnerabilities identified in CISA's [Known Exploited Vulnerabilities Catalog](https://www.cisa.gov/known-exploited-vulnerabilities-catalog);
- Periodic security testing;
- Timeline to develop and release patches;
- Update processes;
- Patching capability (i.e., rate at which update can be delivered to devices);
- Description of their coordinated vulnerability disclosure process; and
- Description of how the manufacturer intends to communicate forthcoming remediations, patches, and updates to customers.

Additional recommendations on coordinated vulnerability disclosure plans may be found in FDA's [Postmarket Cybersecurity Guidance](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/postmarket-management-cybersecurity-medical-devices).

[^48]: Users often manage security risks in medical device systems by an end user or within a larger risk management framework like the NIST CSF. 사용자는 종종 최종 사용자가 또는 NIST CSF와 같은 더 큰 위험 관리 프레임워크 내에서 의료기기 시스템의 보안 위험을 관리합니다.

[^49]: See FDA's Guidance "Applying Human Factors and Usability Engineering to Medical Devices." FDA의 가이던스 "의료기기에 인적 요인 및 사용성 엔지니어링 적용"을 참조하십시오.

[^50]: For more information regarding FDA's policy on labeling changes and submission requirements, manufacturers can use the Search for FDA Guidance Documents tool to identify relevant guidance documents for their product and submission type. 라벨링 변경 및 제출 요구사항에 관한 FDA의 정책에 대한 자세한 정보는, 제조업체가 자신의 제품 및 제출 유형에 대한 관련 가이던스 문서를 식별하기 위해 FDA 가이던스 문서 검색 도구를 사용할 수 있습니다.

[^51]: See IEC TR 80001-2-2 Application of risk management for IT-networks incorporating medical devices —Part 2-2: Guidance for the communication of medical device security needs, risks and controls; IEC TR 80001-2-8 Application of risk management for IT-networks incorporating medical devices—Part 2-8: Application guidance — Guidance on standards for establishing the security capabilities identified in IEC 80001-2-2; and IEC TR 80001-2-9 Application of risk management for IT-networks incorporating medical devices—Part 2-9: Application guidance — Guidance for use of security assurance cases to demonstrate confidence in IEC/TR 80001-2-2 security capabilities for further labeling information for compliance with these standards. 이러한 표준 준수를 위한 추가 라벨링 정보는 IEC TR 80001-2-2 의료기기를 통합한 IT 네트워크에 대한 위험 관리 적용 —파트 2-2: 의료기기 보안 요구사항, 위험 및 통제의 전달을 위한 지침; IEC TR 80001-2-8 의료기기를 통합한 IT 네트워크에 대한 위험 관리 적용—파트 2-8: 적용 지침 — IEC 80001-2-2에서 식별된 보안 기능을 수립하기 위한 표준에 관한 지침; 그리고 IEC TR 80001-2-9 의료기기를 통합한 IT 네트워크에 대한 위험 관리 적용—파트 2-9: 적용 지침 — IEC/TR 80001-2-2 보안 기능에 대한 신뢰를 입증하기 위한 보안 보증 사례 사용에 관한 지침을 참조하십시오.

# VI. 사이버보안 투명성
사이버보안 투명성은 기기 및 시스템의 안전하고 효과적인 사용 및 통합을 보장하는 데 매우 중요합니다.[^48] 이러한 투명성은 기기 라벨링 및 제조업체 취약점 관리 계획의 수립을 통해 전달될 수 있습니다. 그러나 다양한 유형의 사용자(예: 제조업체, 서비스 제공자, 환자)는 완화 역할을 맡을 수 있는 다양한 능력을 가지게 되며, 지속적인 사이버보안을 보장하기 위한 조치의 필요성은 사용자 유형에 적합해야 합니다. 사이버 기기 제조업체는 "기기 및 관련 시스템이 사이버 보안을 확보한다는 합리적인 보증을 제공하기 위해 프로세스 및 절차를 설계, 개발 및 유지"할 때 본 섹션의 권장사항을 고려해야 합니다(FD&C법 524B(b)(2)조; 섹션 VII.C.2 참조).

## A. 사이버보안 위험이 있는 기기에 대한 라벨링 권장사항
FDA는 여러 방식으로 기기 라벨링을 규제합니다. 예를 들어, FD&C법 502(f)조는 라벨링에 적절한 사용 지침이 포함되어야 한다고 요구합니다. FD&C법 502(a)(1)조에 따라, 의료기기는 라벨링이 어떤 특정 사항에서 거짓이거나 오해의 소지가 있는 경우 부정 표시로 간주됩니다.

사이버보안 위험이 있는 기기의 경우, 사용자에게 관련 보안 정보를 알리는 것은 그러한 위험과 관련된 라벨링 요구사항을 준수하는 효과적인 방법이 될 수 있습니다. FDA는 또한 라벨링을 통해 사용자에게 보안 정보를 알리는 것이 사이버보안 위험을 완화하고 기기의 지속적인 안전성과 효과성을 보장하는 데 도움이 되는 설계 및 개발 활동의 중요한 부분이 될 수 있다고 믿습니다. 따라서 시판 전 제출에 포함할 라벨링을 작성할 때, 제조업체는 모든 적용 가능한 라벨링 요구사항과 라벨링을 통해 사용자에게 알리는 것이 사이버보안 위험을 관리하고/또는 기기의 안전하고 효과적인 사용을 보장하는 효과적인 방법이 될 수 있는 방법을 고려해야 합니다. 사용자에게 전가된 모든 위험은 상세히 설명되어야 하며 사용자 유형이 이러한 위험을 관리하기 위한 적절한 조치를 취할 수 있는 능력이 있는지 보장하기 위해 사용성 테스트(예: 인적 요인 테스트)[^49] 중 작업으로 포함하는 것을 고려해야 합니다.

아래 권장사항은 사용자에게 자신의 지속적인 보안 태세를 가능하게 할 수 있는 관련 기기 보안 정보를 전달하여 기기가 수명주기 동안 안전하고 효과적으로 유지되도록 돕는 것을 목표로 합니다. 세부 사항의 깊이, 특정 유형의 정보에 대한 라벨링 내 정확한 위치(예: 운영자 매뉴얼, 보안 구현 가이드), 그리고 이 정보를 제공하는 방법은 정보의 의도된 사용자를 고려해야 합니다. 사이버보안 위험을 관리하기 위한 지침은 제한된 기술 지식을 가진 환자 또는 간병인을 포함할 수 있는 의도된 청중이 이해할 수 있어야 합니다. 제조업체는 특정 정보가 사용자에게만 제공되도록 보장하는 방법을 사용하기를 원할 수 있으며, 온라인 포털을 통해 이를 수행하는 경우 사용자가 정확한 정보를 포함하는 최신 링크를 가지고 있는지 확인해야 합니다.[^50]

다음은 사용자에게 관련 보안 정보를 전달하기 위해 라벨링에 포함될 수 있는 정보의 예입니다:[^51]

- 의도된 사용 환경에 적합한 권장 사이버보안 통제와 관련된 기기 지침 및 제품 사양(예: 악성 소프트웨어 방지 소프트웨어, 방화벽 사용, 비밀번호 요구사항).
- 권장 사이버보안 통제를 구현할 수 있도록 하는 사용자를 위한 충분히 상세한 다이어그램.
- 데이터를 수신 및/또는 전송할 것으로 예상되는 네트워크 포트 및 기타 인터페이스 목록. 이 목록에는 포트 기능에 대한 설명이 포함되어야 하며 포트가 수신, 발신 또는 양방향인지 승인된 목적지 엔드포인트와 함께 표시되어야 합니다.
- 기기가 의도한 대로 작동할 수 있도록 지원 인프라 요구사항에 관한 사용자를 위한 구체적인 지침(예: 최소 네트워킹 요구사항, 지원되는 암호화 인터페이스). 적절한 경우, 이러한 지침에는 안전한 네트워크 배포 및 서비스를 허용하는 기술 지침과 사이버보안 취약점 또는 사고 탐지 시 대응 방법에 대한 사용자를 위한 지침이 포함되어야 합니다.
- 섹션 V.A.4에 명시되거나 산업계에서 인정하는 형식에 따라 자산을 효과적으로 관리하고, 식별된 취약점이 의료기기 시스템에 미치는 잠재적 영향을 이해하며, 기기의 안전성과 효과성을 유지하기 위한 대응책을 배포하기 위한 SBOM. 제조업체는 사용자에게 지속적으로 SBOM 정보를 제공하거나 이용 가능하게 해야 합니다. 온라인 포털을 사용하는 경우, 제조업체는 사용자가 정확한 정보를 포함하는 최신 링크를 가지고 있는지 확인해야 합니다. SBOM은 기계 판독 가능한 형식이어야 합니다.
- 사용자가 소프트웨어를 이용할 수 있을 때를 알 수 있는 방법에 대한 설명을 포함하여 버전 식별 가능한 제조업체 승인 소프트웨어 및 펌웨어를 다운로드하기 위한 체계적인 절차 설명.
- 이상 조건이 탐지될 때(즉, 보안 이벤트) 기기가 대응할 수 있도록 하는 설계 방법에 대한 설명. 여기에는 사용자에 대한 알림 및 관련 정보의 로깅이 포함되어야 합니다. 보안 이벤트 유형에는 구성 변경, 네트워크 이상, 로그인 시도 또는 이상 트래픽(예: 알 수 없는 엔티티에 대한 요청 전송)이 포함될 수 있습니다.
- 중요 기능을 보호하는 기기 기능에 대한 상위 수준 설명(예: 백업 모드, 포트/통신 비활성화).
- 인증된 구성을 복원하기 위한 백업 및 복원 기능 및 절차 설명.
- 인증된 승인 사용자에 의한 기기 구성의 보존 및 복구 방법 설명.
- 배송된 기기의 보안 구성에 대한 설명, 사용자 구성 가능한 변경을 위한 지침, 그리고 의료기기 시스템에 대한 보안 위험을 증가시킬 수 있는 사용자 구성 가능한 변경의 식별. 보안 구성에는 악성 소프트웨어 방지, 방화벽/방화벽 규칙, 허용 목록, 거부 목록, 보안 이벤트 매개변수, 로깅 매개변수, 물리적 보안 탐지, 자격 증명 재설정 등과 같은 엔드포인트 보호가 포함될 수 있습니다.
- 의도된 사용 환경에 적절한 경우, 보안 이벤트를 위해 보관되는 로그 파일을 포함하되 이에 국한되지 않는 포렌식 증거가 어떻게 캡처되는지에 대한 설명. 로그 파일 설명에는 로그 파일이 어떻게, 어디에, 어떤 형식으로 위치하고, 저장되고, 재활용되고, 아카이브되는지, 그리고 자동화된 분석 소프트웨어(예: 침입 탐지 시스템(IDS) 또는 보안 정보 및 이벤트 관리(SIEM))에 의해 어떻게 소비될 수 있는지가 포함되어야 합니다.
- 알려졌거나 예상되는 경우, 기기 사이버보안(구성요소 포함) 지원 종료 및 수명 종료에 관한 정보. 지원 종료 시점에서 제조업체는 더 이상 보안 패치 또는 소프트웨어 업데이트를 합리적으로 제공할 수 없을 수 있습니다. 기기가 지원 종료 후에도 서비스를 계속하는 경우, 제조업체는 최종 사용자의 사이버보안 위험이 시간이 지남에 따라 증가할 것으로 예상될 수 있음을 강조하는 위험 전가를 위한 사전 수립되고 사전 전달된 프로세스를 가지고 있어야 합니다.
- 민감하고 기밀이며 독점적인 데이터 및 소프트웨어의 제품을 정화하여 기기를 안전하게 폐기하는 것에 관한 정보.

개정 통제된 [의료기기 보안을 위한 제조업체 공개 성명서(MDS2)](https://www.nema.org/standards/view/manufacturer-disclosure-statement-for-medical-device-security) 및 [의료기기 및 보건 IT 공동 보안 계획 버전 2(JSP2)](https://healthsectorcouncil.org/jsp2/)에 설명된 고객 보안 문서는 위의 여러 권장사항을 다룰 수 있습니다.

## B. 사이버보안 관리 계획

사이버보안 위험이 기기의 TPLC 전반에 걸쳐 기술이 진화함에 따라 진화한다는 것을 인식하여, FDA는 제조업체가 적절한 경우 21 CFR 820.100 및 21 CFR Part 806에 따라 기기를 출시한 후 식별된 취약점을 관련 당사자에게 식별하고 전달하는 방법에 대한 계획을 수립할 것을 권장합니다. 이 계획은 QS 규정 전반에 걸쳐 설명된 보안 위험 관리 프로세스도 지원할 수 있습니다.

FDA는 제조업체가 시판 허가가 달성된 후 기기의 안전성과 효과성을 유지하는 방법을 충분히 다루었는지 FDA가 평가할 수 있도록 시판 전 제출의 일부로 사이버보안 관리 계획을 제출할 것을 권장합니다. 사이버 기기의 경우, "조정된 취약점 공개 및 관련 절차를 포함하여 시판 후 사이버보안 취약점 및 악용을 합리적인 시간 내에 적절하게 모니터링, 식별 및 해결하기 위한 계획"이 필요합니다(FD&C법 524B(b)(1)조 및 본 가이던스의 섹션 VII.C.1 참조).

사이버보안 관리 계획은 다음 요소를 포함해야 합니다:

- 책임 인력;
- 취약점을 모니터링하고 식별하기 위한 출처, 방법 및 빈도(예: 연구자, NIST 국가 취약점 데이터베이스(NIST NVD), 타사 소프트웨어 제조업체);
- CISA의 [알려진 악용된 취약점 카탈로그](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)에서 식별된 취약점 식별 및 해결;
- 정기적인 보안 테스트;
- 패치를 개발하고 릴리스하기 위한 일정;
- 업데이트 프로세스;
- 패치 기능(즉, 업데이트가 기기에 전달될 수 있는 속도);
- 조정된 취약점 공개 프로세스에 대한 설명; 그리고
- 제조업체가 향후 개선, 패치 및 업데이트를 고객에게 전달하려는 방법에 대한 설명.

조정된 취약점 공개 계획에 대한 추가 권장사항은 FDA의 [시판 후 사이버보안 가이던스](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/postmarket-management-cybersecurity-medical-devices)에서 찾을 수 있습니다.

# VII. Cyber Devices
This section identifies the cybersecurity information FDA considers to generally be necessary to support obligations under section 524B of the FD&C Act for cyber devices. This section provides recommendations specifically for cyber devices. Manufacturers of cyber devices should also consider the recommendations throughout this guidance to help meet their obligations under section 524B of the FD&C Act.

## A. Who is Required to Comply with Section 524B of the FD&C Act

Under section 524B(a) of the FD&C Act, a person, including a manufacturer,[^52] who submits a premarket application or submission under any of the following pathways—510(k),[^53] PMA,[^54] PDP, De Novo, or HDE[^55]—for a device that meets the definition of a "cyber device," as defined in section 524B(c), is required to include such information as FDA may require to ensure that the cyber device meets the cybersecurity requirements under section 524B(b).

## B. Devices Subject to Section 524B of the FD&C Act

Section 524B of the FD&C Act and its requirements apply to "cyber devices." Section 524B(c) of the FD&C Act defines a "cyber device" as a device that meets all of the following criteria "(1) includes software validated, installed, or authorized by the sponsor as a device or in a device; (2) has the ability to connect to the internet; and (3) contains any such technological characteristics validated, installed, or authorized by the sponsor that could be vulnerable to cybersecurity threats."

Informed in part by the definitions recognized by NIST for the term "software," FDA considers a "cyber device" to include devices that are or contain software, including software that is firmware or programmable logic.[^56] FDA also considers the "ability to connect to the internet" to include devices that are able to connect to the internet, whether intentionally or unintentionally, through any means (including at any point identified in the evaluation of the threat surface[^57] of the device and the environment of use). It is well-demonstrated that if a device has the ability to connect to the internet, it is possible that it can be connected to the Internet, regardless of whether such connectivity was intended by the device sponsor.[^58]

FDA considers devices that include any of the following features to have the ability to connect to the internet. The list below is illustrative, not exhaustive:

- Network, server, or Cloud Service Provider connections;
- Radio-frequency communications (e.g., Wi-Fi, cellular, Bluetooth, Bluetooth Low Energy);
- Magnetic inductive communications;[^59] and
- Hardware connectors capable of connecting to the internet (e.g., USB, ethernet, serial port).[^60]

## C. Documentation Recommendations to Comply with Section 524B of the FD&C Act

For applicable premarket submission types, manufacturers must provide documentation to comply with the requirements under section 524B of the FD&C Act. Recommendations regarding the documentation to support each of the requirements are discussed in the sections below.

### 1. Plans and Procedures (Section 524B(b)(1))

Section 524B(b)(1) of the FD&C Act requires manufacturers of cyber devices to submit to FDA "a plan to monitor, identify, and address, as appropriate, in a reasonable time, postmarket cybersecurity vulnerabilities and exploits, including coordinated vulnerability disclosure and related procedures" in their premarket submissions. We recommend that the plan contain the information recommended for the Cybersecurity Management Plan described in Section VI.B. In particular, such a plan should address the items discussed below.

First, FDA considers that coordinated vulnerability disclosure (CVD) and related procedures, as required in section 524B(b)(1) of the FD&C Act, could include:

- Coordinated disclosure of vulnerabilities and exploits identified by external entities (including third-party software suppliers and researchers);
- Disclosure of vulnerabilities and exploits identified by the manufacturer of cyber devices; and
- Manufacturer procedures to carry out disclosures of the vulnerabilities and exploits, as identified above.[^61]

Second, plans required by section 524B(b)(1) of the FD&C Act should also describe the timeline, with associated justifications, to develop and release required updates and patches:

- Section 524B(b)(2)(A) of the FD&C Act requires manufacturers of cyber devices to make available updates and patches[^62] to the device and related systems[^63] for known unacceptable vulnerabilities, with these updates and patches made available on a reasonably justified regular cycle.[^64]
  - A "known unacceptable vulnerability" in 524B(b)(2)(A) contrasts with a "critical vulnerability that could cause uncontrolled risks" in 524B(b)(2)(B). A known unacceptable vulnerability could include a vulnerability that could not cause uncontrolled risks; a vulnerability that is not currently known to cause uncontrolled risks; or a vulnerability that could present controlled risk, as described in FDA's [Postmarket Cybersecurity Guidance](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/postmarket-management-cybersecurity-medical-devices). Updates and/or patches to address these vulnerabilities may be intended to maintain the supportability of software. Generally, software should be regularly updated to maintain the supportability of the software. For examples of vulnerabilities associated with controlled risk, see the [Postmarket Cybersecurity Guidance](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/postmarket-management-cybersecurity-medical-devices). Updates and patches to address these types of vulnerabilities are not to reduce uncontrolled risk, and therefore not to reduce a risk to health or to correct a violation of the FD&C Act. See below for more information on section 524B(b)(2)(B) of the FD&C Act.
- Section 524B(b)(2)(B) of the FD&C Act requires manufacturers of cyber devices to make available updates and patches to the device and related systems to address as soon as possible out of cycle,[^65] critical vulnerabilities that could cause uncontrolled risks.
  - In general, this includes vulnerabilities that could cause uncontrolled risks, as described in FDA's [Postmarket Cybersecurity Guidance](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/postmarket-management-cybersecurity-medical-devices). For examples of vulnerabilities associated with uncontrolled risks, see the [Postmarket Cybersecurity Guidance](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/postmarket-management-cybersecurity-medical-devices).

Third, we recommend that manufacturers of cyber devices anticipate and make appropriate updates to these plans,[^66] as well as to the processes and procedures discussed in Section VII.C.2 below,[^67] as new information becomes available, such as when new risks, threats, vulnerabilities, assets, or adverse impacts are discovered throughout the total product lifecycle. To support such efforts, manufacturers should also create or update appropriate documentation (e.g., threat modeling, cybersecurity risk assessment) and maintain it throughout the device lifecycle. Doing so will allow manufacturers to quickly identify vulnerability impacts once a device is released and could also help satisfy the patching requirements of section 524B(b)(2)(A)-(B) of the FD&C Act.

The required plans,[^68] as well as the processes and procedures discussed in Section VII.C.2 below,[^69] also should, as appropriate, account for any differences in the risk management for fielded devices (e.g., differences between marketed devices and devices no longer marketed but still in use). For example, if an update is not applied automatically for all fielded devices, then there will likely be different risk profiles for the differing software configurations of the device. Vulnerabilities should be assessed for any differing impacts for all fielded versions to ensure patient risks are being accurately assessed.

### 2. Design, Develop, and Maintain Processes and Procedures to Provide a Reasonable Assurance of Cybersecurity (Section 524B(b)(2))

Manufacturers of cyber devices must "design, develop, and maintain processes and procedures to provide a reasonable assurance that the device and related systems are cybersecure . . ." (section 524B(b)(2) of the FD&C Act). FDA considers related systems to include, among other things, manufacturer-controlled elements, such as other devices, software that performs "other functions" as described in FDA's Guidance "[Multiple Function Device Products: Policy and Considerations](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/multiple-function-device-products-policy-and-considerations)," software/firmware update servers, and connections to healthcare facility networks. In the design, development and maintenance of a cyber device, manufacturers should consider the cybersecurity risks of related systems to the cyber device and implement appropriate security controls to mitigate those risks. The documentation recommendations identified in this guidance and summarized in Appendix 4 should be considered and used to demonstrate reasonable assurance that the device and related systems are cybersecure as required by section 524B(b)(2) of the FD&C Act.

### 3. Software Bill of Materials (SBOM) (Section 524B(b)(3))

Section 524B(b)(3) of the FD&C Act requires manufacturers of cyber devices to provide an SBOM, including commercial, open-source, and off-the-shelf software components. To assist with complying with this requirement, we recommend that a cyber device provide SBOMs that contain the information recommended in Section V.A.4.b.

## D. Modifications

As previously stated, the requirements under section 524B of the FD&C Act apply to a manufacturer who submits an application or submission under any of the following pathways—510(k), PMA, PDP, De Novo or HDE—for a device that meets the definition of a cyber device. Therefore, a manufacturer required to submit an application or submission under one of the enumerated pathways for a device modification would also need to comply with the requirements in section 524B of the FD&C Act.[^70] In keeping with least burdensome principles,[^71] the information we recommend that manufacturers of cyber devices provide will generally differ based on the type of change and whether such change impacts the cybersecurity of the device. Overall, we recommend that manufacturers use the recommendations below to determine the information FDA recommends manufacturers of cyber devices provide to demonstrate they have met the new requirements under section 524B of the FD&C Act when submitting a premarket submission for a device modification.

### 1. Changes That May Impact Cybersecurity

In general, changes that may impact cybersecurity and may require premarket submission could include changes to authentication or encryption algorithms, new connectivity features, or changing software update process/mechanisms. For these types of changes, see Section VII.C for required and recommended documentation to be included with each premarket submission (see section 524B of the FD&C Act).

### 2. Changes Unlikely to Impact Cybersecurity

In general, changes unlikely to impact cybersecurity could include changes in materials, sterilization method changes, or a change to an algorithm without change to architecture/software structure/connectivity.

For these types of changes, FDA recommends that manufacturers of cyber devices provide the following information to meet their premarket submission requirements in section 524B of the FD&C Act:

- 524B(b)(1)
  - If not previously provided, manufacturers must provide a plan as described in section 524B(b)(1) of the FD&C Act; we recommend that it contain the information as described in Section VII.C.1, above.
  - If a plan described in Section VII.C.1, above, was previously provided, the manufacturer should provide a reference to the prior submission and a summary of any changes to the plan.
- 524B(b)(2)
  - Instead of the full documentation described as required or recommended in Section VII.C.2, above, manufacturers may provide the following information:
    - Description of whether there are currently any "critical vulnerabilities that could cause uncontrolled risks."[^72]
    - Description of whether any vulnerabilities with uncontrolled risk were remediated in the device since the last authorization. If so, manufacturers should describe how remediation was performed following the recommendations in FDA's [Postmarket Cybersecurity Guidance](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/postmarket-management-cybersecurity-medical-devices).
- 524B(b)(3)
  - Section 524B(b)(3) of the FD&C Act requires manufacturers of cyber devices to provide an SBOM, including commercial, open-source, and off-the-shelf software components. To assist with complying with this requirement, we recommend that a manufacturer of a cyber device provide an SBOM that contains the information recommended in Section V.A.4.b above.

In general, in its cybersecurity review, FDA intends to focus substantive review on modifications to cybersecurity controls or modifications that are likely to affect cybersecurity. However, regardless of the type of change being proposed to the device in the premarket submission, FDA intends to take into account known cybersecurity concerns that are applicable to such device when conducting its premarket reviews and in determining whether the device has a reasonable assurance of cybersecurity.

## E. Reasonable Assurance of Cybersecurity of Cyber Devices

Section 3305(c) of FDORA provides that nothing in section 524B of the FD&C Act "shall be construed to affect the Secretary's authority related to ensuring that there is a reasonable assurance of the safety and effectiveness of devices, which may include ensuring that there is a reasonable assurance of the cybersecurity of certain cyber devices . . ." FDA interprets this provision to mean that a "reasonable assurance of cybersecurity" can be part of FDA's determination of a device's safety and effectiveness. Moreover, a determination that there is a reasonable assurance of cybersecurity is relevant to the various premarket pathways and authorization under them, specifically, FDA's review of a 510(k), PMA, PDP, De Novo, and HDE. With the exponential growth of interconnected devices on the market over the past few years (see Section I), ensuring cybersecurity has become essential to FDA's ability to protect the public health and provide reasonable assurance of safety and effectiveness of devices.

When evaluating a 510(k) submission, FDA considers changes to the environment of use (e.g., changes in technology the subject device will interact with or operate within, and any new risks or vulnerabilities the device will be exposed to), new risks or vulnerabilities in the technological characteristics compared to the predicate device submission (e.g., changes to level of support for component software, vulnerabilities in communication protocols or technology used by the subject device), and how the subject device design and/or performance testing (e.g., see the cybersecurity testing recommendations in Section V.C) address these new risks or vulnerabilities.[^73] For example, if in reviewing the 510(k) for an alarm for a central nursing station software, FDA identifies that the device has increased risks compared to its predicate because it does not have the necessary encryption to protect against a recently identified cyber threat, FDA may ask for additional performance data (e.g., see the documentation recommendations in Section V). If the data provided is inadequate, FDA would likely make a determination that the new device is not substantially equivalent (NSE) to the predicate device because this threat, if exploited, could negatively impact the safety and effectiveness of the device because alarm accuracy is essential for healthcare providers to effectively monitor the health of patients in a hospital.

[^52]: Section 524B(a) of the FD&C Act places obligations on the "person" who submits a specific type of device marketing application. Section 524B(b) of the FD&C Act places obligations on a "sponsor." For the purposes of this guidance, we assume that the manufacturer is the entity submitting the application and use the term accordingly throughout the guidance in lieu of the term "person" or "sponsor." However, if another person submits the application or submission enumerated under section 524B(a) of the FD&C Act to the Agency, that person should follow the guidance for manufacturers herein. Whatever person submits the application for a cyber device is subject to the requirements of section 524B. FD&C법 524B(a)조는 특정 유형의 기기 마케팅 신청서를 제출하는 "자"에게 의무를 부과합니다. FD&C법 524B(b)조는 "스폰서"에게 의무를 부과합니다. 본 가이던스의 목적상, 우리는 제조업체가 신청서를 제출하는 엔티티라고 가정하고 "자" 또는 "스폰서"라는 용어 대신 가이던스 전반에 걸쳐 그에 따라 해당 용어를 사용합니다. 그러나 다른 자가 FD&C법 524B(a)조에 열거된 신청서 또는 제출을 기관에 제출하는 경우, 해당 자는 여기에 있는 제조업체를 위한 가이던스를 따라야 합니다. 사이버 기기에 대한 신청서를 제출하는 자는 누구든지 524B조의 요구사항을 적용받습니다.

[^53]: For the purposes of this guidance, "510(k)" refers to the original, special, and abbreviated 510(k) submissions. 본 가이던스의 목적상, "510(k)"는 원본, 특수 및 약식 510(k) 제출을 의미합니다.

[^54]: For the purposes of this guidance, "PMA" refers to the original PMA and supplement PMAs. 본 가이던스의 목적상, "PMA"는 원본 PMA 및 보완 PMA를 의미합니다.

[^55]: For the purposes of this guidance, "HDE" refers to the original HDE and supplement HDEs. 본 가이던스의 목적상, "HDE"는 원본 HDE 및 보완 HDE를 의미합니다.

[^56]: NIST defines a programmable logic controller (PLC) as "[a] solid-state control system that has a user-programmable memory for storing instructions for the purpose of implementing specific functions such as I/O control, logic, timing, counting, three mode (PID) control, communication, arithmetic, and data and file processing." A PLC is therefore a combination of two components: (1) the hardware controller, and (2) the "user-programmable memory," or programmable logic, that instructs the hardware controller to execute specified functions. NIST defines software as, among other things, "computer programs and data stored in hardware – typically in read only memory or programmable read-only memory." Programmable logic is therefore a specific type of computer program and/or data stored on hardware, and is thus a type of software. See the NIST Computer Security Resource Center Glossary for more information on NIST's definitions of these terms. NIST는 프로그래밍 가능한 로직 컨트롤러(PLC)를 "I/O 제어, 로직, 타이밍, 계수, 3모드(PID) 제어, 통신, 산술, 데이터 및 파일 처리와 같은 특정 기능을 구현하기 위한 명령을 저장하기 위한 사용자 프로그래밍 가능한 메모리를 가진 고체 상태 제어 시스템"으로 정의합니다. 따라서 PLC는 두 가지 구성요소의 조합입니다: (1) 하드웨어 컨트롤러, 그리고 (2) 하드웨어 컨트롤러가 지정된 기능을 실행하도록 지시하는 "사용자 프로그래밍 가능한 메모리" 또는 프로그래밍 가능한 로직. NIST는 소프트웨어를 무엇보다도 "하드웨어에 저장된 컴퓨터 프로그램 및 데이터 – 일반적으로 읽기 전용 메모리 또는 프로그래밍 가능한 읽기 전용 메모리에"로 정의합니다. 따라서 프로그래밍 가능한 로직은 특정 유형의 컴퓨터 프로그램 및/또는 하드웨어에 저장된 데이터이므로 소프트웨어의 한 유형입니다. 이러한 용어에 대한 NIST의 정의에 대한 자세한 정보는 NIST 컴퓨터 보안 리소스 센터 용어집을 참조하십시오.

[^57]: For the purposes of this guidance, "threat surface" means the set of points on the boundary of a system, a system element, or an environment where a cyber threat can try to enter, cause an effect on, or extract data from, that system, system element, or environment (definition is adapted from the NIST Computer Security Resource Center Glossary). For the purposes of this guidance "threat surface" is synonymous with the term "attack surface," however, FDA uses the term "threat surface" rather than "attack surface," because cyber threats need not necessarily be an "attack" to pose a risk to a medical device and its related system. 본 가이던스의 목적상, "위협 표면"은 사이버 위협이 해당 시스템, 시스템 요소 또는 환경에 진입하거나, 영향을 미치거나, 데이터를 추출하려고 시도할 수 있는 시스템, 시스템 요소 또는 환경의 경계상 지점 세트를 의미합니다(정의는 NIST 컴퓨터 보안 리소스 센터 용어집에서 적용됨). 본 가이던스의 목적상 "위협 표면"은 "공격 표면"이라는 용어와 동의어이지만, FDA는 사이버 위협이 의료기기 및 관련 시스템에 위험을 제기하기 위해 반드시 "공격"일 필요는 없기 때문에 "공격 표면"보다 "위협 표면"이라는 용어를 사용합니다.

[^58]: For more information, see WannaCry Ransomware Encrypted Hospital Medical Devices and Indicators Associated With WannaCry Ransomware (Update I). 자세한 정보는 WannaCry 랜섬웨어가 병원 의료기기를 암호화함 및 WannaCry 랜섬웨어 관련 지표(업데이트 I)를 참조하십시오.

[^59]: For example, magnetic inductive communication allows wireless data transmission between an implantable medical device and an external programmer. A transmitter coil in the external programmer sends data by modulating magnetic fields which then induces an electrical current in the receiver coil of the implantable medical device. The induced current carries encoded data, which allows communication, between the external programmer and the implantable medical device. 예를 들어, 자기 유도 통신은 이식 가능한 의료기기와 외부 프로그래머 간의 무선 데이터 전송을 가능하게 합니다. 외부 프로그래머의 송신기 코일은 자기장을 변조하여 데이터를 전송하며, 이는 이식 가능한 의료기기의 수신기 코일에 전류를 유도합니다. 유도된 전류는 인코딩된 데이터를 전달하여 외부 프로그래머와 이식 가능한 의료기기 간의 통신을 가능하게 합니다.

[^60]: For example, a device may need to be serviced via a USB connection. While the connection may be brief, the ability to connect is present and the device is therefore considered to have the ability to connect to the internet. 예를 들어, 기기는 USB 연결을 통해 서비스를 받아야 할 수 있습니다. 연결이 짧을 수 있지만, 연결 능력이 존재하므로 기기는 인터넷에 연결할 수 있는 능력이 있는 것으로 간주됩니다.

[^61]: For the purposes of this guidance, manufacturer procedures to carry out disclosures of the vulnerabilities and exploits may include procedures to inform device users, customers, patients, and other relevant healthcare parties. 본 가이던스의 목적상, 취약점 및 악용의 공개를 수행하기 위한 제조업체 절차는 기기 사용자, 고객, 환자 및 기타 관련 의료 당사자에게 알리는 절차를 포함할 수 있습니다.

[^62]: An update is defined by NIST as "[a] patch, upgrade, or other modification to code that corrects security and/or functionality problems in software" (see NIST Computer Security Resource Center Glossary). Patches are defined by CISA as "software and operating system (OS) updates that address security vulnerabilities within a program or product" (see Understanding Patches and Software Updates). We consider an update or patch that would satisfy the requirements under section 524B(b)(2)(A)-(B) for updates or patches as an action that modifies device code to address a cyber risk. 업데이트는 NIST에 의해 "소프트웨어의 보안 및/또는 기능 문제를 수정하는 패치, 업그레이드 또는 기타 코드 수정"으로 정의됩니다(NIST 컴퓨터 보안 리소스 센터 용어집 참조). 패치는 CISA에 의해 "프로그램 또는 제품 내의 보안 취약점을 해결하는 소프트웨어 및 운영 체제(OS) 업데이트"로 정의됩니다(패치 및 소프트웨어 업데이트 이해 참조). 우리는 업데이트 또는 패치에 대한 524B(b)(2)(A)-(B)조의 요구사항을 충족하는 업데이트 또는 패치를 사이버 위험을 해결하기 위해 기기 코드를 수정하는 조치로 간주합니다.

[^63]: For the purposes of this guidance, we refer to the evaluation of "related systems" to the extent needed to determine that the device, as it interacts with related systems, remains cybersecure. Related systems are further described in Section VII.C.2, below. 본 가이던스의 목적상, 우리는 기기가 관련 시스템과 상호 작용할 때 사이버 보안을 유지하는지 결정하는 데 필요한 범위까지 "관련 시스템"의 평가를 언급합니다. 관련 시스템은 아래 섹션 VII.C.2에서 더 자세히 설명됩니다.

[^64]: The justification for the regular cycle should typically be included in the cybersecurity management plan. The length of the regular cycle may vary depending on numerous factors for the particular device. One of the primary factors that may influence the length of the cycle is risk. For example, an interconnected thermometer whose functionality is limited to taking and reporting patient temperature may have lower risk of harm if exploited than an interconnected surgery robot, whose risk of harm may be significantly higher. At the same time, exploitation of a seemingly lower-risk device may provide opportunities to affect other devices within the environment of use, leading to significantly greater risk of harm if these other devices or the larger environment are exploited or disrupted. Manufacturers should fully consider the risks to and from their devices, within the larger context(s) of the environment(s) in which they will be intended to operate, and design and deploy regular update cycles that provide a reasonable assurance of cybersecurity. 정기 주기에 대한 정당화는 일반적으로 사이버보안 관리 계획에 포함되어야 합니다. 정기 주기의 길이는 특정 기기에 대한 수많은 요인에 따라 달라질 수 있습니다. 주기의 길이에 영향을 미칠 수 있는 주요 요인 중 하나는 위험입니다. 예를 들어, 기능이 환자 체온 측정 및 보고로 제한된 상호 연결된 온도계는 악용될 경우 피해 위험이 낮을 수 있지만, 상호 연결된 수술 로봇은 피해 위험이 훨씬 높을 수 있습니다. 동시에, 겉보기에 낮은 위험 기기의 악용은 사용 환경 내의 다른 기기에 영향을 미칠 기회를 제공할 수 있으며, 이러한 다른 기기 또는 더 큰 환경이 악용되거나 중단되는 경우 훨씬 더 큰 피해 위험으로 이어질 수 있습니다. 제조업체는 기기가 작동할 것으로 의도된 환경의 더 큰 맥락 내에서 자신의 기기에 대한 그리고 자신의 기기로부터의 위험을 완전히 고려하고, 사이버보안의 합리적인 보증을 제공하는 정기 업데이트 주기를 설계하고 배포해야 합니다.

[^65]: For example, a manufacturer may make updates outside of the planned reasonably justified regular cycle to remediate an uncontrolled risk. 예를 들어, 제조업체는 통제되지 않은 위험을 개선하기 위해 계획된 합리적으로 정당화된 정기 주기를 벗어나 업데이트를 수행할 수 있습니다.

[^66]: See section 524B(b)(1) of the FD&C Act. FD&C법 524B(b)(1)조를 참조하십시오.

[^67]: See section 524B(b)(2) of the FD&C Act. FD&C법 524B(b)(2)조를 참조하십시오.

[^68]: See section 524B(b)(1) of the FD&C Act. FD&C법 524B(b)(1)조를 참조하십시오.

[^69]: See section 524B(b)(2) of the FD&C Act. FD&C법 524B(b)(2)조를 참조하십시오.

[^70]: For more information on when to submit an application for a device modification, see other FDA guidances, including "Deciding When to Submit a 510(k) for a Software Change to an Existing Device" and "Modifications to Devices Subject to Premarket Approval (PMA) - The PMA Supplement Decision-Making Process." 기기 수정에 대한 신청서를 제출해야 하는 시기에 대한 자세한 정보는 "기존 기기에 대한 소프트웨어 변경을 위한 510(k) 제출 시기 결정" 및 "시판 전 승인(PMA) 대상 기기 수정 - PMA 보완 의사결정 프로세스"를 포함한 다른 FDA 가이던스를 참조하십시오.

[^71]: For more information on FDA's least burdensome provisions, see FDA's guidance "The Least Burdensome Provisions: Concept and Principles." FDA의 최소 부담 조항에 대한 자세한 정보는 FDA의 가이던스 "최소 부담 조항: 개념 및 원칙"을 참조하십시오.

[^72]: Section 524B(b)(2)(B) of the FD&C Act requires manufacturers to make available postmarket updates and patches to the cyber device and related systems to address, as soon as possible out of cycle, critical vulnerabilities that could cause uncontrolled risks, among other requirements. See Section VII.C.1 for more information on "critical vulnerabilities that could cause uncontrolled risks." FD&C법 524B(b)(2)(B)조는 무엇보다도 제조업체가 통제되지 않은 위험을 초래할 수 있는 중대한 취약점을 주기를 벗어나 가능한 한 빨리 해결하기 위해 사이버 기기 및 관련 시스템에 대한 시판 후 업데이트 및 패치를 제공하도록 요구합니다. "통제되지 않은 위험을 초래할 수 있는 중대한 취약점"에 대한 자세한 정보는 섹션 VII.C.1을 참조하십시오.

[^73]: For more information about current review practices for 510(k) submission, see FDA's guidance "The 510(k) Program: Evaluating Substantial Equivalence in Premarket Notifications [510(k)]." 510(k) 제출에 대한 현재 검토 관행에 대한 자세한 정보는 FDA의 가이던스 "510(k) 프로그램: 시판 전 신고[510(k)]에서 실질적 동등성 평가"를 참조하십시오.

# VII. 사이버 기기
본 섹션은 FDA가 사이버 기기에 대한 FD&C법 524B조에 따른 의무를 지원하기 위해 일반적으로 필요하다고 간주하는 사이버보안 정보를 식별합니다. 본 섹션은 사이버 기기에 대한 권장사항을 구체적으로 제공합니다. 사이버 기기 제조업체는 또한 FD&C법 524B조에 따른 의무를 충족하는 데 도움이 되도록 본 가이던스 전반의 권장사항을 고려해야 합니다.

## A. FD&C법 524B조를 준수해야 하는 주체
FD&C법 524B(a)조에 따라, 제조업체를 포함한 자[^52]가 524B(c)조에 정의된 "사이버 기기"의 정의를 충족하는 기기에 대해 다음 경로 중 하나에 따라 시판 전 신청 또는 제출—510(k)[^53], PMA[^54], PDP, De Novo 또는 HDE[^55]—을 제출하는 경우, 사이버 기기가 524B(b)조에 따른 사이버보안 요구사항을 충족하도록 보장하기 위해 FDA가 요구할 수 있는 정보를 포함해야 합니다.

## B. FD&C법 524B조의 적용 대상 기기
FD&C법 524B조 및 그 요구사항은 "사이버 기기"에 적용됩니다. FD&C법 524B(c)조는 "사이버 기기"를 다음 기준을 모두 충족하는 기기로 정의합니다: "(1) 스폰서에 의해 기기로서 또는 기기 내에서 검증, 설치 또는 승인된 소프트웨어를 포함하고; (2) 인터넷에 연결할 수 있는 능력이 있으며; (3) 사이버보안 위협에 취약할 수 있는 스폰서에 의해 검증, 설치 또는 승인된 기술적 특성을 포함하는" 기기.

NIST가 "소프트웨어"라는 용어에 대해 인정하는 정의를 부분적으로 참고하여, FDA는 "사이버 기기"가 펌웨어 또는 프로그래밍 가능한 로직인 소프트웨어를 포함하여 소프트웨어이거나 소프트웨어를 포함하는 기기를 포함하는 것으로 간주합니다.[^56] FDA는 또한 "인터넷에 연결할 수 있는 능력"이 기기 및 사용 환경의 위협 표면[^57] 평가에서 식별된 모든 지점을 포함하여 어떤 수단을 통해서든 의도적으로든 비의도적으로든 인터넷에 연결할 수 있는 기기를 포함하는 것으로 간주합니다. 기기가 인터넷에 연결할 수 있는 능력이 있는 경우, 이러한 연결이 기기 스폰서에 의해 의도되었는지 여부와 관계없이 인터넷에 연결될 수 있다는 것이 잘 입증되어 있습니다.[^58]

FDA는 다음 기능 중 하나를 포함하는 기기가 인터넷에 연결할 수 있는 능력이 있다고 간주합니다. 아래 목록은 예시적이며 전부가 아닙니다:

- 네트워크, 서버 또는 클라우드 서비스 제공자 연결;
- 무선 주파수 통신(예: Wi-Fi, 셀룰러, 블루투스, 블루투스 저에너지);
- 자기 유도 통신;[^59] 그리고
- 인터넷에 연결할 수 있는 하드웨어 커넥터(예: USB, 이더넷, 직렬 포트).[^60]

## C. FD&C법 524B조를 준수하기 위한 문서 권장사항
적용 가능한 시판 전 제출 유형의 경우, 제조업체는 FD&C법 524B조에 따른 요구사항을 준수하기 위한 문서를 제공해야 합니다. 각 요구사항을 지원하기 위한 문서에 관한 권장사항은 아래 섹션에서 논의됩니다.

### 1. 계획 및 절차 (524B(b)(1)조)
FD&C법 524B(b)(1)조는 사이버 기기 제조업체가 시판 전 제출에서 "조정된 취약점 공개 및 관련 절차를 포함하여 시판 후 사이버보안 취약점 및 악용을 합리적인 시간 내에 적절하게 모니터링, 식별 및 해결하기 위한 계획"을 FDA에 제출할 것을 요구합니다. 우리는 이 계획이 섹션 VI.B에 설명된 사이버보안 관리 계획에 권장되는 정보를 포함할 것을 권장합니다. 특히, 이러한 계획은 아래에서 논의되는 항목을 다루어야 합니다.

첫째, FDA는 FD&C법 524B(b)(1)조에서 요구하는 조정된 취약점 공개(CVD) 및 관련 절차가 다음을 포함할 수 있다고 간주합니다:

- 외부 엔티티(타사 소프트웨어 공급업체 및 연구자 포함)가 식별한 취약점 및 악용의 조정된 공개;
- 사이버 기기 제조업체가 식별한 취약점 및 악용의 공개; 그리고
- 위에서 식별된 취약점 및 악용의 공개를 수행하기 위한 제조업체 절차.[^61]

둘째, FD&C법 524B(b)(1)조에서 요구하는 계획은 또한 필요한 업데이트 및 패치를 개발하고 릴리스하기 위한 일정과 관련 정당화를 설명해야 합니다:

- FD&C법 524B(b)(2)(A)조는 사이버 기기 제조업체가 알려진 허용 불가능한 취약점에 대해 기기 및 관련 시스템[^63]에 대한 업데이트 및 패치[^62]를 제공하도록 요구하며, 이러한 업데이트 및 패치는 합리적으로 정당화된 정기 주기로 제공되어야 합니다.[^64]
  - 524B(b)(2)(A)조의 "알려진 허용 불가능한 취약점"은 524B(b)(2)(B)조의 "통제되지 않은 위험을 초래할 수 있는 중대한 취약점"과 대조됩니다. 알려진 허용 불가능한 취약점에는 통제되지 않은 위험을 초래할 수 없는 취약점; 현재 통제되지 않은 위험을 초래하는 것으로 알려지지 않은 취약점; 또는 FDA의 [시판 후 사이버보안 가이던스](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/postmarket-management-cybersecurity-medical-devices)에 설명된 대로 통제된 위험을 제시할 수 있는 취약점이 포함될 수 있습니다. 이러한 취약점을 해결하기 위한 업데이트 및/또는 패치는 소프트웨어의 지원 가능성을 유지하기 위한 것일 수 있습니다. 일반적으로 소프트웨어는 소프트웨어의 지원 가능성을 유지하기 위해 정기적으로 업데이트되어야 합니다. 통제된 위험과 관련된 취약점의 예는 [시판 후 사이버보안 가이던스](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/postmarket-management-cybersecurity-medical-devices)를 참조하십시오. 이러한 유형의 취약점을 해결하기 위한 업데이트 및 패치는 통제되지 않은 위험을 줄이기 위한 것이 아니므로 건강에 대한 위험을 줄이거나 FD&C법 위반을 수정하기 위한 것이 아닙니다. FD&C법 524B(b)(2)(B)조에 대한 자세한 정보는 아래를 참조하십시오.
- FD&C법 524B(b)(2)(B)조는 사이버 기기 제조업체가 통제되지 않은 위험을 초래할 수 있는 중대한 취약점을 해결하기 위해 주기를 벗어나[^65] 가능한 한 빨리 기기 및 관련 시스템에 대한 업데이트 및 패치를 제공하도록 요구합니다.
  - 일반적으로, 여기에는 FDA의 [시판 후 사이버보안 가이던스](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/postmarket-management-cybersecurity-medical-devices)에 설명된 대로 통제되지 않은 위험을 초래할 수 있는 취약점이 포함됩니다. 통제되지 않은 위험과 관련된 취약점의 예는 [시판 후 사이버보안 가이던스](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/postmarket-management-cybersecurity-medical-devices)를 참조하십시오.

셋째, 우리는 사이버 기기 제조업체가 전체 제품 수명주기 동안 새로운 위험, 위협, 취약점, 자산 또는 부정적 영향이 발견될 때와 같이 새로운 정보가 이용 가능해질 때 이러한 계획[^66]과 아래 섹션 VII.C.2에서 논의되는 프로세스 및 절차[^67]에 대한 적절한 업데이트를 예상하고 수행할 것을 권장합니다. 이러한 노력을 지원하기 위해, 제조업체는 또한 적절한 문서(예: 위협 모델링, 사이버보안 위험 평가)를 생성하거나 업데이트하고 기기 수명주기 동안 이를 유지해야 합니다. 이렇게 함으로써 제조업체는 기기가 출시되면 취약점 영향을 신속하게 식별할 수 있으며 FD&C법 524B(b)(2)(A)-(B)조의 패치 요구사항을 충족하는 데도 도움이 될 수 있습니다.

필요한 계획[^68]과 아래 섹션 VII.C.2에서 논의되는 프로세스 및 절차[^69]도 적절한 경우 배치된 기기에 대한 위험 관리의 차이를 설명해야 합니다(예: 시판된 기기와 더 이상 시판되지 않지만 여전히 사용 중인 기기 간의 차이). 예를 들어, 모든 배치된 기기에 대해 업데이트가 자동으로 적용되지 않는 경우, 기기의 서로 다른 소프트웨어 구성에 대해 서로 다른 위험 프로필이 있을 가능성이 높습니다. 환자 위험이 정확하게 평가되도록 모든 배치된 버전에 대해 서로 다른 영향에 대해 취약점이 평가되어야 합니다.

### 2. 사이버보안의 합리적인 보증을 제공하기 위한 프로세스 및 절차 설계, 개발 및 유지 (524B(b)(2)조)
사이버 기기 제조업체는 "기기 및 관련 시스템이 사이버 보안을 확보한다는 합리적인 보증을 제공하기 위해 프로세스 및 절차를 설계, 개발 및 유지해야 합니다..." (FD&C법 524B(b)(2)조). FDA는 관련 시스템이 무엇보다도 다른 기기, FDA의 가이던스 "[다기능 의료기기 제품: 정책 및 고려사항](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/multiple-function-device-products-policy-and-considerations)"에 설명된 "기타 기능"을 수행하는 소프트웨어, 소프트웨어/펌웨어 업데이트 서버, 의료 시설 네트워크에 대한 연결과 같은 제조업체가 통제하는 요소를 포함하는 것으로 간주합니다. 사이버 기기의 설계, 개발 및 유지보수에서, 제조업체는 관련 시스템에서 사이버 기기로의 사이버보안 위험을 고려하고 이러한 위험을 완화하기 위한 적절한 보안 통제를 구현해야 합니다. 본 가이던스에서 식별되고 부록 4에 요약된 문서 권장사항은 FD&C법 524B(b)(2)조에서 요구하는 대로 기기 및 관련 시스템이 사이버 보안을 확보한다는 합리적인 보증을 입증하기 위해 고려되고 사용되어야 합니다.

### 3. 소프트웨어 구성 요소 목록(SBOM) (524B(b)(3)조)
FD&C법 524B(b)(3)조는 사이버 기기 제조업체가 상용, 오픈 소스 및 상용 소프트웨어 구성요소를 포함한 SBOM을 제공할 것을 요구합니다. 이 요구사항을 준수하는 것을 지원하기 위해, 우리는 사이버 기기가 섹션 V.A.4.b에서 권장하는 정보를 포함하는 SBOM을 제공할 것을 권장합니다.

## D. 수정
앞서 언급한 바와 같이, FD&C법 524B조에 따른 요구사항은 사이버 기기의 정의를 충족하는 기기에 대해 다음 경로 중 하나에 따라 신청서 또는 제출—510(k), PMA, PDP, De Novo 또는 HDE—을 제출하는 제조업체에 적용됩니다. 따라서 기기 수정에 대해 열거된 경로 중 하나에 따라 신청서 또는 제출을 제출해야 하는 제조업체는 FD&C법 524B조의 요구사항도 준수해야 합니다.[^70] 최소 부담 원칙에 따라[^71], 사이버 기기 제조업체가 제공할 것을 권장하는 정보는 일반적으로 변경 유형과 그러한 변경이 기기의 사이버보안에 영향을 미치는지 여부에 따라 달라질 것입니다. 전반적으로, 우리는 제조업체가 아래 권장사항을 사용하여 기기 수정에 대한 시판 전 제출을 할 때 FD&C법 524B조에 따른 새로운 요구사항을 충족했음을 입증하기 위해 사이버 기기 제조업체가 제공할 것을 FDA가 권장하는 정보를 결정할 것을 권장합니다.

### 1. 사이버보안에 영향을 미칠 수 있는 변경
일반적으로, 사이버보안에 영향을 미칠 수 있고 시판 전 제출이 필요할 수 있는 변경에는 인증 또는 암호화 알고리즘 변경, 새로운 연결 기능 또는 소프트웨어 업데이트 프로세스/메커니즘 변경이 포함될 수 있습니다. 이러한 유형의 변경의 경우, 각 시판 전 제출에 포함되어야 하는 필수 및 권장 문서는 섹션 VII.C를 참조하십시오(FD&C법 524B조 참조).

### 2. 사이버보안에 영향을 미칠 가능성이 낮은 변경
일반적으로, 사이버보안에 영향을 미칠 가능성이 낮은 변경에는 재료 변경, 멸균 방법 변경 또는 아키텍처/소프트웨어 구조/연결 변경 없이 알고리즘 변경이 포함될 수 있습니다.

이러한 유형의 변경의 경우, FDA는 사이버 기기 제조업체가 FD&C법 524B조의 시판 전 제출 요구사항을 충족하기 위해 다음 정보를 제공할 것을 권장합니다:

- 524B(b)(1)조
  - 이전에 제공되지 않은 경우, 제조업체는 FD&C법 524B(b)(1)조에 설명된 대로 계획을 제공해야 합니다; 우리는 위의 섹션 VII.C.1에 설명된 정보를 포함할 것을 권장합니다.
  - 위의 섹션 VII.C.1에 설명된 계획이 이전에 제공된 경우, 제조업체는 이전 제출에 대한 참조 및 계획에 대한 변경 사항 요약을 제공해야 합니다.
- 524B(b)(2)조
  - 위의 섹션 VII.C.2에서 필수 또는 권장으로 설명된 전체 문서 대신, 제조업체는 다음 정보를 제공할 수 있습니다:
    - 현재 "통제되지 않은 위험을 초래할 수 있는 중대한 취약점"이 있는지 여부에 대한 설명.[^72]
    - 마지막 승인 이후 기기에서 통제되지 않은 위험이 있는 취약점이 개선되었는지 여부에 대한 설명. 그러한 경우, 제조업체는 FDA의 [시판 후 사이버보안 가이던스](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/postmarket-management-cybersecurity-medical-devices)의 권장사항에 따라 개선이 어떻게 수행되었는지 설명해야 합니다.
- 524B(b)(3)조
  - FD&C법 524B(b)(3)조는 사이버 기기 제조업체가 상용, 오픈 소스 및 상용 소프트웨어 구성요소를 포함한 SBOM을 제공할 것을 요구합니다. 이 요구사항을 준수하는 것을 지원하기 위해, 우리는 사이버 기기 제조업체가 위의 섹션 V.A.4.b에서 권장하는 정보를 포함하는 SBOM을 제공할 것을 권장합니다.

일반적으로, 사이버보안 검토에서 FDA는 사이버보안 통제에 대한 수정 또는 사이버보안에 영향을 미칠 가능성이 있는 수정에 대한 실질적인 검토에 초점을 맞출 의도입니다. 그러나 시판 전 제출에서 기기에 제안되는 변경 유형과 관계없이, FDA는 시판 전 검토를 수행하고 기기가 사이버보안의 합리적인 보증을 가지고 있는지 결정할 때 해당 기기에 적용 가능한 알려진 사이버보안 문제를 고려할 의도입니다.

## E. 사이버 기기의 사이버보안 합리적 보증
FDORA의 3305(c)조는 FD&C법 524B조의 어떤 내용도 "특정 사이버 기기의 사이버보안에 대한 합리적인 보증을 보장하는 것을 포함할 수 있는 기기의 안전성과 효과성에 대한 합리적인 보증을 보장하는 것과 관련된 장관의 권한에 영향을 미치는 것으로 해석되어서는 안 된다..."고 규정합니다. FDA는 이 조항이 "사이버보안의 합리적인 보증"이 기기의 안전성과 효과성에 대한 FDA의 결정의 일부가 될 수 있음을 의미하는 것으로 해석합니다. 또한, 사이버보안의 합리적인 보증이 있다는 결정은 다양한 시판 전 경로 및 그에 따른 승인, 구체적으로 FDA의 510(k), PMA, PDP, De Novo 및 HDE 검토와 관련이 있습니다. 지난 몇 년 동안 시장에서 상호 연결된 기기의 기하급수적인 성장(섹션 I 참조)과 함께, 사이버보안 보장은 공중 보건을 보호하고 기기의 안전성과 효과성에 대한 합리적인 보증을 제공하는 FDA의 능력에 필수적이 되었습니다.

510(k) 제출을 평가할 때, FDA는 사용 환경의 변경(예: 대상 기기가 상호 작용하거나 작동할 기술의 변경, 기기가 노출될 새로운 위험 또는 취약점), 술어 기기 제출과 비교하여 기술적 특성의 새로운 위험 또는 취약점(예: 구성요소 소프트웨어에 대한 지원 수준 변경, 대상 기기가 사용하는 통신 프로토콜 또는 기술의 취약점), 그리고 대상 기기 설계 및/또는 성능 테스트(예: 섹션 V.C의 사이버보안 테스트 권장사항 참조)가 이러한 새로운 위험 또는 취약점을 어떻게 다루는지 고려합니다.[^73] 예를 들어, 중앙 간호 스테이션 소프트웨어용 알람에 대한 510(k)를 검토할 때, FDA가 기기가 최근 식별된 사이버 위협으로부터 보호하는 데 필요한 암호화를 가지고 있지 않기 때문에 술어와 비교하여 위험이 증가했다고 식별하는 경우, FDA는 추가 성능 데이터를 요청할 수 있습니다(예: 섹션 V의 문서 권장사항 참조). 제공된 데이터가 부적절한 경우, FDA는 이 위협이 악용되면 알람 정확도가 의료 제공자가 병원 환자의 건강을 효과적으로 모니터링하는 데 필수적이기 때문에 기기의 안전성과 효과성에 부정적인 영향을 미칠 수 있으므로 새 기기가 술어 기기와 실질적으로 동등하지 않다(NSE)고 결정할 가능성이 높습니다.

# Appendix 1. Security Control Categories and Associated Recommendations
The following sections provide detailed descriptions of each of the security control categories introduced in Section V.B.1, as well as specific recommendations for security controls and their implementation, to avoid common pitfalls.

## A. Authentication
There are generally two types of authentication controls—information and entities—and a properly-secured system is able to prove the existence of both.

Authentication of information[^74] exists where the device and the system in which it operates are able to prove that information originated at a known and trusted source, and that the information has not been altered in transit between the original source and the point at which authenticity is verified. It is important to note that while authenticity implies that data is accurate and has been safeguarded from unauthorized user modification (i.e., integrity), integrity alone does not provide assurance that the data is real and came from a trusted source. Therefore, for the purposes of this guidance, authentication is discussed as a larger security objective over integrity.

Authentication of entities exists where a device and the system in which it operates is able to prove the identity of an endpoint (whether hardware and/or software) from which it is sending and/or receiving information, or authorized user/operator at that endpoint.

As part of normal operations within a secure system, devices should verify the authenticity of information from external entities, as well as prove the authenticity of information that they generate. A medical device system that appropriately accounts for authenticity can evaluate and ensure authenticity for:

- Information at rest (stored);
- Information in transit (transmitted);
- Entity authentication of communication endpoints, whether those endpoints consist of software or hardware;
- Software binaries;
- Integrity of the execution state of currently running software; and
- Any other appropriate parts of the medical device system where a manufacturer's threat model and/or risk analyses reveal the need for it.

On a technical level, the strength of a device's authentication scheme is defined by the amount of effort, including time, that an unauthorized party would need to expend to identify the decomposition of the authentication scheme. For example, this could be the time and resources necessary to determine the correct "output" of a cryptographic function from which a cryptographically-based authentication scheme is built and which an unauthorized party could use to bypass the authentication scheme and gain access to the medical device system.

When choosing an authentication scheme, manufacturers should keep in mind the following generally applicable characteristics of different types of schemes:

- Implicit authentication schemes, based solely on non-cryptographic interfaces, handshakes, and/or protocols, are inherently weak because, once they are reverse-engineered, an unauthorized user can easily emulate the correct behavior and appear to be authorized.
- Cryptographic authentication protocols are generally superior, but they need careful design choices and implementation practices to achieve their full strength.

In addition, these schemes are still limited by the confidentiality of the cryptographic keys needed to interact with the scheme, and by the integrity of the devices that hold or otherwise leverage those keys. For more information on cryptography, see Appendix 1 subsection C., below. Therefore, for device operations where non-authenticated behavior could lead to harm, devices should implement additional, non-routine signals of intent based on physical actions, such as a momentary switch, to authorize the command/session.

The following list provides additional recommendations for the implementation of authentication schemes:

- Use cryptographically strong[^75] authentication, where the authentication functionality resides on the device, to authenticate personnel, messages, commands updates, and as applicable, all other communication pathways. Hardware-based security solutions should be considered and employed when possible;
- Authenticate external connections at a frequency commensurate with the associated risks. For example, if a device connects to an offsite server, then the device and the server should mutually authenticate each session and limit the duration of the session, even if the connection is initiated over one or more existing trusted channels;
- Use appropriate user authentication (e.g., multi-factor authentication to permit privileged device access to system administrators, service technicians, or maintenance personnel, among others, as needed);
- Require authentication, and authorization in certain instances, before permitting software or firmware updates, including those updates affecting the operating system, applications, and anti-malware functionality;
- Strengthen password protections. Do not use passwords that are hardcoded, default, easily guessed, or easily compromised (e.g., passwords that are the same for each device; unchangeable; can persist as default; difficult to change; and/or vulnerable to public disclosure);
- Implement anti-replay measures in critical communications such as potentially harmful commands. This can be accomplished with the use of several methods including the use of cryptographic nonces (an arbitrary number used only once in a cryptographic communication);
- Provide mechanisms for verifying the authenticity of information originating from the device, such as telemetry. This is especially important for data that, if spoofed or otherwise modified, could result in patient harm, such as the link between a clinician programmer or monitoring device and an implanted device like a pacemaker, defibrillator, or neurostimulator; or the link between a continuous glucose monitor system and an automated insulin pump;
- Do not rely on cyclic redundancy checks (CRCs) as security controls. CRCs do not provide integrity or authentication protections in a security environment. While CRCs are an error detecting code and provide integrity protection against environmental factors (e.g., noise or EMC), they do not provide protections against an intentional or malicious actor; and
- Consider how the device and/or system should respond in event of authentication failure(s).

## B. Authorization
For the purposes of this guidance, authorization is the right or a permission that is granted to a system entity (e.g., a device, server, or software function) to access a system resource. More specifically, as a defensive measure, an authorization scheme enforces privileges (i.e., "rights" associated with authenticated sessions, identities and/or roles). These privileges either permit allowed behavior, or refuse disallowed behavior in order to ensure that system resources are only accessed in accepted ways, by accepted parties.

Within an adequately designed authorization scheme, the principle of least privileges[^76] should be applied to users, system functions, and others, to only allow those entities the levels of system access necessary to perform a specific function.

For example, in a situation in which a malicious actor has gained access to a credential associated with patient privileges, that malicious actor should not be able to access device resources or functionality reserved for the manufacturer or for the healthcare provider, such as device maintenance routines or the ability to change medication dosage amounts.

While authentication schemes based on cryptographically proven designs are generally considered more robust and are therefore preferred, meaningful authorization checks can be performed based on other compelling evidence (e.g., benefit/risk assessment in accordance with Section 6.5 of AAMI TIR57 or Section 7.4 of ANSI/AAMI SW96 and associated supporting justification and as evidenced through security testing). For example, a medical device programmer that is capable of Near-Field Communications (NFC) could have elevated privileges that are granted based on a signal of intent[^77] over NFC that cannot physically be produced by another unauthorized device over Radio-Frequency (RF) (e.g., a home monitor).

The following list provides recommended design implementations for an authorization scheme:

- Limit authorized access to devices through the authentication of users (e.g., user ID and password, smartcard, biometric, certificates, or other appropriate authentication method);
- Use automatic timed methods to terminate sessions within the medical device system where appropriate for the use environment;
- Employ an authorization model that incorporates the principle of least privileges by differentiating privileges based on the user role (e.g., caregiver, patient, healthcare provider, system administrator) or device functions; and
- Design devices to "deny by default" (i.e., that which is not expressly permitted by a device is denied by default). For example, the device should generally reject all unauthorized connections (e.g., incoming TCP, USB, Bluetooth, serial connections). Ignoring requests is one form of denying authorization.

## C. Cryptography
Cryptographic algorithms and protocols are recommended to be implemented to achieve the secure by design objectives outlined in Section IV. While high-quality, standardized cryptographic algorithms and protocols are readily available, several commercial products that include cryptographic protections have been shown to have exploitable vulnerabilities due to improper configurations and/or implementations.

While other sections of this guidance reference cryptographic controls, the following recommendations are specifically related to the selection and implementation of the underlying cryptographic scheme used by a device and the larger system in which it operates:

- Select industry-standard cryptographic algorithms and protocols, and select appropriate key generation, distribution, management and protection, as well as robust nonce mechanisms.
- Use current NIST recommended standards for cryptography (e.g., FIPS 140-3[^78]) or equivalent-strength cryptographic protection that are expected to be considered cryptographically strong throughout the service life of the device.
  - Manufacturers should not implement cryptographic algorithms that have been deprecated or disallowed in applicable standards or best practices (e.g., NIST SP 800-131A, Transitioning the Use of Cryptographic Algorithms and Key Lengths). Implementation of algorithms with a status of "legacy use" should be discussed with FDA during a pre-submission meeting.
- Design a system architecture and implement security controls to prevent a situation where the full compromise of any single device can result in the ability to reveal keys for other devices.
  - For example, avoid using master-keys stored on device, or key derivation algorithms based solely on device identifiers or other readily discoverable information.
  - For example, avoid using device serial numbers as keys or as part of keys. Device serial numbers may be disclosed by patients seeking additional information on their device or might be disclosed during a device recall to identify affected products and should be avoided as part of the key generation process (e.g., public-key cryptography can be employed to help meet this objective).
- Implement cryptographic protocols that permit negotiated parameters/versions such that the most recent, secure configurations are used, unless otherwise necessary.
- Do not allow downgrades, or version rollbacks, unless absolutely necessary for safety reasons, and log and document the event. Downgrades can allow attackers to exploit prior, less protected versions and should be avoided.

## D. Code, Data, and Execution Integrity
Many cyber incidents are caused, at their root, by the violation of some form of device integrity. This includes the violation of stored code, stored and operational data, or execution state. The following recommendations are provided to address each of these categories.

- **Code Integrity**
  - Hardware-based security solutions should be considered and employed when possible;
  - Authenticate firmware and software. Verify authentication tags (e.g., signatures, message authentication codes (MACs)) of software/firmware content, version numbers, and other metadata. The version numbers intended to be installed should themselves be signed or have MACs. Devices should be electronically and visibly identifiable (e.g., Unique device identifier (UDI),[^79] model number, serial number);
  - Allow installation of cryptographically authenticated firmware and software updates, and do not allow installation where such cryptographic authentication either is absent or fails. Use cryptographically signed updates to help prevent any unauthorized reductions in the level of protection (downgrade or rollback attacks) by ensuring that the new update represents an authorized version change;
    - One possible approach for authorized downgrades would be to sign new metadata for downgrade requests which, by definition, only happen in exceptional circumstances.
  - Ensure that the authenticity of software, firmware, and configuration are validated prior to execution, e.g., "allow-listing"[^80] based on digital signatures;
  - Disable or otherwise restrict unauthorized access to all test and debug ports (e.g., JTAG, UART) prior to delivering products; and
  - Employ tamper evident seals on device enclosures and their sensitive communication ports to help verify physical integrity.
- **Data Integrity**
  - Verify the integrity of all incoming data, ensuring that it is not modified in transit or at rest. Cryptographic authentication schemes verify data integrity, but do not verify data validity. Therefore, the integrity of all incoming data should be verified to ensure that it is not modified in transit or at rest;
  - Validate that all data originating from external sources is well-formed and compliant with the expected protocol or specification. Additionally, as appropriate, validate data ranges to ensure they fall within safe limits; and
  - Protect the integrity of data necessary to ensure the safety and effectiveness of the device, e.g., critical configuration settings such as energy output.
- **Execution Integrity**
  - Use industry-accepted best practices to maintain and verify integrity of code while it is being executed on the device. For example, Host-based Intrusion Detection/Prevention Systems (HIDS/HIPS) can be used to accomplish this goal; and
  - Carefully design and review all code that handles the parsing of external data using automated (e.g., static and dynamic analyses) and manual (i.e., code review) methods.

## E. Confidentiality
Manufacturers should ensure support for the confidentiality[^81] of any/all data whose disclosure could lead to patient harm (e.g., through the unauthorized use of otherwise valid credentials, lack of encryption). Loss of confidentiality of credentials could be used by a threat-actor to effect multi-patient harm. Lack of encryption to protect sensitive information and or data at rest and in transit can expose this information to misuse that can lead to patient harm. For example, confidentiality is required in the handling and storage of cryptographic keys used for authentication because disclosure could lead to unauthorized use/abuse of device functionality.

The proper implementation of authorization and authentication schemes as described in Sections A and B of this appendix will generally ensure confidentiality. However, manufacturers should evaluate and assess whether this is the case during their threat modeling and other risk management activities and make any appropriate changes to their medical device systems to ensure appropriate confidentiality controls are in place.

## F. Event Detection and Logging
Event detection and logging are critical capabilities that should be present in a device and the larger system in which it operates in order to ensure that suspected and successful attempts to compromise a medical device may be identified and tracked. These event detection capabilities and logs should include storage capabilities, if possible, so that forensic discovery may later be performed.

While many of the following recommendations are tailored for workstations, the concepts presented below also apply to embedded computing devices. Manufacturers should consider the following for all devices:

- Implement design features that allow for security compromises and suspected compromise attempts to be detected, recognized, logged, timed, and acted upon during normal use. Acting upon security events should consider the benefit/risk assessment in accordance with Section 6.5 of AAMI TIR57 or Section 7.4 of ANSI/AAMI SW96 in determining whether it is appropriate to affect standard device functionality during a security event.
- Ensure the design enables forensic evidence capture.[^82] The design should include mechanisms to securely create and store log files off the device to track security events. Documentation should include how and where log files are located, stored, recycled, archived, and how they could be consumed by automated analysis software (e.g., IDS). Examples of security events include, but are not limited to, configuration changes, network anomalies, login attempts, and anomalous traffic (e.g., sending requests to unknown entities).
- Design devices such that the potential impact of vulnerabilities is limited by specifying a secure configuration. Secure configurations may include endpoint protections, such as anti-malware, firewall/firewall rules, allow-listing, defining security event parameters, logging parameters, physical security detection, and/or HIDS/HIPS.
- Design devices such that they may integrate and/or leverage antivirus/anti-malware protection capabilities. These capabilities may vary depending on the type of device and the software and hardware components it contains:
  - For devices that leverage Windows Operating System:
    - Antivirus/anti-malware is recommended on the device. Manufacturers are recommended to qualify multiple options to support user preferences for different options, especially if the device is used in healthcare facility environments.
  - For devices that leverage other Commercial Operating Systems (e.g., Ubuntu, Unix, Linux, Apple, Android):
    - Antivirus/anti-malware may be recommended based on the environment and associated risks of the device. Different operating systems will likely follow a case-by-case determination based on network exposure and risk.
  - For devices that leverage Embedded Operating Systems (e.g., Real-Time Operating Systems, Windows embedded):
    - Antivirus/malware detection/protection software is generally not needed unless a particular risk or threat is identified that would not be addressed by other expected security controls.
- Design devices to enable software configuration management and permit tracking and control of software changes to be electronically obtainable (i.e., machine readable) by authorized users.
- Design devices to facilitate the performance of variant analyses such that the same vulnerabilities can be identified across device models and product lines.
- Design devices to notify users when malfunctions or anomalous device behavior, including those potentially related to a cybersecurity breach, are detected.
- Consider designing devices such that they are able to produce an SBOM in a machine readable format.

## G. Resiliency and Recovery
Devices should be designed to be resilient to possible cyber incident scenarios (also known as "cyber-resiliency") and maintain availability. Cyber-resiliency capabilities are important for medical devices because they provide a safety margin against unknown future vulnerabilities. The following recommendations are intended to help designers achieve cyber-resiliency:

- Implement features that protect critical functionality and data, even when the device has been partially compromised. For example, process isolation, virtualization techniques, and hardware-backed trusted execution environments all provide mechanisms to potentially contain the impact of a successful exploitation of a device.
- Design devices to provide methods for retention and recovery of trusted default device configuration by an authenticated, authorized user.
- Design devices to specify the level of resilience, or independent ability to function, that any component of the medical device system possesses when its communication capabilities with the rest of the medical device system are disrupted, including disruption of significant duration.
- Design devices to be resilient to possible cyber incident scenarios such as network outages, Denial of Service,[^83] excessive bandwidth usage by other products, disrupted quality of service (QoS),[^84] and/or excessive jitter[^85] (i.e., a variation in the delay of received packets).
- Design devices to be resilient to possible noise items (e.g., scanning).

## H. Firmware and Software Updates
Devices should be capable of being updated in a secure and timely manner to maintain safety and effectiveness throughout the product's lifecycle. Despite best efforts, undiscovered, exploitable vulnerabilities may exist in devices after they are marketed. This is especially true over the device's service life, as threats evolve over time and exploit methods change, and become more sophisticated.

FDA recommends that manufacturers should not only build in the ability for devices to be updated, but that manufacturers also plan for the rapid testing, evaluation, and patching of devices deployed in the field. The following recommendations can help to achieve this:

- Design devices to anticipate the need for software and firmware patches and updates to address future cybersecurity vulnerabilities. This will likely necessitate the need for additional storage space and processing resources.
- Consider update process reliability and how update process works in event of communication interruption or failure. This should include both considerations for hardware impacts (timing specifics of interruptions) and which phase of the update process the interruption or failure occurs.
- Consider cybersecurity patches and updates that are independent of regular feature update cycles.
- Implement processes, technologies, security architectures, and exercises to facilitate the rapid verification, validation, and distribution of patches and updates.
- Preserve and maintain full build environments and virtual machines, regression test suites, engineering development kits, emulators, debuggers, and other related tools that were used to develop and test the original product to ensure updates and patches may be applied safely and in a timely manner.
- Maintain necessary third-party licenses throughout the supported lifespan of the device. Develop contingency plans for the possibility that a third-party company goes out of business or stops supporting a licensed product. Modular designs should be considered such that third-party solutions could be readily replaced.
- Implement a secure process and mechanism for providing validated software updates and patches for users.

[^74]: For the purposes of this control, "information" includes the software/firmware itself, as well as input and output data. 본 통제의 목적상, "정보"에는 소프트웨어/펌웨어 자체뿐만 아니라 입력 및 출력 데이터가 포함됩니다.

[^75]: See the definition of security strength in Appendix 5, Terminology. 부록 5, 용어의 보안 강도 정의를 참조하십시오.

[^76]: CNSSI 4009-2015 defines "least privilege" as "The principle that a security architecture should be designed so that each entity (e.g., user, asset) is granted the minimum system resources and authorizations that the entity needs to perform its function." CNSSI 4009-2015는 "최소 권한"을 "보안 아키텍처가 각 엔티티(예: 사용자, 자산)에게 엔티티가 기능을 수행하는 데 필요한 최소한의 시스템 리소스 및 권한이 부여되도록 설계되어야 한다는 원칙"으로 정의합니다.

[^77]: For the purposes of this guidance, "signal of intent" is specific to the implementation of NFC communications. 본 가이던스의 목적상, "의도 신호"는 NFC 통신 구현에 특정합니다.

[^78]: See NIST FIPS 140-3 Security Requirements for Cryptographic Modules. https://doi.org/10.6028/NIST.FIPS.140-3 NIST FIPS 140-3 암호화 모듈에 대한 보안 요구사항을 참조하십시오. https://doi.org/10.6028/NIST.FIPS.140-3

[^79]: For more information regarding UDI, see FDA's webpage UDI Rule, Guidances, Training, and Other Resources. UDI에 관한 자세한 정보는 FDA의 웹페이지 UDI 규칙, 가이던스, 교육 및 기타 리소스를 참조하십시오.

[^80]: For the purposes of this guidance, "allow-list" means a list of discrete entities, such as hosts or applications that are known to be benign and are approved for use within an organization and/or information system. This term is leveraged from the definition of "whitelist" in NIST SP 800-128. https://doi.org/10.6028/NIST.SP.800-128 본 가이던스의 목적상, "허용 목록"은 양성으로 알려져 있고 조직 및/또는 정보 시스템 내에서 사용하도록 승인된 호스트 또는 애플리케이션과 같은 개별 엔티티 목록을 의미합니다. 이 용어는 NIST SP 800-128의 "화이트리스트" 정의에서 활용됩니다. https://doi.org/10.6028/NIST.SP.800-128

[^81]: For the purposes of this guidance, loss of confidential health information is generally not considered to be a direct impact on safety and effectiveness. Although protecting the confidentiality of PHI is beyond the scope of this document, it should be noted that manufacturers and other entities, depending on the facts and circumstances, may be obligated to protect the confidentiality, integrity and availability of PHI throughout the product lifecycle, in accordance with applicable federal and state laws, including the Health Insurance Portability and Accountability Act (HIPAA). For more information on HIPAA, please see the Summary of the HIPAA Security Rule. 본 가이던스의 목적상, 기밀 건강 정보의 손실은 일반적으로 안전성과 효과성에 대한 직접적인 영향으로 간주되지 않습니다. PHI의 기밀성을 보호하는 것은 본 문서의 범위를 벗어나지만, 제조업체 및 기타 엔티티는 사실 및 상황에 따라 건강 보험 이동성 및 책임에 관한 법률(HIPAA)을 포함한 적용 가능한 연방 및 주 법률에 따라 제품 수명주기 동안 PHI의 기밀성, 무결성 및 가용성을 보호할 의무가 있을 수 있다는 점에 유의해야 합니다. HIPAA에 대한 자세한 정보는 HIPAA 보안 규칙 요약을 참조하십시오.

[^82]: Forensic evidence capture is a necessary part of digital forensics. NIST SP 800-86 defines digital forensics as "The application of science to the identification, collection, examination, and analysis, of data while preserving the integrity of the information and maintaining a strict chain of custody for the data." https://doi.org/10.6028/NIST.SP.800-86 포렌식 증거 캡처는 디지털 포렌식의 필수 부분입니다. NIST SP 800-86은 디지털 포렌식을 "정보의 무결성을 보존하고 데이터에 대한 엄격한 보관 사슬을 유지하면서 데이터의 식별, 수집, 검사 및 분석에 과학을 적용하는 것"으로 정의합니다. https://doi.org/10.6028/NIST.SP.800-86

[^83]: Denial of Service is an attack that prevents or impairs the authorized use of the information system, resources, or services. 서비스 거부는 정보 시스템, 리소스 또는 서비스의 승인된 사용을 방지하거나 손상시키는 공격입니다.

[^84]: From the CNSSI 4009 National Information Assurance (IA) Glossary. CNSSI 4009 국가 정보 보증(IA) 용어집에서.

[^85]: From the NIST Computer Security Resource Center Glossary. NIST 컴퓨터 보안 리소스 센터 용어집에서.

# 부록 1. 보안 통제 범주 및 관련 권장사항
다음 섹션은 섹션 V.B.1에서 소개된 각 보안 통제 범주에 대한 상세한 설명과 일반적인 함정을 피하기 위한 보안 통제 및 그 구현에 대한 구체적인 권장사항을 제공합니다.

## A. 인증(Authentication)
일반적으로 두 가지 유형의 인증 통제—정보 및 엔티티—가 있으며, 적절하게 보안된 시스템은 둘 다의 존재를 증명할 수 있습니다.

정보의 인증[^74]은 기기 및 기기가 작동하는 시스템이 정보가 알려지고 신뢰할 수 있는 출처에서 유래했으며 원래 출처와 진위성이 확인되는 지점 사이의 전송 중에 정보가 변경되지 않았음을 증명할 수 있는 경우에 존재합니다. 진위성은 데이터가 정확하고 무단 사용자 수정(즉, 무결성)으로부터 보호되었음을 의미하지만, 무결성만으로는 데이터가 실제이고 신뢰할 수 있는 출처에서 나왔다는 보증을 제공하지 않는다는 점에 유의하는 것이 중요합니다. 따라서 본 가이던스의 목적상, 인증은 무결성에 대한 더 큰 보안 목표로 논의됩니다.

엔티티의 인증은 기기 및 기기가 작동하는 시스템이 정보를 송수신하는 엔드포인트(하드웨어 및/또는 소프트웨어) 또는 해당 엔드포인트의 승인된 사용자/운영자의 신원을 증명할 수 있는 경우에 존재합니다.

보안 시스템 내의 정상 작동의 일부로, 기기는 외부 엔티티로부터의 정보의 진위성을 확인하고 자신이 생성하는 정보의 진위성을 증명해야 합니다. 진위성을 적절하게 고려하는 의료기기 시스템은 다음에 대한 진위성을 평가하고 보장할 수 있습니다:

- 저장된 정보(정지 상태);
- 전송 중인 정보(전송);
- 소프트웨어 또는 하드웨어로 구성된 엔드포인트인지 여부에 관계없이 통신 엔드포인트의 엔티티 인증;
- 소프트웨어 바이너리;
- 현재 실행 중인 소프트웨어의 실행 상태 무결성; 그리고
- 제조업체의 위협 모델 및/또는 위험 분석이 필요성을 나타내는 의료기기 시스템의 다른 적절한 부분.

기술적 수준에서, 기기의 인증 체계의 강도는 무단 당사자가 인증 체계의 분해를 식별하기 위해 소비해야 하는 시간을 포함한 노력의 양으로 정의됩니다. 예를 들어, 이는 암호화 기반 인증 체계가 구축되는 암호화 함수의 올바른 "출력"을 결정하는 데 필요한 시간과 리소스일 수 있으며, 무단 당사자가 이를 사용하여 인증 체계를 우회하고 의료기기 시스템에 대한 접근을 얻을 수 있습니다.

인증 체계를 선택할 때, 제조업체는 다양한 유형의 체계에 대한 다음과 같은 일반적으로 적용 가능한 특성을 염두에 두어야 합니다:

- 비암호화 인터페이스, 핸드셰이크 및/또는 프로토콜에만 기반한 암묵적 인증 체계는 본질적으로 약한데, 일단 리버스 엔지니어링되면 무단 사용자가 올바른 동작을 쉽게 에뮬레이션하고 승인된 것처럼 보일 수 있기 때문입니다.
- 암호화 인증 프로토콜이 일반적으로 우수하지만, 전체 강도를 달성하기 위해서는 신중한 설계 선택과 구현 관행이 필요합니다.

또한, 이러한 체계는 여전히 체계와 상호 작용하는 데 필요한 암호화 키의 기밀성과 해당 키를 보유하거나 활용하는 기기의 무결성에 의해 제한됩니다. 암호화에 대한 자세한 정보는 아래 부록 1 하위 섹션 C를 참조하십시오. 따라서 비인증 동작이 피해로 이어질 수 있는 기기 작동의 경우, 기기는 명령/세션을 승인하기 위해 순간 스위치와 같은 물리적 조치에 기반한 추가적이고 비일상적인 의도 신호를 구현해야 합니다.

다음 목록은 인증 체계 구현에 대한 추가 권장사항을 제공합니다:

- 인증 기능이 기기에 있는 경우, 암호화적으로 강력한[^75] 인증을 사용하여 인력, 메시지, 명령 업데이트 및 해당되는 경우 다른 모든 통신 경로를 인증합니다. 가능한 경우 하드웨어 기반 보안 솔루션을 고려하고 사용해야 합니다;
- 관련 위험에 상응하는 빈도로 외부 연결을 인증합니다. 예를 들어, 기기가 오프사이트 서버에 연결되는 경우, 기기와 서버는 각 세션을 상호 인증하고 연결이 하나 이상의 기존 신뢰 채널을 통해 시작되더라도 세션 기간을 제한해야 합니다;
- 적절한 사용자 인증을 사용합니다(예: 필요에 따라 시스템 관리자, 서비스 기술자 또는 유지보수 인력 등에게 기기에 대한 특권 접근을 허용하기 위한 다중 인증);
- 운영 체제, 애플리케이션 및 악성 소프트웨어 방지 기능에 영향을 미치는 업데이트를 포함하여 소프트웨어 또는 펌웨어 업데이트를 허용하기 전에 인증 및 특정 경우 권한 부여를 요구합니다;
- 비밀번호 보호를 강화합니다. 하드코딩되거나, 기본값이거나, 쉽게 추측되거나, 쉽게 손상되는 비밀번호(예: 각 기기에 대해 동일한 비밀번호; 변경할 수 없음; 기본값으로 지속될 수 있음; 변경하기 어려움; 및/또는 공개 공개에 취약함)를 사용하지 마십시오;
- 잠재적으로 해로운 명령과 같은 중요한 통신에서 재생 방지 조치를 구현합니다. 이는 암호화 논스(암호화 통신에서 한 번만 사용되는 임의의 숫자)의 사용을 포함한 여러 방법의 사용으로 달성될 수 있습니다;
- 원격 측정과 같이 기기에서 유래하는 정보의 진위성을 확인하기 위한 메커니즘을 제공합니다. 이는 스푸핑되거나 수정될 경우 환자 피해를 초래할 수 있는 데이터, 예를 들어 임상의 프로그래머 또는 모니터링 기기와 심박조율기, 제세동기 또는 신경자극기와 같은 이식 기기 간의 링크; 또는 연속 포도당 모니터 시스템과 자동 인슐린 펌프 간의 링크의 경우 특히 중요합니다;
- 순환 중복 검사(CRC)를 보안 통제로 의존하지 마십시오. CRC는 보안 환경에서 무결성 또는 인증 보호를 제공하지 않습니다. CRC는 오류 감지 코드이며 환경 요인(예: 노이즈 또는 EMC)에 대한 무결성 보호를 제공하지만 의도적이거나 악의적인 행위자에 대한 보호를 제공하지 않습니다; 그리고
- 인증 실패 시 기기 및/또는 시스템이 어떻게 대응해야 하는지 고려합니다.

## B. 권한 부여(Authorization)
본 가이던스의 목적상, 권한 부여는 시스템 리소스에 접근하기 위해 시스템 엔티티(예: 기기, 서버 또는 소프트웨어 기능)에 부여되는 권리 또는 허가입니다. 보다 구체적으로, 방어 수단으로서 권한 부여 체계는 권한(즉, 인증된 세션, 신원 및/또는 역할과 관련된 "권리")을 시행합니다. 이러한 권한은 허용된 동작을 허가하거나, 시스템 리소스가 승인된 당사자에 의해 승인된 방식으로만 접근되도록 보장하기 위해 허용되지 않는 동작을 거부합니다.

적절하게 설계된 권한 부여 체계 내에서, 최소 권한 원칙[^76]이 사용자, 시스템 기능 및 기타에 적용되어 해당 엔티티에게 특정 기능을 수행하는 데 필요한 시스템 접근 수준만 허용해야 합니다.

예를 들어, 악의적인 행위자가 환자 권한과 관련된 자격 증명에 대한 접근을 얻은 상황에서, 해당 악의적인 행위자는 기기 유지보수 루틴 또는 약물 투여량을 변경하는 능력과 같이 제조업체 또는 의료 제공자를 위해 예약된 기기 리소스 또는 기능에 접근할 수 없어야 합니다.

암호화적으로 증명된 설계를 기반으로 한 인증 체계가 일반적으로 더 견고한 것으로 간주되어 선호되지만, 의미 있는 권한 부여 검사는 다른 설득력 있는 증거(예: AAMI TIR57의 섹션 6.5 또는 ANSI/AAMI SW96의 섹션 7.4에 따른 이익/위험 평가 및 관련 지원 정당화 및 보안 테스트를 통해 입증됨)를 기반으로 수행될 수 있습니다. 예를 들어, 근거리 통신(NFC)이 가능한 의료기기 프로그래머는 무선 주파수(RF)를 통해 다른 무단 기기(예: 가정 모니터)가 물리적으로 생성할 수 없는 NFC를 통한 의도 신호[^77]를 기반으로 부여되는 높은 권한을 가질 수 있습니다.

다음 목록은 권한 부여 체계에 대한 권장 설계 구현을 제공합니다:

- 사용자 인증을 통해 기기에 대한 승인된 접근을 제한합니다(예: 사용자 ID 및 비밀번호, 스마트카드, 생체 인식, 인증서 또는 기타 적절한 인증 방법);
- 사용 환경에 적합한 경우 의료기기 시스템 내에서 세션을 종료하기 위한 자동 시간 지정 방법을 사용합니다;
- 사용자 역할(예: 간병인, 환자, 의료 제공자, 시스템 관리자) 또는 기기 기능에 따라 권한을 차별화하여 최소 권한 원칙을 통합하는 권한 부여 모델을 사용합니다; 그리고
- 기기가 "기본적으로 거부"하도록 설계합니다(즉, 기기에 의해 명시적으로 허용되지 않은 것은 기본적으로 거부됨). 예를 들어, 기기는 일반적으로 모든 무단 연결(예: 수신 TCP, USB, 블루투스, 직렬 연결)을 거부해야 합니다. 요청을 무시하는 것은 권한 부여를 거부하는 한 가지 형태입니다.

## C. 암호화(Cryptography)
암호화 알고리즘 및 프로토콜은 섹션 IV에 설명된 설계에 의한 보안 목표를 달성하기 위해 구현할 것을 권장합니다. 고품질의 표준화된 암호화 알고리즘 및 프로토콜을 쉽게 사용할 수 있지만, 암호화 보호를 포함하는 여러 상용 제품이 부적절한 구성 및/또는 구현으로 인해 악용 가능한 취약점을 가지고 있는 것으로 나타났습니다.

본 가이던스의 다른 섹션에서 암호화 통제를 참조하지만, 다음 권장사항은 기기 및 기기가 작동하는 더 큰 시스템에서 사용되는 기본 암호화 체계의 선택 및 구현과 구체적으로 관련됩니다:

- 산업 표준 암호화 알고리즘 및 프로토콜을 선택하고, 적절한 키 생성, 배포, 관리 및 보호뿐만 아니라 강력한 논스 메커니즘을 선택합니다.
- 기기의 서비스 수명 동안 암호화적으로 강력한 것으로 간주될 것으로 예상되는 암호화에 대한 현재 NIST 권장 표준(예: FIPS 140-3[^78]) 또는 동등한 강도의 암호화 보호를 사용합니다.
  - 제조업체는 적용 가능한 표준 또는 모범 사례(예: NIST SP 800-131A, 암호화 알고리즘 및 키 길이 사용 전환)에서 폐기되거나 허용되지 않은 암호화 알고리즘을 구현해서는 안 됩니다. "레거시 사용" 상태의 알고리즘 구현은 사전 제출 회의 중 FDA와 논의되어야 합니다.
- 단일 기기의 완전한 손상이 다른 기기의 키를 공개하는 능력을 초래할 수 있는 상황을 방지하기 위해 시스템 아키텍처를 설계하고 보안 통제를 구현합니다.
  - 예를 들어, 기기에 저장된 마스터 키 사용을 피하거나, 기기 식별자 또는 기타 쉽게 발견할 수 있는 정보에만 기반한 키 파생 알고리즘을 피합니다.
  - 예를 들어, 기기 일련번호를 키로 또는 키의 일부로 사용하지 마십시오. 기기 일련번호는 자신의 기기에 대한 추가 정보를 찾는 환자에 의해 공개되거나 영향을 받는 제품을 식별하기 위한 기기 리콜 중에 공개될 수 있으므로 키 생성 프로세스의 일부로 피해야 합니다(예: 공개 키 암호화는 이 목표를 달성하는 데 도움이 되도록 사용될 수 있음).
- 그렇지 않으면 필요하지 않는 한 가장 최근의 안전한 구성이 사용되도록 협상된 매개변수/버전을 허용하는 암호화 프로토콜을 구현합니다.
- 안전상의 이유로 절대적으로 필요하지 않는 한 다운그레이드 또는 버전 롤백을 허용하지 말고, 이벤트를 로깅하고 문서화합니다. 다운그레이드는 공격자가 이전의 덜 보호된 버전을 악용할 수 있게 하므로 피해야 합니다.

## D. 코드, 데이터 및 실행 무결성
많은 사이버 사고는 근본적으로 어떤 형태의 기기 무결성 위반에 의해 발생합니다. 여기에는 저장된 코드, 저장 및 운영 데이터, 또는 실행 상태의 위반이 포함됩니다. 다음 권장사항은 이러한 각 범주를 다루기 위해 제공됩니다.

- **코드 무결성**
  - 가능한 경우 하드웨어 기반 보안 솔루션을 고려하고 사용해야 합니다;
  - 펌웨어 및 소프트웨어를 인증합니다. 소프트웨어/펌웨어 콘텐츠, 버전 번호 및 기타 메타데이터의 인증 태그(예: 서명, 메시지 인증 코드(MAC))를 확인합니다. 설치하려는 버전 번호 자체가 서명되거나 MAC를 가져야 합니다. 기기는 전자적으로 그리고 시각적으로 식별 가능해야 합니다(예: 고유 기기 식별자(UDI),[^79] 모델 번호, 일련번호);
  - 암호화적으로 인증된 펌웨어 및 소프트웨어 업데이트의 설치를 허용하고, 이러한 암호화 인증이 없거나 실패하는 경우 설치를 허용하지 마십시오. 새 업데이트가 승인된 버전 변경을 나타내도록 보장하여 보호 수준의 무단 감소(다운그레이드 또는 롤백 공격)를 방지하기 위해 암호화 서명된 업데이트를 사용합니다;
    - 승인된 다운그레이드를 위한 한 가지 가능한 접근 방식은 정의상 예외적인 상황에서만 발생하는 다운그레이드 요청에 대한 새 메타데이터에 서명하는 것입니다.
  - 소프트웨어, 펌웨어 및 구성의 진위성이 실행 전에 검증되도록 보장합니다. 예: 디지털 서명을 기반으로 한 "허용 목록";[^80]
  - 제품을 인도하기 전에 모든 테스트 및 디버그 포트(예: JTAG, UART)에 대한 무단 접근을 비활성화하거나 제한합니다; 그리고
  - 기기 인클로저 및 민감한 통신 포트에 변조 방지 봉인을 사용하여 물리적 무결성을 확인하는 데 도움을 줍니다.
- **데이터 무결성**
  - 모든 수신 데이터의 무결성을 확인하여 전송 중 또는 저장 중에 수정되지 않았는지 확인합니다. 암호화 인증 체계는 데이터 무결성을 확인하지만 데이터 유효성은 확인하지 않습니다. 따라서 모든 수신 데이터의 무결성은 전송 중 또는 저장 중에 수정되지 않았는지 확인하기 위해 검증되어야 합니다;
  - 외부 소스에서 유래한 모든 데이터가 잘 형성되어 있고 예상되는 프로토콜 또는 사양을 준수하는지 확인합니다. 또한, 적절한 경우 데이터 범위가 안전한 한계 내에 속하는지 확인하기 위해 데이터 범위를 검증합니다; 그리고
  - 기기의 안전성과 효과성을 보장하는 데 필요한 데이터의 무결성을 보호합니다. 예: 에너지 출력과 같은 중요한 구성 설정.
- **실행 무결성**
  - 기기에서 실행되는 동안 코드의 무결성을 유지하고 확인하기 위해 산업계에서 인정하는 모범 사례를 사용합니다. 예를 들어, 호스트 기반 침입 탐지/방지 시스템(HIDS/HIPS)을 사용하여 이 목표를 달성할 수 있습니다; 그리고
  - 자동화된(예: 정적 및 동적 분석) 및 수동(즉, 코드 검토) 방법을 사용하여 외부 데이터의 파싱을 처리하는 모든 코드를 신중하게 설계하고 검토합니다.

## E. 기밀성(Confidentiality)
제조업체는 공개가 환자 피해로 이어질 수 있는 모든 데이터의 기밀성[^81](예: 유효한 자격 증명의 무단 사용, 암호화 부족)을 지원해야 합니다. 자격 증명의 기밀성 상실은 위협 행위자가 다중 환자 피해를 일으키는 데 사용될 수 있습니다. 민감한 정보 및 저장 중이거나 전송 중인 데이터를 보호하기 위한 암호화 부족은 이 정보를 환자 피해로 이어질 수 있는 오용에 노출시킬 수 있습니다. 예를 들어, 공개가 기기 기능의 무단 사용/남용으로 이어질 수 있기 때문에 인증에 사용되는 암호화 키의 처리 및 저장에서 기밀성이 요구됩니다.

본 부록의 섹션 A 및 B에 설명된 대로 권한 부여 및 인증 체계를 적절하게 구현하면 일반적으로 기밀성이 보장됩니다. 그러나 제조업체는 위협 모델링 및 기타 위험 관리 활동 중에 이것이 사실인지 평가하고 평가해야 하며, 적절한 기밀성 통제가 마련되도록 의료기기 시스템에 적절한 변경을 수행해야 합니다.

## F. 이벤트 탐지 및 로깅
이벤트 탐지 및 로깅은 의료기기를 손상시키려는 의심스럽고 성공적인 시도가 식별되고 추적될 수 있도록 보장하기 위해 기기 및 기기가 작동하는 더 큰 시스템에 존재해야 하는 중요한 기능입니다. 이러한 이벤트 탐지 기능 및 로그는 가능한 경우 저장 기능을 포함해야 하므로 나중에 포렌식 발견을 수행할 수 있습니다.

다음 권장사항 중 많은 부분이 워크스테이션에 맞춰져 있지만, 아래에 제시된 개념은 임베디드 컴퓨팅 기기에도 적용됩니다. 제조업체는 모든 기기에 대해 다음을 고려해야 합니다:

- 정상 사용 중에 보안 손상 및 의심되는 손상 시도가 탐지, 인식, 로깅, 시간 기록 및 조치될 수 있도록 하는 설계 기능을 구현합니다. 보안 이벤트에 대한 조치는 보안 이벤트 중에 표준 기기 기능에 영향을 미치는 것이 적절한지 결정하기 위해 AAMI TIR57의 섹션 6.5 또는 ANSI/AAMI SW96의 섹션 7.4에 따른 이익/위험 평가를 고려해야 합니다.
- 설계가 포렌식 증거 캡처를 가능하게 하도록 보장합니다.[^82] 설계는 보안 이벤트를 추적하기 위해 기기 밖에서 로그 파일을 안전하게 생성하고 저장하는 메커니즘을 포함해야 합니다. 문서는 로그 파일이 어떻게 그리고 어디에 위치하고, 저장되고, 재활용되고, 아카이브되는지, 그리고 자동화된 분석 소프트웨어(예: IDS)에 의해 어떻게 소비될 수 있는지 포함해야 합니다. 보안 이벤트의 예로는 구성 변경, 네트워크 이상, 로그인 시도 및 이상 트래픽(예: 알 수 없는 엔티티에 요청 전송)이 포함되지만 이에 국한되지 않습니다.
- 안전한 구성을 지정하여 취약점의 잠재적 영향이 제한되도록 기기를 설계합니다. 안전한 구성에는 악성 소프트웨어 방지, 방화벽/방화벽 규칙, 허용 목록, 보안 이벤트 매개변수 정의, 로깅 매개변수, 물리적 보안 탐지 및/또는 HIDS/HIPS와 같은 엔드포인트 보호가 포함될 수 있습니다.
- 기기가 바이러스 백신/악성 소프트웨어 방지 보호 기능을 통합 및/또는 활용할 수 있도록 설계합니다. 이러한 기능은 기기 유형과 포함된 소프트웨어 및 하드웨어 구성요소에 따라 달라질 수 있습니다:
  - Windows 운영 체제를 활용하는 기기의 경우:
    - 기기에 바이러스 백신/악성 소프트웨어 방지가 권장됩니다. 제조업체는 특히 기기가 의료 시설 환경에서 사용되는 경우 다양한 옵션에 대한 사용자 선호도를 지원하기 위해 여러 옵션을 검증할 것을 권장합니다.
  - 다른 상용 운영 체제(예: Ubuntu, Unix, Linux, Apple, Android)를 활용하는 기기의 경우:
    - 바이러스 백신/악성 소프트웨어 방지는 기기의 환경 및 관련 위험을 기반으로 권장될 수 있습니다. 다른 운영 체제는 네트워크 노출 및 위험을 기반으로 사례별 결정을 따를 가능성이 높습니다.
  - 임베디드 운영 체제(예: 실시간 운영 체제, Windows 임베디드)를 활용하는 기기의 경우:
    - 바이러스 백신/악성 소프트웨어 탐지/보호 소프트웨어는 다른 예상 보안 통제로 해결되지 않는 특정 위험 또는 위협이 식별되지 않는 한 일반적으로 필요하지 않습니다.
- 소프트웨어 구성 관리를 가능하게 하고 승인된 사용자가 소프트웨어 변경 사항을 전자적으로 추적하고 제어할 수 있도록(즉, 기계 판독 가능) 기기를 설계합니다.
- 동일한 취약점이 기기 모델 및 제품 라인 전반에 걸쳐 식별될 수 있도록 변형 분석의 수행을 용이하게 하도록 기기를 설계합니다.
- 사이버보안 침해와 잠재적으로 관련된 것을 포함하여 오작동 또는 이상 기기 동작이 탐지될 때 사용자에게 알리도록 기기를 설계합니다.
- 기기가 기계 판독 가능한 형식으로 SBOM을 생성할 수 있도록 설계하는 것을 고려합니다.

## G. 복원력 및 복구
기기는 가능한 사이버 사고 시나리오("사이버 복원력"이라고도 함)에 복원력이 있고 가용성을 유지하도록 설계되어야 합니다. 사이버 복원력 기능은 알려지지 않은 미래 취약점에 대한 안전 마진을 제공하기 때문에 의료기기에 중요합니다. 다음 권장사항은 설계자가 사이버 복원력을 달성하는 데 도움을 주기 위한 것입니다:

- 기기가 부분적으로 손상된 경우에도 중요한 기능과 데이터를 보호하는 기능을 구현합니다. 예를 들어, 프로세스 격리, 가상화 기술 및 하드웨어 지원 신뢰 실행 환경은 모두 기기의 성공적인 악용의 영향을 잠재적으로 억제하는 메커니즘을 제공합니다.
- 인증되고 승인된 사용자가 신뢰할 수 있는 기본 기기 구성의 보존 및 복구를 위한 방법을 제공하도록 기기를 설계합니다.
- 의료기기 시스템의 나머지 부분과의 통신 기능이 중단될 때, 상당한 기간의 중단을 포함하여, 의료기기 시스템의 모든 구성요소가 보유한 복원력 또는 독립적인 기능 수행 능력의 수준을 지정하도록 기기를 설계합니다.
- 네트워크 중단, 서비스 거부,[^83] 다른 제품에 의한 과도한 대역폭 사용, QoS(서비스 품질)[^84] 중단 및/또는 과도한 지터[^85](즉, 수신된 패킷의 지연 변동)와 같은 가능한 사이버 사고 시나리오에 복원력이 있도록 기기를 설계합니다.
- 노이즈 항목(예: 스캐닝)에 대해 복원력이 있도록 기기를 설계합니다.

## H. 펌웨어 및 소프트웨어 업데이트
기기는 제품의 수명주기 동안 안전성과 효과성을 유지하기 위해 안전하고 시기적절한 방식으로 업데이트될 수 있어야 합니다. 최선의 노력에도 불구하고, 기기가 시판된 후에 발견되지 않은 악용 가능한 취약점이 존재할 수 있습니다. 이는 위협이 시간이 지남에 따라 진화하고 악용 방법이 변경되고 더욱 정교해짐에 따라 기기의 서비스 수명 동안 특히 그렇습니다.

FDA는 제조업체가 기기를 업데이트할 수 있는 기능을 구축할 뿐만 아니라 현장에 배치된 기기의 신속한 테스트, 평가 및 패치를 위한 계획도 세워야 한다고 권장합니다. 다음 권장사항은 이를 달성하는 데 도움이 될 수 있습니다:

- 미래의 사이버보안 취약점을 해결하기 위한 소프트웨어 및 펌웨어 패치 및 업데이트의 필요성을 예상하도록 기기를 설계합니다. 이는 추가 저장 공간 및 처리 리소스의 필요성을 필요로 할 가능성이 높습니다.
- 통신 중단 또는 실패 시 업데이트 프로세스 신뢰성 및 업데이트 프로세스가 어떻게 작동하는지 고려합니다. 여기에는 하드웨어 영향(중단의 타이밍 세부사항)과 업데이트 프로세스의 어느 단계에서 중단 또는 실패가 발생하는지에 대한 고려사항이 모두 포함되어야 합니다.
- 정기적인 기능 업데이트 주기와 독립적인 사이버보안 패치 및 업데이트를 고려합니다.
- 패치 및 업데이트의 신속한 검증, 타당성 확인 및 배포를 용이하게 하기 위한 프로세스, 기술, 보안 아키텍처 및 연습을 구현합니다.
- 업데이트 및 패치가 안전하고 시기적절하게 적용될 수 있도록 보장하기 위해 원본 제품을 개발하고 테스트하는 데 사용된 전체 빌드 환경 및 가상 머신, 회귀 테스트 제품군, 엔지니어링 개발 키트, 에뮬레이터, 디버거 및 기타 관련 도구를 보존하고 유지합니다.
- 기기의 지원 수명 동안 필요한 타사 라이선스를 유지합니다. 타사 회사가 폐업하거나 라이선스 제품 지원을 중단할 가능성에 대한 비상 계획을 개발합니다. 타사 솔루션을 쉽게 교체할 수 있도록 모듈식 설계를 고려해야 합니다.
- 사용자를 위한 검증된 소프트웨어 업데이트 및 패치를 제공하기 위한 안전한 프로세스 및 메커니즘을 구현합니다.

# Appendix 2. Submission Documentation for Security Architecture Flows
In premarket submissions, FDA recommends that manufacturers provide detailed information for the views identified in Section V.B.2. Methods for providing the views and the recommendations for the level of detail to provide are discussed in the sections below. In addition to diagrams and explanatory text, call-flow views can be provided to convey some of the information details expected to be addressed in the architecture views.

## A. Diagrams
FDA recommends that manufacturers provide diagrams to help describe the medical device system architecture, interfaces, communication protocols, threats, and cybersecurity controls used throughout the system. Different diagramming methods can be used to describe the architecture, including data flow diagrams, state diagrams, swim-lane diagrams, and call-flow diagrams, among others. Architecture views should include diagram(s) with explanatory text that describes the sequence of process or protocol steps in explicit detail for an associated use case. Architecture views should provide specific protocol details of the communication pathways between parts of the medical device system, to include authentication or authorization procedures and session management techniques. These views should be sufficiently detailed such that engineers and reviewers should be able to logically and easily follow data, code, and commands from any asset (e.g., a manufacturer server) to any other associated asset (e.g., a medical device), while possibly crossing intermediate assets (e.g., application). The diagrams may also include items from the information details identified below for the architecture views identified in Section V.B.2 if the information is better represented or conveyed through a diagram than explanatory text alone.

## B. Information Details for an Architecture View
For each view described in Section V.B.2, manufacturers should provide a system-level description and analysis inclusive of end-to-end security analyses of all the communications in the medical device system regardless of intended use. This should include detailed diagrams and traces for all communication paths as described below. Security-relevant analysis requires the ability to construct and follow a detailed trace for important communication paths, which describes how data, code, and commands are protected between any two assets in the medical device system. This analysis can also help identify the software that should be included in the SBOM for each device.

FDA recommends that security architecture views should consider the following examples of information for inclusion:

- Detailed diagrams and supporting explanatory text that identify all medical device system assets, including but not limited to:
  - Device hardware itself (including assessments for any commercial platforms);
  - Applications, hardware, and/or other supporting assets that directly interact with the targeted device, such as configuration, installation/upgrade, and data transfer applications;
  - Healthcare facility-operated assets;
  - Communications/networking assets; and
  - Manufacturer-controlled assets, including any servers that interact with external entities (e.g., a server that collects and redistributes device data, or a firmware update server).
- For every communication path that exists between any two assets in the security use case view (and/or explanatory text), including indirect connections when there is at least one intermediate asset (e.g., an app), the following details should be provided:
  - A list of the communication interfaces and paths, including communication paths (e.g., between two assets through an intermediary), and any unused interfaces;
  - An indication of whether the path is used for data, code, and/or commands, and type of data/information/code being transferred;
  - Protocol name(s), version number(s), and ports/channels/frequencies;
  - Detailed descriptions of the primary and all available functionality for each medical device system asset, including assessment of any functionality that is built in but not currently used or enabled (e.g., dormant application functionality or ports), including assurance that this functionality cannot be activated and/or misused;
  - Access control models or features (if any) for every asset (such as privileges, user accounts/groups, passwords);
  - Users' roles and levels of responsibility if they interact with the assets and communication channels;
  - Any "handoff" sequences from one communication path to another (e.g., from asset to asset, network to network, or Bluetooth to Wi-Fi), and how the data, code, and/or commands are secured/protected during handoff (i.e., how is their integrity/authenticity ensured);
  - Explanations of intended behavior in unusual/erroneous/unexpected circumstances (e.g., termination of a connection in the middle of a data transfer);
  - Authentication mechanism (if any), including the algorithm name/version (if available), "strength" indicators (e.g., key bit length, number of computational rounds) and mode of operation (if applicable);
  - Descriptions of the cryptographic method used and the type and level of cryptographic key usage and their style of use throughout the medical device system (e.g., one-time use, key length, the standard employed, symmetric or otherwise). Descriptions should also include details of cryptographic protection for firmware and software updates;
  - Detailed analyses by cryptography experts if a cryptography algorithm is proprietary, or a proprietary modification of a standard algorithm;
  - For each authenticator created, a list of where it is verified, and how verification credentials (e.g., certificates, asymmetric keys, or shared keys) are distributed to both endpoints;
  - A precise, detailed list of how each type of credential (e.g., password, key) is generated, stored, configured, transferred, and maintained, including both manufacturer- and healthcare facility-controlled assets (e.g., key management and public key infrastructure (PKI));
  - Identity management[^86] (if any), including how identities are managed/transferred and configured (e.g., from manufacturer to programmer and from programmer to device);
  - If communication sessions are used or supported, a detailed explanation of how sessions are established, maintained, and broken down, including but not limited to assurances of security properties such as uniqueness, unpredictability, time-stamping, and verification of session identifiers;
  - Include any security configuration settings and their default values;
  - Precise links between diagram elements (or explanatory text), associated hazards and controls, and testing;
  - Explanations or links to the evidence that may be used to justify security claims and any assumptions; and
  - Traceability of the asset to the SBOM component described in Section V.B.2, above, for proprietary and third-party code, when appropriate.

[^86]: For the purposes of this guidance, "identity management" means the process that governs the authentication and authorization of users to devices and assets. 본 가이던스의 목적상, "신원 관리"는 기기 및 자산에 대한 사용자의 인증 및 권한 부여를 관리하는 프로세스를 의미합니다.

# 부록 2. 보안 아키텍처 흐름에 대한 제출 문서
시판 전 제출에서, FDA는 제조업체가 섹션 V.B.2에서 식별된 뷰에 대한 상세한 정보를 제공할 것을 권장합니다. 뷰를 제공하는 방법과 제공할 세부 수준에 대한 권장사항은 아래 섹션에서 논의됩니다. 다이어그램 및 설명 텍스트 외에도, 아키텍처 뷰에서 다루어질 것으로 예상되는 정보 세부사항의 일부를 전달하기 위해 호출 흐름 뷰가 제공될 수 있습니다.

## A. 다이어그램
FDA는 제조업체가 의료기기 시스템 아키텍처, 인터페이스, 통신 프로토콜, 위협 및 시스템 전반에 걸쳐 사용되는 사이버보안 통제를 설명하는 데 도움이 되는 다이어그램을 제공할 것을 권장합니다. 데이터 흐름 다이어그램, 상태 다이어그램, 스윔 레인 다이어그램, 호출 흐름 다이어그램 등을 포함하여 아키텍처를 설명하기 위해 다양한 다이어그램 방법을 사용할 수 있습니다. 아키텍처 뷰는 관련 사용 사례에 대한 프로세스 또는 프로토콜 단계의 시퀀스를 명시적으로 상세하게 설명하는 설명 텍스트가 포함된 다이어그램을 포함해야 합니다. 아키텍처 뷰는 인증 또는 권한 부여 절차 및 세션 관리 기술을 포함하여 의료기기 시스템의 부분 간 통신 경로의 구체적인 프로토콜 세부사항을 제공해야 합니다. 이러한 뷰는 엔지니어와 검토자가 중간 자산(예: 애플리케이션)을 거칠 수 있는 동안 모든 자산(예: 제조업체 서버)에서 다른 관련 자산(예: 의료기기)으로 데이터, 코드 및 명령을 논리적으로 그리고 쉽게 따라갈 수 있도록 충분히 상세해야 합니다. 다이어그램은 또한 정보가 설명 텍스트만으로보다 다이어그램을 통해 더 잘 표현되거나 전달되는 경우 섹션 V.B.2에서 식별된 아키텍처 뷰에 대해 아래에서 식별된 정보 세부사항의 항목을 포함할 수 있습니다.

## B. 아키텍처 뷰에 대한 정보 세부사항
섹션 V.B.2에 설명된 각 뷰에 대해, 제조업체는 의도된 사용과 관계없이 의료기기 시스템의 모든 통신에 대한 엔드투엔드 보안 분석을 포함하는 시스템 수준 설명 및 분석을 제공해야 합니다. 여기에는 아래에 설명된 대로 모든 통신 경로에 대한 상세한 다이어그램 및 추적이 포함되어야 합니다. 보안 관련 분석은 의료기기 시스템의 두 자산 간에 데이터, 코드 및 명령이 어떻게 보호되는지 설명하는 중요한 통신 경로에 대한 상세한 추적을 구성하고 따를 수 있는 능력이 필요합니다. 이 분석은 또한 각 기기에 대한 SBOM에 포함되어야 하는 소프트웨어를 식별하는 데 도움이 될 수 있습니다.

FDA는 보안 아키텍처 뷰가 포함을 위해 다음 정보 예를 고려할 것을 권장합니다:

- 다음을 포함하되 이에 국한되지 않는 모든 의료기기 시스템 자산을 식별하는 상세한 다이어그램 및 지원 설명 텍스트:
  - 기기 하드웨어 자체(모든 상용 플랫폼에 대한 평가 포함);
  - 구성, 설치/업그레이드 및 데이터 전송 애플리케이션과 같이 대상 기기와 직접 상호 작용하는 애플리케이션, 하드웨어 및/또는 기타 지원 자산;
  - 의료 시설이 운영하는 자산;
  - 통신/네트워킹 자산; 그리고
  - 기기 데이터를 수집하고 재배포하는 서버 또는 펌웨어 업데이트 서버와 같이 외부 엔티티와 상호 작용하는 모든 서버를 포함한 제조업체가 통제하는 자산.
- 중간 자산(예: 앱)이 하나 이상 있는 경우 간접 연결을 포함하여 보안 사용 사례 뷰(및/또는 설명 텍스트)의 두 자산 간에 존재하는 모든 통신 경로에 대해 다음 세부사항이 제공되어야 합니다:
  - 중개자를 통한 두 자산 간의 통신 경로 및 사용되지 않는 인터페이스를 포함한 통신 인터페이스 및 경로 목록;
  - 경로가 데이터, 코드 및/또는 명령에 사용되는지 여부 및 전송되는 데이터/정보/코드의 유형에 대한 표시;
  - 프로토콜 이름, 버전 번호 및 포트/채널/주파수;
  - 현재 사용되거나 활성화되지 않은 내장 기능(예: 휴면 애플리케이션 기능 또는 포트)에 대한 평가를 포함하여 각 의료기기 시스템 자산에 대한 기본 및 모든 사용 가능한 기능에 대한 상세한 설명, 이 기능이 활성화 및/또는 오용될 수 없다는 보증 포함;
  - 모든 자산에 대한 접근 통제 모델 또는 기능(있는 경우)(예: 권한, 사용자 계정/그룹, 비밀번호);
  - 자산 및 통신 채널과 상호 작용하는 경우 사용자의 역할 및 책임 수준;
  - 한 통신 경로에서 다른 통신 경로로의 "핸드오프" 시퀀스(예: 자산에서 자산으로, 네트워크에서 네트워크로 또는 블루투스에서 Wi-Fi로), 그리고 핸드오프 중 데이터, 코드 및/또는 명령이 어떻게 보안/보호되는지(즉, 무결성/진위성이 어떻게 보장되는지);
  - 비정상적/오류/예상치 못한 상황에서의 의도된 동작에 대한 설명(예: 데이터 전송 중간에 연결 종료);
  - 인증 메커니즘(있는 경우), 알고리즘 이름/버전(사용 가능한 경우), "강도" 지표(예: 키 비트 길이, 계산 라운드 수) 및 작동 모드(해당되는 경우) 포함;
  - 의료기기 시스템 전반에 걸쳐 사용되는 암호화 방법 및 암호화 키 사용의 유형과 수준 및 사용 스타일에 대한 설명(예: 일회용 사용, 키 길이, 사용된 표준, 대칭 또는 기타). 설명에는 펌웨어 및 소프트웨어 업데이트에 대한 암호화 보호의 세부사항도 포함되어야 합니다;
  - 암호화 알고리즘이 독점적이거나 표준 알고리즘의 독점적 수정인 경우 암호화 전문가의 상세한 분석;
  - 생성된 각 인증자에 대해 확인되는 위치 목록 및 확인 자격 증명(예: 인증서, 비대칭 키 또는 공유 키)이 양쪽 엔드포인트에 배포되는 방법;
  - 제조업체 및 의료 시설이 통제하는 자산을 포함하여 각 유형의 자격 증명(예: 비밀번호, 키)이 어떻게 생성, 저장, 구성, 전송 및 유지되는지에 대한 정확하고 상세한 목록(예: 키 관리 및 공개 키 인프라(PKI));
  - 신원 관리[^86](있는 경우), 신원이 어떻게 관리/전송되고 구성되는지 포함(예: 제조업체에서 프로그래머로, 프로그래머에서 기기로);
  - 통신 세션이 사용되거나 지원되는 경우, 세션 식별자의 고유성, 예측 불가능성, 타임스탬핑 및 검증과 같은 보안 속성의 보증을 포함하되 이에 국한되지 않는 세션이 어떻게 설정, 유지 및 종료되는지에 대한 상세한 설명;
  - 모든 보안 구성 설정 및 기본값 포함;
  - 다이어그램 요소(또는 설명 텍스트), 관련 위험 및 통제, 그리고 테스트 간의 정확한 링크;
  - 보안 주장 및 모든 가정을 정당화하는 데 사용될 수 있는 증거에 대한 설명 또는 링크; 그리고
  - 적절한 경우 독점 및 타사 코드에 대해 위의 섹션 V.B.2에 설명된 SBOM 구성요소에 대한 자산의 추적 가능성.

# Appendix 3. Submission Documentation for Investigational Device Exemptions
FDA understands the need to balance innovation and security in designs especially during clinical trials. In order to ensure security is addressed early in the device design, FDA has identified a subset of the documentation recommended throughout this guidance to submit with IDE applications.

Under 21 CFR 812.25, manufacturers must provide an investigational plan as a part of their IDE application. For investigational devices within the scope of this guidance, FDA recommends that this investigational plan include information on the cybersecurity of the subject device. Specifically, FDA recommends the following documentation be included as part of IDE applications:

- Inclusion of cybersecurity risks as part of informed consent form (21 CFR 50.25(a)(2) and 21 CFR 812.25(g));
- Global, multi-patient and updateability/patchability views (21 CFR 812.25(c), (d));
- Security use case views for functionality with safety risks (e.g., implant programming) (21 CFR 812.25(c), (d));
- Software Bill of Materials (21 CFR 812.25(c), (d)); and
- General labeling – connectivity and associated general cybersecurity risks, updateability/process (21 CFR 812.25(f)).

FDA intends to review this information in the context of the overall benefit-risk assessment of investigational devices as outlined in FDA's guidance "Factors to Consider When Making Benefit-Risk Determinations for Medical Device Investigational Device Exemptions." Therefore, approval of an IDE based on the documentation recommended above does not preclude the possibility of future cybersecurity questions or concerns being raised during review of a subsequent marketing application. This is, in part, due to the understanding that design changes may be needed and the temporal nature of cybersecurity. Cybersecurity improvements will likely be needed between the time of clinical trials and when the device is submitted for marketing authorization (e.g., operating system no longer supported or nearing end of support, third-party software updates).

# 부록 3. 임상시험용 기기 면제에 대한 제출 문서
FDA는 특히 임상 시험 중에 설계에서 혁신과 보안의 균형을 맞출 필요성을 이해합니다. 기기 설계 초기에 보안이 다루어지도록 보장하기 위해, FDA는 IDE 신청서와 함께 제출할 본 가이던스 전반에 걸쳐 권장되는 문서의 하위 집합을 식별했습니다.

21 CFR 812.25에 따라, 제조업체는 IDE 신청서의 일부로 임상시험 계획을 제공해야 합니다. 본 가이던스의 범위 내에 있는 임상시험용 기기의 경우, FDA는 이 임상시험 계획이 대상 기기의 사이버보안에 관한 정보를 포함할 것을 권장합니다. 구체적으로, FDA는 다음 문서가 IDE 신청서의 일부로 포함될 것을 권장합니다:

- 사전 동의서의 일부로 사이버보안 위험 포함 (21 CFR 50.25(a)(2) 및 21 CFR 812.25(g));
- 글로벌, 다중 환자 및 업데이트 가능성/패치 가능성 뷰 (21 CFR 812.25(c), (d));
- 안전 위험이 있는 기능(예: 임플란트 프로그래밍)에 대한 보안 사용 사례 뷰 (21 CFR 812.25(c), (d));
- 소프트웨어 구성 요소 목록 (21 CFR 812.25(c), (d)); 그리고
- 일반 라벨링 – 연결성 및 관련 일반 사이버보안 위험, 업데이트 가능성/프로세스 (21 CFR 812.25(f)).

FDA는 FDA의 가이던스 "의료기기 임상시험용 기기 면제에 대한 이익-위험 결정을 내릴 때 고려해야 할 요소"에 설명된 대로 임상시험용 기기의 전반적인 이익-위험 평가의 맥락에서 이 정보를 검토할 의도입니다. 따라서 위에서 권장된 문서를 기반으로 한 IDE 승인이 후속 마케팅 신청 검토 중에 향후 사이버보안 질문 또는 우려가 제기될 가능성을 배제하지는 않습니다. 이는 부분적으로 설계 변경이 필요할 수 있으며 사이버보안의 시간적 특성에 대한 이해 때문입니다. 임상 시험 시점과 기기가 마케팅 승인을 위해 제출될 때 사이에 사이버보안 개선이 필요할 가능성이 높습니다(예: 운영 체제가 더 이상 지원되지 않거나 지원 종료가 임박함, 타사 소프트웨어 업데이트).

# Appendix 4. General Premarket Submission Documentation Elements and Scaling with Risk
As stated in Section IV.D and throughout the guidance, device cybersecurity design and documentation are expected to scale with the cybersecurity risk of that device. While documentation breadth is expected to scale, each type of documentation identified throughout the guidance is recommended for all premarket submissions for devices with potential cybersecurity risks. As mentioned previously, the submission documentation recommendations in this guidance are intended to help manufacturers meet their obligations for cyber devices under section 524B of the FD&C Act.

Table 1 below summarizes the specific documentation elements identified throughout the guidance for premarket submissions, the associated sections of the guidance for the document, and whether the documentation is recommended for IDE submissions. While documentation elements are identified for the security risk management report, manufacturers can provide the documentation elements in a way that is consistent with their existing documentation processes. This table is not intended to serve as merely a deliverable checklist, as the processes outlined throughout the guidance are intended to help align generation of these documents and their resultant content with FDA's recommendations. This table represents one possible way to organize the recommended information.

The below documentation will naturally scale with the level of cybersecurity risk. This will be most evident in the breadth of the Threat Modeling and Architecture Views documentation.

- For example, a device with either only one hardware connection (e.g., USB port) or a SaMD product with limited other software dependencies and connectivity will likely only need to have single architecture view for each of the global system, multi-patient harm, and updateability/patchability views; the security use case view(s) will likely be limited to a smaller subset of unique views to address the available connectivity and software.
- For a device with greater complexities such as, but not limited to, networking, wireless connections, cloud, and/or commercial operating systems, multiple architecture views may be needed for the multi-patient harm and updateability/patchability views as there may be multiple ways to cause multi-patient harm or update elements of the device. Additionally, many security use case views will likely be needed to convey the various unique security and clinical use cases throughout the architecture.

**Table 1. Recommended Premarket Submission Documentation**

| Type of Premarket Submission Documentation | Guidance Section(s) | IDE Submission* |
|-------------------------------------------|---------------------|-----------------|
| Cybersecurity Risk Management Report | Sections V, VI.B | Could be helpful to submit, but not specifically recommended |
| - Threat Model (may include Architecture Views) | Sections V.A.1, V.A.3, V.A.4, V.A.5, V.B.2, Appendix 1, Appendix 2 | Could be helpful to submit, but not specifically recommended (see Architecture View recommendations) |
| - Cybersecurity Risk Assessment | Sections V.A.2, V.A.3, V.A.4, V.A.5, V.A.6 | Could be helpful to submit, but not specifically recommended |
| - SBOM | Sections V.A.4, VI.A | Recommended |
| - Vulnerability Assessment and Software Support | Section V.A.4 | Could be helpful to submit, but not specifically recommended |
| - Unresolved Anomalies Assessment | Section V.A.5 | Could be helpful to submit, but not specifically recommended |
| - Traceability | Sections V.A, V.A.1, V.A.2, V.A.3, V.A.4, V.A.5, V.A.6, V.B.1, V.B.2, V.C, VI.A | Could be helpful to submit, but not specifically recommended |
| Measures and Metrics | Section V.A.6 | Could be helpful to submit, but not specifically recommended |
| Architecture Views | Section V.B | Recommended<br>• Global, Multi-patient and Updateability/Patchability views<br>• Security Use Case views for functionality with safety risks |
| - Requirements | Sections V.B.1, Appendix 1 | Recommended<br>• Global, Multi-patient and Updateability/Patchability views<br>• Security Use Case views for functionality with safety risks |
| - Architecture Views (may be included in Threat Model) | Sections V.A.1, V.B.2, Appendix 1, Appendix 2 | Recommended<br>• Global, Multi-patient and Updateability/Patchability views<br>• Security Use Case views for functionality with safety risks |
| Testing | Section V.C | Could be helpful to submit, but not specifically recommended |
| Labeling | Section VI.A | Recommended<br>• Informed Consent Form to include cybersecurity risks<br>• General Cybersecurity Labeling - Connectivity and associated general cybersecurity risks, updateability/process |
| Cybersecurity Management Plans | Section VI.B | Could be helpful to submit, but not specifically recommended |

*For the purposes of this table, "recommended" refers to the elements of an IDE submission FDA discusses in Appendix 3 of this document; "could be helpful to submit, but not specifically recommended" refers to additional elements that could be helpful to FDA if submitted, but are not specifically recommended in Appendix 3. If a device-specific guidance contains additional or different recommendations to those in this table, the device-specific recommendations should be followed. If a manufacturer is unsure, they should utilize the FDA Q-submission process.

# 부록 4. 일반 시판 전 제출 문서 요소 및 위험에 따른 확장
섹션 IV.D 및 가이던스 전반에 걸쳐 언급된 바와 같이, 기기 사이버보안 설계 및 문서는 해당 기기의 사이버보안 위험에 따라 확장될 것으로 예상됩니다. 문서 폭이 확장될 것으로 예상되지만, 가이던스 전반에 걸쳐 식별된 각 유형의 문서는 잠재적인 사이버보안 위험이 있는 기기에 대한 모든 시판 전 제출에 권장됩니다. 앞서 언급한 바와 같이, 본 가이던스의 제출 문서 권장사항은 제조업체가 FD&C법 524B조에 따른 사이버 기기에 대한 의무를 충족하는 데 도움을 주기 위한 것입니다.

아래 표 1은 시판 전 제출을 위해 가이던스 전반에 걸쳐 식별된 특정 문서 요소, 문서에 대한 가이던스의 관련 섹션, 그리고 문서가 IDE 제출에 권장되는지 여부를 요약합니다. 보안 위험 관리 보고서에 대한 문서 요소가 식별되지만, 제조업체는 기존 문서화 프로세스와 일치하는 방식으로 문서 요소를 제공할 수 있습니다. 이 표는 단순히 제공물 체크리스트 역할을 하기 위한 것이 아니며, 가이던스 전반에 걸쳐 설명된 프로세스는 이러한 문서의 생성과 그 결과 내용을 FDA의 권장사항과 일치시키는 데 도움을 주기 위한 것입니다. 이 표는 권장 정보를 구성하는 한 가지 가능한 방법을 나타냅니다.

아래 문서는 사이버보안 위험 수준에 따라 자연스럽게 확장될 것입니다. 이는 위협 모델링 및 아키텍처 뷰 문서의 폭에서 가장 명백할 것입니다.

- 예를 들어, 하나의 하드웨어 연결(예: USB 포트)만 있는 기기 또는 제한된 다른 소프트웨어 종속성 및 연결성을 가진 SaMD 제품은 글로벌 시스템, 다중 환자 피해 및 업데이트 가능성/패치 가능성 뷰 각각에 대해 단일 아키텍처 뷰만 필요할 가능성이 높습니다; 보안 사용 사례 뷰는 사용 가능한 연결성 및 소프트웨어를 다루기 위한 고유 뷰의 더 작은 하위 집합으로 제한될 가능성이 높습니다.
- 네트워킹, 무선 연결, 클라우드 및/또는 상용 운영 체제와 같이 더 큰 복잡성을 가진 기기의 경우, 다중 환자 피해를 일으키거나 기기의 요소를 업데이트하는 여러 방법이 있을 수 있으므로 다중 환자 피해 및 업데이트 가능성/패치 가능성 뷰에 대해 여러 아키텍처 뷰가 필요할 수 있습니다. 또한, 아키텍처 전반에 걸쳐 다양한 고유 보안 및 임상 사용 사례를 전달하기 위해 많은 보안 사용 사례 뷰가 필요할 가능성이 높습니다.

**표 1. 권장 시판 전 제출 문서**

| 시판 전 제출 문서 유형 | 가이던스 섹션 | IDE 제출* |
|-------------------------------------------|---------------------|-----------------|
| 사이버보안 위험 관리 보고서 | 섹션 V, VI.B | 제출하는 것이 도움이 될 수 있지만 구체적으로 권장되지는 않음 |
| - 위협 모델 (아키텍처 뷰 포함 가능) | 섹션 V.A.1, V.A.3, V.A.4, V.A.5, V.B.2, 부록 1, 부록 2 | 제출하는 것이 도움이 될 수 있지만 구체적으로 권장되지는 않음 (아키텍처 뷰 권장사항 참조) |
| - 사이버보안 위험 평가 | 섹션 V.A.2, V.A.3, V.A.4, V.A.5, V.A.6 | 제출하는 것이 도움이 될 수 있지만 구체적으로 권장되지는 않음 |
| - SBOM | 섹션 V.A.4, VI.A | 권장됨 |
| - 취약점 평가 및 소프트웨어 지원 | 섹션 V.A.4 | 제출하는 것이 도움이 될 수 있지만 구체적으로 권장되지는 않음 |
| - 미해결 이상 평가 | 섹션 V.A.5 | 제출하는 것이 도움이 될 수 있지만 구체적으로 권장되지는 않음 |
| - 추적 가능성 | 섹션 V.A, V.A.1, V.A.2, V.A.3, V.A.4, V.A.5, V.A.6, V.B.1, V.B.2, V.C, VI.A | 제출하는 것이 도움이 될 수 있지만 구체적으로 권장되지는 않음 |
| 측정 및 메트릭 | 섹션 V.A.6 | 제출하는 것이 도움이 될 수 있지만 구체적으로 권장되지는 않음 |
| 아키텍처 뷰 | 섹션 V.B | 권장됨<br>• 글로벌, 다중 환자 및 업데이트 가능성/패치 가능성 뷰<br>• 안전 위험이 있는 기능에 대한 보안 사용 사례 뷰 |
| - 요구사항 | 섹션 V.B.1, 부록 1 | 권장됨<br>• 글로벌, 다중 환자 및 업데이트 가능성/패치 가능성 뷰<br>• 안전 위험이 있는 기능에 대한 보안 사용 사례 뷰 |
| - 아키텍처 뷰 (위협 모델에 포함 가능) | 섹션 V.A.1, V.B.2, 부록 1, 부록 2 | 권장됨<br>• 글로벌, 다중 환자 및 업데이트 가능성/패치 가능성 뷰<br>• 안전 위험이 있는 기능에 대한 보안 사용 사례 뷰 |
| 테스트 | 섹션 V.C | 제출하는 것이 도움이 될 수 있지만 구체적으로 권장되지는 않음 |
| 라벨링 | 섹션 VI.A | 권장됨<br>• 사이버보안 위험을 포함한 사전 동의서<br>• 일반 사이버보안 라벨링 - 연결성 및 관련 일반 사이버보안 위험, 업데이트 가능성/프로세스 |
| 사이버보안 관리 계획 | 섹션 VI.B | 제출하는 것이 도움이 될 수 있지만 구체적으로 권장되지는 않음 |

*이 표의 목적상, "권장됨"은 본 문서의 부록 3에서 FDA가 논의하는 IDE 제출의 요소를 의미합니다; "제출하는 것이 도움이 될 수 있지만 구체적으로 권장되지는 않음"은 제출될 경우 FDA에 도움이 될 수 있지만 부록 3에서 구체적으로 권장되지 않는 추가 요소를 의미합니다. 기기별 가이던스가 이 표의 권장사항과 추가적이거나 다른 권장사항을 포함하는 경우, 기기별 권장사항을 따라야 합니다. 제조업체가 확실하지 않은 경우 FDA Q-제출 프로세스를 활용해야 합니다.

# Appendix 5. Terminology
The terminology listed here are for the purposes of this guidance and are intended for use in the context of assessing medical device cybersecurity. These terms are not intended to be applied in any context beyond this guidance.

**Anomaly** – any condition that deviates from the expected behavior based on user needs, requirements, specifications, design documents, or standards.

**Asset** – anything that has value to an individual or an organization.[^87]

**Attack Surface Analysis** – evaluation of attack surface to determine all avenues of ingress and egress to and from a system including common vulnerabilities and exposed ports and services.[^88]

**Authentication** – the act of verifying the identity of a user, process, or device as a prerequisite to allowing access to the device, its data, information, or systems, or provision of assurance that a claimed characteristic of an entity is correct.[^89]

**Authenticity** – information, hardware, or software having the property of being genuine and being able to be verified and trusted; confidence that the contents of a message originate from the expected party and has not been modified during transmission or storage.[^90]

**Authorization** – the right or a permission that is granted to a system entity to access a system resource.[^91]

**Availability** – the property of data, information, and information systems to be accessible and usable on a timely basis in the expected manner (i.e., the assurance that information will be available when needed).[^92]

**Boundary Analysis** – the process of uniquely assigning information resources to an information system, which defines the security boundary for that system.[^93]

**Closed Box Testing** – a method of software testing that examines the functionality of an application without peering into its internal structures of workings.[^94]

**Compensating Controls** – a safeguard or countermeasure deployed, in lieu of, or in the absence of controls designed in by a device manufacturer. These controls are external to the device design, configurable in the field, employed by a user, and provide supplementary or comparable cyber protection for a medical device.[^95]

**Confidentiality** – the property of data, information, or system structures to be accessible only to authorized persons and entities and are processed at authorized times and in the authorized manner, thereby helping ensure data and system security. Confidentiality provides the assurance that no unauthorized users (i.e., only trusted users) have access to the data, information, or system structures.[^96]

**Configuration** – the possible conditions, parameters, and specifications with which a device or system component can be described or arranged.[^97]

**Configuration Management** – a collection of activities focused on establishing and maintaining the integrity of information technology products and information systems, through control of processes for initializing, changing, and monitoring the configurations of those products and systems throughout the system development lifecycle.[^98]

**Controlled Risk** – when there is sufficiently low (acceptable) residual risk of patient harm due to a device's particular cybersecurity vulnerability.

**Cryptography** – the discipline that embodies the principles, means, and methods for providing information security; including confidentiality, data integrity, non-repudiation, and authenticity.[^99]

**Cybersecurity** – the process of preventing unauthorized access, modification, misuse or denial of use, or the unauthorized use of information that is stored, accessed, or transferred from a medical device to an external recipient.[^100]

**Decommission** – a process in the disposition process that includes proper identification, authorization for disposition, and sanitization of the equipment, as well as removal of Patient Health Information (PHI) or software, or both.[^101]

**Disposal** – a process to end the existence of a system asset or system for a specified intended use, appropriately handle replaced or retired assets, and to properly attend to identified critical disposal needs (e.g., per an agreement, per organizational policy, or for environmental, legal, safety, or security aspects).[^102]

**Encryption** – is the cryptographic transformation of data (called "plaintext") into a form (called "ciphertext") that conceals the data's original meaning to prevent it from being known or used.[^103]

**End of support** – a point beyond which the product manufacturer ceases to provide support, which may include cybersecurity support, for a product or service.

**Exploitability** – the feasibility or ease and technical means by which the vulnerability can be exploited by a threat.[^104]

**Firmware** – software program or set of instructions programmed on the flash read-only memory (ROM) of a hardware device. It provides the necessary instructions for how the device communicates with the other computer hardware.[^105]

**Fuzz Testing** – process of creating malformed or unexpected data or call sequences to be consumed by the entity under test to verify that they are handled appropriately.[^106]

**Hardware** – the material physical components of an information system.[^107]

**Integrity** – the property of data, information and software to be accurate and complete and have not been improperly or maliciously modified.[^108]

**Lifecycle** – all phases in the life of a medical device, from initial conception to final decommissioning and disposal.[^109]

**Malware** – software or firmware intended to perform an unauthorized process that will have adverse impact on the confidentiality, integrity, or availability of an information system.[^110]

**Patch** – a "repair job" for a piece of programming; also known as a "fix". A patch is the immediate solution to an identified problem that is provided to users. The patch is not necessarily the best solution for the problem, and the product developers often find a better solution to provide when they package the product for its next release. A patch is usually developed and distributed as a replacement for or an insertion in compiled code (that is, in a binary file or object module). In many operating systems, a special program is provided to manage and track the installation of patches.[^111]

**Patient harm** – injury or damage to the health of patients, including death.[^112]

**Programmable logic** – hardware that has undefined function at the time of manufacture and must be programmed with software to function (e.g., Field-programmable gate array).

**Reasonably foreseeable misuse** – use of a product or system in a way not intended by the manufacturer, but which can result from readily predictable human behavior.[^113]

**Resilience** – the ability of an information system to continue to: (i) operate under adverse conditions or stress, even if in a degraded or debilitated state, while maintaining essential operational capabilities; and (ii) recover to an effective operational posture in a time frame consistent with mission needs.[^114]

**Secure Product Development Framework (SPDF)** – a set of processes that reduce the number and severity of vulnerabilities in products. Additional information about an SPDF and its implementation is discussed in Sections IV and V, and throughout the guidance.[^115]

**Security Architecture** – a set of physical and logical security-relevant representations (i.e., views) of system architecture that conveys information about how the system is partitioned into security domains and makes use of security-relevant elements to enforce security policies within and between security domains based on how data and information must be protected. The security architecture reflects security domains, the placement of security-relevant elements within the security domains, the interconnections and trust relationships between the security-relevant elements, and the behavior and interactions between the security-relevant elements.[^116]

**Security Strength** – a measure of the computational complexity associated with recovering certain secret and/or security-critical information concerning a given cryptographic algorithm from known data (e.g., plaintext/ciphertext pairs for a given encryption algorithm).[^117] Throughout this guidance "strong" and other iterations of this term may be used that apply to this definition.

**Security Risk Management** – a process (or processes) that evaluates and controls threat-based risks. For security risk management, this includes an evaluation of the impact of exploitation on the device's safety and effectiveness, the exploitability, and the severity of patient harm if exploited.

**Software Bill of Materials (SBOM)** – a formal inventory of software components and dependencies, information about those components, and their hierarchical relationships.[^118] The software components in an SBOM include, but are not limited to, commercial, open source, off-the-shelf, and custom software components. See Section V.A.4 for a more complete description of an SBOM.

**System** – the combination of interacting elements or assets organized to achieve one or more function.[^119]

**Threat** – Threat is any circumstance or event with the potential to adversely impact the device, organizational operations (including mission, functions, image, or reputation), organizational assets, individuals, or other organizations through an information system via unauthorized access, destruction, disclosure, modification of information, and/or denial of service. Threats exercise vulnerabilities, which may impact the safety or effectiveness of the device.[^120]

**Threat modeling** – a methodology for optimizing system, product, network, application, and connection security by identifying objectives and vulnerabilities, and then defining countermeasures to prevent, or mitigate the effects of, threats to the system.[^121]

**Trustworthy Device** – a medical device that: (1) is reasonably secure from cybersecurity intrusion and misuse; (2) provides a reasonable level of availability and reliability; (3) is reasonably suited to performing its intended functions; and (4) adheres to generally accepted security procedures to support correct operation.[^122]

**Uncontrolled risk** – when there is unacceptable residual risk of patient harm due to inadequate compensating controls and risk mitigations.

**Unresolved anomaly** – a defect that still resides in the software because a sponsor deemed it appropriate not to correct or fix the anomaly, according to a risk-based rationale about its impact to the device's safety and effectiveness.[^123]

**Updatability and Patchability** – the ease and timeliness with which a device and related assets can be changed for any reason (e.g., feature update, security patch, hardware replacement).

**Update** – corrective, preventative, adaptive, or perfective modifications made to software of a medical device.[^124]

**Vulnerability** – a weakness in an information system, system security procedure(s), internal control(s), human behavior, or implementation that could be exploited.

**Vulnerability Chaining** – the sequential exploit of multiple vulnerabilities in order to attack to attack a system, where one or more exploits at the end of the chain require the successful completion of prior exploits in order to be exploited.[^125]

# 부록 5. 용어
여기에 나열된 용어는 본 가이던스의 목적을 위한 것이며 의료기기 사이버보안 평가의 맥락에서 사용하기 위한 것입니다. 이러한 용어는 본 가이던스를 넘어서는 어떤 맥락에서도 적용되도록 의도되지 않았습니다.

**이상(Anomaly)** – 사용자 요구, 요구사항, 사양, 설계 문서 또는 표준을 기반으로 예상되는 동작에서 벗어나는 모든 조건.

**자산(Asset)** – 개인 또는 조직에 가치가 있는 모든 것.[^87]

**공격 표면 분석(Attack Surface Analysis)** – 일반적인 취약점과 노출된 포트 및 서비스를 포함하여 시스템으로의 모든 진입 및 이탈 경로를 결정하기 위한 공격 표면 평가.[^88]

**인증(Authentication)** – 기기, 데이터, 정보 또는 시스템에 대한 접근을 허용하기 위한 전제 조건으로 사용자, 프로세스 또는 기기의 신원을 확인하는 행위, 또는 엔티티의 주장된 특성이 올바르다는 보증 제공.[^89]

**진위성(Authenticity)** – 진정하고 검증되고 신뢰될 수 있는 속성을 가진 정보, 하드웨어 또는 소프트웨어; 메시지의 내용이 예상된 당사자로부터 유래했으며 전송 또는 저장 중에 수정되지 않았다는 확신.[^90]

**권한 부여(Authorization)** – 시스템 리소스에 접근하기 위해 시스템 엔티티에 부여되는 권리 또는 허가.[^91]

**가용성(Availability)** – 예상되는 방식으로 시기적절하게 데이터, 정보 및 정보 시스템에 접근하고 사용할 수 있는 속성(즉, 필요할 때 정보를 이용할 수 있다는 보증).[^92]

**경계 분석(Boundary Analysis)** – 정보 리소스를 정보 시스템에 고유하게 할당하는 프로세스로, 해당 시스템의 보안 경계를 정의함.[^93]

**블랙박스 테스트(Closed Box Testing)** – 내부 구조나 작동을 들여다보지 않고 애플리케이션의 기능을 검사하는 소프트웨어 테스트 방법.[^94]

**보상 통제(Compensating Controls)** – 기기 제조업체가 설계한 통제 대신 또는 부재 시 배치되는 안전 장치 또는 대응책. 이러한 통제는 기기 설계 외부에 있고, 현장에서 구성 가능하며, 사용자에 의해 사용되며, 의료기기에 대한 보완적이거나 비교 가능한 사이버 보호를 제공함.[^95]

**기밀성(Confidentiality)** – 승인된 사람 및 엔티티만 접근할 수 있고 승인된 시간에 승인된 방식으로 처리되는 데이터, 정보 또는 시스템 구조의 속성으로, 데이터 및 시스템 보안을 보장하는 데 도움을 줌. 기밀성은 무단 사용자(즉, 신뢰할 수 있는 사용자만)가 데이터, 정보 또는 시스템 구조에 접근할 수 없다는 보증을 제공함.[^96]

**구성(Configuration)** – 기기 또는 시스템 구성요소를 설명하거나 배열할 수 있는 가능한 조건, 매개변수 및 사양.[^97]

**구성 관리(Configuration Management)** – 시스템 개발 수명주기 전반에 걸쳐 해당 제품 및 시스템의 구성을 초기화, 변경 및 모니터링하기 위한 프로세스를 통제함으로써 정보 기술 제품 및 정보 시스템의 무결성을 수립하고 유지하는 데 초점을 맞춘 활동 모음.[^98]

**통제된 위험(Controlled Risk)** – 기기의 특정 사이버보안 취약점으로 인한 환자 피해의 잔여 위험이 충분히 낮은(허용 가능한) 경우.

**암호화(Cryptography)** – 기밀성, 데이터 무결성, 부인 방지 및 진위성을 포함한 정보 보안을 제공하기 위한 원칙, 수단 및 방법을 구현하는 학문.[^99]

**사이버보안(Cybersecurity)** – 의료기기에서 외부 수신자로 저장, 접근 또는 전송되는 정보에 대한 무단 접근, 수정, 오용 또는 사용 거부, 또는 무단 사용을 방지하는 프로세스.[^100]

**폐기(Decommission)** – 적절한 식별, 처분 승인, 장비의 정화뿐만 아니라 환자 건강 정보(PHI) 또는 소프트웨어 또는 둘 다의 제거를 포함하는 처분 프로세스의 프로세스.[^101]

**처리(Disposal)** – 지정된 의도된 사용을 위한 시스템 자산 또는 시스템의 존재를 종료하고, 교체되거나 폐기된 자산을 적절하게 처리하며, 식별된 중요한 처리 요구(예: 계약에 따라, 조직 정책에 따라, 또는 환경, 법률, 안전 또는 보안 측면에 대해)를 적절하게 처리하는 프로세스.[^102]

**암호화(Encryption)** – 데이터("평문"이라고 함)를 원래 의미를 숨기는 형태("암호문"이라고 함)로 암호화 변환하여 알려지거나 사용되는 것을 방지하는 것.[^103]

**지원 종료(End of support)** – 제품 제조업체가 제품 또는 서비스에 대한 사이버보안 지원을 포함할 수 있는 지원을 중단하는 시점.

**악용 가능성(Exploitability)** – 취약점이 위협에 의해 악용될 수 있는 실행 가능성 또는 용이성 및 기술적 수단.[^104]

**펌웨어(Firmware)** – 하드웨어 기기의 플래시 읽기 전용 메모리(ROM)에 프로그래밍된 소프트웨어 프로그램 또는 명령 세트. 기기가 다른 컴퓨터 하드웨어와 통신하는 방법에 대한 필요한 명령을 제공함.[^105]

**퍼즈 테스트(Fuzz Testing)** – 테스트 대상 엔티티가 소비할 잘못된 형식이거나 예상치 못한 데이터 또는 호출 시퀀스를 생성하여 적절하게 처리되는지 확인하는 프로세스.[^106]

**하드웨어(Hardware)** – 정보 시스템의 물질적 물리적 구성요소.[^107]

**무결성(Integrity)** – 데이터, 정보 및 소프트웨어가 정확하고 완전하며 부적절하게 또는 악의적으로 수정되지 않은 속성.[^108]

**수명주기(Lifecycle)** – 초기 개념부터 최종 폐기 및 처리까지 의료기기 수명의 모든 단계.[^109]

**악성 소프트웨어(Malware)** – 정보 시스템의 기밀성, 무결성 또는 가용성에 부정적인 영향을 미칠 무단 프로세스를 수행하기 위한 소프트웨어 또는 펌웨어.[^110]

**패치(Patch)** – 프로그래밍의 "수리 작업"; "수정"이라고도 함. 패치는 사용자에게 제공되는 식별된 문제에 대한 즉각적인 솔루션. 패치가 반드시 문제에 대한 최선의 솔루션은 아니며, 제품 개발자는 다음 릴리스를 위해 제품을 패키징할 때 종종 더 나은 솔루션을 찾음. 패치는 일반적으로 컴파일된 코드(즉, 바이너리 파일 또는 객체 모듈)에서 교체 또는 삽입으로 개발 및 배포됨. 많은 운영 체제에서 패치 설치를 관리하고 추적하기 위한 특수 프로그램이 제공됨.[^111]

**환자 피해(Patient harm)** – 사망을 포함한 환자의 건강에 대한 상해 또는 손상.[^112]

**프로그래밍 가능한 로직(Programmable logic)** – 제조 시점에 정의되지 않은 기능을 가지며 기능하기 위해 소프트웨어로 프로그래밍되어야 하는 하드웨어(예: 필드 프로그래밍 가능한 게이트 어레이).

**합리적으로 예견 가능한 오용(Reasonably foreseeable misuse)** – 제조업체가 의도하지 않았지만 쉽게 예측 가능한 인간 행동으로 인해 발생할 수 있는 제품 또는 시스템의 사용.[^113]

**복원력(Resilience)** – 정보 시스템이 계속해서 (i) 필수 운영 능력을 유지하면서 저하되거나 약화된 상태에서도 불리한 조건이나 스트레스 하에서 작동하고; (ii) 임무 요구와 일치하는 시간 프레임 내에 효과적인 운영 태세로 복구할 수 있는 능력.[^114]

**보안 제품 개발 프레임워크(SPDF)** – 제품의 취약점 수와 심각도를 줄이는 프로세스 세트. SPDF 및 그 구현에 대한 추가 정보는 섹션 IV 및 V와 가이던스 전반에 걸쳐 논의됨.[^115]

**보안 아키텍처(Security Architecture)** – 시스템이 보안 도메인으로 분할되는 방법을 전달하고 데이터 및 정보를 보호해야 하는 방법에 따라 보안 도메인 내 및 보안 도메인 간에 보안 정책을 시행하기 위해 보안 관련 요소를 사용하는 시스템 아키텍처의 물리적 및 논리적 보안 관련 표현(즉, 뷰) 세트. 보안 아키텍처는 보안 도메인, 보안 도메인 내 보안 관련 요소의 배치, 보안 관련 요소 간의 상호 연결 및 신뢰 관계, 보안 관련 요소 간의 동작 및 상호 작용을 반영함.[^116]

**보안 강도(Security Strength)** – 알려진 데이터(예: 주어진 암호화 알고리즘에 대한 평문/암호문 쌍)로부터 주어진 암호화 알고리즘에 관한 특정 비밀 및/또는 보안에 중요한 정보를 복구하는 것과 관련된 계산 복잡성의 측정.[^117] 본 가이던스 전반에 걸쳐 이 정의에 적용되는 이 용어의 "강력한" 및 기타 반복이 사용될 수 있음.

**보안 위험 관리(Security Risk Management)** – 위협 기반 위험을 평가하고 통제하는 프로세스. 보안 위험 관리의 경우, 여기에는 악용이 기기의 안전성과 효과성에 미치는 영향, 악용 가능성 및 악용될 경우 환자 피해의 심각성에 대한 평가가 포함됨.

**소프트웨어 구성 요소 목록(SBOM)** – 소프트웨어 구성요소 및 종속성, 해당 구성요소에 대한 정보 및 그들의 계층적 관계에 대한 공식 목록.[^118] SBOM의 소프트웨어 구성요소에는 상용, 오픈 소스, 상용 및 맞춤형 소프트웨어 구성요소가 포함되지만 이에 국한되지 않음. SBOM에 대한 보다 완전한 설명은 섹션 V.A.4를 참조하십시오.

**시스템(System)** – 하나 이상의 기능을 달성하기 위해 조직된 상호 작용하는 요소 또는 자산의 조합.[^119]

**위협(Threat)** – 정보 시스템을 통한 무단 접근, 파괴, 공개, 정보 수정 및/또는 서비스 거부를 통해 기기, 조직 운영(임무, 기능, 이미지 또는 평판 포함), 조직 자산, 개인 또는 기타 조직에 부정적인 영향을 미칠 가능성이 있는 모든 상황 또는 이벤트. 위협은 취약점을 행사하며, 이는 기기의 안전성 또는 효과성에 영향을 미칠 수 있음.[^120]

**위협 모델링(Threat modeling)** – 목표 및 취약점을 식별한 다음 시스템에 대한 위협을 방지하거나 그 영향을 완화하기 위한 대응책을 정의함으로써 시스템, 제품, 네트워크, 애플리케이션 및 연결 보안을 최적화하기 위한 방법론.[^121]

**신뢰할 수 있는 기기(Trustworthy Device)** – (1) 사이버보안 침입 및 오용으로부터 합리적으로 안전하고; (2) 합리적인 수준의 가용성 및 신뢰성을 제공하며; (3) 의도된 기능을 수행하는 데 합리적으로 적합하고; (4) 올바른 작동을 지원하기 위해 일반적으로 인정되는 보안 절차를 준수하는 의료기기.[^122]

**통제되지 않은 위험(Uncontrolled risk)** – 부적절한 보상 통제 및 위험 완화로 인해 환자 피해의 허용 불가능한 잔여 위험이 있는 경우.

**미해결 이상(Unresolved anomaly)** – 스폰서가 기기의 안전성과 효과성에 미치는 영향에 대한 위험 기반 근거에 따라 이상을 수정하거나 고치지 않는 것이 적절하다고 판단했기 때문에 소프트웨어에 여전히 남아 있는 결함.[^123]

**업데이트 가능성 및 패치 가능성(Updatability and Patchability)** – 어떤 이유로든(예: 기능 업데이트, 보안 패치, 하드웨어 교체) 기기 및 관련 자산을 변경할 수 있는 용이성 및 시기적절성.

**업데이트(Update)** – 의료기기의 소프트웨어에 대한 시정적, 예방적, 적응적 또는 완성적 수정.[^124]

**취약점(Vulnerability)** – 정보 시스템, 시스템 보안 절차, 내부 통제, 인간 행동 또는 구현의 약점으로 악용될 수 있음.

**취약점 체이닝(Vulnerability Chaining)** – 시스템을 공격하기 위해 여러 취약점을 순차적으로 악용하는 것으로, 체인의 끝에 있는 하나 이상의 악용이 악용되기 위해 이전 악용의 성공적인 완료를 필요로 함.[^125]

[^87]: Definition is adapted from ISO/IEC 27032 Information technology — Security techniques — Guidelines for cybersecurity, clause 4.6. 정의는 ISO/IEC 27032 정보 기술 — 보안 기법 — 사이버보안 가이드라인, 조항 4.6에서 적용됨.
[^88]: Definition is adapted from ANSI/ISA 62443-1-1:2018. 정의는 ANSI/ISA 62443-1-1:2018에서 적용됨.
[^89]: Definition is adapted from NIST FIPS 200 Minimum Security Requirements for Federal Information and Information Systems (https://doi.org/10.6028/NIST.FIPS.200) and from ISO/IEC 18014-2:2009(E) Information technology – Security techniques - Time-stamping Services - Part 2: Mechanisms producing independent tokens, clause 3. 정의는 NIST FIPS 200 연방 정보 및 정보 시스템에 대한 최소 보안 요구사항 (https://doi.org/10.6028/NIST.FIPS.200) 및 ISO/IEC 18014-2:2009(E) 정보 기술 – 보안 기법 - 타임스탬프 서비스 - 파트 2: 독립적인 토큰을 생성하는 메커니즘, 조항 3에서 적용됨.
[^90]: Definition is adapted from NIST SP 800-53 Security and Privacy Controls for Federal Information Systems and Organizations. https://doi.org/10.6028/NIST.SP.800-53r5 정의는 NIST SP 800-53 연방 정보 시스템 및 조직에 대한 보안 및 개인정보 통제에서 적용됨. https://doi.org/10.6028/NIST.SP.800-53r5
[^91]: Definition is adapted from CNSSI 4009-2015 Committee on National Security Systems (CNSS) Glossary. 정의는 CNSSI 4009-2015 국가 보안 시스템 위원회(CNSS) 용어집에서 적용됨.
[^92]: Definition is adapted from ISO IEC 27000-2018, Clause 3.7 and CNSSI 4009-2015 CNSS Glossary. 정의는 ISO IEC 27000-2018, 조항 3.7 및 CNSSI 4009-2015 CNSS 용어집에서 적용됨.
[^93]: Definition is adapted from NIST Special Publication 800-18 Revision 1 Guide for Developing Security Plans for Federal Information Systems. 정의는 NIST 특별 간행물 800-18 개정 1 연방 정보 시스템에 대한 보안 계획 개발 가이드에서 적용됨.
[^94]: Definition is adapted from CNSSI 4009-2015 CNSS Glossary. 정의는 CNSSI 4009-2015 CNSS 용어집에서 적용됨.
[^95]: Definition is adapted from NIST SP 800-53A Rev. 5 Assessing Security and Privacy Controls in Federal Information Systems and Organizations. https://doi.org/10.6028/NIST.SP.800-53Ar5 정의는 NIST SP 800-53A Rev. 5 연방 정보 시스템 및 조직의 보안 및 개인정보 통제 평가에서 적용됨. https://doi.org/10.6028/NIST.SP.800-53Ar5
[^96]: Definition is adapted from ISO IEC 27000-2018, Clause 3.10: Property that information is not made available or disclosed to unauthorized individuals, entities, or processes. 정의는 ISO IEC 27000-2018, 조항 3.10: 정보가 무단 개인, 엔티티 또는 프로세스에 제공되거나 공개되지 않는 속성에서 적용됨.
[^97]: Definition is adapted from NIST SP 800-128 Guide for Security-Focused Configuration Management of Information Systems. https://doi.org/10.6028/NIST.SP.800-128 정의는 NIST SP 800-128 정보 시스템의 보안 중심 구성 관리 가이드에서 적용됨. https://doi.org/10.6028/NIST.SP.800-128
[^98]: Definition is adapted from NIST SP 800-53 Rev. 5. 정의는 NIST SP 800-53 Rev. 5에서 적용됨.
[^99]: Definition is adapted from CNSSI 4009-2015 CNSS Glossary. 정의는 CNSSI 4009-2015 CNSS 용어집에서 적용됨.
[^100]: Definition is adapted from ISO IEC 27032: 2012, Clause 4.20. 정의는 ISO IEC 27032: 2012, 조항 4.20에서 적용됨.
[^101]: Definition is adapted from Medical Device and Health IT Joint Security Plan version 2 (JSP2). 정의는 의료기기 및 보건 IT 공동 보안 계획 버전 2(JSP2)에서 적용됨.
[^102]: Definition is adapted from ISO/IEC/IEEE 12207:2017(E) Systems and Software Engineering – Software Life Cycle Processes, subclause 6.4.14.1 Disposal process purpose. 정의는 ISO/IEC/IEEE 12207:2017(E) 시스템 및 소프트웨어 엔지니어링 – 소프트웨어 수명주기 프로세스, 하위 조항 6.4.14.1 처리 프로세스 목적에서 적용됨.
[^103]: Definition is cited from NIST SP 800-82 Guide to Operational Technology (OT) Security. https://doi.org/10.6028/NIST.SP.800-82r3 정의는 NIST SP 800-82 운영 기술(OT) 보안 가이드에서 인용됨. https://doi.org/10.6028/NIST.SP.800-82r3
[^104]: Definition is adapted from the Common Vulnerability Scoring System (CVSS) specification document (v3.1). 정의는 공통 취약점 평가 시스템(CVSS) 사양 문서(v3.1)에서 적용됨.
[^105]: Definition is adapted from NISTIR 8183. https://doi.org/10.6028/NIST.IR.8183 정의는 NISTIR 8183에서 적용됨. https://doi.org/10.6028/NIST.IR.8183
[^106]: Definition is cited from ANSI/ISA 62443-1-1:2018. 정의는 ANSI/ISA 62443-1-1:2018에서 인용됨.
[^107]: Definition is cited from CNSSI 4009-2015 CNSS Glossary. 정의는 CNSSI 4009-2015 CNSS 용어집에서 인용됨.
[^108]: Definition is adapted from AAMI TIR 57 Principles for Medical Device Security – Risk management, Clause 2.15. 정의는 AAMI TIR 57 의료기기 보안 원칙 – 위험 관리, 조항 2.15에서 적용됨.
[^109]: Definition is cited from ANSI/AAMI/ISO 14971:2019 Medical Devices – Application of Risk Management to Medical Devices. 정의는 ANSI/AAMI/ISO 14971:2019 의료기기 – 의료기기에 대한 위험 관리 적용에서 인용됨.
[^110]: Definition is cited from NIST SP 800-53 Rev. 4. 정의는 NIST SP 800-53 Rev. 4에서 인용됨.
[^111]: Definition is adapted from NIST SP 800-45 Version 2. 정의는 NIST SP 800-45 버전 2에서 적용됨.
[^112]: Patient harm from cybersecurity risks is discussed at length throughout this guidance and the Postmarket Cybersecurity Guidance. 사이버보안 위험으로 인한 환자 피해는 본 가이던스 및 시판 후 사이버보안 가이던스 전반에 걸쳐 상세히 논의됨.
[^113]: Definition is adapted from ISO 14971:2019 Medical Devices – Application of Risk Management to Medical Devices. 정의는 ISO 14971:2019 의료기기 – 의료기기에 대한 위험 관리 적용에서 적용됨.
[^114]: Definition is cited from NISTSP 800-53 Rev. 4 Security and Privacy Controls for Federal Information Systems and Organizations, definition of Information System Resilience. https://doi.org/10.6028/NIST.SP.800-53r4 정의는 NISTSP 800-53 Rev. 4 연방 정보 시스템 및 조직에 대한 보안 및 개인정보 통제, 정보 시스템 복원력의 정의에서 인용됨. https://doi.org/10.6028/NIST.SP.800-53r4
[^115]: The term "Secure Product Development Framework" was developed for the purposes of this guidance to help reflect and encompass the concepts related to secure development lifecycles and frameworks. While the term SPDF is new, the concepts around secure product development and risk management are not new, and align with expectations in the Quality System and Labeling Regulations. As cybersecurity continues to evolve, FDA continues to align its terminology to reflect best practices. "보안 제품 개발 프레임워크"라는 용어는 보안 개발 수명주기 및 프레임워크와 관련된 개념을 반영하고 포괄하는 데 도움을 주기 위해 본 가이던스의 목적을 위해 개발되었습니다. SPDF라는 용어는 새로운 것이지만, 보안 제품 개발 및 위험 관리에 대한 개념은 새로운 것이 아니며 품질 시스템 및 라벨링 규정의 기대와 일치합니다. 사이버보안이 계속 진화함에 따라 FDA는 모범 사례를 반영하기 위해 용어를 계속 조정합니다.
[^116]: Definition is cited from NIST 800-160v1 Systems Security Engineering. https://doi.org/10.6028/NIST.SP.800-160v1r1 정의는 NIST 800-160v1 시스템 보안 엔지니어링에서 인용됨. https://doi.org/10.6028/NIST.SP.800-160v1r1
[^117]: Definition is cited from NIST SP 800-108 Recommendation for Key Derivation Using Pseudorandom Functions. https://doi.org/10.6028/NIST.SP.800-108 정의는 NIST SP 800-108 의사 난수 함수를 사용한 키 파생 권장사항에서 인용됨. https://doi.org/10.6028/NIST.SP.800-108
[^118]: Definition is adapted from NTIA's Framing Software Component Transparency: Establishing a Common Software Bill of Materials (SBOM). 정의는 NTIA의 소프트웨어 구성요소 투명성 프레이밍: 공통 소프트웨어 구성 요소 목록(SBOM) 수립에서 적용됨.
[^119]: Definition is adapted from ISO/IEC/IEEE 12207:2017 Systems and Software Engineering – Software Life Cycle Processes. https://doi.org/10.1109/IEEESTD.2017.8100771 정의는 ISO/IEC/IEEE 12207:2017 시스템 및 소프트웨어 엔지니어링 – 소프트웨어 수명주기 프로세스에서 적용됨. https://doi.org/10.1109/IEEESTD.2017.8100771
[^120]: Definition is adapted from NIST SP 800-53. https://doi.org/10.6028/NIST.SP.800-53r5 정의는 NIST SP 800-53에서 적용됨. https://doi.org/10.6028/NIST.SP.800-53r5
[^121]: Definition is adapted from CNSSI 4009-2015 CNSS Glossary. 정의는 CNSSI 4009-2015 CNSS 용어집에서 적용됨.
[^122]: Definition is adapted from NIST SP 800-32 Introduction to Public Key Technology and the Federal PKI Infrastructure. https://doi.org/10.6028/NIST.SP.800-32 정의는 NIST SP 800-32 공개 키 기술 및 연방 PKI 인프라 소개에서 적용됨. https://doi.org/10.6028/NIST.SP.800-32
[^123]: Definition is consistent with the Premarket Software Guidance even though we use the terms differently. 정의는 우리가 용어를 다르게 사용하지만 시판 전 소프트웨어 가이던스와 일치합니다.
[^124]: Definition is cited from IMDRF Guidance "Principles and Practices for Medical Device Cybersecurity." 정의는 IMDRF 가이던스 "의료기기 사이버보안을 위한 원칙 및 관행"에서 인용됨.
[^125]: Definition is adapted from the Common Vulnerability Scoring System (CVSS) specification document (v3.1). 정의는 공통 취약점 평가 시스템(CVSS) 사양 문서(v3.1)에서 적용됨.
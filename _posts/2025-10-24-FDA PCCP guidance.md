---
title:  "[FDA] Marketing Submission Recommendations for a Predetermined Change Control Plan for Artificial Intelligence-Enabled Device Software Functions (번역 포함)"
last_modified_at: 2025-10-24 11:48:22 ## ctrl+shift=I
categories: 
  - guidance
tags:
  - guidance
  - regulatory
  - artificial Intelligence
  - AIMD
toc: true
toc_sticky: true
toc_label: "Table of Contents"
---
**Marketing Submission Recommendations for a Predetermined Change Control Plan for Artificial Intelligence-Enabled Device Software Functions**

Document issued on August 18, 2025.
Document originally issued on December 4, 2024.

번역

# I. Introduction

FDA has a longstanding commitment to develop and apply innovative approaches to the regulation of medical device software and other digital health technologies to ensure their safety and effectiveness[^1]. As technology continues to advance all facets of healthcare, medical software incorporating artificial intelligence (AI), including the subset of AI known as machine learning (ML), has become an important part of many medical devices. This guidance is intended to provide a forward-thinking approach to promote the development of safe and effective AI-enabled devices.

AI technologies have the potential to transform healthcare by deriving new and important insights from the vast amount of data generated during the delivery of healthcare every day. Medical device manufacturers[^2] are using AI technologies to innovate their products to better assist healthcare providers and improve patient care. Examples of AI applications in medicine include earlier disease detection and diagnosis, development of personalized diagnostics and therapeutics, and development of assistive functions to improve the use of devices with the goal of improving user and patient experience.

FDA recognizes that the development of AI-enabled devices (also referred to as AI-enabled device software functions or AI-DSFs)[^3] is an iterative process. This guidance describes an approach that would often be least burdensome[^4] for manufacturers to support iterative improvement through modifications to an AI-DSF while continuing to provide a reasonable assurance of device safety and effectiveness. As such, this guidance demonstrates FDA's broader commitment to developing innovative approaches to the regulation of device software functions as a whole.

Specifically, this guidance provides recommendations on the information to include in a Predetermined Change Control Plan (PCCP) in a marketing submission for a device that includes one or more AI-DSFs. This guidance recommends that a PCCP describe the planned AI-DSF modifications, the associated methodology to develop, validate, and implement those modifications, and an assessment of the impact of those modifications. FDA reviews the PCCP as part of a marketing submission for a device to ensure the continued safety and effectiveness of the device without necessitating additional marketing submissions for implementing each modification described in the PCCP.

In general, FDA's guidance documents do not establish legally enforceable responsibilities. Instead, guidances describe the Agency's current thinking on a topic and should be viewed only as recommendations, unless specific regulatory or statutory requirements are cited. The use of the word *should* in Agency guidances means that something is suggested or recommended, but not required.

[^1]: FDA regulates software that meets the definition of device, which is defined in section 201(h)(1) of the Federal Food, Drug, and Cosmetic Act (FD&C Act) as "an instrument, apparatus, implement, machine, contrivance, implant, in vitro reagent, or other similar or related article, including any component, part, or accessory, which is – recognized in the official National Formulary, or the United States Pharmacopoeia, or any supplement to them, intended for use in the diagnosis of disease or other conditions, or in the cure, mitigation, treatment, or prevention of disease, in man or other animals, or intended to affect the structure or any function of the body of man or other animals, and which does not achieve its primary intended purposes through chemical action within or on the body of man or other animals and which is not dependent upon being metabolized for the achievement of its primary intended purposes. The term 'device' does not include software functions excluded pursuant to section 520(o)" of the FD&C Act. FDA는 기기의 정의를 충족하는 소프트웨어를 규제하며, 이는 연방 식품, 의약품 및 화장품법(FD&C Act)의 섹션 201(h)(1)에서 "기구, 장치, 도구, 기계, 고안물, 이식물, 체외 진단 시약, 또는 기타 유사하거나 관련된 제품으로, 모든 구성요소, 부품 또는 부속품을 포함하며, 공식 국가처방집, 미국약전 또는 그 부록에 수록된 것으로, 인간 또는 다른 동물의 질병 또는 기타 상태의 진단, 치료, 완화, 치료 또는 예방에 사용하도록 의도되거나, 인간 또는 다른 동물의 신체 구조 또는 기능에 영향을 미치도록 의도된 것으로서, 인간 또는 다른 동물의 신체 내부 또는 신체에 대한 화학적 작용을 통해 주된 의도된 목적을 달성하지 않으며 주된 의도된 목적의 달성을 위해 대사되는 것에 의존하지 않는 것"으로 정의됩니다. '기기'라는 용어에는 FD&C Act의 섹션 520(o)에 따라 제외된 소프트웨어 기능은 포함되지 않습니다.

[^2]: For purposes of this guidance, "manufacturer" is used in accordance with the definitions of manufacturer in 21 CFR Parts 803, 806, 807, and 820 and as described in FDA's guidance "[Policy for Device Software Functions and Mobile Medical Applications](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/policy-device-software-functions-and-mobile-medical-applications)." 이 가이던스의 목적상, "제조업체"는 21 CFR Parts 803, 806, 807, 820의 제조업체 정의 및 FDA의 가이던스 "[기기 소프트웨어 기능 및 모바일 의료 애플리케이션에 대한 정책](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/policy-device-software-functions-and-mobile-medical-applications)"에 설명된 대로 사용됩니다.

[^3]: For purposes of this guidance, the terms "AI-enabled device" and "AI-DSF" are used interchangeably, and "device" refers to an AI-DSF unless otherwise stated. Additionally, reference to an "AI-DSF" is referring to a software function that meets the definition of device, as defined in section 201(h) of the FD&C Act. See Section IV. for details on definitions. 이 가이던스의 목적상, "AI 지원 기기"와 "AI-DSF"라는 용어는 상호 교환적으로 사용되며, "기기"는 달리 명시되지 않는 한 AI-DSF를 지칭합니다. 또한, "AI-DSF"에 대한 언급은 FD&C Act의 섹션 201(h)에 정의된 기기의 정의를 충족하는 소프트웨어 기능을 지칭합니다. 정의에 대한 세부사항은 섹션 IV.를 참조하십시오.

[^4]: See FDA's guidance "[The Least Burdensome Provisions: Concept and Principles](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/least-burdensome-provisions-concept-and-principles)." FDA의 가이던스 "[최소 부담 조항: 개념 및 원칙](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/least-burdensome-provisions-concept-and-principles)"을 참조하십시오.

# I. 서론

FDA는 의료기기 소프트웨어 및 기타 디지털 헬스 기술의 안전성과 효과성을 보장하기 위해 혁신적인 접근법을 개발하고 적용하는 데 오랜 기간 전념해 왔다[^1]. 기술이 의료의 모든 측면을 지속적으로 발전시킴에 따라, 머신러닝(ML)으로 알려진 AI의 하위 집합을 포함한 인공지능(AI)을 통합한 의료 소프트웨어는 많은 의료기기의 중요한 부분이 되었다. 본 가이던스는 안전하고 효과적인 AI 기반 기기의 개발을 촉진하기 위한 미래지향적 접근법을 제공하기 위한 것이다.

AI 기술은 매일 의료 서비스 제공 과정에서 생성되는 방대한 양의 데이터로부터 새롭고 중요한 통찰력을 도출함으로써 의료를 변화시킬 잠재력을 가지고 있다. 의료기기 제조업체[^2]는 AI 기술을 사용하여 의료 제공자를 더 잘 지원하고 환자 치료를 개선하기 위해 제품을 혁신하고 있다. 의학 분야의 AI 응용 사례로는 조기 질병 발견 및 진단, 개인 맞춤형 진단 및 치료제 개발, 그리고 사용자 및 환자 경험 개선을 목표로 기기 사용을 향상시키는 보조 기능 개발 등이 있다.

FDA는 AI 기반 기기(AI 기반 기기 소프트웨어 기능 또는 AI-DSF라고도 함)[^3]의 개발이 반복적인 과정임을 인식하고 있다. 본 가이던스는 제조업체가 기기의 안전성과 효과성에 대한 합리적인 보증을 지속적으로 제공하면서 AI-DSF의 수정을 통한 반복적 개선을 지원하는 데 있어 종종 최소 부담[^4]이 될 수 있는 접근법을 설명한다. 따라서 본 가이던스는 기기 소프트웨어 기능 전체의 규제에 대한 혁신적인 접근법을 개발하려는 FDA의 광범위한 약속을 보여준다.

구체적으로, 본 가이던스는 하나 이상의 AI-DSF를 포함하는 기기에 대한 시판 신청서에 사전결정 변경관리계획(PCCP)에 포함해야 할 정보에 대한 권고사항을 제공한다. 본 가이던스는 PCCP가 계획된 AI-DSF 수정사항, 해당 수정사항을 개발, 검증 및 구현하기 위한 관련 방법론, 그리고 해당 수정사항의 영향에 대한 평가를 설명할 것을 권장한다. FDA는 PCCP에 기술된 각 수정사항을 구현하기 위한 추가 시판 신청서를 필요로 하지 않고 기기의 지속적인 안전성과 효과성을 보장하기 위해 기기에 대한 시판 신청서의 일부로서 PCCP를 검토한다.

일반적으로 FDA의 가이던스 문서는 법적으로 집행 가능한 책임을 수립하지 않는다. 대신, 가이던스는 특정 규제 또는 법적 요건이 인용되지 않는 한 해당 주제에 대한 FDA의 현재 견해를 설명하며 권고사항으로만 간주되어야 한다. FDA 가이던스에서 *should*라는 단어의 사용은 어떤 것이 제안되거나 권장되지만 필수는 아님을 의미한다.


# II. Background

In April 2019, FDA published the "[Proposed Regulatory Framework for Modifications to Artificial Intelligence/Machine Learning (AI/ML)-Based Software as a Medical Device (SaMD) - Discussion Paper and Request for Feedback](https://www.fda.gov/media/122535/download)" ("2019 discussion paper")[^5]. The 2019 discussion paper describes FDA's foundation for a potential approach to premarket review for AI/ML-driven software modifications. The ideas delineated in the 2019 discussion paper and further described in this guidance leveraged practices from our premarket programs and relied on the International Medical Device Regulators Forum's risk categorization principles[^6], the FDA's benefit-risk framework[^7], risk management principles described in the Device Modifications guidances[^8], and a total product lifecycle approach[^9].

AI is a machine-based system that can, for a given set of human-defined objectives, make predictions, recommendations, or decisions influencing real or virtual environments. ML is an application of AI that is characterized by providing systems the ability to automatically learn and improve on the basis of data or experience, without being explicitly programmed. One of the greatest potential benefits of AI and ML resides in the ability to improve model performance through iterative modifications, including by learning from real-world data. To support the iterative development of AI-DSFs, and as part of the proposed framework presented in the 2019 discussion paper, FDA described a "Predetermined Change Control Plan" that could be included in a marketing submission for an AI/ML-based device. In this guidance, we provide recommendations on the marketing submission content for a PCCP for an AI-DSF, which generally includes: 1) a detailed description of the specific, planned device modifications, which is referred to as the "Description of Modifications"; 2) the associated methodology to develop, validate, and implement those modifications in a manner that ensures the continued safety and effectiveness of the device across the intended use populations, which is referred to as the "Modification Protocol"; and 3) the assessment of the benefits and risks of the planned modifications and risk mitigations, which is referred to as the "Impact Assessment."

The 2019 discussion paper received a substantial amount of feedback from a wide array of interested parties. General comments were received, as well as specific responses to 18 questions posed in the 2019 discussion paper[^10]. Additionally, numerous articles in peer-reviewed journals discuss or reference the framework proposed in the 2019 discussion paper[^11].

FDA has also held a number of public meetings and workshops on AI/ML topics. On February 25-26, 2020, FDA held a [Public Workshop on the "Evolving Role of Artificial Intelligence in Radiological Imaging"](https://www.fda.gov/medical-devices/workshops-conferences-medical-devices/public-workshop-evolving-role-artificial-intelligence-radiological-imaging-02252020-02262020) to discuss emerging applications of AI in radiological imaging, including AI devices intended to automate the diagnostic radiology workflow as well as guide image acquisition. At this workshop, the Agency worked with interested parties, including patients, to identify both benefits and risks associated with the use of AI in radiological imaging, and discussed best practices for the validation of fully automated radiological imaging software and image acquisition devices.

On October 22, 2020, FDA held a [Patient Engagement Advisory Committee meeting on "Artificial Intelligence and Machine Learning in Medical Devices"](https://www.fda.gov/advisory-committees/advisory-committee-calendar/october-22-2020-patient-engagement-advisory-committee-meeting-announcement-10222020-10222020) to further elicit input from a diverse group of patients. The Committee provided recommendations on AI/ML-enabled medical devices and how to foster patient trust in them, considering the diverse populations in which they are and will be used.

On October 14, 2021, FDA held a [Public Workshop on "Transparency of Artificial Intelligence/Machine Learning-enabled Medical Devices"](https://www.fda.gov/medical-devices/workshops-conferences-medical-devices/virtual-public-workshop-transparency-artificial-intelligencemachine-learning-enabled-medical-devices) for patients, caregivers, and providers. The purpose of the workshop was to 1) identify unique considerations in achieving transparency for users of AI/ML-enabled medical devices and ways in which transparency might enhance the safety and effectiveness of these devices; and 2) gather input from various interested parties on the types of information that would be helpful for manufacturers to include in the labeling and public facing information of AI/ML-enabled medical devices, as well as other potential mechanisms for information sharing.

FDA continues to receive an increasing number of premarket submissions for devices leveraging AI and ML technologies, and the Agency expects this to increase over time. Moreover, since the 2019 discussion paper's publication, there has been strong interest in utilizing PCCPs for AI-enabled devices.

In light of the public health need to facilitate innovation for AI/ML-based devices while providing appropriate oversight for them, on January 12, 2021, the CDRH Digital Health Center of Excellence issued [FDA's Artificial Intelligence/Machine Learning (AI/ML)-Based Software as a Medical Device Action Plan](https://www.fda.gov/medical-devices/software-medical-device-samd/artificial-intelligence-and-machine-learning-aiml-enabled-medical-devices) ("the Action Plan"). The Action Plan describes FDA's strategy for addressing AI/ML-based devices in a holistic, collaborative, and multidisciplinary manner. An important pillar of the Action Plan is the further advancement of the tailored regulatory framework for AI/ML-based devices that was proposed in the 2019 discussion paper.

Additionally, section 3308 of the Food and Drug Omnibus Reform Act of 2022, Title III of Division FF of the Consolidated Appropriations Act, 2023, Pub. L. No. 117-328 ("FDORA") enacted on December 29, 2022, added section 515C "Predetermined Change Control Plans for Devices" to the FD&C Act. Section 515C of the FD&C Act (21 U.S.C. 360e-4) has provisions regarding PCCPs for devices requiring premarket approval (PMA) or premarket notification (510(k)). For example, section 515C provides that a supplemental application (section 515C(a)) or new 510(k) (section 515C(b)) is not required for a change to a device that would otherwise require a PMA supplement or a new 510(k) if the change is consistent with a PCCP approved or cleared by FDA. Section 515C also provides that FDA may require that a PCCP include labeling for safe and effective use of a device as such device changes pursuant to such plan, notification requirements if the device does not function as intended pursuant to such plan, and performance requirements for changes made under the plan[^12].

While under the FD&C Act FDA may approve or clear a PCCP for a variety of devices, this guidance provides recommendations specifically for PCCPs for AI-DSFs. These recommendations are based on the statutory authorities provided in the FD&C Act, including the provisions added by FDORA, as well as feedback obtained through our various interactions with interested parties.

[^5]: Also available at FDA's website on "[Artificial Intelligence and Machine Learning in Software as a Medical Device](https://www.fda.gov/medical-devices/software-medical-device-samd/artificial-intelligence-and-machine-learning-software-medical-device)." FDA 웹사이트 "[의료기기로서의 소프트웨어에서의 인공지능 및 머신러닝](https://www.fda.gov/medical-devices/software-medical-device-samd/artificial-intelligence-and-machine-learning-software-medical-device)"에서도 이용 가능합니다.

[^6]: See FDA's website on "[Global Approach to Software as a Medical Device](https://www.fda.gov/medical-devices/cdrh-international-programs/global-approach-software-medical-device)" and the International Medical Device Regulators Forum (IMDRF) document "[Software as a Medical Device: Possible Framework for Risk Categorization and Corresponding Considerations](http://www.imdrf.org/docs/imdrf/final/technical/imdrf-tech-140918-samd-framework-risk-categorization-141013.pdf)." FDA 웹사이트 "[의료기기로서의 소프트웨어에 대한 글로벌 접근법](https://www.fda.gov/medical-devices/cdrh-international-programs/global-approach-software-medical-device)" 및 국제 의료기기 규제자 포럼(IMDRF) 문서 "[의료기기로서의 소프트웨어: 위험 분류 및 해당 고려사항에 대한 가능한 프레임워크](http://www.imdrf.org/docs/imdrf/final/technical/imdrf-tech-140918-samd-framework-risk-categorization-141013.pdf)"를 참조하십시오.

[^7]: See FDA's guidance "[Factors to Consider When Making Benefit-Risk Determinations in Medical Device Premarket Approval and De Novo Classifications](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/factors-consider-when-making-benefit-risk-determinations-medical-device-premarket-approval-and-de)" and FDA's guidance "[Benefit-Risk Factors to Consider When Determining Substantial Equivalence in Premarket Notifications (510(k)) with Different Technological Characteristics](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/benefit-risk-factors-consider-when-determining-substantial-equivalence-premarket-notifications-510k)." FDA 가이던스 "[의료기기 시판 전 승인 및 De Novo 분류에서 이익-위험 결정을 내릴 때 고려할 요인](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/factors-consider-when-making-benefit-risk-determinations-medical-device-premarket-approval-and-de)" 및 FDA 가이던스 "[다른 기술적 특성을 가진 시판 전 신고(510(k))에서 실질적 동등성을 결정할 때 고려할 이익-위험 요인](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/benefit-risk-factors-consider-when-determining-substantial-equivalence-premarket-notifications-510k)"을 참조하십시오.

[^8]: See FDA's guidances "[Modifications to Devices Subject to Premarket Approval (PMA) - The PMA Supplement Decision-Making Process](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/modifications-devices-subject-premarket-approval-pma-pma-supplement-decision-making-process)," "[Deciding When to Submit a 510(k) for a Change to an Existing Device](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/deciding-when-submit-510k-change-existing-device)," or "[Deciding When to Submit a 510(k) for a Software Change to an Existing Device](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/deciding-when-submit-510k-software-change-existing-device)," referred to as the "Device Modifications guidances" hereafter. FDA 가이던스 "[시판 전 승인(PMA) 대상 기기의 변경 - PMA 보완 의사결정 프로세스](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/modifications-devices-subject-premarket-approval-pma-pma-supplement-decision-making-process)", "[기존 기기의 변경에 대해 510(k)를 제출할 시기 결정](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/deciding-when-submit-510k-change-existing-device)" 또는 "[기존 기기의 소프트웨어 변경에 대해 510(k)를 제출할 시기 결정](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/deciding-when-submit-510k-software-change-existing-device)"을 참조하십시오. 이하 "기기 변경 가이던스"라고 합니다.

[^9]: See FDA's website on "[Total Product Life Cycle for Medical Devices](https://www.fda.gov/industry/regulated-products/medical-device-overview)." FDA 웹사이트 "[의료기기의 전체 제품 수명 주기](https://www.fda.gov/industry/regulated-products/medical-device-overview)"를 참조하십시오.

[^10]: For more information, see the 2019 discussion paper's public docket, [FDA-2019-N-1185](https://www.regulations.gov/docket/FDA-2019-N-1185). 자세한 정보는 2019년 논의 문서의 공개 문서철 [FDA-2019-N-1185](https://www.regulations.gov/docket/FDA-2019-N-1185)를 참조하십시오.

[^11]: For example, Gerke S et al., "The need for a system view to regulate artificial intelligence/machine learning-based software as medical device," *NPJ Digital Medicine* 3, 53 (2020); Harvey et al., "How the FDA Regulates AI," *Academic Radiology* 27, 58-61 (2020); and Subbaswamy et al., "From development to deployment: dataset shift, causality, and shift-stable models in health AI," *Biostatistics* 21, 345-352 (2020). 예를 들어, Gerke S 등, "의료기기로서 인공지능/머신러닝 기반 소프트웨어를 규제하기 위한 시스템 관점의 필요성", *NPJ Digital Medicine* 3, 53 (2020); Harvey 등, "FDA가 AI를 규제하는 방법", *Academic Radiology* 27, 58-61 (2020); 및 Subbaswamy 등, "개발에서 배포까지: 데이터셋 변화, 인과관계, 건강 AI의 변화 안정 모델", *Biostatistics* 21, 345-352 (2020).

[^12]: Sections 515C(a)(3) and 515C(b)(3) of the FD&C Act. FD&C Act의 섹션 515C(a)(3) 및 515C(b)(3).

# II. 배경

2019년 4월, FDA는 "[의료기기로서의 인공지능/머신러닝(AI/ML) 기반 소프트웨어의 수정에 대한 규제 프레임워크 제안 - 토론 문서 및 피드백 요청(Proposed Regulatory Framework for Modifications to Artificial Intelligence/Machine Learning (AI/ML)-Based Software as a Medical Device (SaMD) - Discussion Paper and Request for Feedback)](https://www.fda.gov/media/122535/download)"("2019 토론 문서")[^5]을 발표했다. 2019 토론 문서는 AI/ML 기반 소프트웨어 수정에 대한 시판 전 심사를 위한 잠재적 접근법에 대한 FDA의 기초를 설명한다. 2019 토론 문서에서 설명되고 본 가이던스에서 더욱 자세히 기술된 아이디어는 우리의 시판 전 프로그램의 관행을 활용했으며, 국제의료기기규제당국포럼(International Medical Device Regulators Forum)의 위험 분류 원칙[^6], FDA의 편익-위험 프레임워크[^7], 기기 수정 가이던스에 설명된 위험 관리 원칙[^8], 그리고 총 제품 수명주기 접근법[^9]에 의존했다.

AI는 인간이 정의한 일련의 목표에 대해 실제 또는 가상 환경에 영향을 미치는 예측, 권장사항 또는 결정을 내릴 수 있는 기계 기반 시스템이다. ML은 명시적으로 프로그래밍되지 않고도 데이터 또는 경험을 기반으로 자동으로 학습하고 개선하는 능력을 시스템에 제공하는 것을 특징으로 하는 AI의 응용 분야이다. AI와 ML의 가장 큰 잠재적 이점 중 하나는 실제 데이터로부터 학습하는 것을 포함하여 반복적인 수정을 통해 모델 성능을 개선할 수 있는 능력에 있다. AI-DSF의 반복적 개발을 지원하기 위해, 그리고 2019 토론 문서에서 제시된 제안 프레임워크의 일부로서, FDA는 AI/ML 기반 기기에 대한 시판 신청서에 포함될 수 있는 "사전결정 변경관리계획"을 설명했다. 본 가이던스에서, 우리는 AI-DSF에 대한 PCCP의 시판 신청서 내용에 대한 권고사항을 제공하며, 이는 일반적으로 다음을 포함한다: 1) 구체적이고 계획된 기기 수정사항에 대한 상세한 설명으로 "수정사항 설명(Description of Modifications)"이라고 하며; 2) 의도된 사용 집단 전체에서 기기의 지속적인 안전성과 효과성을 보장하는 방식으로 해당 수정사항을 개발, 검증 및 구현하기 위한 관련 방법론으로 "수정 프로토콜(Modification Protocol)"이라고 하며; 그리고 3) 계획된 수정사항의 편익과 위험 및 위험 완화에 대한 평가로 "영향 평가(Impact Assessment)"라고 한다.

2019 토론 문서는 광범위한 이해관계자들로부터 상당한 양의 피드백을 받았다. 일반적인 의견뿐만 아니라 2019 토론 문서에서 제기된 18개 질문에 대한 구체적인 응답이 접수되었다[^10]. 또한, 동료 심사 저널의 수많은 논문들이 2019 토론 문서에서 제안된 프레임워크를 논의하거나 참조하고 있다[^11].

FDA는 또한 AI/ML 주제에 관한 다수의 공개 회의와 워크숍을 개최했다. 2020년 2월 25-26일, FDA는 진단 방사선 워크플로우를 자동화하고 영상 획득을 안내하기 위한 AI 기기를 포함하여 방사선 영상에서 AI의 새로운 응용 분야를 논의하기 위해 ["방사선 영상에서 인공지능의 진화하는 역할"에 관한 공개 워크숍(Public Workshop on the "Evolving Role of Artificial Intelligence in Radiological Imaging")](https://www.fda.gov/medical-devices/workshops-conferences-medical-devices/public-workshop-evolving-role-artificial-intelligence-radiological-imaging-02252020-02262020)을 개최했다. 이 워크숍에서 FDA는 환자를 포함한 이해관계자들과 협력하여 방사선 영상에서 AI 사용과 관련된 편익과 위험을 모두 파악하고, 완전 자동화된 방사선 영상 소프트웨어 및 영상 획득 기기의 검증을 위한 모범 사례를 논의했다.

2020년 10월 22일, FDA는 다양한 환자 그룹으로부터 추가 의견을 수렴하기 위해 ["의료기기의 인공지능 및 머신러닝"에 관한 환자 참여 자문위원회 회의(Patient Engagement Advisory Committee meeting on "Artificial Intelligence and Machine Learning in Medical Devices")](https://www.fda.gov/advisory-committees/advisory-committee-calendar/october-22-2020-patient-engagement-advisory-committee-meeting-announcement-10222020-10222020)를 개최했다. 위원회는 AI/ML 기반 의료기기가 사용되고 사용될 다양한 집단을 고려하여 AI/ML 기반 의료기기에 대한 권고사항과 이에 대한 환자의 신뢰를 촉진하는 방법을 제공했다.

2021년 10월 14일, FDA는 환자, 간병인 및 의료 제공자를 위해 ["인공지능/머신러닝 기반 의료기기의 투명성"에 관한 공개 워크숍(Public Workshop on "Transparency of Artificial Intelligence/Machine Learning-enabled Medical Devices")](https://www.fda.gov/medical-devices/workshops-conferences-medical-devices/virtual-public-workshop-transparency-artificial-intelligencemachine-learning-enabled-medical-devices)을 개최했다. 워크숍의 목적은 1) AI/ML 기반 의료기기 사용자를 위한 투명성 달성에 있어 고유한 고려사항과 투명성이 이러한 기기의 안전성과 효과성을 향상시킬 수 있는 방법을 식별하고; 2) 제조업체가 AI/ML 기반 의료기기의 라벨링 및 공개 정보에 포함하는 것이 도움이 될 정보 유형과 정보 공유를 위한 기타 잠재적 메커니즘에 대해 다양한 이해관계자로부터 의견을 수집하는 것이었다.

FDA는 AI 및 ML 기술을 활용하는 기기에 대한 시판 전 신청서를 지속적으로 증가하여 받고 있으며, FDA는 이것이 시간이 지남에 따라 증가할 것으로 예상한다. 더욱이, 2019 토론 문서 발표 이후 AI 기반 기기에 대한 PCCP 활용에 대한 강한 관심이 있어 왔다.

AI/ML 기반 기기에 대한 혁신을 촉진하는 동시에 적절한 감독을 제공해야 하는 공중 보건의 필요성에 비추어, 2021년 1월 12일, CDRH 디지털 헬스 우수센터는 [FDA의 의료기기로서의 인공지능/머신러닝(AI/ML) 기반 소프트웨어 실행 계획(FDA's Artificial Intelligence/Machine Learning (AI/ML)-Based Software as a Medical Device Action Plan)](https://www.fda.gov/medical-devices/software-medical-device-samd/artificial-intelligence-and-machine-learning-aiml-enabled-medical-devices)("실행 계획")을 발표했다. 실행 계획은 전체적이고 협력적이며 다학제적인 방식으로 AI/ML 기반 기기를 다루기 위한 FDA의 전략을 설명한다. 실행 계획의 중요한 기둥은 2019 토론 문서에서 제안된 AI/ML 기반 기기를 위한 맞춤형 규제 프레임워크의 추가 발전이다.

추가적으로, 2022년 12월 29일에 제정된 2023년 통합 세출법(Consolidated Appropriations Act, 2023)의 Division FF의 Title III인 2022년 식품의약품 종합 개혁법(Food and Drug Omnibus Reform Act of 2022)의 섹션 3308, Pub. L. No. 117-328("FDORA")은 FD&C Act에 섹션 515C "기기에 대한 사전결정 변경관리계획(Predetermined Change Control Plans for Devices)"을 추가했다. FD&C Act의 섹션 515C(21 U.S.C. 360e-4)는 시판 전 승인(PMA) 또는 시판 전 신고(510(k))가 필요한 기기에 대한 PCCP에 관한 조항을 포함하고 있다. 예를 들어, 섹션 515C는 변경사항이 FDA에 의해 승인되거나 허가된 PCCP와 일치하는 경우, 그렇지 않으면 PMA 보완 또는 새로운 510(k)를 요구하는 기기 변경에 대해 보완 신청서(섹션 515C(a)) 또는 새로운 510(k)(섹션 515C(b))가 필요하지 않다고 규정한다. 섹션 515C는 또한 FDA가 PCCP에 해당 계획에 따라 기기가 변경됨에 따라 기기의 안전하고 효과적인 사용을 위한 라벨링, 해당 계획에 따라 기기가 의도대로 기능하지 않는 경우의 통지 요건, 그리고 계획에 따라 이루어진 변경에 대한 성능 요건을 포함하도록 요구할 수 있다고 규정한다[^12].

FD&C Act에 따라 FDA가 다양한 기기에 대한 PCCP를 승인하거나 허가할 수 있지만, 본 가이던스는 특히 AI-DSF에 대한 PCCP에 대한 권고사항을 제공한다. 이러한 권고사항은 FDORA에 의해 추가된 조항을 포함하여 FD&C Act에 제공된 법적 권한뿐만 아니라 이해관계자들과의 다양한 상호작용을 통해 얻은 피드백을 기반으로 한다.


# III. Scope
This guidance is applicable to AI-DSFs that the manufacturer intends to modify over time. This includes AI-DSFs for which modifications to the AI model are implemented automatically (i.e., for which the modifications are implemented automatically by software, also known as "continuous learning"), AI-DSFs for which modifications to the AI model are implemented manually (i.e., involving steps that require human input, action, review, and/or decision-making, and therefore are not implemented automatically), or a combination of both.

While the recommendations and content in this guidance for PCCPs are intended to be broadly applicable to all AI-enabled devices, the majority of marketing submissions containing PCCPs that FDA has reviewed are submissions for devices that incorporate the subset of AI known as ML. As such, many of the recommendations in this guidance are tailored to devices that incorporate ML.

This guidance describes an approach that would often be least burdensome for manufacturers to support the ability to modify an AI-DSF while maintaining the safety and effectiveness of the device across the intended use populations. Specifically, this guidance includes recommendations on the information that should be included in the PCCP in a marketing submission[^13] for an AI-DSF.

For purposes of this guidance, a PCCP includes those device modifications that generally would otherwise require a new marketing submission[^14],[^15]. These modifications include those that could significantly affect[^16], or that otherwise affect[^17], the safety or effectiveness of the device[^18], unless those modifications are covered by an authorized PCCP. By including a PCCP in a marketing submission for an AI-DSF, manufacturers can prospectively specify and seek premarket authorization[^19] for intended modifications to an AI-DSF without needing to submit additional marketing submissions or obtain further FDA authorization before implementing such modifications – provided the changes are implemented consistent with the PCCP that has been reviewed and established through a device marketing authorization (referred to hereafter as the "authorized PCCP")[^20]. In other words, obtaining FDA authorization of a PCCP as part of a marketing submission for an AI-DSF allows a manufacturer to modify its AI-DSF over time in accordance with the PCCP instead of obtaining separate FDA authorization for each significant change prior to each implementation[^21].

Because a PCCP is appropriate for device modifications that generally would otherwise require a new marketing submission[^22], this guidance does not address a plan that contains a proposal for modifications that would not require a new marketing submission. For such modifications, the Quality System regulation (QSR) (21 CFR Part 820)[^23] requires manufacturers of finished medical devices to, among other things, document the change in the device master record[^24]. For devices subject to PMA requirements, such modifications need to be reported to FDA in post-approval periodic reports required as a condition to approval of the device[^25].

Premarket authorization for an AI-DSF with a PCCP may be established through the PMA pathway (see section 515C(a) of the FD&C Act), the 510(k) pathway (see section 515C(b) of the FD&C Act), or the De Novo pathway (see section 513(f)(2) of the FD&C Act)[^26]. For devices subject to 510(k) requirements, in making a determination of substantial equivalence where the predicate device was authorized with a PCCP, the subject device must be compared to the version of the predicate device cleared or approved prior to changes made under the PCCP[^27].

Generally, the recommendations in this guidance apply to the device constituent[^28] part of device-led[^29] combination products[^30], when the device constituent part includes an AI-DSF. The recommendations in this guidance do not apply to the drug or biologic constituent part of device-led combination products. If a modification to the AI-DSF in a PCCP impacts the drug or biologic constituent part, we highly encourage early engagement with FDA. For such modifications and device-led combination products with a PCCP for an AI-DSF, the FDA review division will consult CBER or CDER, as appropriate.

FDA highly encourages early engagement regarding a proposed PCCP with the FDA review division that will review the AI-DSF; in particular, early engagement could be especially helpful for certain AI-DSFs, including combination products and high-risk, life-sustaining, life-supporting, or implantable devices. FDA encourages manufacturers to leverage the Q-Submission Program[^31] for obtaining FDA feedback on a proposed PCCP for an AI-DSF prior to submitting a marketing submission. The FDA review division with purview over the AI-DSF will provide feedback on a proposed PCCP, including whether the scope of the modifications is appropriate for inclusion in a PCCP and, based on the statutory and regulatory requirements applicable to that AI-DSF, what evidence and information would ensure that the AI-DSF under that PCCP remains safe and effective.

This guidance is intended to provide recommendations on the information to include in a PCCP in a marketing submission for an AI-DSF. This guidance is not intended to provide a complete description of what may be necessary to include in a marketing submission for an AI-DSF[^32]. The recommendations in this guidance do not change applicable statutory and regulatory standards, such as device clearance or approval standards, nor the applicable requirements, including marketing submission content requirements and the requirements for valid scientific evidence[^33]. FDA recommends that you refer to other guidances, as applicable to a specific device, for recommendations on aspects of the submission beyond the PCCP.

This guidance is intended to provide recommendations on certain types of modifications that, at this time, FDA believes generally may be appropriate for inclusion in a PCCP for an AI-DSF. This guidance is not intended to delineate a comprehensive list of modifications FDA would consider appropriate for inclusion in a PCCP for an AI-DSF.

Section IV. of this guidance defines certain terms as they are used for purposes of this guidance. Section V. of this guidance discusses the policy for PCCPs for AI-DSFs, including the components of a PCCP and where information about the PCCP should be included in the marketing submission for a device, and how to establish, implement, or modify a PCCP. Sections VI.-VIII. of this guidance provide an overview of the recommended content for each component of a PCCP for an AI-DSF. The Appendices provide key information to help manufacturers implement the recommendations in this guidance, including detailed questions and considerations for the recommended content of a Modification Protocol in a PCCP for an AI-DSF (Appendix A), as well as example scenarios for employing a PCCP for an AI-DSF (Appendix B).

[^13]: For purposes of this guidance, the term "marketing submission" includes a PMA application, 510(k) submission, or De Novo Classification request. 이 가이던스의 목적상, "마케팅 제출"이라는 용어는 PMA 신청, 510(k) 제출 또는 De Novo 분류 요청을 포함합니다.

[^14]: For purposes of this guidance, unless otherwise stated, references to "device modifications" or "modifications" are those that generally would otherwise require a new marketing submission pursuant to 21 CFR 807.81(a)(3) and 21 CFR 814.39(a). 이 가이던스의 목적상, 달리 명시되지 않는 한, "기기 변경" 또는 "변경사항"에 대한 언급은 일반적으로 21 CFR 807.81(a)(3) 및 21 CFR 814.39(a)에 따라 새로운 마케팅 제출을 요구하는 것들입니다.

[^15]: For more information on whether a modification would require a new marketing submission, see the Device Modifications guidances. 변경사항이 새로운 마케팅 제출을 요구하는지에 대한 자세한 정보는 기기 변경 가이던스를 참조하십시오.

[^16]: 21 CFR 807.81(a)(3). 21 CFR 807.81(a)(3).

[^17]: 21 CFR 814.39(a). 21 CFR 814.39(a).

[^18]: In accordance with 21 CFR 807.81(a)(3), a 510(k) is required for significant changes or modifications to a device and include 1) those that "could significantly affect the safety or effectiveness of the device, e.g., a significant change or modification in design, material, chemical composition, energy source, or manufacturing process" or include 2) "a major change or modification in the intended use of the device." In accordance with 21 CFR 814.39(a), a PMA supplement is required for "change[s] affecting the safety or effectiveness of the device" unless an exception applies (see 21 CFR 814.39). For simplicity, in this guidance, the phrase "significant changes" or "significant modifications" refers to 21 CFR 807.81(a)(3). However, for devices subject to PMA requirements, the broader requirement pursuant to 21 CFR 814.39(a) of a "change affecting the safety or effectiveness" applies. 21 CFR 807.81(a)(3)에 따라, 510(k)는 기기에 대한 중대한 변경 또는 수정에 대해 요구되며, 1) "기기의 안전성 또는 유효성에 중대한 영향을 미칠 수 있는 것, 예: 설계, 재료, 화학 조성, 에너지 원 또는 제조 공정의 중대한 변경 또는 수정" 또는 2) "기기의 의도된 용도에 대한 주요 변경 또는 수정"을 포함합니다. 21 CFR 814.39(a)에 따라, 예외가 적용되지 않는 한(21 CFR 814.39 참조) "기기의 안전성 또는 유효성에 영향을 미치는 변경"에 대해 PMA 보완이 요구됩니다. 간단히 하기 위해, 이 가이던스에서 "중대한 변경" 또는 "중대한 수정"이라는 문구는 21 CFR 807.81(a)(3)을 지칭합니다. 그러나 PMA 요구사항의 적용을 받는 기기의 경우, 21 CFR 814.39(a)에 따른 "안전성 또는 유효성에 영향을 미치는 변경"의 보다 광범위한 요구사항이 적용됩니다.

[^19]: For purposes of this guidance, the term "authorization" includes approval of a PMA application, clearance of a 510(k) submission, or grant of a De Novo Classification request. 이 가이던스의 목적상, "승인"이라는 용어는 PMA 신청의 승인(approval), 510(k) 제출의 허가(clearance) 또는 De Novo 분류 요청의 부여(grant)를 포함합니다.

[^20]: For purposes of this guidance, the term "authorized PCCP" refers to a PCCP that has been reviewed and established through a device marketing authorization. See Section IV. for more information on definitions. 이 가이던스의 목적상, "승인된 PCCP"라는 용어는 기기 마케팅 승인을 통해 검토되고 확립된 PCCP를 지칭합니다. 정의에 대한 자세한 정보는 섹션 IV.를 참조하십시오.

[^21]: Sections 515C(a)(1) and 515C(b)(1) of the FD&C Act, 21 CFR 807.81(a)(3), and 21 CFR 814.39(a). FD&C Act의 섹션 515C(a)(1) 및 515C(b)(1), 21 CFR 807.81(a)(3), 21 CFR 814.39(a).

[^22]: 21 CFR 807.81(a)(3) and 21 CFR 814.39(a). 21 CFR 807.81(a)(3) 및 21 CFR 814.39(a).

[^23]: On February 2, 2024, FDA issued a final rule amending the device QSR, 21 CFR Part 820, to align more closely with international consensus standards for devices ([89 FR 7496](https://www.federalregister.gov/documents/2024/02/02/2024-02067/medical-devices-quality-system-requirements)). This final rule will take effect on February 2, 2026. Once in effect, this rule will withdraw the majority of the current requirements in Part 820 and instead incorporate by reference the 2016 edition of the International Organization for Standardization (ISO) 13485, Medical devices – Quality management systems – Requirements for regulatory purposes, in Part 820. As stated in the final rule, the requirements in ISO 13485 are, when taken in totality, substantially similar to the requirements of the current Part 820, providing a similar level of assurance in a firm's quality management system and ability to consistently manufacture devices that are safe and effective and otherwise in compliance with the FD&C Act. When the final rule takes effect, FDA will also update the references to provisions in 21 CFR Part 820 in this guidance to be consistent with that rule. 2024년 2월 2일, FDA는 기기에 대한 국제 합의 표준과 보다 밀접하게 정렬하기 위해 기기 QSR인 21 CFR Part 820을 개정하는 최종 규칙을 발표했습니다([89 FR 7496](https://www.federalregister.gov/documents/2024/02/02/2024-02067/medical-devices-quality-system-requirements)). 이 최종 규칙은 2026년 2월 2일에 발효됩니다. 발효되면, 이 규칙은 Part 820의 현행 요구사항의 대부분을 철회하고 대신 국제표준화기구(ISO) 13485, 의료기기 - 품질 관리 시스템 - 규제 목적을 위한 요구사항의 2016년 판을 Part 820에 참조로 통합합니다. 최종 규칙에 명시된 바와 같이, ISO 13485의 요구사항은 전체적으로 볼 때 현행 Part 820의 요구사항과 실질적으로 유사하며, 기업의 품질 관리 시스템과 안전하고 효과적이며 FD&C Act를 준수하는 기기를 일관되게 제조할 수 있는 능력에 대한 유사한 수준의 보증을 제공합니다. 최종 규칙이 발효되면, FDA는 또한 이 가이던스의 21 CFR Part 820 조항에 대한 참조를 해당 규칙과 일치하도록 업데이트할 것입니다.

[^24]: See 21 CFR 820.181. 21 CFR 820.181을 참조하십시오.

[^25]: See 21 CFR 814.39(b) and 814.82(a)(7) and FDA's guidance "[Annual Reports for Approved Premarket Approval Applications (PMA)](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/annual-reports-approved-premarket-approval-applications-pma)." 21 CFR 814.39(b) 및 814.82(a)(7) 및 FDA 가이던스 "[승인된 시판 전 승인 신청(PMA)에 대한 연례 보고서](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/annual-reports-approved-premarket-approval-applications-pma)"를 참조하십시오.

[^26]: The De Novo classification process allows FDA to classify a device into class I or II when general controls or general controls and special controls provide a reasonable assurance of safety and effectiveness, but for which there is no legally marketed predicate. The De Novo pathway, therefore, allows FDA to develop special controls that provide a reasonable assurance of the safety and effectiveness of the subject device. At this time, FDA expects that if it authorizes an AI-DSF with a PCCP via the De Novo pathway, the Agency would develop appropriate special controls, which may include specific requirements for a PCCP. De Novo 분류 프로세스는 일반 관리 또는 일반 관리 및 특별 관리가 안전성 및 유효성에 대한 합리적인 보증을 제공하지만 법적으로 판매된 대조기기가 없는 경우 FDA가 기기를 클래스 I 또는 II로 분류할 수 있도록 합니다. 따라서 De Novo 경로는 FDA가 대상 기기의 안전성 및 유효성에 대한 합리적인 보증을 제공하는 특별 관리를 개발할 수 있도록 합니다. 현재, FDA는 De Novo 경로를 통해 PCCP를 가진 AI-DSF를 승인하는 경우, 기관이 PCCP에 대한 특정 요구사항을 포함할 수 있는 적절한 특별 관리를 개발할 것으로 예상합니다.

[^27]: See section 515C(c) of the FD&C Act. FD&C Act의 섹션 515C(c)를 참조하십시오.

[^28]: See 21 CFR 4.2. 21 CFR 4.2를 참조하십시오.

[^29]: See 21 CFR 3.4 for information on lead center assignment. 주관 센터 배정에 대한 정보는 21 CFR 3.4를 참조하십시오.

[^30]: See 21 CFR 3.2(e). 21 CFR 3.2(e)를 참조하십시오.

[^31]: See FDA's guidance "[Requests for Feedback and Meetings for Medical Device Submissions: The Q-Submission Program](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/requests-feedback-and-meetings-medical-device-submissions-q-submission-program)" hereafter referred to as the "Q-Submission Program." FDA 가이던스 "[의료기기 제출에 대한 피드백 및 회의 요청: Q-제출 프로그램](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/requests-feedback-and-meetings-medical-device-submissions-q-submission-program)"을 참조하십시오. 이하 "Q-제출 프로그램"이라고 합니다.

[^32]: See, e.g., 21 CFR 807.87, 21 CFR 860.220, or 21 CFR 814.20. 예를 들어, 21 CFR 807.87, 21 CFR 860.220 또는 21 CFR 814.20을 참조하십시오.

[^33]: See, e.g., 21 CFR 807.87, 21 CFR 860.220, or 21 CFR 814.20, and 21 CFR 860.7(c). 예를 들어, 21 CFR 807.87, 21 CFR 860.220 또는 21 CFR 814.20, 및 21 CFR 860.7(c)를 참조하십시오.

# III. 적용 범위

본 가이던스는 제조업체가 시간이 지남에 따라 수정하려는 AI-DSF에 적용된다. 여기에는 AI 모델에 대한 수정사항이 자동으로 구현되는 AI-DSF(즉, 수정사항이 소프트웨어에 의해 자동으로 구현되며, "지속적 학습"이라고도 함), AI 모델에 대한 수정사항이 수동으로 구현되는 AI-DSF(즉, 인간의 입력, 행동, 검토 및/또는 의사결정이 필요한 단계를 포함하므로 자동으로 구현되지 않음), 또는 두 가지의 조합이 포함된다.

PCCP에 대한 본 가이던스의 권고사항과 내용은 모든 AI 기반 기기에 광범위하게 적용되도록 의도되었지만, FDA가 검토한 PCCP를 포함하는 대부분의 시판 신청서는 ML로 알려진 AI의 하위 집합을 통합한 기기에 대한 신청서이다. 따라서 본 가이던스의 많은 권고사항은 ML을 통합한 기기에 맞춰져 있다.

본 가이던스는 의도된 사용 집단 전체에서 기기의 안전성과 효과성을 유지하면서 AI-DSF를 수정할 수 있는 능력을 지원하는 데 있어 제조업체에게 종종 최소 부담이 될 수 있는 접근법을 설명한다. 구체적으로, 본 가이던스는 AI-DSF에 대한 시판 신청서[^13]에서 PCCP에 포함되어야 하는 정보에 대한 권고사항을 포함한다.

본 가이던스의 목적상, PCCP는 일반적으로 그렇지 않으면 새로운 시판 신청서를 요구하는 기기 수정사항을 포함한다[^14],[^15]. 이러한 수정사항에는 승인된 PCCP에 의해 포함되지 않는 한, 기기의 안전성 또는 효과성에 상당한 영향을 미칠 수 있는[^16] 것, 또는 그렇지 않으면 영향을 미치는[^17] 것이 포함된다[^18]. AI-DSF에 대한 시판 신청서에 PCCP를 포함함으로써, 제조업체는 추가 시판 신청서를 제출하거나 그러한 수정사항을 구현하기 전에 추가 FDA 승인을 받을 필요 없이 AI-DSF에 대한 의도된 수정사항을 사전에 명시하고 시판 전 승인[^19]을 요청할 수 있다 – 단, 변경사항이 기기 시판 승인을 통해 검토되고 수립된 PCCP(이하 "승인된 PCCP"라고 함)[^20]와 일치하게 구현되는 경우에 한한다. 즉, AI-DSF에 대한 시판 신청서의 일부로서 PCCP에 대한 FDA 승인을 받으면 제조업체는 각 구현 전에 각 중요한 변경사항에 대해 별도의 FDA 승인을 받는 대신 PCCP에 따라 시간이 지남에 따라 AI-DSF를 수정할 수 있다[^21].

PCCP는 일반적으로 그렇지 않으면 새로운 시판 신청서를 요구하는 기기 수정사항에 적합하므로[^22], 본 가이던스는 새로운 시판 신청서를 요구하지 않는 수정사항에 대한 제안을 포함하는 계획을 다루지 않는다. 이러한 수정사항의 경우, 품질 시스템 규정(QSR)(21 CFR Part 820)[^23]은 완성된 의료기기 제조업체가 특히 기기 마스터 기록에 변경사항을 문서화하도록 요구한다[^24]. PMA 요건의 적용을 받는 기기의 경우, 이러한 수정사항은 기기 승인 조건으로 요구되는 승인 후 정기 보고서에서 FDA에 보고되어야 한다[^25].

PCCP가 있는 AI-DSF에 대한 시판 전 승인은 PMA 경로(FD&C Act의 섹션 515C(a) 참조), 510(k) 경로(FD&C Act의 섹션 515C(b) 참조), 또는 De Novo 경로(FD&C Act의 섹션 513(f)(2) 참조)를 통해 수립될 수 있다[^26]. 510(k) 요건의 적용을 받는 기기의 경우, 선행 기기가 PCCP와 함께 승인된 경우 실질적 동등성을 판단함에 있어, 대상 기기는 PCCP에 따라 변경이 이루어지기 전에 허가 또는 승인된 버전의 선행 기기와 비교되어야 한다[^27].

일반적으로, 본 가이던스의 권고사항은 기기 구성 부분[^28]이 AI-DSF를 포함하는 경우, 기기 주도[^29] 복합 제품[^30]의 기기 구성 부분에 적용된다. 본 가이던스의 권고사항은 기기 주도 복합 제품의 의약품 또는 생물학적 제제 구성 부분에는 적용되지 않는다. PCCP의 AI-DSF에 대한 수정사항이 의약품 또는 생물학적 제제 구성 부분에 영향을 미치는 경우, FDA와의 조기 협의를 강력히 권장한다. 이러한 수정사항 및 AI-DSF에 대한 PCCP가 있는 기기 주도 복합 제품의 경우, FDA 심사 부서는 적절하게 CBER 또는 CDER과 협의할 것이다.

FDA는 AI-DSF를 검토할 FDA 심사 부서와 제안된 PCCP에 관한 조기 협의를 강력히 권장한다; 특히, 조기 협의는 복합 제품 및 고위험, 생명 유지, 생명 지원 또는 이식형 기기를 포함한 특정 AI-DSF에 특히 도움이 될 수 있다. FDA는 제조업체가 시판 신청서를 제출하기 전에 AI-DSF에 대한 제안된 PCCP에 대한 FDA 피드백을 얻기 위해 Q-제출 프로그램[^31]을 활용할 것을 권장한다. AI-DSF에 대한 관할권을 가진 FDA 심사 부서는 수정사항의 범위가 PCCP에 포함하기에 적절한지 여부 및 해당 AI-DSF에 적용되는 법적 및 규제 요건에 기반하여 해당 PCCP 하의 AI-DSF가 안전하고 효과적으로 유지되도록 보장하는 증거 및 정보가 무엇인지를 포함하여 제안된 PCCP에 대한 피드백을 제공할 것이다.

본 가이던스는 AI-DSF에 대한 시판 신청서에서 PCCP에 포함할 정보에 대한 권고사항을 제공하기 위한 것이다. 본 가이던스는 AI-DSF에 대한 시판 신청서에 포함할 필요가 있을 수 있는 것에 대한 완전한 설명을 제공하기 위한 것이 아니다[^32]. 본 가이던스의 권고사항은 기기 허가 또는 승인 기준과 같은 적용 가능한 법적 및 규제 기준, 시판 신청서 내용 요건 및 유효한 과학적 증거에 대한 요건을 포함한 적용 가능한 요건을 변경하지 않는다[^33]. FDA는 PCCP를 넘어선 신청서의 측면에 대한 권고사항은 특정 기기에 적용 가능한 다른 가이던스를 참조할 것을 권장한다.

본 가이던스는 현재 FDA가 일반적으로 AI-DSF에 대한 PCCP에 포함하기에 적절할 수 있다고 판단하는 특정 유형의 수정사항에 대한 권고사항을 제공하기 위한 것이다. 본 가이던스는 FDA가 AI-DSF에 대한 PCCP에 포함하기에 적절하다고 고려하는 수정사항의 포괄적인 목록을 설명하기 위한 것이 아니다.

본 가이던스의 섹션 IV는 본 가이던스의 목적상 사용되는 특정 용어를 정의한다. 본 가이던스의 섹션 V는 PCCP의 구성요소 및 기기에 대한 시판 신청서에 PCCP에 대한 정보가 포함되어야 하는 위치, PCCP를 수립, 구현 또는 수정하는 방법을 포함하여 AI-DSF에 대한 PCCP의 정책을 논의한다. 본 가이던스의 섹션 VI.-VIII.은 AI-DSF에 대한 PCCP의 각 구성요소에 대한 권장 내용의 개요를 제공한다. 부록은 AI-DSF에 대한 PCCP의 수정 프로토콜의 권장 내용에 대한 상세한 질문 및 고려사항(부록 A)과 AI-DSF에 대한 PCCP를 사용하는 예시 시나리오(부록 B)를 포함하여 본 가이던스의 권고사항을 구현하는 데 도움이 되는 주요 정보를 제공한다.


# IV. Definitions

This section defines certain terms as they are used for purposes of this guidance.

## A. Software Functions

**Artificial Intelligence (AI):** A machine-based system that can, for a given set of human-defined objectives, make predictions, recommendations, or decisions influencing real or virtual environments. Artificial intelligence systems use machine- and human-based inputs to perceive real and virtual environments; abstract such perceptions into models through analysis in an automated manner; and use model inference to formulate options for information or action[^34].

**Machine Learning (ML):** An application of artificial intelligence that is characterized by providing systems the ability to automatically learn and improve on the basis of data or experience, without being explicitly programmed[^35].

**Device Software Function (DSF):** A software function that meets the device definition in section 201(h) of the FD&C Act[^36] [^37]. As discussed in other FDA guidance, the term "function" is a distinct purpose of the product, which could be the intended use or a subset of the intended use of the product[^38].

**Artificial Intelligence-Enabled Device Software Function (AI-DSF):** A device software function (as defined above) that implements an AI model. AI-DSFs are the focus of this guidance.

## B. Data Sets

**Training Data:** These data are used by the manufacturer of an AI-DSF in procedures and training algorithms to build an AI model, including to define model weights, connections, and components[^39]. These data typically should be representative of the proposed intended use populations (e.g., with respect to race, ethnicity, disease severity, sex, age, or others, as appropriate) and intended environments.

**Tuning Data:** These data are typically used by the manufacturer of an AI-DSF to evaluate a small number of trained AI models. This process involves exploring various aspects, including different architectures or hyperparameters[^40]. The tuning phase happens before the testing phase of the AI-DSF and is part of the training process. While the AI and ML communities sometimes use the term "validation" to refer to the tuning data and phase, FDA does not use the word "validation" in this context.

**Test Data:** These data are used to characterize the performance of an AI-DSF. These data are never shown to the algorithm during training and are used to estimate the AI model's performance after training[^41]. Testing is conducted to generate evidence to establish the performance of an AI-DSF before it is deployed or marketed. The testing phase is also expected to provide evidence to demonstrate a reasonable assurance of safety and effectiveness of an AI-DSF before it is deployed or marketed. These data typically should be representative of the proposed intended use populations (e.g., with respect to race, ethnicity, disease severity, sex, age, or others, as appropriate) and intended environments. Test data should be independent of data used for training and tuning and should generally be from multiple sites different from those that were used to generate training and tuning data.

## C. Predetermined Change Control Plan

**Predetermined Change Control Plan (PCCP):** The documentation describing what modifications will be made to a device and how the modifications will be assessed. The modifications described in the PCCP include device modifications that would otherwise require a PMA supplement or new premarket notification[^42]. The PCCP includes a Description of Modifications, Modification Protocol, and Impact Assessment. PCCPs for AI-DSFs are the focus of this guidance.

**Authorized Predetermined Change Control Plan (Authorized PCCP):** A PCCP that has been reviewed and established through a device marketing authorization. An authorized PCCP is a technological characteristic of the authorized device with which it was established.

**Modification Protocol:** The documentation describing the methods that will be followed when developing, validating, and implementing modifications delineated in the Description of Modifications section of the PCCP. The Modification Protocol includes the verification and validation activities (including pre-defined acceptance criteria) for those modifications and is intended to provide a step-by-step delineation of how the modifications included in the PCCP will be implemented while ensuring the device remains safe and effective.

**Impact Assessment:** The documentation of the assessment of the benefits and risks of implementing a PCCP, as well as the plan for risk mitigation.

[^34]: 15 U.S.C. 9401(3). 15 U.S.C. 9401(3).

[^35]: 15 U.S.C. 9401(11). 15 U.S.C. 9401(11).

[^36]: See footnote 1. 각주 1을 참조하십시오.

[^37]: Device software functions may include Software as a Medical Device (SaMD) and Software in a Medical Device (SiMD). See FDA's website on "[Software as a Medical Device (SaMD)](https://www.fda.gov/medical-devices/digital-health-center-excellence/software-medical-device-samd)." 기기 소프트웨어 기능에는 의료기기로서의 소프트웨어(SaMD) 및 의료기기 내 소프트웨어(SiMD)가 포함될 수 있습니다. FDA 웹사이트 "[의료기기로서의 소프트웨어(SaMD)](https://www.fda.gov/medical-devices/digital-health-center-excellence/software-medical-device-samd)"를 참조하십시오.

[^38]: See FDA's guidance "[Multiple Function Device Products: Policy and Considerations](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/multiple-function-device-products-policy-and-considerations)." FDA 가이던스 "[다기능 기기 제품: 정책 및 고려사항](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/multiple-function-device-products-policy-and-considerations)"을 참조하십시오.

[^39]: Adapted from the IMDRF document "[Machine Learning-enabled Medical Devices: Key Terms and Definitions](http://www.imdrf.org/docs/imdrf/final/technical/imdrf-tech-220922-mlmd-key-definitions-n71.pdf)." IMDRF 문서 "[머신러닝 지원 의료기기: 주요 용어 및 정의](http://www.imdrf.org/docs/imdrf/final/technical/imdrf-tech-220922-mlmd-key-definitions-n71.pdf)"에서 발췌.

[^40]: Adapted from IEEE 2802 Standard for Performance and Safety Evaluation of Artificial Intelligence Based Medical Devices: Terminology. IEEE 2802 인공지능 기반 의료기기의 성능 및 안전성 평가 표준: 용어에서 발췌.

[^41]: Adapted from the IMDRF document "[Machine Learning-enabled Medical Devices: Key Terms and Definitions](http://www.imdrf.org/docs/imdrf/final/technical/imdrf-tech-220922-mlmd-key-definitions-n71.pdf)." IMDRF 문서 "[머신러닝 지원 의료기기: 주요 용어 및 정의](http://www.imdrf.org/docs/imdrf/final/technical/imdrf-tech-220922-mlmd-key-definitions-n71.pdf)"에서 발췌.

[^42]: Section 515C(a)(2) and 515C(b)(2) of the FD&C Act. FD&C Act의 섹션 515C(a)(2) 및 515C(b)(2).

# IV. 정의

본 섹션은 본 가이던스의 목적상 사용되는 특정 용어를 정의한다.

## A. 소프트웨어 기능

**인공지능(AI):** 인간이 정의한 일련의 목표에 대해 실제 또는 가상 환경에 영향을 미치는 예측, 권장사항 또는 결정을 내릴 수 있는 기계 기반 시스템. 인공지능 시스템은 기계 및 인간 기반 입력을 사용하여 실제 및 가상 환경을 인식하고; 자동화된 방식으로 분석을 통해 이러한 인식을 모델로 추상화하며; 모델 추론을 사용하여 정보 또는 행동을 위한 옵션을 공식화한다[^34].

**머신러닝(ML):** 명시적으로 프로그래밍되지 않고도 데이터 또는 경험을 기반으로 자동으로 학습하고 개선하는 능력을 시스템에 제공하는 것을 특징으로 하는 인공지능의 응용 분야[^35].

**기기 소프트웨어 기능(DSF):** FD&C Act의 섹션 201(h)에서 기기 정의를 충족하는 소프트웨어 기능[^36],[^37]. 다른 FDA 가이던스에서 논의된 바와 같이, "기능"이라는 용어는 제품의 의도된 용도 또는 제품의 의도된 용도의 하위 집합이 될 수 있는 제품의 명확한 목적이다[^38].

**AI 기반 기기 소프트웨어 기능(AI-DSF):** AI 모델을 구현하는 기기 소프트웨어 기능(위에서 정의한 대로). AI-DSF는 본 가이던스의 초점이다.

## B. 데이터 세트

**훈련 데이터:** 이러한 데이터는 모델 가중치, 연결 및 구성요소를 정의하는 것을 포함하여 AI 모델을 구축하기 위해 AI-DSF 제조업체가 절차 및 훈련 알고리즘에서 사용하는 데이터이다[^39]. 이러한 데이터는 일반적으로 제안된 의도된 사용 집단(예: 인종, 민족, 질병 중증도, 성별, 연령 또는 적절한 경우 기타 특성과 관련하여) 및 의도된 환경을 대표해야 한다.

**튜닝 데이터:** 이러한 데이터는 일반적으로 AI-DSF 제조업체가 소수의 훈련된 AI 모델을 평가하기 위해 사용한다. 이 프로세스는 다양한 아키텍처 또는 하이퍼파라미터를 포함한 다양한 측면을 탐색하는 것을 포함한다[^40]. 튜닝 단계는 AI-DSF의 테스트 단계 이전에 발생하며 훈련 프로세스의 일부이다. AI 및 ML 커뮤니티는 때때로 튜닝 데이터 및 단계를 지칭하기 위해 "검증"이라는 용어를 사용하지만, FDA는 이러한 맥락에서 "검증"이라는 단어를 사용하지 않는다.

**테스트 데이터:** 이러한 데이터는 AI-DSF의 성능을 특성화하기 위해 사용된다. 이러한 데이터는 훈련 중에 알고리즘에 절대 표시되지 않으며 훈련 후 AI 모델의 성능을 추정하기 위해 사용된다[^41]. 테스트는 AI-DSF가 배포되거나 시판되기 전에 AI-DSF의 성능을 입증하기 위한 증거를 생성하기 위해 수행된다. 테스트 단계는 또한 AI-DSF가 배포되거나 시판되기 전에 AI-DSF의 안전성과 효과성에 대한 합리적인 보증을 입증하기 위한 증거를 제공할 것으로 예상된다. 이러한 데이터는 일반적으로 제안된 의도된 사용 집단(예: 인종, 민족, 질병 중증도, 성별, 연령 또는 적절한 경우 기타 특성과 관련하여) 및 의도된 환경을 대표해야 한다. 테스트 데이터는 훈련 및 튜닝에 사용된 데이터와 독립적이어야 하며 일반적으로 훈련 및 튜닝 데이터를 생성하는 데 사용된 것과 다른 여러 사이트에서 가져와야 한다.

## C. 사전결정 변경관리계획

**사전결정 변경관리계획(PCCP):** 기기에 어떤 수정사항이 이루어질 것인지 그리고 수정사항이 어떻게 평가될 것인지를 설명하는 문서. PCCP에 설명된 수정사항에는 그렇지 않으면 PMA 보완 또는 새로운 시판 전 신고를 요구하는 기기 수정사항이 포함된다[^42]. PCCP에는 수정사항 설명, 수정 프로토콜 및 영향 평가가 포함된다. AI-DSF에 대한 PCCP는 본 가이던스의 초점이다.

**승인된 사전결정 변경관리계획(승인된 PCCP):** 기기 시판 승인을 통해 검토되고 수립된 PCCP. 승인된 PCCP는 그것이 수립된 승인된 기기의 기술적 특성이다.

**수정 프로토콜:** PCCP의 수정사항 설명 섹션에 기술된 수정사항을 개발, 검증 및 구현할 때 따라야 할 방법을 설명하는 문서. 수정 프로토콜에는 해당 수정사항에 대한 검증 및 확인 활동(사전 정의된 수용 기준 포함)이 포함되며, 기기가 안전하고 효과적으로 유지되도록 하면서 PCCP에 포함된 수정사항이 어떻게 구현될 것인지에 대한 단계별 설명을 제공하기 위한 것이다.

**영향 평가:** PCCP 구현의 편익과 위험에 대한 평가 문서 및 위험 완화 계획.

# V. Policy for Predetermined Change Control Plans
Software development is an iterative process, and FDA appreciates that manufacturers of device software functions strive to continually improve and update their devices. Manufacturers should evaluate the impact of modifications to their devices and must generally submit a marketing submission when device modifications affect the intended use of the device or could significantly affect the safety or effectiveness of the device[^43].

An authorized PCCP specifies planned modifications that, if not included in a PCCP, could otherwise require a new marketing submission pursuant to 21 CFR 807.81(a)(3) and 21 CFR 814.39(a), and consistent with the Device Modifications guidances. An authorized PCCP should include the following sections, which will be further described in Sections VI. through VIII. of this guidance:

* **Description of Modifications (Section VI.)** – The specifications for the characteristics and performance of the planned modifications to the device;
* **Modification Protocol (Section VII.)** – The associated verification and validation testing activities that will support the planned modifications and acceptance criteria to assure the device remains safe and effective across the intended use populations; and
* **Impact Assessment (Section VIII.)** – The assessment of the benefits and risks of implementing a PCCP, as well as the plan for risk mitigation.

Because modifications that are specified and implemented in accordance with an authorized PCCP were reviewed and authorized through the marketing submission containing the PCCP, the modifications can be implemented to the AI-DSF without triggering the need for a new marketing submission[^44].

FDA would consider it to be a deviation from the authorized PCCP in circumstances where the PCCP is not followed or cannot be followed[^45]. Deviations from the authorized PCCP could significantly affect the safety or effectiveness of the device. This could include, for example, issues related to the Modification Protocol, such as data management or re-training failure, or failure to meet pre-specified performance criteria. Device modifications that would not require a marketing submission would not be considered a deviation from an authorized PCCP[^46]. However, significant modifications made to an AI-DSF that are not specified in, or implemented in accordance with, the authorized PCCP likely require a new marketing submission prior to implementation of the modification[^47]. Deviations from the authorized PCCP reviewed in the marketing submission would generally cause the device to be adulterated and misbranded under sections 501(f)(1) and 502(o) of the FD&C Act, respectively. The introduction or delivery for introduction into interstate commerce of any food, drug, device, tobacco product, or cosmetic that is adulterated or misbranded is prohibited under section 301(a) of the FD&C Act, and where appropriate, FDA may take legal or regulatory action against violations of prohibited acts, including, without limitation, seizure or injunction.

## A. Components of a PCCP

A PCCP should consist of a detailed Description of Modifications, a Modification Protocol, and an Impact Assessment (see Sections VI. – VIII. of this guidance) because these components are intended to provide FDA with information that will enable our review of the proposed modifications. When developing a PCCP, manufacturers should consider the intended use populations (with respect to race, ethnicity, disease severity, sex, age, or others, as appropriate) and intended environments of use, so that the device continues to reflect these populations and environments as the device is modified. The detailed Description of Modifications should outline the specific, planned modifications that may be made to the AI-DSF. This includes defining the specifications for the characteristics and performance of the planned modifications to the device. The Modification Protocol should describe the verification and validation activities, including pre-defined acceptance criteria, that will support each modification to assure the device remains safe and effective across the intended use populations. The Impact Assessment helps to tie the Description of Modifications to the Modification Protocol in that the Impact Assessment identifies the benefits and risks introduced by the specified, planned modifications and addresses how the verification and validation activities of the Modification Protocol will continue to assure the safety and effectiveness of the device. The detailed Description of Modifications, Modification Protocol, and Impact Assessment are all interrelated components of a PCCP. The Appendices provide key information to help manufacturers implement the recommendations in this guidance, including detailed questions and considerations for the recommended content of a Modification Protocol in a PCCP (Appendix A), as well as example scenarios for employing a PCCP for an AI-DSF (Appendix B).

## B. Establishing a PCCP

Premarket authorization for an AI-DSF with a PCCP must be established through the PMA pathway, 510(k) pathway, or De Novo pathway, as appropriate, as a PCCP must be reviewed and established as part of a marketing authorization[^48],[^49] for a device prior to a manufacturer implementing any modifications under that PCCP. Correspondingly, submission types for which FDA does not make an affirmative decision (i.e., authorization) would not be appropriate to establish a PCCP. In general, FDA considers the following submission types to be appropriate to establish a PCCP:

* For AI-DSFs subject to PMA requirements:
  * Original PMA application
  * Modular PMA application, where a PCCP comprises a module of review
  * 180-Day PMA supplement
  * Panel Track PMA supplement
  * Real-Time PMA supplement, where a PCCP comprises minor changes and the manufacturer and FDA agree that the review can be achieved in a real-time setting[^50],[^51]
* For AI-DSFs subject to 510(k) requirements:
  * Traditional 510(k) submission
  * Abbreviated 510(k) submission[^52]
* For AI-DSFs subject to De Novo requirements:
  * Original De Novo request

A PCCP is authorized as part of the device marketing authorization. FDA must reach a determination[^53] of reasonable assurance of safety and effectiveness or substantial equivalence in review of the device, including each modification specified in the PCCP, for the PCCP to be authorized with the device.

As manufacturers implement modifications included in an authorized PCCP, FDA expects manufacturers to implement the modifications consistent with their authorized PCCP, i.e., in accordance with their Modification Protocol. A manufacturer must implement any changes in accordance with their quality system[^54]. A manufacturer's quality system is critical for change management processes for a device, especially for devices that include a PCCP, because a PCCP includes modifications that generally would otherwise require a new marketing submission[^55]. Compliance with the QSR is essential in order for a manufacturer to implement modifications consistent with their authorized PCCP and failure to do so could potentially present a serious risk to human health.

Under section 515C(a)(2) of the FD&C Act, FDA may approve a PCCP submitted in a PMA. Under section 515(d)(2)(C) of the FD&C Act, FDA must deny approval of a PMA if FDA finds that the methods used in, or the facilities or controls used for, the manufacture, processing, packing, or installation of such device do not conform to the QSR requirements. Thus, consistent with sections 515C(a)(2) and 515(d)(2)(C) of the FD&C Act, FDA must deny approval of a PCCP submitted in a PMA if FDA finds that the methods used in, or the facilities or controls used for, the manufacture, processing, packing, or installation of the subject device do not conform to the QSR requirements.

Under section 515C(b)(2) of the FD&C Act, FDA may clear a PCCP submitted in a 510(k). Generally, under section 513(f)(5) of the FD&C Act, FDA may not withhold a determination of the initial classification of a device under section 513(f)(1) of the FD&C Act because of, among other things, a finding that the facility in which the device is manufactured is not in compliance with the QSR. However, also under section 513(f)(5), for devices subject to 510(k), FDA may withhold a substantial equivalence determination if FDA finds that there is a substantial likelihood that the failure to comply with QSR will potentially present a serious risk to human health. Thus, consistent with sections 515C(b)(2) and 513(f)(5) of the FD&C Act, FDA may under certain case-by-case circumstances withhold clearance of a PCCP submitted in a 510(k) based on findings in the regulatory history of the manufacturer that demonstrate failure to comply with QSR.

For devices subject to 510(k) requirements, the determination of substantial equivalence includes, among other requirements, a comparison between the technological characteristics of the predicate device and the subject device[^56]. In FDA's determination of substantial equivalence, FDA considers the PCCP to be part of the technological characteristics of the device. For 510(k) submissions, in making a determination of substantial equivalence where the predicate device was authorized with a PCCP, the subject device must be compared to the version of the predicate device cleared or approved prior to changes made under the PCCP[^57]. Once a 510(k) for a device that includes modifications that have been implemented consistent with the authorized PCCP has been cleared in a subsequent marketing submission, such device can now serve as an eligible predicate device. The PCCP can be considered during the 510(k) review process at multiple points in the decision tree to address the critical questions in the 510(k) Decision-Making Flowchart[^58]. In general, FDA anticipates that the PCCP will primarily be reviewed after FDA finds that the intended use of the subject device and the predicate device are the same, to help determine whether the devices have different technological characteristics that do not raise different questions of safety and effectiveness[^59].

FDA encourages manufacturers to leverage the [Q-Submission Program](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/requests-feedback-and-meetings-medical-device-submissions-q-submission-program) to obtain FDA feedback on a proposed PCCP for a device and submission type prior to submitting a marketing submission. While manufacturers are encouraged to discuss their plans through a Pre-Submission, FDA does not authorize a PCCP in a Pre-Submission.

## C. Identifying a PCCP in a Marketing Submission

The PCCP should be included as a standalone section within the marketing submission, with a title and version number. Additionally, it should be prominently included and discussed in the cover letter and included in the marketing submission's table of contents as "Predetermined Change Control Plan." The PCCP should be discussed in the marketing submission as part of the device description, labeling, and relevant sections used for the assessment of reasonable assurance of safety and effectiveness or the substantial equivalence comparison. Any information pertaining to the PCCP content included outside of the PCCP section should include appropriate references to the PCCP section.

Device labeling must comply with applicable statutes and regulations[^60]. FDA may require that a device with an authorized PCCP include labeling required for safe and effective use of the device as such device changes pursuant to such plan[^61], excluding, as appropriate, trade secret and confidential commercial information. For AI-DSFs with an authorized PCCP, the labeling should explain that the device incorporates machine learning and has an authorized PCCP so that users are aware that the device may require the user to perform software updates, and that such software updates may modify the device's performance, inputs, or use. Information on the AI-DSF and its authorized PCCP in the labeling is important in order for a user to use the device safely and effectively for the purposes for which it is intended. In particular, information on the device's authorized PCCP may be necessary for a user to understand changes in the device and to continue to use the device safely and effectively across the intended use populations and intended environments as the device changes pursuant to the authorized PCCP.

FDA recommends that the labeling include a statement that the device has an authorized PCCP. When appropriate, including as modifications are implemented consistent with an authorized PCCP, FDA recommends that the labeling related to the PCCP be updated to include the relevant information listed below for the device and the PCCP so that users may be aware of modifications that have been implemented that impact use of the device:

* A description of the implemented modifications, including a summary of current device performance, a description of the relevant data (training, tuning, and test data) as applicable used to implement a modification, associated inputs/outputs, validation requirements, and related evidence;
* A description of how the modifications were implemented; and
* A description of how users will be informed of implemented modifications, including, for example, updated instructions for use or a version history.

When utilizing an authorized PCCP to implement device modifications, the manufacturer should update the labeling for the device as specified in the authorized PCCP[^62].

The PCCP should be described in publicly available device summaries including, for example, the PMA summary of safety and effectiveness document (SSED) and approval order[^63], 510(k) summary[^64],[^65], or De Novo decision summary[^66]. Details of the PCCP should be included in sufficient detail in the public-facing documents to support transparency to users of the assessment of reasonable assurance of safety and effectiveness or the substantial equivalence comparison for the device and the device's specifications, excluding, as appropriate, trade secret and confidential commercial information. In addition, FDA recommends public-facing documents include a summary of the following information regarding the PCCP, as appropriate:

* Planned modifications;
* Testing methods;
* Validation activities and performance requirements to be met in order for modifications to be implemented; and
* Means by which users will be informed of device modifications implemented in accordance with the authorized PCCP.

## D. Utilizing an Authorized PCCP to Implement Device Modifications

FDA expects manufacturers to follow their authorized PCCP, and manufacturers are required to follow applicable legal requirements regarding the device and its authorized PCCP. In general, a PCCP should be evaluated within the existing risk management framework of the device and must be implemented in accordance with the manufacturer's quality system[^67].

Figure 1 depicts the process for implementing a modification to a device with an authorized PCCP. Manufacturers should first consider whether the particular modification is or is not consistent with the authorized PCCP; FDA considers a modification to be consistent with the authorized PCCP when the modification has been specified in the Description of Modifications included in the PCCP and has been implemented in accordance with the Modification Protocol.

If the particular modification is consistent with the authorized PCCP, a new marketing submission is not necessary; the modification can be implemented in accordance with the Modification Protocol, and the manufacturer should document that modification and the analysis in accordance with the manufacturer's quality system.

If the particular modification is not consistent with the authorized PCCP – including if the modification is not included in the authorized PCCP or if the modification is included in the authorized PCCP but is not implemented in accordance with the methods and specifications described in the Modification Protocol – the manufacturer should then proceed to evaluate the particular modification as described below. As part of the review of the particular modification, manufacturers should consider how implementation of the particular modification may affect the PCCP for the device by reviewing the Impact Assessment of the PCCP to determine if the particular modification introduces or significantly modifies risk mitigations for the PCCP.

* If the modification is not included in the authorized PCCP, the manufacturer should proceed based on their evaluation of the particular modification in accordance with applicable FDA statutory and regulatory requirements and after consulting the Device Modifications guidances.
* If the modification is included in the authorized PCCP but is not implemented in accordance with the methods and specifications described in the Modification Protocol, in most cases, because modifications included in a PCCP are those that would generally otherwise require a new marketing submission, it is likely that a new marketing submission will be required before the manufacturer can implement the change[^68].

As described in the introduction of Section V. of this guidance, FDA would consider it to be a deviation from the authorized PCCP in circumstances where the PCCP is not followed or cannot be followed[^69]. Deviations from the authorized PCCP could significantly affect the safety or effectiveness of the device. Significant modifications made to a device that are not specified in, or implemented in accordance with, the authorized PCCP likely require a new marketing submission[^70]. If a manufacturer believes that the deviation from their authorized PCCP is not significant, we strongly encourage discussion with the appropriate FDA review division. In general, manufacturers may contact the appropriate FDA review division for a discussion about a proposed modification and whether it may be considered consistent with the authorized PCCP.

If, after review of applicable FDA statutory and regulatory requirements a new marketing submission is required[^71], the appropriate marketing submission could request authorization for:

* A modification to the authorized PCCP[^72] (see Section V.E. of this guidance); and/or
* The modified device (i.e., a device modification not implemented through a PCCP).

In each of these cases, the marketing submission for the modification must include the appropriate marketing submission requirements[^73] for the device. If the manufacturer requests authorization for a modification to the authorized PCCP, the manufacturer must also submit the proposed, modified PCCP for the device[^74]. If the manufacturer requests authorization for the modified device, the manufacturer must also submit the proposed PCCP for the modified device[^75]. In both scenarios, the manufacturer must obtain FDA authorization for the device and proposed PCCP before implementing the PCCP[^76].

See Appendix B for example scenarios for implementing modifications to an AI-DSF with an authorized PCCP.

(그림 삽입)

**Figure 1: Implementing a Modification to a Device with an Authorized PCCP**


## E. Modifying a Previously Authorized PCCP

FDA believes that modifications to an authorized PCCP will generally constitute changes to the AI-DSF that would otherwise require a new marketing submission[^77]. In other words, FDA anticipates that modifications to a PCCP will need to be reviewed and established as part of the marketing submission for the modified device because a modification to the PCCP will generally significantly affect the safety or effectiveness of the device[^78].

For a manufacturer who would like to modify their PCCP for a previously authorized device with a PCCP[^79], the marketing submission must include the appropriate marketing submission requirements[^80] and the proposed, modified PCCP for the device[^81]. We recommend that manufacturers provide a summary of the changes to the authorized PCCP, and where practicable, a tracked changes version compared to the authorized PCCP. In general, FDA considers the PMA supplement and 510(k) submission types included in Section V.B. of this guidance to be appropriate to modify a PCCP. In addition to those submission types, for devices subject to 510(k) requirements, a special 510(k) submission may be appropriate to modify a PCCP where the modifications to a PCCP comprise changes to the manufacturer's own device and PCCP and where well-established methods are available to evaluate the change to the PCCP[^82].

FDA intends to focus its review on the aspects of the device that are most significantly modified[^83]. For example, if the device has been relatively unchanged since FDA's prior authorization and a modified PCCP is proposed, FDA would focus its review on the modified PCCP. Manufacturers may discuss proposed changes to the PCCP with the appropriate FDA review division through the [Q-Submission Program](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/requests-feedback-and-meetings-medical-device-submissions-q-submission-program).

## F. Version Control and Maintenance of a PCCP for a Device

At this time, as manufacturers gain experience developing and implementing PCCPs, FDA anticipates that review of a marketing submission that includes a PCCP will be interactive. It is possible that a PCCP submitted as part of a marketing submission may need revisions before FDA can make a determination[^84] of reasonable assurance of safety and effectiveness or substantial equivalence in review of the device, including each modification in the PCCP, for the PCCP to be authorized with the device. FDA should work with the manufacturer to revise the PCCP, and will do so using FDA's existing processes to request additional information through interactive review or through a deficiency letter[^85]. If deficiencies with the PCCP remain unresolved, FDA may authorize the device upon withdrawal of the PCCP.

As described in Section V.C. of this guidance, a copy of the PCCP with a title and version number should be included in the marketing submission for the device. If the PCCP is revised during review, such as in response to deficiencies, a final, revised version of the PCCP should be submitted as a clean copy to FDA and should include a title and current version number for the PCCP. FDA authorizes the PCCP as part of the marketing authorization of a device. To that end, the PCCP will be referenced in the device's letter of authorization, including the PCCP title and version number.

Over time, as a manufacturer implements their authorized PCCP for their device, they may wish to make modifications to the device that are not included in their authorized PCCP and that may require a new marketing submission[^86]. If prior modifications have been implemented consistent with the authorized PCCP for the device, the new marketing submission for the device should include a summary of those modifications that have been implemented. This may include information in the device description, labeling, and other relevant sections of the marketing submission so that FDA can understand the current device characteristics and performance. In the context of premarket authorization, FDA does not intend to re-review the adequacy of modifications implemented consistent with an authorized PCCP; however, FDA needs to have an understanding of the current device characteristics and performance in order to make a determination[^87] of reasonable assurance of safety and effectiveness or substantial equivalence. Additionally, if the manufacturer would also like to modify their previously authorized PCCP, the marketing submission must include the appropriate marketing submission requirements[^88] and the proposed, modified PCCP for the device (see Section V.E. of this guidance)[^89].

For devices subject to 510(k) requirements, a manufacturer must compare their subject device to the version of the predicate device cleared or approved prior to changes made under the PCCP[^90]. However, once a 510(k) for a device that includes modifications that have been implemented consistent with the authorized PCCP has been cleared in a subsequent marketing submission, such device can now serve as an eligible predicate device.

[^43]: 21 CFR 807.81(a)(3) and 21 CFR 814.39(a). 21 CFR 807.81(a)(3) 및 21 CFR 814.39(a).

[^44]: Sections 515C(a)(1) and 515C(b)(1) of the FD&C Act, 21 CFR 807.81(a)(3), and 21 CFR 814.39(a). FD&C Act의 섹션 515C(a)(1) 및 515C(b)(1), 21 CFR 807.81(a)(3), 21 CFR 814.39(a).

[^45]: FDA would not consider it to be a deviation from the authorized PCCP in situations where a manufacturer chooses not to implement modifications in their authorized PCCP or where a manufacturer chooses to submit a new marketing submission for a device modification in lieu of using their authorized PCCP. FDA는 제조업체가 승인된 PCCP의 변경사항을 구현하지 않기로 선택하거나 승인된 PCCP를 사용하는 대신 기기 변경에 대한 새로운 마케팅 제출을 하기로 선택하는 상황에서는 승인된 PCCP로부터의 이탈로 간주하지 않습니다.

[^46]: See Section V.D. below for further details on implementing device modifications that may or may not require a new marketing submission in accordance with 21 CFR 807.81(a)(3) and 21 CFR 814.39(a). 21 CFR 807.81(a)(3) 및 21 CFR 814.39(a)에 따라 새로운 마케팅 제출을 요구하거나 요구하지 않을 수 있는 기기 변경사항 구현에 대한 자세한 내용은 아래 섹션 V.D.를 참조하십시오.

[^47]: 21 CFR 807.81(a)(3) and 21 CFR 814.39(a). 21 CFR 807.81(a)(3) 및 21 CFR 814.39(a).

[^48]: See sections 513(f)(2) and 515C of the FD&C Act. FD&C Act의 섹션 513(f)(2) 및 515C를 참조하십시오.

[^49]: This includes marketing authorization for a device and PCCP where the device or a derivative thereof has yet to be introduced into interstate commerce, or marketing authorization for a device or a derivative thereof has been introduced into interstate commerce, and for which is being modified to add a PCCP. 여기에는 기기 또는 그 파생물이 아직 주간 상거래에 도입되지 않은 기기 및 PCCP에 대한 마케팅 승인, 또는 기기 또는 그 파생물이 주간 상거래에 도입되었으며 PCCP를 추가하기 위해 수정되는 기기에 대한 마케팅 승인이 포함됩니다.

[^50]: Section 737(4)(D) of the FD&C Act defines a real-time supplement as "a supplement to an approved premarket application or premarket report under section 515 that requests a minor change to the device, such as a minor change to the design of the device, software, sterilization, or labeling, and for which the applicant has requested and the agency has granted a meeting or similar forum to jointly review and determine the status of the supplement." FD&C Act의 섹션 737(4)(D)는 실시간 보완을 "기기의 설계, 소프트웨어, 멸균 또는 라벨링의 경미한 변경과 같은 기기에 대한 경미한 변경을 요청하는 섹션 515에 따라 승인된 시판 전 신청 또는 시판 전 보고서에 대한 보완으로, 신청자가 요청하고 기관이 보완의 상태를 공동으로 검토하고 결정하기 위한 회의 또는 유사한 포럼을 승인한 것"으로 정의합니다.

[^51]: See FDA's guidance "[Real-Time Premarket Approval Application (PMA) Supplements](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/real-time-premarket-approval-application-pma-supplements)." FDA 가이던스 "[실시간 시판 전 승인 신청(PMA) 보완](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/real-time-premarket-approval-application-pma-supplements)"을 참조하십시오.

[^52]: See FDA's guidance "[The Abbreviated 510(k) Program](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/abbreviated-510k-program)." FDA 가이던스 "[간소화된 510(k) 프로그램](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/abbreviated-510k-program)"을 참조하십시오.

[^53]: See, e.g., sections 513(i)(1) and 515C of the FD&C Act and 21 CFR 860.7. 예를 들어, FD&C Act의 섹션 513(i)(1) 및 515C 및 21 CFR 860.7을 참조하십시오.

[^54]: 21 CFR Part 820. 21 CFR Part 820.

[^55]: Sections 515C(a)(2) and 515C(b)(2) of the FD&C Act, 21 CFR 807.81(a)(3), and 21 CFR 814.39(a). FD&C Act의 섹션 515C(a)(2) 및 515C(b)(2), 21 CFR 807.81(a)(3), 21 CFR 814.39(a).

[^56]: See section 513(i) of the FD&C Act. FD&C Act의 섹션 513(i)를 참조하십시오.

[^57]: See section 515C(c) of the FD&C Act. FD&C Act의 섹션 515C(c)를 참조하십시오.

[^58]: See FDA's guidance "[The 510(k) Program: Evaluating Substantial Equivalence in Premarket Notifications [510(k)]](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/510k-program-evaluating-substantial-equivalence-premarket-notifications-510k)" Appendix A, Decision Points 1 through 4. FDA 가이던스 "[510(k) 프로그램: 시판 전 신고[510(k)]에서 실질적 동등성 평가](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/510k-program-evaluating-substantial-equivalence-premarket-notifications-510k)" 부록 A, 결정 포인트 1부터 4를 참조하십시오.

[^59]: See id. at Decision Points 5a and 5b. 같은 문서의 결정 포인트 5a 및 5b를 참조하십시오.

[^60]: 21 CFR Part 801 (Labeling) and 21 CFR Part 809 (In Vitro Diagnostic Products for Human Use). See, e.g., 21 CFR 801.5 (requiring that labeling include adequate directions for use); 21 CFR 801.109(c) (for prescription devices, requiring that labeling include any relevant hazards, contraindications, side effects, and precautions under which practitioners licensed by law to administer the device can use the device safely and for the purpose for which it is intended); and 21 CFR 809.10(b)(6) (for in vitro diagnostic products, requiring labeling accompanying any instruments use or function, installation procedures, performance characteristics and specifications, service and maintenance information, etc.). 21 CFR Part 801(라벨링) 및 21 CFR Part 809(인간 사용을 위한 체외 진단 제품). 예를 들어, 21 CFR 801.5(라벨링에 적절한 사용 지침 포함 요구); 21 CFR 801.109(c)(처방 기기의 경우, 법적으로 기기를 관리할 수 있는 허가를 받은 실무자가 기기를 안전하게 그리고 의도된 목적에 맞게 사용할 수 있는 관련 위험, 금기사항, 부작용 및 주의사항을 라벨링에 포함하도록 요구); 21 CFR 809.10(b)(6)(체외 진단 제품의 경우, 기구 사용 또는 기능, 설치 절차, 성능 특성 및 사양, 서비스 및 유지보수 정보 등을 포함하는 라벨링 요구)를 참조하십시오.

[^61]: See sections 515C(a)(3), 515C(b)(3), and 513(f)(2) of the FD&C Act. FD&C Act의 섹션 515C(a)(3), 515C(b)(3), 513(f)(2)를 참조하십시오.

[^62]: See Section VII.B.(4) for recommendations on update procedures in a Modification Protocol, which should address how labeling will be updated when modifications are implemented, as appropriate. 변경사항이 구현될 때 라벨링이 어떻게 업데이트될지를 적절히 다루어야 하는 변경사항 프로토콜의 업데이트 절차에 대한 권고사항은 섹션 VII.B.(4)를 참조하십시오.

[^63]: In accordance with 21 CFR 814.9(e), "FDA will make available to the public … a detailed summary of information submitted to FDA respecting the safety and effectiveness of the device that is the subject of the PMA and that is the basis for the order." 21 CFR 814.9(e)에 따라, "FDA는 대중에게 ... PMA의 대상이 되는 기기의 안전성 및 유효성에 관하여 FDA에 제출된 정보의 상세한 요약으로 명령의 근거가 되는 것을 이용 가능하게 할 것입니다."

[^64]: In accordance with 21 CFR 807.92, "a 510(k) summary shall be in sufficient detail to provide an understanding of the basis for a determination of substantial equivalence." This includes, but is not limited to, a description of the device, and for those 510(k) submissions in which a determination of substantial equivalence is also based on an assessment of performance data, non-clinical tests, and clinical tests. 21 CFR 807.92에 따라, "510(k) 요약은 실질적 동등성 결정의 근거에 대한 이해를 제공하기에 충분한 세부사항이 있어야 합니다." 여기에는 기기에 대한 설명과, 실질적 동등성의 결정이 성능 데이터, 비임상 시험 및 임상 시험의 평가에도 기반한 510(k) 제출의 경우가 포함되지만 이에 국한되지 않습니다.

[^65]: If a sponsor chooses to submit a 510(k) Statement rather than a 510(k) Summary, the sponsor should provide to requestors all PCCP information in the 510(k) that supports transparency to users of FDA's determination of substantial equivalence for the device and its specifications, as such information constitutes safety and effectiveness information. See 21 CFR 807.93 for requirements on the content and format of a 510(k) Statement. 스폰서가 510(k) 요약 대신 510(k) 진술서를 제출하기로 선택하는 경우, 스폰서는 요청자에게 기기 및 그 사양에 대한 FDA의 실질적 동등성 결정의 사용자에 대한 투명성을 지원하는 510(k)의 모든 PCCP 정보를 제공해야 하며, 그러한 정보는 안전성 및 유효성 정보를 구성합니다. 510(k) 진술서의 내용 및 형식에 대한 요구사항은 21 CFR 807.93을 참조하십시오.

[^66]: The De Novo decision summary is intended to present an objective and balanced summary of the scientific evidence that served as the basis for the FDA's decision to grant a De Novo request; see FDA's website on [De Novo Classification Request](https://www.fda.gov/medical-devices/premarket-submissions-selecting-and-preparing-correct-submission/de-novo-classification-request). De Novo 결정 요약은 FDA가 De Novo 요청을 승인하기로 결정한 근거가 된 과학적 증거의 객관적이고 균형 잡힌 요약을 제시하기 위한 것입니다. FDA 웹사이트 [De Novo 분류 요청](https://www.fda.gov/medical-devices/premarket-submissions-selecting-and-preparing-correct-submission/de-novo-classification-request)을 참조하십시오.

[^67]: Manufacturers are required to comply with the QSR (21 CFR Part 820). The device and PCCP must be implemented consistent with 21 CFR Part 820, including, but not limited to design controls (21 CFR 820.30), nonconforming products (21 CFR 820.90), and corrective and preventative action (21 CFR 820.100). The QSR also includes requirements to review and approve modifications to device design and production (21 CFR 820.30 and 820.70), and requirements to document changes and approvals in the device master record (21 CFR 820.181). 제조업체는 QSR(21 CFR Part 820)을 준수해야 합니다. 기기 및 PCCP는 설계 관리(21 CFR 820.30), 부적합 제품(21 CFR 820.90), 시정 및 예방 조치(21 CFR 820.100)를 포함하되 이에 국한되지 않고 21 CFR Part 820과 일치하게 구현되어야 합니다. QSR은 또한 기기 설계 및 생산에 대한 수정을 검토하고 승인하는 요구사항(21 CFR 820.30 및 820.70)과 기기 마스터 기록에 변경 및 승인을 문서화하는 요구사항(21 CFR 820.181)을 포함합니다.

[^68]: 21 CFR 807.81(a)(3) and 21 CFR 814.39(a). 21 CFR 807.81(a)(3) 및 21 CFR 814.39(a).

[^69]: FDA would not consider it to be a deviation from the authorized PCCP in situations where a manufacturer chooses not to implement modifications in their authorized PCCP or where a manufacturer chooses to submit a new marketing submission for a device modification in lieu of using their authorized PCCP. FDA는 제조업체가 승인된 PCCP의 변경사항을 구현하지 않기로 선택하거나 승인된 PCCP를 사용하는 대신 기기 변경에 대한 새로운 마케팅 제출을 하기로 선택하는 상황에서는 승인된 PCCP로부터의 이탈로 간주하지 않습니다.

[^70]: 21 CFR 807.81(a)(3) and 21 CFR 814.39(a). 21 CFR 807.81(a)(3) 및 21 CFR 814.39(a).

[^71]: 21 CFR 807.81(a)(3) and 21 CFR 814.39(a). 21 CFR 807.81(a)(3) 및 21 CFR 814.39(a).

[^72]: A change to the authorized PCCP could include a change in the Description of Modifications, the Modification Protocol, and/or the Impact Assessment, as appropriate. 승인된 PCCP에 대한 변경은 적절한 경우 변경사항 설명, 변경사항 프로토콜 및/또는 영향 평가의 변경을 포함할 수 있습니다.

[^73]: See, e.g., 21 CFR 807.87, 21 CFR 860.220, or 21 CFR 814.20. In general, manufacturers may provide references in the marketing submission to prior marketing submissions for content that remains unchanged, as appropriate. 예를 들어, 21 CFR 807.87, 21 CFR 860.220 또는 21 CFR 814.20을 참조하십시오. 일반적으로, 제조업체는 적절한 경우 변경되지 않은 내용에 대해 마케팅 제출에서 이전 마케팅 제출에 대한 참조를 제공할 수 있습니다.

[^74]: Sections 515C(a)(2) and 515C(b)(2) of the FD&C Act. FD&C Act의 섹션 515C(a)(2) 및 515C(b)(2).

[^75]: Sections 515C(a)(2) and 515C(b)(2) of the FD&C Act. FD&C Act의 섹션 515C(a)(2) 및 515C(b)(2).

[^76]: Section 515C of the FD&C Act, 21 CFR 807.81(a)(3), and 21 CFR 814.39(a). FD&C Act의 섹션 515C, 21 CFR 807.81(a)(3), 21 CFR 814.39(a).

[^77]: Section 515C(a)(2) and 515C(b)(2) of the FD&C Act, 21 CFR 807.81(a)(3), and 21 CFR 814.39(a). FD&C Act의 섹션 515C(a)(2) 및 515C(b)(2), 21 CFR 807.81(a)(3), 21 CFR 814.39(a).

[^78]: Section 515C(a)(2) and 515C(b)(2) of the FD&C Act, 21 CFR 807.81(a)(3), and 21 CFR 814.39(a). FD&C Act의 섹션 515C(a)(2) 및 515C(b)(2), 21 CFR 807.81(a)(3), 21 CFR 814.39(a).

[^79]: E.g., through a PMA supplement or a traditional 510(k) for a device that has already been authorized. 예를 들어, 이미 승인된 기기에 대한 PMA 보완 또는 전통적인 510(k)을 통해.

[^80]: See, e.g., 21 CFR 807.87, 21 CFR 860.220, or 21 CFR 814.20. In cases where the modified PCCP is the reason for the marketing submission, and in general, manufacturers may provide references in the marketing submission to prior marketing submissions for content that remains unchanged, as appropriate. 예를 들어, 21 CFR 807.87, 21 CFR 860.220 또는 21 CFR 814.20을 참조하십시오. 수정된 PCCP가 마케팅 제출의 이유인 경우, 그리고 일반적으로, 제조업체는 적절한 경우 변경되지 않은 내용에 대해 마케팅 제출에서 이전 마케팅 제출에 대한 참조를 제공할 수 있습니다.

[^81]: Sections 515C(a)(2) and 515C(b)(2) of the FD&C Act. FD&C Act의 섹션 515C(a)(2) 및 515C(b)(2).

[^82]: See FDA's guidance "[The Special 510(k) Program](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/special-510k-program)." FDA 가이던스 "[특별 510(k) 프로그램](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/special-510k-program)"을 참조하십시오.

[^83]: Note that "focus of the review" is not intended to imply a review of the PCCP only; rather, the focus on the PCCP is as a significant change to the device that could affect the safety or effectiveness of the device. "검토의 초점"은 PCCP만의 검토를 의미하는 것이 아니라, PCCP에 대한 초점은 기기의 안전성 또는 유효성에 영향을 미칠 수 있는 기기에 대한 중대한 변경으로서라는 점에 유의하십시오.

[^84]: See, e.g., sections 513(i)(1) and 515C of the FD&C Act and 21 CFR 860.7. 예를 들어, FD&C Act의 섹션 513(i)(1) 및 515C 및 21 CFR 860.7을 참조하십시오.

[^85]: See FDA's guidance, "[Developing and Responding to Deficiencies in Accordance with the Least Burdensome Provisions](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/developing-and-responding-deficiencies-accordance-least-burdensome-provisions)." FDA 가이던스 "[최소 부담 조항에 따른 결함 개발 및 대응](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/developing-and-responding-deficiencies-accordance-least-burdensome-provisions)"을 참조하십시오.

[^86]: 21 CFR 807.81(a)(3) and 21 CFR 814.39(a). 21 CFR 807.81(a)(3) 및 21 CFR 814.39(a).

[^87]: See, e.g., sections 513(i)(1) and 515C of the FD&C Act and 21 CFR 860.7. 예를 들어, FD&C Act의 섹션 513(i)(1) 및 515C 및 21 CFR 860.7을 참조하십시오.

[^88]: See, e.g., 21 CFR 807.87, 21 CFR 860.220, or 21 CFR 814.20. In general, manufacturers may provide references in the marketing submission to prior marketing submissions for content that remains unchanged, as appropriate. 예를 들어, 21 CFR 807.87, 21 CFR 860.220 또는 21 CFR 814.20을 참조하십시오. 일반적으로, 제조업체는 적절한 경우 변경되지 않은 내용에 대해 마케팅 제출에서 이전 마케팅 제출에 대한 참조를 제공할 수 있습니다.

[^89]: Sections 515C(a)(2) and 515C(b)(2) of the FD&C Act. FD&C Act의 섹션 515C(a)(2) 및 515C(b)(2).

[^90]: Section 515C(c) of the FD&C Act. FD&C Act의 섹션 515C(c).

# V. 사전결정 변경관리계획에 대한 정책

소프트웨어 개발은 반복적인 과정이며, FDA는 기기 소프트웨어 기능의 제조업체가 자사 기기를 지속적으로 개선하고 업데이트하기 위해 노력한다는 것을 인정한다. 제조업체는 자사 기기의 수정사항의 영향을 평가해야 하며, 기기 수정사항이 기기의 의도된 용도에 영향을 미치거나 기기의 안전성 또는 효과성에 상당한 영향을 미칠 수 있는 경우 일반적으로 시판 신청서를 제출해야 한다[^43].

승인된 PCCP는 PCCP에 포함되지 않은 경우 그렇지 않으면 21 CFR 807.81(a)(3) 및 21 CFR 814.39(a)에 따라, 그리고 기기 수정 가이던스와 일치하게 새로운 시판 신청서를 요구할 수 있는 계획된 수정사항을 명시한다. 승인된 PCCP는 본 가이던스의 섹션 VI.부터 VIII.까지에서 더 자세히 설명될 다음 섹션을 포함해야 한다:

* **수정사항 설명(섹션 VI.)** – 기기에 대한 계획된 수정사항의 특성 및 성능에 대한 사양;
* **수정 프로토콜(섹션 VII.)** – 계획된 수정사항을 지원하고 의도된 사용 집단 전체에서 기기가 안전하고 효과적으로 유지되도록 보장하기 위한 관련 검증 및 확인 테스트 활동 및 수용 기준; 그리고
* **영향 평가(섹션 VIII.)** – PCCP 구현의 편익과 위험에 대한 평가 및 위험 완화 계획.

승인된 PCCP에 따라 명시되고 구현된 수정사항은 PCCP를 포함하는 시판 신청서를 통해 검토되고 승인되었기 때문에, 수정사항은 새로운 시판 신청서의 필요성을 유발하지 않고 AI-DSF에 구현될 수 있다[^44].

FDA는 PCCP가 준수되지 않거나 준수될 수 없는 상황에서 승인된 PCCP로부터의 이탈로 간주할 것이다[^45]. 승인된 PCCP로부터의 이탈은 기기의 안전성 또는 효과성에 상당한 영향을 미칠 수 있다. 여기에는 예를 들어 데이터 관리 또는 재훈련 실패, 또는 사전 명시된 성능 기준을 충족하지 못하는 것과 같은 수정 프로토콜과 관련된 문제가 포함될 수 있다. 시판 신청서를 요구하지 않는 기기 수정사항은 승인된 PCCP로부터의 이탈로 간주되지 않을 것이다[^46]. 그러나 승인된 PCCP에 명시되지 않았거나 승인된 PCCP에 따라 구현되지 않은 AI-DSF에 대한 중요한 수정사항은 수정사항을 구현하기 전에 새로운 시판 신청서를 요구할 가능성이 높다[^47]. 시판 신청서에서 검토된 승인된 PCCP로부터의 이탈은 일반적으로 FD&C Act의 섹션 501(f)(1) 및 502(o)에 따라 기기가 불량품이 되고 잘못된 상표가 붙게 한다. FD&C Act의 섹션 301(a)에 따라 불량품이거나 잘못된 상표가 붙은 식품, 의약품, 기기, 담배 제품 또는 화장품을 주간 통상에 도입하거나 도입을 위해 인도하는 것은 금지되며, 적절한 경우 FDA는 압수 또는 금지명령을 포함하되 이에 국한되지 않는 금지된 행위의 위반에 대해 법적 또는 규제 조치를 취할 수 있다.

## A. PCCP의 구성요소

PCCP는 이러한 구성요소가 제안된 수정사항에 대한 FDA의 검토를 가능하게 하는 정보를 제공하기 위한 것이므로 상세한 수정사항 설명, 수정 프로토콜 및 영향 평가(본 가이던스의 섹션 VI. – VIII. 참조)로 구성되어야 한다. PCCP를 개발할 때, 제조업체는 기기가 수정됨에 따라 기기가 이러한 집단 및 환경을 계속 반영하도록 의도된 사용 집단(인종, 민족, 질병 중증도, 성별, 연령 또는 적절한 경우 기타 특성과 관련하여) 및 의도된 사용 환경을 고려해야 한다. 상세한 수정사항 설명은 AI-DSF에 대해 수행될 수 있는 구체적이고 계획된 수정사항을 개괄해야 한다. 여기에는 기기에 대한 계획된 수정사항의 특성 및 성능에 대한 사양을 정의하는 것이 포함된다. 수정 프로토콜은 의도된 사용 집단 전체에서 기기가 안전하고 효과적으로 유지되도록 보장하기 위해 각 수정사항을 지원할 사전 정의된 수용 기준을 포함한 검증 및 확인 활동을 설명해야 한다. 영향 평가는 영향 평가가 명시된 계획된 수정사항에 의해 도입된 편익과 위험을 식별하고 수정 프로토콜의 검증 및 확인 활동이 기기의 안전성과 효과성을 계속 보장할 방법을 다루는 점에서 수정사항 설명을 수정 프로토콜에 연결하는 데 도움이 된다. 상세한 수정사항 설명, 수정 프로토콜 및 영향 평가는 모두 PCCP의 상호 관련된 구성요소이다. 부록은 PCCP의 수정 프로토콜의 권장 내용에 대한 상세한 질문 및 고려사항(부록 A)과 AI-DSF에 대한 PCCP를 사용하는 예시 시나리오(부록 B)를 포함하여 본 가이던스의 권고사항을 구현하는 데 도움이 되는 주요 정보를 제공한다.

## B. PCCP 수립

PCCP가 있는 AI-DSF에 대한 시판 전 승인은 PCCP가 제조업체가 해당 PCCP에 따라 수정사항을 구현하기 전에 기기에 대한 시판 승인[^48],[^49]의 일부로서 검토되고 수립되어야 하므로, 적절하게 PMA 경로, 510(k) 경로 또는 De Novo 경로를 통해 수립되어야 한다. 이에 따라, FDA가 긍정적인 결정(즉, 승인)을 내리지 않는 신청 유형은 PCCP를 수립하기에 적절하지 않을 것이다. 일반적으로 FDA는 다음 신청 유형이 PCCP를 수립하기에 적절하다고 고려한다:

**PMA 요건의 적용을 받는 AI-DSF의 경우:**

* 최초 PMA 신청서
* 모듈형 PMA 신청서, 여기서 PCCP가 검토 모듈을 구성함
* 180일 PMA 보완
* 패널 트랙 PMA 보완
* 실시간 PMA 보완, 여기서 PCCP가 경미한 변경사항을 구성하고 제조업체와 FDA가 검토가 실시간 환경에서 달성될 수 있다는 데 동의함[^50],[^51]

**510(k) 요건의 적용을 받는 AI-DSF의 경우:**

* 전통적인 510(k) 신청서
* 약식 510(k) 신청서[^52]

**De Novo 요건의 적용을 받는 AI-DSF의 경우:**

* 최초 De Novo 요청

PCCP는 기기 시판 승인의 일부로서 승인된다. FDA는 PCCP가 기기와 함께 승인되기 위해 PCCP에 명시된 각 수정사항을 포함하여 기기에 대한 검토에서 안전성과 효과성에 대한 합리적인 보증 또는 실질적 동등성의 판단[^53]에 도달해야 한다.

제조업체가 승인된 PCCP에 포함된 수정사항을 구현함에 따라, FDA는 제조업체가 승인된 PCCP와 일치하게, 즉 수정 프로토콜에 따라 수정사항을 구현할 것으로 기대한다. 제조업체는 품질 시스템에 따라 모든 변경사항을 구현해야 한다[^54]. 제조업체의 품질 시스템은 기기에 대한 변경 관리 프로세스에 매우 중요하며, 특히 PCCP를 포함하는 기기의 경우 더욱 그러한데, PCCP에는 일반적으로 그렇지 않으면 새로운 시판 신청서를 요구하는 수정사항이 포함되기 때문이다[^55]. QSR 준수는 제조업체가 승인된 PCCP와 일치하게 수정사항을 구현하기 위해 필수적이며 그렇게 하지 않으면 잠재적으로 인간 건강에 심각한 위험을 초래할 수 있다.

FD&C Act의 섹션 515C(a)(2)에 따라, FDA는 PMA에 제출된 PCCP를 승인할 수 있다. FD&C Act의 섹션 515(d)(2)(C)에 따라, FDA는 해당 기기의 제조, 가공, 포장 또는 설치에 사용되는 방법, 또는 사용되는 시설 또는 관리가 QSR 요건을 준수하지 않는다고 판단하는 경우 PMA의 승인을 거부해야 한다. 따라서 FD&C Act의 섹션 515C(a)(2) 및 515(d)(2)(C)와 일치하게, FDA는 대상 기기의 제조, 가공, 포장 또는 설치에 사용되는 방법, 또는 사용되는 시설 또는 관리가 QSR 요건을 준수하지 않는다고 판단하는 경우 PMA에 제출된 PCCP의 승인을 거부해야 한다.

FD&C Act의 섹션 515C(b)(2)에 따라, FDA는 510(k)에 제출된 PCCP를 허가할 수 있다. 일반적으로 FD&C Act의 섹션 513(f)(5)에 따라, FDA는 특히 기기가 제조되는 시설이 QSR을 준수하지 않는다는 판단 때문에 FD&C Act의 섹션 513(f)(1)에 따른 기기의 최초 분류 판단을 보류할 수 없다. 그러나 또한 섹션 513(f)(5)에 따라, 510(k)의 적용을 받는 기기의 경우, FDA는 QSR 준수 실패가 잠재적으로 인간 건강에 심각한 위험을 초래할 상당한 가능성이 있다고 판단하는 경우 실질적 동등성 판단을 보류할 수 있다. 따라서 FD&C Act의 섹션 515C(b)(2) 및 513(f)(5)와 일치하게, FDA는 QSR 준수 실패를 입증하는 제조업체의 규제 이력의 판단에 기반하여 특정 사례별 상황에서 510(k)에 제출된 PCCP의 허가를 보류할 수 있다.

510(k) 요건의 적용을 받는 기기의 경우, 실질적 동등성 판단에는 특히 선행 기기와 대상 기기의 기술적 특성 간의 비교가 포함된다[^56]. FDA의 실질적 동등성 판단에서, FDA는 PCCP를 기기의 기술적 특성의 일부로 고려한다. 510(k) 신청서의 경우, 선행 기기가 PCCP와 함께 승인된 경우 실질적 동등성을 판단함에 있어, 대상 기기는 PCCP에 따라 변경이 이루어지기 전에 허가 또는 승인된 버전의 선행 기기와 비교되어야 한다[^57]. 승인된 PCCP와 일치하게 구현된 수정사항을 포함하는 기기에 대한 510(k)가 후속 시판 신청서에서 허가되면, 그러한 기기는 이제 적격 선행 기기로 사용될 수 있다. PCCP는 510(k) 의사결정 흐름도의 중요한 질문을 다루기 위해 의사결정 트리의 여러 지점에서 510(k) 검토 프로세스 중에 고려될 수 있다[^58]. 일반적으로 FDA는 PCCP가 대상 기기와 선행 기기의 의도된 용도가 동일하다고 FDA가 판단한 후 주로 검토될 것으로 예상하며, 기기가 안전성과 효과성에 대한 다른 질문을 제기하지 않는 다른 기술적 특성을 가지고 있는지 여부를 판단하는 데 도움이 된다[^59].

FDA는 제조업체가 시판 신청서를 제출하기 전에 기기 및 신청 유형에 대한 제안된 PCCP에 대한 FDA 피드백을 얻기 위해 Q-제출 프로그램을 활용할 것을 권장한다. 제조업체는 사전 제출을 통해 계획을 논의할 것을 권장하지만, FDA는 사전 제출에서 PCCP를 승인하지 않는다.

## C. 시판 신청서에서 PCCP 식별

PCCP는 제목과 버전 번호가 있는 시판 신청서 내의 독립적인 섹션으로 포함되어야 한다. 또한, 표지 편지에 눈에 띄게 포함되고 논의되어야 하며 시판 신청서의 목차에 "사전결정 변경관리계획"으로 포함되어야 한다. PCCP는 기기 설명, 라벨링, 그리고 안전성과 효과성에 대한 합리적인 보증의 평가 또는 실질적 동등성 비교에 사용되는 관련 섹션의 일부로서 시판 신청서에서 논의되어야 한다. PCCP 섹션 외부에 포함된 PCCP 내용과 관련된 모든 정보는 PCCP 섹션에 대한 적절한 참조를 포함해야 한다.

기기 라벨링은 적용 가능한 법령 및 규정을 준수해야 한다[^60]. FDA는 승인된 PCCP가 있는 기기가 적절하게 영업 비밀 및 기밀 상업 정보를 제외하고, 해당 계획에 따라 기기가 변경됨에 따라 기기의 안전하고 효과적인 사용에 필요한 라벨링을 포함하도록 요구할 수 있다[^61]. 승인된 PCCP가 있는 AI-DSF의 경우, 라벨링은 사용자가 기기가 소프트웨어 업데이트를 수행해야 할 수 있으며 그러한 소프트웨어 업데이트가 기기의 성능, 입력 또는 사용을 수정할 수 있다는 것을 인식하도록 기기가 머신러닝을 통합하고 승인된 PCCP를 가지고 있음을 설명해야 한다. 라벨링의 AI-DSF 및 승인된 PCCP에 대한 정보는 사용자가 기기를 의도된 목적에 맞게 안전하고 효과적으로 사용하기 위해 중요하다. 특히, 기기의 승인된 PCCP에 대한 정보는 사용자가 기기의 변경사항을 이해하고 기기가 승인된 PCCP에 따라 변경됨에 따라 의도된 사용 집단 및 의도된 환경 전체에서 기기를 계속 안전하고 효과적으로 사용하는 데 필요할 수 있다.

FDA는 라벨링에 기기가 승인된 PCCP를 가지고 있다는 진술을 포함할 것을 권장한다. 승인된 PCCP와 일치하게 수정사항이 구현될 때를 포함하여 적절한 경우, FDA는 사용자가 기기 사용에 영향을 미치는 구현된 수정사항을 인식할 수 있도록 기기 및 PCCP에 대한 아래 나열된 관련 정보를 포함하도록 PCCP와 관련된 라벨링을 업데이트할 것을 권장한다:

* 현재 기기 성능의 요약, 수정사항을 구현하는 데 사용된 관련 데이터(훈련, 튜닝 및 테스트 데이터)의 설명(해당되는 경우), 관련 입력/출력, 검증 요건 및 관련 증거를 포함한 구현된 수정사항에 대한 설명;
* 수정사항이 어떻게 구현되었는지에 대한 설명; 그리고
* 예를 들어 업데이트된 사용 지침 또는 버전 이력을 포함하여 사용자가 구현된 수정사항에 대해 어떻게 통보받을 것인지에 대한 설명.

승인된 PCCP를 활용하여 기기 수정사항을 구현할 때, 제조업체는 승인된 PCCP에 명시된 대로 기기에 대한 라벨링을 업데이트해야 한다[^62].

PCCP는 예를 들어 PMA 안전성 및 효과성 요약 문서(SSED) 및 승인 명령[^63], 510(k) 요약[^64],[^65], 또는 De Novo 결정 요약[^66]을 포함한 공개적으로 이용 가능한 기기 요약에 설명되어야 한다. PCCP의 세부사항은 적절하게 영업 비밀 및 기밀 상업 정보를 제외하고, 기기에 대한 안전성과 효과성에 대한 합리적인 보증의 평가 또는 실질적 동등성 비교 및 기기의 사양의 사용자에 대한 투명성을 지원하기에 충분한 세부사항으로 공개 문서에 포함되어야 한다. 또한, FDA는 공개 문서가 적절하게 PCCP에 관한 다음 정보의 요약을 포함할 것을 권장한다:

* 계획된 수정사항;
* 테스트 방법;
* 수정사항이 구현되기 위해 충족되어야 하는 검증 활동 및 성능 요건; 그리고
* 승인된 PCCP에 따라 구현된 기기 수정사항에 대해 사용자가 통보받을 수단.

## D. 승인된 PCCP를 활용하여 기기 수정사항 구현

FDA는 제조업체가 승인된 PCCP를 따르기를 기대하며, 제조업체는 기기 및 승인된 PCCP에 관한 적용 가능한 법적 요건을 따라야 한다. 일반적으로 PCCP는 기기의 기존 위험 관리 프레임워크 내에서 평가되어야 하며 제조업체의 품질 시스템에 따라 구현되어야 한다[^67].

그림 1은 승인된 PCCP가 있는 기기에 대한 수정사항을 구현하는 프로세스를 나타낸다. 제조업체는 먼저 특정 수정사항이 승인된 PCCP와 일치하는지 여부를 고려해야 한다; FDA는 수정사항이 PCCP에 포함된 수정사항 설명에 명시되었고 수정 프로토콜에 따라 구현된 경우 수정사항이 승인된 PCCP와 일치한다고 간주한다.

특정 수정사항이 승인된 PCCP와 일치하는 경우, 새로운 시판 신청서가 필요하지 않다; 수정사항은 수정 프로토콜에 따라 구현될 수 있으며, 제조업체는 제조업체의 품질 시스템에 따라 해당 수정사항 및 분석을 문서화해야 한다.

특정 수정사항이 승인된 PCCP와 일치하지 않는 경우 – 수정사항이 승인된 PCCP에 포함되지 않은 경우 또는 수정사항이 승인된 PCCP에 포함되어 있지만 수정 프로토콜에 설명된 방법 및 사양에 따라 구현되지 않은 경우를 포함하여 – 제조업체는 아래 설명된 대로 특정 수정사항을 평가하도록 진행해야 한다. 특정 수정사항의 검토의 일부로서, 제조업체는 PCCP의 영향 평가를 검토하여 특정 수정사항이 PCCP에 대한 위험 완화를 도입하거나 상당히 수정하는지 여부를 판단함으로써 특정 수정사항의 구현이 기기에 대한 PCCP에 어떻게 영향을 미칠 수 있는지 고려해야 한다.

* 수정사항이 승인된 PCCP에 포함되지 않은 경우, 제조업체는 적용 가능한 FDA 법적 및 규제 요건에 따라 특정 수정사항에 대한 평가를 기반으로 진행해야 하며 기기 수정 가이던스를 참조한 후 진행해야 한다.
* 수정사항이 승인된 PCCP에 포함되어 있지만 수정 프로토콜에 설명된 방법 및 사양에 따라 구현되지 않은 경우, 대부분의 경우 PCCP에 포함된 수정사항은 일반적으로 그렇지 않으면 새로운 시판 신청서를 요구하는 것이므로, 제조업체가 변경사항을 구현하기 전에 새로운 시판 신청서가 요구될 가능성이 높다[^68].

본 가이던스의 섹션 V의 서론에서 설명한 바와 같이, FDA는 PCCP가 준수되지 않거나 준수될 수 없는 상황에서 승인된 PCCP로부터의 이탈로 간주할 것이다[^69]. 승인된 PCCP로부터의 이탈은 기기의 안전성 또는 효과성에 상당한 영향을 미칠 수 있다. 승인된 PCCP에 명시되지 않았거나 승인된 PCCP에 따라 구현되지 않은 기기에 대한 중요한 수정사항은 새로운 시판 신청서를 요구할 가능성이 높다[^70]. 제조업체가 승인된 PCCP로부터의 이탈이 중요하지 않다고 판단하는 경우, 적절한 FDA 심사 부서와의 논의를 강력히 권장한다. 일반적으로 제조업체는 제안된 수정사항 및 그것이 승인된 PCCP와 일치하는 것으로 간주될 수 있는지 여부에 대한 논의를 위해 적절한 FDA 심사 부서에 연락할 수 있다.

적용 가능한 FDA 법적 및 규제 요건의 검토 후 새로운 시판 신청서가 요구되는 경우[^71], 적절한 시판 신청서는 다음에 대한 승인을 요청할 수 있다:

* 승인된 PCCP에 대한 수정사항[^72](본 가이던스의 섹션 V.E. 참조); 및/또는
* 수정된 기기(즉, PCCP를 통해 구현되지 않은 기기 수정사항).

이러한 각 경우에, 수정사항에 대한 시판 신청서는 기기에 대한 적절한 시판 신청서 요건[^73]을 포함해야 한다. 제조업체가 승인된 PCCP에 대한 수정사항에 대한 승인을 요청하는 경우, 제조업체는 또한 기기에 대한 제안된 수정된 PCCP를 제출해야 한다[^74]. 제조업체가 수정된 기기에 대한 승인을 요청하는 경우, 제조업체는 또한 수정된 기기에 대한 제안된 PCCP를 제출해야 한다[^75]. 두 시나리오 모두에서, 제조업체는 PCCP를 구현하기 전에 기기 및 제안된 PCCP에 대한 FDA 승인을 받아야 한다[^76].

승인된 PCCP가 있는 AI-DSF에 대한 수정사항을 구현하는 예시 시나리오는 부록 B를 참조하라.

(그림 삽입)

**그림 1: 승인된 PCCP가 있는 기기에 대한 수정사항 구현**

## E. 이전에 승인된 PCCP 수정

FDA는 승인된 PCCP에 대한 수정사항이 일반적으로 그렇지 않으면 새로운 시판 신청서를 요구하는 AI-DSF에 대한 변경사항을 구성할 것이라고 판단한다[^77]. 즉, FDA는 PCCP에 대한 수정사항이 PCCP에 대한 수정사항이 일반적으로 기기의 안전성 또는 효과성에 상당한 영향을 미치기 때문에 수정된 기기에 대한 시판 신청서의 일부로서 검토되고 수립되어야 할 것으로 예상한다[^78].

PCCP가 있는 이전에 승인된 기기에 대해 PCCP를 수정하고자 하는 제조업체[^79]의 경우, 시판 신청서는 적절한 시판 신청서 요건[^80] 및 기기에 대한 제안된 수정된 PCCP를 포함해야 한다[^81]. 제조업체가 승인된 PCCP에 대한 변경사항의 요약을 제공하고, 실행 가능한 경우 승인된 PCCP와 비교한 변경사항 추적 버전을 제공할 것을 권장한다. 일반적으로 FDA는 본 가이던스의 섹션 V.B.에 포함된 PMA 보완 및 510(k) 신청 유형이 PCCP를 수정하기에 적절하다고 고려한다. 이러한 신청 유형 외에도, 510(k) 요건의 적용을 받는 기기의 경우, PCCP에 대한 수정사항이 제조업체 자신의 기기 및 PCCP에 대한 변경사항을 구성하고 PCCP에 대한 변경사항을 평가하기 위한 잘 수립된 방법이 이용 가능한 경우 특별 510(k) 신청서가 PCCP를 수정하기에 적절할 수 있다[^82].

FDA는 가장 중요하게 수정된 기기의 측면에 검토를 집중할 의도이다[^83]. 예를 들어, 기기가 FDA의 이전 승인 이후 비교적 변경되지 않았고 수정된 PCCP가 제안된 경우, FDA는 수정된 PCCP에 검토를 집중할 것이다. 제조업체는 Q-제출 프로그램을 통해 적절한 FDA 심사 부서와 PCCP에 대한 제안된 변경사항을 논의할 수 있다.

## F. 기기에 대한 PCCP의 버전 관리 및 유지

현재 제조업체가 PCCP를 개발하고 구현하는 경험을 쌓고 있으므로, FDA는 PCCP를 포함하는 시판 신청서의 검토가 상호작용적일 것으로 예상한다. 시판 신청서의 일부로 제출된 PCCP가 PCCP의 각 수정사항을 포함하여 기기에 대한 검토에서 안전성과 효과성에 대한 합리적인 보증 또는 실질적 동등성의 판단[^84]을 FDA가 내릴 수 있기 전에 수정이 필요할 수 있다. FDA는 제조업체와 협력하여 PCCP를 수정해야 하며, 상호작용적 검토를 통해 또는 결함 서한을 통해 추가 정보를 요청하는 FDA의 기존 프로세스를 사용하여 그렇게 할 것이다[^85]. PCCP에 대한 결함이 해결되지 않은 상태로 남아 있는 경우, FDA는 PCCP의 철회 시 기기를 승인할 수 있다.

본 가이던스의 섹션 V.C.에서 설명한 바와 같이, 제목과 버전 번호가 있는 PCCP의 사본이 기기에 대한 시판 신청서에 포함되어야 한다. 결함에 대한 응답과 같이 검토 중에 PCCP가 수정되는 경우, PCCP의 최종 수정 버전은 깨끗한 사본으로 FDA에 제출되어야 하며 PCCP에 대한 제목과 현재 버전 번호를 포함해야 한다. FDA는 기기의 시판 승인의 일부로서 PCCP를 승인한다. 그 목적을 위해, PCCP는 PCCP 제목 및 버전 번호를 포함하여 기기의 승인 서한에서 참조될 것이다.

시간이 지남에 따라, 제조업체가 자사 기기에 대한 승인된 PCCP를 구현함에 따라, 그들은 승인된 PCCP에 포함되지 않고 새로운 시판 신청서를 요구할 수 있는 기기에 대한 수정사항을 원할 수 있다[^86]. 기기에 대한 승인된 PCCP와 일치하게 이전 수정사항이 구현된 경우, 기기에 대한 새로운 시판 신청서는 구현된 해당 수정사항의 요약을 포함해야 한다. 여기에는 FDA가 현재 기기 특성 및 성능을 이해할 수 있도록 기기 설명, 라벨링 및 시판 신청서의 기타 관련 섹션의 정보가 포함될 수 있다. 시판 전 승인의 맥락에서, FDA는 승인된 PCCP와 일치하게 구현된 수정사항의 적절성을 재검토할 의도가 없다; 그러나 FDA는 안전성과 효과성에 대한 합리적인 보증 또는 실질적 동등성의 판단[^87]을 내리기 위해 현재 기기 특성 및 성능에 대한 이해가 필요하다. 또한, 제조업체가 이전에 승인된 PCCP를 수정하고자 하는 경우, 시판 신청서는 적절한 시판 신청서 요건[^88] 및 기기에 대한 제안된 수정된 PCCP를 포함해야 한다(본 가이던스의 섹션 V.E. 참조)[^89].

510(k) 요건의 적용을 받는 기기의 경우, 제조업체는 PCCP에 따라 변경이 이루어지기 전에 허가 또는 승인된 버전의 선행 기기와 대상 기기를 비교해야 한다[^90]. 그러나 승인된 PCCP와 일치하게 구현된 수정사항을 포함하는 기기에 대한 510(k)가 후속 시판 신청서에서 허가되면, 그러한 기기는 이제 적격 선행 기기로 사용될 수 있다.

# VI. Description of Modifications
A description of each planned modification to an AI-DSF should be included in the Description of Modifications section of a PCCP. The detailed description should describe specific changes to the device characteristics and performance resulting from implementation of the modifications. To ensure an efficient review, FDA recommends that a PCCP include only a limited number of modifications that are specific, and that can be verified and validated.

The Appendices provide key information to help manufacturers implement the recommendations in this guidance, including example modifications, as well as scenarios for employing an authorized PCCP for an AI-DSF (Appendix B).

## A. Goals of the Description of Modifications Section

A dedicated Description of Modifications section in a PCCP should identify the specific, planned modifications to the AI-DSF that the manufacturer intends to implement. The Description of Modifications should include the specifications for the characteristics and performance of the device that, following the agreed upon verification and validation described in the Modification Protocol, can be implemented without a new marketing submission.

## B. Content of the Description of Modifications Section

To achieve these goals, FDA recommends that the Description of Modifications enumerate the list of individual proposed device modifications discussed in the PCCP, as well as the specific rationale for the change to each part of the AI-DSF that is planned to be modified. In some situations, a Description of Modifications may consist of multiple modifications. It may be helpful to reference the labeling sections that are anticipated to be impacted for each modification in the Description of Modifications section (such labeling changes for each modification should be included in the Modification Protocol, as described in Section VII.B.(4) of this guidance).

FDA recommends that a PCCP include modifications that are specific, and that can be verified and validated. Modifications should also be presented at a level of detail that permits understanding of the specific modifications that will be made to the AI-DSF. Each modification should be linked to a specific performance evaluation activity within the Modification Protocol (for an example, see Table 1 in Section VII.C. of this guidance).

The Description of Modifications should clearly state if the planned modifications are proposed to be implemented automatically (i.e., whether the modifications are implemented automatically by software), whether modifications are implemented manually (i.e., involving steps that require human input, action, review, and/or decision-making, and therefore are not implemented automatically), or a combination of both. Understanding that this is an evolving area, FDA will consider PCCPs for AI-DSFs for modifications that are implemented automatically. The Agency recognizes that this subset of AI-DSFs has an additional degree of complexity; as with all AI-DSFs, FDA will consider the benefit-risk profile of the specific device that is the subject of the PCCP, the specific modifications being proposed, and FDA's experience applying this policy when reviewing PCCPs containing automatically implemented modifications. To help facilitate FDA's review in this regard, it may be helpful for manufacturers to clearly establish boundaries or guardrails that define the range of automatic updates. Because this guidance includes recommendations for PCCPs for AI-enabled devices broadly, FDA recommends manufacturers discuss considerations for automatic updates for AI-DSFs through the [Q-Submission Program](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/requests-feedback-and-meetings-medical-device-submissions-q-submission-program).

The Description of Modifications should also clearly specify if the proposed modifications will be implemented in a uniform manner across all devices on the market (sometimes referred to as homogenous or global changes, or global adaptations), and/or implemented differently on different devices on the market based on, for example, the unique characteristics of a specific clinical site or individual patients (sometimes referred to as heterogenous or local changes, or local adaptations). For local adaptations, the Description of Modifications should include a description of what local factors or conditions warrant a local change. In addition, the Description of Modifications should also include information regarding the expected frequency of updates. This could range from modifications being implemented, for example, annually, or less frequently, resulting in a device that is primarily 'locked', to modifications being implemented continuously as the device adapts to new data during its use. Finally, it may be helpful to reference the labeling sections that are anticipated to be impacted for each local adaptation in the Description of Modifications section (such labeling changes for each local adaptation should be included in the Modification Protocol, as described in Section VII.B.(4) of this guidance).

## C. Types of Modifications

Modifications that are appropriate for inclusion in a PCCP include those that are intended to maintain or improve the safety or effectiveness of the device. Modifications should also be specific, and should be able to be verified and validated. Types of modifications that may be appropriate for inclusion in a PCCP include:

(i) modifications related to quantitative measures of AI-DSF performance specifications;

(ii) modifications related to device inputs to, and compatibility with, the AI-DSF; and

(iii) certain modifications related to the device's use and performance (e.g., for use within a specific subpopulation).

Modifications related to quantitative measures of AI-DSF performance specifications include improvements to analytical and clinical performance resulting from re-training the AI model based on new data within the intended use population from the same type and range of input signal.

Modifications related to device inputs for the AI-DSF may include changes to data type specifications to include new sources of the same input signal type (e.g., different makes, models, or versions of a data/imaging acquisition system), or limited modifications related to new types of inputs (e.g., adding new data inputs, such as age, or transforming data inputs, such as through data normalizations). Modifications related to input sources and compatibility with the AI-DSF may include updates related to available, compatible software or hardware and device interoperability (e.g., different compatible hardware, updated operating systems, or updated cloud infrastructure).

Modifications related to the device's use and performance could include authorization of a device for a specific subpopulation within the originally indicated population based on re-training on a larger data set for that subpopulation that was not previously available. See Appendix B for examples of modifications included in an authorized PCCP for various AI-DSFs.

Modifications included in a PCCP must maintain the device within the device's intended use[^91], and as applicable, must allow the device to remain substantially equivalent to the predicate device[^92]. In general, FDA believes that modifications included in a PCCP should also maintain the device within the device's indications for use[^93]. As with modifications to the intended use, FDA believes that most modifications to the indications for use included in a PCCP would be difficult for FDA to assess prospectively to determine whether the device would remain safe and effective[^94]. However, there may be certain modifications to the indications for use (e.g., certain changes in the indications for use to specify use of the device with an additional device or component) that may be appropriate for inclusion in a PCCP. FDA highly encourages manufacturers to discuss modifications to the indications for use that may be included in a proposed PCCP with the appropriate FDA review division through the [Q-Submission Program](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/requests-feedback-and-meetings-medical-device-submissions-q-submission-program).

Recognizing there is a spectrum of risk for devices, for the purposes of reviewing a PCCP, FDA intends to, among other considerations, take into account the benefit-risk profile of the specific device that is the subject of the PCCP, the specific modifications being proposed, and FDA's experience applying this policy across different device types. As such, certain modifications that may be appropriate for inclusion in a PCCP for one device may not be appropriate for inclusion in a PCCP for another device. Some modifications may not be appropriate for inclusion within a PCCP for any device. FDA encourages manufacturers to leverage the [Q-Submission Program](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/requests-feedback-and-meetings-medical-device-submissions-q-submission-program) to obtain FDA feedback on a proposed PCCP prior to submitting a marketing submission.

[^91]: See sections 515C(a)(2) and 515C(b)(2) of the FD&C Act. FD&C Act의 섹션 515C(a)(2) 및 515C(b)(2)를 참조하십시오.

[^92]: Section 515C(b)(2)(B) of the FD&C Act. FD&C Act의 섹션 515C(b)(2)(B).

[^93]: FDA has a long-standing policy of applying the definition of indications for use in the PMA regulation at 21 CFR 814.20(b)(3)(i) in the same way in the 510(k) context. See the FDA guidance "[The 510(k) Program: Evaluating Substantial Equivalence in Premarket Notifications [510(k)]](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/510k-program-evaluating-substantial-equivalence-premarket-notifications-510k)." FDA는 21 CFR 814.20(b)(3)(i)의 PMA 규정에서 사용 적응증의 정의를 510(k) 맥락에서 동일한 방식으로 적용하는 오랜 정책을 가지고 있습니다. FDA 가이던스 "[510(k) 프로그램: 시판 전 신고[510(k)]에서 실질적 동등성 평가](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/510k-program-evaluating-substantial-equivalence-premarket-notifications-510k)"를 참조하십시오.

[^94]: Sections 515C(a)(2) and 515C(b)(2)(A) of the FD&C Act. FD&C Act의 섹션 515C(a)(2) 및 515C(b)(2)(A).

# VI. 수정사항 설명

AI-DSF에 대한 각 계획된 수정사항에 대한 설명은 PCCP의 수정사항 설명 섹션에 포함되어야 한다. 상세한 설명은 수정사항의 구현으로 인한 기기 특성 및 성능에 대한 구체적인 변경사항을 설명해야 한다. 효율적인 검토를 보장하기 위해, FDA는 PCCP가 구체적이고 검증 및 확인될 수 있는 제한된 수의 수정사항만을 포함할 것을 권장한다.

부록은 예시 수정사항과 AI-DSF에 대한 승인된 PCCP를 사용하는 시나리오(부록 B)를 포함하여 본 가이던스의 권고사항을 구현하는 데 도움이 되는 주요 정보를 제공한다.

## A. 수정사항 설명 섹션의 목표

PCCP의 전용 수정사항 설명 섹션은 제조업체가 구현하고자 하는 AI-DSF에 대한 구체적이고 계획된 수정사항을 식별해야 한다. 수정사항 설명은 수정 프로토콜에 설명된 합의된 검증 및 확인에 따라 새로운 시판 신청서 없이 구현될 수 있는 기기의 특성 및 성능에 대한 사양을 포함해야 한다.

## B. 수정사항 설명 섹션의 내용

이러한 목표를 달성하기 위해, FDA는 수정사항 설명이 PCCP에서 논의된 개별 제안된 기기 수정사항의 목록과 수정될 예정인 AI-DSF의 각 부분에 대한 변경의 구체적인 근거를 열거할 것을 권장한다. 일부 상황에서는 수정사항 설명이 여러 수정사항으로 구성될 수 있다. 수정사항 설명 섹션에서 각 수정사항에 대해 영향을 받을 것으로 예상되는 라벨링 섹션을 참조하는 것이 도움이 될 수 있다(각 수정사항에 대한 그러한 라벨링 변경사항은 본 가이던스의 섹션 VII.B.(4)에 설명된 대로 수정 프로토콜에 포함되어야 한다).

FDA는 PCCP가 구체적이고 검증 및 확인될 수 있는 수정사항을 포함할 것을 권장한다. 수정사항은 또한 AI-DSF에 대해 수행될 구체적인 수정사항에 대한 이해를 허용하는 세부 수준으로 제시되어야 한다. 각 수정사항은 수정 프로토콜 내의 구체적인 성능 평가 활동과 연결되어야 한다(예시는 본 가이던스의 섹션 VII.C.의 표 1 참조).

수정사항 설명은 계획된 수정사항이 자동으로 구현되도록 제안되는지(즉, 수정사항이 소프트웨어에 의해 자동으로 구현되는지 여부), 수정사항이 수동으로 구현되는지(즉, 인간의 입력, 행동, 검토 및/또는 의사결정이 필요한 단계를 포함하므로 자동으로 구현되지 않음), 또는 두 가지의 조합인지를 명확하게 명시해야 한다. 이것이 진화하는 영역임을 이해하면서, FDA는 자동으로 구현되는 수정사항에 대한 AI-DSF에 대한 PCCP를 고려할 것이다. FDA는 이러한 AI-DSF의 하위 집합이 추가적인 복잡성의 정도를 가지고 있음을 인식한다; 모든 AI-DSF와 마찬가지로, FDA는 자동으로 구현된 수정사항을 포함하는 PCCP를 검토할 때 PCCP의 대상인 특정 기기의 편익-위험 프로필, 제안되는 구체적인 수정사항, 그리고 이 정책을 적용하는 FDA의 경험을 고려할 것이다. 이와 관련하여 FDA의 검토를 촉진하기 위해, 제조업체가 자동 업데이트의 범위를 정의하는 경계 또는 가드레일을 명확하게 수립하는 것이 도움이 될 수 있다. 본 가이던스가 AI 기반 기기에 대한 PCCP에 대한 권고사항을 광범위하게 포함하기 때문에, FDA는 제조업체가 Q-제출 프로그램을 통해 AI-DSF에 대한 자동 업데이트에 대한 고려사항을 논의할 것을 권장한다.

수정사항 설명은 또한 제안된 수정사항이 시장의 모든 기기에 균일한 방식으로 구현될 것인지(때때로 동질적 또는 전역 변경, 또는 전역 적응이라고 함), 및/또는 예를 들어 특정 임상 사이트 또는 개별 환자의 고유한 특성을 기반으로 시장의 다른 기기에 다르게 구현될 것인지(때때로 이질적 또는 지역 변경, 또는 지역 적응이라고 함)를 명확하게 명시해야 한다. 지역 적응의 경우, 수정사항 설명은 어떤 지역 요인 또는 조건이 지역 변경을 정당화하는지에 대한 설명을 포함해야 한다. 또한, 수정사항 설명은 업데이트의 예상 빈도에 관한 정보도 포함해야 한다. 이것은 예를 들어 연간 또는 덜 빈번하게 수정사항이 구현되어 주로 '고정된' 기기를 초래하는 것에서부터 기기가 사용 중에 새로운 데이터에 적응함에 따라 수정사항이 지속적으로 구현되는 것까지 범위가 있을 수 있다. 마지막으로, 수정사항 설명 섹션에서 각 지역 적응에 대해 영향을 받을 것으로 예상되는 라벨링 섹션을 참조하는 것이 도움이 될 수 있다(각 지역 적응에 대한 그러한 라벨링 변경사항은 본 가이던스의 섹션 VII.B.(4)에 설명된 대로 수정 프로토콜에 포함되어야 한다).

## C. 수정사항의 유형

PCCP에 포함하기에 적절한 수정사항에는 기기의 안전성 또는 효과성을 유지하거나 개선하기 위한 것이 포함된다. 수정사항은 또한 구체적이어야 하며, 검증 및 확인될 수 있어야 한다. PCCP에 포함하기에 적절할 수 있는 수정사항의 유형에는 다음이 포함된다:

(i) AI-DSF 성능 사양의 정량적 측정과 관련된 수정사항;

(ii) AI-DSF에 대한 기기 입력 및 호환성과 관련된 수정사항; 그리고

(iii) 기기의 사용 및 성능과 관련된 특정 수정사항(예: 특정 하위 집단 내에서의 사용).

AI-DSF 성능 사양의 정량적 측정과 관련된 수정사항에는 동일한 유형 및 범위의 입력 신호로부터 의도된 사용 집단 내의 새로운 데이터를 기반으로 AI 모델을 재훈련한 결과로 인한 분석적 및 임상적 성능 개선이 포함된다.

AI-DSF에 대한 기기 입력과 관련된 수정사항에는 동일한 입력 신호 유형의 새로운 소스를 포함하도록 데이터 유형 사양의 변경(예: 데이터/영상 획득 시스템의 다른 제조사, 모델 또는 버전), 또는 새로운 유형의 입력과 관련된 제한적 수정사항(예: 연령과 같은 새로운 데이터 입력 추가, 또는 데이터 정규화와 같은 데이터 입력 변환)이 포함될 수 있다. AI-DSF와의 입력 소스 및 호환성과 관련된 수정사항에는 사용 가능하고 호환 가능한 소프트웨어 또는 하드웨어 및 기기 상호운용성과 관련된 업데이트(예: 다른 호환 가능한 하드웨어, 업데이트된 운영 체제 또는 업데이트된 클라우드 인프라)가 포함될 수 있다.

기기의 사용 및 성능과 관련된 수정사항에는 이전에 사용할 수 없었던 해당 하위 집단에 대한 더 큰 데이터 세트에 대한 재훈련을 기반으로 원래 표시된 집단 내의 특정 하위 집단에 대한 기기의 승인이 포함될 수 있다. 다양한 AI-DSF에 대한 승인된 PCCP에 포함된 수정사항의 예시는 부록 B를 참조하라.

PCCP에 포함된 수정사항은 기기를 기기의 의도된 용도 내에 유지해야 하며[^91], 해당되는 경우 기기가 선행 기기와 실질적으로 동등하게 유지되도록 해야 한다[^92]. 일반적으로 FDA는 PCCP에 포함된 수정사항이 또한 기기를 기기의 사용 적응증 내에 유지해야 한다고 판단한다[^93]. 의도된 용도에 대한 수정사항과 마찬가지로, FDA는 PCCP에 포함된 사용 적응증에 대한 대부분의 수정사항이 기기가 안전하고 효과적으로 유지될 것인지 여부를 판단하기 위해 FDA가 사전에 평가하기 어려울 것이라고 판단한다[^94]. 그러나 사용 적응증에 대한 특정 수정사항(예: 추가 기기 또는 구성요소와의 기기 사용을 명시하기 위한 사용 적응증의 특정 변경사항)이 PCCP에 포함하기에 적절할 수 있다. FDA는 제조업체가 제안된 PCCP에 포함될 수 있는 사용 적응증에 대한 수정사항을 Q-제출 프로그램을 통해 적절한 FDA 심사 부서와 논의할 것을 강력히 권장한다.

기기에 대한 위험의 스펙트럼이 있음을 인식하면서, PCCP를 검토하는 목적상, FDA는 다른 고려사항 중에서도 PCCP의 대상인 특정 기기의 편익-위험 프로필, 제안되는 구체적인 수정사항, 그리고 다양한 기기 유형에 걸쳐 이 정책을 적용하는 FDA의 경험을 고려할 의도이다. 따라서 한 기기에 대한 PCCP에 포함하기에 적절할 수 있는 특정 수정사항이 다른 기기에 대한 PCCP에 포함하기에 적절하지 않을 수 있다. 일부 수정사항은 어떤 기기에 대한 PCCP 내에 포함하기에 적절하지 않을 수 있다. FDA는 제조업체가 시판 신청서를 제출하기 전에 제안된 PCCP에 대한 FDA 피드백을 얻기 위해 Q-제출 프로그램을 활용할 것을 권장한다.

# VII. Modification Protocol

The Modification Protocol should include the documentation describing the methods that will be followed when developing, validating, and implementing modifications delineated in the Description of Modifications section of the PCCP. The Modification Protocol should also include the verification and validation activities, including pre-defined acceptance criteria, for those modifications, and a step-by-step delineation of how those modifications will be implemented while assuring the device remains safe and effective. The Appendices provide key information to help manufacturers implement the recommendations in this guidance, including detailed questions and considerations for the recommended content of a Modification Protocol in a PCCP (Appendix A).

Documentation of modifications verified and validated per the Modification Protocol must be compliant with the QSR, including that the manufacturer must document the change in accordance with the manufacturer's quality system[^95]. The QSR requires manufacturers of finished medical devices to review and approve modifications to device design and production (21 CFR 820.30(i) and 820.70(b)) and document changes and approvals in the device master record (21 CFR 820.181).

## A. Goals of the Modification Protocol Section

Whereas the Description of Modifications outlines the planned modifications to an AI-DSF, the Modification Protocol should describe the methods that will be followed when developing, validating, and implementing those modifications, to ensure the device remains safe and effective. The methods described in the Modification Protocol should be consistent with and support the modifications outlined in the Description of Modifications.

The goals of the Modification Protocol are to:

* Identify the appropriate and applicable data, test methods, analysis methods, and specified acceptance criteria used to develop, validate, and implement all proposed modifications;
* Identify the update process, and as appropriate, the plans for communication and/or training for users for implemented modifications;
* Ensure that the information that would otherwise be generated and submitted to FDA (i.e., if the modifications were implemented on a device that did not have an authorized PCCP) will be generated by the manufacturer for each modification and maintained consistent with recordkeeping requirements and in accordance with the manufacturer's quality system[^96];
* Ensure that anticipated risks and risk mitigation strategies have been identified and included in the Impact Assessment; and
* Be least burdensome[^97] for the manufacturer to develop and for FDA to review. This includes being traceable (so that modifications in the Description of Modifications can be traced to verification and validation activities in the Modification Protocol) and specific (so that the PCCP is sufficiently comprehensive to support the proposed modifications).

This guidance identifies four primary components of a Modification Protocol that outline a manufacturer's 1) data management practices, 2) re-training practices, 3) performance evaluation protocols, and 4) update procedures, including communication and transparency to users and real-world monitoring plans as applicable, for each modification in a PCCP. In FDA's experience, these four components should generally provide FDA with the information needed to evaluate the PCCP. For a particular marketing submission, additional components of a Modification Protocol may need to be included to assist in FDA's determination of substantial equivalence or reasonable assurance of safety and effectiveness of the device and PCCP.

Manufacturers should follow their risk management processes to develop a Modification Protocol that considers each modification[^98]. In some cases, the same methods in each component of the Modification Protocol may support all modifications in a PCCP for a device. In other cases, the same methods in each component of the Modification Protocol may not be adequate for every modification in a PCCP. For each planned modification provided in the Description of Modifications, FDA recommends that each of the four primary components of a Modification Protocol be addressed. The Modification Protocol should include a description of how its proposed methods are similar to or different from methods used elsewhere in the marketing submission. For example, if the validation methods in the Modification Protocol represent a subset of the original testing for the device, or if the acceptance criteria for the validation are different, manufacturers should describe these differences and provide a justification. The justification for a different methodology may include references to other marketing submissions where the methodology was used for similar modifications.

## B. Content of the Modification Protocol Section

To achieve these goals, FDA recommends that a Modification Protocol outline the methods for each component described below. Example elements of each of the four Modification Protocol components are provided in Appendix A.

### (1) Data management practices

*What they are:* AI-DSF training, tuning, and testing typically utilize data that include the inputs (e.g., medical images) that will be used by the device and often utilize a label or 'reference standard' that is determined through a reference standard determination and/or an annotation process. Training data, tuning data, and test data are sequestered (i.e., the test data set is a unique data set compared to the data set used for training and tuning) to prevent overfitting and misquotes of test performance. The training, tuning, and testing methods aim to identify and mitigate unwanted bias in the data (which may be inherent from historical datasets) and to improve the robustness and resilience of these algorithms to withstand changing clinical inputs and conditions. Additional methods to mitigate bias may be helpful, such as cross-validation, bootstrapping, bagging, ensembling, and the use of synthetic or augmented data. To support modifications to an AI-DSF that may need training, tuning, and/or testing, it is anticipated that new data (i.e., data that were not used to develop the initial AI-DSF) will be collected. The data management practices in a Modification Protocol should outline how those new data will be collected, annotated, curated, stored, retained[^99], controlled, and used by the manufacturer for each modification. The data management practices in a Modification Protocol should also clarify the relationship between all of the data used to train, tune, and test the initial and any subsequent versions of the AI-DSF. It should also describe the control methods employed to ensure that the data used to test the AI-DSF is separate and independent from the development process used to train and tune the AI-DSF.

*Why they are recommended:* This information allows FDA to understand the manufacturer's data management practices that will be used to support each modification to an AI-DSF, including 1) how the manufacturer plans to obtain and use training, tuning, and test data that are complete and representative of the proposed intended use populations (e.g., with respect to race, ethnicity, disease severity, sex, age, etc.[^100]) and intended environments; 2) whether identifiable subpopulations will be adequately represented, including intersectional groups, and separated into training, tuning, and test sets to minimize AI model bias; 3) how training, tuning, and test data will be sequestered to prevent overfitting and misquotes of test performance; 4) how older data will be complemented or replaced by newer data so that the performance is representative of the current patient population and standard of care; 5) whether the reference standard represents the best available process for determining the ground truth; and 6) how the data management practices may reduce the potential to produce discriminatory outcomes. A clear explanation of data management practices also provides assurance to FDA that modifications to the AI-DSF are based on data that are representative of the device's indications for use. This includes information regarding products that will be used to generate data as inputs for the AI-DSF, patient populations in which the device will be used, and clinical scenarios where the device will be used.

*What manufacturers should include in a submission:* Examples of the types of information manufacturers should provide in a Modification Protocol describing their data management practices are provided in Appendix A. In general, this information should describe: how data will be collected, including clinical study protocols with inclusion/exclusion criteria; information on how data will be processed, stored, and retained[^101]; the process that will be followed to determine the reference standard; when clinician interpretation is used for determining the reference standard (representing the ground truth), a protocol describing how the reference standard is determined; the quality assurance process related to the data; the data sequestration strategies that will be followed during data collection to separate the data into training, tuning, and test sets; and the protocols in place to prevent access during the training, tuning, and testing process to data intended for performance testing.

### (2) Re-training practices

*What they are:* AI software generally involves multiple processing steps from the point the AI-DSF receives the input data to the point it provides an output. The re-training practices component of a Modification Protocol should identify the processing steps that are subject to change for each modification and the methods that will be used by the manufacturer to implement modifications to the AI-DSF. In addition, if re-training involves architecture modifications (e.g., in a neural network, modifications to training hyperparameters or the number of nodes, layers, etc.), the re-training practices component of a Modification Protocol should also describe the rationale or the justification for each specific architecture modification.

*Why they are recommended:* Information on the manufacturer's re-training practices allows FDA to understand how the proposed modifications will be achieved through re-training, to determine if modifications are implemented following appropriate, well-defined practices[^102], and to determine if the performance evaluation and update procedures (discussed below) support the modifications. Information on the manufacturer's re-training practices is typically provided in the "device description" of a marketing submission for the majority of AI-DSFs that FDA reviews. The specifics of what should be included in this component of the Modification Protocol will depend on the type of modification and specific device.

*What manufacturers should include in a submission:* Examples of the types of information manufacturers should provide in a Modification Protocol describing their re-training practices are provided in Appendix A. In general, this information should identify the objective of the re-training process, provide a description of the AI model, identify the device components that may be modified, outline the practices that will be followed (e.g., data sequestration strategies during re-training), and identify any triggers for re-training (e.g., when the quantity of new data reaches a certain size or when a drift in data is observed over time).

### (3) Performance evaluation

*What they are:* FDA may require that performance requirements for changes made under the plan be provided in a PCCP[^103]. Performance evaluation methods should describe the processes that will be followed to verify and validate that the modified AI-DSF will meet the specifications identified as part of a specific modification, in addition to maintaining the specifications that are not part of the modification, but may be impacted by the modification. Performance evaluation should include, as applicable, the plans for verification and validation of the entire device following the implementation of each individual modification and in aggregate for the planned modifications. This includes, but is not limited to, AI model testing protocols comparing the newly modified device to both the original device (the version of the device without any modifications implemented) and the last modified version of the device. For example, for device software functions that drive hardware functionality, performance evaluation should include not only the device software functions, but also the effect of the modifications on hardware functionality. The content of this section in a Modification Protocol should provide details on the study design, performance metrics, pre-defined acceptance criteria, and statistical tests for each planned modification. More comprehensive testing can potentially support a broader set of proposed modifications.

*Why they are recommended:* Information regarding the manufacturer's performance evaluation methods allow FDA to confirm that appropriate study designs, including performance metrics and statistical tests, will be used to evaluate the effect of modifications on overall device performance. Performance evaluation of the device is important to ensure that specified acceptance criteria for all proposed modifications will continue to be met for the device's specifications.

*What manufacturers should include in a submission:* Examples of the types of information manufacturers should provide in a Modification Protocol describing their performance evaluation are provided in Appendix A. In general, this information should describe how performance evaluation will be triggered; how sequestered test data representative of the clinical population and intended use will be applied for testing; what performance metrics will be computed; and what statistical analysis plans will be employed to test hypotheses relevant to performance objectives for each modification. The Modification Protocol should also affirmatively state that if there is an unresolvable failure in performance evaluation for a specific modification (e.g., the predefined acceptance criteria for a specific modification are not met), the failure(s) will be recorded, and the specific modification(s) will not be implemented. A failure would not be considered to be unresolvable if a root cause analysis of the failure reveals it is not related to specific aspects of the PCCP, and in such cases, performance testing may be conducted again.

### (4) Update procedures

*What they are:* Data management practices, re-training practices, and performance evaluation described above largely relate to making and testing modifications to the AI-DSF. Once these meet the performance objectives, manufacturers will need to update the AI-DSF to implement the modifications and communicate information to users about the modifications that is needed to safely use the device. The update procedures should clearly describe which planned modifications will be implemented automatically, implemented manually, or a combination of both, and how the manufacturer plans to communicate this information to users. The update procedures in a Modification Protocol should describe how manufacturers will update their devices to implement the modifications consistent with QSR, and, if appropriate for such modifications, provide appropriate transparency to users and updated user training[^104]. The manufacturer should also describe their post-market surveillance plans and procedures, which may include real-world monitoring and notification requirements if the device does not function as intended pursuant to the authorized PCCP[^105]. As part of a manufacturer's responsibility to ensure that devices remain safe and effective, FDA anticipates that manufacturers will monitor their device's safety (e.g., adverse events) and effectiveness (e.g., performance) over time as modifications are implemented consistent with their authorized PCCP. Monitoring activities may differ for AI-DSFs for which updates are deployed manually compared to automatically, or for which updates are deployed globally or locally.

The update procedures in a Modification Protocol should also address how labeling will be updated when modifications are implemented, as appropriate[^106]. It should also include a description of the labeling sections that are anticipated to be impacted by the implementation of the modifications. The available labeling must include adequate directions for use[^107]. The available labeling should also reflect information about the current version(s) of the AI-DSF available to the user, including information regarding site-specific modifications. New unique device identifiers (UDIs) are required for devices that are required to bear a UDI on its label when there is a new version and/or model, and for new device packages[^108]. FDA recommends that the labeling not include information on modifications to the AI-DSF that have not been implemented in the available version because it could cause confusion and would be misleading. Additionally, if the labeling states that a modification to the AI-DSF has been implemented when it has not, the device might be deemed misbranded[^109].

*Why they are recommended:* Information on the manufacturer's update procedures allows FDA to understand 1) how risks from implementing modifications may be mitigated by the update process; 2) how communication regarding the device updates will be provided to users (e.g., so that updates in device output results will be correctly interpreted by users); 3) how the device operation will remain safe and effective after the update; and 4) how all users will be kept up-to-date about device functionality and performance. In addition, it is important for FDA to understand how potential risks associated with the update process, itself, may be mitigated.

*What manufacturers should include in a submission:* Examples of the types of information manufacturers should provide in a Modification Protocol describing their update procedures are provided in Appendix A. In general, this information should include 1) confirmation that the verification and validation plans for the modified version of the device are the same as those that have been performed for the version of the device prior to the implementation of the modifications, or identification of any differences between the two plans; 2) a description of how software updates will be implemented; 3) a description of how legacy users will be affected by the software update (if applicable); and 4) a description of how modifications will be communicated to the users, including transparency on any differences in performance or device inputs, and/or known issues that were addressed in the update. Communication of performance changes should be consistent with performance evaluation described in the Modification Protocol.

## C. Traceability Between the Description of Modifications Section and the Modification Protocol Section

The PCCP should clearly delineate which parts of the Modification Protocol are applicable to each modification within the Description of Modifications. For a PCCP with multiple modifications, this may be accomplished through a traceability table; a sample traceability table is provided below in Table 1. This sample traceability table provides an example of how a manufacturer can depict the traceability between the Description of Modifications and Modification Protocol, as well as how to provide clear references to where within the PCCP this information is located in a marketing submission. In other words, a traceability table can help to identify where each method supporting each modification may be found in the marketing submission.

**Table 1. Example of Description of Modifications to Modification Protocol Traceability Table**

| Modification | Data management practices | Re-training practices | Performance evaluation | Update procedures |
|--------------|---------------------------|----------------------|------------------------|-------------------|
| *Modification #1* | *Method A (see Section X.A)* | *Method D (see Section X.D)* | *Method G (see Section X.G)* | *Method J (see Section X.J)* |
| *Modification #2* | *Method A (see Section X.A)* | *Method E (see Section X.E)* | *Method H (see Section X.H)* | *Method J (see Section X.J)* |
| *Modification #3* | *Method B (see Section X.B)* | *Method F (see Section X.F)* | *Method I (see Section X.I)* | *Method J (see Section X.J)* |

[^95]: 21 CFR Part 820. 21 CFR Part 820.

[^96]: 21 CFR Part 820. 21 CFR Part 820.

[^97]: See FDA's guidance "[The Least Burdensome Provisions: Concept and Principles](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/least-burdensome-provisions-concept-and-principles)." FDA 가이던스 "[최소 부담 조항: 개념 및 원칙](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/least-burdensome-provisions-concept-and-principles)"을 참조하십시오.

[^98]: See AAMI CR 34971:2022, AAMI Consensus Report – Guidance on the Application of ISO 14971 To Artificial Intelligence And Machine Learning. AAMI CR 34971:2022, AAMI 합의 보고서 – 인공지능 및 머신러닝에 ISO 14971 적용에 관한 가이던스를 참조하십시오.

[^99]: The QSR requires manufacturers to retain all records for a period of time equivalent to the design and expected life of the device, but in no case less than 2 years from the date of release for commercial distribution by the manufacturer (21 CFR 820.180(b)). QSR은 제조업체가 기기의 설계 및 예상 수명과 동등한 기간 동안 모든 기록을 보유할 것을 요구하지만, 어떠한 경우에도 제조업체의 상업적 유통을 위한 출시일로부터 2년 미만이어서는 안 됩니다(21 CFR 820.180(b)).

[^100]: We recommend that manufacturers consider additional characteristics, such as race, color, ethnicity, sex (including pregnancy, childbirth, and related medical conditions), religion, age, national origin, disability, veteran status, and genetic information. 제조업체가 인종, 피부색, 민족성, 성별(임신, 출산 및 관련 의학적 상태 포함), 종교, 연령, 출신 국가, 장애, 재향군인 지위 및 유전 정보와 같은 추가 특성을 고려할 것을 권장합니다.

[^101]: See 21 CFR 820.180(b). 21 CFR 820.180(b)를 참조하십시오.

[^102]: For example, FDA has published a document on "[Good Machine Learning Practice for Medical Device Development: Guiding Principles](https://www.fda.gov/medical-devices/software-medical-device-samd/good-machine-learning-practice-medical-device-development-guiding-principles)." 예를 들어, FDA는 "[의료기기 개발을 위한 우수 머신러닝 실무: 지도 원칙](https://www.fda.gov/medical-devices/software-medical-device-samd/good-machine-learning-practice-medical-device-development-guiding-principles)"에 관한 문서를 발표했습니다.

[^103]: See sections 515C(a)(3), 515C(b)(3), and 513(f)(2) of the FD&C Act. FD&C Act의 섹션 515C(a)(3), 515C(b)(3), 513(f)(2)를 참조하십시오.

[^104]: See sections 515C(a)(3), 515C(b)(3), and 513(f)(2) of the FD&C Act. FD&C Act의 섹션 515C(a)(3), 515C(b)(3), 513(f)(2)를 참조하십시오.

[^105]: See sections 515C(a)(3), 515C(b)(3), and 513(f)(2) of the FD&C Act. FD&C Act의 섹션 515C(a)(3), 515C(b)(3), 513(f)(2)를 참조하십시오.

[^106]: See Section V.C. of this guidance for the recommendations regarding information about the PCCP that should be included in the device labeling. 기기 라벨링에 포함되어야 하는 PCCP에 대한 정보에 관한 권고사항은 이 가이던스의 섹션 V.C.를 참조하십시오.

[^107]: See 21 CFR 801.5(a), requiring that labeling include adequate directions for use including statements of all conditions, purposes, or uses for which the device is intended. 라벨링에 기기가 의도된 모든 조건, 목적 또는 용도의 진술을 포함한 적절한 사용 지침을 포함할 것을 요구하는 21 CFR 801.5(a)를 참조하십시오.

[^108]: See 21 CFR 830.50. 21 CFR 830.50을 참조하십시오.

[^109]: See section 502(a)(1) of the FD&C Act, stating that a medical device is deemed misbranded if its labeling is false or misleading in any particular. 라벨링이 어떠한 특정 사항에서 허위이거나 오해를 불러일으키는 경우 의료기기가 부정표시(misbranded)로 간주된다고 명시하는 FD&C Act의 섹션 502(a)(1)을 참조하십시오.

# VII. 수정 프로토콜

수정 프로토콜은 PCCP의 수정사항 설명 섹션에 기술된 수정사항을 개발, 검증 및 구현할 때 따라야 할 방법을 설명하는 문서를 포함해야 한다. 수정 프로토콜은 또한 해당 수정사항에 대한 사전 정의된 수용 기준을 포함한 검증 및 확인 활동, 그리고 기기가 안전하고 효과적으로 유지되도록 보장하면서 해당 수정사항이 어떻게 구현될 것인지에 대한 단계별 설명을 포함해야 한다. 부록은 PCCP의 수정 프로토콜의 권장 내용에 대한 상세한 질문 및 고려사항을 포함하여 본 가이던스의 권고사항을 구현하는 데 도움이 되는 주요 정보를 제공한다(부록 A).

수정 프로토콜에 따라 검증 및 확인된 수정사항의 문서화는 제조업체가 품질 시스템에 따라 변경사항을 문서화해야 하는 것을 포함하여 QSR을 준수해야 한다[^95]. QSR은 제조업체가 기기 설계 및 생산에 대한 수정사항을 검토하고 승인하고(21 CFR 820.30(i) 및 820.70(b)) 기기 마스터 기록에 변경사항 및 승인을 문서화하도록 요구한다(21 CFR 820.181).

## A. 수정 프로토콜 섹션의 목표

수정사항 설명이 AI-DSF에 대한 계획된 수정사항을 개괄하는 반면, 수정 프로토콜은 기기가 안전하고 효과적으로 유지되도록 보장하기 위해 해당 수정사항을 개발, 검증 및 구현할 때 따라야 할 방법을 설명해야 한다. 수정 프로토콜에 설명된 방법은 수정사항 설명에 개괄된 수정사항과 일치하고 이를 지원해야 한다.

수정 프로토콜의 목표는 다음과 같다:

* 모든 제안된 수정사항을 개발, 검증 및 구현하는 데 사용되는 적절하고 적용 가능한 데이터, 테스트 방법, 분석 방법 및 명시된 수용 기준을 식별한다;
* 업데이트 프로세스, 그리고 적절한 경우 구현된 수정사항에 대한 사용자를 위한 의사소통 및/또는 교육 계획을 식별한다;
* 그렇지 않으면 FDA에 생성되고 제출될 정보(즉, 승인된 PCCP가 없는 기기에 수정사항이 구현된 경우)가 각 수정사항에 대해 제조업체에 의해 생성되고 기록 보관 요건과 일치하게 그리고 제조업체의 품질 시스템에 따라 유지되도록 보장한다[^96];
* 예상되는 위험 및 위험 완화 전략이 식별되고 영향 평가에 포함되었는지 확인한다; 그리고
* 제조업체가 개발하고 FDA가 검토하기에 최소 부담이 되도록 한다[^97]. 여기에는 추적 가능성(수정사항 설명의 수정사항이 수정 프로토콜의 검증 및 확인 활동으로 추적될 수 있도록) 및 구체성(PCCP가 제안된 수정사항을 지원하기에 충분히 포괄적이도록)이 포함된다.

본 가이던스는 PCCP의 각 수정사항에 대한 제조업체의 1) 데이터 관리 관행, 2) 재훈련 관행, 3) 성능 평가 프로토콜, 4) 업데이트 절차를 개괄하는 수정 프로토콜의 네 가지 주요 구성요소를 식별한다. FDA의 경험상, 이러한 네 가지 구성요소는 일반적으로 FDA가 PCCP를 평가하는 데 필요한 정보를 제공해야 한다. 특정 시판 신청서의 경우, FDA의 기기 및 PCCP의 실질적 동등성 또는 안전성과 효과성에 대한 합리적인 보증 판단을 지원하기 위해 수정 프로토콜의 추가 구성요소를 포함해야 할 수 있다.

제조업체는 각 수정사항을 고려하는 수정 프로토콜을 개발하기 위해 위험 관리 프로세스를 따라야 한다[^98]. 일부 경우, 수정 프로토콜의 각 구성요소에서 동일한 방법이 기기에 대한 PCCP의 모든 수정사항을 지원할 수 있다. 다른 경우, 수정 프로토콜의 각 구성요소에서 동일한 방법이 PCCP의 모든 수정사항에 적합하지 않을 수 있다. 수정사항 설명에 제공된 각 계획된 수정사항에 대해, FDA는 수정 프로토콜의 네 가지 주요 구성요소 각각이 다루어질 것을 권장한다. 수정 프로토콜은 제안된 방법이 시판 신청서의 다른 곳에서 사용된 방법과 어떻게 유사하거나 다른지에 대한 설명을 포함해야 한다. 예를 들어, 수정 프로토콜의 검증 방법이 기기에 대한 원래 테스트의 하위 집합을 나타내거나 검증에 대한 수용 기준이 다른 경우, 제조업체는 이러한 차이점을 설명하고 정당성을 제공해야 한다. 다른 방법론에 대한 정당성에는 유사한 수정사항에 대해 방법론이 사용된 다른 시판 신청서에 대한 참조가 포함될 수 있다.

## B. 수정 프로토콜 섹션의 내용

이러한 목표를 달성하기 위해, FDA는 수정 프로토콜이 아래에 설명된 각 구성요소에 대한 방법을 개괄할 것을 권장한다. 네 가지 수정 프로토콜 구성요소 각각의 예시 요소는 부록 A에 제공된다.

### (1) 데이터 관리 관행

*그것이 무엇인가:* AI-DSF 훈련, 튜닝 및 테스트는 일반적으로 기기가 사용할 입력(예: 의료 영상)을 포함하는 데이터를 활용하며 종종 참조 표준 결정 및/또는 주석 프로세스를 통해 결정되는 라벨 또는 '참조 표준'을 활용한다. 훈련 데이터, 튜닝 데이터 및 테스트 데이터는 과적합 및 테스트 성능의 잘못된 인용을 방지하기 위해 격리된다(즉, 테스트 데이터 세트는 훈련 및 튜닝에 사용된 데이터 세트와 비교하여 고유한 데이터 세트임). 훈련, 튜닝 및 테스트 방법은 데이터의 원치 않는 편향(역사적 데이터 세트에서 고유할 수 있음)을 식별하고 완화하며 이러한 알고리즘의 견고성과 복원력을 개선하여 변화하는 임상 입력 및 조건을 견디도록 하는 것을 목표로 한다. 교차 검증, 부트스트래핑, 배깅, 앙상블 및 합성 또는 증강 데이터의 사용과 같은 편향을 완화하기 위한 추가 방법이 도움이 될 수 있다. 훈련, 튜닝 및/또는 테스트가 필요할 수 있는 AI-DSF에 대한 수정사항을 지원하기 위해, 새로운 데이터(즉, 초기 AI-DSF를 개발하는 데 사용되지 않은 데이터)가 수집될 것으로 예상된다. 수정 프로토콜의 데이터 관리 관행은 각 수정사항에 대해 제조업체가 해당 새로운 데이터를 어떻게 수집, 주석 처리, 큐레이션, 저장, 보유[^99], 관리 및 사용할 것인지를 개괄해야 한다. 수정 프로토콜의 데이터 관리 관행은 또한 초기 및 후속 버전의 AI-DSF를 훈련, 튜닝 및 테스트하는 데 사용된 모든 데이터 간의 관계를 명확히 해야 한다. 또한 AI-DSF를 테스트하는 데 사용된 데이터가 AI-DSF를 훈련하고 튜닝하는 데 사용된 개발 프로세스와 분리되고 독립적임을 보장하기 위해 사용되는 관리 방법을 설명해야 한다.

*왜 권장되는가:* 이 정보를 통해 FDA는 1) 제조업체가 제안된 의도된 사용 집단(예: 인종, 민족, 질병 중증도, 성별, 연령 등과 관련하여[^100]) 및 의도된 환경을 대표하는 완전하고 대표적인 훈련, 튜닝 및 테스트 데이터를 얻고 사용할 계획; 2) 교차 그룹을 포함하여 식별 가능한 하위 집단이 적절하게 표현되고 AI 모델 편향을 최소화하기 위해 훈련, 튜닝 및 테스트 세트로 분리될 것인지 여부; 3) 과적합 및 테스트 성능의 잘못된 인용을 방지하기 위해 훈련, 튜닝 및 테스트 데이터가 어떻게 격리될 것인지; 4) 성능이 현재 환자 집단 및 치료 표준을 대표하도록 오래된 데이터가 최신 데이터로 보완되거나 대체될 방법; 5) 참조 표준이 정답을 결정하기 위한 최상의 이용 가능한 프로세스를 나타내는지 여부; 그리고 6) 데이터 관리 관행이 차별적 결과를 생성할 가능성을 어떻게 줄일 수 있는지를 포함하여 AI-DSF에 대한 각 수정사항을 지원하는 데 사용될 제조업체의 데이터 관리 관행을 이해할 수 있다. 데이터 관리 관행에 대한 명확한 설명은 또한 AI-DSF에 대한 수정사항이 기기의 사용 적응증을 대표하는 데이터를 기반으로 한다는 것을 FDA에 보증한다. 여기에는 AI-DSF에 대한 입력으로 데이터를 생성하는 데 사용될 제품, 기기가 사용될 환자 집단, 그리고 기기가 사용될 임상 시나리오에 관한 정보가 포함된다.

*제조업체가 신청서에 포함해야 할 것:* 제조업체가 데이터 관리 관행을 설명하는 수정 프로토콜에 제공해야 하는 정보 유형의 예시는 부록 A에 제공된다. 일반적으로, 이 정보는 다음을 설명해야 한다: 포함/제외 기준이 있는 임상 연구 프로토콜을 포함하여 데이터가 수집되는 방법; 데이터가 처리, 저장 및 보유[^101]되는 방법에 대한 정보; 참조 표준을 결정하기 위해 따라야 할 프로세스; 참조 표준(정답을 나타냄)을 결정하기 위해 임상의 해석이 사용되는 경우, 참조 표준이 어떻게 결정되는지 설명하는 프로토콜; 데이터와 관련된 품질 보증 프로세스; 데이터 수집 중에 데이터를 훈련, 튜닝 및 테스트 세트로 분리하기 위해 따라야 할 데이터 격리 전략; 그리고 성능 테스트를 위한 데이터에 대한 훈련, 튜닝 및 테스트 프로세스 중 접근을 방지하기 위한 프로토콜.

### (2) 재훈련 관행

*그것이 무엇인가:* AI 소프트웨어는 일반적으로 AI-DSF가 입력 데이터를 받는 시점부터 출력을 제공하는 시점까지 여러 처리 단계를 포함한다. 수정 프로토콜의 재훈련 관행 구성요소는 각 수정사항에 대해 변경의 대상이 되는 처리 단계와 제조업체가 AI-DSF에 대한 수정사항을 구현하는 데 사용할 방법을 식별해야 한다. 또한, 재훈련이 아키텍처 수정사항(예: 신경망에서 훈련 하이퍼파라미터 또는 노드, 레이어 등의 수 수정)을 포함하는 경우, 수정 프로토콜의 재훈련 관행 구성요소는 또한 각 특정 아키텍처 수정사항에 대한 근거 또는 정당성을 설명해야 한다.

*왜 권장되는가:* 제조업체의 재훈련 관행에 대한 정보를 통해 FDA는 제안된 수정사항이 재훈련을 통해 어떻게 달성될 것인지 이해하고, 수정사항이 적절하고 잘 정의된 관행에 따라 구현되는지 판단하며[^102], 성능 평가 및 업데이트 절차(아래에서 논의)가 수정사항을 지원하는지 판단할 수 있다. 제조업체의 재훈련 관행에 대한 정보는 일반적으로 FDA가 검토하는 대부분의 AI-DSF에 대한 시판 신청서의 "기기 설명"에 제공된다. 수정 프로토콜의 이 구성요소에 포함되어야 할 구체적인 내용은 수정사항의 유형 및 특정 기기에 따라 달라질 것이다.

*제조업체가 신청서에 포함해야 할 것:* 제조업체가 재훈련 관행을 설명하는 수정 프로토콜에 제공해야 하는 정보 유형의 예시는 부록 A에 제공된다. 일반적으로, 이 정보는 재훈련 프로세스의 목표를 식별하고, AI 모델에 대한 설명을 제공하며, 수정될 수 있는 기기 구성요소를 식별하고, 따라야 할 관행(예: 재훈련 중 데이터 격리 전략)을 개괄하며, 재훈련을 위한 트리거(예: 새로운 데이터의 양이 특정 크기에 도달하는 경우 또는 시간 경과에 따른 데이터의 드리프트가 관찰되는 경우)를 식별해야 한다.

### (3) 성능 평가

*그것이 무엇인가:* FDA는 계획에 따라 이루어진 변경사항에 대한 성능 요건을 PCCP에 제공하도록 요구할 수 있다[^103]. 성능 평가 방법은 수정사항의 일부가 아니지만 수정사항에 의해 영향을 받을 수 있는 사양을 유지하는 것 외에도, 수정된 AI-DSF가 특정 수정사항의 일부로서 식별된 사양을 충족할 것임을 검증하고 확인하기 위해 따라야 할 프로세스를 설명해야 한다. 성능 평가는 해당되는 경우 각 개별 수정사항의 구현에 따른 그리고 계획된 수정사항에 대한 총체적인 전체 기기의 검증 및 확인 계획을 포함해야 한다. 여기에는 새로 수정된 기기를 원래 기기(수정사항이 구현되지 않은 버전의 기기) 및 마지막으로 수정된 버전의 기기 모두와 비교하는 AI 모델 테스트 프로토콜이 포함되지만 이에 국한되지 않는다. 예를 들어, 하드웨어 기능을 구동하는 기기 소프트웨어 기능의 경우, 성능 평가는 기기 소프트웨어 기능뿐만 아니라 하드웨어 기능에 대한 수정사항의 영향도 포함해야 한다. 수정 프로토콜의 이 섹션의 내용은 각 계획된 수정사항에 대한 연구 설계, 성능 지표, 사전 정의된 수용 기준 및 통계적 테스트에 대한 세부사항을 제공해야 한다. 더 포괄적인 테스트는 잠재적으로 더 광범위한 제안된 수정사항 세트를 지원할 수 있다.

*왜 권장되는가:* 제조업체의 성능 평가 방법에 관한 정보를 통해 FDA는 전체 기기 성능에 대한 수정사항의 영향을 평가하기 위해 성능 지표 및 통계적 테스트를 포함한 적절한 연구 설계가 사용될 것임을 확인할 수 있다. 기기의 성능 평가는 모든 제안된 수정사항에 대한 명시된 수용 기준이 기기의 사양에 대해 계속 충족될 것임을 보장하는 데 중요하다.

*제조업체가 신청서에 포함해야 할 것:* 제조업체가 성능 평가를 설명하는 수정 프로토콜에 제공해야 하는 정보 유형의 예시는 부록 A에 제공된다. 일반적으로, 이 정보는 성능 평가가 어떻게 트리거될 것인지; 임상 집단 및 의도된 용도를 대표하는 격리된 테스트 데이터가 테스트에 어떻게 적용될 것인지; 어떤 성능 지표가 계산될 것인지; 그리고 각 수정사항에 대한 성능 목표와 관련된 가설을 테스트하기 위해 어떤 통계적 분석 계획이 사용될 것인지를 설명해야 한다. 수정 프로토콜은 또한 특정 수정사항에 대한 성능 평가에 해결할 수 없는 실패가 있는 경우(예: 특정 수정사항에 대한 사전 정의된 수용 기준이 충족되지 않음), 실패가 기록될 것이며 특정 수정사항이 구현되지 않을 것임을 확인적으로 명시해야 한다. 실패의 근본 원인 분석이 그것이 PCCP의 특정 측면과 관련이 없음을 밝히는 경우 실패는 해결할 수 없는 것으로 간주되지 않을 것이며, 그러한 경우 성능 테스트가 다시 수행될 수 있다.

### (4) 업데이트 절차

*그것이 무엇인가:* 위에서 설명한 데이터 관리 관행, 재훈련 관행 및 성능 평가는 주로 AI-DSF에 대한 수정사항을 만들고 테스트하는 것과 관련이 있다. 이것들이 성능 목표를 충족하면, 제조업체는 수정사항을 구현하고 기기를 안전하게 사용하는 데 필요한 수정사항에 대한 정보를 사용자에게 전달하기 위해 AI-DSF를 업데이트해야 할 것이다. 업데이트 절차는 어떤 계획된 수정사항이 자동으로 구현될 것인지, 수동으로 구현될 것인지, 또는 두 가지의 조합인지를 명확하게 설명하고, 제조업체가 이 정보를 사용자에게 전달할 계획을 어떻게 세울 것인지를 설명해야 한다. 수정 프로토콜의 업데이트 절차는 제조업체가 QSR과 일치하게 수정사항을 구현하기 위해 기기를 어떻게 업데이트할 것인지 설명하고, 그러한 수정사항에 적절한 경우 사용자에게 적절한 투명성을 제공하고 업데이트된 사용자 교육을 제공해야 한다[^104]. 제조업체는 또한 기기가 승인된 PCCP에 따라 의도대로 기능하지 않는 경우 실제 감시 계획 및 절차, 그리고 통지 요건을 포함할 수 있는 시판 후 감시 계획을 설명해야 한다[^105]. 기기가 안전하고 효과적으로 유지되도록 보장하는 제조업체의 책임의 일부로서, FDA는 제조업체가 수정사항이 승인된 PCCP와 일치하게 구현됨에 따라 시간이 지남에 따라 기기의 안전성(예: 부작용) 및 효과성(예: 성능)을 모니터링할 것으로 예상한다. 모니터링 활동은 업데이트가 수동으로 배포되는지 자동으로 배포되는지, 또는 업데이트가 전역적으로 또는 지역적으로 배포되는지에 따라 달라질 수 있다.

수정 프로토콜의 업데이트 절차는 또한 수정사항이 구현될 때 적절하게 라벨링이 어떻게 업데이트될 것인지를 다루어야 한다[^106]. 수정사항의 구현에 의해 영향을 받을 것으로 예상되는 라벨링 섹션에 대한 설명도 포함해야 한다. 이용 가능한 라벨링은 사용을 위한 적절한 지침을 포함해야 한다[^107]. 이용 가능한 라벨링은 또한 사이트별 수정사항에 대한 정보를 포함하여 사용자가 이용할 수 있는 AI-DSF의 현재 버전에 대한 정보를 반영해야 한다. 라벨에 UDI를 부착해야 하는 기기의 경우 새로운 버전 및/또는 모델이 있는 경우, 그리고 새로운 기기 패키지의 경우 새로운 고유 기기 식별자(UDI)가 필요하다[^108]. FDA는 라벨링이 구현되지 않은 수정사항에 대한 정보를 포함하지 않을 것을 권장하는데, 이는 혼란을 야기하고 오해의 소지가 있을 수 있기 때문이다. 또한, 라벨링이 AI-DSF에 대한 수정사항이 구현되지 않았는데 구현되었다고 명시하는 경우, 기기가 잘못된 상표가 붙은 것으로 간주될 수 있다[^109].

*왜 권장되는가:* 제조업체의 업데이트 절차에 대한 정보를 통해 FDA는 1) 수정사항 구현으로 인한 위험이 업데이트 프로세스에 의해 어떻게 완화될 수 있는지; 2) 기기 업데이트에 관한 의사소통이 사용자에게 어떻게 제공될 것인지(예: 기기 출력 결과의 업데이트가 사용자에 의해 올바르게 해석되도록); 3) 업데이트 후 기기 작동이 어떻게 안전하고 효과적으로 유지될 것인지; 그리고 4) 모든 사용자가 기기 기능 및 성능에 대해 어떻게 최신 정보를 유지할 것인지를 이해할 수 있다. 또한, 업데이트 프로세스 자체와 관련된 잠재적 위험이 어떻게 완화될 수 있는지를 FDA가 이해하는 것이 중요하다.

*제조업체가 신청서에 포함해야 할 것:* 제조업체가 업데이트 절차를 설명하는 수정 프로토콜에 제공해야 하는 정보 유형의 예시는 부록 A에 제공된다. 일반적으로, 이 정보는 1) 기기의 수정된 버전에 대한 검증 및 확인 계획이 수정사항 구현 전 기기 버전에 대해 수행된 것과 동일하거나, 두 계획 간의 차이점 식별에 대한 확인; 2) 소프트웨어 업데이트가 어떻게 구현될 것인지에 대한 설명; 3) 레거시 사용자가 소프트웨어 업데이트에 의해 어떻게 영향을 받을 것인지에 대한 설명(해당되는 경우); 그리고 4) 성능 또는 기기 입력의 차이 및/또는 업데이트에서 해결된 알려진 문제에 대한 투명성을 포함하여 수정사항이 사용자에게 어떻게 전달될 것인지에 대한 설명을 포함해야 한다. 성능 변경의 전달은 수정 프로토콜에 설명된 성능 평가와 일치해야 한다.

## C. 수정사항 설명 섹션과 수정 프로토콜 섹션 간의 추적 가능성

PCCP는 수정 프로토콜의 어떤 부분이 수정사항 설명 내의 각 수정사항에 적용 가능한지를 명확하게 설명해야 한다. 여러 수정사항이 있는 PCCP의 경우, 이것은 추적 가능성 표를 통해 달성될 수 있다; 샘플 추적 가능성 표는 아래 표 1에 제공된다. 이 샘플 추적 가능성 표는 제조업체가 수정사항 설명과 수정 프로토콜 간의 추적 가능성을 나타내는 방법과 시판 신청서에서 이 정보가 위치한 곳에 대한 명확한 참조를 제공하는 방법의 예를 제공한다. 즉, 추적 가능성 표는 각 수정사항을 지원하는 각 방법이 시판 신청서의 어디에서 찾을 수 있는지 식별하는 데 도움이 될 수 있다.

**표 1. 수정사항 설명에서 수정 프로토콜로의 추적 가능성 표 예시**

| 수정사항 | 데이터 관리 관행 | 재훈련 관행 | 성능 평가 | 업데이트 절차 |
|---------|----------------|------------|----------|-------------|
| *수정사항 #1* | *방법 A (섹션 X.A 참조)* | *방법 D (섹션 X.D 참조)* | *방법 G (섹션 X.G 참조)* | *방법 J (섹션 X.J 참조)* |
| *수정사항 #2* | *방법 A (섹션 X.A 참조)* | *방법 E (섹션 X.E 참조)* | *방법 H (섹션 X.H 참조)* | *방법 J (섹션 X.J 참조)* |
| *수정사항 #3* | *방법 B (섹션 X.B 참조)* | *방법 F (섹션 X.F 참조)* | *방법 I (섹션 X.I 참조)* | *방법 J (섹션 X.J 참조)* |

# VIII. Impact Assessment
An Impact Assessment in a PCCP is the documentation of the assessment of the benefits and risks of implementing a PCCP for an AI-DSF, as well as the mitigations of those risks. The manufacturer's existing quality system should be used as the framework in which to conduct an Impact Assessment for the modifications set forth in the PCCP.

Documentation for an Impact Assessment provided to FDA in a marketing submission containing a PCCP should:

1. Compare the version of the device with each modification implemented individually to the version of the device without any modifications implemented;
2. Discuss the benefits and risks, including risks of harm[^110] and unintended bias, of each individual modification;
3. Discuss how the verification and validation activities proposed within the Modification Protocol continue to reasonably ensure the safety and effectiveness of the device;
4. Discuss how the implementation of one modification impacts the implementation of another; and
5. Describe the cumulative impact of implementing all modifications.

FDA believes it is important to address these elements in an Impact Assessment in order to demonstrate that the combination of the proposed modifications is unlikely to introduce additional, unmitigated risks, and that the safety and effectiveness of the device is maintained as modifications are implemented.

Impact Assessment documentation for a PCCP in a marketing submission should discuss how the individual modifications included in the PCCP impact not only the AI-DSF, but also how they impact the overall functionality of the device, including how they impact other device software functions and/or device hardware. For combination products, such documentation should also discuss how the individual modifications included in the PCCP for the device constituent part impact the biologic and/or drug constituent part, and the combination product as a whole. Additionally, if the modifications in a PCCP are intended to affect any device function(s) of a multiple function device product, we recommend considering FDA's guidance "[Multiple Function Device Products: Policy and Considerations](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/multiple-function-device-products-policy-and-considerations)." In particular, as it pertains to the AI-DSF and the PCCP, it is important to determine if any information should be included in the Impact Assessment in a PCCP in a marketing submission so that FDA may assess the impact of the "other function(s)" on the safety or effectiveness of the AI-DSF as it is modified consistent with the PCCP.

Some information related to the Impact Assessment may be included elsewhere in the marketing submission, for example in sections for the risk assessment for the device or the Modification Protocol in the PCCP. As such, FDA recommends providing clear references in the Impact Assessment section of the PCCP to the relevant sections in the marketing submission that support the Impact Assessment.

[^110]: See, e.g., harm, as defined in ISO 14971 Medical devices – Application of risk management to medical devices, is the physical injury or damage to the health of people. 예를 들어, ISO 14971 의료기기 – 의료기기에 대한 위험 관리의 적용에서 정의된 위해(harm)는 사람의 건강에 대한 신체적 상해 또는 손상을 의미합니다.

# VIII. 영향 평가

PCCP의 영향 평가는 AI-DSF에 대한 PCCP 구현의 편익과 위험에 대한 평가 문서 및 해당 위험의 완화이다. 제조업체의 기존 품질 시스템은 PCCP에 명시된 수정사항에 대한 영향 평가를 수행하는 프레임워크로 사용되어야 한다.

PCCP를 포함하는 시판 신청서에서 FDA에 제공되는 영향 평가에 대한 문서는 다음을 수행해야 한다:

1. 각 수정사항이 개별적으로 구현된 기기의 버전을 수정사항이 구현되지 않은 기기의 버전과 비교한다;
2. 각 개별 수정사항의 위해 위험[^110] 및 의도하지 않은 편향을 포함한 편익과 위험을 논의한다;
3. 수정 프로토콜 내에서 제안된 검증 및 확인 활동이 기기의 안전성과 효과성을 어떻게 합리적으로 계속 보장하는지 논의한다;
4. 한 수정사항의 구현이 다른 수정사항의 구현에 어떻게 영향을 미치는지 논의한다; 그리고
5. 모든 수정사항을 구현하는 누적 영향을 설명한다.

FDA는 제안된 수정사항의 조합이 추가적이고 완화되지 않은 위험을 도입할 가능성이 낮으며 수정사항이 구현됨에 따라 기기의 안전성과 효과성이 유지된다는 것을 입증하기 위해 영향 평가에서 이러한 요소를 다루는 것이 중요하다고 판단한다.

시판 신청서에서 PCCP에 대한 영향 평가 문서는 PCCP에 포함된 개별 수정사항이 AI-DSF뿐만 아니라 다른 기기 소프트웨어 기능 및/또는 기기 하드웨어에 미치는 영향을 포함하여 기기의 전체 기능에 어떻게 영향을 미치는지 논의해야 한다. 복합 제품의 경우, 그러한 문서는 또한 기기 구성 부분에 대한 PCCP에 포함된 개별 수정사항이 생물학적 제제 및/또는 의약품 구성 부분, 그리고 복합 제품 전체에 어떻게 영향을 미치는지 논의해야 한다. 또한, PCCP의 수정사항이 다기능 기기 제품의 기기 기능에 영향을 미치기 위한 것인 경우, FDA의 가이던스 "[다기능 기기 제품: 정책 및 고려사항(Multiple Function Device Products: Policy and Considerations)](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/multiple-function-device-products-policy-and-considerations)"을 고려할 것을 권장한다. 특히, AI-DSF 및 PCCP와 관련하여, FDA가 AI-DSF가 PCCP와 일치하게 수정됨에 따라 AI-DSF의 안전성 또는 효과성에 대한 "기타 기능"의 영향을 평가할 수 있도록 시판 신청서의 PCCP의 영향 평가에 어떤 정보를 포함해야 하는지 결정하는 것이 중요하다.

영향 평가와 관련된 일부 정보는 예를 들어 기기에 대한 위험 평가 또는 PCCP의 수정 프로토콜에 대한 섹션과 같이 시판 신청서의 다른 곳에 포함될 수 있다. 따라서 FDA는 영향 평가를 지원하는 시판 신청서의 관련 섹션에 대한 명확한 참조를 PCCP의 영향 평가 섹션에 제공할 것을 권장한다.

# Appendix A: Example Elements of Modification Protocol Components for AI-DSFs

In general, a Modification Protocol that is included as part of a PCCP in a marketing submission should include four components that outline a manufacturer's 1) data management practices, 2) re-training practices, 3) performance evaluation protocols, and 4) update procedures, for each modification in the Description of Modifications for the AI-DSF. However, manufacturers may include other or additional components if they believe that their proposed protocols do not fit into any of these four components. To help illustrate the level of detail and additional information that may be helpful to include in a marketing submission, this appendix includes examples of questions for consideration and the types of information manufacturers should provide in the components of a Modification Protocol. In thinking about these questions, manufacturers should consider the intended use populations (e.g., with respect to race, ethnicity, disease severity, sex, age, or others, as appropriate) and intended environments.

Note that this is a developing area, and as FDA gains experience, these example questions may change. The items below are not an exhaustive list of topics that a manufacturer is expected to cover, and all questions may not apply to all marketing submissions. The topics and questions are provided to assist in identifying the types of information that may be helpful to provide to FDA to appropriately describe the components of a Modification Protocol. The appropriate information to provide will vary by the AI-DSF and Modification Protocol.

In certain circumstances, FDA may request additional Modification Protocol components or information to be included in a PCCP for some device types so that FDA can make a determination of reasonable assurance of safety and effectiveness or substantial equivalence when reviewing the device and PCCP[^111]. Additionally, some sections of a Modification Protocol may be more or less detailed depending on the complexity and risks of each modification in the PCCP. Overall, FDA recommends that manufacturers consider the topics and questions in this appendix for their particular AI-DSF and PCCP as a means of encouraging a detailed and methodically prepared PCCP.

## (1) Data Management

Different data can be collected and used for training, tuning, and testing AI model updates. In cases where manufacturers are collecting new training, tuning, and test data, the Modification Protocol should include how the data will be used (e.g., for AI model development or testing), and how the data management supports these uses.

**a. Collection protocols**

1.a.1. For each modification, what are the inclusion/exclusion criteria for data collection, and how are they linked to the intended use population?

1.a.2. What is the intended distribution of the data set along covariates describing the patient population (e.g., sex, age, race, height, weight, disease conditions) and data acquisition conditions (e.g., sites, data acquisition devices/methods, imaging and reconstruction protocols)? Is this distribution representative of the intended use population, including intersectional groups?

1.a.3. Will the data be collected prospectively or retrospectively? Will the data set include consecutive cases within a given date range? Otherwise, if random sampling is planned, what method or technique will be used and how will it account for bias and randomness?

1.a.4. Are there any plans for enrichment or stratified sampling, such as specific patient subgroups (e.g., sex, age, race), relevant disease subtypes (e.g., genotypic or phenotypic variants, disease burden, severity, or presentation, etc.), and/or variations in care delivery (e.g., inpatient/outpatient care settings)?

1.a.5. What is the number and geographical distribution of data collection sites?

1.a.6. What are the measures to mitigate potential unwanted bias in learning or performance estimation, for example, due to issues related to new training, tuning, or test data, respectively?

1.a.7. What are the strategies and measures to understand and mitigate potential biases in the data, such as those due to historical inequalities to medical treatment access by different populations?

1.a.8. What are the strategies to ensure data sets remain relevant over time with respect to changes in, for example, data acquisition technologies or protocols, clinical practice, patient populations, and disease conditions?

1.a.9. Are data collection, storage, retention, and use protocols in compliance with regulations for human subject protections and requirements for clinical investigations (e.g., pursuant to 21 CFR Part 812, 45 CFR Part 46, 21 CFR Part 50, and 21 CFR Part 56, as applicable)?

1.a.10. For AI-DSFs that use input data from dedicated acquisition systems (e.g., software device functions in a patient monitor that uses connected sensors), are the data acquired with the systems and settings with which the AI-DSF will be used? For device software functions that use input data from different acquisition systems (e.g., interoperable medical devices), do the data acquired meet the input specifications of the AI-DSF?

**b. Assurance of data quality**

1.b.1. What processes are in place to ensure data consistency and completeness are maintained during data collection for training, tuning, and test data?

1.b.2. What are the strategies used to promote data authenticity, transparency, and integrity?

1.b.3. How will potentially missing data elements within a case/record be handled for training, tuning, and test data?

1.b.4. Are there criteria for including/excluding cases/records based on data quality (in addition to inclusion/exclusion criteria listed in 1.a.1. above), and if so, what are the criteria and rationale?

1.b.5. If data might be excluded as a result of the quality assurance process, what methods are planned to minimize the impact on the generalizability of training and accuracy of testing?

1.b.6. What are the traceability methods or strategies that will be used to identify and investigate data issues?

1.b.7. Will data that are obsolete or no longer needed be removed? If so, what are the criteria for data removal, and what strategies will be used to appropriately manage data removal in a consistent manner?

1.b.8. What controls are in place to prevent and identify unauthorized access or manipulation of the training, tuning, and test data sets? For example, what controls are in place to prevent malicious addition or deletion of data for the purpose of impacting model performance, introducing bias, or overtraining on repeated data, among others?

1.b.9. Is there an automated process to ensure data quality, and if so, what is the process?

**c. Reference standard determination**

For purposes of this guidance, the reference standard is the most suitable standard to define the true condition for each patient/case/record. The PCCP should include a rationale for the determination of the "most suitable standard," which may include consideration of device risk. The reference standard may be used during training, tuning, testing, or all three.

1.c.1. What is the justification for the method for the determination of the reference standard?

1.c.2. If the reference standard is based on evaluations from clinicians, what was the grading protocol used (e.g., what is the total number of clinicians who participated and their qualifications; what data are these clinicians provided with; and how are the clinicians' evaluations collected/adjudicated for determining the reference standard)?

1.c.3. What is the strategy for addressing cases where results obtained using a reference standard may be equivocal or missing?

1.c.4. What is the uncertainty inherent in the reference standard?

1.c.5. Will any of the methods for determining the reference standard be automated? Are there differences between the reference standards used for training/tuning/testing?

1.c.6. Are there differences between the reference standard used to support the initial AI-DSF marketing authorization and the reference standard being applied to update the AI model?

**d. Sequestration of test data sets**

For purposes of this guidance, sequestration of test data sets means that manufacturers do not have access to the test data set for the purpose of AI-DSF development.

1.d.1. What strategies will be employed at the outset of data collection to shield the test data set from the AI-DSF development?

1.d.2. What are the specific procedures to be followed so that the test data set remains sequestered during re-training?

1.d.3. If test data are planned to be used multiple times for performance evaluation, what measures are in place to prevent unwanted bias from being introduced through AI model manufacturers learning substantial information about the test data set and results?

1.d.4. What are the descriptive statistics (e.g., covariate range, mean, median) for each data set and how similar are they to those for the intended use population?

## (2) Re-Training

**a. Re-training objectives and focus**

2.a.1. How are the modifications presented in the Description of Modifications in the PCCP related to the planned re-training methods?

2.a.2. Which parts of the AI-DSF are planned to be modified (e.g., transfer learning, data pre-processing, data augmentation, only a certain set of coefficients, architecture and hyperparameters, loss functions, optimization methods and criteria, types of AI model inputs and outputs), and what are the details of the planned modifications to the AI-DSF design? What is the specific rationale for the change to each part that is planned to be modified?

2.a.3. For each part of the AI-DSF that will be modified, is AI model re-training needed to achieve the modifications specified in the PCCP?

2.a.4. If re-training applies to only certain parts of the AI-DSF, what are the plans to ensure that other functions or software components are not affected?

**b. Re-training implementation**

2.b.1. What are the triggers for re-training (e.g., when new data reaches a certain size, when a drift is observed, periodically in time)?

2.b.2. What strategies will be employed to identify and limit overfitting?

2.b.3. Are there risks related to AI model bias introduced by re-training a modified AI model, and if so, what are planned mitigations?

## (3) Performance Evaluation

**a. Triggers to initiate performance evaluation**

3.a.1. What are the triggers for initiating performance evaluation of a re-trained AI model or modified AI-DSF (e.g., re-training shows a certain performance level on the training or tuning data, test data reaches a certain size, periodically in time)?

3.a.2. How frequently is this expected to occur?

**b. Assessment metrics and elements**

3.b.1. How are the plans for data management in (1) above applied to produce the test data for performance evaluation that are different from any training or tuning data?

3.b.2. What metrics will be computed to understand device performance?

3.b.3. How do these metrics demonstrate that the modified device can be safely used?

3.b.4. How will the metrics provide a comprehensive assessment of device performance and patient safety?

3.b.5. What challenging cases (i.e., cases outside the norm) or known challenging scenarios will be evaluated?

**c. Statistical analysis plans**

3.c.1. What is the plan for evaluating equivalent or improved performance with respect to previously validated versions, including the original version, of the AI-DSF?

3.c.2. What are the high-risk subpopulations and subgroups (e.g., acquisition protocols) that need to be evaluated?

3.c.3. How will this evaluation be used to support labeling specifications?

3.c.4. How will you test that performance in one area (e.g., sensitivity) does not result in unacceptable degrading performance in another (e.g., specificity)?

3.c.5. How will the sample size be determined?

3.c.6. Is the primary analysis based on the intention-to-diagnose population (no study subjects will be excluded) or the per-protocol population (subjects with protocol violations will be excluded)?

3.c.7. How is variability in the reference standard accounted for (e.g., in the case of reader variability when clinical interpretation is used)? When the reference standard may be imperfect (e.g., sometimes includes a diagnostic error), are errors made by the imperfect reference standard conditionally independent of errors made by the AI-DSF, or are they positively correlated?

3.c.8. How will missing data and outliers be addressed in analysis?

**d. Performance targets**

3.d.1. What are the acceptance criteria? If applicable, how do the acceptance criteria compare to the acceptance criteria for the authorized version of the device?

3.d.2. What clinical considerations were used to develop the acceptance criteria?

3.d.3. How will the acceptance criteria support that the modification will be successfully implemented?

**e. Additional testing needs**

3.e.1. Is database testing sufficient to address the risks associated with the proposed modification (e.g., does the user need to interact with the device to evaluate the performance or address a clinical risk or, for software that is part of a hardware device[^112], how is the effect of the modification on hardware functionality evaluated)?

3.e.2. How may clinical usability need to be addressed for a modification?

## (4) Update Procedures

**a. Software verification and validation**

4.a.1. Does the proposed modification necessitate a different software verification and validation plan from that used for the version of the device without any modifications implemented?

4.a.2. What type of testing will be performed? Does the AI-DSF need to be validated to function in an integrated environment, where interoperable, heterogeneous medical devices and other equipment are combined (e.g., when the input to the AI-DSF originates from other devices or when the output of the AI-DSF affects other devices or equipment for patient care)?

4.a.3. If the device includes other device functions in addition to the AI-DSF, how will the impact of modifications to the AI-DSF on the other device functions be evaluated?

4.a.4. If the device includes "other functions" in addition to the AI-DSF, how will the "other functions'" impact on the safety or effectiveness of the modified AI-DSF be evaluated?

**b. When and how updates will be implemented**

4.b.1. How will the decision be made on when to perform an update? What is the expected timeline for implementing the modifications? Is there a set frequency of updates?

4.b.2. When and how will an update be implemented (e.g., automatically when the device is not being used, manually by users or hospital technicians, or both manually and automatically)? What is the basis on which the mechanism of implementation is dependent?

4.b.3. For AI-DSF updates to reusable medical equipment, how will the device operation, including function of critical safety features (e.g., medical device alarms), be verified following the update?

4.b.4. Will updates be made globally (i.e., the same update applied to all devices in the field) or locally (e.g., the devices may be modified for a patient/provider/care unit/hospital)?

4.b.5. What cybersecurity risk management and validation processes[^113] are used in accordance with the documentation and processes provided for Section VI.B and Appendix 1.H of the FDA guidance "[Cybersecurity in Medical Devices: Quality System Considerations and Content of Premarket Submissions](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/cybersecurity-medical-devices-quality-system-considerations-and-content-premarket-submissions)"?

**c. Communication and transparency to users**

4.c.1. How will the PCCP be described in the public summary document and/or labeling?

4.c.2. How will updates be communicated to users, including, but not limited to, in updated labeling (e.g., release notes)?

4.c.3. What information about modifications to the device (e.g., performance) will be communicated to the user?

4.c.4. How will version information be presented to the user when reviewing device outputs?

4.c.5. Will users have the option to review labeling before implementing an update or be provided the option to opt out of the update?

4.c.6. How will any known biases or other performance issues with the potential to result in individual or unintended bias be disclosed, including, but not limited to, in labeling?

4.c.7. How will any changes in performance related to known issues or sources of bias be communicated to the user, including, but not limited to, in labeling?

4.c.8. What information about the population and methods for validation will be provided?

4.c.9. If patient data from previous device use is available and can be rerun on an updated AI model, will this activity be performed for the available data and will those updated results be available to patients and users? Is there a plan to communicate if patient results before and after an update would provide clinically meaningful differences?

**d. Device monitoring plan**

4.d.1. How will adverse events be tracked for different updates?

4.d.2. Is there a risk-based plan to monitor real-world device performance (beyond general controls) and, if not, why is it not necessary? In an effort to be transparent, will a monitoring plan be provided to the users on the performance of the AI-DSF post implementation?

4.d.3. To be transparent for users, will information about monitoring real-world device performance be provided (e.g., to inform users about the safety performance of the device following implementation of modifications), and if not, why is it not necessary?

4.d.4. How will changes in safety (e.g., adverse events, identification of new or previously unknown risks) and effectiveness (e.g., performance, identification of previously unknown biases) for manually or automatically deployed modifications be monitored, and with what frequency?

4.d.5. How will changes in performance in patient subpopulations be identified?

4.d.6. What will be the response to the identification of previously unknown risks or previously unrecognized high-risk patient subpopulations?

4.d.7. What is the strategy to respond to unexpected performance deficiencies or other hazards, or to higher levels of adverse events, as compared with previous iterations of the device?

4.d.8. How will errors in diagnosis (i.e., misdiagnosis), attributable or partially attributable to the device that do not meet the criteria for an adverse event, be tracked?

4.d.9. Will there be criteria and/or a plan to roll-back an update to reset devices to a previous version, if applicable?

[^111]: Such information would be required in the marketing submission pursuant to e.g., sections 513(i)(1) and 515C of the FD&C Act, and 21 CFR 807.81(a)(3), 21 CFR 814.39(a), 21 CFR 860.7. 그러한 정보는 예를 들어 FD&C Act의 섹션 513(i)(1) 및 515C, 그리고 21 CFR 807.81(a)(3), 21 CFR 814.39(a), 21 CFR 860.7에 따라 마케팅 제출에서 요구됩니다.

[^112]: For purposes of this guidance, "part of a hardware device" means the software is used to control a device, or the software is necessary for a hardware device to achieve its intended use. 이 가이던스의 목적상, "하드웨어 기기의 일부"는 소프트웨어가 기기를 제어하는 데 사용되거나, 하드웨어 기기가 의도된 용도를 달성하는 데 소프트웨어가 필요한 것을 의미합니다.

[^113]: For recommendations related to cybersecurity, please consult FDA guidance documents on this topic, including "[Cybersecurity in Medical Devices: Quality System Considerations and Content of Premarket Submissions](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/cybersecurity-medical-devices-quality-system-considerations-and-content-premarket-submissions)." 사이버보안과 관련된 권고사항은 "[의료기기의 사이버보안: 품질 시스템 고려사항 및 시판 전 제출 내용](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/cybersecurity-medical-devices-quality-system-considerations-and-content-premarket-submissions)"을 포함한 이 주제에 대한 FDA 가이던스 문서를 참조하십시오.

# 부록 A: AI-DSF에 대한 수정 프로토콜 구성요소의 예시 요소

일반적으로, AI-DSF에 대한 PCCP의 일부로서 시판 신청서에 포함된 수정 프로토콜은 PCCP의 수정사항 설명의 각 수정사항에 대한 제조업체의 1) 데이터 관리 관행, 2) 재훈련 관행, 3) 성능 평가 프로토콜, 4) 업데이트 절차를 개괄하는 네 가지 구성요소를 포함해야 한다. 그러나 제조업체는 제안된 프로토콜이 이러한 네 가지 구성요소에 맞지 않는다고 판단하는 경우 다른 또는 추가 구성요소를 포함할 수 있다. 시판 신청서에 포함하는 것이 도움이 될 수 있는 세부 수준 및 추가 정보를 설명하는 데 도움이 되도록, 본 부록은 고려해야 할 질문의 예시와 제조업체가 수정 프로토콜의 구성요소에 제공해야 하는 정보 유형을 포함한다. 이러한 질문을 고려할 때, 제조업체는 의도된 사용 집단(예: 인종, 민족, 질병 중증도, 성별, 연령 또는 적절한 경우 기타 특성과 관련하여) 및 의도된 사용 환경을 고려해야 한다.

이것은 개발 중인 영역이며, FDA가 경험을 쌓음에 따라 이러한 예시 질문은 변경될 수 있다는 점에 유의하라. 아래 항목은 제조업체가 다루어야 할 것으로 예상되는 주제의 완전한 목록이 아니며, 모든 질문이 모든 시판 신청서에 적용되는 것은 아닐 수 있다. 주제와 질문은 수정 프로토콜의 구성요소를 적절하게 설명하기 위해 FDA에 제공하는 것이 도움이 될 수 있는 정보 유형을 식별하는 데 도움이 되도록 제공된다. 제공할 적절한 정보는 AI-DSF 및 수정 프로토콜에 따라 달라질 것이다.

특정 상황에서, FDA는 일부 기기 유형에 대한 PCCP에 추가 수정 프로토콜 구성요소 또는 정보를 포함하도록 요청하여 FDA가 기기 및 PCCP를 검토할 때 안전성과 효과성에 대한 합리적인 보증 또는 실질적 동등성을 판단할 수 있도록 할 수 있다[^111]. 또한, 수정 프로토콜의 일부 섹션은 PCCP의 각 수정사항의 복잡성과 위험에 따라 더 자세하거나 덜 자세할 수 있다. 전반적으로, FDA는 제조업체가 상세하고 체계적으로 준비된 PCCP를 장려하는 수단으로 특정 AI-DSF 및 PCCP에 대한 본 부록의 주제와 질문을 고려할 것을 권장한다.

## (1) 데이터 관리

다른 데이터를 수집하여 AI 모델 업데이트의 훈련, 튜닝 및 테스트에 사용할 수 있다. 제조업체가 새로운 훈련, 튜닝 및 테스트 데이터를 수집하는 경우, 수정 프로토콜은 데이터가 어떻게 사용될 것인지(예: AI 모델 개발 또는 테스트용), 그리고 데이터 관리가 이러한 사용을 어떻게 지원하는지를 포함해야 한다.

**a. 수집 프로토콜**

1.a.1. 각 수정사항에 대해, 데이터 수집을 위한 포함/제외 기준은 무엇이며, 의도된 사용 집단과 어떻게 연결되는가?

1.a.2. 환자 집단을 설명하는 공변량(예: 성별, 연령, 인종, 키, 체중, 질병 상태) 및 데이터 획득 조건(예: 사이트, 데이터 획득 기기/방법, 영상 및 재구성 프로토콜)을 따라 데이터 세트의 의도된 분포는 무엇인가? 이 분포는 교차 그룹을 포함하여 의도된 사용 집단을 대표하는가?

1.a.3. 데이터가 전향적으로 또는 후향적으로 수집될 것인가? 데이터 세트에 주어진 날짜 범위 내의 연속적인 사례가 포함될 것인가? 그렇지 않고, 무작위 샘플링이 계획된 경우, 어떤 방법 또는 기법이 사용될 것이며 편향과 무작위성을 어떻게 고려할 것인가?

1.a.4. 특정 환자 하위 그룹(예: 성별, 연령, 인종), 관련 질병 하위 유형(예: 유전형 또는 표현형 변이, 질병 부담, 중증도 또는 표현 등), 및/또는 치료 제공의 변화(예: 입원 환자/외래 환자 치료 환경)와 같은 강화 또는 층화 샘플링 계획이 있는가?

1.a.5. 데이터 수집 사이트의 수와 지리적 분포는 무엇인가?

1.a.6. 예를 들어 각각 새로운 훈련, 튜닝 또는 테스트 데이터와 관련된 문제로 인해 학습 또는 성능 추정에서 잠재적인 원치 않는 편향을 완화하기 위한 조치는 무엇인가?

1.a.7. 다양한 집단의 의료 치료 접근에 대한 역사적 불평등으로 인한 것과 같은 데이터의 잠재적 편향을 이해하고 완화하기 위한 전략은 무엇인가?

1.a.8. 예를 들어 데이터 획득 기술 또는 프로토콜, 임상 진료, 환자 집단 및 질병 상태의 변화와 관련하여 시간이 지남에 따라 데이터 세트가 관련성을 유지하도록 보장하기 위한 전략은 무엇인가?

1.a.9. 데이터 수집, 저장, 보유 및 사용 프로토콜이 인간 대상 보호 및 임상 조사 요건에 대한 규정을 준수하는가(예: 적용 가능한 경우 21 CFR Part 812, 45 CFR Part 46, 21 CFR Part 50, 21 CFR Part 56에 따라)?

1.a.10. 전용 획득 시스템(예: 연결된 센서를 사용하는 환자 모니터의 소프트웨어 기기 기능)의 입력 데이터를 사용하는 AI-DSF의 경우, AI-DSF가 사용될 시스템 및 설정으로 데이터가 획득되는가? 다양한 획득 시스템(예: 상호운용 가능한 의료기기)의 입력 데이터를 사용하는 기기 소프트웨어 기능의 경우, 획득된 데이터가 AI-DSF의 입력 사양을 충족하는가?

**b. 데이터 품질 보증**

1.b.1. 훈련, 튜닝 및 테스트 데이터에 대한 데이터 수집 중에 데이터 일관성과 완전성이 유지되도록 보장하기 위해 어떤 프로세스가 마련되어 있는가?

1.b.2. 데이터 진정성, 투명성 및 무결성을 촉진하기 위해 사용되는 전략은 무엇인가?

1.b.3. 훈련, 튜닝 및 테스트 데이터에 대해 사례/기록 내에서 잠재적으로 누락된 데이터 요소가 어떻게 처리될 것인가?

1.b.4. 데이터 품질에 기반하여 사례/기록을 포함/제외하기 위한 기준이 있는가(위의 1.a.1.에 나열된 포함/제외 기준 외에), 있다면 기준과 근거는 무엇인가?

1.b.5. 품질 보증 프로세스의 결과로 데이터가 제외될 수 있는 경우, 훈련의 일반화 가능성과 테스트의 정확성에 대한 영향을 최소화하기 위해 어떤 방법이 계획되어 있는가?

1.b.6. 데이터 문제를 식별하고 조사하는 데 사용될 추적 가능성 방법 또는 전략은 무엇인가?

1.b.7. 더 이상 필요하지 않거나 구식인 데이터가 제거될 것인가? 그렇다면 데이터 제거 기준은 무엇이며, 일관된 방식으로 데이터 제거를 적절하게 관리하기 위해 어떤 전략이 사용될 것인가?

1.b.8. 훈련, 튜닝 및 테스트 데이터 세트에 대한 무단 접근 또는 조작을 방지하고 식별하기 위해 어떤 관리가 마련되어 있는가? 예를 들어, 모델 성능에 영향을 미치거나, 편향을 도입하거나, 반복된 데이터에 대한 과도한 훈련 등을 목적으로 악의적인 데이터 추가 또는 삭제를 방지하기 위해 어떤 관리가 마련되어 있는가?

1.b.9. 데이터 품질을 보장하기 위한 자동화된 프로세스가 있는가, 있다면 프로세스는 무엇인가?

**c. 참조 표준 결정**

본 가이던스의 목적상, 참조 표준은 각 환자/사례/기록에 대한 실제 상태를 정의하는 데 가장 적합한 표준이다. PCCP는 "가장 적합한 표준"의 결정에 대한 근거를 포함해야 하며, 여기에는 기기 위험에 대한 고려가 포함될 수 있다. 참조 표준은 훈련, 튜닝, 테스트 또는 세 가지 모두 중에 사용될 수 있다.

1.c.1. 참조 표준 결정 방법에 대한 정당성은 무엇인가?

1.c.2. 참조 표준이 임상의의 평가를 기반으로 하는 경우, 사용된 등급 프로토콜은 무엇이었는가(예: 참여한 총 임상의 수와 자격은 무엇인가; 이 임상의들에게 어떤 데이터가 제공되는가; 그리고 참조 표준을 결정하기 위해 임상의의 평가가 어떻게 수집/판정되는가)?

1.c.3. 참조 표준을 사용하여 얻은 결과가 모호하거나 누락될 수 있는 사례를 다루기 위한 전략은 무엇인가?

1.c.4. 참조 표준에 내재된 불확실성은 무엇인가?

1.c.5. 참조 표준을 결정하는 방법 중 자동화될 것이 있는가? 훈련/튜닝/테스트에 사용되는 참조 표준 간에 차이가 있는가?

1.c.6. 초기 AI-DSF 시판 승인을 지원하는 데 사용된 참조 표준과 AI 모델을 업데이트하기 위해 적용되는 참조 표준 간에 차이가 있는가?

**d. 테스트 데이터 세트의 격리**

본 가이던스의 목적상, 테스트 데이터 세트의 격리는 제조업체가 AI-DSF 개발 목적으로 테스트 데이터 세트에 접근하지 않음을 의미한다.

1.d.1. 데이터 수집 초기에 AI-DSF 개발로부터 테스트 데이터 세트를 차단하기 위해 어떤 전략이 사용될 것인가?

1.d.2. 재훈련 중에 테스트 데이터 세트가 격리된 상태로 유지되도록 따라야 할 구체적인 절차는 무엇인가?

1.d.3. 테스트 데이터가 성능 평가를 위해 여러 번 사용될 계획인 경우, AI 모델 제조업체가 테스트 데이터 세트 및 결과에 대한 상당한 정보를 학습하여 원치 않는 편향이 도입되는 것을 방지하기 위해 어떤 조치가 마련되어 있는가?

1.d.4. 각 데이터 세트에 대한 기술 통계(예: 공변량 범위, 평균, 중앙값)는 무엇이며 의도된 사용 집단에 대한 것과 얼마나 유사한가?

## (2) 재훈련

**a. 재훈련 목표 및 초점**

2.a.1. PCCP의 수정사항 설명에 제시된 수정사항이 계획된 재훈련 방법과 어떻게 관련되는가?

2.a.2. AI-DSF의 어떤 부분이 수정될 계획인가(예: 전이 학습, 데이터 전처리, 데이터 증강, 특정 계수 세트만, 아키텍처 및 하이퍼파라미터, 손실 함수, 최적화 방법 및 기준, AI 모델 입력 및 출력의 유형), 그리고 AI-DSF 설계에 대한 계획된 수정사항의 세부사항은 무엇인가? 수정될 계획인 각 부분에 대한 변경의 구체적인 근거는 무엇인가?

2.a.3. 수정될 AI-DSF의 각 부분에 대해, PCCP에 명시된 수정사항을 달성하기 위해 AI 모델 재훈련이 필요한가?

2.a.4. 재훈련이 AI-DSF의 특정 부분에만 적용되는 경우, 다른 기능이나 소프트웨어 구성요소가 영향을 받지 않도록 보장하기 위한 계획은 무엇인가?

**b. 재훈련 구현**

2.b.1. 재훈련을 위한 트리거는 무엇인가(예: 새로운 데이터가 특정 크기에 도달하는 경우, 드리프트가 관찰되는 경우, 시간상 주기적으로)?

2.b.2. 과적합을 식별하고 제한하기 위해 어떤 전략이 사용될 것인가?

2.b.3. 수정된 AI 모델을 재훈련하여 도입된 AI 모델 편향과 관련된 위험이 있는가, 있다면 계획된 완화 조치는 무엇인가?

## (3) 성능 평가

**a. 성능 평가를 시작하는 트리거**

3.a.1. 재훈련된 AI 모델 또는 수정된 AI-DSF의 성능 평가를 시작하는 트리거는 무엇인가(예: 재훈련이 훈련 또는 튜닝 데이터에서 특정 성능 수준을 보여주는 경우, 테스트 데이터가 특정 크기에 도달하는 경우, 시간상 주기적으로)?

3.a.2. 이것이 발생할 것으로 예상되는 빈도는 어떻게 되는가?

**b. 평가 지표 및 요소**

3.b.1. (1) 위의 데이터 관리 계획이 훈련 또는 튜닝 데이터와 다른 성능 평가를 위한 테스트 데이터를 생성하기 위해 어떻게 적용되는가?

3.b.2. 기기 성능을 이해하기 위해 어떤 지표가 계산될 것인가?

3.b.3. 이러한 지표는 수정된 기기가 안전하게 사용될 수 있음을 어떻게 입증하는가?

3.b.4. 이 지표는 기기 성능과 환자 안전에 대한 포괄적인 평가를 어떻게 제공할 것인가?

3.b.5. 어떤 도전적인 사례(즉, 표준을 벗어난 사례) 또는 알려진 도전적인 시나리오가 평가될 것인가?

**c. 통계적 분석 계획**

3.c.1. AI-DSF의 이전에 검증된 버전(원래 버전 포함)과 관련하여 동등하거나 개선된 성능을 평가하기 위한 계획은 무엇인가?

3.c.2. 평가가 필요한 고위험 하위 집단과 하위 그룹(예: 획득 프로토콜)은 무엇인가?

3.c.3. 이 평가가 라벨링 사양을 지원하기 위해 어떻게 사용될 것인가?

3.c.4. 한 영역(예: 민감도)의 성능이 다른 영역(예: 특이도)의 허용할 수 없는 성능 저하를 초래하지 않는다는 것을 어떻게 테스트할 것인가?

3.c.5. 표본 크기는 어떻게 결정될 것인가?

3.c.6. 주 분석이 진단 의도 집단(연구 대상자가 제외되지 않음) 또는 프로토콜별 집단(프로토콜 위반이 있는 대상자가 제외됨)을 기반으로 하는가?

3.c.7. 참조 표준의 변동성이 어떻게 설명되는가(예: 임상 해석이 사용되는 경우 판독자 변동성의 경우)? 참조 표준이 불완전할 수 있는 경우(예: 때때로 진단 오류를 포함), 불완전한 참조 표준에 의해 만들어진 오류가 AI-DSF에 의해 만들어진 오류와 조건부로 독립적인가, 아니면 양의 상관관계가 있는가?

3.c.8. 누락된 데이터와 이상치가 분석에서 어떻게 다루어질 것인가?

**d. 성능 목표**

3.d.1. 수용 기준은 무엇인가? 해당되는 경우, 수용 기준이 기기의 승인된 버전에 대한 수용 기준과 어떻게 비교되는가?

3.d.2. 수용 기준을 개발하기 위해 어떤 임상적 고려사항이 사용되었는가?

3.d.3. 수용 기준이 수정사항이 성공적으로 구현될 것임을 어떻게 지원할 것인가?

**e. 추가 테스트 필요사항**

3.e.1. 데이터베이스 테스트가 제안된 수정사항과 관련된 위험을 다루기에 충분한가(예: 성능을 평가하거나 임상적 위험을 다루기 위해 사용자가 기기와 상호작용해야 하는가, 또는 하드웨어 기기의 일부인 소프트웨어[^112]의 경우 하드웨어 기능에 대한 수정사항의 영향이 어떻게 평가되는가)?

3.e.2. 수정사항에 대해 임상적 사용성이 어떻게 다루어져야 하는가?

## (4) 업데이트 절차

**a. 소프트웨어 검증 및 확인**

4.a.1. 제안된 수정사항이 수정사항이 구현되지 않은 기기 버전에 사용된 것과 다른 소프트웨어 검증 및 확인 계획을 필요로 하는가?

4.a.2. 어떤 유형의 테스트가 수행될 것인가? AI-DSF가 상호운용 가능하고 이질적인 의료기기 및 기타 장비가 결합된 통합 환경에서 기능하도록 검증되어야 하는가(예: AI-DSF에 대한 입력이 다른 기기에서 시작되거나 AI-DSF의 출력이 환자 치료를 위한 다른 기기 또는 장비에 영향을 미치는 경우)?

4.a.3. 기기가 AI-DSF 외에 다른 기기 기능을 포함하는 경우, AI-DSF에 대한 수정사항이 다른 기기 기능에 미치는 영향이 어떻게 평가될 것인가?

4.a.4. 기기가 AI-DSF 외에 "기타 기능"을 포함하는 경우, 수정된 AI-DSF의 안전성 또는 효과성에 대한 "기타 기능"의 영향이 어떻게 평가될 것인가?

**b. 업데이트가 언제 그리고 어떻게 구현될 것인가**

4.b.1. 업데이트를 수행할 시기에 대한 결정이 어떻게 이루어질 것인가? 수정사항 구현을 위한 예상 일정은 무엇인가? 설정된 업데이트 빈도가 있는가?

4.b.2. 업데이트가 언제 그리고 어떻게 구현될 것인가(예: 기기가 사용되지 않을 때 자동으로, 사용자 또는 병원 기술자에 의해 수동으로, 또는 수동 및 자동 모두)? 구현 메커니즘이 의존하는 기준은 무엇인가?

4.b.3. 재사용 가능한 의료 장비에 대한 AI-DSF 업데이트의 경우, 업데이트 후 중요한 안전 기능(예: 의료기기 경보)의 기능을 포함한 기기 작동이 어떻게 검증될 것인가?

4.b.4. 업데이트가 전역적으로(즉, 현장의 모든 기기에 동일한 업데이트 적용) 또는 지역적으로(예: 기기가 환자/의료 제공자/치료 단위/병원에 대해 수정될 수 있음) 이루어질 것인가?

4.b.5. FDA 가이던스 "[의료기기의 사이버 보안: 품질 시스템 고려사항 및 시판 전 신청서의 내용(Cybersecurity in Medical Devices: Quality System Considerations and Content of Premarket Submissions)](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/cybersecurity-medical-devices-quality-system-considerations-and-content-premarket-submissions)"의 섹션 VI.B 및 부록 1.H에 제공된 문서 및 프로세스와 일치하여 사용되는 사이버 보안 위험 관리 및 검증 프로세스[^113]는 무엇인가?

**c. 사용자에 대한 의사소통 및 투명성**

4.c.1. PCCP가 공개 요약 문서 및/또는 라벨링에 어떻게 설명될 것인가?

4.c.2. 업데이트된 라벨링(예: 릴리스 노트)을 포함하되 이에 국한되지 않고 업데이트가 사용자에게 어떻게 전달될 것인가?

4.c.3. 기기에 대한 수정사항(예: 성능)에 대한 어떤 정보가 사용자에게 전달될 것인가?

4.c.4. 기기 출력을 검토할 때 버전 정보가 사용자에게 어떻게 제공될 것인가?

4.c.5. 사용자가 업데이트를 구현하기 전에 라벨링을 검토하거나 업데이트를 선택 해제할 수 있는 옵션이 제공될 것인가?

4.c.6. 라벨링을 포함하되 이에 국한되지 않고 개별적 또는 의도하지 않은 편향을 초래할 가능성이 있는 알려진 편향 또는 기타 성능 문제가 어떻게 공개될 것인가?

4.c.7. 라벨링을 포함하되 이에 국한되지 않고 알려진 문제 또는 편향의 원인과 관련된 성능의 변화가 사용자에게 어떻게 전달될 것인가?

4.c.8. 검증을 위한 집단 및 방법에 대한 어떤 정보가 제공될 것인가?

4.c.9. 이전 기기 사용의 환자 데이터가 이용 가능하고 업데이트된 AI 모델에서 재실행될 수 있는 경우, 이 활동이 이용 가능한 데이터에 대해 수행될 것이며 해당 업데이트된 결과가 환자 및 사용자에게 이용 가능할 것인가? 업데이트 전후의 환자 결과가 임상적으로 의미 있는 차이를 제공하는지 전달할 계획이 있는가?

**d. 기기 모니터링 계획**

4.d.1. 다양한 업데이트에 대한 부작용이 어떻게 추적될 것인가?

4.d.2. 실제 기기 성능을 모니터링하기 위한 위험 기반 계획(일반 관리를 넘어서)이 있는가, 없다면 왜 필요하지 않은가? 투명성을 위해, 구현 후 AI-DSF의 성능에 대한 모니터링 계획이 사용자에게 제공될 것인가?

4.d.3. 사용자에게 투명하게, 실제 기기 성능 모니터링에 대한 정보가 제공될 것인가(예: 수정사항 구현 후 기기의 안전 성능에 대해 사용자에게 알리기 위해), 없다면 왜 필요하지 않은가?

4.d.4. 수동 또는 자동으로 배포된 수정사항에 대한 안전성(예: 부작용, 새로운 또는 이전에 알려지지 않은 위험의 식별) 및 효과성(예: 성능, 이전에 알려지지 않은 편향의 식별)의 변화가 어떻게 그리고 어떤 빈도로 모니터링될 것인가?

4.d.5. 환자 하위 집단의 성능 변화가 어떻게 식별될 것인가?

4.d.6. 이전에 알려지지 않은 위험 또는 이전에 인식되지 않은 고위험 환자 하위 집단의 식별에 대한 대응은 무엇이 될 것인가?

4.d.7. 기기의 이전 반복과 비교하여 예상치 못한 성능 결함 또는 기타 위험, 또는 더 높은 수준의 부작용에 대응하는 전략은 무엇인가?

4.d.8. 부작용 기준을 충족하지 않는 기기에 기인하거나 부분적으로 기인하는 진단 오류(즉, 오진)가 어떻게 추적될 것인가?

4.d.9. 해당되는 경우, 기기를 이전 버전으로 재설정하기 위해 업데이트를 롤백하기 위한 기준 및/또는 계획이 있을 것인가?

# Appendix B: Example AI-DSF Scenarios Employing PCCPs

The examples in this appendix illustrate different AI-DSF scenarios where a PCCP could be employed. Due to the complexity of AI-DSFs, all examples are hypothetical and do not reflect any specific authorized device.

Each example begins with a brief description of an authorized device, its intended use, and one summary of a modification from the Description of Modifications in its authorized PCCP (in the examples, denoted as "Brief Overview of Pre-Specified Modification"). Please note that the provided summaries of the devices and modifications in this appendix are not intended to reflect the complete content or detail expected in a Description of Modifications section in a PCCP. Rather, proposed modifications should be described in much greater detail in a PCCP, consistent with the recommendations provided throughout this guidance. The post-authorization modification scenarios are described to illustrate how the PCCP would be implemented. As described in Section V.D. of this guidance, FDA considers a modification to be consistent with the authorized PCCP when the modification has been specified in the Description of Modifications included in the PCCP and has been implemented in accordance with the Modification Protocol. A distinction is drawn between post-authorization modifications that 1) are consistent with the authorized PCCP and can be implemented without a new marketing submission or 2) are not consistent with the authorized PCCP and may require a new marketing submission[^114] before the device could be introduced into interstate commerce.

Due to the complexity of AI-DSFs, it is not practical to describe all relevant considerations for a complete PCCP for the limited examples presented below. Therefore, while these examples highlight important concepts that could inform the development and utility of a PCCP, the PCCP will be specific to the circumstances of a particular AI-DSF, based on factors including a scientifically valid assessment of benefits and risks.

FDA recommends that the PCCP strategy be discussed with the appropriate FDA review division through the [Q-Submission Program](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/requests-feedback-and-meetings-medical-device-submissions-q-submission-program) prior to submitting a marketing submission containing a PCCP. As part of a marketing submission, the manufacturer should provide a PCCP, consisting of a Description of Modifications (Section VI.), a Modification Protocol (Section VII.), and an Impact Assessment (Section VIII.).

## (1) Patient Monitoring Software

**Background:**

The device is an AI-DSF intended for use in high-acuity healthcare environments (e.g., an intensive care unit). The software obtains physiological signals (e.g., electrocardiogram, blood pressure, pulse oximetry) from a primary patient monitor. The physiological signals are processed and analyzed by an AI model to detect patterns that occur at the onset of physiologic instability. When physiologic instability is detected, an audible alarm signal is generated to indicate that prompt clinical action is needed to prevent potential harm to the patient. The AI-enabled medical device was authorized with a PCCP.

**Brief Overview of Pre-Specified Modification:**

The manufacturer would like to re-train the AI model with more data to reduce the false alarm rate while maintaining or increasing sensitivity to the onset of physiologic instability. The baseline sensitivity is y%. The manufacturer would like to demonstrate a significant improvement in the false-alarm rate while the sensitivity remains within a pre-specified non-inferiority margin of z% when compared with the original device, i.e., the version of the device without any modifications.[^115]

**Post-Authorization Modification Scenarios:**

*Modification Scenario 1: Modification related to quantitative measures of device performance, as specified in the PCCP and implemented in accordance with the PCCP*

In accordance with the Modification Protocol, data were collected and used to re-train the AI model. The modified AI model was tested per the methods specified in the Modification Protocol. The results demonstrated that the false alarm rate was significantly reduced while the mean sensitivity estimate was statistically within the proposed non-inferiority margin of the baseline sensitivity y%. Labeling was updated in accordance with the modified AI-DSF performance, and communication was provided to the device users. Because the device modification was specified in the PCCP, and it was implemented in conformance with the PCCP, the device modification would not require a new marketing submission. The manufacturer should document the modification that was specified in the PCCP in accordance with their quality system.

*Modification Scenario 2: Modification beyond quantitative measures of device performance, which was not specified in the PCCP*

In accordance with the Modification Protocol, the manufacturer re-trained their AI model using additional data to improve the sensitivity. Analytical validation demonstrated that the revised AI model has the same false alarm rate and sensitivity as the previous version. However, the manufacturer also noticed that the modified AI model maintained the same sensitivity and can now also predict physiologic instability in advance of its onset, which the previous version of the AI model could not do. The manufacturer would like to update the device's indications for use to reflect this additional performance claim to predict physiologic instability in advance of its onset, which was not previously included in the PCCP. The methods used for analysis, performance, and statistics were not specified in the PCCP for predicting a future state. Because this modification that was not included in the PCCP could significantly affect the safety or effectiveness of the device, a new marketing submission would be required.

## (2) Skin Lesion Software

**Background:**

The device is an AI-DSF that analyzes images of skin lesions by identifying and characterizing its features (e.g., color, quantification of area change over time) to aid in diagnosis. It was validated with a specific camera and is intended to be used by a primary healthcare provider. The AI-enabled medical device was authorized with a PCCP.

**Brief Overview of Pre-Specified Modification:**

The manufacturer would like to extend the AI-DSF for use on additional general-purpose computing platforms, including smartphones and tablets. The general-purpose computing platform must include a two-dimensional camera that meets the minimum specifications defined in the PCCP. The updated device must achieve a minimum performance defined in the Modification Protocol using a specified methodology.

**Post-Authorization Modification Scenarios:**

*Modification Scenario 1: Modification in input, as specified in the PCCP and implemented in accordance with the PCCP*

The manufacturer's analytical validation demonstrated that the AI-DSF can be deployed on two additional smartphones that have image acquisition specifications that meet the minimum specifications provided in the PCCP. The analytical performance using the new image acquisition systems was found to be statistically equivalent to the baseline performance, as specified in the Modification Protocol. Labeling was updated to reflect the new AI-DSF compatibility with the additional smartphones, which may increase access of the AI-DSF in the healthcare community. Communication updates on device compatibility were also provided. Because the device modification was specified in the PCCP, and it was implemented in conformance with the PCCP, the device modification would not require a new marketing submission. The manufacturer should document the modification that was specified in the PCCP in accordance with their quality system.

*Modification Scenario 2: Modification in input, which was not specified in the PCCP*

The manufacturer would like to deploy a modified AI model that uses images captured by a thermographic camera; however, the new camera technology was not specified in the PCCP. Because this modification that was not included in the PCCP could significantly affect the safety or effectiveness of the device, a new marketing submission would be required.

*Modification Scenario 3: Modification related to the device's use and performance, which was not specified in the PCCP*

The manufacturer would like to distribute a new version of the AI-DSF that is patient-facing. The AI-DSF would provide an analysis of the physiological characteristics of skin lesions, as it does currently, and direct patients to follow-up with a dermatologist based on the preliminary analysis of the malignancy of the skin lesion. The modification introduces many new, unconsidered risks that were not yet mitigated in the current PCCP, given that the modified AI-DSF will be patient-facing. Because this modification that was not included in the PCCP could significantly affect the safety or effectiveness of the device, a new marketing submission would be required.

## (3) Ventilator Settings Software

**Background:**

The device is an AI-DSF intended for use in the healthcare or home-use setting. The AI-DSF recommends the ideal ventilation parameters based on input data interpretation, which can then be programmed into the ventilator by a healthcare provider. The manufacturer proposes modifications to the AI-DSF to improve performance within the original indications. The AI-enabled medical device was authorized with a PCCP.

**Brief Overview of Pre-Specified Modification:**

The manufacturer would like to re-train the AI model to optimize site-specific performance for a specific subset of patients with a particular condition, for whom sufficient data were not previously available. Specifically, the manufacturer would like to modify the AI model to improve its ability to optimize ventilator settings for minute volume and tidal volume to reduce the variability to ±x% within the specified range to improve treatment outcomes for that subset of patients at different sites.

**Post-Authorization Modification Scenarios:**

*Modification Scenario 1: Modification related to the device's use and performance in a subset of the patient population, which was specified in the PCCP and implemented in accordance with the PCCP*

The manufacturer re-trained and re-validated the AI model on newly acquired data in a subpopulation of patients with a particular disorder. As evidenced by additional clinical performance data collected and analyzed per the Modification Protocol, the re-training on new data improved the reliability and precision of ventilator setting recommendations, showing improvements and specializations to improve site-specific ventilator operation. The updated recommendations were validated against patient outcomes and adverse events that may occur due to ventilator setting inaccuracies following the methods in the Modification Protocol. The adverse event rates and outcomes acceptance criteria were established in the Modification Protocol, and as such, were used to validate the updated AI model. The AI-DSF was updated to implement the re-trained AI model and the labeling was updated for clarity to inform users how the updated AI model accounts for local experience and prevalence. The implementation of this modification was done only at applicable sites. Because the device modification was specified in the PCCP, and it was implemented in conformance with the PCCP, the device modification would not require a new marketing submission. The manufacturer should document the modification that was specified in the PCCP in accordance with their quality system.

*Modification Scenario 2: Modification related to device's use and performance in a subset of the patient population, which was specified in the PCCP, but was not implemented in conformance with the PCCP*

The manufacturer re-trained and re-validated the AI model on newly acquired data, but was unable to fulfill the protocol because the manufacturer had to implement a reference standard that was different from the one described in the Modification Protocol. Even though the modification was specified in the PCCP, it was not implemented in conformance with the PCCP. Because this modification that was not implemented in conformance with the PCCP could significantly affect the safety or effectiveness of the device, a new marketing submission would be required.

## (4) Image Acquisition Assistance Device

**Background:**

The AI-DSF is integrated into an imaging system and is intended to assist healthcare providers during acquisition of ultrasound images of the shoulder region in adult and pediatric populations by highlighting portions of the image where it detects a potential abnormality in real time. The AI-DSF interfaces with the device acquisition system, analyzes its output using an AI model, provides real-time alerts to the operator if an abnormality is detected, and automatically adjusts parameters in the device acquisition system during image acquisition to optimize the imaging. The device does not provide a diagnosis. The AI-enabled medical device was authorized with a PCCP.

**Brief Overview of Pre-Specified Modification:**

The manufacturer would like to re-train their AI model to further optimize the accuracy of the abnormality detection. The PCCP pre-specifies that both the sensitivity and specificity will be shown to be significantly superior for abnormality identification during the shoulder exam.

**Post-Authorization Modification Scenario:**

*Modification Scenario 1: Modification related to quantitative measures of device performance, as specified in the PCCP and implemented in accordance with the PCCP*

In accordance with the Modification Protocol, imaging data were collected and used to re-train the AI model. The modified AI model was tested according to a specified test protocol in the Modification Protocol. The results demonstrated that the sensitivity and specificity for abnormality identification met statistical superiority pre-specifications. Labeling was updated in accordance with the modified device performance, and communication was provided to the device users. Because the device modification was specified in the PCCP, and because it was implemented in conformance with the PCCP, the device modification would not require a new marketing submission. The manufacturer should document the modification that was specified in the PCCP in accordance with their quality system.

*Modification Scenario 2: Modification related to the device's use and performance, which was not specified in the PCCP*

The manufacturer used new images to re-train the AI model and would like to update their labeling to reflect improved performance in the same shoulder region in a subset of the pediatric patient population identified in the device's indications for use. However, the modification was not specified in the PCCP. Because this modification that was not included in the PCCP could significantly affect the safety or effectiveness of the device, a new marketing submission would be required.

## (5) Feeding Tube Placement Radiograph Analysis Software

**Background:**

The device is an AI-DSF that analyzes chest radiographs from hospitalized patients to evaluate feeding tube placement. The AI-DSF flags images within the radiologist's review queue so that radiographs identified as having a higher likelihood of feeding tube misplacement may be prioritized for reading. The device is designed and validated for specific X-ray machines. The AI-enabled medical device was authorized with a PCCP.

**Brief Overview of Pre-Specified Modifications:**

The manufacturer would like to improve AI model performance by increasing sensitivity from a baseline of x% (for the original device) to z% (with appropriate confidence intervals) to detect misplaced feeding tubes by re-training on new data. Additionally, the manufacturer would like to expand the compatibility of the device to additional X-ray machines.

**Post-Authorization Modification Scenarios:**

*Modification Scenario 1: Modification related to device's use and performance, as specified in the PCCP and implemented in accordance with the PCCP*

The manufacturer re-trained and re-validated the AI model on newly acquired data as described in the Modification Protocol, which significantly improved the AI-DSF sensitivity from x% to z% to detect incorrect feeding tube placements. The analytical performance on new X-ray machines was found to be statistically equivalent to the performance on previously compatible X-ray machines, as specified in the Modification Protocol. Labeling of the device was changed in accordance with the PCCP. Because the device modification was specified in the PCCP, and it was implemented in conformance with the PCCP, the device modification would not require a new marketing submission. The manufacturer should document the modification that was specified in the PCCP in accordance with their quality system.

*Modification Scenario 2: Modification related to device's use and performance, which was not specified in the PCCP*

The manufacturer used the same database of images to re-train the AI model to identify pneumothorax on chest radiographs. The pneumothorax identification function was found to have the same sensitivity and specificity as the feeding tube AI model. The manufacturer would like to employ the new pneumothorax identification function feature alongside the feeding tube placement AI model in radiograph triage. The modification was not specified in the PCCP. Because this modification that was not included in the PCCP could significantly affect the safety or effectiveness of the device, a new marketing submission would be required.

## (6) Optical Imaging System Co-packaged with Imaging Drug

**Background:**

The product is a device-led combination product including an AI-DSF integrated into an imaging system co-packaged with an approved optical imaging drug. The AI-DSF analyzes images in real-time and highlights potential cancerous lesions for further evaluation. The product was authorized with a PCCP.

**Brief Overview of Pre-Specified Modification:**

The manufacturer would like to train the AI-DSF to improve speed of the lesion detection. The PCCP specifies that the speed of lesion detection can be improved provided that the sensitivity and specificity do not fall below a pre-specified level.

**Post-Authorization Modification Scenarios:**

*Modification Scenario 1: Modification related to device performance, as specified in the PCCP and implemented in accordance with the PCCP*

The manufacturer retrained the AI-DSF using imaging data collected and analyzed in accordance with the Modification Protocol. Analytical validation demonstrated that the modified AI-DSF resulted in image processing speed improvements of 20%. The analytical performance of the imaging system with the increased image processing speed was found to be statistically equivalent to the baseline performance of the imaging system, as specified in the Modification Protocol. Because the device modification was specified in the PCCP, and it was implemented in conformance with the PCCP, the device modification would not require a new marketing submission. The manufacturer should document the modification that was specified in the PCCP in accordance with their quality system.

*Modification Scenario 2: Modification related to device's use and performance, which was not specified in the PCCP*

The manufacturer would like to deploy a modified AI model that uses data from a patient population that was not included in the intended use population. The modification was not specified in the PCCP. Because this modification that was not included in the PCCP could significantly affect the safety or effectiveness of the device, a new marketing submission would be required.

*Modification Scenario 3: Modification related to device's use, which was not specified in the PCCP*

The manufacturer would like to distribute a new version of the AI-DSF that is used with a modified dosing regimen of the drug. This modification was not specified in the PCCP. Because this modification that was not included in the PCCP could significantly affect the safety or effectiveness of the device, a new marketing submission would be required.

Also note that, consistent with the scope of this guidance (see Section III.), the recommendations in this guidance do not apply to modifications to the drug or biologic constituent part of device-led combination products.

[^114]: 21 CFR 807.81(a)(3) or 21 CFR 814.39(a). 21 CFR 807.81(a)(3) 또는 21 CFR 814.39(a).

[^115]: The values in this example are shown as variable terms. A completed PCCP should include specific criteria whenever possible. 이 예시의 값은 변수 용어로 표시됩니다. 완성된 PCCP는 가능한 한 구체적인 기준을 포함해야 합니다.

# 부록 B: PCCP를 사용하는 AI-DSF 시나리오 예시

이 부록의 예시들은 PCCP가 활용될 수 있는 다양한 AI-DSF 시나리오를 보여줍니다. AI-DSF의 복잡성으로 인해, 모든 예시는 가상의 것이며 특정 승인된 기기를 반영하지 않습니다.

각 예시는 승인된 기기, 그 의도된 용도, 그리고 승인된 PCCP의 변경사항 설명(Description of Modifications)에서 하나의 변경사항 요약(예시에서 "사전 명시된 변경사항의 간략한 개요"로 표시)으로 시작합니다. 이 부록에 제공된 기기 및 변경사항의 요약은 PCCP의 변경사항 설명 섹션에서 기대되는 완전한 내용이나 세부사항을 반영하도록 의도된 것이 아니라는 점에 유의하십시오. 오히려, 제안된 변경사항은 이 가이던스 전반에 걸쳐 제공된 권고사항과 일치하게 PCCP에서 훨씬 더 상세하게 설명되어야 합니다. 승인 후 변경사항 시나리오는 PCCP가 어떻게 구현될 것인지를 설명하기 위해 기술됩니다. 이 가이던스의 섹션 V.D.에서 설명된 바와 같이, FDA는 변경사항이 PCCP에 포함된 변경사항 설명에 명시되어 있고 변경사항 프로토콜에 따라 구현된 경우 승인된 PCCP와 일치한다고 간주합니다. 승인 후 변경사항은 1) 승인된 PCCP와 일치하여 새로운 마케팅 제출 없이 구현될 수 있는 것과 2) 승인된 PCCP와 일치하지 않아 기기가 주간 상거래에 도입되기 전에 새로운 마케팅 제출[^114]이 필요할 수 있는 것으로 구분됩니다.

AI-DSF의 복잡성으로 인해, 아래에 제시된 제한된 예시들에 대한 완전한 PCCP의 모든 관련 고려사항을 설명하는 것은 실용적이지 않습니다. 따라서 이러한 예시들이 PCCP의 개발과 유용성에 정보를 제공할 수 있는 중요한 개념들을 강조하지만, PCCP는 이익-위험에 대한 과학적으로 타당한 평가를 포함한 요인들을 기반으로 특정 AI-DSF의 상황에 맞게 구체화될 것입니다.

FDA는 PCCP를 포함하는 마케팅 제출을 하기 전에 Q-제출 프로그램을 통해 적절한 FDA 검토 부서와 PCCP 전략을 논의할 것을 권장합니다. 마케팅 제출의 일부로, 제조업체는 변경사항 설명(섹션 VI.), 변경사항 프로토콜(섹션 VII.), 영향 평가(섹션 VIII.)로 구성된 PCCP를 제공해야 합니다.

## (1) 환자 모니터링 소프트웨어

**배경:**

이 기기는 고위험도 의료 환경(예: 중환자실)에서 사용하도록 의도된 AI-DSF입니다. 이 소프트웨어는 주 환자 모니터로부터 생리학적 신호(예: 심전도, 혈압, 맥박 산소측정)를 획득합니다. 생리학적 신호는 생리학적 불안정성의 시작 시 발생하는 패턴을 감지하기 위해 AI 모델에 의해 처리되고 분석됩니다. 생리학적 불안정성이 감지되면, 환자에게 잠재적 위해를 방지하기 위해 신속한 임상 조치가 필요함을 나타내는 가청 알람 신호가 생성됩니다. AI 지원 의료기기는 PCCP와 함께 승인되었습니다.

**사전 명시된 변경사항의 간략한 개요:**

제조업체는 생리학적 불안정성의 시작에 대한 민감도를 유지하거나 증가시키면서 거짓 알람률을 줄이기 위해 더 많은 데이터로 AI 모델을 재훈련하고자 합니다. 기준선 민감도는 y%입니다. 제조업체는 민감도가 원래 기기, 즉 변경사항이 구현되지 않은 기기 버전과 비교하여 z%의 사전 명시된 비열등성 마진 내에 유지되면서 거짓 알람률의 유의미한 개선을 입증하고자 합니다.[^115]

**승인 후 변경사항 시나리오:**

*변경사항 시나리오 1: PCCP에 명시되고 PCCP에 따라 구현된 기기 성능의 정량적 측정과 관련된 변경사항*

변경사항 프로토콜에 따라, 데이터가 수집되고 AI 모델 재훈련에 사용되었습니다. 수정된 AI 모델은 변경사항 프로토콜에 명시된 방법에 따라 테스트되었습니다. 결과는 평균 민감도 추정치가 기준선 민감도 y%의 제안된 비열등성 마진 내에 통계적으로 있는 동안 거짓 알람률이 유의미하게 감소되었음을 입증했습니다. 라벨링은 수정된 AI-DSF 성능에 따라 업데이트되었고, 기기 사용자에게 의사소통이 제공되었습니다. 기기 변경사항이 PCCP에 명시되었고 PCCP에 따라 구현되었기 때문에, 기기 변경사항은 새로운 마케팅 제출을 필요로 하지 않습니다. 제조업체는 PCCP에 명시된 변경사항을 품질 시스템에 따라 문서화해야 합니다.

*변경사항 시나리오 2: PCCP에 명시되지 않은 기기 성능의 정량적 측정을 넘어서는 변경사항*

변경사항 프로토콜에 따라, 제조업체는 민감도를 개선하기 위해 추가 데이터를 사용하여 AI 모델을 재훈련했습니다. 분석 검증은 수정된 AI 모델이 이전 버전과 동일한 거짓 알람률과 민감도를 가지고 있음을 입증했습니다. 그러나 제조업체는 또한 수정된 AI 모델이 동일한 민감도를 유지하고 이제 이전 버전의 AI 모델이 할 수 없었던 생리학적 불안정성의 시작을 미리 예측할 수 있다는 것을 발견했습니다. 제조업체는 PCCP에 이전에 포함되지 않았던 생리학적 불안정성을 미리 예측하는 이 추가 성능 주장을 반영하기 위해 기기의 사용 적응증을 업데이트하고자 합니다. 분석, 성능 및 통계에 사용된 방법은 미래 상태를 예측하기 위한 PCCP에 명시되지 않았습니다. PCCP에 포함되지 않은 이 변경사항이 기기의 안전성 또는 유효성에 유의미한 영향을 미칠 수 있기 때문에, 새로운 마케팅 제출이 필요합니다.

## (2) 피부 병변 소프트웨어

**배경:**

이 기기는 진단을 보조하기 위해 피부 병변의 특징(예: 색상, 시간 경과에 따른 면적 변화의 정량화)을 식별하고 특성화하여 피부 병변의 이미지를 분석하는 AI-DSF입니다. 특정 카메라로 검증되었으며 일차 의료 제공자가 사용하도록 의도되었습니다. AI 지원 의료기기는 PCCP와 함께 승인되었습니다.

**사전 명시된 변경사항의 간략한 개요:**

제조업체는 스마트폰과 태블릿을 포함한 추가 범용 컴퓨팅 플랫폼에서 사용하도록 AI-DSF를 확장하고자 합니다. 범용 컴퓨팅 플랫폼은 PCCP에 정의된 최소 사양을 충족하는 2차원 카메라를 포함해야 합니다. 업데이트된 기기는 명시된 방법론을 사용하여 변경사항 프로토콜에 정의된 최소 성능을 달성해야 합니다.

**승인 후 변경사항 시나리오:**

*변경사항 시나리오 1: PCCP에 명시되고 PCCP에 따라 구현된 입력의 변경사항*

제조업체의 분석 검증은 AI-DSF가 PCCP에 제공된 최소 사양을 충족하는 이미지 획득 사양을 가진 두 개의 추가 스마트폰에 배포될 수 있음을 입증했습니다. 새로운 이미지 획득 시스템을 사용한 분석 성능은 변경사항 프로토콜에 명시된 대로 기준선 성능과 통계적으로 동등한 것으로 확인되었습니다. 라벨링은 추가 스마트폰과의 새로운 AI-DSF 호환성을 반영하도록 업데이트되었으며, 이는 의료 커뮤니티에서 AI-DSF의 접근성을 증가시킬 수 있습니다. 기기 호환성에 대한 의사소통 업데이트도 제공되었습니다. 기기 변경사항이 PCCP에 명시되었고 PCCP에 따라 구현되었기 때문에, 기기 변경사항은 새로운 마케팅 제출을 필요로 하지 않습니다. 제조업체는 PCCP에 명시된 변경사항을 품질 시스템에 따라 문서화해야 합니다.

*변경사항 시나리오 2: PCCP에 명시되지 않은 입력의 변경사항*

제조업체는 열화상 카메라로 캡처한 이미지를 사용하는 수정된 AI 모델을 배포하고자 합니다. 그러나 새로운 카메라 기술은 PCCP에 명시되지 않았습니다. PCCP에 포함되지 않은 이 변경사항이 기기의 안전성 또는 유효성에 유의미한 영향을 미칠 수 있기 때문에, 새로운 마케팅 제출이 필요합니다.

*변경사항 시나리오 3: PCCP에 명시되지 않은 기기의 사용 및 성능과 관련된 변경사항*

제조업체는 환자 대면형인 AI-DSF의 새 버전을 배포하고자 합니다. AI-DSF는 현재와 같이 피부 병변의 생리학적 특성에 대한 분석을 제공하고, 피부 병변의 악성도에 대한 예비 분석을 기반으로 환자를 피부과 의사에게 후속 진료를 받도록 안내할 것입니다. 이 변경사항은 수정된 AI-DSF가 환자 대면형이 될 것이라는 점을 고려할 때 현재 PCCP에서 아직 완화되지 않은 많은 새롭고 고려되지 않은 위험을 도입합니다. PCCP에 포함되지 않은 이 변경사항이 기기의 안전성 또는 유효성에 유의미한 영향을 미칠 수 있기 때문에, 새로운 마케팅 제출이 필요합니다.

## (3) 인공호흡기 설정 소프트웨어

**배경:**

이 기기는 의료 환경 또는 가정 환경에서 사용하도록 의도된 AI-DSF입니다. AI-DSF는 입력 데이터 해석을 기반으로 이상적인 환기 매개변수를 권장하며, 이는 의료 제공자가 인공호흡기에 프로그래밍할 수 있습니다. 제조업체는 원래 적응증 내에서 성능을 개선하기 위해 AI-DSF의 변경사항을 제안합니다. AI 지원 의료기기는 PCCP와 함께 승인되었습니다.

**사전 명시된 변경사항의 간략한 개요:**

제조업체는 이전에 충분한 데이터가 없었던 특정 질환을 가진 환자의 특정 하위 집단에 대한 부위별 성능을 최적화하기 위해 AI 모델을 재훈련하고자 합니다. 구체적으로, 제조업체는 다양한 부위에서 해당 환자 하위 집단의 치료 결과를 개선하기 위해 분당 환기량 및 일회 호흡량에 대한 인공호흡기 설정을 최적화하고 지정된 범위 내에서 변동성을 ±x%로 줄이는 능력을 향상시키기 위해 AI 모델을 수정하고자 합니다.

**승인 후 변경사항 시나리오:**

*변경사항 시나리오 1: PCCP에 명시되고 PCCP에 따라 구현된 환자 모집단의 하위 집단에서 기기의 사용 및 성능과 관련된 변경사항*

제조업체는 특정 장애를 가진 환자의 하위 모집단에서 새롭게 획득한 데이터로 AI 모델을 재훈련하고 재검증했습니다. 변경사항 프로토콜에 따라 수집되고 분석된 추가 임상 성능 데이터로 입증된 바와 같이, 새로운 데이터에 대한 재훈련은 인공호흡기 설정 권장사항의 신뢰성과 정확성을 향상시켜 부위별 인공호흡기 작동을 개선하기 위한 개선 및 전문화를 보여주었습니다. 업데이트된 권장사항은 변경사항 프로토콜의 방법을 따라 인공호흡기 설정 부정확성으로 인해 발생할 수 있는 환자 결과 및 부작용에 대해 검증되었습니다. 부작용률 및 결과 수용 기준은 변경사항 프로토콜에 설정되었으며, 따라서 업데이트된 AI 모델을 검증하는 데 사용되었습니다. AI-DSF는 재훈련된 AI 모델을 구현하도록 업데이트되었고, 라벨링은 업데이트된 AI 모델이 지역 경험 및 유병률을 어떻게 고려하는지 사용자에게 알리기 위해 명확성을 위해 업데이트되었습니다. 이 변경사항의 구현은 해당 부위에서만 수행되었습니다. 기기 변경사항이 PCCP에 명시되었고 PCCP에 따라 구현되었기 때문에, 기기 변경사항은 새로운 마케팅 제출을 필요로 하지 않습니다. 제조업체는 PCCP에 명시된 변경사항을 품질 시스템에 따라 문서화해야 합니다.

*변경사항 시나리오 2: PCCP에 명시되었으나 PCCP에 따라 구현되지 않은 환자 모집단의 하위 집단에서 기기의 사용 및 성능과 관련된 변경사항*

제조업체는 새롭게 획득한 데이터로 AI 모델을 재훈련하고 재검증했지만, 변경사항 프로토콜에 설명된 것과 다른 참조 표준을 구현해야 했기 때문에 프로토콜을 완료할 수 없었습니다. 변경사항이 PCCP에 명시되었지만 PCCP에 따라 구현되지 않았습니다. PCCP에 따라 구현되지 않은 이 변경사항이 기기의 안전성 또는 유효성에 유의미한 영향을 미칠 수 있기 때문에, 새로운 마케팅 제출이 필요합니다.

## (4) 이미지 획득 보조 기기

**배경:**

AI-DSF는 영상 시스템에 통합되어 있으며, 의료 제공자가 성인 및 소아 환자의 어깨 부위 초음파 이미지를 획득하는 동안 실시간으로 잠재적 이상을 감지하는 이미지 부분을 강조 표시하여 지원하도록 의도되었습니다. AI-DSF는 기기 획득 시스템과 인터페이스하고, AI 모델을 사용하여 출력을 분석하며, 이상이 감지되면 운영자에게 실시간 경보를 제공하고, 이미지 획득 중 기기 획득 시스템의 매개변수를 자동으로 조정하여 영상을 최적화합니다. 이 기기는 진단을 제공하지 않습니다. AI 지원 의료기기는 PCCP와 함께 승인되었습니다.

**사전 명시된 변경사항의 간략한 개요:**

제조업체는 이상 감지의 정확도를 더욱 최적화하기 위해 AI 모델을 재훈련하고자 합니다. PCCP는 어깨 검사 중 이상 식별을 위해 민감도와 특이도 모두가 유의미하게 우수함이 입증될 것이라고 미리 명시합니다.

**승인 후 변경사항 시나리오:**

*변경사항 시나리오 1: PCCP에 명시되고 PCCP에 따라 구현된 기기 성능의 정량적 측정과 관련된 변경사항*

변경사항 프로토콜에 따라, 영상 데이터가 수집되고 AI 모델 재훈련에 사용되었습니다. 수정된 AI 모델은 변경사항 프로토콜의 명시된 테스트 프로토콜에 따라 테스트되었습니다. 결과는 이상 식별을 위한 민감도와 특이도가 통계적 우월성 사전 명세를 충족했음을 입증했습니다. 라벨링은 수정된 기기 성능에 따라 업데이트되었고, 기기 사용자에게 의사소통이 제공되었습니다. 기기 변경사항이 PCCP에 명시되었고 PCCP에 따라 구현되었기 때문에, 기기 변경사항은 새로운 마케팅 제출을 필요로 하지 않습니다. 제조업체는 PCCP에 명시된 변경사항을 품질 시스템에 따라 문서화해야 합니다.

*변경사항 시나리오 2: PCCP에 명시되지 않은 기기의 사용 및 성능과 관련된 변경사항*

제조업체는 새로운 이미지를 사용하여 AI 모델을 재훈련했고, 기기의 사용 적응증에서 식별된 소아 환자 모집단의 하위 집단에서 동일한 어깨 부위의 개선된 성능을 반영하도록 라벨링을 업데이트하고자 합니다. 그러나 변경사항은 PCCP에 명시되지 않았습니다. PCCP에 포함되지 않은 이 변경사항이 기기의 안전성 또는 유효성에 유의미한 영향을 미칠 수 있기 때문에, 새로운 마케팅 제출이 필요합니다.

## (5) 급식 튜브 위치 방사선 사진 분석 소프트웨어

**배경:**

이 기기는 급식 튜브 위치를 평가하기 위해 입원 환자의 흉부 방사선 사진을 분석하는 AI-DSF입니다. AI-DSF는 방사선과 의사의 검토 대기열 내에서 이미지를 표시하여 급식 튜브 잘못된 위치 가능성이 더 높은 것으로 식별된 방사선 사진이 읽기를 위해 우선순위가 지정될 수 있도록 합니다. 이 기기는 특정 X선 기계용으로 설계되고 검증되었습니다. AI 지원 의료기기는 PCCP와 함께 승인되었습니다.

**사전 명시된 변경사항의 간략한 개요:**

제조업체는 새로운 데이터에 대한 재훈련을 통해 잘못 배치된 급식 튜브를 감지하기 위한 민감도를 (원래 기기의) 기준선 x%에서 z%로 (적절한 신뢰 구간과 함께) 증가시켜 AI 모델 성능을 개선하고자 합니다. 또한, 제조업체는 추가 X선 기계로 기기의 호환성을 확장하고자 합니다.

**승인 후 변경사항 시나리오:**

*변경사항 시나리오 1: PCCP에 명시되고 PCCP에 따라 구현된 기기의 사용 및 성능과 관련된 변경사항*

제조업체는 변경사항 프로토콜에 설명된 대로 새롭게 획득한 데이터로 AI 모델을 재훈련하고 재검증했으며, 이는 잘못된 급식 튜브 배치를 감지하기 위한 AI-DSF 민감도를 x%에서 z%로 유의미하게 향상시켰습니다. 새로운 X선 기계에서의 분석 성능은 변경사항 프로토콜에 명시된 대로 이전에 호환되는 X선 기계에서의 성능과 통계적으로 동등한 것으로 확인되었습니다. 기기의 라벨링은 PCCP에 따라 변경되었습니다. 기기 변경사항이 PCCP에 명시되었고 PCCP에 따라 구현되었기 때문에, 기기 변경사항은 새로운 마케팅 제출을 필요로 하지 않습니다. 제조업체는 PCCP에 명시된 변경사항을 품질 시스템에 따라 문서화해야 합니다.

*변경사항 시나리오 2: PCCP에 명시되지 않은 기기의 사용 및 성능과 관련된 변경사항*

제조업체는 동일한 이미지 데이터베이스를 사용하여 흉부 방사선 사진에서 기흉을 식별하도록 AI 모델을 재훈련했습니다. 기흉 식별 기능은 급식 튜브 AI 모델과 동일한 민감도와 특이도를 가진 것으로 확인되었습니다. 제조업체는 방사선 사진 분류에서 급식 튜브 배치 AI 모델과 함께 새로운 기흉 식별 기능을 사용하고자 합니다. 변경사항은 PCCP에 명시되지 않았습니다. PCCP에 포함되지 않은 이 변경사항이 기기의 안전성 또는 유효성에 유의미한 영향을 미칠 수 있기 때문에, 새로운 마케팅 제출이 필요합니다.

## (6) 영상 약물과 함께 포장된 광학 영상 시스템

**배경:**

이 제품은 승인된 광학 영상 약물과 함께 포장된 영상 시스템에 통합된 AI-DSF를 포함하는 기기 주도 복합 제품입니다. AI-DSF는 실시간으로 이미지를 분석하고 추가 평가를 위한 잠재적 암성 병변을 강조 표시합니다. 이 제품은 PCCP와 함께 승인되었습니다.

**사전 명시된 변경사항의 간략한 개요:**

제조업체는 병변 감지 속도를 개선하기 위해 AI-DSF를 훈련하고자 합니다. PCCP는 민감도와 특이도가 사전 명시된 수준 아래로 떨어지지 않는 한 병변 감지 속도가 개선될 수 있다고 명시합니다.

**승인 후 변경사항 시나리오:**

*변경사항 시나리오 1: PCCP에 명시되고 PCCP에 따라 구현된 기기 성능과 관련된 변경사항*

제조업체는 변경사항 프로토콜에 따라 수집되고 분석된 영상 데이터를 사용하여 AI-DSF를 재훈련했습니다. 분석 검증은 수정된 AI-DSF가 이미지 처리 속도에서 20%의 개선을 가져왔음을 입증했습니다. 증가된 이미지 처리 속도를 가진 영상 시스템의 분석 성능은 변경사항 프로토콜에 명시된 대로 영상 시스템의 기준선 성능과 통계적으로 동등한 것으로 확인되었습니다. 기기 변경사항이 PCCP에 명시되었고 PCCP에 따라 구현되었기 때문에, 기기 변경사항은 새로운 마케팅 제출을 필요로 하지 않습니다. 제조업체는 PCCP에 명시된 변경사항을 품질 시스템에 따라 문서화해야 합니다.

*변경사항 시나리오 2: PCCP에 명시되지 않은 기기의 사용 및 성능과 관련된 변경사항*

제조업체는 의도된 사용 모집단에 포함되지 않은 환자 모집단의 데이터를 사용하는 수정된 AI 모델을 배포하고자 합니다. 변경사항은 PCCP에 명시되지 않았습니다. PCCP에 포함되지 않은 이 변경사항이 기기의 안전성 또는 유효성에 유의미한 영향을 미칠 수 있기 때문에, 새로운 마케팅 제출이 필요합니다.

*변경사항 시나리오 3: PCCP에 명시되지 않은 기기의 사용과 관련된 변경사항*

제조업체는 약물의 수정된 투여 요법과 함께 사용되는 AI-DSF의 새 버전을 배포하고자 합니다. 이 변경사항은 PCCP에 명시되지 않았습니다. PCCP에 포함되지 않은 이 변경사항이 기기의 안전성 또는 유효성에 유의미한 영향을 미칠 수 있기 때문에, 새로운 마케팅 제출이 필요합니다.

또한 이 가이던스의 범위(섹션 III. 참조)와 일치하게, 이 가이던스의 권고사항은 기기 주도 복합 제품의 약물 또는 생물학적 구성 부분에 대한 변경사항에는 적용되지 않습니다.
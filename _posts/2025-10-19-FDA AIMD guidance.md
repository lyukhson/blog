---
title:  "Artificial Intelligence-Enabled Device Software Functions: Lifecycle Management and Marketing Submission Recommendations: Draft Guidance (번역 포함)"
last_modified_at: 
header:
  teaser: "/assets/images/500x300.png"
categories: 
  - Regulatory
tags:
  - TBD, TBD
toc: true
toc_sticky: true
toc_label: "Table of Contents"
---

DRAFT GUIDANCE: This draft guidance document is being distributed for comment purposes only. Document issued on January 7, 2025.

This draft guidance, when finalized, will represent the current thinking of the Food and Drug Administration (FDA or Agency) on this topic. It does not establish any rights for any person and is not binding on FDA or the public. You can use an alternative approach if it satisfies the requirements of the applicable statutes and regulations. To discuss an alternative approach, contact the FDA staff or Office responsible for this guidance as listed on the title page.

초안 지침서: 본 초안 지침 문서는 의견 수렴을 목적으로 배포되는 것입니다. 2025년 1월 7일 발행.
본 초안 지침서는 최종 확정될 경우, 이 주제에 대한 식품의약국(FDA 또는 본 기관)의 현재 입장을 나타내게 됩니다. 본 문서는 어떠한 개인에게도 권리를 부여하지 않으며, FDA나 대중에게 구속력을 갖지 않습니다. 해당 법령 및 규정의 요건을 충족하는 경우, 대안적인 접근 방식을 사용할 수 있습니다. 대안적인 접근 방식에 대해 논의하려면, 표지에 명시된 본 지침서 담당 FDA 직원 또는 부서에 연락하시기 바랍니다.

# I. Introduction
FDA has long promoted a total product life cycle (TPLC) approach to the oversight of medical devices, including artificial intelligence (AI)-enabled devices, and has committed to developing guidances and resources for such an approach. Some recent efforts include developing guiding principles for good machine learning practice (GMLP) and transparency for machine learning-enabled devices to help promote safe, effective, and high-quality machine learning models; and a public workshop on fostering a patient-centered approach to AI-enabled devices, including discussions of device transparency for users. This guidance intends to continue these efforts by providing lifecycle management and marketing submission recommendations consistent with a TPLC approach for AI-enabled devices.

This guidance provides recommendations on the contents of marketing submissions for devices that include AI-enabled device software functions, including documentation and information that will support FDA’s review. To support the development of appropriate documentation for FDA’s assessment of devices, this guidance also provides recommendations for the design and development of AI-enabled devices that manufacturers may consider using throughout the TPLC. The recommendations reflect a comprehensive approach to lifecycle management of AI-enabled devices throughout the TPLC. Furthermore, the guidance includes FDA’s current thinking on strategies to address transparency and bias throughout the TPLC of AI-enabled devices, including collecting evidence to evaluate whether a device benefits all relevant demographic groups (e.g., race, ethnicity, sex, and age) similarly, to help ensure that these devices remain safe and effective for their intended use.

The emergence of consensus standards related to software has helped to improve the consistency and quality of software development and documentation, particularly with respect to activities such as risk assessment and management. When possible, FDA harmonized the terminology and recommendations in this guidance with software-related consensus standards. The Agency encourages the consideration of such FDA-recognized consensus standards when developing AI-enabled devices and preparing premarket documentation. For the current edition of the FDA-recognized consensus standards referenced in this document, see the FDA Recognized Consensus Standards Database. If submitting a Declaration of Conformity to a recognized standard, we recommend including the appropriate supporting documentation. For more information regarding use of consensus standards in regulatory submissions, refer to the FDA guidance titled “Appropriate Use of Voluntary Consensus Standards in Premarket Submissions for Medical Devices” and “Standards Development and the Use of Standards in Regulatory Submissions Reviewed in the Center for Biologics Evaluation and Research.”

In general, FDA’s guidance documents do not establish legally enforceable responsibilities. Instead, guidances describe the Agency’s current thinking on a topic and should be viewed only as recommendations, unless specific regulatory or statutory requirements are cited. The use of the word *should* in Agency guidances means that something is suggested or recommended, but not required.

**I. 서론**

FDA는 인공지능(AI) 기반 기기를 포함한 의료기기의 감독에 있어 총체적 제품 수명주기(TPLC) 접근법을 오랫동안 장려해 왔으며, 이러한 접근법을 위한 지침서 및 자료 개발에 전념해 왔습니다. 최근의 노력 사례로는 안전하고 효과적이며 고품질의 기계학습 모델을 촉진하기 위한 우수 기계학습 실무(GMLP) 및 기계학습 기반 기기의 투명성에 대한 지도 원칙 개발, 그리고 사용자를 위한 기기 투명성 논의를 포함한 AI 기반 기기에 대한 환자 중심 접근법 촉진을 위한 공개 워크숍 등이 있습니다. 본 지침서는 AI 기반 기기에 대한 TPLC 접근법과 일관된 수명주기 관리 및 시판 신청 권고사항을 제공함으로써 이러한 노력을 지속하고자 합니다.

본 지침서는 FDA의 검토를 지원할 문서 및 정보를 포함하여, AI 기반 기기 소프트웨어 기능을 포함하는 기기의 시판 신청서 내용에 대한 권고사항을 제공합니다. 기기에 대한 FDA의 평가를 위한 적절한 문서 개발을 지원하기 위해, 본 지침서는 또한 제조업체가 TPLC 전반에 걸쳐 사용할 수 있는 AI 기반 기기의 설계 및 개발에 대한 권고사항을 제공합니다. 이러한 권고사항은 TPLC 전반에 걸친 AI 기반 기기의 수명주기 관리에 대한 포괄적인 접근법을 반영합니다. 또한, 본 지침서는 AI 기반 기기의 TPLC 전반에 걸친 투명성 및 편향성 문제를 다루기 위한 전략에 대한 FDA의 현재 입장을 포함하며, 이는 해당 기기가 의도된 용도에 있어 안전하고 효과적으로 유지되도록 보장하기 위해 모든 관련 인구통계학적 그룹(예: 인종, 민족, 성별, 연령)에 유사하게 혜택을 제공하는지 평가하기 위한 증거 수집을 포함합니다.

소프트웨어와 관련된 합의 표준의 출현은 특히 위험 평가 및 관리와 같은 활동과 관련하여 소프트웨어 개발 및 문서화의 일관성과 품질을 개선하는 데 도움이 되었습니다. 가능한 경우, FDA는 본 지침서의 용어 및 권고사항을 소프트웨어 관련 합의 표준과 조화시켰습니다. 본 기관은 AI 기반 기기를 개발하고 시판 전 문서를 준비할 때 이러한 FDA 인정 합의 표준을 고려할 것을 권장합니다. 본 문서에서 참조된 FDA 인정 합의 표준의 최신판에 대해서는 FDA 인정 합의 표준 데이터베이스를 참조하시기 바랍니다. 인정된 표준에 대한 적합성 선언서를 제출하는 경우, 적절한 뒷받침 문서를 포함할 것을 권장합니다. 규제 제출물에서의 합의 표준 사용에 대한 자세한 정보는 "의료기기 시판 전 신청서에서의 자발적 합의 표준의 적절한 사용" 및 "생물학적 제제 평가 연구 센터에서 검토되는 규제 제출물에서의 표준 개발 및 표준 사용"이라는 제목의 FDA 지침서를 참조하시기 바랍니다.

일반적으로 FDA의 지침 문서는 법적으로 집행 가능한 책임을 설정하지 않습니다. 대신, 지침서는 특정 주제에 대한 본 기관의 현재 입장을 설명하며, 특정 규제 또는 법적 요건이 인용되지 않는 한 권고사항으로만 간주되어야 합니다. 본 기관 지침서에서 should라는 단어의 사용은 무언가가 제안되거나 권장되지만 필수는 아님을 의미합니다.

# II. Scope
For purposes of this guidance, FDA refers to a software function that meets the definition of a device as a “device software function.” A “device software function” is a software function that meets the device definition in section 201(h) of the Federal Food, Drug, and Cosmetic Act (FD&C Act). As discussed in other FDA guidance, the term “function” is a distinct purpose of the product, which could be the intended use or a subset of the intended use of the product.

AI-enabled devices are devices that include one or more AI-enabled device software functions (AI-DSFs). An AI-DSF is a device software function that implements one or more “AI models” (referred to as “models” in this guidance) to achieve its intended purpose. A model is a mathematical construct that generates an inference or prediction based on new input data. In this guidance, when “AI-enabled device” is used, it refers to the whole device, whereas when “AI-DSF” is used, it refers only to the function that uses AI. In this guidance, when “model” is used, it refers only to the mathematical construct.

To continue to support the development of AI-enabled devices, this guidance provides recommendations on the documentation and information that should be included in marketing submissions to support FDA’s review of devices that include AI-DSFs. For purposes of this guidance, the term “marketing submission” refers to premarket notification (510(k)) submission, De Novo classification request, Premarket Approval (PMA) application, Humanitarian Device Exemption (HDE), or Biologics License Application (BLA). Some of the proposed recommendations in this guidance also may apply to Investigational Device Exemption (IDE) submissions. For AI-enabled devices subject to 510(k) requirements, an AI-enabled device can be found substantially equivalent to a non-AI-enabled device with the same intended use provided, among other things, the AI-enabled device does not introduce different questions of safety and effectiveness compared to the non-AI-enabled device and meets other requirements for a determination of substantial equivalence in accordance with section 513(i) of the FD&C Act.

Generally, the recommendations in this guidance also apply to the device constituent part of a combination product when the device constituent part includes an AI-DSF. In developing an AI-DSF, sponsors should consider the impact of the AI-DSF in the context of the combination product as a whole. For a combination product that includes an AI-DSF, we highly encourage early engagement with the FDA lead review division for the combination product. In accordance with the Inter-Center consult process, the FDA lead review division will consult the appropriate subject matter experts. FDA recommends that sponsors refer to other guidances for recommendations on other aspects of investigational considerations and marketing submissions for combination products.

The recommendations proposed within this guidance are based on FDA’s experience with reviewing a variety of AI-enabled devices, as well as current regulatory science research.

While the proposed recommendations are intended to be broadly applicable to AI-enabled devices, many of these recommendations may be specifically relevant to devices that incorporate the subset of AI known as machine learning, particularly deep learning and neural networks. Additional considerations may apply for other forms of AI.

In some cases, this guidance highlights recommendations from other guidances in order to assist manufacturers with applying those recommendations to AI-enabled devices. The inclusion of certain recommendations in this guidance does not negate applicable recommendations in other guidances that may not be included. This guidance should be considered in the context of the FD&C Act, its implementing regulations, and other guidance documents.

This guidance is not intended to provide a complete description of what may be necessary to include in a marketing submission for an AI-enabled device. In particular, this guidance references sections of the FDA guidance titled *“Content of Premarket Submissions for Device Software Functions”* (hereafter referred to as “Premarket Software Guidance”), which includes significant additional considerations for AI-enabled devices, but does not include references to every section of that guidance. Additionally, this guidance does not address all of the data and information to be submitted in support of a specific indication for an AI-enabled device. FDA recommends that sponsors also refer to other guidances, as applicable to a particular device, for recommendations on other aspects of a marketing submission. Examples of relevant guidances for specific technologies include the FDA guidances titled *“Technical Performance Assessment of Quantitative Imaging in Radiological Device Premarket Submissions”* and *“Technical Considerations for Medical Devices with Physiologic Closed-Loop Control Technology.”* FDA further encourages sponsors to consider other available resources, including consensus standards and publicly available information, when preparing their marketing submissions. As with all devices, FDA intends to take a risk-based approach to determining specific testing and applicable recommendations to support marketing submissions for AI-enabled devices.

Early engagement with FDA can help guide product development and submission preparation. In particular, early engagement could be helpful when new and emerging technology is used in the development or design of the device, or when novel methods are used during the validation of the device. FDA encourages sponsors to consider discussing these plans with FDA via the Q-Submission Program.

**II. 적용 범위**

본 지침서의 목적상, FDA는 기기의 정의를 충족하는 소프트웨어 기능을 "기기 소프트웨어 기능"이라고 지칭합니다. "기기 소프트웨어 기능"은 연방 식품, 의약품 및 화장품법(FD&C Act) 제201조(h)항의 기기 정의를 충족하는 소프트웨어 기능입니다. 다른 FDA 지침서에서 논의된 바와 같이, "기능"이라는 용어는 제품의 명확한 목적을 의미하며, 이는 제품의 의도된 용도 또는 의도된 용도의 하위 집합이 될 수 있습니다.

AI 기반 기기는 하나 이상의 AI 기반 기기 소프트웨어 기능(AI-DSF)을 포함하는 기기입니다. AI-DSF는 의도된 목적을 달성하기 위해 하나 이상의 "AI 모델"(본 지침서에서는 "모델"이라고 지칭)을 구현하는 기기 소프트웨어 기능입니다. 모델은 새로운 입력 데이터를 기반으로 추론 또는 예측을 생성하는 수학적 구조입니다. 본 지침서에서 "AI 기반 기기"가 사용될 때는 전체 기기를 지칭하는 반면, "AI-DSF"가 사용될 때는 AI를 사용하는 기능만을 지칭합니다. 본 지침서에서 "모델"이 사용될 때는 수학적 구조만을 지칭합니다.

AI 기반 기기의 개발을 지속적으로 지원하기 위해, 본 지침서는 AI-DSF를 포함하는 기기에 대한 FDA의 검토를 뒷받침하기 위해 시판 신청서에 포함되어야 하는 문서 및 정보에 대한 권고사항을 제공합니다. 본 지침서의 목적상, "시판 신청서"라는 용어는 시판 전 신고(510(k)) 제출, De Novo 분류 요청, 시판 전 승인(PMA) 신청, 인도주의적 기기 면제(HDE) 또는 생물학적 제제 허가 신청(BLA)을 의미합니다. 본 지침서의 일부 권고사항은 임상시험용 기기 면제(IDE) 제출에도 적용될 수 있습니다. 510(k) 요건의 적용을 받는 AI 기반 기기의 경우, AI 기반 기기가 동일한 의도된 용도를 가진 비AI 기반 기기와 실질적으로 동등하다고 판단될 수 있는데, 이는 특히 AI 기반 기기가 비AI 기반 기기와 비교하여 안전성 및 유효성에 대한 다른 의문을 제기하지 않으며 FD&C Act 제513조(i)항에 따른 실질적 동등성 판정을 위한 기타 요건을 충족하는 경우입니다.

일반적으로 본 지침서의 권고사항은 기기 구성 부품이 AI-DSF를 포함하는 경우 복합제품의 기기 구성 부품에도 적용됩니다. AI-DSF를 개발할 때, 스폰서는 복합제품 전체의 맥락에서 AI-DSF의 영향을 고려해야 합니다. AI-DSF를 포함하는 복합제품의 경우, 복합제품에 대한 FDA 주관 심사 부서와의 조기 협의를 강력히 권장합니다. 부서 간 자문 절차에 따라, FDA 주관 심사 부서는 적절한 전문가들과 협의할 것입니다. FDA는 스폰서가 복합제품의 임상시험 고려사항 및 시판 신청의 다른 측면에 대한 권고사항을 위해 다른 지침서를 참조할 것을 권장합니다.

본 지침서 내에서 제안된 권고사항은 다양한 AI 기반 기기를 검토한 FDA의 경험과 현재의 규제 과학 연구를 기반으로 합니다.

제안된 권고사항은 AI 기반 기기에 광범위하게 적용되도록 의도되었지만, 이러한 권고사항 중 다수는 기계학습으로 알려진 AI의 하위 집합, 특히 딥러닝 및 신경망을 통합한 기기에 특별히 관련될 수 있습니다. 다른 형태의 AI에는 추가적인 고려사항이 적용될 수 있습니다.

경우에 따라, 본 지침서는 제조업체가 AI 기반 기기에 해당 권고사항을 적용하는 데 도움을 주기 위해 다른 지침서의 권고사항을 강조합니다. 본 지침서에 특정 권고사항이 포함되었다고 해서 포함되지 않았을 수 있는 다른 지침서의 적용 가능한 권고사항이 무효화되는 것은 아닙니다. 본 지침서는 FD&C Act, 그 시행 규정 및 기타 지침 문서의 맥락에서 고려되어야 합니다.

본 지침서는 AI 기반 기기의 시판 신청서에 포함되어야 할 사항에 대한 완전한 설명을 제공하고자 하는 것이 아닙니다. 특히, 본 지침서는 *"기기 소프트웨어 기능의 시판 전 신청 내용"*(이하 "시판 전 소프트웨어 지침서"라고 지칭)이라는 제목의 FDA 지침서의 섹션들을 참조하는데, 이는 AI 기반 기기에 대한 중요한 추가 고려사항을 포함하지만 해당 지침서의 모든 섹션에 대한 참조를 포함하지는 않습니다. 또한, 본 지침서는 AI 기반 기기의 특정 적응증을 뒷받침하기 위해 제출해야 하는 모든 데이터 및 정보를 다루지 않습니다. FDA는 스폰서가 시판 신청의 다른 측면에 대한 권고사항을 위해 특정 기기에 적용 가능한 다른 지침서도 참조할 것을 권장합니다. 특정 기술에 대한 관련 지침서의 예로는 *"방사선 기기 시판 전 신청서에서의 정량적 영상의 기술적 성능 평가"* 및 *"생리학적 폐쇄 루프 제어 기술을 가진 의료기기에 대한 기술적 고려사항"*이라는 제목의 FDA 지침서가 있습니다. FDA는 스폰서가 시판 신청서를 준비할 때 합의 표준 및 공개 정보를 포함한 기타 이용 가능한 자료를 고려할 것을 추가로 권장합니다. 모든 기기와 마찬가지로, FDA는 AI 기반 기기의 시판 신청을 뒷받침하기 위한 특정 시험 및 적용 가능한 권고사항을 결정함에 있어 위험 기반 접근법을 취할 것입니다.

FDA와의 조기 협의는 제품 개발 및 신청 준비를 안내하는 데 도움이 될 수 있습니다. 특히, 신기술 및 신흥 기술이 기기의 개발 또는 설계에 사용되거나, 기기의 검증 중에 새로운 방법이 사용되는 경우 조기 협의가 도움이 될 수 있습니다. FDA는 스폰서가 Q-제출 프로그램을 통해 이러한 계획을 FDA와 논의하는 것을 고려할 것을 권장합니다.

# III. TPLC Approach: General Principles
This guidance acknowledges the importance of a TPLC approach to the management of AI-enabled devices. In addition to recommendations regarding the documentation and information that should be included in marketing submissions, which reflect a comprehensive approach to the management of risk throughout the TPLC, the resources provided in this guidance are also intended to assist with the device development and lifecycle management of AI-enabled devices, which should help support the safety and effectiveness of these devices. This guidance provides both specific recommendations on the information and documentation to support a marketing submission for an AI-enabled device, as well as recommendations for the design, development, deployment, and maintenance of AI-enabled devices, including performance management.

This guidance also includes FDA’s current thinking on strategies to address transparency and bias throughout the TPLC of AI-enabled devices. These interconnected considerations are important throughout the TPLC and should be incorporated from the earliest stage of device design through decommission to help design transparency and the control of bias into the device and ensure its safety and effectiveness. Transparency involves ensuring that important information is both accessible and functionally comprehensible and is connected both to the sharing of information and to the usability of a device. AI bias is a potential tendency to produce incorrect results in a systematic, but sometimes unforeseeable way, which can impact safety and effectiveness of the device within all or a subset of the intended use population (e.g., different healthcare settings, different input devices, sex, age, etc.). A comprehensive approach to transparency and bias is particularly important for AI-enabled devices, which can be hard for users to understand due to the opacity of many models and model reliance on data correlations that may not map directly to biologically plausible mechanisms of action. Recommendations for a design approach to transparency are provided in Appendix B (Transparency Design Considerations). With regard to the control of bias for AI-enabled devices, this can include addressing representativeness in data collection for development, testing, and monitoring throughout the product lifecycle, as well as evaluating performance across subgroups of intended use.

Finally, this guidance includes recommendations that address the performance of AI-enabled devices throughout the TPLC, including in the postmarket setting. For example, AI-enabled devices can be sensitive to differences in input data (also referred to as data drift), such as input data used during development as compared to input data in actual deployments. Further, in addition to data drift, which occurs when systems that produce inputs for AI-enabled devices change over time in ways that may impact the performance of the device but may not be evident to users, AI-enabled devices can also be susceptible to changes in performance due to other factors. Sponsors are also encouraged to consider the use of a predetermined change control plan (PCCP), as discussed in FDA guidance titled *“Marketing Submission Recommendations for a Predetermined Change Control Plan for Artificial Intelligence-Enabled Device Software Functions,”* which describes an approach for manufacturers to prospectively specify and seek premarket authorization for intended modifications to an AI-DSF (e.g., to improve device performance) without needing to submit additional marketing submissions or obtain further FDA authorization before implementing such modification consistent with the PCCP.

**III. TPLC 접근법: 일반 원칙**

본 지침서는 AI 기반 기기의 관리에 있어 TPLC 접근법의 중요성을 인정합니다. TPLC 전반에 걸친 위험 관리에 대한 포괄적인 접근법을 반영하는 시판 신청서에 포함되어야 하는 문서 및 정보에 대한 권고사항 외에도, 본 지침서에서 제공되는 자료는 AI 기반 기기의 기기 개발 및 수명주기 관리를 지원하기 위한 것이며, 이는 이러한 기기의 안전성 및 유효성을 뒷받침하는 데 도움이 될 것입니다. 본 지침서는 AI 기반 기기의 시판 신청을 뒷받침하기 위한 정보 및 문서에 대한 구체적인 권고사항과 더불어 성능 관리를 포함한 AI 기반 기기의 설계, 개발, 배포 및 유지보수에 대한 권고사항을 제공합니다.

본 지침서는 또한 AI 기반 기기의 TPLC 전반에 걸친 투명성 및 편향성 문제를 다루기 위한 전략에 대한 FDA의 현재 입장을 포함합니다. 이러한 상호 연결된 고려사항은 TPLC 전반에 걸쳐 중요하며, 기기의 투명성을 설계하고 편향성을 통제하여 기기의 안전성 및 유효성을 보장하기 위해 기기 설계의 초기 단계부터 폐기까지 통합되어야 합니다. 투명성은 중요한 정보가 접근 가능하고 기능적으로 이해 가능하도록 보장하는 것을 포함하며, 정보 공유와 기기의 사용성 모두와 연결됩니다. AI 편향성은 체계적이지만 때로는 예측할 수 없는 방식으로 잘못된 결과를 생성하는 잠재적 경향으로, 의도된 사용 인구 전체 또는 일부(예: 다양한 의료 환경, 다양한 입력 기기, 성별, 연령 등) 내에서 기기의 안전성 및 유효성에 영향을 미칠 수 있습니다. 투명성 및 편향성에 대한 포괄적인 접근법은 AI 기반 기기에 특히 중요한데, 이는 많은 모델의 불투명성과 생물학적으로 타당한 작용 메커니즘과 직접적으로 연결되지 않을 수 있는 데이터 상관관계에 대한 모델 의존성으로 인해 사용자가 이해하기 어려울 수 있기 때문입니다. 투명성에 대한 설계 접근법에 대한 권고사항은 부록 B(투명성 설계 고려사항)에 제공됩니다. AI 기반 기기의 편향성 통제와 관련하여, 이는 제품 수명주기 전반에 걸친 개발, 시험 및 모니터링을 위한 데이터 수집의 대표성 처리와 의도된 사용의 하위 그룹 간 성능 평가를 포함할 수 있습니다.

마지막으로, 본 지침서는 시판 후 환경을 포함하여 TPLC 전반에 걸친 AI 기반 기기의 성능을 다루는 권고사항을 포함합니다. 예를 들어, AI 기반 기기는 개발 중에 사용된 입력 데이터와 실제 배포에서의 입력 데이터와 같이 입력 데이터의 차이(데이터 드리프트라고도 함)에 민감할 수 있습니다. 또한, AI 기반 기기의 입력을 생성하는 시스템이 기기의 성능에 영향을 미칠 수 있지만 사용자에게는 명확하지 않을 수 있는 방식으로 시간이 지남에 따라 변화할 때 발생하는 데이터 드리프트 외에도, AI 기반 기기는 다른 요인으로 인한 성능 변화에도 취약할 수 있습니다. 스폰서는 또한 *"인공지능 기반 기기 소프트웨어 기능에 대한 사전 결정 변경 관리 계획의 시판 신청 권고사항"*이라는 제목의 FDA 지침서에서 논의된 바와 같이 사전 결정 변경 관리 계획(PCCP)의 사용을 고려할 것을 권장받습니다. 이는 제조업체가 AI-DSF에 대한 의도된 수정사항(예: 기기 성능 개선)을 사전에 명시하고 시판 전 승인을 받아, PCCP와 일치하는 방식으로 해당 수정사항을 구현하기 전에 추가 시판 신청서를 제출하거나 추가 FDA 승인을 받을 필요 없이 이를 실행할 수 있는 접근법을 설명합니다.

# IV. How to Use this Guidance: Overview of AI-Enabled Device Marketing Submission Content Recommendations
This guidance provides recommendations on the documentation and information that should be included in marketing submissions to support FDA’s review of devices that include AI-DSFs.

There are some differences between the way FDA and the AI community consider the AI-enabled device TPLC and certain terminology. Therefore, this guidance clarifies these differences to facilitate better understanding of the recommendations in this guidance. For example, the AI community often uses the term “validation” to refer to data curation or model tuning that can be combined with the model training phase to optimize the model selection. However, validation is defined in 21 CFR 820.3(z) as “...confirmation by examination and provision of objective evidence that the particular requirements for a specific intended use can be consistently fulfilled.” This guidance uses the definition in 21 CFR 820.3(z), specifically when addressing the evaluation of performance of the model for its intended use. For clarity, using the term “validation” to refer to the training and tuning process should be avoided in the context of medical device marketing submissions. Also, the term “development” is used throughout this guidance to refer to training, tuning, and tuning evaluation (often referred to as “internal testing” in the AI community). In this guidance, “test data” is used to refer to data that may be used for verification and validation activities, also known as the testing process, and is not used to describe part of the development process. The *FDA Digital Health and Artificial Intelligence Glossary – Educational Resource* provides a compilation of commonly used terms in the artificial intelligence and machine learning space and their definitions.

Sections V through XIII of this guidance describe the marketing submission content recommendations for AI-enabled devices. Specifically, in each section, under “Why should it be included in a submission for an AI-enabled device,” an explanation is provided for why certain information should be included in a marketing submission. An explanation of what documentation and information should be included in a marketing submission can be found under “What sponsors should include in a submission.” Finally, recommendations regarding where sponsors should include the information within each section of a marketing submission can be found under “Where sponsors should provide it in a submission.” Information regarding recommendations for lifecycle considerations as well as examples of marketing submission materials are provided in the appendices of this guidance.

The recommendations related to marketing submissions are organized according to how they should appear in the submission (see Appendix A, *Table of Recommended Documentation*), which does not always align directly with the order of activities in the TPLC. While all referenced submission sections are provided to FDA during premarket review, they include information about what has already been done to develop and validate the device, as well as what a sponsor plans to do in the future to ensure a device’s ongoing safety and effectiveness. Some sections of the guidance also describe information relevant to multiple steps in the TPLC. One example of how the sections in this guidance may align with the TPLC is included below:

* **Development** – Risk Assessment, Data Management, and Model Description and Development
* **Validation** – Data Management and Validation
* **Description of the Final Device** – Device Description, Model Description and Development, User Interface and Labeling, Public Submission Summary
* **Postmarket Management** – Device Performance Monitoring and Cybersecurity

This guidance generally describes information that would be generated and documented during software development, verification, and validation. However, the information necessary to support market authorization will vary based on the specifics of each AI-enabled device, and during premarket review FDA may request additional information that is needed to evaluate the submission.

**IV. 본 지침서 사용 방법: AI 기반 기기 시판 신청 내용 권고사항 개요**

본 지침서는 AI-DSF를 포함하는 기기에 대한 FDA의 검토를 뒷받침하기 위해 시판 신청서에 포함되어야 하는 문서 및 정보에 대한 권고사항을 제공합니다.

FDA와 AI 커뮤니티가 AI 기반 기기 TPLC 및 특정 용어를 고려하는 방식에는 몇 가지 차이점이 있습니다. 따라서 본 지침서는 본 지침서의 권고사항에 대한 더 나은 이해를 촉진하기 위해 이러한 차이점을 명확히 합니다. 예를 들어, AI 커뮤니티는 종종 "validation"이라는 용어를 모델 선택을 최적화하기 위해 모델 학습 단계와 결합될 수 있는 데이터 큐레이션 또는 모델 튜닝을 지칭하는 데 사용합니다. 그러나 validation은 21 CFR 820.3(z)에서 "...특정 의도된 용도에 대한 특정 요건이 일관되게 충족될 수 있다는 것을 검사 및 객관적 증거 제공을 통해 확인하는 것"으로 정의됩니다. 본 지침서는 특히 의도된 용도에 대한 모델의 성능 평가를 다룰 때 21 CFR 820.3(z)의 정의를 사용합니다. 명확성을 위해, 의료기기 시판 신청의 맥락에서 학습 및 튜닝 과정을 지칭하기 위해 "validation"이라는 용어를 사용하는 것은 피해야 합니다. 또한, "개발(development)"이라는 용어는 본 지침서 전반에 걸쳐 학습, 튜닝 및 튜닝 평가(AI 커뮤니티에서는 종종 "내부 시험"이라고 지칭됨)를 지칭하는 데 사용됩니다. 본 지침서에서 "시험 데이터(test data)"는 검증 및 밸리데이션 활동, 즉 시험 과정에 사용될 수 있는 데이터를 지칭하는 데 사용되며, 개발 과정의 일부를 설명하는 데는 사용되지 않습니다. FDA 디지털 헬스 및 인공지능 용어집 – 교육 자료는 인공지능 및 기계학습 분야에서 일반적으로 사용되는 용어와 그 정의의 모음을 제공합니다.

본 지침서의 섹션 V부터 XIII까지는 AI 기반 기기의 시판 신청 내용 권고사항을 설명합니다. 구체적으로, 각 섹션에서 "AI 기반 기기의 신청서에 왜 포함되어야 하는가"라는 항목 하에 특정 정보가 시판 신청서에 포함되어야 하는 이유에 대한 설명이 제공됩니다. 시판 신청서에 어떤 문서 및 정보가 포함되어야 하는지에 대한 설명은 "스폰서가 신청서에 포함해야 할 내용"에서 찾을 수 있습니다. 마지막으로, 스폰서가 시판 신청서의 각 섹션 내에서 정보를 어디에 포함해야 하는지에 대한 권고사항은 "스폰서가 신청서에서 제공해야 할 위치"에서 찾을 수 있습니다. 수명주기 고려사항에 대한 권고사항 및 시판 신청 자료의 예시에 관한 정보는 본 지침서의 부록에 제공됩니다.

시판 신청과 관련된 권고사항은 신청서에 나타나야 하는 방식에 따라 구성되어 있으며(부록 A, 권장 문서 표 참조), 이는 항상 TPLC의 활동 순서와 직접적으로 일치하지는 않습니다. 모든 참조된 신청 섹션은 시판 전 검토 중에 FDA에 제공되지만, 기기를 개발하고 검증하기 위해 이미 수행된 작업에 대한 정보와 기기의 지속적인 안전성 및 유효성을 보장하기 위해 스폰서가 향후 수행할 계획인 작업에 대한 정보를 포함합니다. 지침서의 일부 섹션은 또한 TPLC의 여러 단계와 관련된 정보를 설명합니다. 본 지침서의 섹션이 TPLC와 어떻게 일치할 수 있는지에 대한 한 가지 예시는 다음과 같습니다:

* 개발 – 위험 평가, 데이터 관리, 모델 설명 및 개발
* 검증 – 데이터 관리 및 검증
* 최종 기기의 설명 – 기기 설명, 모델 설명 및 개발, 사용자 인터페이스 및 라벨링, 공개 신청 요약
* 시판 후 관리 – 기기 성능 모니터링 및 사이버보안

본 지침서는 일반적으로 소프트웨어 개발, 검증 및 밸리데이션 중에 생성되고 문서화될 정보를 설명합니다. 그러나 시판 승인을 뒷받침하는 데 필요한 정보는 각 AI 기반 기기의 구체적인 사항에 따라 다르며, 시판 전 검토 중에 FDA는 신청서를 평가하는 데 필요한 추가 정보를 요청할 수 있습니다.

## A. Quality System Documentation
When considering the recommendations in Sections V through XIII of this guidance, it may be helpful to consider whether the documentation and information that should be included in a marketing submission, under “What sponsors should include in a submission,” could also exist in the Quality System documentation. One source of documentation that may be used as part of demonstrating substantial equivalence or reasonable assurance of safety and effectiveness in the marketing submission for certain AI-enabled devices is documentation related to the ongoing requirements of the Quality System (QS) Regulation. This guidance explains how some documentation that may be relevant for QS Regulation compliance for medical devices generally can also be provided premarket to demonstrate how a sponsor or manufacturer is addressing risks associated with AI-enabled devices specifically.

For example, the QS Regulation requires that manufacturers establish design controls for certain finished devices (see 21 CFR 820.30). Specifically, as part of design controls, a manufacturer must “establish and maintain procedures for validating the device design,” which “shall ensure that devices conform to defined user needs and intended uses and shall include testing of production units under actual or simulated use conditions” (21 CFR 820.30(g)). In addition, under 21 CFR 820.30(i), a manufacturer must establish and maintain procedures to identify, document, validate or, where appropriate, verify, review, and approve design changes before their implementation (“design changes”) for all devices, including those automated with software.

Similarly, as part of the control of nonconforming product, manufacturers must establish and maintain procedures to “control product that does not conform to specified requirements,” including, under some circumstances, user requirements, and to implement corrective and preventive action, including “complaints” and “other sources of quality data” to identify “existing and potential causes of nonconforming product” (21 CFR 820.90(a) and 820.100(a)(1)). Further, manufacturers have ongoing responsibility to manage the quality system and maintain device quality, including by reviewing the “suitability and effectiveness of the quality system at defined intervals and with sufficient frequency according to established procedures” to ensure the quality objectives are being met.

**A. 품질 시스템 문서**

본 지침서의 섹션 V부터 XIII까지의 권고사항을 고려할 때, "스폰서가 신청서에 포함해야 할 내용"에 따라 시판 신청서에 포함되어야 하는 문서 및 정보가 품질 시스템 문서에도 존재할 수 있는지 고려하는 것이 도움이 될 수 있습니다. 특정 AI 기반 기기의 시판 신청서에서 실질적 동등성 또는 안전성 및 유효성에 대한 합리적 보증을 입증하는 일부로 사용될 수 있는 문서의 한 출처는 품질 시스템(QS) 규정의 지속적인 요건과 관련된 문서입니다. 본 지침서는 일반적으로 의료기기의 QS 규정 준수와 관련될 수 있는 일부 문서가 스폰서 또는 제조업체가 AI 기반 기기와 관련된 위험을 구체적으로 어떻게 다루고 있는지 입증하기 위해 시판 전에도 제공될 수 있는 방법을 설명합니다.

예를 들어, QS 규정은 제조업체가 특정 완제 기기에 대한 설계 관리를 수립하도록 요구합니다(21 CFR 820.30 참조). 구체적으로, 설계 관리의 일부로, 제조업체는 "기기 설계를 검증하기 위한 절차를 수립하고 유지"해야 하며, 이는 "기기가 정의된 사용자 요구사항 및 의도된 용도에 부합하도록 보장해야 하며, 실제 또는 모의 사용 조건 하에서 생산 단위의 시험을 포함해야" 합니다(21 CFR 820.30(g)). 또한, 21 CFR 820.30(i)에 따라, 제조업체는 소프트웨어로 자동화된 기기를 포함한 모든 기기에 대해 설계 변경("설계 변경")을 구현하기 전에 이를 식별, 문서화, 검증 또는 적절한 경우 확인, 검토 및 승인하는 절차를 수립하고 유지해야 합니다.

마찬가지로, 부적합 제품의 관리의 일부로, 제조업체는 경우에 따라 사용자 요구사항을 포함하여 "명시된 요건을 충족하지 않는 제품을 관리"하는 절차를 수립하고 유지해야 하며, "부적합 제품의 기존 및 잠재적 원인"을 식별하기 위해 "불만사항" 및 "기타 품질 데이터 출처"를 포함한 시정 및 예방 조치를 실행해야 합니다(21 CFR 820.90(a) 및 820.100(a)(1)). 또한, 제조업체는 품질 목표가 충족되고 있는지 확인하기 위해 "수립된 절차에 따라 정해진 간격으로 충분한 빈도로 품질 시스템의 적합성 및 효과성을 검토"하는 것을 포함하여 품질 시스템을 관리하고 기기 품질을 유지할 지속적인 책임이 있습니다.

# V. Device Description
*Why it should be included in a submission for an AI-enabled device:*
The following section describes information that sponsors should provide in the *Device Description* section of their marketing submission to help FDA understand the general characteristics of the AI-enabled device. These recommendations supplement device-specific recommendations and those provided in the *Premarket Software Guidance*, where applicable.

The device description supports FDA’s understanding of the intended use, expected operational sequence (e.g., clinical workflow), use environment, features of the model, and overall design of the AI-enabled device. This information is necessary for FDA to evaluate the safety and effectiveness of the device. The device description provides essential context about what the device does, how it works, how users interact with it, and the conditions under which it is intended to be used.

For recommendations related to how to include information in the marketing submission about the technical characteristics of the model and the method by which the model was developed, see Section IX (*Model Description and Development*) of this guidance.

*What sponsors should include in a submission:*
In general, sponsors should include the following types of information as part of a device description for an AI-enabled device:

* A statement that AI is used in the device.
* A description of the device inputs and outputs, including whether the inputs are entered manually or automatically, and a list of compatible input devices and acquisition protocols, as applicable.
* An explanation of how AI is used to achieve the device’s intended use. For devices with multiple functions, this explanation may include how AI-DSFs interact with each other and with non-AI-DSFs.
* A description of the intended users, their characteristics, and the level and type of training they are expected to have and/or receive. Users include those who will interpret the output. When relevant, list the qualifications or clinical roles of users intended to interpret outputs. Users may also include those involved in installation, operation, and maintenance—such as technicians, healthcare providers, patients, caregivers, administrators, and others involved in device deployment and clinical integration.
* A description of the intended use environment(s) (e.g., clinical setting, home setting).
* A description of the intended workflow for use of the device (e.g., decision-making role), including:
  * The degree of automation the device provides compared to the current standard of care;
  * The clinical circumstances that may lead to device use; and
  * How the outputs will be used within the clinical workflow.
* A description of installation and maintenance procedures.
* A description of any calibration and/or configuration procedures required to maintain performance, including when calibration must be performed, how to identify when recalibration is needed, and how to detect calibration errors, as applicable.

Additionally, sponsors should include the following types of information as part of a device description for an AI-enabled device that has elements that can be configured by a user:

* A description of all configurable elements, such as:

  * Visualizations users can toggle (e.g., overlays, quality indicators, heatmaps);
  * Software inputs;
  * Model parameters configurable during use; and/or
  * Alert thresholds.
* A description of how these elements and their settings can be configured, including:

  * Who makes configuration decisions (e.g., clinical, administrative, or patient users) and their qualifications/training requirements;
  * How users know which selections have been made;
  * The level at which configurations are defined (e.g., patient-level, clinical site-level, or hospital network-level); and
  * A description of customizable predefined operating points, their outputs and performance ranges, and how these were selected based on the device’s indications for use.
* A description of the potential impact of configurable elements on user decision-making.

Finally, if a device contains multiple connected applications with separate interfaces, the device description should address all applications in the device. For example, if there is an application for patients, an application for caregivers, and a data portal for healthcare providers, the device description should include details on all functions across the applications and address how they are connected. Sponsors may also wish to consider enhancing the device description with the use of graphics, diagrams, illustrations, screen captured images, or video demonstrations, including

*Where sponsors should provide it in a submission:* The AI-enabled device description information should be included in the **Device Description** section of the marketing submission.

**V. 기기 설명**

*AI 기반 기기의 신청서에 왜 포함되어야 하는가:* 다음 섹션은 FDA가 AI 기반 기기의 일반적인 특성을 이해하는 데 도움이 되도록 스폰서가 시판 신청서의 *기기 설명* 섹션에 제공해야 하는 정보를 설명합니다. 이러한 권고사항은 해당되는 경우 기기별 권고사항 및 *시판 전 소프트웨어 지침서*에 제공된 권고사항을 보완합니다.

기기 설명은 의도된 용도, 예상되는 작동 순서(예: 임상 워크플로), 사용 환경, 모델의 특징 및 AI 기반 기기의 전반적인 설계에 대한 FDA의 이해를 뒷받침합니다. 이 정보는 FDA가 기기의 안전성 및 유효성을 평가하는 데 필요합니다. 기기 설명은 기기가 무엇을 하는지, 어떻게 작동하는지, 사용자가 어떻게 상호작용하는지, 그리고 어떤 조건 하에서 사용되도록 의도되었는지에 대한 필수적인 맥락을 제공합니다.

모델의 기술적 특성 및 모델이 개발된 방법에 대한 정보를 시판 신청서에 포함하는 방법과 관련된 권고사항은 본 지침서의 섹션 IX(*모델 설명 및 개발*)를 참조하십시오.

*스폰서가 신청서에 포함해야 할 내용:* 일반적으로, 스폰서는 AI 기반 기기의 기기 설명의 일부로 다음 유형의 정보를 포함해야 합니다:
* 기기에 AI가 사용된다는 진술.
* 입력이 수동으로 입력되는지 자동으로 입력되는지 여부를 포함한 기기 입력 및 출력에 대한 설명, 그리고 해당되는 경우 호환 가능한 입력 기기 및 획득 프로토콜 목록.
* 기기의 의도된 용도를 달성하기 위해 AI가 어떻게 사용되는지에 대한 설명. 여러 기능을 가진 기기의 경우, 이 설명에는 AI-DSF가 서로 및 비AI-DSF와 어떻게 상호작용하는지가 포함될 수 있습니다.
* 의도된 사용자, 그들의 특성, 그리고 그들이 받을 것으로 예상되거나 받아야 하는 교육의 수준 및 유형에 대한 설명. 사용자는 출력을 해석할 사람들을 포함합니다. 관련이 있는 경우, 출력을 해석하도록 의도된 사용자의 자격 또는 임상 역할을 나열하십시오. 사용자는 또한 기술자, 의료 제공자, 환자, 간병인, 관리자 및 기기 배포 및 임상 통합에 관여하는 기타 사람들과 같이 설치, 작동 및 유지보수에 관여하는 사람들을 포함할 수 있습니다.
* 의도된 사용 환경에 대한 설명(예: 임상 환경, 가정 환경).
* 다음을 포함한 기기 사용을 위한 의도된 워크플로에 대한 설명(예: 의사결정 역할):
  * 현재 표준 치료와 비교하여 기기가 제공하는 자동화 정도;
  * 기기 사용으로 이어질 수 있는 임상 상황; 그리고
  * 임상 워크플로 내에서 출력이 어떻게 사용될 것인지.
* 설치 및 유지보수 절차에 대한 설명.
* 해당되는 경우, 교정을 수행해야 하는 시기, 재교정이 필요한 시기를 식별하는 방법, 교정 오류를 감지하는 방법을 포함하여 성능을 유지하는 데 필요한 모든 교정 및/또는 구성 절차에 대한 설명.

또한, 스폰서는 사용자가 구성할 수 있는 요소가 있는 AI 기반 기기의 기기 설명의 일부로 다음 유형의 정보를 포함해야 합니다:
* 다음과 같은 모든 구성 가능한 요소에 대한 설명:
  * 사용자가 전환할 수 있는 시각화(예: 오버레이, 품질 지표, 히트맵);
  * 소프트웨어 입력;
  * 사용 중에 구성할 수 있는 모델 매개변수; 그리고/또는
  * 경고 임계값.
* 다음을 포함하여 이러한 요소와 설정이 어떻게 구성될 수 있는지에 대한 설명:
  * 구성 결정을 내리는 사람(예: 임상, 행정 또는 환자 사용자) 및 그들의 자격/교육 요건;
  * 사용자가 어떤 선택이 이루어졌는지 알 수 있는 방법;
  * 구성이 정의되는 수준(예: 환자 수준, 임상 현장 수준 또는 병원 네트워크 수준); 그리고
  * 사용자 정의 가능한 사전 정의된 작동 지점, 그들의 출력 및 성능 범위, 그리고 이들이 기기의 사용 적응증에 기반하여 어떻게 선택되었는지에 대한 설명.
* 구성 가능한 요소가 사용자 의사결정에 미치는 잠재적 영향에 대한 설명.

마지막으로, 기기가 별도의 인터페이스를 가진 여러 연결된 애플리케이션을 포함하는 경우, 기기 설명은 기기의 모든 애플리케이션을 다루어야 합니다. 예를 들어, 환자용 애플리케이션, 간병인용 애플리케이션, 의료 제공자용 데이터 포털이 있는 경우, 기기 설명에는 애플리케이션 전반의 모든 기능에 대한 세부사항이 포함되어야 하며, 그들이 어떻게 연결되어 있는지를 다루어야 합니다. 스폰서는 또한 그래픽, 다이어그램, 일러스트레이션, 화면 캡처 이미지 또는 비디오 시연의 사용을 포함하여 기기 설명을 강화하는 것을 고려할 수 있습니다.

*스폰서가 신청서에서 제공해야 할 위치:* AI 기반 기기 설명 정보는 시판 신청서의 **기기 설명** 섹션에 포함되어야 합니다.

# VI. User Interface and Labeling
The user interface includes all points of interaction between the user and the device, encompassing all elements with which the user interacts (e.g., parts that users see, hear, or touch). It also includes all sources of information transmitted by the device—such as packaging, labeling, training materials, and all physical controls and display elements (including alarms and the logic of operation of each device component and the user interface system as a whole), as applicable. A user interface may be used throughout many phases of installation and use, including setup (e.g., unpacking, calibration), operation, and maintenance (e.g., cleaning, battery replacement, repairs). Designing the user interface to provide critical information throughout the course of use helps ensure that the device conforms to defined user needs and supports its safety and effectiveness. Integrating information throughout the interface ensures users receive the right information at the right time and location to enable safe, effective use consistent with the intended purpose. For software or mobile applications, manufacturers may use interface elements—such as on-screen messages or alerts sent to other devices—in addition to traditional labeling, to communicate device risks at the appropriate time.

It is important to provide a holistic understanding of the user interface in a marketing submission to help FDA understand how the device operates. If a sponsor references the user interface design in the risk analysis or other sections of the submission as a control measure, inclusion of the user interface description can support explanations of those risk controls. However, the actual analysis of the effectiveness of the risk control should be located separately from the user interface description. Additional details on this topic are described in Section VII (*Risk Assessment*) and Appendix D (*Usability Evaluation Considerations*).

With regard to labeling, a device user interface includes, but is not limited to, labeling. Labeling within the user interface is subject to specific regulatory requirements. For example, depending on whether the device is for prescription use or not, manufacturers must provide labeling containing adequate directions for use to ensure that a layperson or, for prescription devices, a licensed practitioner “can use the device safely and for the purposes for which it is intended.” One way to meet these requirements for AI-enabled devices is to provide clear information in the labeling about the model, its performance characteristics, and how the model is integrated into the device. Users may need details such as the nature of the data used for model training, which can be critical to understanding how the device should perform and what factors may influence performance.

The following sections provide detailed recommendations on the user interface (Section VI.A) and labeling (Section VI.B) that should be included in a marketing submission to support FDA’s understanding of what is communicated to users and how users interact with the device.

Appendix B (Transparency Design Considerations) offers a recommended approach to transparency, including examples of types of information, communication modes, and styles that may be useful when designing the user interface (including labeling) of an AI-enabled medical device. It may also be beneficial to include a model card in the device labeling to clearly communicate essential information about the AI-enabled device (see Appendix E, Example Model Card).

Note that inclusion of a unique device identifier (UDI) in the labeling is required for all devices, including AI-enabled devices, that are subject to UDI regulations. A new UDI is required for each new version or model and for new device packages. See FDA’s Unique Device Identification System webpage for additional information.

**VI. 사용자 인터페이스 및 라벨링**

사용자 인터페이스는 사용자와 기기 간의 모든 상호작용 지점을 포함하며, 사용자가 상호작용하는 모든 요소(예: 사용자가 보고, 듣고, 만지는 부분)를 포함합니다. 또한 해당되는 경우 포장, 라벨링, 교육 자료 및 모든 물리적 제어 및 디스플레이 요소(경보 및 각 기기 구성 요소와 전체적인 사용자 인터페이스 시스템의 작동 논리 포함)와 같이 기기에 의해 전달되는 모든 정보 출처를 포함합니다. 사용자 인터페이스는 설정(예: 포장 풀기, 교정), 작동 및 유지보수(예: 청소, 배터리 교체, 수리)를 포함하여 설치 및 사용의 여러 단계에 걸쳐 사용될 수 있습니다. 사용 과정 전반에 걸쳐 중요한 정보를 제공하도록 사용자 인터페이스를 설계하는 것은 기기가 정의된 사용자 요구사항을 충족하고 안전성 및 유효성을 뒷받침하도록 보장하는 데 도움이 됩니다. 인터페이스 전반에 걸쳐 정보를 통합하면 사용자가 의도된 목적에 부합하는 안전하고 효과적인 사용을 가능하게 하기 위해 적절한 시간과 위치에 올바른 정보를 받을 수 있습니다. 소프트웨어 또는 모바일 애플리케이션의 경우, 제조업체는 전통적인 라벨링에 더하여 화면 메시지 또는 다른 기기로 전송되는 경고와 같은 인터페이스 요소를 사용하여 적절한 시간에 기기 위험을 전달할 수 있습니다.

FDA가 기기의 작동 방식을 이해하는 데 도움이 되도록 시판 신청서에 사용자 인터페이스에 대한 전체적인 이해를 제공하는 것이 중요합니다. 스폰서가 위험 분석 또는 신청서의 다른 섹션에서 사용자 인터페이스 설계를 제어 수단으로 참조하는 경우, 사용자 인터페이스 설명을 포함하는 것이 해당 위험 통제에 대한 설명을 뒷받침할 수 있습니다. 그러나 위험 통제의 효과성에 대한 실제 분석은 사용자 인터페이스 설명과는 별도로 위치해야 합니다. 이 주제에 대한 추가 세부사항은 섹션 VII(*위험 평가*) 및 부록 D(*사용성 평가 고려사항*)에 설명되어 있습니다.

라벨링과 관련하여, 기기 사용자 인터페이스는 라벨링을 포함하지만 이에 국한되지 않습니다. 사용자 인터페이스 내의 라벨링은 특정 규제 요건의 적용을 받습니다. 예를 들어, 기기가 처방용인지 여부에 따라, 제조업체는 일반인 또는 처방 기기의 경우 면허를 소지한 의료인이 "기기를 안전하게 그리고 의도된 목적으로 사용할 수 있도록" 보장하기 위한 적절한 사용 지침을 포함하는 라벨링을 제공해야 합니다. AI 기반 기기에 대해 이러한 요건을 충족하는 한 가지 방법은 라벨링에 모델, 성능 특성 및 모델이 기기에 어떻게 통합되는지에 대한 명확한 정보를 제공하는 것입니다. 사용자는 모델 학습에 사용된 데이터의 성격과 같은 세부사항이 필요할 수 있으며, 이는 기기가 어떻게 수행되어야 하는지 그리고 어떤 요인이 성능에 영향을 미칠 수 있는지를 이해하는 데 중요할 수 있습니다.

다음 섹션은 사용자에게 무엇이 전달되고 사용자가 기기와 어떻게 상호작용하는지에 대한 FDA의 이해를 뒷받침하기 위해 시판 신청서에 포함되어야 하는 사용자 인터페이스(섹션 VI.A) 및 라벨링(섹션 VI.B)에 대한 상세한 권고사항을 제공합니다.

부록 B(투명성 설계 고려사항)는 AI 기반 의료기기의 사용자 인터페이스(라벨링 포함) 설계 시 유용할 수 있는 정보 유형, 커뮤니케이션 모드 및 스타일의 예시를 포함하여 투명성에 대한 권장 접근법을 제공합니다. AI 기반 기기에 대한 필수 정보를 명확하게 전달하기 위해 기기 라벨링에 모델 카드를 포함하는 것도 유익할 수 있습니다(부록 E, 모델 카드 예시 참조).

UDI 규정의 적용을 받는 AI 기반 기기를 포함한 모든 기기의 경우 라벨링에 고유 기기 식별자(UDI)를 포함하는 것이 필수임을 유의하십시오. 각각의 새로운 버전 또는 모델 그리고 새로운 기기 포장에 대해 새로운 UDI가 필요합니다. 추가 정보는 FDA의 고유 기기 식별 시스템 웹페이지를 참조하십시오.

## A. User Interface
*Why it should be included in a submission for an AI-enabled device:*
It is important for FDA to understand the device’s user interface in order to fully assess how the device is used. The user interface conveys essential information about what the device is intended to do and how users are expected to interact with it. Viewing the user interface allows FDA to understand how the device will be operated and how it integrates into the clinical workflow, which supports the agency’s evaluation of the device’s safety and effectiveness.

A representation of the user interface can also support the sponsor’s risk assessment and related documentation when the user interface is referenced as a risk control measure. For instance, the user interface can communicate key information that enables safe and effective use, and its design may play a critical role in mitigating or eliminating risks that stem from user misunderstanding or lack of awareness of essential information. While not mandatory, if a sponsor uses elements of the user interface as part of risk controls in their risk assessment, including the user interface in the submission can facilitate FDA’s review. Additional guidance on this topic can be found in Section VII (*Risk Assessment*) and Appendix D (*Usability Evaluation Considerations*).

Although the user interface includes printed labeling (e.g., packaging, user manuals), and all user interface elements should work together to support the user’s understanding of proper device use, labeling should be submitted separately as described in Section VI.B (*Labeling*). This section focuses on how sponsors should provide FDA with an understanding of the remaining elements of the user interface.

*What sponsors should include in a submission:*
Sponsors should provide clear and comprehensive information about the user interface that illustrates the device workflow, including what information is provided to users, when it is provided, and how it is presented. Possible methods to provide this information include:

* Graphical representations (e.g., photographs, illustrations, wireframes, or line drawings) of the device and its user interface, depicting the overall device and all user-interactive components (e.g., display and function screens, alarm speakers, controls).
* Written descriptions explaining the user interface and its main elements.
* An overview of the operational sequence** of the device and the user’s expected interactions with it, detailing user actions and corresponding device responses when relevant.
* Examples of output formats, such as representative reports showing a range of expected outcomes.
* A recorded demonstration video of the device in operation, showing how users interact with the interface and how outputs are presented.

*Where sponsors should provide it in a submission:* The user information about the user interface should be included in the **“Software Description”** section within the Software Documentation portion of the marketing submission.

**A. 사용자 인터페이스**

*AI 기반 기기의 신청서에 왜 포함되어야 하는가:* FDA가 기기의 사용 방식을 완전히 평가하기 위해서는 기기의 사용자 인터페이스를 이해하는 것이 중요합니다. 사용자 인터페이스는 기기가 무엇을 하도록 의도되었는지 그리고 사용자가 어떻게 상호작용할 것으로 예상되는지에 대한 필수 정보를 전달합니다. 사용자 인터페이스를 확인함으로써 FDA는 기기가 어떻게 작동될 것인지 그리고 임상 워크플로에 어떻게 통합되는지를 이해할 수 있으며, 이는 기기의 안전성 및 유효성에 대한 기관의 평가를 뒷받침합니다.

사용자 인터페이스의 표현은 또한 사용자 인터페이스가 위험 통제 수단으로 참조될 때 스폰서의 위험 평가 및 관련 문서를 뒷받침할 수 있습니다. 예를 들어, 사용자 인터페이스는 안전하고 효과적인 사용을 가능하게 하는 주요 정보를 전달할 수 있으며, 그 설계는 사용자의 오해나 필수 정보에 대한 인식 부족에서 비롯되는 위험을 완화하거나 제거하는 데 중요한 역할을 할 수 있습니다. 필수는 아니지만, 스폰서가 위험 평가에서 위험 통제의 일부로 사용자 인터페이스의 요소를 사용하는 경우, 신청서에 사용자 인터페이스를 포함하면 FDA의 검토를 촉진할 수 있습니다. 이 주제에 대한 추가 지침은 섹션 VII(*위험 평가*) 및 부록 D(*사용성 평가 고려사항*)에서 찾을 수 있습니다.

사용자 인터페이스가 인쇄된 라벨링(예: 포장, 사용자 매뉴얼)을 포함하고 모든 사용자 인터페이스 요소가 적절한 기기 사용에 대한 사용자의 이해를 뒷받침하기 위해 함께 작동해야 하지만, 라벨링은 섹션 VI.B(*라벨링*)에 설명된 대로 별도로 제출되어야 합니다. 이 섹션은 스폰서가 사용자 인터페이스의 나머지 요소에 대한 이해를 FDA에 제공해야 하는 방법에 중점을 둡니다.

*스폰서가 신청서에 포함해야 할 내용:* 스폰서는 사용자에게 제공되는 정보, 제공 시기 및 제시 방법을 포함하여 기기 워크플로를 설명하는 사용자 인터페이스에 대한 명확하고 포괄적인 정보를 제공해야 합니다. 이 정보를 제공하는 가능한 방법은 다음과 같습니다:

* 전체 기기 및 모든 사용자 상호작용 구성 요소(예: 디스플레이 및 기능 화면, 경보 스피커, 제어장치)를 묘사하는 기기 및 사용자 인터페이스의 그래픽 표현(예: 사진, 일러스트레이션, 와이어프레임 또는 선 그림).
* 사용자 인터페이스 및 주요 요소를 설명하는 서면 설명.
* 관련이 있는 경우 사용자 행동 및 이에 상응하는 기기 반응을 상세히 설명하면서, 기기의 작동 순서 및 이에 대한 사용자의 예상 상호작용에 대한 개요.
* 예상되는 결과의 범위를 보여주는 대표 보고서와 같은 출력 형식의 예시.
* 사용자가 인터페이스와 상호작용하는 방식 및 출력이 제시되는 방식을 보여주는 작동 중인 기기의 녹화된 시연 비디오.

*스폰서가 신청서에서 제공해야 할 위치:* 사용자 인터페이스에 대한 사용자 정보는 시판 신청서의 소프트웨어 문서 부분 내 **"소프트웨어 설명"** 섹션에 포함되어야 합니다.

## B. Labeling
*Why it should be included in a submission for an AI-enabled device:*
A marketing submission must include labeling information in sufficient detail to allow FDA to determine that the proposed labeling meets applicable regulatory requirements for the type of submission. Device labeling must comply with all relevant FDA labeling regulations, including but not limited to 21 CFR Part 801. This section of the guidance provides labeling considerations specific to AI-enabled devices to help ensure compliance with these requirements and to support FDA’s evaluation of whether the labeling appropriately conveys information necessary for the device’s safe and effective use.

*What sponsors should include in a submission:* The labeling for an AI-enabled device should provide clear, accessible, and user-appropriate information. It should be presented in a format and at a reading level suited to the intended user population—considering characteristics such as age, education or literacy level, sensory or physical impairments, and occupational background—to help ensure users can readily find and comprehend critical information. The use of tables, graphics, or visual elements is encouraged to communicate complex information effectively.

**Inclusion of AI**
* Statement that AI is used in the device.
* Explanation of how AI is used to achieve the device’s intended purpose.
  * For devices with multiple functions, this explanation may include how AI-DSFs (AI-enabled device software functions) interact with each other and how they interact with non-AI DSFs.

**Model Input**
* Description of the model inputs, such as signals or patterns acquired from compatible devices, images from acquisition systems (e.g., MRI), or patient-derived samples that may be entered manually or automatically. Related aspects to consider include:
  * For systems incorporating inputs from an electronic interface: details on necessary system configurations to ensure inputs remain consistent with the design and validation of the AI-enabled device.
  * For systems that require inputs from other medical devices (e.g., x-ray or ultrasound systems): a list of compatible devices or specifications, along with the acceptable acquisition protocols, as applicable.
  * For systems in which loss of model inputs could prevent the device from generating an output: an explanation of the potential impact of lost inputs on device performance.
* Instructions on any steps the user is expected to take to prepare input data for processing by the device, including any expected characteristics (e.g., functional capabilities, experience and knowledge levels, and level of training) of those performing these steps. This information should be consistent with the intended use that was studied in the device validation.

**Model Output**
* Explanation of what the model output means and how it is intended to be used.

**Automation**
* Explanation of the intended degree of automation the device exhibits.

**Model Architecture**
* High level description of the methods and architecture used to develop the model(s) implemented in the device.

**Model Development Data**
* Description of the development data, including:
  * The source(s) of data;
  * Study sites;
  * Sample size;
  * Demographic distributions; and
  * Criteria/expertise used for determining clinical reference standard (ground truth).

**Performance Data**
* Description of the performance validation data, including:
  * The source(s) of data;
  * Study sites;
  * Sample size;
  * Other important study design and data structure information (e.g., randomization schemes, repeated measurements, clinical reference standard);
  * Primary endpoints of the validation study, including pre-specified performance criteria; and
  * Criteria/expertise used for determining clinical reference standard data.

**Device Performance Metrics**
* Description of the device performance metrics.
  * An example of performance metrics may include metrics such as the area under the receiver operating characteristic curve (AUROC), sensitivity and specificity, true/false positive and true/false negative counts (e.g., in a confusion matrix), positive/negative predictive values (PPV/NPV), and positive/negative diagnostic likelihood ratios (PLR/NLR). All performance estimates should be provided with confidence intervals.
* Explanation of the device performance across important subgroups. Generally, subgroup analysis by patient characteristics (e.g., sex, age, race, ethnicity, disease severity), geographic sites, and data collection equipment are appropriate.
* Description of the corresponding performance for different operating points, including subgroup analysis for each operating point, as applicable.

**Performance Monitoring**
* Description of any methods or tools to monitor and manage device performance, including instructions for the use of such tools, as applicable when ongoing performance monitoring and management by the user is considered necessary for the safe and effective use of the device.

**Limitations**
* Description of all known limitations of the AI-enabled device, AI-DSF(s), or model(s).
  * Some limitations of a model may not reach the degree of severity that would warrant a contraindication, warning, or precaution, but they may still be important to include in labeling. For example, the training dataset may have only included a few patients with a rare presentation of a disease or condition; users may benefit knowing the limitations of the data when that rare presentation is suggested by the model as a diagnosis.

**Installation and Use**
* Information about the installation and implementation instructions, including:
  * Instructions on integrating the AI-enabled device into the site’s data systems and clinical workflow; and
  * Instructions for ensuring that any input data are compatible and appropriate for the device.
    * Terms may need to be explicitly defined. For example, a healthcare system and a manufacturer may both have data labeled as “sex,” but one may be using sex at birth while the other may be using self-reported sex.

**Customization**
* Description of and instructions on any customizable features, including:
  * When users or healthcare systems can configure the operating points for the device;
  * When it is appropriate to select different configurations; and
  * When operating points are configurable, how end users can discern the operating point the device is currently operating at.

**Metrics and Visualizations**
* Explanation of any additional metrics or visualizations used to add context to the model output.

**Patient and Caregiver Information**
For AI-enabled devices intended for use by patients or caregivers, manufacturers should provide labeling material that is designed for patients and caregivers describing the instructions for use, the device’s indication, intended use, risks, and limitations. Patients and caregivers are considered users if they will operate the device, interpret the outcome, or make decisions based on the outcome, even if they are not the only user or the primary operator of the device. This material should be at an appropriate reading level for the intended audience. If patient and caregiver-specific material is not provided, sponsors should provide an explanation of how patients and caregivers will understand how to use the device, including how to make decisions about whether to use the device and how to use the output of the device.

*Where sponsors should provide it in a submission:* Information regarding the AI-enabled device labeling should be included in the “Labeling” section of the marketing submission.

**B. 라벨링**

*AI 기반 기기의 신청서에 왜 포함되어야 하는가:* 시판 신청서는 제안된 라벨링이 신청 유형에 대한 적용 가능한 규제 요건을 충족한다는 것을 FDA가 판단할 수 있도록 충분히 상세한 라벨링 정보를 포함해야 합니다. 기기 라벨링은 21 CFR Part 801을 포함하되 이에 국한되지 않는 모든 관련 FDA 라벨링 규정을 준수해야 합니다. 본 지침서의 이 섹션은 이러한 요건의 준수를 보장하고 라벨링이 기기의 안전하고 효과적인 사용에 필요한 정보를 적절하게 전달하는지에 대한 FDA의 평가를 뒷받침하기 위해 AI 기반 기기에 특정한 라벨링 고려사항을 제공합니다.

*스폰서가 신청서에 포함해야 할 내용:* AI 기반 기기의 라벨링은 명확하고 접근 가능하며 사용자에게 적합한 정보를 제공해야 합니다. 사용자가 중요한 정보를 쉽게 찾고 이해할 수 있도록 보장하기 위해, 연령, 교육 또는 문해력 수준, 감각 또는 신체적 장애, 직업적 배경과 같은 특성을 고려하여 의도된 사용자 집단에 적합한 형식과 읽기 수준으로 제시되어야 합니다. 복잡한 정보를 효과적으로 전달하기 위해 표, 그래픽 또는 시각적 요소의 사용이 권장됩니다.

**AI의 포함**
* 기기에 AI가 사용된다는 진술.
* 기기의 의도된 목적을 달성하기 위해 AI가 어떻게 사용되는지에 대한 설명.
  * 여러 기능을 가진 기기의 경우, 이 설명에는 AI-DSF(AI 기반 기기 소프트웨어 기능)가 서로 어떻게 상호작용하고 비AI DSF와 어떻게 상호작용하는지가 포함될 수 있습니다.

**모델 입력**
* 호환 기기로부터 획득된 신호 또는 패턴, 획득 시스템(예: MRI)의 영상, 또는 수동 또는 자동으로 입력될 수 있는 환자 유래 샘플과 같은 모델 입력에 대한 설명. 고려해야 할 관련 측면은 다음과 같습니다:
  * 전자 인터페이스로부터의 입력을 통합하는 시스템의 경우: 입력이 AI 기반 기기의 설계 및 검증과 일치하도록 보장하기 위해 필요한 시스템 구성에 대한 세부사항.
  * 다른 의료기기(예: X선 또는 초음파 시스템)로부터의 입력이 필요한 시스템의 경우: 해당되는 경우 호환 기기 또는 사양 목록과 허용 가능한 획득 프로토콜.
  * 모델 입력의 손실이 기기가 출력을 생성하는 것을 방해할 수 있는 시스템의 경우: 손실된 입력이 기기 성능에 미치는 잠재적 영향에 대한 설명.
* 기능적 능력, 경험 및 지식 수준, 교육 수준 등 이러한 단계를 수행하는 사람들의 예상되는 특성을 포함하여, 사용자가 기기에 의해 처리될 입력 데이터를 준비하기 위해 수행할 것으로 예상되는 모든 단계에 대한 지침. 이 정보는 기기 검증에서 연구된 의도된 용도와 일치해야 합니다.

**모델 출력**
* 모델 출력이 의미하는 바와 어떻게 사용되도록 의도되었는지에 대한 설명.

**자동화**
* 기기가 나타내는 의도된 자동화 정도에 대한 설명.

**모델 아키텍처**
* 기기에 구현된 모델을 개발하는 데 사용된 방법 및 아키텍처에 대한 개괄적 설명.

**모델 개발 데이터**
* 다음을 포함한 개발 데이터에 대한 설명:
  * 데이터 출처;
  * 연구 현장;
  * 샘플 크기;
  * 인구통계학적 분포; 그리고
  * 임상 기준 표준(ground truth)을 결정하는 데 사용된 기준/전문성.

**성능 데이터**
* 다음을 포함한 성능 검증 데이터에 대한 설명:
  * 데이터 출처;
  * 연구 현장;
  * 샘플 크기;
  * 기타 중요한 연구 설계 및 데이터 구조 정보(예: 무작위화 방식, 반복 측정, 임상 기준 표준);
  * 사전 명시된 성능 기준을 포함한 검증 연구의 주요 평가변수; 그리고
  * 임상 기준 표준 데이터를 결정하는 데 사용된 기준/전문성.

**기기 성능 지표**
* 기기 성능 지표에 대한 설명.
  * 성능 지표의 예로는 수신자 조작 특성 곡선 아래 면적(AUROC), 민감도 및 특이도, 참/거짓 양성 및 참/거짓 음성 횟수(예: 혼동 행렬), 양성/음성 예측값(PPV/NPV), 양성/음성 진단 우도비(PLR/NLR)와 같은 지표가 포함될 수 있습니다. 모든 성능 추정치는 신뢰구간과 함께 제공되어야 합니다.
* 중요한 하위 그룹 전반의 기기 성능에 대한 설명. 일반적으로, 환자 특성(예: 성별, 연령, 인종, 민족, 질병 중증도), 지리적 현장 및 데이터 수집 장비별 하위 그룹 분석이 적절합니다.
* 해당되는 경우 각 작동 지점에 대한 하위 그룹 분석을 포함하여 다양한 작동 지점에 대한 해당 성능에 대한 설명.

**성능 모니터링**
* 사용자에 의한 지속적인 성능 모니터링 및 관리가 기기의 안전하고 효과적인 사용에 필요하다고 간주될 때 해당되는 경우, 이러한 도구의 사용 지침을 포함하여 기기 성능을 모니터링하고 관리하는 모든 방법 또는 도구에 대한 설명.

**제한사항**
* AI 기반 기기, AI-DSF 또는 모델의 알려진 모든 제한사항에 대한 설명.
  * 모델의 일부 제한사항은 금기사항, 경고 또는 주의사항을 정당화할 정도의 심각도에 도달하지 않을 수 있지만, 여전히 라벨링에 포함하는 것이 중요할 수 있습니다. 예를 들어, 학습 데이터셋에는 질병 또는 상태의 드문 발현을 가진 환자가 몇 명만 포함되었을 수 있습니다; 모델이 진단으로 드문 발현을 제안할 때 사용자는 데이터의 제한사항을 아는 것이 도움이 될 수 있습니다.

**설치 및 사용**
* 다음을 포함한 설치 및 구현 지침에 대한 정보:
  * AI 기반 기기를 현장의 데이터 시스템 및 임상 워크플로에 통합하는 지침; 그리고
  * 모든 입력 데이터가 기기에 호환되고 적절한지 확인하기 위한 지침.
    * 용어는 명시적으로 정의되어야 할 수 있습니다. 예를 들어, 의료 시스템과 제조업체 모두 "성별"로 라벨링된 데이터를 가질 수 있지만, 하나는 출생 시 성별을 사용하고 다른 하나는 자가 보고된 성별을 사용할 수 있습니다.

**맞춤화**
* 다음을 포함한 모든 맞춤화 가능한 기능에 대한 설명 및 지침:
  * 사용자 또는 의료 시스템이 기기의 작동 지점을 구성할 수 있는 시기;
  * 다양한 구성을 선택하는 것이 적절한 시기; 그리고
  * 작동 지점이 구성 가능할 때, 최종 사용자가 기기가 현재 작동하고 있는 작동 지점을 어떻게 식별할 수 있는지.

**지표 및 시각화**
* 모델 출력에 맥락을 추가하는 데 사용되는 모든 추가 지표 또는 시각화에 대한 설명.

**환자 및 간병인 정보**
환자 또는 간병인이 사용하도록 의도된 AI 기반 기기의 경우, 제조업체는 사용 지침, 기기의 적응증, 의도된 용도, 위험 및 제한사항을 설명하는 환자 및 간병인을 위해 설계된 라벨링 자료를 제공해야 합니다. 환자 및 간병인은 비록 그들이 유일한 사용자 또는 기기의 주요 작동자가 아니더라도, 기기를 작동하거나, 결과를 해석하거나, 결과에 기반하여 결정을 내릴 경우 사용자로 간주됩니다. 이 자료는 의도된 대상에게 적절한 읽기 수준이어야 합니다. 환자 및 간병인 특정 자료가 제공되지 않는 경우, 스폰서는 기기 사용 여부에 대한 결정을 내리는 방법 및 기기의 출력을 사용하는 방법을 포함하여 환자 및 간병인이 기기 사용 방법을 어떻게 이해할 것인지에 대한 설명을 제공해야 합니다.

*스폰서가 신청서에서 제공해야 할 위치:* AI 기반 기기 라벨링에 관한 정보는 시판 신청서의 "라벨링" 섹션에 포함되어야 합니다.

ADDITIONAL RESOURCES:
* Appendix B (Transparency Design Considerations) outlines a potential approach to understanding a device’s indications for use and a model card, which may aid in the development of the user interface.
* While model cards are not required for presenting information about the labeling or user interface, they may be a helpful tool to organize information. In general, model cards can be adapted to the specific needs and context of each AI-enabled device.
  * Appendix E (Example Model Card) includes an example of a basic model card format intended for users and healthcare providers that conveys information including a summary of the model’s intended use and intended users, and evidence supporting safety and effectiveness.
  * Appendix F (Example 510(k) Submission Summary with Model Card) includes an example of a completed basic model card.
* FDA’s guidance titled “Device Labeling Guidance #G91-1 (Blue Book Memo)” includes suggestions regarding what information should be included within device labeling.

추가 자료:
* 부록 B(투명성 설계 고려사항)는 기기의 사용 적응증 및 모델 카드를 이해하기 위한 잠재적 접근법을 개괄하며, 이는 사용자 인터페이스 개발에 도움이 될 수 있습니다.
* 모델 카드는 라벨링 또는 사용자 인터페이스에 대한 정보를 제시하는 데 필수는 아니지만, 정보를 구성하는 데 유용한 도구가 될 수 있습니다. 일반적으로 모델 카드는 각 AI 기반 기기의 특정 요구사항 및 맥락에 맞게 조정될 수 있습니다.
  * 부록 E(모델 카드 예시)는 모델의 의도된 용도 및 의도된 사용자에 대한 요약, 그리고 안전성 및 유효성을 뒷받침하는 증거를 포함한 정보를 전달하는, 사용자 및 의료 제공자를 위한 기본 모델 카드 형식의 예시를 포함합니다.
  * 부록 F(모델 카드가 포함된 510(k) 신청 요약 예시)는 작성이 완료된 기본 모델 카드의 예시를 포함합니다.
* "기기 라벨링 지침 #G91-1(Blue Book Memo)"이라는 제목의 FDA 지침서는 기기 라벨링 내에 포함되어야 하는 정보에 대한 제안을 포함합니다.

# VII. Risk Assessment
*Why should it be included in a submission for an AI-enabled device:* A comprehensive risk assessment helps ensure the device is safe and effective. When included in a marketing submission, a comprehensive risk assessment helps FDA understand whether appropriate risks have been identified and how they are controlled. In Section VI.C of the Premarket Software Guidance, FDA recommends that marketing submissions that include device software functions include a risk management file composed of a risk management plan, a risk assessment, and a risk management report. Consistent with this, marketing submissions of AI-enabled devices should include a risk management file that takes into account the recommendations of Premarket Software Guidance and the recommendations of this guidance, in addition to any other applicable guidance.

Sponsors should also refer to the FDA-recognized version of ANSI/AAMI/ISO 14971 *Medical devices - Application of risk management to medical devices* for additional information on the development and application of a risk management file, which is also applicable to AI-enabled devices. FDA also recognizes that AI-enabled devices can be associated with new or different risks than device software functions generally. Therefore, FDA also recommends that sponsors incorporate the considerations outlined in the FDA-recognized voluntary consensus standard of AAMI CR34971 *Guidance on the Application of ISO 14971 to Artificial Intelligence and Machine Learning*, which is specific to AI-enabled devices.

**Risks Across the TPLC**
When conducting a risk analysis, the *Medical Devices; Current Good Manufacturing Practice (CGMP), final rule* (Oct. 7, 1996, 61 FR 52602) states “manufacturers are expected to identify possible hazards associated with the design in both normal and fault conditions. The risks associated with the hazards, including those resulting from user error, should then be calculated in both normal and fault conditions. If any risk is judged unacceptable, it should be reduced to acceptable levels by the appropriate means.” This risk assessment should take into account all users, as described in Section VI (User Interface and Labeling) of this guidance, across the TPLC. FDA recommends that manufacturers follow this approach for AI-enabled devices across their TPLC.

**Risks Related to Information in AI-Enabled Devices**
One aspect of risk management that can be particularly important for AI-enabled devices is the management of risks that are related to understanding information that is necessary to use or interpret the device, including risks related to lack of information or unclear information. Misunderstood, misused, or unavailable information can impact the safe and effective use of a device. For example, for devices that utilize complex algorithms, including AI-enabled devices, the performance in different disease subtypes may not be apparent to users, or the logic underlying the output information may not be easily understandable, which can negatively affect user understanding and use of the device. Lack of, or unclear information can also make it difficult for different users to understand whether a device is not performing as expected, or how to correctly follow instructions. FDA recommends that consideration of risks related to understanding information should be one part of a comprehensive approach to risk management for an AI-enabled device.

**VII. 위험 평가**

*AI 기반 기기의 신청서에 왜 포함되어야 하는가:* 포괄적인 위험 평가는 기기가 안전하고 효과적임을 보장하는 데 도움이 됩니다. 시판 신청서에 포함될 때, 포괄적인 위험 평가는 FDA가 적절한 위험이 식별되었는지 그리고 그것이 어떻게 통제되는지를 이해하는 데 도움이 됩니다. 시판 전 소프트웨어 지침서의 섹션 VI.C에서, FDA는 기기 소프트웨어 기능을 포함하는 시판 신청서가 위험 관리 계획, 위험 평가 및 위험 관리 보고서로 구성된 위험 관리 파일을 포함할 것을 권장합니다. 이와 일치하게, AI 기반 기기의 시판 신청서는 시판 전 소프트웨어 지침서의 권고사항 및 본 지침서의 권고사항과 기타 적용 가능한 지침서를 고려한 위험 관리 파일을 포함해야 합니다.

스폰서는 또한 AI 기반 기기에도 적용 가능한 위험 관리 파일의 개발 및 적용에 대한 추가 정보를 위해 ANSI/AAMI/ISO 14971 *의료기기 - 의료기기에 대한 위험 관리의 적용*의 FDA 인정 버전을 참조해야 합니다. FDA는 또한 AI 기반 기기가 일반적인 기기 소프트웨어 기능과 다른 새로운 또는 다른 위험과 연관될 수 있음을 인식하고 있습니다. 따라서 FDA는 또한 스폰서가 AI 기반 기기에 특정한 AAMI CR34971 *ISO 14971의 인공지능 및 기계학습에 대한 적용 지침*의 FDA 인정 자발적 합의 표준에 개괄된 고려사항을 통합할 것을 권장합니다.

**TPLC 전반의 위험**

위험 분석을 수행할 때, *의료기기; 현행 우수 제조 관리 기준(CGMP), 최종 규칙*(1996년 10월 7일, 61 FR 52602)은 "제조업체는 정상 및 고장 조건 모두에서 설계와 관련된 가능한 위해요소를 식별할 것으로 예상된다. 사용자 오류로 인한 것을 포함하여 위해요소와 관련된 위험은 정상 및 고장 조건 모두에서 계산되어야 한다. 어떤 위험이든 허용 불가능하다고 판단되면, 적절한 수단을 통해 허용 가능한 수준으로 감소시켜야 한다"고 명시합니다. 이 위험 평가는 TPLC 전반에 걸쳐 본 지침서의 섹션 VI(사용자 인터페이스 및 라벨링)에 설명된 모든 사용자를 고려해야 합니다. FDA는 제조업체가 TPLC 전반에 걸쳐 AI 기반 기기에 대해 이 접근법을 따를 것을 권장합니다.

**AI 기반 기기의 정보와 관련된 위험**

AI 기반 기기에 특히 중요할 수 있는 위험 관리의 한 측면은 정보 부족 또는 불명확한 정보와 관련된 위험을 포함하여, 기기를 사용하거나 해석하는 데 필요한 정보의 이해와 관련된 위험의 관리입니다. 잘못 이해되거나, 잘못 사용되거나, 이용할 수 없는 정보는 기기의 안전하고 효과적인 사용에 영향을 미칠 수 있습니다. 예를 들어, AI 기반 기기를 포함하여 복잡한 알고리즘을 활용하는 기기의 경우, 다양한 질병 아형에서의 성능이 사용자에게 명확하지 않을 수 있거나, 출력 정보의 기반이 되는 논리가 쉽게 이해되지 않을 수 있으며, 이는 기기에 대한 사용자의 이해 및 사용에 부정적인 영향을 미칠 수 있습니다. 정보의 부족 또는 불명확한 정보는 또한 다양한 사용자가 기기가 예상대로 작동하지 않는지 여부를 이해하거나 지침을 올바르게 따르는 것을 어렵게 만들 수 있습니다. FDA는 정보의 이해와 관련된 위험에 대한 고려가 AI 기반 기기에 대한 포괄적인 위험 관리 접근법의 일부가 되어야 한다고 권장합니다.

ADDITIONAL RESOURCES:
* ANSI/AAMI HE75 *Human factors engineering - Design of medical devices* includes recommendations on using information in labeling to help control risks.

추가 자료:
* ANSI/AAMI HE75 *인적 요인 공학 - 의료기기의 설계*는 위험을 통제하는 데 도움이 되도록 라벨링에 정보를 사용하는 것에 대한 권고사항을 포함합니다.

*What sponsors should include in a submission:* Sponsors should provide a “Risk Management File” that includes a risk management plan, including a risk assessment. In addition to other considerations, the risk assessment should consider user tasks and knowledge tasks that occur throughout the full continuum of use of the device, including, for example, the process of installing the device, maintaining performance over time, and any risks associated with user interpretation of the results of a device, as appropriate.

In addition to the considerations provided in FDA-recognized voluntary consensus standards and applicable guidances, FDA recommends that sponsors consider the risks related to understanding information during the risk assessment. As with all identified risks, sponsors should provide an explanation of any risk controls, including elements of the user interface, such as labeling, that address the identified risks. Information that may be helpful to discuss such risks and their controls, as applicable, is provided in Appendix D (Usability Evaluation Considerations).

*Where sponsors should provide it in a submission:* Much of the information on risk assessment for an AI-enabled device should be included in the “Risk Management File” in the Software Documentation section of the marketing submission, as recommended by the Premarket Software Guidance.

*스폰서가 신청서에 포함해야 할 내용:* 스폰서는 위험 평가를 포함한 위험 관리 계획을 포함하는 "위험 관리 파일"을 제공해야 합니다. 다른 고려사항 외에도, 위험 평가는 적절한 경우 기기 설치 과정, 시간 경과에 따른 성능 유지, 기기 결과에 대한 사용자 해석과 관련된 모든 위험을 포함하여 기기 사용의 전체 연속체 전반에 걸쳐 발생하는 사용자 작업 및 지식 작업을 고려해야 합니다.

FDA 인정 자발적 합의 표준 및 적용 가능한 지침서에 제공된 고려사항 외에도, FDA는 스폰서가 위험 평가 중에 정보의 이해와 관련된 위험을 고려할 것을 권장합니다. 식별된 모든 위험과 마찬가지로, 스폰서는 식별된 위험을 다루는 라벨링과 같은 사용자 인터페이스의 요소를 포함한 모든 위험 통제에 대한 설명을 제공해야 합니다. 해당되는 경우 이러한 위험 및 그 통제를 논의하는 데 도움이 될 수 있는 정보는 부록 D(사용성 평가 고려사항)에 제공됩니다.

*스폰서가 신청서에서 제공해야 할 위치:* AI 기반 기기의 위험 평가에 대한 정보의 대부분은 시판 전 소프트웨어 지침서에서 권장하는 바와 같이 시판 신청서의 소프트웨어 문서 섹션의 "위험 관리 파일"에 포함되어야 합니다.

ADDITIONAL RESOURCES:
* Appendix B (Transparency Design Considerations) outlines recommendations for a user-centered design approach to developing a device, which may aid in the identification of risks and development of risk controls.
* Appendix D (Usability Evaluation Considerations) provides recommendations on usability testing, which may help sponsors evaluate the efficacy of proposed controls for information-related risks.

추가 자료:
* 부록 B(투명성 설계 고려사항)는 위험 식별 및 위험 통제 개발에 도움이 될 수 있는 기기 개발을 위한 사용자 중심 설계 접근법에 대한 권고사항을 개괄합니다.
* 부록 D(사용성 평가 고려사항)는 스폰서가 정보 관련 위험에 대해 제안된 통제의 효과를 평가하는 데 도움이 될 수 있는 사용성 시험에 대한 권고사항을 제공합니다.

# VIII. Data Management
*Why should it be included in a submission for an AI-enabled device:* For an AI-enabled device, the model is part of the mechanism of action. Therefore, a clear explanation of the data management, including data management practices (i.e., how data has been or will be collected, processed, annotated, stored, controlled, and used) and characterization of data used in the development and validation of the AI-enabled device is critical for FDA to understand how the device was developed and validated. This understanding helps to enable FDA’s evaluation of an AI-enabled device’s safety and effectiveness.

The performance and behavior of AI systems rely heavily on the quality, diversity, and quantity of data used to train and tune them. The accuracy and usefulness of a validation of an AI-enabled device also depends on the quality, diversity, and quantity of data used to test it. Thus, FDA reviewers evaluate data management in order to understand whether an AI-enabled device is safe and effective. This includes the alignment of the collection and management of training and test data with the intended use and resulting device requirements.

Data management is also an important means of identifying and mitigating bias. The characterization of sources of bias is necessary to assess the potential for AI bias in the AI-enabled device. AI bias is a potential tendency to produce incorrect results in a systematic, but sometimes unforeseeable, way due to limitations in the training data or erroneous assumptions in the machine learning process. AI bias has been well-documented. For example, during training, models can be over-trained to recognize features of images that are unique to specific scanners, patient subpopulations, or clinical sites but have little to do with generalizable patient anatomy, physiology, or condition, which can lead to AI bias in the resulting model. In another example, underrepresentation of certain populations in datasets could lead to overfitting (i.e., data fitting too closely to the potential biases of the training data) based on demographic characteristics, which can impact the AI-enabled device performance in the underrepresented population.

Using unbiased, representative training data for models promotes generalizability to the intended use population and avoids perpetuating biases or idiosyncrasies from the data itself. For example, in image recognition tasks, confounding may occur when all the diseased cases are imaged with the same instrument, or with a ruler included (e.g., on clinical images of melanoma). Another example of a potential confounding factor is the use of data collected outside the U.S. (OUS) in training, which may bias the model if the OUS population does not reflect the U.S. population due to differences in demographics, practice of medicine, or standard of care. Such confounders in the training data, if not identified and mitigated, can be inadvertently learned by a model, leading to seemingly accurate (but misleading) predictions based on irrelevant characteristics.

The inclusion of representative data in validation datasets may be important, because underrepresentation may impact the ability to identify any performance problems, including understanding performance in underrepresented populations. Although bias may be difficult to eliminate completely, FDA recommends that manufacturers, as a starting point, ensure that the validation data sufficiently represents the intended use (target) population of a medical device. For more information regarding age-, race-, ethnicity-, and sex-specific data please see the FDA guidances titled, “Collection of Race and Ethnicity Data in Clinical Trials and Clinical Studies for FDA-Regulated Medical Products,” “Evaluation and Reporting of Age-, Race-, and Ethnicity-Specific Data in Medical Device Clinical Studies,” and “Evaluation of Sex-Specific Data in Medical Device Clinical Studies.”

If the same confounders are found in the validation data as the development data, it may be particularly difficult to identify the spurious correlations that appear to be leading to correct predictions. Therefore, information about the representativeness of the datasets used in the development and validation of the AI-enabled device is important to help FDA determine substantial equivalence or if there is a reasonable assurance that the device is safe and effective for its intended use. Beyond addressing AI bias, the details of the data management should support the intended use of the device.

To objectively assess the device performance, it is also important for FDA reviewers to understand whether the test data are independent (e.g., sampled from completely different clinical sites) from the training data and are sequestered from the model developers and the model development stage. Appropriate separation of the development and test datasets can help with evaluating the true performance of an AI-enabled device. Data leakage between the validation and development datasets can create uncertainty regarding the true performance of the AI-enabled device.

*What sponsors should include in a submission:* In a submission, a sponsor should provide the following types of information for both the training and testing data, in the appropriate marketing submission sections. It may be helpful to organize data management information by the sections described below. Generally, information on data collection, development and test data independence, reference standards, and representativeness should be provided. Sponsors should also explain any differences in the data management approach and the characteristics of the data between the development and validation phases. The submission should include an explanation for the differences and justification for them.

Data Collection
* A description of how data were collected (e.g., clinical study protocols with inclusion/exclusion criteria), including:
  * The names of clinical sites or institutions involved.
    * Sites should be uniquely identified, and they should be referred to consistently throughout the submission.
  * The time period during which the data were acquired.
  * If data were used from a pre-existing database, the appropriateness of the use of this database.
  * If real-world data (RWD) are used, the source and collection of this evidence.
    * If RWD are used, FDA recommends that sponsors provide an assessment of fit-for-purpose data for the selected data source(s) that evaluates both the relevance and reliability of the RWD. FDA encourages sponsors to leverage the Q-Submission Program for obtaining FDA feedback on proposed uses of RWD. For more information regarding RWD, please see the FDA guidance titled “Use of Real-World Evidence to Support Regulatory Decision-Making for Medical Devices.”
* A description of the limitations of the dataset.
* A description of the quality assurance processes related to the data, including the controls that were put in place to protect from human error during data acquisition, when applicable.
* A description of the size of each data set.
* A description of the mechanisms used to improve diversity in enrollment within the scope of the study, and how they ensure the generalizability of study results across patient populations and clinical sites. For more information on this topic, please see FDA guidance titled “Collection of Race and Ethnicity Data in Clinical Trials.”
* A description of the use of synthetic data. Synthetic data used in support of a regulatory submission should be accompanied by a comprehensive explanation of how the data were generated and why they are fit-for-purpose.

Data Cleaning/Processing
To provide optimum training results, it may be important to clean data used for development, such as by removing incorrect, duplicate, or incomplete data. These processing steps should be described, including data quality factors used, data inclusion/exclusion criteria, treatment of missing data, and whether the steps are internal or external to the AI-DSF.

Testing data, on the other hand, should only be processed in a manner that is representative of the RWD the model will encounter in its intended use. Any such data processing, data quality factors used, data inclusion/exclusion criteria, and treatment of missing data should be justified as aligned with pre-processing implemented in the final AI-DSF.

**Reference Standard**
For the purposes of this guidance, a reference standard is the best available representative truth that can be used to define the true condition for each patient/case/record. It is possible that a reference standard may be used in device training, device validation, or both. A reference standard is validated by evidence from current practice within the medical and regulatory communities for establishing a patient’s true status with respect to a clinical task. The reference standard should reflect the clinical task. Clinical tasks may consist of, for example, classification of a disease or condition, segmentation of contours on medical images, detection by bounding boxes, or localization by markings. The following types of information should be provided regarding the selected reference standard:
* A description of how the reference standard was established.
* A description of the uncertainty inherent in the selected reference standard.
* A description of the strategy for addressing cases where results obtained using a reference standard may be equivocal or missing.
* If the reference standard is based on evaluations from clinicians, provide:
  * The grading protocol used.
  * What data are provided to these clinicians.
  * How the clinicians’ evaluations are collected/adjudicated for determining the clinical reference standard, including:
    * blinding protocol; and
    * number of participating clinicians and their qualifications.
  * An assessment of the intra- and/or inter-clinician variability for each task, as applicable, as well as an assessment on whether the observed variability is within commonly accepted standards for a particular measurement task.

**Data Annotation**
* When data annotation is used, the following types of information should be provided regarding the data annotation approach:
  * A description of the expertise of those performing the data annotation.
  * A description of the specific training, instructions or guidelines provided to data annotators to guide their annotation decisions, including whether annotators are blinded to each other.
  * A description of the methods for evaluating quality/consistency of data annotations and adjudicating disagreements (consensus evaluation, sampling). FDA recommends the use of independent assessments by each annotator, without knowledge of the other annotators’ decisions, to ensure objective high-quality data annotations; and
  * A detailed plan for addressing incorrect data annotation.

**Data Storage**
A description of the data storage of both training and test data. The description should address dataset version control and should ensure the security of the data by addressing the items described in Section XII (Cybersecurity) of this guidance.

**Management and Independence of Data**
* A description of the development data, including how the development data were split into training, tuning, tuning evaluation, and any additional subsets, and specification of which model development activities were performed using each dataset.
* A description of the controls in place to ensure the data used for testing is sequestered from the development process.
* A justification of why the data used for validation provides a robust external validation. For example, a description of the sites from which test data originates, because, in general, test data should come from sites different from those used to develop the AI-DSF.

**Representativeness**
* An explanation of how the data is representative of the intended use population and indications for use, including:
  * A description of the relevant population characteristics, when available, including:
    * Disease conditions (e.g., positive/negative cases, disease severity, disease subtype, comorbidities, distribution of the disease spectrum);
    * Patient population demographics (e.g., sex, age, race, ethnicity, height, weight);
    * Data acquisition equipment and conditions (e.g., locations at which data are collected, data acquisition devices/methods, imaging and reconstruction protocols), including any factors that may impact signals analyzed during data acquisition (e.g., patient activities, such as whether a patient is ambulatory, resting, standing; or data acquisition environments, such as intensive care unit, MRI); and
    * Test data collection sites (e.g., clinical sites, institutions). Generally, while a single data collection site may be a useful starting place during initial data assessment phases, reliance on a single site is generally not appropriate for understanding whether the data are representative of the intended use population and indications for use. The use of multiple data collection sites, such as sites in diverse clinical practice settings (e.g., large academic hospital vs. community hospital) may assure a more representative sample of the intended use population. For example, the use of at least three geographically diverse U.S. clinical sites (or healthcare systems) may be appropriate to clinically validate an AI-enabled device.
  * A characterization of the distribution of data along important covariates, including those corresponding to the population characteristics described above.
  * If any of the relevant population characteristics above were not available for the data, an explanation of why, and a justification of the use of the data without this information. FDA understands that, depending on the source of the patients and/or samples used in the training and test data, some relevant patient characteristic information may not be available.
  * A subgroup analysis or analyses stratified by the identified covariates.
  * If OUS data are used during validation, an explanation regarding how the data compares to the U.S. population and U.S. medical practice in terms of general medical practice, disease presentation, prevalence, and progression as well as the demographic characteristics of patients.
    * Due to the data-driven nature of typical models and the obscurity of their algorithms to end users, their generalized performance on the U.S. target population may not be adequately captured in the clinical study if a significant portion of the validation data are OUS data. AI-enabled devices may also be more sensitive than traditional medical devices to the idiosyncratic patterns in the training or test data. For these reasons, they may require higher proportion of U.S. data in the clinical validation. FDA encourages sponsors to leverage the Q-Submission process for obtaining FDA feedback on proposed uses of OUS data.

*Where sponsors should provide it in a submission:* The data management information for data used in the development of the model should be included in the “Software Description” in the Software Documentation section of the marketing submission, as described in the Premarket Software Guidance.

The data management information for data used in the performance validation (i.e., clinical validation) documentation should be included in the “Performance Testing” section of the marketing submission. When the characteristics of data used for model training and validation differ, sponsors should highlight and justify the differences along with the performance validation data management section in the performance testing documentation element.

**VIII. 데이터 관리**

*AI 기반 기기의 신청서에 왜 포함되어야 하는가:* AI 기반 기기의 경우, 모델은 작용 메커니즘의 일부입니다. 따라서 데이터 관리 관행(즉, 데이터가 어떻게 수집, 처리, 아노테이션, 저장, 통제 및 사용되었거나 될 것인지)과 AI 기반 기기의 개발 및 검증에 사용된 데이터의 특성화를 포함한 데이터 관리에 대한 명확한 설명은 FDA가 기기가 어떻게 개발되고 검증되었는지를 이해하는 데 중요합니다. 이러한 이해는 FDA가 AI 기반 기기의 안전성 및 유효성을 평가할 수 있도록 합니다.

AI 시스템의 성능 및 행동은 학습 및 튜닝에 사용되는 데이터의 품질, 다양성 및 양에 크게 의존합니다. AI 기반 기기의 검증의 정확성 및 유용성 또한 시험에 사용되는 데이터의 품질, 다양성 및 양에 달려 있습니다. 따라서 FDA 검토자는 AI 기반 기기가 안전하고 효과적인지 이해하기 위해 데이터 관리를 평가합니다. 이는 의도된 용도 및 결과적인 기기 요건과 학습 및 시험 데이터의 수집 및 관리의 일치를 포함합니다.

데이터 관리는 또한 편향성을 식별하고 완화하는 중요한 수단입니다. AI 기반 기기에서 AI 편향성의 가능성을 평가하기 위해서는 편향성의 출처에 대한 특성화가 필요합니다. AI 편향성은 학습 데이터의 제한 또는 기계학습 과정의 잘못된 가정으로 인해 체계적이지만 때로는 예측할 수 없는 방식으로 잘못된 결과를 생성하는 잠재적 경향입니다. AI 편향성은 잘 문서화되어 있습니다. 예를 들어, 학습 중에 모델은 일반화 가능한 환자 해부학, 생리학 또는 상태와 거의 관련이 없지만 특정 스캐너, 환자 하위 집단 또는 임상 현장에 고유한 영상의 특징을 인식하도록 과도하게 학습될 수 있으며, 이는 결과 모델에서 AI 편향성을 초래할 수 있습니다. 또 다른 예로, 데이터셋에서 특정 인구의 과소대표는 인구통계학적 특성에 기반한 과적합(즉, 학습 데이터의 잠재적 편향에 너무 밀접하게 맞춰지는 데이터)으로 이어질 수 있으며, 이는 과소대표된 인구에서 AI 기반 기기 성능에 영향을 미칠 수 있습니다.

모델에 대한 편향되지 않은 대표적인 학습 데이터를 사용하는 것은 의도된 사용 인구에 대한 일반화 가능성을 촉진하고 데이터 자체의 편향성 또는 특이성을 영속화하는 것을 피합니다. 예를 들어, 영상 인식 작업에서 모든 질병 사례가 동일한 기기로 촬영되거나 자가 포함된 경우(예: 흑색종의 임상 영상) 교란이 발생할 수 있습니다. 잠재적 교란 요인의 또 다른 예는 학습에 미국 외(OUS)에서 수집된 데이터를 사용하는 것인데, OUS 인구가 인구통계학, 의료 관행 또는 치료 표준의 차이로 인해 미국 인구를 반영하지 않는 경우 모델을 편향시킬 수 있습니다. 학습 데이터의 이러한 교란 요인이 식별되고 완화되지 않으면, 모델에 의해 의도치 않게 학습될 수 있으며, 무관한 특성에 기반한 겉보기에 정확하지만 오해의 소지가 있는 예측으로 이어질 수 있습니다.

검증 데이터셋에 대표적인 데이터를 포함하는 것은 과소대표가 과소대표된 인구의 성능 이해를 포함하여 성능 문제를 식별하는 능력에 영향을 미칠 수 있기 때문에 중요할 수 있습니다. 편향성을 완전히 제거하는 것은 어려울 수 있지만, FDA는 제조업체가 출발점으로서 검증 데이터가 의료기기의 의도된 사용(목표) 인구를 충분히 대표하도록 보장할 것을 권장합니다. 연령, 인종, 민족 및 성별별 데이터에 대한 자세한 정보는 "FDA 규제 의료제품에 대한 임상시험 및 임상 연구에서의 인종 및 민족 데이터 수집," "의료기기 임상 연구에서 연령, 인종 및 민족별 데이터의 평가 및 보고," "의료기기 임상 연구에서 성별 데이터의 평가"라는 제목의 FDA 지침서를 참조하십시오.

개발 데이터와 동일한 교란 요인이 검증 데이터에서 발견되면, 정확한 예측으로 이어지는 것처럼 보이는 허위 상관관계를 식별하는 것이 특히 어려울 수 있습니다. 따라서 AI 기반 기기의 개발 및 검증에 사용된 데이터셋의 대표성에 대한 정보는 FDA가 실질적 동등성을 판단하거나 기기가 의도된 용도에 안전하고 효과적이라는 합리적 보증이 있는지를 판단하는 데 중요합니다. AI 편향성을 다루는 것 외에도, 데이터 관리의 세부사항은 기기의 의도된 용도를 뒷받침해야 합니다.

기기 성능을 객관적으로 평가하기 위해서는 FDA 검토자가 시험 데이터가 학습 데이터로부터 독립적인지(예: 완전히 다른 임상 현장에서 샘플링됨) 그리고 모델 개발자 및 모델 개발 단계로부터 격리되어 있는지를 이해하는 것도 중요합니다. 개발 및 시험 데이터셋의 적절한 분리는 AI 기반 기기의 실제 성능을 평가하는 데 도움이 될 수 있습니다. 검증 및 개발 데이터셋 간의 데이터 누출은 AI 기반 기기의 실제 성능에 대한 불확실성을 야기할 수 있습니다.

*스폰서가 신청서에 포함해야 할 내용:* 신청서에서 스폰서는 적절한 시판 신청 섹션에 학습 및 시험 데이터 모두에 대해 다음 유형의 정보를 제공해야 합니다. 아래에 설명된 섹션별로 데이터 관리 정보를 구성하는 것이 도움이 될 수 있습니다. 일반적으로 데이터 수집, 개발 및 시험 데이터 독립성, 참조 표준 및 대표성에 대한 정보가 제공되어야 합니다. 스폰서는 또한 개발 및 검증 단계 간의 데이터 관리 접근법과 데이터 특성의 모든 차이점을 설명해야 합니다. 신청서는 차이점에 대한 설명과 그에 대한 정당화를 포함해야 합니다.

**데이터 수집**
* 다음을 포함한 데이터 수집 방법에 대한 설명(예: 포함/제외 기준이 있는 임상 연구 프로토콜):
  * 관련된 임상 현장 또는 기관의 이름.
    * 현장은 고유하게 식별되어야 하며, 신청서 전반에 걸쳐 일관되게 참조되어야 합니다.
  * 데이터가 획득된 기간.
  * 기존 데이터베이스의 데이터가 사용된 경우, 이 데이터베이스 사용의 적절성.
  * 실세계 데이터(RWD)가 사용되는 경우, 이 증거의 출처 및 수집.
    * RWD가 사용되는 경우, FDA는 스폰서가 RWD의 관련성 및 신뢰성을 모두 평가하는 선택된 데이터 출처에 대한 목적 적합 데이터 평가를 제공할 것을 권장합니다. FDA는 스폰서가 제안된 RWD 사용에 대한 FDA 피드백을 얻기 위해 Q-제출 프로그램을 활용할 것을 권장합니다. RWD에 대한 자세한 정보는 "의료기기에 대한 규제 의사결정을 뒷받침하기 위한 실세계 증거의 사용"이라는 제목의 FDA 지침서를 참조하십시오.
* 데이터셋의 제한사항에 대한 설명.
* 해당되는 경우 데이터 획득 중 인적 오류로부터 보호하기 위해 마련된 통제를 포함하여 데이터와 관련된 품질 보증 프로세스에 대한 설명.
* 각 데이터 세트의 크기에 대한 설명.
* 연구 범위 내에서 등록의 다양성을 개선하는 데 사용된 메커니즘과 환자 인구 및 임상 현장 전반에 걸친 연구 결과의 일반화 가능성을 보장하는 방법에 대한 설명. 이 주제에 대한 자세한 정보는 "임상시험에서의 인종 및 민족 데이터 수집"이라는 제목의 FDA 지침서를 참조하십시오.
* 합성 데이터의 사용에 대한 설명. 규제 신청서를 뒷받침하는 데 사용되는 합성 데이터는 데이터가 어떻게 생성되었는지 그리고 왜 목적에 적합한지에 대한 포괄적인 설명을 수반해야 합니다.

**데이터 정제/처리**

최적의 학습 결과를 제공하기 위해, 잘못되거나 중복되거나 불완전한 데이터를 제거하는 등 개발에 사용되는 데이터를 정제하는 것이 중요할 수 있습니다. 사용된 데이터 품질 요인, 데이터 포함/제외 기준, 누락 데이터 처리, 그리고 단계가 AI-DSF의 내부인지 외부인지를 포함하여 이러한 처리 단계가 설명되어야 합니다.

반면 시험 데이터는 모델이 의도된 용도에서 접하게 될 RWD를 대표하는 방식으로만 처리되어야 합니다. 이러한 데이터 처리, 사용된 데이터 품질 요인, 데이터 포함/제외 기준 및 누락 데이터 처리는 최종 AI-DSF에 구현된 전처리와 일치하는 것으로 정당화되어야 합니다.

**참조 표준**

본 지침서의 목적상, 참조 표준은 각 환자/사례/기록에 대한 실제 상태를 정의하는 데 사용될 수 있는 가장 이용 가능한 대표적 진실입니다. 참조 표준은 기기 학습, 기기 검증 또는 둘 다에 사용될 수 있습니다. 참조 표준은 임상 작업과 관련하여 환자의 실제 상태를 확립하기 위한 의료 및 규제 커뮤니티 내의 현재 관행의 증거에 의해 검증됩니다. 참조 표준은 임상 작업을 반영해야 합니다. 임상 작업은 예를 들어 질병 또는 상태의 분류, 의료 영상의 윤곽 분할, 경계 상자에 의한 검출 또는 표시에 의한 위치 파악으로 구성될 수 있습니다. 선택된 참조 표준과 관련하여 다음 유형의 정보가 제공되어야 합니다:
* 참조 표준이 어떻게 확립되었는지에 대한 설명.
* 선택된 참조 표준에 내재된 불확실성에 대한 설명.
* 참조 표준을 사용하여 얻은 결과가 모호하거나 누락된 경우를 다루기 위한 전략에 대한 설명.
* 참조 표준이 임상의의 평가에 기반하는 경우, 다음을 제공하십시오:
  * 사용된 등급 프로토콜.
  * 이러한 임상의에게 제공되는 데이터.
  * 다음을 포함하여 임상 참조 표준을 결정하기 위해 임상의의 평가가 어떻게 수집/판정되는지:
    * 맹검 프로토콜; 그리고
    * 참여 임상의의 수와 그들의 자격.
  * 해당되는 경우 각 작업에 대한 임상의 내 및/또는 임상의 간 변동성 평가, 그리고 관찰된 변동성이 특정 측정 작업에 대해 일반적으로 수용되는 표준 내에 있는지에 대한 평가.

**데이터 아노테이션(annotation)**
* 데이터 아노테이션이 사용되는 경우, 데이터 아노테이션 접근법과 관련하여 다음 유형의 정보가 제공되어야 합니다:
  * 데이터 아노테이션을 수행하는 사람들의 전문성에 대한 설명.
  * 아노테이션자이 서로에게 맹검되어 있는지 여부를 포함하여, 아노테이션 결정을 안내하기 위해 데이터 아노테이션 수행자에게 제공된 특정 교육, 지침 또는 가이드라인에 대한 설명.
  * 데이터 아노테이션의 품질/일관성을 평가하고 불일치를 판정하는 방법에 대한 설명(합의 평가, 샘플링). FDA는 객관적이고 고품질의 데이터 아노테이션를 보장하기 위해 다른 아노테이션자의 결정을 알지 못한 채 각 아노테이션자에 의한 독립적인 평가의 사용을 권장합니다; 그리고
  * 잘못된 데이터 아노테이션를 다루기 위한 상세한 계획.

**데이터 저장**
학습 및 시험 데이터 모두의 데이터 저장에 대한 설명. 설명은 데이터셋 버전 관리를 다루어야 하며, 본 지침서의 섹션 XII(사이버보안)에 설명된 항목을 다룸으로써 데이터의 보안을 보장해야 합니다.

**데이터의 관리 및 독립성**
* 개발 데이터가 학습, 튜닝, 튜닝 평가 및 추가 하위 집합으로 어떻게 분할되었는지, 그리고 각 데이터셋을 사용하여 어떤 모델 개발 활동이 수행되었는지에 대한 사양을 포함한 개발 데이터에 대한 설명.
* 시험에 사용되는 데이터가 개발 프로세스로부터 격리되도록 보장하기 위해 마련된 통제에 대한 설명.
* 검증에 사용된 데이터가 강력한 외부 검증을 제공하는 이유에 대한 정당화. 예를 들어, 일반적으로 시험 데이터는 AI-DSF를 개발하는 데 사용된 현장과 다른 현장에서 나와야 하기 때문에, 시험 데이터가 유래한 현장에 대한 설명.

**대표성**
* 다음을 포함하여 데이터가 의도된 사용 인구 및 사용 적응증을 대표하는 방법에 대한 설명:
  * 이용 가능한 경우 다음을 포함한 관련 인구 특성에 대한 설명:
    * 질병 상태(예: 양성/음성 사례, 질병 중증도, 질병 아형, 동반 질환, 질병 스펙트럼의 분포);
    * 환자 인구 인구통계(예: 성별, 연령, 인종, 민족, 키, 체중);
    * 데이터 획득 중 분석된 신호에 영향을 미칠 수 있는 모든 요인을 포함하여 데이터 획득 장비 및 조건(예: 데이터가 수집되는 위치, 데이터 획득 기기/방법, 영상 및 재구성 프로토콜)(예: 환자가 보행 중인지, 휴식 중인지, 서 있는지와 같은 환자 활동; 또는 중환자실, MRI와 같은 데이터 획득 환경); 그리고
    * 시험 데이터 수집 현장(예: 임상 현장, 기관). 일반적으로 단일 데이터 수집 현장은 초기 데이터 평가 단계에서 유용한 출발점이 될 수 있지만, 단일 현장에 의존하는 것은 일반적으로 데이터가 의도된 사용 인구 및 사용 적응증을 대표하는지 이해하는 데 적절하지 않습니다. 다양한 임상 진료 환경(예: 대형 학술 병원 대 지역 병원)의 현장과 같은 여러 데이터 수집 현장의 사용은 의도된 사용 인구의 보다 대표적인 샘플을 보장할 수 있습니다. 예를 들어, AI 기반 기기를 임상적으로 검증하기 위해 지리적으로 다양한 최소 3개의 미국 임상 현장(또는 의료 시스템)의 사용이 적절할 수 있습니다.
  * 위에 설명된 인구 특성에 해당하는 것을 포함하여 중요한 공변량을 따른 데이터 분포의 특성화.
  * 위의 관련 인구 특성 중 데이터에 대해 이용 가능하지 않은 것이 있는 경우, 그 이유와 이 정보 없이 데이터를 사용하는 것에 대한 정당화에 대한 설명. FDA는 학습 및 시험 데이터에 사용된 환자 및/또는 샘플의 출처에 따라 일부 관련 환자 특성 정보를 이용할 수 없을 수 있음을 이해합니다.
  * 식별된 공변량으로 계층화된 하위 그룹 분석.
  * 검증 중에 OUS 데이터가 사용되는 경우, 일반적인 의료 관행, 질병 발현, 유병률 및 진행뿐만 아니라 환자의 인구통계학적 특성 측면에서 데이터가 미국 인구 및 미국 의료 관행과 어떻게 비교되는지에 대한 설명.
    * 일반적인 모델의 데이터 중심적 특성과 최종 사용자에게 알고리즘의 불투명성으로 인해, 검증 데이터의 상당 부분이 OUS 데이터인 경우 임상 연구에서 미국 목표 인구에 대한 일반화된 성능이 적절하게 포착되지 않을 수 있습니다. AI 기반 기기는 또한 학습 또는 시험 데이터의 특이한 패턴에 전통적인 의료기기보다 더 민감할 수 있습니다. 이러한 이유로, 임상 검증에서 더 높은 비율의 미국 데이터가 필요할 수 있습니다. FDA는 스폰서가 제안된 OUS 데이터 사용에 대한 FDA 피드백을 얻기 위해 Q-제출 프로세스를 활용할 것을 권장합니다.

*스폰서가 신청서에서 제공해야 할 위치:* 모델 개발에 사용된 데이터에 대한 데이터 관리 정보는 시판 전 소프트웨어 지침서에 설명된 대로 시판 신청서의 소프트웨어 문서 섹션의 "소프트웨어 설명"에 포함되어야 합니다.

성능 검증(즉, 임상 검증) 문서에 사용된 데이터에 대한 데이터 관리 정보는 시판 신청서의 "성능 시험" 섹션에 포함되어야 합니다. 모델 학습 및 검증에 사용된 데이터의 특성이 다른 경우, 스폰서는 성능 시험 문서 요소의 성능 검증 데이터 관리 섹션과 함께 차이점을 강조하고 정당화해야 합니다.

ADDITIONAL RESOURCES:
In addition to the considerations in this guidance, to support the TPLC approach to development, FDA recommends that sponsors and investigators consider the unique characteristics of the AI-enabled device during the study design, conduct, and reporting phases for clinical investigations. Researchers should understand how Investigational Device Exemption (IDE), Protection of Human Subjects and Institutional Review Board regulations, and Good Clinical Practice (GCP) regulations apply to their devices. Resources include consensus guidelines, as well as FDA guidances titled:

* “Significant Risk and Nonsignificant Risk Medical Device Studies”
* “Informed Consent Guidance for IRBs, Clinical Investigators, and Sponsors”
* “Acceptance of Clinical Data to Support Medical Device Applications and Submissions: Frequently Asked Questions”

For more information regarding age-, race-, and ethnicity-specific data, and sex-specific data please see the FDA guidances titled:
* “Collection of Race and Ethnicity Data in Clinical Trials”
* “Evaluation and Reporting of Age-, Race-, and Ethnicity-Specific Data in Medical Device Clinical Studies”
* “Evaluation of Sex-Specific Data in Medical Device Clinical Studies”

추가 자료:

본 지침서의 고려사항 외에도, 개발에 대한 TPLC 접근법을 뒷받침하기 위해, FDA는 스폰서와 연구자가 임상 조사를 위한 연구 설계, 수행 및 보고 단계에서 AI 기반 기기의 고유한 특성을 고려할 것을 권장합니다. 연구자는 임상시험용 기기 면제(IDE), 인간 대상자 보호 및 기관심사위원회 규정, 그리고 우수 임상 시험 관리 기준(GCP) 규정이 그들의 기기에 어떻게 적용되는지 이해해야 합니다. 자료에는 합의 지침과 다음 제목의 FDA 지침서가 포함됩니다:

* "중대한 위험 및 비중대한 위험 의료기기 연구"
* "IRB, 임상 연구자 및 스폰서를 위한 사전 동의 지침"
* "의료기기 신청 및 제출을 뒷받침하기 위한 임상 데이터의 수용: 자주 묻는 질문"

연령, 인종 및 민족별 데이터, 그리고 성별 데이터에 대한 자세한 정보는 다음 제목의 FDA 지침서를 참조하십시오:
* "임상시험에서의 인종 및 민족 데이터 수집"
* "의료기기 임상 연구에서 연령, 인종 및 민족별 데이터의 평가 및 보고"
* "의료기기 임상 연구에서 성별 데이터의 평가"

# IX. Model Description and Development
Why should it be included in a submission for an AI-enabled device:
Information about the model (and device) design, including its biases and limitations, supports FDA’s ability to assess the safety and effectiveness of an AI-enabled device and determine the device’s performance testing specifications.

Section VI.B of the Premarket Software Guidance describes information that should be included as part of a software description in a marketing submission, including the model description. Whereas the device description is broader and provides information about the whole device, how users interact with it, and how it fits into the clinical workflow, the model description, as part of the software description, specifically provides detailed information about the technical characteristics of the model(s) themselves and the algorithms and methods that were used in their development. This information helps FDA understand the basis for the functionality of an AI-enabled device. Understanding the methods used to develop the model also helps FDA identify potential limitations, sources of AI bias, and considerations for appropriate device labeling.

*What sponsors should include in a submission:* In a submission, sponsors should include the information described below for each model in the AI-enabled device.

In situations where multiple models are employed as part of the AI-enabled device, it can be particularly helpful to include a diagram of how model outputs combine to create the device outputs. The description of the algorithms and models should be sufficiently detailed to enable a competent AI practitioner to produce an equivalent model. The use of diagrams in addition to textual descriptions is encouraged to enhance clarity.

Model Description
* An explanation of each model used as part of the AI-enabled device, including but not limited to:
  * Model inputs and outputs;
  * A description of model architecture;
  * A description of features;
  * A description of the feature selection process and any loss function(s) used for model design and optimization, as appropriate; and
  * Model parameters.
* In situations where the AI-enabled device has customizable features involving the model, such as being customizable to operate at multiple pre-defined operating points or with a variable number of inputs, a description of the technical elements of the model that allow for and control customization.
* A description of any quality control criteria or algorithms, including AI-based and third-party ones, for the input data, including how the quality assessment metrics align with the intended use of the device (e.g., intended patient population and use environment).
* A description of any methods applied to the input and/or output data, including:
  * Pre-processing of input data (e.g., normalization);
  * Post-processing of output data; and
  * Data augmentation or synthesis.

Model Development
* A description of how the model was trained, including but not limited to:
  * Optimization methods;
  * Training paradigms (e.g., supervised, unsupervised or semi-supervised learning, federated learning, active learning);
  * Regularization techniques employed;
  * Training hyperparameters (e.g., the loss function learning rate) as applicable; and
  * Summary training performance such as the loss function convergence curves for the different data subsets (such as training, tuning, tuning evaluation).
* If tuning evaluation was conducted, a description of the metrics and results obtained.
* An explanation of any pre-trained models that were used, as applicable.
  * If a pre-trained model was used, specify the dataset that was used for pre-training and how the pre-trained model was obtained.
* A description of the use of ensemble methods (e.g., bagging or boosting), as applicable.
* An explanation of how any thresholds (e.g., operating points) were determined.
* An explanation of any calibration of the model output.

*Where sponsors should provide it in a submission:* Information on model development, including the model description and the method for model development, should be included as part of the “Software Description” in the Software Documentation section of the marketing submission, as described in the Premarket Software Guidance.

**IX. 모델 설명 및 개발**

*AI 기반 기기의 신청서에 왜 포함되어야 하는가:* 편향성 및 제한사항을 포함한 모델(및 기기) 설계에 대한 정보는 FDA가 AI 기반 기기의 안전성 및 유효성을 평가하고 기기의 성능 시험 사양을 결정하는 능력을 뒷받침합니다.

시판 전 소프트웨어 지침서의 섹션 VI.B는 모델 설명을 포함하여 시판 신청서의 소프트웨어 설명의 일부로 포함되어야 하는 정보를 설명합니다. 기기 설명이 더 광범위하며 전체 기기, 사용자가 이와 상호작용하는 방법, 그리고 임상 워크플로에 어떻게 적합한지에 대한 정보를 제공하는 반면, 소프트웨어 설명의 일부인 모델 설명은 특히 모델 자체의 기술적 특성과 개발에 사용된 알고리즘 및 방법에 대한 상세한 정보를 제공합니다. 이 정보는 FDA가 AI 기반 기기의 기능성의 기반을 이해하는 데 도움이 됩니다. 모델을 개발하는 데 사용된 방법을 이해하는 것은 또한 FDA가 잠재적 제한사항, AI 편향성의 출처 및 적절한 기기 라벨링에 대한 고려사항을 식별하는 데 도움이 됩니다.

*스폰서가 신청서에 포함해야 할 내용:* 신청서에서 스폰서는 AI 기반 기기의 각 모델에 대해 아래에 설명된 정보를 포함해야 합니다.

여러 모델이 AI 기반 기기의 일부로 사용되는 상황에서는, 모델 출력이 어떻게 결합되어 기기 출력을 생성하는지에 대한 다이어그램을 포함하는 것이 특히 도움이 될 수 있습니다. 알고리즘 및 모델에 대한 설명은 유능한 AI 실무자가 동등한 모델을 생성할 수 있을 만큼 충분히 상세해야 합니다. 명확성을 향상시키기 위해 텍스트 설명 외에 다이어그램의 사용이 권장됩니다.

**모델 설명**
* 다음을 포함하되 이에 국한되지 않는 AI 기반 기기의 일부로 사용되는 각 모델에 대한 설명:
  * 모델 입력 및 출력;
  * 모델 아키텍처에 대한 설명;
  * 특성에 대한 설명;
  * 적절한 경우 모델 설계 및 최적화에 사용되는 특성 선택 프로세스 및 손실 함수에 대한 설명; 그리고
  * 모델 매개변수.
* AI 기반 기기가 여러 사전 정의된 작동 지점에서 작동하도록 맞춤화되거나 가변 개수의 입력을 갖는 것과 같이 모델과 관련된 맞춤화 가능한 기능을 가진 상황에서, 맞춤화를 허용하고 제어하는 모델의 기술적 요소에 대한 설명.
* 기기의 의도된 용도(예: 의도된 환자 인구 및 사용 환경)와 품질 평가 지표가 어떻게 일치하는지를 포함하여, AI 기반 및 제3자 알고리즘을 포함한 입력 데이터에 대한 모든 품질 관리 기준 또는 알고리즘에 대한 설명.
* 다음을 포함하여 입력 및/또는 출력 데이터에 적용된 모든 방법에 대한 설명:
  * 입력 데이터의 전처리(예: 정규화);
  * 출력 데이터의 후처리; 그리고
  * 데이터 증강 또는 합성.

**모델 개발**
* 다음을 포함하되 이에 국한되지 않는 모델이 어떻게 학습되었는지에 대한 설명:
  * 최적화 방법;
  * 학습 패러다임(예: 지도 학습, 비지도 학습 또는 준지도 학습, 연합 학습, 능동 학습);
  * 사용된 정규화 기법;
  * 해당되는 경우 학습 하이퍼파라미터(예: 손실 함수 학습률); 그리고
  * 다양한 데이터 하위 집합(학습, 튜닝, 튜닝 평가 등)에 대한 손실 함수 수렴 곡선과 같은 학습 성능 요약.
* 튜닝 평가가 수행된 경우, 얻어진 지표 및 결과에 대한 설명.
* 해당되는 경우 사용된 사전 학습 모델에 대한 설명.
  * 사전 학습 모델이 사용된 경우, 사전 학습에 사용된 데이터셋과 사전 학습 모델을 얻은 방법을 명시하십시오.
* 해당되는 경우 앙상블 방법(예: 배깅 또는 부스팅)의 사용에 대한 설명.
* 모든 임계값(예: 작동 지점)이 어떻게 결정되었는지에 대한 설명.
* 모델 출력의 모든 교정에 대한 설명.

*스폰서가 신청서에서 제공해야 할 위치:* 모델 설명 및 모델 개발 방법을 포함한 모델 개발에 대한 정보는 시판 전 소프트웨어 지침서에 설명된 대로 시판 신청서의 소프트웨어 문서 섹션의 "소프트웨어 설명"의 일부로 포함되어야 합니다.

ADDITIONAL RESOURCES:
In situations where manufacturers wish to consider development of models that automatically or continuously update, FDA encourages manufacturers to use the Q-Submission Program to discuss considerations related to these AI models early in the development process and review the FDA guidance titled “Marketing Submission Recommendations for a Predetermined Change Control Plan for Artificial Intelligence-Enabled Device Software Functions.”

추가 자료:

제조업체가 자동으로 또는 지속적으로 업데이트되는 모델의 개발을 고려하고자 하는 상황에서, FDA는 제조업체가 개발 프로세스 초기에 이러한 AI 모델과 관련된 고려사항을 논의하기 위해 Q-제출 프로그램을 사용하고 "인공지능 기반 기기 소프트웨어 기능에 대한 사전 결정 변경 관리 계획의 시판 신청 권고사항"이라는 제목의 FDA 지침서를 검토할 것을 권장합니다.

# X. Validation
For an AI-enabled device, validation includes ensuring that the device, as utilized by users, will perform its intended use safely and effectively, as well as establishing that the relevant performance specifications of the device can be consistently met. For AI-enabled devices, manufacturers should demonstrate users’ ability to interact with and understand the device as intended in addition to ensuring the device itself meets relevant performance specifications. To this end, it can be helpful to consider both performance validation (including human factors validation) and an evaluation of usability. Note that, for the purposes of this guidance (in the context of risk controls in the absence of human factors validation), usability describes whether the device can be used safely and effectively by the intended users, including whether users consistently and correctly receive, understand, interpret, and apply information related to the AI-enabled device.

The FDA guidance titled “Applying Human Factors and Usability Engineering to Medical Devices” (hereafter referred to as “Human Factors Guidance”), describes recommendations and requirements for devices and establishes that human factors validation testing encompasses, “all testing conducted at the end of the device development process to assess user interactions with a device user interface to identify use errors that would or could result in serious harm to the patient or user,” and is also used “to assess the effectiveness of risk management measures.” While the Human Factors Guidance outlines specific recommendations and requirements for human factors validation for devices that have critical tasks, the application of the same or a similar process can also be helpful to demonstrate the appropriate control of other risks. Appendix D (Usability Evaluation Considerations) includes recommendations to help sponsors understand when usability testing may help support the control of risks. The appendix also includes recommendation to help sponsors develop and describe certain types of usability testing in addition to human factors validation, or when human factors validation is not required. The appendix supplements device-specific recommendations and recommendations provided in the Human Factors Guidance where applicable.

Together, performance validation and human factors validation (or an evaluation of usability as appropriate) help provide FDA with information to understand how the device may be used and perform under real world circumstances. Performance validation may employ a variety of testing and monitoring methods to evaluate the statistical performance of the model under testing conditions, and human factors validation testing involves understanding how various users are likely to use a device in context. In other words, performance validation is meant to provide confirmation that device specifications conform to user needs and intended uses, and that performance requirements implemented can be consistently fulfilled, while human factors validation and an evaluation of usability are meant to specifically address whether all intended users can achieve specific goals while using the device and whether users will be able to consistently interact with the device safely and effectively.

Software Version History
Section VI.I of the Premarket Software Guidance describes information that should be included as part of a software description in a marketing submission, including information regarding the software version history. For AI-enabled devices, the software version history includes consideration of the model version and any differences between the tested version of the model and the released version, along with an assessment of the potential effect of the differences on the safety and effectiveness of the device. It is important for FDA to understand what version of the model was tested in order to ensure that all validation activities will be objective, and the model has not been adjusted opportunistically in light of the test data (i.e., post-hoc adjustment) without the Agency’s concurrence.

New unique device identifiers (UDIs) are required for devices that are required to bear a UDI on its label when there is a new version and/or model, and for new device packages.

**X. 검증**

AI 기반 기기의 경우, 검증은 사용자가 활용하는 기기가 의도된 용도를 안전하고 효과적으로 수행할 것임을 보장하고, 기기의 관련 성능 사양이 일관되게 충족될 수 있음을 확립하는 것을 포함합니다. AI 기반 기기의 경우, 제조업체는 기기 자체가 관련 성능 사양을 충족하도록 보장하는 것 외에도 사용자가 의도된 대로 기기와 상호작용하고 이해할 수 있는 능력을 입증해야 합니다. 이를 위해 성능 검증(인적 요인 검증 포함)과 사용성 평가를 모두 고려하는 것이 도움이 될 수 있습니다. 본 지침서의 목적상(인적 요인 검증이 없는 경우 위험 통제의 맥락에서) 사용성은 사용자가 AI 기반 기기와 관련된 정보를 일관되고 정확하게 수신, 이해, 해석 및 적용하는지 여부를 포함하여, 의도된 사용자가 기기를 안전하고 효과적으로 사용할 수 있는지 여부를 설명한다는 점에 유의하십시오.

"의료기기에 대한 인적 요인 및 사용성 공학 적용"(이하 "인적 요인 지침서"라고 지칭)이라는 제목의 FDA 지침서는 기기에 대한 권고사항 및 요건을 설명하며, 인적 요인 검증 시험이 "환자 또는 사용자에게 심각한 해를 초래하거나 초래할 수 있는 사용 오류를 식별하기 위해 기기 사용자 인터페이스와의 사용자 상호작용을 평가하기 위해 기기 개발 프로세스의 끝에 수행되는 모든 시험"을 포함하며, "위험 관리 조치의 효과를 평가"하는 데도 사용됨을 확립합니다. 인적 요인 지침서는 중요한 작업을 가진 기기에 대한 인적 요인 검증을 위한 구체적인 권고사항 및 요건을 개괄하지만, 동일하거나 유사한 프로세스의 적용은 다른 위험의 적절한 통제를 입증하는 데도 도움이 될 수 있습니다. 부록 D(사용성 평가 고려사항)는 스폰서가 사용성 시험이 위험 통제를 뒷받침하는 데 도움이 될 수 있는 시기를 이해하는 데 도움이 되는 권고사항을 포함합니다. 부록은 또한 스폰서가 인적 요인 검증 외에 특정 유형의 사용성 시험을 개발하고 설명하는 데 도움이 되는 권고사항을 포함하거나, 인적 요인 검증이 필요하지 않은 경우를 포함합니다. 부록은 해당되는 경우 기기별 권고사항 및 인적 요인 지침서에 제공된 권고사항을 보완합니다.

성능 검증과 인적 요인 검증(또는 적절한 경우 사용성 평가)은 함께 FDA에 기기가 실제 환경에서 어떻게 사용되고 수행될 수 있는지를 이해하는 정보를 제공하는 데 도움이 됩니다. 성능 검증은 시험 조건 하에서 모델의 통계적 성능을 평가하기 위해 다양한 시험 및 모니터링 방법을 사용할 수 있으며, 인적 요인 검증 시험은 다양한 사용자가 맥락 내에서 기기를 사용할 가능성이 있는 방법을 이해하는 것을 포함합니다. 즉, 성능 검증은 기기 사양이 사용자 요구사항 및 의도된 용도에 부합하고 구현된 성능 요건이 일관되게 충족될 수 있다는 확인을 제공하기 위한 것이며, 인적 요인 검증 및 사용성 평가는 모든 의도된 사용자가 기기를 사용하는 동안 특정 목표를 달성할 수 있는지 그리고 사용자가 기기와 안전하고 효과적으로 일관되게 상호작용할 수 있는지를 구체적으로 다루기 위한 것입니다.

**소프트웨어 버전 이력**

시판 전 소프트웨어 지침서의 섹션 VI.I는 소프트웨어 버전 이력에 대한 정보를 포함하여 시판 신청서의 소프트웨어 설명의 일부로 포함되어야 하는 정보를 설명합니다. AI 기반 기기의 경우, 소프트웨어 버전 이력은 모델 버전 및 시험된 모델 버전과 출시된 버전 간의 모든 차이점에 대한 고려와 함께 차이점이 기기의 안전성 및 유효성에 미치는 잠재적 영향에 대한 평가를 포함합니다. 모든 검증 활동이 객관적이고 본 기관의 동의 없이 시험 데이터를 고려하여 모델이 기회주의적으로 조정되지 않았음(즉, 사후 조정)을 보장하기 위해 FDA가 어떤 버전의 모델이 시험되었는지를 이해하는 것이 중요합니다.

라벨에 UDI를 표시하도록 요구되는 기기의 경우 새로운 버전 및/또는 모델이 있을 때, 그리고 새로운 기기 포장에 대해 새로운 고유 기기 식별자(UDI)가 필요합니다.

## A. Performance Validation
*Why should it be included in a submission for an AI-enabled device:* The performance validation for an AI-enabled device provides objective evidence that the device performs predictably and reliably in the target population according to its intended use. The following recommendations are intended to supplement device-specific recommendations and recommendations provided in other FDA guidances where applicable, including “Design Considerations for Pivotal Clinical Investigations for Medical Devices,” “Statistical Guidance on Reporting Results from Studies Evaluating Diagnostic Tests,” and “Electronic Source Data in Clinical Investigations.”

As part of FDA’s evaluation of safety and effectiveness of the device, it is important for FDA to understand how the device performs overall in the intended use population, as well as in subgroups of interest. Acceptable performance in certain subgroups may mask lower performance in other subgroups when the evaluation is performed only for the total population. Poor performance in specific subgroups could make the device unsafe for use in those groups, which may impact the potential scope of the intended use population. Section VIII (Data Management) outlines why stratification and analyses of subgroups of interest is important to FDA’s evaluation of safety and effectiveness. An analysis of subgroup performance that supports safe and effective use across the expected intended use population also helps to ensure that devices can be used for all intended patients.

While differential performance across subgroups is not unique to AI-enabled devices, the reliance of models on relationships learned from large amounts of data, and the relative opacity of models to users make AI-enabled devices particularly susceptible to unexpected differences in performance. Even when the data used to develop the model is representative during training, models can be over-trained to recognize features of data that are unique to specific characteristics of the study dataset but may be spurious to the identification or treatment of the disease or condition. Spurious learnings could impact performance differentially across characteristics of interest such as disease subtype or patient demographics, especially when data from study participants from different groups tend to be collected at different sites. For example, models may erroneously use demographic information, or another variable correlated with demographic information, as a variable of interest in the model because patients of one demographic tended to be more likely to have a disease in the training dataset. This can be particularly difficult to identify with complex models in which the variables of interest may not be understandable to humans. For this reason, the accuracy and usefulness of an evaluation of an AI-enabled device also depends on the quality, diversity, and quantity of data used to test it.

Subgroup analysis provides the tools to evaluate the performance of the device in specific populations and can be helpful in identifying scenarios in which the device performs worse than overall performance. In addition, subgroup analyses are helpful in identifying potential limitations of the device and can contribute to effective labeling by providing end users with additional useful information.

Information on the uncertainty of device outputs is also important because it helps reviewers understand how to interpret device outputs. When not specified for a device type in statute, regulation, or guidance, repeatability and/or reproducibility studies can still help FDA understand and quantify the uncertainty associated with device outputs when provided.

Appendix C (Performance Validation Considerations) of this guidance includes additional recommendations for some common approaches to performance validation. In addition, FDA encourages sponsors to leverage the Q-Submission Program for obtaining FDA feedback on proposed approaches to AI-enabled device development and validation. In particular, early engagement could be helpful to discuss the use of RWD, the use of new and emerging study methods, or the validation of new technologies.

**Assessing the Performance of the Human-Device Team**

It is important for sponsors to consider the interactions between users and the device when identifying the appropriate methods for performance testing. In the document, “Good Machine Learning Practice: Guiding Principles,” Principle Seven discusses placing focus on “the performance of the Human-AI Team.” This principle explains that it is important to understand the performance of the “Human-AI team, rather than just the performance of the model in isolation” when a model has a “human in the loop.” The intended use and clinical workflow of AI-enabled devices span a continuum of decision-making roles from more autonomous systems to supportive (aid) tools that assist specific users, but rely on the human to interpret the AI outputs and ultimately make clinical decisions.

As the device moves along this spectrum, the nature of the clinical study or other studies (e.g., human factors validation testing) that would be appropriate to support performance evaluation of an AI-based medical device will vary according to the intended use of the model. For some devices, more emphasis may be placed on the model’s standalone performance (i.e., Did the actual output match the expected output?). For others, a focus may be assessing the performance of the human-AI team, beyond just the performance of the model in isolation (i.e., Did the intended user working with the new device perform the same or better than the operator alone or with another device?). Sponsors should consider that, in certain scenarios, both standalone and human-device team performance evaluations may support the overall performance evaluation of the AI-enabled device.

Performance evaluation of AI-based medical image analysis systems is an illustrative example of how the clinical study approaches may change as the intended use of the device moves along the spectrum of human-device interactions. Standalone assessments measure the model’s performance independently of human interaction, whereas reader studies compare the performance of the intended user both with and without the AI-enabled device (i.e., comparing the human vs. human-device team performance). Reader studies typically serve as the primary performance evaluation for AI-enabled devices that aid in clinical decision-making in medical imaging applications, because they allow sponsors to evaluate the tool’s clinical benefit in the hands of the intended user.

*What sponsors should include in a submission:* The validation testing should provide objective information to characterize the model performance with respect to the intended use. A validation assesses the model’s performance on independent datasets. Assessing the robustness of the model to anticipate reasonably foreseeable changes in input data and conditions of use should also be included, as appropriate, based on risk associated with these changes.

Validation methods differ depending on the intended use of a device. For example:
* Devices estimating defined measurements otherwise performed by accepted reference methods may need a precision study to adequately assess their repeatability and reproducibility.
* Devices monitoring time-series patient data and needing periodic re-calibrations may need a stability study and a change tracking study to assess their dynamic responses.
* Devices similar to survey instruments measuring less well-defined patient parameters may need additional evidence of construct validity (i.e., the extent to which a test measures what it is proposed to measure).
* Prognostic clinical decision support devices may need longitudinal data with survival analysis, calibration analysis, and/or discrimination analysis (e.g., risk stratification analysis), among other methods.

Depending on the specific AI-enabled device, this evidence could come from non-clinical bench or analytical studies, pre-clinical animal studies, clinical performance studies, clinical outcome studies, or some combination thereof.

Study Protocols
To support performance validation, sponsors should include information regarding all study protocols including statistical analysis plans. The statistical analysis plans should include study design and analysis details. Important aspects for these documents to cover include:
* Study design details, including:
  * A study design description (e.g., prospective, comparative study design with a sufficient statistical power to demonstrate the key clinical performance metric).
    * For a prospective study, procedures and methods that will be followed, a description of the operators involved in these procedures and methods, and any tools or equipment to be used.
    * For a retrospective study, plans on how to handle, prepare, process, and select archived data or material.
  * A description of the data recording mechanisms that will be used to record the version or state of the AI-enabled device used during the study for a given patient.
    * To ensure accuracy, automated collection of these data implemented in an electronic case report form (eCRF) or electronic data capture (EDC) system may be appropriate.
  * A description of the procedures and methods for blinding of the device outputs from the clinical reference standard determination process, masking of the clinical reference standard from the users/interpreters of the device outputs, and masking of the test data from the model developers and clinical team (to avoid opportunistic tweaking or bias in the study design), as applicable.
  * A description of the controls in place to address any risks posed to the patient or user by the AI-enabled device during the study.
  * If the protocol is altered during the execution of the clinical study, the applicant should explain the changes, and identify which changes are deemed minor and major, providing adequate justification for any repeated tests or tests with deviations from the pre-specified plans. The study protocol should be followed and all types of protocol deviations, including those deemed minor, should be minimized.
  * A full accounting of all enrolled subjects (with an accountability table).
  * A description of baseline distributions of the study population and other important factors in the dataset such as data acquisition equipment, device configurations, and disease status or conditions, and a justification of their representativeness. For more information on representativeness in AI-enabled medical devices, refer to Section VIII (Data Management) of this guidance.
* Statistical analysis plans, including:
  * A description of the primary endpoint(s) or outcome(s), which should be reflective of the primary objective of the study.
  * Pre-specified study success/failure criteria with respect to each of multiple primary endpoints (e.g., performance goals) that are clinically justified (e.g., supported by literature or prior investigations).
  * An explanation of the statistical hypotheses, such as null hypothesis and the alternative (working) hypothesis.
  * A sample size justification that ensures adequate study power.
  * An explanation of the statistical analysis of the primary endpoint(s), including information to justify the sample size calculation.
  * An explanation of the pre-specified, appropriate statistical approaches for handling multiplicity issues and controlling for overall Type I error rates.
  * A description of the appropriate statistical methodology.
  * A subgroup analysis plan.
    * The appropriate subgroups are informed by the intended use of the device, but should generally include patient sex, age, race, ethnicity, disease variables, clinical data site, data acquisition equipment (e.g., camera brand), and, if applicable, conditions for use (including skill level of the user when relevant), device configurations, and other relevant confounding factors that may impact the device performance.
    * When a specific performance claim is made with respect to a subgroup, the subgroup analysis should be statistically significant, including the inclusion of appropriately powered subgroups. However, when specific subgroup performance claims are not made, subgroup performance does not need to be statistically powered for each subgroup, but effort should be made to include reasonable numbers of patients for each subgroup so that any reported results have meaning and context.

Study Results
To support performance validation, sponsors should include information regarding the study results. Important aspects for these documents to cover include:
* An explanation of the pre-specified results for each test, including subgroup analyses.
* An explanation of the results with adequate subgroup analyses for relevant subgroups as described above.
  * If demographic information is not available for the study data, an explanation of the reasons it is not available, why performance evaluation can be supported without demographic subgroup analysis, and how risks associated with the lack of demographic subgroup analyses have been controlled.
* When feasible and appropriate, an evaluation of the device repeatability and reproducibility. The specifics of how these studies are conducted will depend on the specific device being evaluated, and may include phantom, simulated, contrived, or clinical data.

*Where sponsors should provide it in a submission:* Information on the non-clinical or clinical testing of the device should be included in the appropriate sections of the marketing submission. For example, clinical study findings should go in the clinical section of the marketing submission. Information on the software verification and software validation of the model should be included in the “Software Testing as part of Verification and Validation” in the Software Documentation section of the marketing submission, as described in the Premarket Software Guidance.

**A. 성능 검증**

*AI 기반 기기의 신청서에 왜 포함되어야 하는가:* AI 기반 기기의 성능 검증은 기기가 의도된 용도에 따라 목표 인구에서 예측 가능하고 신뢰할 수 있게 수행된다는 객관적 증거를 제공합니다. 다음 권고사항은 "의료기기에 대한 중추적 임상 조사의 설계 고려사항," "진단 시험을 평가하는 연구의 결과 보고에 대한 통계적 지침," "임상 조사에서의 전자 원본 데이터"를 포함하여 해당되는 경우 기기별 권고사항 및 다른 FDA 지침서에 제공된 권고사항을 보완하기 위한 것입니다.

기기의 안전성 및 유효성에 대한 FDA의 평가의 일부로, FDA가 의도된 사용 인구 전체에서 기기가 어떻게 수행되는지, 그리고 관심 하위 그룹에서 어떻게 수행되는지를 이해하는 것이 중요합니다. 특정 하위 그룹에서의 허용 가능한 성능은 평가가 전체 인구에 대해서만 수행될 때 다른 하위 그룹에서의 낮은 성능을 가릴 수 있습니다. 특정 하위 그룹에서의 낮은 성능은 해당 그룹에서 기기를 사용하기에 안전하지 않게 만들 수 있으며, 이는 의도된 사용 인구의 잠재적 범위에 영향을 미칠 수 있습니다. 섹션 VIII(데이터 관리)는 관심 하위 그룹의 계층화 및 분석이 FDA의 안전성 및 유효성 평가에 중요한 이유를 개괄합니다. 예상되는 의도된 사용 인구 전반에 걸쳐 안전하고 효과적인 사용을 뒷받침하는 하위 그룹 성능 분석은 또한 기기가 모든 의도된 환자에게 사용될 수 있도록 보장하는 데 도움이 됩니다.

하위 그룹 간의 차등적 성능은 AI 기반 기기에 고유한 것은 아니지만, 대량의 데이터로부터 학습된 관계에 대한 모델의 의존성과 사용자에 대한 모델의 상대적 불투명성은 AI 기반 기기를 예상치 못한 성능 차이에 특히 취약하게 만듭니다. 모델을 개발하는 데 사용된 데이터가 학습 중에 대표적이더라도, 모델은 연구 데이터셋의 특정 특성에 고유하지만 질병 또는 상태의 식별이나 치료에는 허위일 수 있는 데이터의 특징을 인식하도록 과도하게 학습될 수 있습니다. 허위 학습은 특히 다른 그룹의 연구 참여자로부터의 데이터가 다른 현장에서 수집되는 경향이 있는 경우 질병 아형 또는 환자 인구통계와 같은 관심 특성 전반에 걸쳐 성능에 차등적으로 영향을 미칠 수 있습니다. 예를 들어, 모델은 학습 데이터셋에서 특정 인구통계의 환자가 질병을 가질 가능성이 더 높은 경향이 있었기 때문에 인구통계학적 정보 또는 인구통계학적 정보와 상관관계가 있는 다른 변수를 모델의 관심 변수로 잘못 사용할 수 있습니다. 이는 관심 변수가 인간에게 이해될 수 없을 수 있는 복잡한 모델에서 식별하기가 특히 어려울 수 있습니다. 이러한 이유로, AI 기반 기기의 평가의 정확성 및 유용성도 이를 시험하는 데 사용되는 데이터의 품질, 다양성 및 양에 달려 있습니다.

하위 그룹 분석은 특정 인구에서 기기의 성능을 평가하는 도구를 제공하며, 기기가 전반적인 성능보다 더 낮게 수행되는 시나리오를 식별하는 데 도움이 될 수 있습니다. 또한 하위 그룹 분석은 기기의 잠재적 제한사항을 식별하는 데 도움이 되며, 최종 사용자에게 추가적인 유용한 정보를 제공함으로써 효과적인 라벨링에 기여할 수 있습니다.

기기 출력의 불확실성에 대한 정보도 검토자가 기기 출력을 해석하는 방법을 이해하는 데 도움이 되기 때문에 중요합니다. 법령, 규정 또는 지침서에서 기기 유형에 대해 명시되지 않은 경우에도, 반복성 및/또는 재현성 연구는 제공될 때 FDA가 기기 출력과 관련된 불확실성을 이해하고 정량화하는 데 도움이 될 수 있습니다.

본 지침서의 부록 C(성능 검증 고려사항)는 성능 검증에 대한 몇 가지 일반적인 접근법에 대한 추가 권고사항을 포함합니다. 또한, FDA는 스폰서가 AI 기반 기기 개발 및 검증에 대한 제안된 접근법에 대한 FDA 피드백을 얻기 위해 Q-제출 프로그램을 활용할 것을 권장합니다. 특히, RWD의 사용, 신규 및 신흥 연구 방법의 사용 또는 신기술의 검증을 논의하기 위한 조기 협의가 도움이 될 수 있습니다.

**인간-기기 팀의 성능 평가**

스폰서가 성능 시험을 위한 적절한 방법을 식별할 때 사용자와 기기 간의 상호작용을 고려하는 것이 중요합니다. "우수 기계학습 실무: 지도 원칙" 문서에서 원칙 7은 "인간-AI 팀의 성능"에 초점을 두는 것에 대해 논의합니다. 이 원칙은 모델이 "루프 내 인간"을 가질 때 "고립된 모델의 성능만이 아닌 인간-AI 팀의 성능"을 이해하는 것이 중요하다고 설명합니다. AI 기반 기기의 의도된 용도와 임상 워크플로는 더 자율적인 시스템에서부터 특정 사용자를 보조하지만 인간이 AI 출력을 해석하고 궁극적으로 임상 결정을 내리는 것에 의존하는 지원(보조) 도구에 이르기까지 의사결정 역할의 연속체에 걸쳐 있습니다.

기기가 이 스펙트럼을 따라 이동함에 따라, AI 기반 의료기기의 성능 평가를 뒷받침하는 데 적절한 임상 연구 또는 기타 연구(예: 인적 요인 검증 시험)의 성격은 모델의 의도된 용도에 따라 달라질 것입니다. 일부 기기의 경우, 모델의 독립 실행형 성능에 더 많은 중점을 둘 수 있습니다(즉, 실제 출력이 예상 출력과 일치했는가?). 다른 기기의 경우, 고립된 모델의 성능만이 아닌 인간-AI 팀의 성능을 평가하는 데 초점을 맞출 수 있습니다(즉, 새 기기와 함께 작업하는 의도된 사용자가 단독으로 또는 다른 기기와 함께 작업하는 작업자와 동일하거나 더 나은 성능을 보였는가?). 스폰서는 특정 시나리오에서 독립 실행형 및 인간-기기 팀 성능 평가 모두가 AI 기반 기기의 전반적인 성능 평가를 뒷받침할 수 있음을 고려해야 합니다.

AI 기반 의료 영상 분석 시스템의 성능 평가는 기기의 의도된 용도가 인간-기기 상호작용의 스펙트럼을 따라 이동함에 따라 임상 연구 접근법이 어떻게 변할 수 있는지를 보여주는 예시입니다. 독립 실행형 평가는 인간 상호작용과 독립적으로 모델의 성능을 측정하는 반면, 판독자 연구는 AI 기반 기기가 있을 때와 없을 때 의도된 사용자의 성능을 비교합니다(즉, 인간 대 인간-기기 팀 성능 비교). 판독자 연구는 스폰서가 의도된 사용자의 손에서 도구의 임상적 이점을 평가할 수 있게 하기 때문에 일반적으로 의료 영상 응용 분야에서 임상 의사결정을 돕는 AI 기반 기기에 대한 주요 성능 평가 역할을 합니다.

*스폰서가 신청서에 포함해야 할 내용:* 검증 시험은 의도된 용도와 관련하여 모델 성능을 특성화하기 위한 객관적 정보를 제공해야 합니다. 검증은 독립적인 데이터셋에서 모델의 성능을 평가합니다. 이러한 변화와 관련된 위험에 기반하여 적절한 경우, 입력 데이터 및 사용 조건에서 합리적으로 예측 가능한 변화를 예상하기 위한 모델의 견고성 평가도 포함되어야 합니다.

검증 방법은 기기의 의도된 용도에 따라 다릅니다. 예를 들어:
* 수용된 참조 방법에 의해 달리 수행되는 정의된 측정을 추정하는 기기는 반복성 및 재현성을 적절히 평가하기 위해 정밀도 연구가 필요할 수 있습니다.
* 시계열 환자 데이터를 모니터링하고 주기적인 재교정이 필요한 기기는 동적 반응을 평가하기 위해 안정성 연구 및 변화 추적 연구가 필요할 수 있습니다.
* 덜 명확하게 정의된 환자 매개변수를 측정하는 설문조사 도구와 유사한 기기는 구성 타당성(즉, 시험이 측정하고자 하는 것을 측정하는 정도)에 대한 추가 증거가 필요할 수 있습니다.
* 예후 임상 의사결정 지원 기기는 다른 방법들 중에서 생존 분석, 교정 분석 및/또는 판별 분석(예: 위험 계층화 분석)을 포함한 종단 데이터가 필요할 수 있습니다.

특정 AI 기반 기기에 따라, 이 증거는 비임상 벤치 또는 분석 연구, 전임상 동물 연구, 임상 성능 연구, 임상 결과 연구 또는 이들의 일부 조합으로부터 나올 수 있습니다.

**연구 프로토콜**

성능 검증을 뒷받침하기 위해, 스폰서는 통계 분석 계획을 포함한 모든 연구 프로토콜에 대한 정보를 포함해야 합니다. 통계 분석 계획은 연구 설계 및 분석 세부사항을 포함해야 합니다. 이러한 문서가 다루어야 할 중요한 측면은 다음과 같습니다:
* 다음을 포함한 연구 설계 세부사항:
  * 연구 설계 설명(예: 주요 임상 성능 지표를 입증하기에 충분한 통계적 검정력을 가진 전향적, 비교 연구 설계).
    * 전향적 연구의 경우, 따라야 할 절차 및 방법, 이러한 절차 및 방법에 관여하는 작업자에 대한 설명, 그리고 사용될 모든 도구 또는 장비.
    * 후향적 연구의 경우, 보관된 데이터 또는 자료를 처리, 준비, 처리 및 선택하는 방법에 대한 계획.
  * 특정 환자에 대해 연구 중에 사용된 AI 기반 기기의 버전 또는 상태를 기록하는 데 사용될 데이터 기록 메커니즘에 대한 설명.
    * 정확성을 보장하기 위해, 전자 증례 보고서 양식(eCRF) 또는 전자 데이터 캡처(EDC) 시스템에 구현된 이러한 데이터의 자동 수집이 적절할 수 있습니다.
  * 해당되는 경우, 임상 참조 표준 결정 프로세스로부터 기기 출력의 맹검 절차 및 방법, 기기 출력의 사용자/해석자로부터 임상 참조 표준의 마스킹, 그리고 모델 개발자 및 임상 팀으로부터 시험 데이터의 마스킹(기회주의적 조정 또는 연구 설계의 편향을 피하기 위해)에 대한 설명.
  * 연구 중 AI 기반 기기가 환자 또는 사용자에게 제기하는 모든 위험을 다루기 위해 마련된 통제에 대한 설명.
  * 임상 연구 실행 중에 프로토콜이 변경되는 경우, 신청자는 변경 사항을 설명하고, 어떤 변경 사항이 경미하고 주요한 것으로 간주되는지를 식별하며, 사전 명시된 계획으로부터의 반복 시험 또는 일탈이 있는 시험에 대한 적절한 정당화를 제공해야 합니다. 연구 프로토콜을 따라야 하며, 경미한 것으로 간주되는 것을 포함하여 모든 유형의 프로토콜 일탈이 최소화되어야 합니다.
  * 등록된 모든 대상자에 대한 완전한 설명(책임 표 포함).
  * 연구 인구의 기준선 분포 및 데이터 획득 장비, 기기 구성, 질병 상태 또는 조건과 같은 데이터셋의 기타 중요한 요인에 대한 설명과 그들의 대표성에 대한 정당화. AI 기반 의료기기의 대표성에 대한 자세한 정보는 본 지침서의 섹션 VIII(데이터 관리)를 참조하십시오.
* 다음을 포함한 통계 분석 계획:
  * 연구의 주요 목적을 반영해야 하는 주요 평가변수 또는 결과에 대한 설명.
  * 문헌 또는 이전 조사에 의해 뒷받침되는 등 임상적으로 정당화되는 여러 주요 평가변수(예: 성능 목표) 각각에 대한 사전 명시된 연구 성공/실패 기준.
  * 귀무가설 및 대립(작업) 가설과 같은 통계적 가설에 대한 설명.
  * 적절한 연구 검정력을 보장하는 샘플 크기 정당화.
  * 샘플 크기 계산을 정당화하는 정보를 포함한 주요 평가변수의 통계 분석에 대한 설명.
  * 다중성 문제를 처리하고 전반적인 제1종 오류율을 통제하기 위한 사전 명시된 적절한 통계적 접근법에 대한 설명.
  * 적절한 통계 방법론에 대한 설명.
  * 하위 그룹 분석 계획.
    * 적절한 하위 그룹은 기기의 의도된 용도에 의해 알려지지만, 일반적으로 환자 성별, 연령, 인종, 민족, 질병 변수, 임상 데이터 현장, 데이터 획득 장비(예: 카메라 브랜드), 해당되는 경우 사용 조건(관련이 있는 경우 사용자의 기술 수준 포함), 기기 구성 및 기기 성능에 영향을 미칠 수 있는 기타 관련 교란 요인을 포함해야 합니다.
    * 하위 그룹과 관련하여 특정 성능 주장이 이루어지는 경우, 하위 그룹 분석은 적절하게 검정력이 있는 하위 그룹의 포함을 포함하여 통계적으로 유의해야 합니다. 그러나 특정 하위 그룹 성능 주장이 이루어지지 않는 경우, 하위 그룹 성능은 각 하위 그룹에 대해 통계적으로 검정력이 있을 필요는 없지만, 보고된 결과가 의미와 맥락을 가질 수 있도록 각 하위 그룹에 대해 합리적인 수의 환자를 포함하기 위한 노력을 기울여야 합니다.

**연구 결과**

성능 검증을 뒷받침하기 위해, 스폰서는 연구 결과에 대한 정보를 포함해야 합니다. 이러한 문서가 다루어야 할 중요한 측면은 다음과 같습니다:
* 하위 그룹 분석을 포함하여 각 시험에 대한 사전 명시된 결과에 대한 설명.
* 위에 설명된 관련 하위 그룹에 대한 적절한 하위 그룹 분석을 포함한 결과에 대한 설명.
  * 연구 데이터에 대해 인구통계학적 정보를 이용할 수 없는 경우, 이용할 수 없는 이유, 인구통계학적 하위 그룹 분석 없이 성능 평가가 뒷받침될 수 있는 이유, 그리고 인구통계학적 하위 그룹 분석의 부족과 관련된 위험이 어떻게 통제되었는지에 대한 설명.
* 실행 가능하고 적절한 경우, 기기 반복성 및 재현성 평가. 이러한 연구가 수행되는 방식의 구체적인 사항은 평가되는 특정 기기에 따라 달라지며, 팬텀, 시뮬레이션, 고안된 또는 임상 데이터를 포함할 수 있습니다.

*스폰서가 신청서에서 제공해야 할 위치:* 기기의 비임상 또는 임상 시험에 대한 정보는 시판 신청서의 적절한 섹션에 포함되어야 합니다. 예를 들어, 임상 연구 결과는 시판 신청서의 임상 섹션에 포함되어야 합니다. 모델의 소프트웨어 검증 및 소프트웨어 밸리데이션에 대한 정보는 시판 전 소프트웨어 지침서에 설명된 대로 시판 신청서의 소프트웨어 문서 섹션의 "검증 및 밸리데이션의 일부로서의 소프트웨어 시험"에 포함되어야 합니다.

ADDITIONAL RESOURCES:
Appendix C (Performance Validation Considerations) includes recommendations to help develop and analyze a performance validation study and its data. Appendix D (Usability Evaluation Considerations) includes information to help sponsors evaluate usability risk controls for AI-enabled device submissions.

FDA encourages sponsors to use the Q-Submission Program for obtaining FDA feedback on proposed approaches for AI-enabled device development and validation. If real-world evidence is used, sponsors may also wish to refer to FDA guidance titled “Use of Real-World Evidence to Support Regulatory Decision-Making for Medical Devices.”

# XI. Device Performance Monitoring
*Why should it be included in a submission for an AI-enabled device:* The performance of AI-enabled devices deployed in a real-world environment (i.e., marketed AI-enabled devices following approval or clearance) may change or degrade over time, presenting a risk to patients. In general, as part of the quality system for a medical device, including an AI-enabled device, manufacturers should have a postmarket performance monitoring plan to help identify and respond to changes in performance in a postmarket setting. The inclusion of a performance monitoring plan in the marketing submission may help to reduce uncertainty and support FDA’s evaluation of risk controls.

As part of their ongoing management of AI-enabled devices, manufacturers should proactively monitor, identify, and address device performance changes, as well as changes to device inputs and the context in which the device is used that could lead to changes in device performance. In addition, sponsors must develop and implement plans for comprehensive risk analysis programs and documentation consistent with the Quality System Regulation (21 CFR Part 820) to manage risks related to undesirable changes in device performance for AI-enabled devices. These regulations include, but are not limited to, management responsibility (21 CFR 820.20), design validation (21 CFR 820.30(g)), design changes (21 CFR 820.30(i)), nonconforming product (21 CFR 820.90), and corrective and preventive action (21 CFR 820.100). Further, manufacturers must monitor device performance and report to FDA information about deaths, serious injuries, and malfunctions in accordance with 21 CFR Parts 803 and 806.

FDA generally does not assess quality system regulation compliance as part of its review of marketing submissions under section 510(k) of the FD&C Act. However, in some cases, it may be appropriate for FDA to review details from the sponsor’s quality system in the marketing submission to ensure adequate ongoing performance. Such a review may help support a determination of substantial equivalence.

Ongoing performance monitoring is important for AI-enabled devices because, as described above, models are highly dependent on the characteristics of data used to train them, and as such, their performance can be particularly sensitive to changes in data inputs. Changes in device performance may originate from many factors, such as changes in patient populations over time, disease patterns, or data drift from other changes. When performance changes do occur, users may be less likely to identify them in AI-enabled devices if, for example, the devices are part of a highly automated process with limited on-going human interaction, or if the output is prognostic such that different healthcare professionals may be involved in the use of the device and in confirmatory follow-up interactions with the patient. Because the performance of AI-enabled devices can change as aspects of the environments in which they are approved or cleared for use may change over time, it may not be possible to completely control risks with development and testing activities performed premarket (prior to device authorization and deployment).

FDA recognizes that the environments where medical devices are deployed cannot be completely controlled by the device manufacturer. Further, the presence of factors that may lead to changes in device performance may not always raise concerns about patient harm. Rather, as part of ongoing risk management, it is important for device manufacturers to consider the impact of these factors (e.g., data drift) on the safety and effectiveness of the device. Additional information about performance management processes may be helpful for FDA to determine whether risks have been adequately identified, addressed, and controlled.

*What sponsors should include in a submission:* Sponsors of AI-enabled devices that elect to employ proactive performance monitoring as a means of risk control and to provide reasonable assurance of the device’s safety and effectiveness should include information regarding their performance monitoring plans as part of the premarket submission. Sponsors are encouraged to obtain FDA feedback on the plan through the Q-Submission Program. For a 510(k) submission, FDA generally does not require such plans for devices, absent certain circumstances, for which a performance monitoring plan is not a special control for the particular device type (i.e., the applicable classification regulation). For a De Novo classification request, such a plan may be necessary to control risks posed by the particular device type and so FDA may establish a special control for the device type going forward. For a PMA, a performance monitoring plan may be a condition of approval. However, sponsors may opt to include information regarding the performance monitoring plan in any submission for an AI-enabled device.

Performance monitoring plans should identify and respond to, in a timely fashion, performance changes or conditions that may lead to performance change or degradation. A robust performance monitoring plan includes proactive efforts to capture device performance after deployment. Components of such a plan may include:
* A description of the data collection and analysis methods for:
  * Identifying, characterizing, and assessing changes in model performance, including assessing the results from performance monitoring on safety and effectiveness.
  * Monitoring potential causes of undesirable changes in performance, such as:
    * Changes in patient demographics or disease prevalence;
    * Shifts in input data;
    * Changes to input data due to corruption in the data pipeline (input data integrity), such as missing values, duplicate records, or data type mismatches; and
    * Changes in users’ behavior or in user demographics.
* A description of robust software lifecycle processes that include mechanisms for monitoring in the deployment environment.
* A plan for deploying updates, mitigations, and corrective actions that address changing performance in a timely manner.
  * FDA notes that some actions taken to address performance changes may not require a marketing submission or authorization (21 CFR 807.81(a)(3) and 21 CFR 814.39(a)) prior to being taken. Please refer to FDA guidances titled “Deciding When to Submit a 510(k) for a Change to an Existing Device” and “Deciding When to Submit a 510(k) for a Software Change to an Existing Device” to help assess whether a particular change may require a premarket submission to FDA. Sponsors may also wish to consider the use of a PCCP, as appropriate.
  * This plan does not replace applicable statutory or regulatory requirements, including the requirements to report to FDA information about certain adverse events, and corrections and removals, under 21 CFR Parts 803 and 806.
* A description of the procedures for communicating the results of performance monitoring and any mitigations to device users.

*Where sponsors should provide it in a submission:* When appropriate, a device performance monitoring plan should be included in the **“Risk Management File”** in the Software Documentation section of the marketing submission.

# XII. Cybersecurity
*Why should it be included in a submission for an AI-enabled device:* As with any digital or software component integrated into a medical device, AI can present cybersecurity risks. FDA’s general recommendations for designing and maintaining cybersecurity as well as relevant marketing submission documentation are provided in the guidance document titled *“Cybersecurity in Medical Devices: Quality System Considerations and Content of Premarket Submissions”* (hereafter referred to as the “2023 Premarket Cybersecurity Guidance”). The 2023 Premarket Cybersecurity Guidance identifies security objectives that may be relevant for medical devices, including AI-enabled devices: authenticity, which includes integrity; authorization; availability; confidentiality; and secure and timely updatability and patchability.

For AI-enabled devices that meet the definition of a “cyber device” under section 524B(c) of the FD&C Act, the recommendations in this section of the guidance are intended to help manufacturers meet their obligations under section 524B of the FD&C Act. Examples of AI risks which can be impacted by cybersecurity threats include, but are not limited to:
* *Data Poisoning:* Cyber threats could lead to data poisoning by deliberately injecting inauthentic or maliciously modified data, risking outcomes in areas like medical diagnosis.
* *Model Inversion/Stealing:* Cyber threats could intentionally use forged or altered data to infer details from or replicate models. These pose risks to continued model performance as well as intellectual property and privacy breaches.
* *Model Evasion:* Cyber attackers could intentionally craft or modify input samples to deceive models, leading them to incorrect classifications. These pose risks to the reliability and integrity of model predictions, potentially undermining trust in AI-enabled devices and exposing them to malicious exploitation.
* *Data Leakage:* Cyber threats could exploit vulnerabilities to access sensitive training or inference data in models.
* *Overfitting:* Cyber threats could deliberately “overfit” a model, exposing the AI components to adversarial attacks as these components struggle to adapt effectively to modified patient data.
* *Model Bias:* Cyber threats could lead to manipulation of training data to introduce or accentuate biases. They could exploit known biases using adversarial examples, embed backdoors during training to later trigger biased behaviors, or leverage pre-trained models with inherent biases, amplifying them with skewed fine-tuning data.
* *Performance Drift:* Cyber threats could lead to model performance drift by changing the underlying data distribution, which degrades model performance. Cyber threats could slightly shift the input data over time or exploit vulnerabilities in dynamic environments, causing the model to make inaccurate predictions or become more susceptible to adversarial attacks.

*What sponsors should include in a submission:* Consistent with the submission documentation recommended in the 2023 Premarket Cybersecurity Guidance regarding the cybersecurity controls and security risk management relevant to the AI components or features, sponsors should include the following types of information:
* Any additional elements in the cybersecurity risk management report, threat modeling, cybersecurity risk assessment, labeling, and other deliverables, where there are unique considerations related to AI cybersecurity.
* An explanation regarding how the cybersecurity testing is appropriate to address the risks associated with the model, including, at minimum, the following tests:
  * Malformed input (fuzz) testing; and
  * Penetration testing.
* A Security Use Case View(s) that covers the AI-enabled considerations for the device.
* A description of controls implemented to address data vulnerability and preventing data leakage, including:
  * Access controls;
  * Any data encryption; and
  * Anonymization or de-identification of sensitive data.

Sponsors should refer to the control recommendations in Appendix 1 of the 2023 Premarket Cybersecurity Guidance for how they may wish to address the specific risks above. Example approaches to controlling cybersecurity risks related to AI-enabled devices include:
* For data poisoning attacks, consider:
  * Validating, authenticating, and cleansing data.
  * Employing anomaly detection and data integrity checks (e.g., cryptographic hashes).
  * Applying adversarial training, which is a method used to improve the robustness and security of models.
* For cyber threats using forged data to introduce overfitting, model bias, etc., consider:
  * Adopting differential privacy, which is a technique to protect the privacy of individual data points in a dataset. When utilizing differential privacy, sponsors should be cognizant of potential trade-offs between privacy and factors such as model accuracy, utility, and efficiency, and provide information on how the trade-offs are addressed.
  * Engaging in secure multi-party computation (MPC), which is a technique that can allow multiple parties to collaboratively train a model without revealing their local datasets to each other.
  * Employing data authentication and integrity protections.
  * Introducing watermarking, which involves embedding hidden watermarks into AI models to prove ownership.
  * Applying continuous model performance monitoring.
* For model evasion, consider adversarial training to enhance model robustness and implement strict input verification checks to ensure data conforms to expected patterns. When deploying adversarial training techniques, sponsors should be cognizant of the trade-offs that may arise between enhanced robustness to attacks and the potential negative impact on model performance (e.g., accuracy), and provide information on how the trade-offs are managed.

*Where sponsors should provide it in a submission:* The cybersecurity information should be included in the **“Cybersecurity/Interoperability”** section of the marketing submission, as described in the 2023 Premarket Cybersecurity Guidance.

ADDITIONAL RESOURCES:
Sponsors may also refer to other FDA guidance documents for additional recommendations relevant to cybersecurity:

* *Cybersecurity in Medical Devices: Quality System Considerations and Content of Premarket Submissions*
* *Postmarket Management of Cybersecurity in Medical Devices*
* *Cybersecurity for Networked Medical Devices Containing Off-the-Shelf (OTS) Software*
* *Off-The-Shelf Software Use in Medical Devices*

# XIII. Public Submission Summary
*Why should it be included in a submission for an AI-enabled device:* Transparency is a key component of premarket authorization and is important to patient care. This is especially important for AI-enabled devices, which are heavily data-driven and incorporate algorithms exhibiting a degree of opacity. In public workshops and comments, including the October 14, 2021 virtual public workshop on the transparency of AI-enabled devices titled *“Transparency of Artificial Intelligence/Machine Learning-enabled Medical Devices,”* patients noted concerns with the use of AI in their care. The public has consistently called for additional information about how FDA makes authorization decisions about AI-enabled devices, as well as more information about the design and validation of these devices. The public submission summary should include specific information describing the characteristics of these devices to support transparency, which can contribute to public health by increasing understanding of AI-enabled devices and developing public trust.

Public submission summaries are required and available on the FDA website for most marketing authorization decisions. These summaries describe the device and the information supporting regulatory decision-making. Where a public summary is required, details about the AI-enabled device must be included in sufficient detail in the public-facing documents to support transparency to users of FDA’s determination of substantial equivalence or reasonable assurance of safety and effectiveness for the device. To ensure public access to important information on authorized AI-enabled devices, this section describes the types of information sponsors should include in the public submission summary as well as a possible format for such information.

For AI-enabled devices submitted through the PMA, HDE, De Novo, BLA, or 510(k) pathways, FDA recommends that the information discussed in this section be included in the relevant public submission summary, or the 510(k) Summary (in the section prepared in compliance with 21 CFR 807.92(a)(4)), as applicable. Sponsors should provide the recommended information excluding any patient identifiers, trade secrets, and confidential commercial information. For sponsors submitting a 510(k) Statement (21 CFR 807.93), FDA recommends providing the same information in the submission excluding any patient identifiers, trade secrets, and confidential commercial information.

While not required, the use of a model card may be one way to communicate information about AI-enabled devices because they are a means to consistently summarize the key aspects of AI-enabled devices and can be used to concisely describe their characteristics, performance, and limitations. Appendix E (*Example Model Card*) provides recommendations for the contents and formatting of a model card. Research has demonstrated that the use of a model card can increase user trust and understanding. The use of a model card as part of a public submission summary specifically is one way to support clear and consistent communication about an AI-enabled device to the interested parties in the public as well as to users, such as patients, clinicians, regulators, and researchers. The use of the model card can address the challenges associated with determining the best approach to communicate important information about the AI-enabled device.

*What sponsors should include in a submission:* Sponsors must comply with the submission regulations for their particular submission. In addition, sponsors should consider FDA recommendations for the relevant marketing submission type. Sponsors should also provide the following types of information excluding any patient identifiers, trade secrets, and confidential commercial information:
* A statement that AI is used in the device.
* An explanation of how AI is used as part of the device’s intended use. For devices with multiple functions, this explanation may include how AI-DSFs interact with each other as well as how they interact with non-AI DSFs.
* A description of the class of model (e.g., convolutional neural network, recurrent neural network, support vector machine, transformers) and limitations of the model within the device description.
* A description of the development and validation datasets (size, source of data), including information about the demographic characteristics in the training and validation data, along with information about the demographic characteristics in the population(s) of intended use. The description should also compare the training dataset to the validation dataset and model data inputs expected in the intended use. The comparison should describe how independence of test data from training data was ensured.
* A description of the statistical confidence level of predictions, including any other descriptions or metrics that describe statistical confidence and uncertainty, as applicable.
* A description of how the model will be updated and maintained over time, if applicable.

Sponsors should consider using a model card to organize information. Appendix E (*Example Model Card*) includes recommendations on the elements that may be included within a model card. While the example model card includes recommended elements and format for a model card, sponsors may include additional information and/or follow a different format. In the absence of the model card structure, sponsors should still consider including the information a model card contains.

*Where sponsors should provide it in a submission:* The public submission summary should be included in the **“Administrative Documentation”** section of the marketing submission.

ADDITIONAL RESOURCES:
Appendix E (*Example Model Card*) of this guidance provides one example of the format of a model card.
Appendix F (*Example 510(k) Summary with Model Card*) of this guidance provides an example of a public submission summary for a product, including a completed model card.

# Appendix A: Table of Recommended Documentation
Sections V–XIII of this guidance provide recommendations regarding the documentation that may be included within a marketing submission for AI-enabled devices. The table below summarizes recommended locations within the marketing submission to provide discussed documentation. One way this documentation may be submitted is through the eSTAR Program. Specifically, eSTAR is an interactive PDF form that guides applicants through the process of preparing a comprehensive medical device submission. eSTAR is free and is required for all 510(k) submissions, unless exempted.

| **Guidance Section and Recommended Information** | **Recommended Section in Sponsor’s Marketing Submission** |
| --- | --- |
| Section V — Device Description | Device Description  |
| Section VI.A — User Interface | Software Description |
| Section VI.B — Labeling | Labeling |
| Section VII — Risk Assessment | Risk Management File of Software Documentation |
| Section VIII — Data Management | Data for development: Software Description of Software Documentation<br>Data for testing: Performance Testing |
| Section IX — Model Description and Development | Software Description  |
| Section X.A — Performance Validation | Clinical and non-clinical testing: Performance Testing<br>Software verification and software validation: Software testing as part of verification and validation of Software Documentation |
| Section XI — Device Performance Monitoring  | Risk Management File of Software Documentation |
| Section XII — Cybersecurity | Cybersecurity |
| Section XIII — Public Submission Summary | Administration Information |

# Appendix B: Transparency Design Considerations
This appendix contains recommendations for developing a transparent device centered around users. These recommendations are intended to help sponsors develop safe and effective medical devices and high-quality marketing submissions. While sponsors may identify alternate approaches that support FDA’s evaluation of safety and effectiveness, they should integrate transparency considerations starting at the design phase of the TPLC to ensure the availability of information to support the marketing submission. It can be difficult to integrate transparency into a device in later stages of the TPLC when changes to the device might require additional testing. In this guidance, transparency refers to clearly communicating the contextually relevant performance and design information of a device to the appropriate stakeholders in a manner that they can understand and act on. Transparency involves ensuring that important information is both accessible and functionally comprehensible and is connected both to the sharing of information, and to the usability of a device. As such, a user-centered approach to transparency design helps support the safe and effective use of AI-enabled devices. Including appropriate transparency information has also been shown to more than double willingness to use a device.

Transparency by Design Across the TPLC
Sponsors should take a holistic approach to identifying relevant contextual factors for device use and how those factors impact device performance when determining what information should be communicated. Sponsors should consider transparency throughout the full continuum of implementation through use, maintenance, and decommission of the AI-enabled device, and should design the device with transparency in mind from the beginning.

The user interface is another area where transparency principles should be used, when appropriate. The information in other elements of the user interface can complement the printed labeling (e.g., packaging and user manuals) to support the user’s understanding of how to use the device by providing timely and contextually relevant information throughout the use process, as described in Section VI (User Interface and Labeling). Examples of points of interaction include alerts generated by a device and displayed on the device or pushed to another product, components of associated hardware, and display screens. Effective transparency planning identifies the necessary information for the intended user(s) and context of use, as well as the optimal mediums, timing, and strategies for successful communication of the necessary information.

Generally, the transparency design process should begin with a holistic approach to obtain an understanding of the context in which a product is used, followed by identifying user tasks, and possible risks associated with communication of information during those tasks. This can be accomplished by determining how and when information is needed, integrating contextually appropriate risk controls into the design of the product, and finally validating that the intended users receive and can functionally understand the key information in relevant use contexts. This process may be iterative and may not flow linearly.

Transparency is contextually dependent, so appropriate information will vary across the range of AI-enabled devices and depend upon their benefit/risk profiles and the needs of intended users. The considerations in this appendix are not exhaustive and are intended to help sponsors identify information about the context in which the device will be used and the needs of the users for the purpose of developing a consistent approach to understanding the transparency needs for their AI-enabled device. It is also important to note that while transparency can help to address certain device risks, particularly those related to misunderstanding or misusing information output by a device, providing transparency about the existence of a significant clinical risk, including a significant risk related to performance in subpopulations of intended users, alone may not be an adequate risk control.

The Right Information at the Right Time
Consider what information the users might need, when they might need it to facilitate decision-making, and the potential risks if the users do not have the appropriate information at the right time, at all, or if it is misunderstood. It is important to focus on the tasks that each user has to perform, and what the user needs to know to perform them in concurrence with the intended use. To identify what information needs to be gained and is critical for users, consider the intended use comprehensively with questions, such as:
* Who needs the information and what is the most effective method of communication?
* When does the user need to understand information to support safe and effective use?
* What is the context of use? Examples of questions about the context of use include:
  * Where will the device be used and what are the conditions in that space?
  * What else might users be doing at the same time?
  * How timely is the application of the information?
  * In what settings will the device output be viewed?
  * Will users who interpret and apply the output be the same as those who operate the device?

Information should be communicated at the time that it is needed. Some examples of elements of the user interface that could be used to communicate transparency information include:
* Packaging
* Labeling
* User Training
* Controls
* Display elements
* Outputs/reports
* Alarms/warnings
* Logic of operation of each device component and of the user interface system as a whole

Understanding User Characteristics and Needs
The ability of a user to operate an AI-enabled device depends on their personal characteristics and the device use environment. The environments in which AI-enabled devices are used may also influence a user interface design. As part of design inputs, consider the needs of users in the context of use. Understanding users and their needs and limitations should occur early in the development process for the AI-enabled device and may be repeated as the design process continues. Users may include, for example:
* Patients
* Purchasers
* Administrators
* Healthcare Professionals
* Caregivers
* Maintenance Technicians

It is important to consider the characteristics of each user that may impact the user needs, including appropriate content and format for communication. Considerations may include:
* The user’s functional capabilities, including cognitive, physical and sensory capabilities
* The experience and knowledge levels of the users, including their educational backgrounds
* The frequency at which the user will interact with the device
* The level of training users are expected to receive
* The similarities and differences of the new information as compared to information the users have utilized in the past

Communication Style and Format
It is also important to consider the format used for communication. The format should be clear and appropriate for each user at each user task. Factors may include:
* The reading level of the user
* The location of information
* Design elements such as:
  * Hierarchy
  * Visualizations
  * Dynamic labeling

The selection of the timing, mode, and format of communication should be incorporated early to allow for iterative design.

Explainability Information and Visualizations
It is also important to consider when additional information may detract from understanding, rather than add to it. For example, explainability tools or visualizations can be valuable in increasing model transparency and a user’s confidence in a model’s output and could be developed as part of the user interface. However, if not well designed and validated for the target user group, explainability tools or visualizations could also significantly mislead users. Therefore, sponsors should develop and validate explainability metrics and visualizations through appropriate testing.

# Appendix C: Performance Validation Considerations
This appendix contains recommendations for some aspects of clinical performance validation in AI-enabled devices, which are intended to help sponsors develop safe and effective medical devices. While sponsors may identify alternate approaches that support FDA’s evaluation of safety and effectiveness, they should rigorously test the device to establish the device’s performance, and integrate that planning early in the design and development process to ensure the collection of appropriate data to support the device’s intended use. It can be difficult, for example, to gather additional supportive data after the completion of the pivotal clinical study. Sponsors should also follow the recommendations found in other FDA guidances regarding specific clinical study considerations. For example, additional information on evaluating and reporting results for AI-enabled devices can be found in the FDA guidances “Design Considerations for Pivotal Clinical Investigations for Medical Devices,” “Statistical Guidance on Reporting Results from Studies Evaluating Diagnostic Tests,” and “Electronic Source Data in Clinical Investigations.” These recommendations may not apply to all device types.

Pre-specification of Study Protocols and Statistical Analysis Plan
Post-hoc analysis may bias the performance assessment. Therefore, to accurately evaluate the performance of the device, study protocols and statistical analysis plans should be pre-specified. Regardless of whether data are collected prospectively or retrospectively, study design elements (such as sample size justification, and plans on how to handle, prepare, process, and select archived data or material) should be specified prior to beginning the validation study.

Study Reports
All performance and usability assessments should be objective, and the model should not be tweaked opportunistically in light of the test data results (i.e., no post-hoc adjustment). In general, proceeding to execute the study protocol only after a sound validation plan (study protocol and statistical analysis plan) is documented and finalized helps avoid these post-hoc adjustments. Execution of the plan includes collecting the required data, conducting the pre-specified analysis, and reporting the study results. Validation study reports should specify the associated protocol version and adequate justifications should be provided for any repeated tests or tests with deviations from the pre-specified plans.

Masking Protocol
For diagnostic devices, a masking protocol in the clinical study ensures that the user of the test is “blinded/masked” to the clinical reference standard result while the provider of the clinical reference standard result is “blinded/masked” to the test result. The masking protocol also ensures that model developers and the clinical team are completely masked from the test data during the model development process.

For therapeutic devices, masking is sometimes implemented through a randomized-controlled study with two arms (e.g., placebo/sham device arm and subject device arm), when ethically appropriate such as with non-invasive diagnostic devices. This ensures patients and care providers are blinded to the actual treatment assignment. The placebo arm may not have any measurement but only serve as a blinding tool (e.g., so that caretakers will not provide differentiated care in different arms). When such a two-arms study design is not feasible, there may be potential bias in the performance assessment due to placebo effects.

Model Precision: Repeatability and Reproducibility
An AI-enabled device may often be intended to measure physiological signals when the device is placed on a particular anatomical location. It is important to know how robust the device output is due to potential variations in the measurement system (e.g., whether repeated tests by users will generate significantly different device output due to operator difference and signal variation). A precision study gauges the variability of a device output when making repeated measurements on the same patient, either with the same operator and device (repeatability), or with different operators and devices (reproducibility). More generally, repeatability is the closeness of agreement of repeated measurements taken under the same conditions; and reproducibility is the closeness of agreement of repeated measurements taken under different, pre-specified conditions.

It is important to note that not every diagnostic device needs a precision study, due to clinical and feasibility considerations. For example, there is a feasibility concern when a device may be too harmful on the patients with repeated use (e.g., for radiation or invasive devices). Another example is a monitoring device that tracks a patient’s changing physiological status (e.g., hemodynamic parameters) in real-time, where repeated observations of the same truth are not possible.

Key statistics to summarize the repeatability and reproducibility, based on a variance component analysis using a model’s continuous metric (e.g., a probability score), are the subject-level standard deviation (SD) and the percent coefficient of variation (%CV). Improving the model to reduce SD or %CV may provide a low-cost way to improve product quality and the success likelihood of a future pivotal clinical study. This is, in part, because the clinical reference standard (i.e., the best available method for establishing the presence or absence of the target condition) is not measured in a precision study. Depending on the product, additional factors may be considered in the precision study. In image classification tasks, a model may be sensitive to data perturbation (e.g., image translation/rotation, light intensity change, random noise). This phenomenon could be abundant for an AI-enabled medical device software running on a generic smartphone using its camera to capture measurement data (e.g., skin lesion analyzers).

Study Endpoints and Acceptance Criteria
Primary endpoints are usually assessed using pre-specified acceptance criteria within a statistical hypothesis testing framework. This approach necessitates an adequate sample size to ensure sufficient study power (i.e., acceptable type II error rate). Secondary and exploratory endpoints may also be used to inform the effectiveness of the device and are part of the totality of evidence that inform regulatory decisions. The evaluations of primary endpoints are typically based on their 95% two-sided confidence intervals (so that type I error can be protected at 5% for two-sided testing; and at 2.5% for one-sided testing). The validation of all outputs should be addressed, appropriately by type (e.g., continuous, categorical, risk scores).

An AI-enabled medical device can produce a variety of outputs, such as diagnostic/prognostic predictions, or treatment triaging/priority ranking/selection/planning. The validation of these outputs may involve an analytic study (e.g., precision, bench, simulation study), literature review, a diagnostic performance study, a reader study (e.g., multi-reader multi-case imaging study), or a clinical outcome study (e.g., based on a study or randomized-controlled trial design).

When specifically considering an AI-enabled diagnostic device, the key performance assessment is its diagnostic accuracy, which is evaluated in a pivotal diagnostic performance study. Due to sampling variation, the uncertainties of the accuracy estimates are typically quantified, usually in the form of 95% two-sided confidence intervals. The study acceptance criteria can be based on statistical inferences using hypothesis testing methods (e.g., comparing a lower/upper confidence limit to a pre-specified performance goal). Note that inferences based on point estimates ignores the statistical uncertainty of the estimates and is not generally acceptable in the primary analysis. It is always compared to a comparator that can be tested and evaluated on the same patient/data as the device. This comparator can be the clinician, another device that is adequately validated for the same intended use, or standard of care. The evaluation on the same patient/data is key to mitigate differences in the task difficulty levels and disease spectrum due to sampling variation.

Depending on the nature of the diagnostic output (i.e., binary, polychotomous, or continuous), different evaluation metrics are possible.
* For binary diagnostic output, evaluation may be based on sensitivity, specificity, positive/negative predictive values (PPV/NPV), and positive/negative diagnostic likelihood ratios (LR+/LR-).
* For risk stratification output that classifies a patient into one of multiple risk groups and that may often be found in prognostic models, some evaluation metrics are pre/post-test risks and likelihood ratios.
* For an output that evaluates a patient’s disease risk with a continuous score, some risk evaluation methods are calibration plot, receiver operating characteristic (ROC) curve, and decision curve analysis. In the context of biomarker evaluation, the predictiveness curve analysis may be used.
* For continuous score, agreement study methods using MAE (mean absolute error), RMSE (root mean squared error), scatter plot, Deming regression, and Bland-Altman analysis are often used.

When the test data consists of multiple observations per patient, the within-patient correlations should be accounted for in the calculation of confidence intervals. Failure to account for the repeated measurements appropriately in the statistical analysis may lead to biased estimates and incorrect narrow confidence intervals, which may hinder objective evaluation of the device performance. Statistical techniques that account for patient-level repeated measurements include the bootstrap resampling method and analytic methods for clustered data.

Validation of AI-based Pre-processing Steps
Some models may include a quality control algorithm that discards “low” quality cases from further processing. However, such low-quality cases may actually be truly hard/difficult ones – an example of missing not at random (MNAR), which may lead to skewed diagnostic performance in accuracy metrics (e.g., sensitivity and specificity) but also may be biased (e.g., in the sense that more patients than warranted may not get any results due to declared low-quality events). An analysis of cases deemed low-quality should be conducted to verify that the quality control algorithm does not discard challenging cases.

For example, compare two hypothetical AI-enabled diagnostic devices (A and B) using cellphone cameras for certain skin disease detection. Assume they use the same diagnostic models, except that A has a more aggressive quality control (QC) algorithm than B in declaring low-quality cases. After excluding those cases that fail the QC algorithm, it may not be surprising to observe that A would have a better diagnostic performance than B, because many low-quality images dropped by A but not by B may in fact be good quality but difficult cases which are not included in the performance assessment for A.

Thus, a good practice is to examine the influence of a QC algorithm by checking the proportion of low-quality dropouts and assessing the results of a sensitivity analysis assuming a worst-case scenario (i.e., assuming the QC failure cases are all difficult ones that the model fails to classify successfully).

# Appendix D: Usability Evaluation Considerations
As described in this guidance Section X Validation, sponsors should conduct human factors evaluations as part of design controls (21 CFR 820.30) for every medical device requiring a premarket submission. The Human Factors Guidance outlines analytical approaches to this evaluation as well as specific requirements for human factors validation for devices when one or more critical tasks has been identified. Human factors engineering processes typically begin with preliminary analysis and evaluation of all tasks that identifies critical tasks which, if performed incorrectly or not performed at all, could cause serious harm. Sponsors should perform this analysis to identify whether a device has a critical task. If a critical task is identified, sponsors should refer to the Human Factors Guidance and perform human factors validation. While sponsors of devices that do not have a critical task may not need to submit a human factors validation testing report, they may choose to use the process outlined in the Human Factors Guidance, or another approach of their choosing to evaluate usability, to test their device design, and support the efficacy of risk controls. This appendix is focused on the evaluation of usability to support risk controls when a human factors validation testing report is not required, where usability addresses whether all intended users can achieve specific goals while using the device and whether users will be able to consistently interact with the device safely and effectively. This includes, but is not limited to, whether users can consistently and correctly receive, understand, interpret, and apply information related to the AI-enabled device.

While FDA’s Human Factors Guidance outlines recommended analytic approaches for evaluating usability, sponsors may choose to utilize alternative approaches for the evaluation of user tasks outside of the scope of that guidance. If this testing is used to support a risk control (as described in Section VII (Risk Assessment)), sponsors should include a description of the pre-specified testing protocols and analysis plans, and a justification for the appropriateness of the assessment method.

For AI-enabled devices, it may be specifically important for sponsors to identify and evaluate risk controls related to user tasks regarding the interpretation and use of information and interactions with novel user interfaces. The application of this information is a particular challenge for users of AI-enabled devices because models developed through AI techniques vary in explainability and interpretability. For example, some models can be explained using a simple decision tree which is generally easy for a user to follow and understand the basis of a model’s recommendations.
Other models use complex, deep neural networks, where it may not be feasible to explain in a way that allows a user to completely understand the basis of recommendations, even with comprehensive information on its inputs, nodes, and weights. This means that users may not be able to easily and independently verify whether the recommendations and decisions made by an AI-enabled device are appropriate. As such, AI-enabled devices can be prone to errors of device use and information interpretation. The challenges with interpretability and explainability increase when the intended user has limited training in interpreting the output of models, when the intended use is in situations that require urgent action, when the model has no evident biological mechanism of action, and
when the model changes through iterative updates. These errors can cause harm (injury or damage to health, including the effects of delayed or incorrect clinical intervention, or damage to property or the environment) and impact the safe and effective use of the device.

When sponsors choose to include an evaluation of usability to support the control of risks related to information, as described in Section VII (Risk Assessment), the evaluation should be appropriate to demonstrate that the user can both find and apply the information. In such cases, an impact assessment may be used to determine which user tasks could have an adverse or positive effect on knowing, understanding, and applying information for the device. As appropriate for the AI device, this assessment may include, for example, evaluation of the training program intended for risk control. For more complex AI devices with several sequential risk controls, use of the device in a clinical feasibility study that includes comprehensive assessment of how the user interpreted the AI outputs and what actions were taken. Ultimately, it is important to evaluate whether the user can operate and interpret the device, including demonstrating that users can understand and apply important information about the use of the device and its output in the actual context of clinical decision-making.

Sponsors may wish to draw on the general structure outlined in Section 6.3.1 (Task Analysis) of the Human Factors Guidance, which provides an example of an analysis technique to systematically break down device use into discrete user tasks. However, it is important to understand that while the Human Factors Guidance focuses on “serious harm,” sponsors may need to provide documentation evaluating and addressing any potential risk associated with misuse, including misinterpretation, to ensure that the device is safe and effective for its intended use.

Appendix B (Transparency Design Considerations) of this guidance also outlines recommendations to user-centered transparency, which may help with the identification of user tasks and risks related to usability and information interpretation, as well as help sponsors develop design approaches to control these risks.

# Appendix E: Example Model Card
A model card is a popular format for communicating information about a device that may align with the kind of information that FDA may require, for example in the publicly available 510(k) summaries and labeling. The model card format and content discussed below is intended to serve as an example of possible formatting a sponsor could use to communicate information about the model and the AI-enabled device in the public submission summary and other locations where this information may be shared by the sponsor. It is important to note that FDA does not require the inclusion of a model card or a specific model card format, and this example should not be considered a template. The example model card below has been designed based on user-centered research to present data in an order and format that is useful and easy to understand for non-technical audiences and is provided to sponsors to facilitate the inclusion of a model card.

In general, model cards can be adapted to the specific needs and context of each AI-enabled device. However, for the public summary, sponsors are encouraged to follow the general principles for creating model cards outlined in this guidance. Some elements may not be available for all devices.

When model cards are provided in a digital format, research has demonstrated that a dynamic approach to formatting that allows users to expand sections individually as needed makes the information easier to digest. While the public submission summary is provided as a PDF document and the format is static, sponsors should consider the use of dynamic labeling when possible.

**DEVICE NAME – Model Card**

**Device Information:**
* Name of the Device
* Version of the Device
* Date when the Device was created (or last updated)
* Model Architecture

**Regulatory Status (for model cards used outside of the public submission summary):**
* Authorization status
* File number

**Description:**
* Intended users (e.g., healthcare professionals, caregivers, patients)
* Intended use – The general purpose of the device or its function, including the indications for use
* Indications for use – Describes the disease or condition the device will diagnose, treat, prevent, cure, or mitigate, including a description of the target patient population for which the device is intended and the intended use environment (e.g., intensive care unit, step-down unit, home)
* Instructions for Use – Directions and recommendations for optimal use of the model
* Clinical benefits (e.g., analyze personalized patient information to improve diagnosis, treatment assignment, monitoring, or prevention of a medical condition, risk assessment) and limitations, including whether the device is intended to be used by, or under the supervision of, a healthcare provider
* Clinical workflow phase (e.g., patient pre-registration, digitization of forms or clinical scales, patients’ triage, telehealth & virtual rounds, clinical decision support systems, workflow optimization, evidence-based methods to optimize medical interventions, feedback from users)
* Inputs and outputs of the model and contribution to healthcare decisions or actions
* Degree of automation compared to the current standard of care, including whether the device supports or automates decision making

**Performance and Limitations:**
* Accuracy (e.g., sensitivity, specificity, positive/negative predictive values, and their 95% two-sided confidence intervals)
* Known biases or failure modes
* Precision (reproducibility) associated with the provided outputs
* Known gaps in the data characterization, such as patient populations that are not well represented in development (e.g., training) or testing datasets, and therefore may be at risk of bias
* Limitations in the model development or performance evaluation
* Known circumstances where the device input will not align with the data used in development and validation
* Evidence (e.g., clinical trial number or for published results of a supporting study, the unique reference ID such as Digital Object Identifier, or PubMed Identifier information)
  * Data Characterization for data used to test the device:
    * Data sources (e.g., clinical trials, public or proprietary databases) including details on any devices used to collect data
    * Data types used (e.g., structured numerical data, structured categorical data, unstructured text, images, time-series data, or a combination)
    * Relevant details including the sample size, effect size, data quality, reference standard, diversity, and representativeness
* Methods used to establish and ensure that the model meets the intended use and user requirements (e.g., human factors validation/usability evaluation, user acceptance testing, clinical validation, identification of pre-trained models, other)

**Risk Management:**
* Potential risks associated with the model, the data, and the outputs (e.g., contraindications, side effects, data privacy risks, cybersecurity risks, bias risks, information gaps)
* Description of information that could impact risks and patient outcomes, across the product lifecycle
* Interactions, Deployment, and Updates. When appropriate, provide the:
  * Computational Resources Required
  * Details regarding how the model is deployed and updated, including:
    * How to conduct local site-specific acceptance testing or validation
    * Ongoing performance monitoring
    * Transparent reporting of successes and failures
    * Change management strategies
    * Proactive approaches to address vulnerabilities
  * Communication to parties of as-needed information
  * Software quality (specify standards and regulatory compliance issues, intellectual property issues, risk management and safeguards used, other)

**Development:**
* Data Characterization of data used to develop the device:
  * Data sources (e.g., clinical trials, public or proprietary databases) including details on any devices used to collect data
  * Data types used (e.g., structured numerical data, structured categorical data, unstructured text, images, time-series data, or a combination)
  * Relevant details including the sample size, effect size, data quality, reference standard, diversity, and representativeness

# Appendix F: Example 510(k) Summary with Model Card
In general, publicly available summaries must follow the applicable requirements for the specific marketing submission (e.g., 510(k), De Novo, PMA). The items below are not an exhaustive list of topics that a manufacturer may be expected to cover, and all topics may not apply to all marketing submissions. Likewise, FDA may request additional information to be included in this summary. This appendix serves only as an example of the types of information sponsors should generally provide in a 510(k) summary, including an example of a completed Basic Model Card. Information does not need to be repeated between the model card and other sections of the public summary, but duplication is acceptable if it provides useful context.

**Indications For Use:**
The *Disease X Screening Model* is software intended to aid in screening for Disease X in patients above the age of 22 by analyzing 12-lead electrocardiogram (ECG) recordings from compatible ECG devices. It is not intended to be a stand-alone diagnostic device for Disease X. However, a positive result may suggest the need for further clinical evaluation in order to establish a diagnosis of Disease X. If the patient is at high risk for Disease X, a negative result should not rule out further non-invasive evaluation. It should not be used to replace the current standard of care methods for diagnosis of Disease X but applied jointly with clinician judgment.

**Device Description:**
The stand-alone software contains a machine learning model that uses a convolutional neural network (CNN) to interpret and analyze 10 seconds of a 12-lead resting electrocardiogram acquired from four compatible ECG devices (A, B, C, and D) and provide an output on the likelihood that a patient has Disease X and requires further clinical evaluation. The software also contains quality checks that will notify the end user whether the ECG data provided meets the input requirements necessary to generate a model output. If the data do not meet these requirements, an error message will be displayed.

| **Summary of Technological Characteristics** | **Subject Device** | **Predicate Device** | **Comparison** |                                   
| --- | --- | --- | --- |
| **Application Number** | KXXXXXX  | KXXXXXX | -   |
| **Product Codes**  | XXX   | XXX | -  |
| **Regulation Number** | 21 CFR XXXX  | 21 CFR XXXX | -  |
| **Rx/OTC**  | Rx | Rx  | Same |
| **Indication for Use** | The Disease X screening model is software intended to aid in screening for Disease X on patients above the age of 22 by analyzing 12-lead electrocardiogram recorded from compatible ECG devices. It is not intended to be a stand-alone diagnostic device for Disease X. However, a positive result may suggest the need for further clinical evaluation in order to establish a diagnosis of Disease X. If the patient is at high risk for Disease X, a negative result should not rule out further evaluation. It should not be used to replace the current standard of care methods for diagnosis of Disease X but applied jointly with clinician judgment. | Software intended to be used as an aid in determining if a patient has Disease X in patients 18 years and above. The software analyzes a 12-lead ECG from compatible devices and should not be used as a stand-alone diagnostic device. | Similar. Both devices are used as aids and screening tools for Disease X. The indications for use for the predicate device is for patients 18 years and above, whereas the subject device is for patients 22 and above. |
| **Operational Mode**  | Spot Check / Not to be used as a diagnostic device | Spot Check / Not to be used as a diagnostic device  | Same  |
| **Hardware Inputs**  | 12-lead ECG from the following compatible devices: A, B, C, D  | 12-lead ECG from the following compatible devices: A, B  | Similar. While both require inputs from a 12-lead ECG, the subject device allows for more compatible ECG input devices. |
| **Output**  | The software provides the following outputs:<br>1. Presence of Disease X. Seek further clinical evaluation to establish a diagnosis of Disease X.<br>2. Presence of Disease X not likely. However, please use clinical judgment and determine if further evaluation is necessary.<br>3. Error Message: The 12-lead ECG does not pass the quality checks in place. | Software provides an output on the possibility of Disease X and if further evaluation is needed. | Similar. Both devices identify if there is presence of Disease X and whether further evaluation is needed. Both indicate that they should not be used as a stand-alone and that clinical judgment should guide further evaluation. |
| **Ground Truth for Model Training** | Echocardiogram  | Echocardiogram  | Same  |
| **Performance** | Sensitivity: 87% (83%, 89%)<br>Specificity: 83% (81%, 85%)<br>Positive Predictive Value (PPV): 56%  | Sensitivity: 82% (78%, 85%)<br>Specificity: 81% (79%, 84%)<br>Positive Predictive Value (PPV): 53%  | Similar. The subject device has slightly better performance than the predicate device in sensitivity, specificity, and PPV. |

**Model Training Description:**
The model was trained from a dataset independent from the test dataset. The model was trained with 30,000 patients that received an ECG and echocardiogram performed within 30 days apart from one another. The echocardiogram was used to establish clinical reference standard (ground truth) in patients. The dataset was collected from clinical databases from 2 diverse hospital networks (Hospital A and Hospital B). Disease X was defined as patients who had a left ventricular wall thickness >= 15 mm based on echocardiographic imaging.
The training dataset contained the following demographic breakdown that was representative of the disease population:

| Race                                | Percentage (%) |
| ----------------------------------- | -------------- |
| White                               | 75.5           |
| Black or African American           | 13.6           |
| American Indian or Alaska Native    | 1.3            |
| Asian                               | 6.3            |
| Native Hawaiian or Pacific Islander | 0.3            |
| Two or More Races                   | 3.0            |

The sample consisted of 49.5% male and 50.5% female participants. The average age was 62 years with the following age breakdown below:

| Age (years)                | Percentage (%) |
| -------------------------- | -------------- |
| Under the age of 40        | 10             |
| 40-49                      | 10             |
| 50-59                      | 25             |
| 60-69                      | 30             |
| 70-79                      | 15             |
| Greater than the age of 79 | 10             |

Patients with Disease X were 20% of the overall cohort while patients without Disease X (control group) consisted of 80% of the overall cohort. Both groups were split into training (50%), tuning (20%) and tuning evaluation (30%) datasets. The sensitivity and specificity of the model were calculated from the tuning evaluation datasets. The model was able to achieve the following:
* Sensitivity: 87% (83%, 89%)
* Specificity: 83% (81%, 85%)
* Positive Predictive Value (PPV): 56%

**Summary of Non-Clinical Performance Data**
The model was evaluated taking into account applicable requirements of the FD&C Act and implementing regulations. This included the following testing:
* Human Factors and Usability testing was conducted and documentation was provided as recommended in FDA’s guidance document “Applying Human Factors and Usability Engineering to Medical Devices.”
* Cybersecurity testing was conducted and documentation was provided as recommended in FDA’s guidance document “Cybersecurity in Medical Devices: Quality System Considerations and Content of Premarket Submissions.”
* Software verification and validation testing was conducted and documentation was provided as recommended in the Premarket Software Guidance.

**Summary of Clinical Validation:**
**Study Design**
The model was validated in a retrospective study of 25,000 patients and their patient records across 5 different and diverse health systems across the United States. The objective of the study was to establish the performance of the model on screening for the presence of disease X. The inclusion criteria for the model were the following:
* The patients enrolled in the study were greater than the age of 22 with at least one 12-lead resting ECG and an echocardiogram within 30 days following the date of the ECG. The most recent echocardiogram was paired with the most recent ECG for that patient 2100 prior to the echocardiogram.
* The following models of ECG devices (A, B, C and D) were used to collect the 12-lead 2102 resting ECG data and used as the inputs to the model.
  * The 12-lead ECG duration must be 10 seconds long.

The exclusion criteria for the model were the following:
* The patients enrolled in the study were less than 22 years old.
* Mandatory data were missing (i.e., technical parameters of ECG, age or race demographic, information regarding the conducted ECG and echocardiogram).
* Different device models of 12-lead ECGs were used to collect the ECG data.
* The 12-lead ECG duration is not 10 seconds long.
* The patient has a pacemaker.

Each of the 5 sites contributed around 5,000 patient-ECG pairs to a final pool of 25,000 pairs.

| Race                                | Percentage (%) |
| ----------------------------------- | -------------- |
| White                               | 75.5           |
| Black or African American           | 13.6           |
| American Indian or Alaska Native    | 1.3            |
| Asian                               | 6.3            |
| Native Hawaiian or Pacific Islander | 0.3            |
| Two or More Races                   | 3.0            |

The study sample had the following hospital site breakdown:

| Hospital Site | Percentage (%) |
| ------------- | -------------- |
| A             | 19.64          |
| B             | 21.36          |
| C             | 20.1           |
| D             | 18.4           |
| E             | 21.5           |

The sample consisted of 49.5% male and 50.5% female participants. The average age was 65 years with the following age breakdown below:

| Age (years)                | Percentage (%) |
| -------------------------- | -------------- |
| Under the age of 40        | 10             |
| 40-49                      | 10             |
| 50-59                      | 16             |
| 60-69                      | 23             |
| 70-79                      | 22             |
| Greater than the age of 79 | 19             |

The study sample ECG pairs were collected by the following ECG acquisition devices. The breakdown can be found below:

| ECG Device | Percentage (%) |
| ---------- | -------------- |
| A          | 26.6           |
| B          | 25.1           |
| C          | 24.9           |
| D          | 23.3           |


**Primary Endpoints:**
The co-primary endpoints regarding this study were to have the lower limits of their 95% two-sided confidence intervals be:
* Sensitivity: 75% or higher
* PPV: 50% or higher

**Study Results:**
The model achieved a sensitivity of 84%, a specificity of 83%, a PPV of 55%, and a negative predictive value (NPV) of 95%. Both the point estimates and their 95% two-sided confidence intervals, along with the confusion matrix, can be reported in a table as shown in the following example.

|             | Ref. Pos | Ref. Neg | Sum   | Likelihood Ratio | Performance                   |
| ----------- | -------- | -------- | ----- | ---------------- | ----------------------------- |
| Test. Pos   | 4200     | 3400     | 7600  | 4.9 (4.8, 5.1)   | PPV = 55.3% (54.1%, 56.4%)    |
| Test. Neg   | 800      | 16600    | 17400 | 0.2 (0.2, 0.2)   | NPV = 95.4% (95.1%, 95.7%)    |
| Sum         | 5000     | 20000    | 25000 | 1 (1, 1)         | Prevalence 20% (19.5%, 20.5%) |
| Performance | Sensitivity = 84% (82.9%, 85%)| Specificity = 83% (82.5%, 83.5%)|       |                  |                               |

**Plain Language Interpretation for Benefit-Risk Consideration:**
Assume the prevalence of Disease X in the intended use population of the device is 20%. Among 1000 patients from the target population, about 168 (1000 × Prevalence × Sensitivity) patients will be correctly classified as having the Disease X (i.e., 168 device true positives out of 200 total reference positive patients), while about 136 (1000 × (1 - Prevalence) × (1 - Specificity)) patients will be wrongly classified as having the Disease X (i.e., 136 device false positives out of 800 total reference negative patients). Thus, each true positive patient comes at the cost of 0.8 (136/168) false positive patients (compares to Y from the standard of care, or 4 (800/200) from a worst-case scenario where every patient is called positive). Furthermore, to identify one extra true positive patient, we need to assess about two patients (considering potential device positive/negative outcomes) since NNP (Number Needed to Predict) = 1 / (PPV + NPV - 1) = 1.97 (compares to the standard of care with NNP of Z, or a perfect device with a NNP of one).

// 여기에 삽ㅇ비

The subgroup analysis for each demographic can be found below. 

*Please note that while confidence intervals could not be generated for this fictitious example, sponsors should include confidence intervals on all reported results. Placeholders have been included in each cell to represent the confidence interval: (Xll, Xul), where “ll” stands for lower limit and “ul” stands for upper limit.*

| Race                                             | Percentage (%) | Sensitivity     | PPV              |
| ------------------------------------------------ | -------------- | --------------- | ---------------- |
| White                                            | 75.5           | 85.3 (Xll, Xul) | 57.3% (Xll, Xul) |
| Black or African American                        | 13.6           | 82.9 (Xll, Xul) | 54.4% (Xll, Xul) |
| American Indian and Alaska Native                | 1.3            | 81.6 (Xll, Xul) | 54.8% (Xll, Xul) |
| Asian                                            | 6.3            | 83.9 (Xll, Xul) | 56.1% (Xll, Xul) |
| Native Hawaiian and Other Pacific Islander alone | 0.3            | 83.6 (Xll, Xul) | 56.5% (Xll, Xul) |
| Two or More Races                                | 3              | 84.1 (Xll, Xul) | 55.4% (Xll, Xul) |

| Age                        | Percentage (%) | Sensitivity     | PPV              |
| -------------------------- | -------------- | --------------- | ---------------- |
| Under the age of 40        | 10             | 84.9 (Xll, Xul) | 55% (Xll, Xul)   |
| 40-49                      | 10             | 85.1 (Xll, Xul) | 55.4% (Xll, Xul) |
| 50-59                      | 16             | 84.1 (Xll, Xul) | 55.4% (Xll, Xul) |
| 60-69                      | 23             | 84.5 (Xll, Xul) | 56% (Xll, Xul)   |
| 70-79                      | 22             | 83.6 (Xll, Xul) | 55.4% (Xll, Xul) |
| Greater than the age of 79 | 19             | 82.1 (Xll, Xul) | 52.7% (Xll, Xul) |

| ECG Acquisition Device | Percentage (%) | Sensitivity     | PPV              |
| ---------------------- | -------------- | --------------- | ---------------- |
| A                      | 26.6           | 84.7 (Xll, Xul) | 56.5% (Xll, Xul) |
| B                      | 25.1           | 83.6 (Xll, Xul) | 54.3% (Xll, Xul) |
| C                      | 24.9           | 85.4 (Xll, Xul) | 57.9% (Xll, Xul) |
| D                      | 23.3           | 84.6 (Xll, Xul) | 55.1% (Xll, Xul) |

| Hospital Sites | Percentage (%) | Sensitivity     | PPV              |
| -------------- | -------------- | --------------- | ---------------- |
| A              | 19.64          | 83.6 (Xll, Xul) | 54.3% (Xll, Xul) |
| B              | 21.36          | 85.1 (Xll, Xul) | 51.4% (Xll, Xul) |
| C              | 20.1           | 84.1 (Xll, Xul) | 55.4% (Xll, Xul) |
| D              | 18.4           | 85.4 (Xll, Xul) | 57.9% (Xll, Xul) |
| E              | 21.5           | 84.7 (Xll, Xul) | 56.5% (Xll, Xul) |

**Model Card:**
**Device Information**
* Model Name: Disease X Screening Model
* Model version: version 1.0.1
* Model release date: December 2023
* Model architecture: Convolutional Neural Network

**Device Description**
* Intended User: Healthcare professionals.
* Indications for Use: The model is software intended to aid in screening for Disease X on patients above the age of 22 by analyzing recordings of 12-lead ECG made on compatible ECG devices. It is not intended to be a stand-alone diagnostic device for Disease X. However, a positive result may suggest the need for further clinical evaluation in order to establish a diagnosis of Disease X. If the patient is at high risk for Disease X, a negative result should not rule out further non-invasive evaluation. It should not be used to replace the current standard of care methods for diagnosis of Disease X but applied jointly with clinician judgment.
* Clinical workflow phases: To be used as an aid and screening tool for further clinical follow-up (e.g., echocardiogram) in order to establish a diagnosis of Disease X.
* Clinical Benefit: To provide point-of-care screening of Disease X where cardiac imaging may not be available.

**Performance and Limitations**
* Data type: 12-lead electrocardiogram (ECG)
  * Description: 10 second duration of a 12-lead electrocardiogram (ECG) obtained from the following four compatible ECG devices (A, B, C, and D). The compatible ECG devices have a sampling rate of 500 Hz.
* Clinical Reference Standard: An echocardiogram obtained within 30 days of the ECG to establish clinical reference standard.
* Model Validation:
  * Data size and type: A retrospective study of 25,000 patients and their patient records across 5 different and diverse health systems across the United States. Each of the 5 sites contributed 5,000 patient-ECG pairs to a final pool of 25,000 patient-ECG pairs.
  * Exclusion Criteria:
    * The patients enrolled in the study were less than 22 years old.
    * Mandatory data were missing (i.e., technical parameters of ECG, age or race demographic, information regarding the conducted ECG and echocardiogram).
    * ECG data contained either corrupt or missing lead(s).
    * Different models of 12-lead ECGs were used to collect the ECG data.
    * The 12-lead ECG duration is not 10 seconds long.
    * The patient has a pacemaker.
  * Data Results (calculated from test datasets):
    * Sensitivity: 84% (82.9%, 85%)
    * Specificity: 83% (82.5%, 83.5%)
    * PPV: 55.3% (54.1%, 56.4%)
    * NPV: 95.4% (95.1%, 95.7%)
* Non-Clinical Testing:
  * Human Factors and Usability testing was conducted and documentation was provided as recommended in FDA’s guidance document “Applying Human Factors and Usability Engineering to Medical Devices.”
  * Cybersecurity testing was conducted and documentation was provided as recommended in FDA’s guidance document “Cybersecurity in Medical Devices: Quality System Considerations and Content of Premarket Submissions.”
  * Software verification and validation testing was conducted and documentation was provided as recommended in the Premarket Software Guidance.

**Risk Management**
Risk management was conducted, and documentation was provided as recommend in the Premarket Software Guidance and in accordance with ANSI/AAMI/ISO 14971 Medical devices - Applications of risk management to medical devices.
* Potential risks associated with the model, the data, and the outputs (e.g., contraindications, side effects, data privacy risks, cybersecurity risks, bias risks, information gaps): The potential risks associated with the model include incorrect follow-up due to a false positive or false negative output, which can occur because of (1) model bias or (2) using the model in an unsupported patient population or with unsupported input/hardware. Furthermore, information gaps may lead to overreliance on the device output for follow-up. Controls for identified risks include clinical validation testing, software verification and validation testing, human factors testing and labeling.
* Description of information that could impact risks and patient outcomes, across the product lifecycle: Model development and clinical validation included only 10% of participants under the age of 40, which may mean that the model’s performance on that subgroup is not fully characterized.
* Interactions, Deployment, and Updates: A comprehensive Device Performance Monitoring Plan is in place that is consistent with the Quality System Regulation (21 CFR Part 820) which continuously monitors the deployed model to evaluate site-specific performance, identify vulnerabilities, and ensure transparency of performance and ongoing maintenance to sites and end users.
  * Computational resources required.
  * Details regarding how the model is deployed and updated:
    * How to conduct local site-specific acceptance testing or validation: Prior to use of the model in the site’s entire population, the model is deployed, and data is collected for a one-month period in order to understand any issues with integration into the sites’ existing systems and measure performance on a subset of the patient population for that site. Through this process, issues with deployment can be addressed prior to exposure to the entire population and can help characterize performance of the model and the need for additional training and development. Alternatively, sites may opt to provide historical data that can be used to assess expected performance at the site.
    * Ongoing performance monitoring: Automated performance calculation is deployed along with the model and calculated every 6 months; if the performance is out of the expected range, an automated e-mail will be sent to the site administrator and sponsor. This will initiate a process for understanding performance issues and a mitigation plan will be put in place to address this.
    * Transparent reporting of successes and failures: All sites will have access to anonymized reports that will include successes and failures of deployed models at various sites, along with site characteristics to contextualize these successes and failures.
    * Change management strategies: Change management will be implemented consistent with established Quality System procedures if and when issues arise that require a change or if features are requested by sites and users.
    * Proactive approaches to address vulnerabilities: Sites and users are encouraged to report any issues within 48 hours of the issue occurring, which will then follow complaint handling procedures and for which a fix will be issued according to these procedures.
  * Communication to parties of as-needed information: Automated e-mails will be generated by the device when performance is out of the expected range, as described above.
  * Software quality (specify, standards and regulatory compliance issues, intellectual property issues, risk management and safeguards used, other).

**Development**
* Model Training:
  * Data size: 30,000 patients that received an ECG and echocardiogram performed within 30 days apart from one another. Dataset collected from clinical databases from 2 diverse hospital networks (Hospital A and Hospital B).
  * Patients with Disease X were 20% of the overall cohort while patients without Disease X (control group) consisted of 80% of the overall cohort. Both groups were split into training (50%), tuning (20%) and tuning evaluation (30%) datasets.
  * Data Results (calculated from tuning evaluation datasets):

    * Sensitivity: 87% (83%, 89%)
    * Specificity: 83% (81%, 85%)

**Conclusion**
While there are differences noted in the technological characteristics of the proposed system and the predicate device, the differences do not raise different questions of safety or effectiveness. Based on the information provided in this submission, the subject device demonstrates that it is substantially equivalent to the predicate device through the results of clinical performance and results of non-clinical verification and validation.
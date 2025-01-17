
# CIPTA SRIGATI LESTARI

PT Cipta Srigati Lestari (CIPTA) has over ten years of experiences as the Strongest Indonesian Smart Card Technology Company. CIPTA has a business core in Telecommunication, Banking, Retail and Government sector. CIPTA also has already started to expand the Solution for every business aspect. With more than 1000+ professional and expert manpower, CIPTA has successfully received Three International Certifications of Security Accreditation Scheme (SAS), MasterCard, and Visa

## Career History

### Smart Card Engineer (R & D Team Department)

 #### Alpha QC Engineer (Feb 2017 - DEC 2018)
  - Conducted offline testing of smart card products using automated techniques, such as scripting and test automation tools, following standards like ISO/IEC 7816, 3GPP, and ETSI
    
 #### Beta QC Engineer (OCT 2016 - Feb 2017)
  - Conducted direct online testing using handset to validate functionality and performance at final implementation levels

The Flow is Alpha Testing and then Beta testing

### Tech stack Development
 - Hardware : Smart Card (Native, Java Card), Card Reader Omnikey Card Man, SIM 900, Handset/Smart Phone
 - Software : Tools (Telco Tools, sopi tools etc)
 - Languange : C++, C#, Java

## Alpha Testing

| Type of Testing                    | Description                                                                                     |
|------------------------------------|-------------------------------------------------------------------------------------------------|
| Requirement test                   | Ensuring the software meets specified requirements.                                             |
| Compliance with Standards          | Checking if the software complies with industry standards and regulations.                      |
| Functional test                    | Verifying the functionality of the code with scipt test.                                        |
| Conformance test                   | Ensuring the software conforms to predefined standards or specifications.                       |
| Security Test                      | Checking the software for vulnerabilities and ensuring data security.                           |
| OTA                                | Testing software updates delivered over the air.                                                |
| Stress Test                        | Testing the software under extreme conditions to evaluate stability.                            |
| Regression Testing                 | Verifying that recent code changes have not adversely affected existing features.               |

## Beta Testing

| Type of Testing                    | Description                                                                                     |
|------------------------------------|-------------------------------------------------------------------------------------------------|
| Functional test                    | Verifying functionality in a real-world environment.                                            |
| Compatibility test                 | Testing compatibility with different systems, browsers, and devices.                            |
| Cross-Device Testing               | Ensuring correct operation on various devices.                                                  |
| Usability test SIM Toolkit         | Evaluating the user interface and user experience.                                              |
| Network testing                    | Testing performance and reliability over different networks.                                    |
| Compliance and Regulatory Testing  | Ensuring compliance with regulations and standards.                                             |
| Installation and Update Testing    | Testing installation and update processes.                                                      |

## ALL PROJECT
All the projects not only on a national but also on an international, detail can be seen as follows (+/- 59 Project): 

![Screenshot 2024-05-10 200657](https://github.com/DianPermana/Smart-Card-History-In-Indonesia/assets/18004033/ca169390-f4fc-44db-b172-7da42d0ae8fb)

![Screenshot 2024-05-10 200723](https://github.com/DianPermana/Smart-Card-History-In-Indonesia/assets/18004033/1aece0bb-efe9-4f4e-a580-fbc29a32dfdf)


## Heandset specification

Example handset Android for Beta QC :

![image](https://github.com/DianPermana/Smart-Card-History-In-Indonesia/assets/18004033/cfdc176e-0bc7-4b16-be7e-5280922160f2)

Including : Android (1 : Froyo- 7 : Lollipop), IOS (Iphone 4 - 6 plus), Windows Phone, Blackberry, AndroidTab, Non-Android (Nokia, Erricsson, Mito, LG, ZTE, Esia, Nexian, Motorolla, etc)

## Structure Folder Project 

Here's example Structure Folder each project : 

```
Project X
├── Documentation (project manager, smart card Developer, smart card dev reviewer, Alpha QC, Alpha QC Reviewer, Beta QC, Beta QC Review)
│   ├── Specification.docx >> Pure From Customer
│   ├── Software Architecture Description      (SAD) : Architecture in General
│   ├── Software Requirement Specification     (SRS) : All Requirement tools in General as a team
│   ├── Project Kick Off                       (PKO) : Participant Review, Document Review
│   ├── Project Requirement Review             (PRR) : Deliver Document
│   ├── Functional Requirment Specification    (FRS) : Project Informations based on Functional
│   ├── Technical Answer and Planning          (TAP) : All Blocker in Technical Level
│   ├── Product Generation Description         (PGD) : All requirment based on Development work
│   ├── Project Test Plan                      (PTP) : Testing Information (Hardware, software, Tools, Type Of testing including alpha & Beta)
│   ├── Alpha Test Description                 (ATD) : Tools Information needed (Hardware, Software, Tools, Requirement software feature, Profile, Reference Project before)
│   ├── Beta Test Description                  (BTD) : Tools Information needed (Hardware, Software, Tools, Requirement software feature, Profile, Reference Project before)
│   ├── Alpha Test Results                     (ATR) : Testing Information Results (refers to Alpha Testing/Test Report >> ConformanceSIM, Profile etc)
│   ├── Beta Test Results                      (BTR) : Testing Information Results (Setup Call, Internet Access, Messaging, SIM Message, SPN, STK Menu)
│   ├── Test Deviation                          (TD) : Alpha & Beta Test Deviation (Not bug, but something should be clarify and statement)
│   ├── Project Closed Review                  (PCR) : Delivery Document
│   ├── Change Request                          (CR) : Change request while project running
│   └── etc
|
├── Development or Generation
│   ├── PSF, XML, SPS File on .zip
│   └── Readme.txt
|
├── Testing
│   ├── Results
│   │   ├── Alpha Test Report.zip
│   │   |    └── GSM_1117, GSM_Additional_Test, COMP128, ConformanceSIM, ConformanceUSIM, OTA, Millenage Authentication, OTA Specific Customer, Profile, Authentication, PERSO File, SimServiceTable, SpecificationCustomer, etc.txt
|   │   │      └── ConformanceSIM : Read Binary, Read Record, ChangePIN, Activate, Deactivate, Enable, Disable, Increase, etc
|   │   │          └── etc.
|   │   └──  Beta Test Report.docx
│   ├── Script   
│   │   ├──  Alpha Test Scripts
│   │          └── GSM_1117, GSM_Additional_Test, COMP128, ConformanceSIM, ConformanceUSIM, OTA, Millenage Authentication, OTA Specific Customer, Profile, Authentication, PERSO File, SimServiceTable, SpecificationCustomer, etc.cpp
│   │           └── ConformanceSIM : Read Binary, Read Record, ChangePIN, Activate, Deactivate, Enable, Disable, Increase, etc
|   │             └── etc.
|   │
└── Tools
    └── Persogen.dll

```

## Standart Technical DOC

### Standart Technical ISO-7816
Complex Cards support all communication protocols present on regular smart cards: contact, thanks to a contact pad as defined ISO/IEC 7816 standard, contactless following the ISO/IEC 14443 standard, and magstripe.
ISO/IEC-7816 consists of the following parts, under the general title Identification cards — Integrated circuit  cards with contacts: 
 - Part 1: Physical characteristics
 - Part 2: Cards with contacts — Dimensions and location of the contacts
 - Part 3: Cards with contacts — Electrical interface and transmission protocols
 - Part 4: Organization, security and commands for interchange
 - Part 5: Registration of application providers
 - Part 6: Interindustry data elements for interchange
 - Part 7: Interindustry commands for Structured Card Query Language (SCQL)
 - Part 8: Commands for security operations
 - Part 9: Commands for card management
 - Part 10: Electronic signals and answer to reset for synchronous cards
 - Part 11: Personal verification through biometric methods
 - Part 12: Cards with contacts — USB electrical interface and operating procedures
 - Part 13: Commands for application management in a multi-application environment
 - Part 15: Cryptographic information application

### Standart Technical 3GPP for SIM  : 
  - 3GPP TS 11.11  (182 Page) 	: 3rd Generation Partnership Project; Technical Specification Group Terminals Specification of the Subscriber Identity Module - Mobile Equipment (SIM - ME) interface
  - 3GPP TS 11.14  (157 Page)	: 3rd Generation Partnership Project; Specification of the SIM Application Toolkit for the Subscriber Identity Module - Mobile Equipment (SIM - ME) interface
  - 3GPP TS 11.17  (88  Page)	: 3rd Generation Partnership Project; Technical Specification Group Core Network and Terminals; Subscriber Identity Module (SIM) conformance test specification
  - 3GPP TS 23.038 (88  Page) 	: 3rd Generation Partnership Project; Technical Specification Group Core Network and Terminals; Alphabets and language-specific information
  - 3GPP TS 23.040 (204 Page) 	: Digital cellular telecommunications system (Phase 2+); Universal Mobile Telecommunications System (UMTS); Technical realization of the Short Message Service (SMS)
  - 3GPP TS 03.48  (34  Page)	: 3rd Generation Partnership Project; Technical Specification Group Terminals; Security mechanisms for the SIM application toolkit; Stage 2
### Standart Technical ETSI for SIM, USIM, UICC : 
  - ETSI TS 131 111 (138 Page) : Digital cellular telecocommunications system (Phase 2+); Universal Mobile telecommunications System (UMTS); LTE; Universal Subscriber Identity Module (USIM) Application Toolkit (USAT) (3GPP TS 31.111 version 12.7.0 Release 12)
  - ETSI TS 131 122 (214 Page) : Universal Mobile Telecommunications System (UMTS); LTE;  Universal Subscriber Identity Module (USIM)  conformance test specification (3GPP TS 31.122 version 11.0.0 Release 11)
  - ETSI TS 131 124 (1127 Page): Universal Mobile Telelecommunications System Mobile Equipment (UMTS); LTE;  Mobile Equipment (ME) Conformance test specification; Universal Subscriber Identity Module Application Toolkit (USAT) conformance test specification (3GPP TS 31.124 version 12.3.0 Release 12)
  - ETSI TS 102 221 (174): Smart Cards; UICC-Terminal interface; Physical and logical characteristics
  - ETSI TS 131 101 (36) : Universal Mobile Telecommunications System (UMTS); UICC-terminal interface; Physical and logical characteristics (3GPP TS 31.101 version 9.1.2 Release 9)
  - ETSI TS 131 102 (205): Universal Mobile Telecommunications System (UMTS); LTE; Characteristics of the Universal Subscriber  Identity Module (USIM) application (3GPP TS 31.102 version 8.4.0 Release 8)
  - ETSI TS 131 121 (290): Universal Mobile Telecommunications System (UMTS); LTE; UICC-terminal interface; Universal Subscriber Identity Module (USIM) application test specification (3GPP TS 31.121 version 10.1.0 Release 10)
  - ETSI TS 151 011 (172): Digital cellular telecommunications system (Phase 2+); Specification of the Subscriber Identity Module - Mobile Equipment (SIM-ME) interface (3GPP TS 51.011 version 4.15.0 Release 4)

I try to Mapping All progress that I learn : https://github.com/DianPermana/Smart-Card-History-In-Indonesia/blob/main/3GPP%20TS%2011.11%20V8.14.0%20(2007-06)%20Dian%20Permana.xlsx

## Research \& Development
- Read SMS on SIMCard using C# : still working in windows 11
  
| Read SMS                           | Read Phonebook                                                                                  |
|------------------------------------|-------------------------------------------------------------------------------------------------|
| ![image](https://github.com/DianPermana/Smart-Card-History-In-Indonesia/assets/18004033/9181a6ac-18e9-4c9c-a19c-eb95f4a8cc27) | ![image](https://github.com/DianPermana/Smart-Card-History-In-Indonesia/assets/18004033/4aa23c06-4edf-4f23-8f23-413aada4fd7a)
                                            
- Calling other Number via AT-Command using SIM-900
- Now in 2024 I have integrated Reporting with allure report for smart Card testing using python, detail can be check here : [https://www.youtube.com/playlist?list=PL-PGLNGPDn5_7h3M-lxxbf_OvYFgAWiz_](https://youtube.com/playlist?list=PL-PGLNGPDn5_7h3M-lxxbf_OvYFgAWiz_&si=7NUI6jlOeUGQtckR)

## Learn From CIPTA
- Make it simple, Learning by doing, Learning from sharing
- Testing is the comparison of results VS expectations.
- Flow proccess SmartCard Development Life Cycle should be clear based on Organization, yes Agility is important but without clear flow everyhing will crash
- The flow of process testing in the SmartCard Development Life Cycle should be conducted starting from how data is stored in memory, particularly in smart cards where data is in Transparent, Linear Fixed, and Cycle formats. This is one of the fundamental aspects of how data is stored. In different systems like databases, there are agents or protocols that connect the application level with the database, hence testing is necessary.
- This tools is awesome, I will help you to contact mas seno if your company need it (just ping me) 
 ![image](https://github.com/DianPermana/Smart-Card-History-In-Indonesia/assets/18004033/b2e0231f-cd2d-456c-a031-a5f00845d3ab)

    
## Thank You
Hopefully the knowledge gained will be useful and contribute to building Indonesia's golden generation in 2045.

Thank you,

Dian Permana

#SmartCard #ISO7816 #simcard #3GPP #ETSI #Fundamental #ChipCard #SecurityTechnology #EMV #NFC #ContactlessPayment #Authentication #CryptographicTechnology #CardTechnology #RFID #DigitalSecurity #PaymentSystems #shortsvideo #fyp #fypシ #pyscard #python #pytest #allure #Reporting





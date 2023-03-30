## Category
* [About me](#about-me)
* [Skills](#skills)
* [Work Experience](#work-experience)
	* [Freelancer](#freelancer)
	* [Intel](#intel)
	* [Renasas Mobile](#renasas-mobile)
	* [MStar Semiconductor](#mstar-semiconductor)
	* [LiteOn](#liteon)
	* [BenQ](#benq)
* [Awards](#awards)
* [Education](#education)
* [Side Projects](#side-projects)
* [Language](#language)

---
## About me
>* 3 years experiences on back-end/front-end server implementation.
>* 8 years experiences on implement Android App.
>* 5 years experiences on Linux/Android system bring up and BSP.
>* 3 years experiences on chip verification and device driver implementation.
>* 7 years experiences on mobile phone developments, including BB/RF driver, Layer1 Protocol, GCF certification.

> **Full of curiosity**, **love coding**, **enjoy of chalenges**, **self discipline**
---

## Skills
#### Speciallity 
>C/C++, Java, Kotlin, JavaScript, Android App, Android BSP, Android RIL, SQLite, MongoDB, HTML5, CSS, Angular, NodeJS, Embedded System, Firmware, 3GPP L1, SUPL

#### Algorithm
> 1000+ problems solved on [LeetCode](https://leetcode.com/kevinchung0921/)
<img width='400' src='https://github.com/kevinchung0921/resume/blob/b35cc92a912cecd41cee3e8295ee38689b1b7405/images/leetcode_2023_03.png' href='https://leetcode.com/kevinchung0921/'/>

---

## Work experience
#### Freelancer 
###### Software Engineer, *05 / 2015 ~ now*
	
>* [KA Finance App](https://play.google.com/store/apps/details?id=com.kevin.finance_v2)
>* [KA Finance website](https://finance.ka-soft.com/)
>* [Idar](https://finance.ka-soft.com/idar)
>* [IAB OM sdk certification](https://iabtechlab.com/compliance-programs/compliant-companies/) for [UCFunnel](https://ucfunnel.com)

---

#### Intel
###### Software Engineer, *09 / 2013 - 05 / 2015*
>* Android RIL support for customer integration
>* Port 3G dongle for Intel tablet platform
>* ODM/OEM customer training


---
#### Renasas Mobile
###### Technical Manager, *02 / 2012 - 07 / 2013*

>* Support Renesas Mobile LTE modem + TI OMAP blaze for Quanta (USB interface)	
>* Spport Renesas Mobile LTE modem + nVidia Tegra3 for Compal communication (HSI interface)	
>* Support Renesas Mobile Single Chip for HTC evaluation 

---
#### MStar Semiconductor
###### Technical Deputy Manager, *05 / 2007 - 01 / 2012*

>* **WiFi test tool and test cases**: I wrote a PC tool with GUI(BCB) for automatically regression test and some of the test case.	
>* **SUPL protocol**: to develop the SUPL protocol to enable AGPS function of MStar GPS chip. I made this from scratch include specification study, ASN.1 compiler survey, software architecture and the implementation. Finally it was adopted by the customer including the IOT with the operator.	
>* **GPS logger application**: The features of this tool require reading position information from MStar GPS chip and using Google Map to show it. 	
>* **Linux BSP for PND device**: I was the software leader for a new PND chip bring up and Linux BSP implement. This role required not only coordinate with IC designer, hardware and application engineer but also have to implement the device driver. So I ported the NAND, Touch screen, Backlight and keyboard driver in this project and have good knowledge on Linux kernel driver. And I also successfully ported the Android onto this platform with limited function in just 2 weeks after the first release of Android source code.
>* **Connected PND chip (GPRS/GPS integration)**: We integrate GPS and GPRS chip in the same die in this project. I was in charge the GPRS part function. With very limited human resources, we break the company’s record to get GCF certification in one month. 	
>* **TDD/GSM Dual mode**: manager decided to send two best layer1 engineers of company to UK branch for transfer TDS-CDMA/GSM dual mode technology. I was recommended to be one. After few weeks training and co-worked with UK and Shanghai team, we finally delivered this feature.
>* **3.5G Android platform**: I was assigned to porting in house RIL with multiplexer function, I successfully porting the in house proprietary RIL on Android with very limited modifications on interface. 	
>* **Linux FM radio** via UIO; define new Hardware Abstraction Layer, JNI and associated Java application. 

---
#### LiteOn
###### Associate Manager, *11 / 2004 - 11 / 2006*
>* Manage system/protocol/driver team to deveopment GSM/GPRS feature phone
>* GPRS/GPS module for fleet management, wireless meter reader application
>* 3G data card survey and plan
>* Create patent map database for 3GPP IPR

---
#### BenQ
###### Technical Associate Manager, *10 / 1999 - 10 / 2004*

>* **Smart battery driver** (**1-wire protocol**): This protocol use a single GPIO as input and output which requires accurate timing control. Because of not allow to mask interupts during access, error detect and handle was also implemented.
>* Design and maintain **AT command** via **UART** for communicate between application processor and modem.  
>* Developing various **GSM/GPRS RF drivers** (Infineon, SiLab, Conexant): I wrote the very first GPRS driver in the company, in spite of lacking of RF background knowledge and experiences at that time, I still manage to make first phone call just one week later after the handset pilot-run. 
>* **Current consumption reduction**: we successfully reduce the 20% current consumption by fine tune RF driver, optimize system behavior and find out circuit leakage.
>* **Mobile phone certification**(GCF) support at 7 Layer(Cambridge, UK), ADR lab(Flensburg, Germany).
>* **Camera driver** development on feature phone(**SPI interface**). 
>* Resolve field trial issues: This the toughest part before phone going mass-production due to the complex network environment and various user behaviors. It requires the capability to analyze huge logs very carefully.

---
## Side projects
#### AT2
###### Language: BCB
###### Purpose: Auto test for GSM modem functions
###### Features: COM port read/write, string matching, flow control, Equipments control via GPIB, script save/load

<img width='400' src='https://github.com/kevinchung0921/resume/blob/26850dabe3ae4b3146133268fb743f2222b4f027/images/AT2.png' />

#### RD Driver analyzer
###### Language: BCB
###### Purpose: Transfer RF driver C source code to GPIO timing chart for analysis and tuning
###### Features: Parsing C source via Preprocessor and draw as timing chart, support measurement between signals

<img width='400' src='https://github.com/kevinchung0921/resume/blob/26850dabe3ae4b3146133268fb743f2222b4f027/images/RF_driver_analyzer.png' />

#### PCTM
###### Language: BCB
###### Purpose: GUI for RF/BB test commands on TI modem platform
###### Features: Send various test command on the fly

<img width='400' src='https://github.com/kevinchung0921/resume/blob/26850dabe3ae4b3146133268fb743f2222b4f027/images/pctm.png' />

#### COFFEE
###### Language: BCB
###### Purpose: Extract COFF(common object file format) debug symbols to translate address to source file name and line number
###### Features: COFF parser, crash log analysis, symbol search, disassembly on ARM/Thumb mode

<img width='400' src='https://github.com/kevinchung0921/resume/blob/26850dabe3ae4b3146133268fb743f2222b4f027/images/coffee.png' />

#### RIL MSC
###### Language: Python
###### Purpose: Convert Android logcat messages into RIL message sequence chart
###### Features: Collect log from couples of RIL relevant thread and create mscgen script for generate chart

<img width='400' src='https://github.com/kevinchung0921/resume/blob/26850dabe3ae4b3146133268fb743f2222b4f027/images/ril_log_msc.png' />

#### SUPL test tool
###### Language: BCB
###### Purpose: Perform SUPL flow for function verification
###### Features: Initial SUPL protocol to specified server, dump PDU, write aiding data into in house GPS solution

<img width='400' src='https://github.com/kevinchung0921/resume/blob/26850dabe3ae4b3146133268fb743f2222b4f027/images/supl.png' />

#### [MDIDrawable](https://github.com/kevinchung0921/MdiDrawable)
###### Language: Kotlin/Python
###### Purpose: Runtime generate icon from MDI font
###### Features: auto download mdi font and generate Android string resource xml file, many controllable effects including color, shadow,..

<img width='400' src='https://github.com/kevinchung0921/resume/blob/c3d7cc5d3d49092ced0ba1d8af2695e08e921981/images/Screenshot%20from%202023-03-28%2014-03-20.png' href='https://github.com/kevinchung0921/MdiDrawable'/>

#### [EInvoice SDK](https://github.com/kevinchung0921/einvoice_sdk)
###### Language: Kotlin
###### Purpose: Taiwan EInvoice API SDK
###### Features: Query einvoice header and details

<img width='400' src='https://github.com/kevinchung0921/resume/blob/734c107b9f9b8f421830ac8a4c5d91e2d58b8d1a/images/Screenshot%20from%202023-03-28%2016-52-35.png' href='https://github.com/kevinchung0921/einvoice_sdk' />


#### [Product classifier](https://github.com/kevinchung0921/product_classifier)
###### Language: Python, pyTorch
###### Purpose: Machine Learning model for classify merchandise 
###### Features: Use Selenium for collect web pages, and pyTorch for model training.


---
## Awards
* Several peer Recognitions at **Intel**
* Short term award at **MStar**
* President award at **MStar** 
* Special bonus at **BenQ**


## Education
* **Master**, Electric Engineering
    * National Taiwan Ocean University, *09/1997~06/2000*
* **Bachelor**, Electric Engineering
    * National Taiwan Ocean University, *09/1993~06/1997*
---
## Language
* Chinese: Native Speaker
* English: Fluent, ** TOEIC 835 **
<img width='400' src='https://github.com/kevinchung0921/resume/blob/26850dabe3ae4b3146133268fb743f2222b4f027/images/toeic_.png' />


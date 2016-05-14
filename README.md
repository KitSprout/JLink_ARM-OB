[JLink_ARM-OB](https://github.com/KitSprout/JLink_ARM-OB)
========
* Author  : [Hom](https://github.com/Hom-Wang)
* Version : v2.2(103), v1.0(072)
* Update  : 2016/05/14

Description
========
JLink_ARM-OB 是一個採用 STM32 的 JLink 燒錄器，為了縮減電路體積，僅有 [SWD](http://en.wikipedia.org/wiki/Joint_Test_Action_Group#Serial_Wire_Debug) ( Serial Wire Debug ) 功能，除了上述與無法檢測電壓外，其餘功能與 JLink 一樣，072 版本增加了 VCP 的功能，進一步簡化開發所需的工具。

License
========
* 硬體(Hardware)採用 [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/deed.zh_TW) 方式授權 
  
　　<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/deed.zh_TW"><img alt="創用 CC 授權條款" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/3.0/tw/80x15.png" /></a>  
　　<span xmlns:dct="http://purl.org/dc/terms/" property="dct:title"> JLink_ARM-OB 072 v1.0 </span>由<a xmlns:cc="http://creativecommons.org/ns#" href="http://about.me/Hom" property="cc:attributionName" rel="cc:attributionURL"> Hom </a>製作，以<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/deed.zh_TW"> 創用CC 姓名標示-相同方式分享 4.0 國際 授權條款 </a>釋出。  

Hardware
========
* 控制器　 : STM32F072C8 48Pin
* PCB 尺寸 : 12 * 24mm
* 設計軟體 [Altium Designer 16](http://www.altium.com/en/products/altium-designer) ( PcbLib use AD [PcbLib v2.5](https://github.com/KitSprout/AltiumDesigner_PcbLibrary/releases/tag/v2.5) )

Related Documents
========
* [Google Drive](http://goo.gl/CKChoa)

View
========
<img src="https://lh3.googleusercontent.com/OnGatLQCXPB4itrc_-s3h01Sx0GTfRR3TBeKPkFEuCEqPDyZvTO6G9s7INqBRyCFq6HrMjtmPjBIoWJlOUmndXdGNELkoTD_-TaYROu3EjdtAmCoSWlDsEUZS8faQE8otolemeUVEVvvGuzsV4lI1HD4D78I2iS81TQd90C87XnrynMfS57dCSICOq3CaqErDSnFyNtkb2697oPfci7450pMp593Z5R8l86AUloegFU_zvHA_dgNIwn147uoaWsK6OszFeOxRNDdKX46JWkIXD7A34Dl25i2bAf5CzcxIhoLP9oayNDzpH0eUHJon0VPzRvvfmiyV9K9NMeuVL4e6gvNx6mmImrHrP-sxEoOLZGG5zRUaM_vtARp5RFmiHIPxioyRltZtO1SR31Guf_BOhc45u55g12BvdvitLwU0ipS0o1nduyY2sVV9mLlo5AqnazzCFlD_R3vwEloEaeYAT9wru1LCQZnILNWCB-w-0BiKKo1Jk1xSIRb_ZhMr6vcx9K6AplIxeo5sFZkrrUDvSneQu0RzbBcA0dfirDcpC2lzkxo4bgHgjIb1kO-T7fEbf72wTt9duGDYTP9hjxdr_MolkzCizU=w1034-h775-no" />

Schematic
========
<img src="https://lh3.googleusercontent.com/1jYmqUdMQ9F6zWqd1CC5AZxal1-stVp1aGT2D0LsqaxImtUyluchCa52QPlcCytYTlxtVQoZSvklPSGrWB-XGvlxSQn0454I-OuvZ3q3_zip4ukUrMkhIsUctA0honnfYUHdAQ8Zb4NvZTayifYjTDOrvLPZFsHFCjxbVmlBCdC8v2zciJj0RMS3P71ptW3nptu-EvP_ylsH06iIDAHRMw5cmNC8VKeR6HYOaiku3vdQXsQmpHJl9-SieQ2XX_9nmPQBua-skMIH2q0zUiq6YQUtlmBjMA6iA7qGgvUedbsPtsYqGLxTIftAcQlMZKny47cNcfqlyTsKzEahTNnu6VMxP4rXjFhlrrn08TRgOjnHYj-zds9CYGepavmWy99VPeTHkpAtypOa-mjH3Jp0SRJljSH-1AxGRTw0qVH8KO6rY-59wMD1jYiJX-ITSizVnT2KzLGbdp9BGVZnJEcTHtL22jGe1HI7MUcKMaHhd9bFv6A7smDE7tbgXBb9GrjVgIDMmpLn3sXVFWYf_8SgXWIm8zhTlUDEcUHH6uMyPFXpRky6iUhf-6Qj_uHV3A4kH2ExgSJ-w1pgLFjxZuFHHaGMpBkkbFU=w1086-h775-no" />

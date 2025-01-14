# BeepTrace_release![](https://img.shields.io/badge/license-MIT-blue)
## Background
In order to solve the problem of privacy leakage in the contact tracing of traditional infectious diseases, such as the recent COVID-19 epidemic, we are developing a blockchain-enabled Privacy-preserving contact tracing smartphone application, named BeepTrace.

## Framework
Based on a sharing concern about user privacy, there are two different modes of BeepTrace, BeepTrace-active, and BeepTrace-passive. The backbone of both approaches is the blockchain, and their main difference is in the method of generating contact information and the positive cases matching protocols. The sensing technology for `active mode` is  `Bluetooth Low Energy (BLE)`, and Geographic Information System (PostGIS) is for passive mode. The detailed information is illustrated in these two articles: _BeepTrace: Blockchain-enabled Privacy-preserving Contact Tracing for COVID-19 Pandemic and Beyond_ and _Privacy-Preserving Contact Tracing and Public Risk Assessment Using Blockchain for COVID-19 Pandemic_.
## UI design

<div align=center>
<img src="https://user-images.githubusercontent.com/62978386/117529601-f4e8ef80-b00a-11eb-9c21-b75fab366cf7.png" width="415" height="900" alt="home"/>
<img src="https://user-images.githubusercontent.com/62978386/117540447-0f8a8b00-b042-11eb-900d-3edbcb02caa7.png" width="415" height="900" alt="home"/>
</div>

<div align=center>
<img src="https://user-images.githubusercontent.com/62978386/117541255-968d3280-b045-11eb-8ad4-00893dada297.png" width="830" height="711" alt="home"/>
</div>

## Blockchian logs
The following picture shows the settings of our Ethereum private chain, as well as the blockchain logs (uploading activity).

<div align=center><img src="https://user-images.githubusercontent.com/62978386/117529350-c3bbef80-b009-11eb-9b62-dbae53dd06d7.png" alt="logs"/></div>

From the follwing screenshot of Geth client, all risky pseudo-IDs (desensitizing contact information from positive cases) are packaged into a block.

![image](https://user-images.githubusercontent.com/62978386/117545099-f3451900-b056-11eb-9c09-51b235fb6ec4.png)

A demonstration on Ganache:

![image](https://user-images.githubusercontent.com/62978386/117545315-cc3b1700-b057-11eb-8f7d-8e467611f7db.png)


## License
[MIT](https://choosealicense.com/licenses/mit/)

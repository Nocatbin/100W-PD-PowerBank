# 100W-PD-PowerBank
基于英集芯IP5389-BZ，支持最大100W输出的全协议充电宝。本设计参考英集芯DEMO V1.2和@wzw666的开源工程，对原理图进行了小幅修改，同时改为4层PCB设计。

REF：https://oshwhub.com/wzw666/ip5389

注：

1、数码管需使用与Datasheet中原理图相同的5Pin数码管，可以实现快充小闪电与百分号显示，6Pin只能显示188数字

2、电感可改用10uH 6A铁硅铝磁环电感，大大降低BOM成本

3、100W输出输入稳定性暂时没有条件测试，从协议上看能够支持

## 各种测试

USB-A协议测试

![pic](https://github.com/Nocatbin/100W-PD-PowerBank/blob/master/Reference/TestResult/USBA_Protocol.jpg)

USB-C协议测试

![pic](https://github.com/Nocatbin/100W-PD-PowerBank/blob/master/Reference/TestResult/USBC_Protocol.jpg)

65W充电测试

![pic](https://github.com/Nocatbin/100W-PD-PowerBank/blob/master/Reference/TestResult/Charging_65W.jpg)

100W PD诱骗转DC测试

![pic](https://github.com/Nocatbin/100W-PD-PowerBank/blob/master/Reference/TestResult/PD_OUT_100W_Peak.jpg)
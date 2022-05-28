---
description: Simple Network Manager Protocol
---

# SNMP 架構及應用方式

目的：以一種 MIB 樹狀架構, 將每一管理物件內的屬性以 ID編號(OID), 包裝於.\*mib中, 只要透過載入 \*.mib, 便可以透過指定 Method, 取得物件位置及數值

> MIB (Manangement Information Base):管理資訊資料庫, 顧名思義是將物件集中在一個資料庫中管理

### SNMP架構包含四個要素

1. SNMP Manager
2. SNMP Agent
3. OID
4. NMS

> NMS(Network Management Station): 為管理 SNMP Agent 的站台

### 索取資訊Method

1. Traps
2. Request / Response



### SNMP Agent / Manager 與 Method的關係

![](.gitbook/assets/SNMP\_function.png)



### SNMP Version

* **SNMPv1:**&#x20;

1. only read
2. agent與Manager需要設定相同Community

* **SNMPv2 ＆ SNMPv3:**&#x20;

1. 加密傳輸



SNMP 指令:

1. Bulk
2. Walk
3. Next

## 以 iReasoning MIB Browser 實作



> 小心得分享:
>
> 死記硬背理論, 還不如實際應用一回來的印象深刻!


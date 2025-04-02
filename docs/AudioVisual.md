# Audio Visual System

## HDMI
```mermaid
graph TB
    TV["TV<br>BRAVIA KJ-43W730E"]
    SWITCH["Nintendo Switch"]
    AMP["アンプ<br>SONY STR-DH710"]
    BD["BDプレーヤ<br>BDZ-FBT4200"]
    AMATV["Amazon Fire TV Stick 4K"]

    TV-- HDMI1 ---AMP
    TV-- HDMI2 ---SWITCH
    AMP-- HDMI1 ---BD
    AMP-- HDMI2 ---AMATV

    subgraph Wi-Fi
        WiFi24G["Wi-Fi(2.4G)"]
        WiFi5G["Wi-Fi(5G)"]
    end

    TV -..- WiFi24G
    SWITCH -..- WiFi5G
    BD -..- WiFi5G
    AMATV -..- WiFi5G
```

## Audio
```mermaid
graph LR
    AMP["アンプ<br>SONY STR-DH710"]

    subgraph speaker
        direction LR
        S_C["スピーカー(センター)"]
        S_L["スピーカー(L)"]
        S_R["スピーカー(R)"]
        S_BL["スピーカー(リアL)"]
        S_BR["スピーカー(リアR)"]
    end

    AMP---speaker
```

## Nintendo Switch item list

* Joy-Con(R) ネオンレッド
* Joy-Con(L) ネオンブルー
* Joy-Con(R) ネオンオレンジ
* Joy-Con(L) ネオンパープル
* Nintendo Switch Proコントローラー
* リングコン
* フィットボクシング用グリップ * 2
* カラオケ用マイク

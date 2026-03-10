# test
テスト用
```mermaid
flowchart LR

U[ユーザー] --> P[参加手順PDF<br>※代理店様ごとに異なる]

P --> B[BAND]
P --> O[LINEオープンチャット]

B --> O
O --> B

B --> S[公式サイト（WordPress）閲覧PW：pokesa11]

S --> B
S --> O

click S "https://pocket-m.net/p-salon/" "公式サイトを開く"
```

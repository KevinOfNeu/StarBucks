# StarBucks Specification Note

StarBucks Specification note v0.0.1

## 0. 杯型
每家星巴克门店都有四种杯型，分别是 小杯、中杯、大杯、超大杯，对应的意大利文是 short、tall、grande、venti。
在这之外，还有喝浓缩咖啡的 4oz 杯（可以装最多 3 份浓缩咖啡，第 4 份的时候会满出来）。 
菜单版上的杯型和展示用的杯型是从中杯开始的，但热饮均可以点小杯，冰饮没有小杯。小杯的价格在中杯的基础上减去 3 元即可。

![](https://pic2.zhimg.com/80/v2-427385893ac5c18610e83a959ac59185_hd.jpg)

每种杯型对应的容量如下：
 - Short 236ml
 - Tall 355ml
 - Grande 473ml
 - Venti 591ml
 

## 1. 饮品缩写
星巴克得纸杯上面有五个框框。分别是Decaf,Shots,Syrup,Milk,Custom,Drink。

 - Decaf
   低因。如果有些顾客需要用低因豆，就会在框内打个X，代表使用低因咖啡豆出shot，但因为很少很少顾客会要求低因，所以那包低因豆开了到 mark out 通常都用不完，所以这方面建议还是喝浓缩咖啡豆的比较新鲜。

 - Shots
   浓缩咖啡份数。就是要几个shot的问题了。一般手工调制咖啡都是有比例的，热饮除了美式，其他的按杯型从short到venti的shot一般为1，1，2，2。加一个shot4块钱，但有时这个不一定收，看你和partner熟不熟，因为也就咖啡机上一个按键的事。

 - Syrup
   糖水口味，常用点的就c焦糖 v香草 cl原味 h榛果 a杏仁，糖水口味前的数字代表糖水泵数，没数字代表配方默认泵数。一般那些每个季度的promo drink推广饮品，就是在四大基础饮品（拿铁，卡布，焦玛，摩卡，ps本来美式算第五，但是这货点的人不多，
   而且也变不出什么花样来，所以不计入）上加各种口味糖浆和cream变来的，
   till位伙伴一般在糖浆上写个什么糖浆，吧位伙伴就知道是不是当期推广饮品。

 - Milk
   牛奶。就是脱脂奶和豆奶等会标记N或S等。
   
 - Custom
   顾客定制。多点什么就X-**，少点什么就Lt***。
   k代表for kids低温，h代表hot，ice加斜杠代表去冰，l+?代表?少加点，x+？代表？多加，nf代表不要奶泡，cf代表加可可碎片（只有星冰乐可以加）。
   
 - Drink
   这个最基础了，什么饮品写什么。L拿铁，C卡布奇诺，CM焦糖玛其朵，M摩卡，A美式, BC 新鲜调制咖啡, GRTL 抹茶拿铁，星冰乐的话分 CRM 奶油星冰乐，MF摩卡星冰乐，CF 咖啡星冰乐。
   基本都是英文名首字母为主。

## 附录

### 术语
```
X
低咖啡因

1/2
半份咖啡因

R
Ristretto

1
單份Single

2
雙份Double

3
三份Triple

4
四份Quadruple

A
杏仁糖漿

C
焦糖糖漿

CL
經典糖漿

CR
焦糖醬

H
榛果糖漿

MO
摩卡醬、摩卡糖漿

W
濕

WC
鮮奶油

x
Extra額外附加(寫左側）

TN
太妃核果糖漿

V
香草糖漿

/
刪除（覆蓋代碼上方）

LF
低脂牛奶

N
零脂牛奶

S
豆漿

D
乾

F
奶泡

H
熱

K
兒童飲品

Lt
少量（寫左側）

NTH
不要太燙、溫

CR CRM
焦糖奶霜星冰樂

CF
咖啡星冰樂

CRF
焦糖星冰樂

EF
濃縮星冰樂

MF
摩卡星冰樂

T/ MFJ
雙果果汁星冰樂

A
美式咖啡

BC
每日精選咖啡

BLTL
經典紅茶那堤

C
卡布奇諾

CM
焦糖瑪奇朵

E
濃縮咖啡

GRTL
抹茶那提

IC
冰咖啡

L
那堤

M
摩卡

MIS
咖啡密斯朵

BTL
冰搖檸檬紅茶

PTL
冰搖檸檬果茶

GTL
冰搖檸檬綠茶

BT
冰搖紅茶

PT
冰搖果茶

GT
冰搖綠茶

SHC
經典熱巧克力

SM
熱鮮奶

OBT
東方美人茶

RBT
紅玉紅茶

AOT
阿里山烏龍茶

S
小杯240ml 8oz

T
中杯360ml 12oz

G
大杯480ml 16oz

V
特大杯600ml 20oz

C FC CF
焦糖可可碎片星冰樂

FC MF
摩卡可可碎片星冰樂

FC DMF
黑摩卡可可碎片星冰樂

V CRM
香草風味星冰樂

MO CRM
巧克力星冰樂

MO FC CRM
巧克力可可碎片星冰樂

GT CRM
抹茶奶霜星冰樂

RF TL
玫瑰蜜香茶那堤

V L
香草風味那堤

MEF
抹茶咖啡

KHC
兒童熱可可

VNL
香草牛軋糖風味那堤

VNF
香草牛軋糖星冰樂

TNCL
太妃核果風味那堤

TNCF
太妃核果風味星冰樂

TABT
茶瓦納蘋果紅茶

CBIC
冷萃咖啡

CBICM
冷萃咖啡加牛奶

RB
濃萃那堤

BTG
蜜柚紅茶

VSCC
甜香草奶油冷萃咖啡
```

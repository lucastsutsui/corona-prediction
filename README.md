# Predicting the next day value for confirmed cases of covid-19 in some countries.

Evaluating and constructing simple linear regression models to predict the next day number for **confirmed cases** of covid-19 in Italy, Spain, USA, and Brazil.

|                  | Italy | Spain |  USA  | Brazil |
|:----------------:|:-----:|:-----:|:-----:|:------:|
| 3/22 prediction  | 61,280 | 30,220 | 36,702 |  1,502  |
|  3/22 real cases | **59,138** | **28,768** | **33,272** |  **1,593**  |
| 3/23 prediction  | 67,520 | 34,738 | 40,826 |  1,735  |
|  3/23 real cases | **63,927** | **35,136** | **43,847** |  **1,924**  |
| 3/24 prediction  | 72,271 | 41,391 | 58,754 |  2,724  |
|  3/24 real cases | **69,176** | **39,885** | **53,740** |  **2,247**  |
| 3/25 prediction  | 74,193 | 47,498 | 71,377 |  2,935  |
|  3/25 real cases | **74,386** | **49,515** | **65,778** |  **2,554**  |
| 3/26 prediction  | 78,962 | 57,916 | 84,089 |  3,139  |
|  3/26 real cases | **80,589** | **57,786** | **83,836** |  **2,985**  |
| 3/27 prediction  | 84,706 | 73,091 | 105,078 |  3,531  |
|  3/27 real cases | **86,498** | **65,719** | **101,657** |  **3,417**  |
| 3/28 prediction  | 90,941 | 77,689 | 128,144 |  4,006  |
|  3/28 real cases | **92,472** | **73,235** | **121,478** |  **3,904**  |
| 3/29 prediction  | 96,935 | 85,432 | 150,621 |  4,521  |
|  3/29 real cases | **97,689** | **80,110** | **140,886** |  **4,256**  |
| 3/30 prediction  | 102,245 | 92,105 | 160,584 |  4,893  |
|  3/30 real cases | **101,739** | **87,956** | **161,807** |  **4,579**  |
| 3/31 prediction  | 106,044 | 94,074 | 178,578 |  5,167  |
|  3/31 real cases | **105,792** | **95,923** | **188,172** |  **5,717**  |
| 4/1 prediction  | 109,392 | 101,756 | 203,673 |  6,332  |
|  4/1 real cases | **110,574** | **104,118** | **213,372** |  **6,836**  |
| 4/2 prediction  | 113,595 | 109,769 | 234,588 |  7,797  |
|  4/2 real cases | **115,242** | **112,065** | **243,453** |  **8,044**  |
| 4/3 prediction  | 118,109 | 117,753 | 264,329 |  9,296  |
|  4/3 real cases | **119,827** | **119,199** | **275,586** |  **9,056**  |
| 4/4 prediction  | 122,555 | 124,819 | 300,793 |  10,517  |
|  4/4 real cases | **124,632** | **126,168** | **308,850** |  **10,360**  |
| 4/5 prediction  | 127,206 | 131,260 | 337,413 |  11,896  |
|  4/5 real cases | **128,948** | **131,646** | **337,072** |  **11,130**  |
| 4/6 prediction  | 131,541 | 136,493 | 367,522 |  12,756  |
|  4/6 real cases | **132,547** | **136,675** | **366,614** |  **12,161**  |
| 4/7 prediction  | 135,099 | 140,747 | 392,414 |  13,664  |
|  4/7 real cases | **135,586** | **141,942** | **396,223** |  **14,034**  |
| 4/8 prediction  | 137,966 | 145,266 | 420,067 |  15,629  |
|  4/8 real cases | **139,422** | **148,220** | **429,052** |  **16,170**  |
| 4/9 prediction  | 141,420 | 150,903 | 451,185 |  18,145  |
|  4/9 real cases | **143,626** | **153,222** | **461,437** |  **18,092**  |
| 4/10 prediction  | 145,457 | 155,970 | 484,330 |  20,427  |
|  4/10 real cases | **147,577** | **158,273** | **496,535** |  **19,638**  |
| 4/11 prediction  | 151,271 | 160,685 | 519,275 |  22,106  |
|  4/11 real cases | **152,271** | **163,027** | **526,396** |  **20,727**  |
| 4/12 prediction  | 156,265 | 165,240 | 550,870 |  23,104  |
|  4/12 real cases | **156,363** | **166,831** | **555,313** |  **22,192**  |
| 4/13 prediction  | 160,886 | 168,959 | 578,426 |  23,561  |
|  4/13 real cases | **159,516** | **170,099** | **580,619** |  **23,430**  |
| 4/14 prediction  | 163,166 | 172,002 | 602,465 |  24,713  |
|  4/14 real cases | **162,488** | **172,541** | **605,193** |  **25,262**  |
| 4/15 prediction  | 165,834 | 174,265 | 624,606 |  26,296  |
|  4/15 real cases | **165,155** | **177,644** | **636,350** |  **28,320**  |
| 4/16 prediction  | 168,237 | 178,613 | 653,935 |  30,644  |
|  4/16 real cases | **168,941** | **184,948** | **667,801** |  **30,425**  |
| 4/17 prediction  | 171,698 | 185,435 | 684,509 |  33,118  |
|  4/17 real cases | **172,434** | **190,839** | **699,706** |  **33,682**  |
| 4/18 prediction  | 175,349 | 191,701 | 716,817 |  36,541  |
|  4/18 real cases | **175,925** | **191,726** | **732,197** |  **36,658**  |
| 4/19 prediction  | 178,887 | 193,430 | 768,246 |  39,899  |
|  4/19 real cases | **178,972** | **198,674** | **759,086** |  **38,654**  |
| 4/20 prediction  | 181,995 | 199,192 | 778,083 |  42,055  |
|  4/20 real cases | ? | ? | ? |  ?  |

**Average error** = 3.02 %

# Error formula

error = abs(y_predicted - y_real) / y_real

average_error = average(error_i, for each prediction i)

# Dataset source 
[Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19)

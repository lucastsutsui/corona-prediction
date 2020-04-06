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
|  4/6 real cases | ? | ? | ? |  ?  |

**Average error** = 4.31 %

# Error formula

error = abs(y_predicted - y_real) / y_real

average_error = mean(error_i, for each prediction i)

# Dataset source 
[Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19)

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
|  3/30 real cases | ? | ? | ? |  ?  |

**Average error** = 5.59 %

# Error formula

error = abs(y_predicted - y_real) / y_real

average_error = sum(error_i) for each prediction i

# Dataset source 
[Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19)

# 国外航空
>## 亚洲航空
---
### API接口地址
---
**实例URL:**

https://www.airasia.com/flights/zh/cn/wp-json/aa0144/v1/routes/1/continent?get_price=true&max=20&currency_code=CNY&context=destination&page=1

**请求地址：**

https://www.airasia.com/flights/zh/cn/wp-json/aa0144/v1/routes/1/continent?

**参数：**

- get_price=true（是否获取价格）
- max=20 （最大获取折扣数量）
- currency_code=CNY （货币）
- context=destination (未知)
- page=1 （页面数量）

**返回数据格式：**

![json](https://img.shields.io/badge/Data-JSON-brightgreen.svg?style=flat-square "json")

### 跳转URL
---
**实例URL:**

https://www.airasia.com/select/zh/cn/MNL/DMK/2020-03-11/N/1/0/0/O/N/MYR/ST

**请求地址：**

*返回JSON文件中包含跳转地址:JSON.item.0.url*

>## 瑞安航空
---
### API接口地址
---
**实例URL:**

https://www.ryanair.com/api/farfnd/3/oneWayFares?departureAirportIataCode=NRN&language=zh&limit=49&market=zh-cn&offset=0&outboundDepartureDateFrom=2020-03-01&outboundDepartureDateTo=2020-03-31

**请求地址：**

 https://www.ryanair.com/api/farfnd/3/oneWayFares?

**构建参数:** 

- departureAirportIataCode=NRN (国际航空运输协会机场代码)
- language=zh（语言）
- limit=number （显示数量）
- market=zh-cn （面向国家市场）
- offset=0（未知）
- outboundDepartureDateFrom=2020-03-01 （折扣开始时间）
- outboundDepartureDateTo=2020-03-31 （折扣截止时间）

**返回数据格式：**

![json](https://img.shields.io/badge/Data-JSON-brightgreen.svg?style=flat-square "json")

### 跳转URL
---
**实例URL:**

https://www.ryanair.com/cn/zh/cheap-flights/dublin-to-london-southend?out-from-date=2020-03-04&out-to-date=2021-03-04&budget=150

**请求地址：**

https://www.ryanair.com/cn/zh/cheap-flights/

**构建参数:** 
- dublin-to-london-southend :(*对应API请求返回的JSON文件中的 JSON.fares.1.outbound.departureAirport.city.name-to-JSON.fares.1.outbound.arrivalAirport.city.name*)

- out-from-date=yyyy-mm-dd : (*对应API请求返回的JSON文件中的 JSON.fares.1.departureDate*)

- out-to-date=yyyy-mm-dd : (*对应API请求返回的JSON文件中的 JSON.fares.1.arrivalDate*))
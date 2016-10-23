# OOAD-WEEK10
Sequence Diagram

ส่งการบ้าน 5 รูป
* การสนทนาระหว่าง Bella Jacob และ Edward :1 

![](http://www.plantuml.com/plantuml/img/RO_12O0m34NldI8BP04HAO8NjuWsg12hr4hNjz0IKBmbFxptYRqYXNZlOaQQZmcmWvv521gOISIK1NDSxWsGln87Y2l3kHwUZHbSek0KhMHDMyIN4H9jSVDBDRUeOlRksraTFwLgLxdYDa_veGS0)

 ```
@startuml
Jacob -> Bella : call
Bella --> Jacob : answer the phone
Edward -> Bella: call
Edward <-- Bella : call waiting
Bella <- Jacob : end call
Bella --> Edward : answer the phone
Edward <- Bella : end call
@enduml
 ```
* การสั่งของออนไลน์ ระหว่าง Opal Oke และ ไปรษณีย์ :2

![](http://www.plantuml.com/plantuml/img/RP5HZiCW34J_ESLSW0j4rQhT_rLMsbw04hT18IO2KYctNoUGgehwYNcU6Tldb4tCy-XLEnaF_OLs83HeOqSHgNSn9mJsZacjFtebLhB1nTemSyQtuG4yZpTfEAXSe-5qb_eOc1OunkNwezHl45UFazQLIyJTRcOoSayepEPvqgXFGH-KCPbeoMEIMZK-Pji4Fs0rdu15C55yIhm6jYSxVEfuvuu6ZkyXZYQxmFjGWbJY4FJeBCIVUp1r40r4ikIUj4rUcjwYbXszc7rFFfBfbZBvArVkrsiiOLRgB17biFy0)

 ```
 @startuml
Opal -> Oke : Order shirts online
Oke --> Opal : Account Bank number 
Opal -> Oke : Transfer money in ATM

Postal <-- Oke : send shirts at the Postal
Oke <-  Postal : get parcel post number
Oke --> Opal : send parcel post number

Opal --> Postalserver : check parcel post number
Postalserver--> Opal : send information

Postal-->Opal : get parcel post
Opal --> Postal : Signed for receive the parcel

Opal --> Oke :  receive shirts already
Oke -> Opal : thank you

@enduml
 
  ```
* ไปซื้อของที่ห้างสรรพสินค้า :3

![](http://www.plantuml.com/plantuml/img/RP31QiGm34Jl_Wf1ptijT0zbsvIU5xRGisAhiOXZ6rbfwTzN2IGi9JT9ynWDSscAelEKN1ivLnISe4S_3bBc7BgIYi13z_RwylJexf28EVm8gr86bPcSSxLKE9sUmQF06OQY1JGIJ9ZIhYsBYP-OHk1yHDmYfMzg1drn3b2bXDbhs_NjOC2D4dbTBG8r5jhnkomjCYrvkaX-X9xjrNPSxGmymuTPL65FO95wcv73WSSLVpaFwyELFd1wvxGWr_-njr8WbidAkb0ErlaV)


```
@startuml
skinparam backgroundColor #CDBA96

skinparam handwritten true


pop --> car : goto the mall
pop --> mall : Walk into the mall
pop --> Shelves : find products
pop --> products : Select the desired product
pop --> cashier : Check bill
cashier --> pop : The price to be paid
pop --> cashier : Paying the price
cashier --> pop : Filing Products
pop --> car : go home

@enduml
```
* การเข้าfacebook: 4

![](http://www.plantuml.com/plantuml/img/RLBRQiCm37sklyAmvqAphfVrOJHD4zZenc1Vu2PgQn9RcUrGjh5_dvsumKtdXqWwv-X8WgorOSeqeYAwvB9cYWcwPtbvLDZ88i4A5RtBicIIR0B5YSdYhBWn8AbH3P20q_3PWCo1_f1Hh1IUlKcKFawop6AvGRL1LO3op7BpC8kcPBJZ1zXn2GDo6a_ZW1mk5pzkawtr9QDtUmdFUSsakRAOjE-Q7xeaaJqokj9aACqR4z0kkBYVtv0V_1jejBZ1-ysxiPUJXoFJD9qlPvxzfw_7-pazSbch5VuImXn1NxaqYX7IHJf-eWUMmnwnf2lwWbpIpDUa9wp8orSqGNdWIZ33KL8O2yQhq4n_QGF2wYeySaby6HfqHD22TUkrwYBnfILgrCOsk43QtFaRPXfjqIxfyMV1Zc1XxcBWaQCG89sDpmAkugLhSI7iE34hTr_IlJN8mlxxVm00)

```
@startuml
skinparam backgroundColor #FFC0CB
skinparam handwritten true

skinparam sequence {
	ArrowColor #1E90FF
	ActorBorderColor #8B4513
	LifeLineBorderColor #8B3A3A
	LifeLineBackgroundColor #A9DCDF
	
	ParticipantBorderColor #000000
	ParticipantBackgroundColor #C1FFC1
	ParticipantFontName #8B4726
	ParticipantFontSize 17
	ParticipantFontColor #8B0000
	
	ActorBackgroundColor #EEE685
	ActorFontColor #8B0000
	ActorFontSize 17
	ActorFontName #8B0000
}

actor Mintra

Mintra -> facebook : Join Facebook
facebook -> Mintra : Confirmation e-mail

Mintra -> system : login
system -> Mintra : login

Mintra -> option :option
option -> post : post
post -> status : status
post -> Image : image
option -> comment : comment
option -> like : like
option -> chat :chat

@enduml

```


*    :5
 
 ![]()
 
 ```
 
 ```









README.md 
md เป็นภาษา Markdown นิยมใช้ใน wiki ของ github 

ตัวอย่างโค้ด
```
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3
 
```

ผลที่ได้
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3


## Code ภาษาซี

ตัวอย่างโค้ด
<pre>
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
</pre> 
ผลที่ได้
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
 

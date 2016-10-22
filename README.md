# OOAD-WEEK10
Sequence Diagram

ส่งการบ้าน 5 รูป
* การสนทนาระหว่าง Bella Jacob และ Edward

![](http://www.plantuml.com/plantuml/img/RO_12O0m34NldI8BP04HAO8NjuWsg12hr4hNjz0IKBmbFxptYRqYXNZlOaQQZmcmWvv521gOISIK1NDSxWsGln87Y2l3kHwUZHbSek0KhMHDMyIN4H9jSVDBDRUeOlRksraTFwLgLxdYDa_veGS0)


'''

@startuml

Jacob -> Bella : call

Bella --> Jacob : answer the phone

Edward -> Bella: call

Edward <-- Bella : call waiting

Bella <- Jacob : end call

Bella --> Edward : answer the phone

Edward <- Bella : end call

@enduml

'''





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
 

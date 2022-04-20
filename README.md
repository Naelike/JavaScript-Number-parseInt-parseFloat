# JavaScript-Number-parseInt-parseFloat-
การแปลงประเภทข้อมูล ในภาษา JavaScript [ Number, parseInt, parseFloat ]

ในบทนี้ คุณจะได้เรียนรู้เกี่ยวกับการแปลงประเภทข้อมูลในภาษา JavaScript เพื่อแปลงข้อมูลจากอีกประเภทหนึ่งไปยังอีกประเภทที่เราต้องการใช้งาน การแปลงข้อมูลนั้นเป็นสิ่งที่จำเป็นเนื่องจากการเขียนโปรแกรมเราต้องเจอกับข้อมูลหลายประเภท ในบทนี้เราจะพูดถึงการแปลงประเภทข้อมูลพื้นฐานได้แก่ ตัวเลข String และ Boolean นี่เป็นเนื้อหาในบทนี้

การแปลงข้อมูลเป็นตัวเลข
การแปลงข้อมูลเป็น String
การแปลงข้อมูลเป็น Boolean

String หรือค่าใดๆ ในภาษา JavaScript ให้เป็นตัวเลข เราสามารถทำได้โดยใช้สามฟังก์ชันดังต่อไปนี้

Number(): แปลงออบเจ็คใดๆ ให้เป็นตัวเลข
parseInt(): แปลง String ให้เป็นตัวเลขจำนวนเต็ม
parseFloat(): แปลง String ให้เป็นตัวเลขจำนวนเต็มทศนิยม
นี่เป็นตัวอย่างการแปลง String เป็นตัวเลขในภาษา JavaScript โดยการใช้ฟังก์ชันทั้งสาม

# JavaScript
```
console.log("Number");
console.log(Number("12"));
console.log(Number("-1"));
console.log(Number("3.4567"));

console.log("parseInt");
console.log(parseInt("10"));
console.log(parseInt("10.5"));
console.log(parseInt("1.2345"));

console.log("parseFloat");
console.log(parseFloat("3.14"));
console.log(parseFloat("10E5"));
console.log(parseFloat("-1.2345"));
```
# ผลลัพธ์การทำงาน
```
Number
12
-1
3.4567
parseInt
10
10
1
parseFloat
3.14
1000000
-1.2345
```
# Number ผลลัพธ์การทำงาน
```
console.log(Number("1.602E-19"));   // 1.602e-19
console.log(Number("-3.14"));       // -3.14 
console.log(Number("16px"));        // NaN
console.log(Number("abc"));         // NaN
```
# parseInt ผลลัพธ์การทำงาน
```
console.log(parseInt("-5"));        // -5    
console.log(parseInt("16px"));      // 16
console.log(parseInt("abc"));       // NaN
console.log(parseInt("zz123"));     // NaN   
```
# parseFloat ผลลัพธ์การทำงาน
```
console.log(parseFloat("1.25E3"));    // 1250    
console.log(parseFloat("5.5-6.5"));   // 5.5    
console.log(parseFloat("PI=3.14"));   // NaN  
```

# Developer : NaeLike เนไลก์

<img class="rounded" src="http://img.in.th/images/c938fdabdf2a1d4b2deda8ffea4fa189.jpg" width="120" alt="NaeLike"> 

> Naelike เนไลก์

@เว็บไซต์ :+1: Web :  <https://naelike.com> ..! :shipit:
<br>
@ติดตาม :+1: Web :  <https://naelike.com/addmee> ..! :shipit:

TikTok :  <https://www.tiktok.com/@naelike6564>
<br>
Facebook :  <https://web.facebook.com/NaeLikePage>
<br>
Instagram :  <https://www.instagram.com/naelike_ig>
<br>


<a href="https://link.ckpzmc.xyz/dispnae"> 
   <img class="rounded" src="https://i.pinimg.com/originals/1a/9a/f1/1a9af177bdcd0bd93568e59bb7600cbe.png" width="120" alt="NaeLike"> 
   </br>
   <b class="fs-12">Discord คลิก..!</b> 
</a>

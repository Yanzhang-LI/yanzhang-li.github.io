# MakeUP 美咔

> ** An IoT solution to improving cosmetics managing experience**

**<br />![封面 16:9.png](https://cdn.nlark.com/yuque/0/2019/png/154698/1566630812698-2814b579-b049-410b-9ef8-1131be6d6136.png#align=left&display=inline&height=684&name=%E5%B0%81%E9%9D%A2%2016%3A9.png&originHeight=684&originWidth=1215&size=1121409&status=done&width=1215)

<a name="Xtabc"></a>
# Overview
<a name="4F1MK"></a>
## Brief Introduction
MakeUP is an IoT solution which includes hardware product and a Wechat Mini Program, aiming at improving the user experience of managing cosmetics and skin-care products. It tries to solve the pain points and create fluent experience when users sort out, manage and buy cosmetics.<br />It is a course project of _Design of Information Product, taught by Prof. Sun Lingyun_, and I got the highest mark (98 out of 100) for outstanding contribution to the team as well as the course conference.

<a name="TLf0n"></a>
## Highlights

- **Examined the user's pain points and needs under cosmetic-using situation and figured out unique design direction.**
- **Designed the appearance and structure of the product, delivered a half-function prototype with Arduino, Raspberry Pi or so.**
- **Empowered design with Artificial Intelligence, considered the machine-learning lifecycle and tried to avoid to become a bad AI design.**

<a name="NM58R"></a>
## Info
Apr. 2019 - Jun. 2019 | 2.5 months | 6 people

<a name="47KTO"></a>
## My Role

- As group leader, I was responsible for allocating the work, managing group meetings and product development schedule.
- Contributed the main concept of the product, including modularization, main functions and user interaction. Took charge of shooting video of the product.
- Involved in product and user experience design, helping to develop a variable product with my programming and electronic skills.

![image.png](https://cdn.nlark.com/yuque/0/2019/png/154698/1566558583596-81acbc06-f779-4594-838e-d64424e3dd44.png#align=left&display=inline&height=677&name=image.png&originHeight=677&originWidth=2405&size=2358481&status=done&width=2405)

<a name="olh6x"></a>
# 01 Background
At present, people's  pursuit to beauty encourages a rapid growing of the cosmetic and skin-care product market. In 2018, the Chinese market had reached over 400 billions Yuan _(Euromonitor, collated by the China Business Industry Research Institute, 2018)_, and 79% of women would make up and take care of their skin every day _(NetEase Koala, 6279 samples, 2017_). <br />On the one hand, the growing cosmetics industry drives the development of its surrounding markets, thus the storage and management tool to cosmetics has a great potential.<br />On the other hand, there are experience problems among the process of storage, use and management of cosmetics, which means there are design opportunities.<br />

<a name="SR3l1"></a>
# 02 Design Process
<a name="CO2fM"></a>
### 2.1 Collect Design Opportunities
<a name="R6ncv"></a>
#### 2.1.1 From User Perspective
Interviewed 6 women, age from 22 to 36.<br />![用户称述表.png](https://cdn.nlark.com/yuque/0/2019/png/154698/1566658850152-04e7b677-1289-4021-9e30-a53e9af99191.png#align=left&display=inline&height=485&name=%E7%94%A8%E6%88%B7%E7%A7%B0%E8%BF%B0%E8%A1%A8.png&originHeight=485&originWidth=1254&size=106404&status=done&width=1254)

<a name="ir3pP"></a>
#### 2.1.2 From Business Perspective

- **A Serious Waste Of Products & Money**
  - According to a recent study conducted by Vaseline (2014), 77% of women use less than 10 beauty items regularly, despite spending money on about 100 different products over the course of the year.
  - As a result, a woman would waste an average of 5,846 beauty products in their lifetimes, worthing $300,000. Plus, women admitted to only using 10% of the beauty items they buy.
- **A Skin Problem Due To Dirty Tools & Expired Products**
  - Make up tools like beauty eggs, make up brushes, powder puff, need to be cleaned up after every single use. However, over 65% of users would forget to clean it.
  - Over 77% of users never mind if their cosmetics are expired (Nielsen, 2015, covering 21 cities, aged 18-35), which would cause skin problem gradually.

<a name="GGM7N"></a>
#### 2.1.3 Conclusion
According to the above information, there are 3 main aspects we could focus on:

- Cosmetics and skin-care products make users' desk become a chaos, and it is necessary to have a way to sort out and store the products.
- The storage product needs to consider that some cosmetics would require a different storage situation.
- Users need reminder and manager to manage their products, the possible functions may include remind to clean and use, and expiration.

<a name="eEakF"></a>
### 2.2 Narrow It Down - User Research & Business Analysis
<a name="7bHbY"></a>
#### 2.2.1  Persona
Interviewed 23 woman, age from 22-37, online and offline.<br />Analyzed user's scenario, pain points, needs, desire and emotion journey. Also considered about the potential machine learning difficulty.<br />![image.png](https://cdn.nlark.com/yuque/0/2019/png/154698/1566569487990-fb5ede9f-4ca0-4408-a23b-55d07b069de2.png#align=left&display=inline&height=1683&name=image.png&originHeight=1683&originWidth=2592&size=721466&status=done&width=2592)<br />

<a name="WFfn2"></a>
#### 2.2.2 Business Analysis
Compared and analyzed 5 competitive products, ranging from software to hardware. Analyzed their pros and cons including prizes, functions, design reasons, business potential.<br />![image.png](https://cdn.nlark.com/yuque/0/2019/png/154698/1566559962007-3eddffb5-4923-4573-a28a-b7ecdb3f90f7.png#align=left&display=inline&height=849&name=image.png&originHeight=849&originWidth=1920&size=865270&status=done&width=1920)<br />Competitive Products<br />
<br />Currently, cosmetics management products mainly focus on single aspect, such as ordinary storage, low-temperature storage, tool cleaning, etc., which cannot provide users with a better cosmetics experience persistently. Moreover, the product lacks intelligence and cannot provide users with more real-time and intimate reminders and feedbacks, so it cannot solve the deeper problems of cosmetics experience, and users cannot better understand their cosmetic-use situation and their use habits.

<a name="tT2De"></a>
### 2.3 Design Defination
<a name="WZ48y"></a>
#### 2.3.1 Functions Defination
| **Definition** | **Priority** |
| --- | --- |
| Store and sort out cosmetics and skin-care products. | 0 |
| Flexible Storage. | 1 |
| Low-temperature Storage. | 1 |
| Provide expiration situation of products and reminder. | 1 |
| Intelligent or adorable appearance. | 1 |
| Cleaning Reminder. | 2 |
| Use Reminder | 2 |
| Make-up tools disinfection. | 3 |
| Cosmetics Suggestion. | 3 |
| User habits analysis. | 3 |


<a name="BszRF"></a>
#### 2.3.2 Design Goals

- Improve user experience of cosmetics using and management. Solve the pain points and create valuable experience to users.
- Collect user data. The data, such as how do users  use each product, can be used to enhance the product cycle and to provide strong suggestion to related brands and industry.

<a name="iJ4EN"></a>
### 2.4 Design And Iteration
<a name="yWfdu"></a>
#### 2.4.1 Technical Feasibility Analysis
![难点卡片.png](https://cdn.nlark.com/yuque/0/2019/png/154698/1566658870858-fa3679ff-80c0-4343-8432-ef0f5edf0949.png#align=left&display=inline&height=847&name=%E9%9A%BE%E7%82%B9%E5%8D%A1%E7%89%87.png&originHeight=847&originWidth=1269&size=178801&status=done&width=1269)

When we consider the technical problem and the real problem we would like to solve, we use **Machine-Learning Canvas** to help us think thoroughly. It is a new methond introduced by teaching assistants. The canvas can help us rethink about the evrey step where machine-learning gets involved. It also helps us to not only think about the user's needs, but also the machine's needs, such as data, model, algorithm.

![image.png](https://cdn.nlark.com/yuque/0/2019/png/154698/1566571381916-0a81e1a5-2ca0-498b-b535-6a6d61bd7e0d.png#align=left&display=inline&height=243&name=image.png&originHeight=243&originWidth=1230&size=484579&status=done&width=1230)

<a name="RF1CV"></a>
#### 2.4.2 First & Second Version
In the first and the second version of design, we used sketchs, 3D models and rendering to do rapid brainstorm about the design, trying to figure out a perfect appearance and structure to satisfy all the requirements.<br />The most difficult part is to realize the modularization and the cosmectics' detection, which requires user's behaviour can be detected by cameras.<br />![image.png](https://cdn.nlark.com/yuque/0/2019/png/154698/1566571964142-47a1e5e8-c912-4f66-860f-a8db2ed26d44.png#align=left&display=inline&height=234&name=image.png&originHeight=234&originWidth=1429&size=288711&status=done&width=1429)

After exploring the possibilities, we decided to completely change the appearance and structure design. We refered to IKEA SKADIS series, trying to put the wall-mounted way into our design. 

<a name="lFQ6S"></a>
#### 2.4.3 Design
![Design_1.png](https://cdn.nlark.com/yuque/0/2019/png/154698/1566658900770-f279b759-5340-4d4c-89a6-d9766857007d.png#align=left&display=inline&height=1416&name=Design_1.png&originHeight=1416&originWidth=2144&size=3646873&status=done&width=2144)![Design_2.png](https://cdn.nlark.com/yuque/0/2019/png/154698/1566658899910-f2b0afa6-cdd0-4f21-bae1-a8bbb00fc48e.png#align=left&display=inline&height=1168&name=Design_2.png&originHeight=1168&originWidth=2206&size=665753&status=done&width=2206)
<a name="iFISl"></a>
### 2.5 Prototyping
<a name="2LQar"></a>
#### 2.5.1 Electronic Implementation
To realize necessary functions, we used Arduino, Raspberry Pi and other electronic components to try to realize the low-temperature storage function and the cosmetics detection function.<br />![电路图.png](https://cdn.nlark.com/yuque/0/2019/png/154698/1566630843184-30326e35-edc3-4f60-b883-0d786d3d560b.png#align=left&display=inline&height=407&name=%E7%94%B5%E8%B7%AF%E5%9B%BE.png&originHeight=1510&originWidth=1429&size=304764&status=done&width=385)![电路实现照片.png](https://cdn.nlark.com/yuque/0/2019/png/154698/1566630843289-c9f95308-4ef1-408e-b7d6-1dca547b7608.png#align=left&display=inline&height=243&name=%E7%94%B5%E8%B7%AF%E5%AE%9E%E7%8E%B0%E7%85%A7%E7%89%87.png&originHeight=243&originWidth=1230&size=604864&status=done&width=1230)

<a name="rgOmz"></a>
#### 2.5.2 Structure Implementation
Based on the electronic components and the appearance, we used sketch and 3D modeling to implement structure design. Then, with CNC and 3D-printing, we build the prototype.<br />![image.png](https://cdn.nlark.com/yuque/0/2019/png/154698/1566631913421-e1ffa787-3f70-4f57-8a6b-1594b37cb3de.png#align=left&display=inline&height=436&name=image.png&originHeight=436&originWidth=1429&size=530601&status=done&width=1429)

<a name="pzOd2"></a>
#### 2.5.3 AI Implementaition
![image.png](https://cdn.nlark.com/yuque/0/2019/png/154698/1566633569314-c7c535dc-e57f-42a5-9f03-e6f716ece542.png#align=left&display=inline&height=339&name=image.png&originHeight=339&originWidth=1188&size=345148&status=done&width=1188)<br />We used Python and TensorFlow Object Detection API Faster RCNN to train our cosmetics ML models and achieved basic detection.

<a name="wRJA2"></a>
#### 2.5.3 Prototype
![image.png](https://cdn.nlark.com/yuque/0/2019/png/154698/1566631945408-e4709db7-6042-427c-b931-270d2d56f78f.png#align=left&display=inline&height=1125&name=image.png&originHeight=1125&originWidth=1999&size=2836632&status=done&width=1999)


<a name="eo0JG"></a>
# 3 Design Output
Background Introduction Video [https://youtu.be/0mI1tX5Wizk](https://youtu.be/0mI1tX5Wizk)<br />Product Introduction Video [https://www.youtube.com/watch?v=poc4QVoUWYU](https://www.youtube.com/watch?v=poc4QVoUWYU)<br />Digital Information Product Conference, ZJU.  [https://v.qq.com/x/page/s0894xcqbnv.html](https://v.qq.com/x/page/s0894xcqbnv.html)

Behind-the-scenes<br />![image.png](https://cdn.nlark.com/yuque/0/2019/png/154698/1566632424407-8cd1bae5-381b-4932-b44d-df647f7e08b9.png#align=left&display=inline&height=498&name=image.png&originHeight=498&originWidth=1211&size=965330&status=done&width=1211)<br />**
<a name="isQka"></a>
# 4 Conclusion & Take Away
_Design of Information Product_ is one of the core courses in my major, and it is also the most difficult one, since each group was required to deliver a prototype on the conference at the end of the semester. In order not to be humiliated on the conference facing hundreds of audience, the concept, design and prototpe must be practical, inspiring and commercially-valuable.<br />From my perspective, makeUP is not a perfect work, but it has some shiny points. We built the concept by user research and business analysis and iterated many times through collecting more information and combining the concept with the technical feasibility. Also, we realized part of the functions by our own knowledge including prototype building (Arduino, 3D-printing, Structure Design), programming (C, Python, JavaScript). What's more, the conference also demands us to have a great presentation skill as well as video-shooting and editing skill. During the whole process, our team almost crashed down for the difficulty many times but finally adjusted ourselves and carried out the work.<br />
<br />


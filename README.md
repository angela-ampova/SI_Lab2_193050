# SI_Lab2_193050

Втора лабораториска вежба по Софтверско инженерство

Ангела Ампова, 193050

Control Flow Graph

![3](https://user-images.githubusercontent.com/81112781/119901326-0fe1bc00-bf46-11eb-9984-6821fa50d787.png)

Цикломатска комплексност

Цикломатската комплексност на графот е 8. Тоа се забележува на три начини: 
1)	Според бројот на региони, кој е еднаков на 8
2)	Според формулата:
V(G) = E – N + 2
V(G) = 26 – 20 + 2 = 8
-Каде што Е е бројот на врски, а N е бројот на јазли во графот
3)	Според друга формула:
V(G) = P + 1
V(G) = 7 + 1 = 8
-Каде што P е бројот на предикатни јазли, кои во CFG се B2, C, D, G, H, J, M. 

Multiple Condition 

If(hr<0 || hr>24)

![image](https://user-images.githubusercontent.com/81112781/119901360-1c661480-bf46-11eb-978e-13a1bb19b7c6.png)

If(min<0 || min>59)

![image](https://user-images.githubusercontent.com/81112781/119901369-1f610500-bf46-11eb-8297-e989fc63545c.png)

If(sec>=0 && sec<=59)

![image](https://user-images.githubusercontent.com/81112781/119901375-21c35f00-bf46-11eb-80a5-d7bc36edf5b9.png)

If(hr==24 && min==0 &&sec==0)

![image](https://user-images.githubusercontent.com/81112781/119901385-2425b900-bf46-11eb-8e3b-0355de4c07b0.png)


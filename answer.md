# Задача 1    
**1.1.** Ответ: 2, это первое значение, которое в логическом контексте даст true.  

**1.2.** Ответ: сначала 1, затем 2.  
alert( alert(1) || 2 || alert(3) );  
Вызов alert не возвращает значения, или, иначе говоря, возвращает undefined.  
Первый оператор ИЛИ || выполнит первый alert(1).  
Получит undefined и пойдёт дальше, ко второму операнду в поисках истинного значения.  
Так как второй операнд 2 является истинным, то вычисления завершатся, результатом undefined || 2 будет 2, которое будет выведено внешним alert( .... ).  
Второй оператор || не будет выполнен, выполнение до alert(3) не дойдёт, поэтому 3 выведено не будет.  

**1.3.** Ответ: null, потому что это первое «ложное» значение из списка.  

**1.4.** Ответ: 1, а затем undefined.  
alert( alert(1) && alert(2) );  
Вызов alert не возвращает значения, или, иначе говоря, возвращает undefined.  
Поэтому до правого alert дело не дойдёт, вычисления закончатся на левом.  

**1.5**. Ответ: 3.  
alert( null || 2 && 3 || 4 );  
Приоритет оператора && выше, чем ||, поэтому он выполнится первым.  
Результат 2 && 3 = 3, поэтому выражение приобретает вид:  null || 3 || 4  
Теперь результатом является первое истинное значение: 3.  

# Задача 2    
![image](https://user-images.githubusercontent.com/113675674/210324147-85f4c817-4bd9-4d2e-b607-053a42090e91.png)  
В JavaScript, переменная **a** будет пустой строкой, переменная **b** будет числом 7, переменная **c** будет числом 1, а переменная **d** будет числом 2.  
Оператор **||** в JavaScript возвращает первое "истинное" значение в выражении.  
В данном случае, **a || c** будет возвращать **''** , которое считается "ложным" значением в javascript, поэтому оно будет возвращать **c** , которое равно 1.  
**b || d** будет возвращать **b** , которое равно 7, потому что это считается "истинным" значением.  
Таким образом, все выражение **a||c && b||d** будет возвращать **1 && 7**, что равно 7. 
**Результатом будет 7, потому что b является первым "истинным" значением в выражении. **   


# Задача 3    
Код выведет значение переменной c – первое значение из списка, которое может быть преобразовано в false.  
![image](https://user-images.githubusercontent.com/113675674/210324278-f3513598-5a41-4c04-b40e-86d486fc823f.png)

# Задача 4   
![image](https://user-images.githubusercontent.com/113675674/210323926-4fd76528-a205-4056-bf4d-8376d11be70d.png)  

# Задача 5   
![image](https://user-images.githubusercontent.com/113675674/210324045-41c89e3f-7da2-44a5-aa92-173bf6a4e95e.png)  


# Задача 6    
![image](https://user-images.githubusercontent.com/113675674/210324968-8398a8f1-d706-4c5c-937e-1ec4c330e33b.png)  

# Задача 7    
 ![image](https://user-images.githubusercontent.com/113675674/210325018-8e7ed906-1b7e-4e53-a38f-27599a9d6a7d.png)  

# Задача 8    
![image](https://user-images.githubusercontent.com/113675674/210325075-be2105ad-0d3b-484f-98c4-a742f064e6fe.png)  

# Оператор нулевого слияния   
## Задача 1  
![image](https://user-images.githubusercontent.com/113675674/210326519-c9d39851-5a41-42e4-b2dd-bcfa2757534d.png)  
 
## Задача 2  
![image](https://user-images.githubusercontent.com/113675674/213422312-8fff3a18-2500-436e-be76-32871e096425.png)   

## Задача 3  
![image](https://user-images.githubusercontent.com/113675674/213422398-c0f8f8e6-ff0d-4f65-bf58-40c1d0efd27d.png)  


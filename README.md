# 7.5_Golang_Aleksandr_Molokov

## ЗАДАНИЕ 1

Установка Golang

sudo apt install golang

версия

![Установка и версия golang](https://user-images.githubusercontent.com/109212419/209213114-55178ea2-0a39-4fca-8866-f80af4cec027.jpg)


## ЗАДАНИЕ 2

Ознакомился с материалами по ссылке https://tour.golang.org/

## ЗАДАНИЕ3

ЗАДАЧА 1

 Напишите программу для перевода метров в футы (1 фут = 0.3048 метр). Можно запросить исходные данные 
у пользователя, а можно статически задать в коде.
    Для взаимодействия с пользователем можно использовать функцию `Scanf`:
    ```
    package main
    
    import "fmt"
    
    func main() {
        fmt.Print("Enter a number: ")
        var input float64
        fmt.Scanf("%f", &input)
    
        output := input * 2
    
        fmt.Println(output)    
    }
  
  ## ОТВЕТ
  
Код
 
![Задание 1](https://user-images.githubusercontent.com/109212419/209216734-6e223709-01b4-437f-884f-aae78bcbdd64.jpg)

Демонстрация

![Задание 1-1](https://user-images.githubusercontent.com/109212419/209216837-df115a8f-6d5e-4895-971e-398cae15500c.jpg)

  
ЗАДАЧА 2

Напишите программу, которая найдет наименьший элемент в любом заданном списке, например:
    ```
    x := []int{48,96,86,68,57,82,63,70,37,34,83,27,19,97,9,17,}
    
## ОТВЕТ    

Код

![код задание 2](https://user-images.githubusercontent.com/109212419/209396951-ac336a9a-1009-4aea-833d-a993edcfc90c.jpg)

Демонстрация

![вывод задание 2](https://user-images.githubusercontent.com/109212419/209396972-93b92c79-1e4f-4018-9b47-12a55cc750d4.jpg)


ЗАДАЧА 3

Напишите программу, которая выводит числа от 1 до 100, которые делятся на 3. То есть `(3, 6, 9, …)`.

В виде решения ссылку на код или сам код. 

## ОТВЕТ

Код

![код задание 3](https://user-images.githubusercontent.com/109212419/209403269-9009930c-08bf-468e-a2cd-0108002c79de.jpg)

Демонстрация

![результат задание 3](https://user-images.githubusercontent.com/109212419/209403280-db25c061-44b3-41bc-8fed-91c422d7b1a0.jpg)


# Домашнее задание к занятию "Testability, авто-тесты, введение в ООП: объекты и методы"

## Case1
**BonusMilesService.java**
```java
package Case1;

public class BonusMilesService {
    public int calculate(int price) {
        return price / 20;
    }
}
```
**Main.java**
```java
package Case1;

public class Main {
    public static void main(String[] args) {
        BonusMilesService service = new BonusMilesService();
        int price = 10_000;
        int miles = service.calculate(price); // должно получиться 500
        System.out.println("Количество бонусных миль: " + miles);
    }
}
```
**Результат**
```
Количество бонусных миль: 500
```


### Файлы с кодом можно посмотреть в [папке](https://github.com/AngryCFO/Testability/tree/main/src)


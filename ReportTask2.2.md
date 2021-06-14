# Ошибка при расчете суммарного бонуса

### В представленном коде реализована функция сложение основного и дополнительного бонусов.

15.06.2021 - 15.06.2021 было проведено функциональное тестирование представленного кода.

На тестирование затрачено: 1 час.

### В результате тестирования выявлены следующие дефекты:

* [Ошибка при расчете суммарного бонуса](https://github.com/leonidbeltsov/JavaTask2.2/issues/1)

### Описание процесса тестирования

#### Входные данные:

```public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
```
#### Ожидаемый результат:  

* Выведенное значение переменной *totalBonus* соответствует математической сумме значений переменных *regularBonus* и *specialBonus*

#### Фактический результат:
* Выведенное значение переменной *totalBonus* не соответствует математической сумме значений переменных *regularBonus* и *specialBonus*

#### Тестирование производилось в следующем окружении:
* Windows 10 Домашняя (x64)  
  Версия  21H1  
  Сборка ОС	19043.1052  

* openjdk version "11.0.11" 2021-04-20  
  OpenJDK Runtime Environment AdoptOpenJDK-11.0.11+9 (build 11.0.11+9)  
  OpenJDK 64-Bit Server VM AdoptOpenJDK-11.0.11+9 (build 11.0.11+9, mixed mode)  

* IntelliJ IDEA 2021.1.2 (Community Edition)  
  Build #IC-211.7442.40, built on June 1, 2021  
  Runtime version: 11.0.11+9-b1341.57 amd64
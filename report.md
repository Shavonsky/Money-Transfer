# Отчёт о тестировании Money Transfer
## Краткое описание
18.08.20 - 18.08.2020 было проведено Sanity Tasting приложения Money Transfer.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:

- https://github.com/Shavonsky/Money-Transfer/issues/1
## Описание процесса тестирования



В качестве тестовых данных использовались данные https://github.com/netology-code/javaqa-homeworks/tree/master/programming:

```
class main {
public static void main(String[] args){
        int balance=2_000_000_000;
        int transfer=500_000_000;
        int total=balance+transfer;
        System.out.println(total);
        }
}
```

Тестирование производилось в следующем окружении:

- Windows 7, 64-bit
- Java version "11.0.8" 2020-07-14
# Побитови операции

| Оператор | Значение | Тип |
| :---: | :---: | :---: |
| `&` | Побитово **и** | инфиксен, бинарен|
| `\|` | Побитово **или** | инфиксен, бинарен|
| `~` | Побитово **не** | префиксен, унарен|
| `<<` | Побитове отместване наляво | инфиксен, бинарен|
| `>>` | Логическо отместване надясно | инфиксен, бинарен|


```cpp
int x = 7;     // 0b110
int y = 5;     // 0b101
int op1 = x&y; // 0b100
int op2 = x|y; // 0b111
int op3 = ~x;  // 0b001
int op4 = x<<2;// 0b11000
int op5 = x>>2;// 0b1__
```
<slidebreak/>

- Основни побитови операции
    - Проверка дали число е четно
    - Пресмянане 2 на степен k
    - Взимане на стойност на бит
    - Задаване на стойлност на бит
    - Toggle на бит

<slidebreak/>

- Основни приложения
    - Четност на срещане на число (свойство на XOR)
    - Подмножества - генериране на индикаторна функция (свойство на последователните двоични числа)
    - Оптимизация на мястото за съхранение - напр. съхранение на булева информация

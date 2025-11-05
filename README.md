# Домашнее задание к работе 7

## Условие задачи

## 1. Алгоритм и блок-схема
### Алгоритм
1. **Начало**
2. Ввести число от 1 до 12
   -int n
   -scanf("%d", &n);
3. Вывод результата:
   -switch (n) {
   case n: 
   -printf
   break;
4. **Конец**

## 2. Реализация программы
#include <stdio.h>
#include <locale.h>

int main() {
	setlocale(LC_CTYPE, "");
	int n;
	printf("Введите число от 1 до 12: "); 
  scanf("%d", &n);
	switch (n) {
	case 1: printf("I\n"); 
		break; 
	case 2: printf("II\n"); 
		break; 
	case 3: printf("III\n"); 
		break; 
	case 4: printf("IV\n"); 
		break; 
	case 5: printf("V\n");
		break; 
	case 6: printf("VI\n");
		break;
	case 7: printf("VII\n"); 
		break;
	case 8: printf("VIII\n");
		break;
	case 9: printf("IX\n");
		break;
	case 10: printf("X\n"); 
		break;
	case 11: printf("XI\n"); 
		break;
	case 12: printf("XII\n"); 
		break;
	default: printf("Ошибка: число вне диапазона 1-12\n");
	}
	system("pause");
	return 0;
}

## 3. Результаты работы программы
Введите число от 1 до 12: 4
IV
Для продолжения нажмите любую клавишу . . .

## 4. Информация о разработчике
Чумачек Владислав, бИЦ-252

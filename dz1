# dz1
#include <locale.h>

#include <stdio.h>

void main()

{
	setlocale(LC_ALL, "RUS");
	puts("                 ---------------------");
	puts("                |                     |");
	puts("               |                       |");
	puts("              |                         |");
	puts("             |                           |");
	puts("            |                             |");
	puts("           |                               |");
	puts("          |                                 |");
	puts("         |                                   |");
	puts("        |-------------------------------------|");
	puts("        |                                     |");
	puts("        |                                     |");
	puts("        |                                     |");
	puts("        |            |-----------|            |");
	puts("        |            |           |            |");
	puts("        |            |           |            |");
	puts("        |            |           |            |");
	puts("        |            |           |            |");
	puts("        |            |-----------|            |");
	puts("        |                                     |");
	puts("        |                                     |");
	puts("        |                                     |");
	puts("        |-------------------------------------|");
}





dz2
#include <stdio.h>
#include <stdlib.h>
#include <locale.h>
int main()
{
	setlocale(LC_CTYPE, "RUS");
	printf("123\n");
	printf("1\n2\n3\n");

	printf("\t%3d\n\t%3d\n\t%3d\n\t%3d\n", 1, 2, 3, 4);
	printf("%10.5f\n ", 12.234657);
	printf("Остаток от деления %d на %d равен %d\n", 5, 2, 5 % 2);
	printf("Деление 7 на 5 = %d\n", 7 / 5);
	printf("Умножение 2000 на 4 = %d\n", 2000 * 4);
	printf("%d разделить %d равно %d\n", 5, 2, 5 / 2);
	printf("%f разделить %f равно %f\n", 5.0, 2.0, 5.0 / 2.0);
	printf("%g разделить %g равно %g\n", 5.0, 2.0, 5.0 / 2.0);
	printf("%e разделить %e равно %e\n", 5.0, 2.0, 5.0 / 2.0);

	int N, K;
	N = 1;
	K = 2;
	printf("Сейчас %d часов %d минут 00 секунд\n", N, K);
	printf("Идет %d минута суток\n", N * 60 + K);
	printf("До полуночи осталось %d часов и %d минут\n", 23 - N, 60 - K);
	printf("С 8.00 прошло %d секунд\n", N * 3600 + K * 60);
	printf("Текущий час = %f суток и текущая минута = %f часа\n", (float)N / 24, (float)K / 60);

	double n, l, result;
	int k, m;
	l = 133;
	n = 2;
	k = 3;
	m = 7;
	result = n / l;
	printf("%*s\n", k + m + 3, "Данные");
	printf("%*s\n", k + m + 3, "n = 2");
	printf("%*s\n", k + m + 3, "l = 133");
	printf("%*s\n", k + m + 3, "k = 3");
	printf("%*s\n", k + m + 3, "m = 7");

	printf("%-*s\n", k + m + 3, "Результат");
	printf("%-*.*f\n", k + m + 3, m, result);
}



dz3
#include <stdio.h>
#include <locale.h>
#define D_ENGLISH 2.54
#define D_SPANISH 2.32166
#define D_OLD 2.7076
int main() {
    setlocale(LC_CTYPE, "RUS");
    int num;
    int num2;
    
    printf("Введите первое число: ");
    scanf("%d", &num);

    printf("Введите второе число: ");
    scanf("%d", &num2);

    printf("Сумма: %d\n", num + num2);
    printf("Разность: %d\n", num - num2);
    printf("Произведение: %d\n", num * num2);

    
    int dym;
    float result_en, result_sp, result_old;
    printf("Введите значение в дюймах: ");
    scanf("%d", &dym);

    result_en = dym * D_ENGLISH;
    result_sp = dym * D_SPANISH;
    result_old = dym * D_OLD;

    printf("%d дюймов - это %.2f см (английский дюйм)\n", dym, result_en);
    printf("%d дюймов - это %.5f см (испанский дюйм)\n", dym, result_sp);
    printf("%d дюймов - это %.4f см (старолитовский дюйм)\n", dym, result_old);


    int a, b;
    printf("Введите значение числа a: ");
    scanf("%d", &a);
    printf("Введите значение числа b: ");
    scanf("%d", &b);

    printf("                               \n");
    printf("|%7s|%7s|%7s|\n", "a * b", "a + b", "a - b");
    printf("-------------------------------\n");
    printf("|%3.d*%3.d|%3.d*%3.d|%3.d*%3.d|\n", a, b, a, b, a, b);
    printf("-------------------------------\n");
    printf("|%7.0d|%7.0d|%7.0d|\n", a * b, a + b, a - b);
    printf("-------------------------------\n");



    int day, day2, month, month2, year, year2;
    printf("Введите текущую дату(день, месяц, год)");
     scanf("%d %d %d", &day, &month, &year);
    printf("Введите дату рождения(день, месяц, год)");
     scanf("%d %d %d", &day2, &month2, &year2);
    printf("Ваш возраст: %d лет\n", year - year2);
    return 0;
}

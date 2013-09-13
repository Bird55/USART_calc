USART_calc
==========

Программа сложения 2х чисел
Числа вводятся в программе-терминале на PC, туда-же идет и вывод резудьтата.
Используются библиотека newlib_stabs, функции printf, scanf
Программа может работать с USART1, USART2 и USART3

Замечание: Для ввода используется функция scanf, которая считает пробел концом
строки. Сейчас при вводе пробела, происходит рассинхронизация ввода вывода (я
так думаю), и на ввод лезет мусор с терминала. Пока это не поборол, нет пока 
необходимости. 

The program for adding 2x numbers
The numbers are entered in the program-terminal on the PC, there is the same and
the result output. Use the library newlib_stabs and functions printf, scanf
The program can work with USART1, USART2 and USART3

Note: The function scanf is used for input, which believes that the gap is the end
of the line. Now when you enter a space symbol, this desync input output (I
think) and climbs to enter the trash from the terminal. I resisted as long as it is not,
is not yet necessary.

Источник http://www.embedds.com/programming-stm32-usart-using-gcc-tools-part-1/

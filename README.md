### Розберемо як зробити програму з циклами,яка малює трикутник
###  /* Треугольник из звездочек */

 ### #include <stdio.h>
###    /* Печать n символов c */
###    printn(c, n){
  ###          while( --n >= 0 )
   ###                 putchar(c);
   ### }
 ###   void main(argc, argv) char *argv[];
 ###   {
 ###           register int nline;  /* номер строки */
   ###         register int naster; /* количество звездочек в строке */
   ###         register int i;
###            if( argc > 1 )
  ###           for( nline=0; nline < lines ; nline++ ){
 ###                   naster = 1 + 2 * nline;
  ###                  /* лидирующие пробелы */
  ###                  printn(' ', lines-1  - nline);
  ###                  /* звездочки */
  ###                  printn('*', naster);
   ###                 /* перевод строки */
   ###                 putchar( '\n' );
  ###          }
 ###           exit(0);        /* завершение программы */
###    }
    

![cycles1](Снимок.PNG)
    
![cycles2](сс.PNG)
### Команди компіляції
[file](#help.txt)

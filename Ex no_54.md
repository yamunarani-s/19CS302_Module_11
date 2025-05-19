## print all the letters of the English alphabet.

SAMPLE OUTPUT : CAPS and add space to each alphabet

A B C D E F G H I J K L M N O P Q R S T U V W X Y Z

CODE:
#include <stdio.h>

void printAlphabets() {
    char ch;
    for (ch = 'A'; ch <= 'Z'; ch++) {
        printf("%c ", ch);
    }
}
OUTPUT:
A B C D E F G H I J K L M N O P Q R S T U V W X Y Z

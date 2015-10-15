#include <stdio.h>
 
int main()
{
  char ch;
  scanf("%c", &ch);
 
  if (ch == 'a' || ch == 'A' || ch == 'e' || ch == 'E' || ch == 'i' || ch == 'I' || ch =='o' || ch=='O' || ch == 'u' || ch == 'U')
    printf("%c-Vowel", ch);
  else
    printf("%c-Not a Vowel", ch);
 
  return 0;
}

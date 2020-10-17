#include <stdio.h>

int is_simple (int number);
int main()
{
  long int number;
  
  scanf ("%li", & number);
  printf ("%d", is_simple (number));

  return 0;
}

int is_simple (int number)
{
  if (number > 1)
  {
    for (int i = 2; i < number; i++)
    {
      if (number % i == 0)
      {
        return 0;
      }
    }
    return 1;
  }
  else
  {
    printf ("the number you entered must be natural \n");
  }

  return 0;
}

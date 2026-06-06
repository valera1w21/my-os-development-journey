1) #include <stdio.h> tells C to include a header file. 

2) main() is a special function. Your program starts running here. Any code inside the curly brackets {} will be executed.

3) printf() is a function used to output (print) text to the screen. In our example, it prints Hello World!.

4) return 0 ends the main() function and sends a value back to the operating system,
Returning 0 usually means "everything worked". 

!!!Do not forget the closing curly bracket } to end the main() function.!!!

--------------------note--------------------------
Every C statement ends with a semicolon ;

The body of int main() could also be written as:
int main(){printf("Hello World!");return 0;}
__________________________________________________


----------main.c----------
#include <stdio.h>

int main() {
  printf("Hello World!");
  return 0;
}
__________________________
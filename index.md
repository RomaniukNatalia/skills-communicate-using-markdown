# This is an `<h1>` header, which is the largest

## This is an `<h2>` header

### This is an `<h3>` header

#### This is an `<h4>` header

##### This is an `<h5>` header

###### This is an `<h6>` header, which is the smallest

# Activity: Adding an image
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

# Activity: Adding a code example
```c
#include <string.h> //strcpy()
#include <stdio.h> //printf()

#define MAXSTRING 100

int main(void){
  char c = 'a', *p, s[MAXSTRING];
  p = &c;
  printf("%c%c%c ", *p, *p + 1, *p + 2);
  strcpy(s, "ABC");
  printf("%s %c%c%s\n", s, *s + 6, *s + 7, s + 1);
  strcpy(s, "she sells sea shells by the seashore");
  p = s + 14;
  for( ; *p != '\0'; ++p){
    if(*p == 'e') *p = 'E';
    if(*p == ' ') *p = '\n';
  }
  printf("%s\n", s);
  return 0;
}
```
# Activity: Add a task list
- [ ] Turn on GitHub Pages
- [ ] Outline my portfolio
- [ ] Introduce myself to the world

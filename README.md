_hello_@**everyone** $ cat about_me.c

```c
#include <stdio.h>

int greetings(void){
	printf("Hello!, I'm Kanzen \n");
	return 0;
}

int langs(void){
	printf("I create programs using the... \n");
	printf("C programming language 🇨 \n");
    	printf("Nix ❄️ \n");
    	printf("Shell Script 🐚 \n");
    	printf("Lua 🌕 \n\n");
    	printf("I use tools like this to do my projects: \n");
	printf("neovim \n"
	       "git \n"
	       "vscode \n"
	       "zsh \n"
	       "nix-shell \n");
    	printf("Be free and open-source to see my projects ❤️ \n");
	return 0;
}

int main(void){
	greetings();
      	langs();
      	return 0;
}
```

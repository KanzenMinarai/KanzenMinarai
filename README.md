_hello_@**everyone** $ cat about_me.c

```c
#include <stdio.h>

int greetings(void){
	printf("Hello! 👋, I'm Kanzen \n");
	return 0;
}

int langs(void){
	printf("I create programs using the... \n"
	       "C programming language 🇨 \n"
    	       "Nix ❄️ \n"
    	       "Shell Script 🐚 \n"
    	       "Lua 🌕 \n\n"
    	       "I use tools 🧰 like this to do my projects: \n"
	       "neovim 📝 \n"
	       "git 🐱 \n"
	       "vscode ✍️ \n"
	       "zsh 🖥️ \n"
	       "nix-shell ❄️🐚 \n"
    	       "Be free and open-source to see my projects ❤️ \n");
	return 0;
}

int main(void){
	greetings();
 	langs();
	return 0;
}
```

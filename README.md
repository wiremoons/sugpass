# Summary for `sugpass`

A small application that suggests passwords using a pool of English three letter words.

## About

`sugpass` - short for '*suggest password*' is a password creation tool which uses a pool 
of three letter english words to generate password suggestions. The three letter words 
are randomly selected from the pool, creating password suggestions and displaying them 
on the screen for the user to select from.

It is written in c, and is a command line / terminal based
program, that has a Curse interface. It runs on Windows, Mac and Linux.

A three letter English word list of over 1,000 words was acquired for use in the application, 
from the Association of British Scrabble Players (ABSP) web page is here: http://www.absp.org.uk/words/3lw.shtml

## Building the Application

A c compiler will be needed to build the application, a long with the curses or ncurses library.

Compile with: `gcc -Wall --std=gnu11 -o sugpass sugpass.c -lncurses` or use
the provided 'Makefile'.

## License

The program is licensed under the "MIT License" see
http://opensource.org/licenses/MIT for more details.

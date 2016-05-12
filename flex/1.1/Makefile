#

all: my_wc


my_wc: lex.yy.c
	gcc lex.yy.c -lfl -o my_wc
   

lex.yy.c: word_count.l
	flex word_count.l
  
clean:
	rm lex.yy.c my_wc
	

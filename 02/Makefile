TOUT:=mstat maccess ls

tout: ${TOUT}

%: %.c
	gcc -Wall -Werror -ansi -pedantic -D_XOPEN_SOURCE=500 -g -o $@ $<

clean:
	rm ${TOUT}

.PHONY: tout clean

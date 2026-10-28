# Sourov Ahmad

Backend developer in Italy. Years of web work behind me, C in front of me.

```makefile
# Makefile — builds one developer, from source. No binaries shipped.

NAME     = sourov
CC       = curiosity
CFLAGS   = -Wall -Wextra -Werror -fno-shortcuts
LOCATION = Italy

SRC      = years_of_php.c \
           javascript_frontends.c \
           go_backends.c \
           rust_experiments.c \
           c_from_scratch.c   # current: pointers, memory, no libc

all: $(NAME)

$(NAME): $(SRC)
	$(CC) $(CFLAGS) $(SRC) -o $(NAME)
	@echo "builds clean. reads clean. ships."

clean:
	rm -f hype shortcuts unread_tutorials

rebuild: clean all   # has run more than once. works every time.

giving_up:
	@echo "make: *** No rule to make target 'giving_up'.  Stop."

.PHILOSOPHY: boring tools that work > new tools that impress
```

```console
$ make giving_up
make: *** No rule to make target 'giving_up'.  Stop.
```

## Work

| | |
|---|---|
| [C from scratch](https://github.com/Sourovahmad/exercies) | 42 Piscine. Every exercise written by hand: strings, pointers, memory, recursion. |
| [signal-zero-app](https://github.com/Sourovahmad/signal-zero-app) | Deterministic orbital emergency simulator, desktop and web. |
| [sourov.info](https://sourov.info) | Personal site. |

## Elsewhere

[Website](https://sourov.info) · [LinkedIn](https://www.linkedin.com/in/sourov-ahmad-50574120a/) · [YouTube](https://www.youtube.com/@airovs) · [Email](mailto:sourov.okk3@gmail.com)

<sub>No badges, no widgets, no animations. This page needs nothing but Markdown, so it will look the same in ten years. `make rebuild` whenever necessary.</sub>

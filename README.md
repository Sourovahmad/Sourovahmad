# Sourov Ahmad

Backend developer in Italy. Years of web work behind me, C in front of me.

```c
/* ************************************************************************** */
/*                                                                            */
/*                                                        :::      ::::::::   */
/*   sourov.c                                           :+:      :+:    :+:   */
/*                                                    +:+ +:+         +:+     */
/*   By: sourov <sourov.okk3@gmail.com>             +#+  +:+       +#+        */
/*                                                +#+#+#+#+#+   +#+           */
/*   Created: 2020/04/28 12:13:19 by sourov            #+#    #+#             */
/*   Updated: every commit         by sourov          ###   ########.fr       */
/*                                                                            */
/* ************************************************************************** */

#include <unistd.h>

typedef struct s_dev
{
	char	*name;
	char	*base;
	char	*years_of;
	char	*learning;
	char	*right_now;
	char	*believes;
}	t_dev;

int	main(void)
{
	t_dev	me;

	me.name = "Sourov Ahmad";
	me.base = "Italy";
	me.years_of = "PHP, JavaScript, shipping web backends";
	me.learning = "Go, Rust";
	me.right_now = "C at 42: pointers, memory, no libc, no mercy";
	me.believes = "boring tools that work > new tools that impress";
	write(1, "hi\n", 3);
	return (0);
}
```

## Journey

```
$ git log --oneline --reverse sourov

a0b1c2d  init: HTML, CSS, first pages for real clients
3f8e21a  PHP: shipping backends for years, Laravel most of them
9c4d7b2  JavaScript: React and Svelte on the way
d1e5f06  Go, Rust: curiosity about what runs underneath
4242424  (HEAD -> main) C at 42: strings, pointers, memory, all by hand
```

## Work

| | |
|---|---|
| [42 Piscine in C](https://github.com/Sourovahmad/exercies) | Every exercise written from scratch. No libc, norm-checked. |
| [signal-zero-app](https://github.com/Sourovahmad/signal-zero-app) | Deterministic orbital emergency simulator, desktop and web. |
| [sourov.info](https://sourov.info) | Personal site. |

## Elsewhere

[Website](https://sourov.info) · [LinkedIn](https://www.linkedin.com/in/sourov-ahmad-50574120a/) · [YouTube](https://www.youtube.com/@airovs) · [Email](mailto:sourov.okk3@gmail.com)

<sub>No badges, no widgets, no animations. Just the code. It will look the same in ten years.</sub>

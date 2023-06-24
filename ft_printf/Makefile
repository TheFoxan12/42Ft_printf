# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:     #
#                                                     +:+ +:+         +:+      #
#    By: ^@^ Foxan ^@^ <thibaut.unsinger@gmail.com  +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2022/11/07 10:29:40 by ^@^ Foxan ^@^     #+#    #+#              #
#    Updated: 2022/11/07 10:29:42 by ^@^ Foxan ^@^    ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

CC = gcc
NAME = libftprintf.a
SRCS = ft_printf.c printf_putcharstr.c printf_putnrbs.c printf_puthex.c
INCLUDES = includes
FLAGS = -Wall -Wextra -Werror
OBJS = ${SRCS:.c=.o}

all: ${NAME}

${NAME}: ${OBJS}
	ar rc ${NAME} ${OBJS}
	ranlib ${NAME}

.c.o:
	${CC} ${FLAGS} -c $< -o ${<:.c=.o} -I ${INCLUDES}

clean:
	rm -f ${OBJS}

fclean: clean
	rm -f ${NAME}

re:	fclean all

.PHONY: all clean fclean re

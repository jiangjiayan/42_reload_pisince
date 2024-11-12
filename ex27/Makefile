# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: jjiayan <marvin@42.fr>                     +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2024/11/08 16:09:20 by jjiayan           #+#    #+#              #
#    Updated: 2024/11/08 16:09:36 by jjiayan          ###   ########.fr        #
#                                                                              #
# **************************************************************************** #


NAME = ft_display_file

FLAGS = -Wall -Wextra -Werror

SRCS = ft_display_file.c
OBJ = ft_display_file.o

all: ft_display_file.o
	gcc $(FLAGS) ft_display_file.o -o $(NAME)

ft_display_file.o: $(SRCS)
	gcc $(FLAGS) -c $(SRCS)

clean:
	rm -f $(OBJ)

fclean: clean
	rm -f $(NAME)

re: fclean all

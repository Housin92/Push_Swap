# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: mmiguelo <mmiguelo@student.42.fr>          +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2024/10/15 19:51:11 by mmiguelo          #+#    #+#              #
#    Updated: 2024/10/15 19:51:11 by mmiguelo         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

.SILENT:

#==============================================================================#
#                                    NAMES                                     #
#==============================================================================#

NAME = libft.a
CC = cc
CFLAGS = -Wall -Werror -Wextra -g
RM = rm -f


#==============================================================================#
#                                    FILES                                     #
#==============================================================================#

SRCS =	ft_bzero.c
SRCS +=	ft_atoi.c
SRCS += ft_atol.c
SRCS +=	ft_calloc.c
SRCS +=	ft_isalnum.c
SRCS +=	ft_isalpha.c
SRCS +=	ft_isascii.c
SRCS +=	ft_isdigit.c
SRCS +=	ft_isprint.c
SRCS +=	ft_itoa.c
SRCS +=	ft_memchr.c
SRCS +=	ft_memcmp.c
SRCS +=	ft_memcpy.c
SRCS +=	ft_memmove.c
SRCS +=	ft_memset.c
SRCS +=	ft_putchar_fd.c
SRCS +=	ft_putendl_fd.c
SRCS +=	ft_putnbr_fd.c
SRCS +=	ft_putstr_fd.c
SRCS +=	ft_split.c
SRCS +=	ft_strchr.c
SRCS +=	ft_strdup.c
SRCS +=	ft_striteri.c
SRCS +=	ft_strjoin.c
SRCS +=	ft_strlcat.c
SRCS +=	ft_strlcpy.c
SRCS +=	ft_strlen.c
SRCS +=	ft_strmapi.c
SRCS += ft_strcmp.c
SRCS +=	ft_strncmp.c
SRCS +=	ft_strnstr.c
SRCS +=	ft_strrchr.c
SRCS +=	ft_strtrim.c
SRCS +=	ft_substr.c
SRCS +=	ft_tolower.c
SRCS +=	ft_toupper.c
SRCS +=	ft_printf/ft_printf.c
SRCS +=	ft_printf/ft_putchar.c
SRCS +=	ft_printf/ft_puthex.c
SRCS +=	ft_printf/ft_putnbr.c
SRCS +=	ft_printf/ft_putptr.c
SRCS +=	ft_printf/ft_putstr.c
SRCS +=	ft_printf/ft_pututoa.c
SRCS +=	get_next_line/get_next_line.c
SRCS +=	get_next_line/get_next_line_utils.c
SRCS +=	ft_lstnew.c
SRCS +=	ft_lstadd_front.c
SRCS +=	ft_lstsize.c
SRCS +=	ft_lstlast.c
SRCS +=	ft_lstadd_back.c
SRCS +=	ft_lstdelone.c
SRCS +=	ft_lstclear.c
SRCS +=	ft_lstiter.c
SRCS +=	ft_lstmap.c


OBJ = $(SRCS:.c=.o)


#==============================================================================#
#                                    RULES                                     #
#==============================================================================#

all: $(NAME)

$(NAME): $(OBJ)
		@ar rcs $(NAME) $(OBJ)

clean:
		@$(RM) $(OBJ)

fclean: clean
		@$(RM) $(NAME)

re: clean all

PHONY: all clean fclean re

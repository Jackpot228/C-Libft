NAME = libft.a

SRC =	ft_itoa.c ft_putnbr_fd.c ft_strnstr.c\
		ft_atoi.c ft_memccpy.c ft_putstr_fd.c\
		ft_strrchr.c ft_bzero.c ft_memchr.c\
		ft_strchr.c	ft_substr.c ft_calloc.c\
		ft_memcmp.c	ft_strdup.c	ft_tolower.c\
		ft_isalnum.c ft_memcpy.c ft_strjoin.c\
		ft_toupper.c ft_isalpha.c ft_memmove.c\
		ft_strlcat.c ft_isascii.c ft_memset.c\
		ft_strlcpy.c ft_isdigit.c ft_putchar_fd.c\
		ft_strlen.c ft_isprint.c ft_putendl_fd.c\
		ft_strncmp.c ft_strtrim.c ft_split.c\
		ft_strmapi.c

SRC_BONUS = ft_lstnew.c ft_lstadd_front.c ft_lstsize.c\
			ft_lstlast.c ft_lstadd_back.c ft_lstdelone.c\
			ft_lstclear.c ft_lstiter.c ft_lstmap.c


OBJS = ft_itoa.o ft_putnbr_fd.o ft_strnstr.o\
        ft_atoi.o ft_memccpy.o ft_putstr_fd.o\
        ft_strrchr.o ft_bzero.o ft_memchr.o\
        ft_strchr.o ft_substr.o ft_calloc.o\
        ft_memcmp.o ft_strdup.o ft_tolower.o\
        ft_isalnum.o ft_memcpy.o ft_strjoin.o\
        ft_toupper.o ft_isalpha.o ft_memmove.o\
        ft_strlcat.o ft_isascii.o ft_memset.o\
        ft_strlcpy.o ft_isdigit.o ft_putchar_fd.o\
        ft_strlen.o ft_isprint.o ft_putendl_fd.o\
        ft_strncmp.o ft_strtrim.o ft_split.o\
        ft_strmapi.o

OBJS_BONUS = ft_lstnew.o ft_lstadd_front.o ft_lstsize.o\
			 ft_lstlast.o ft_lstadd_back.o ft_lstdelone.o\
			 ft_lstclear.o ft_lstiter.o ft_lstmap.o

FLAGS = -Wall -Wextra -Werror

CC = gcc
CFLAGS = -Wall -Wextra -Werror -I.

all: $(NAME)

$(NAME):	$(OBJS)
	ar -rcs $(NAME) $(OBJS)
	ranlib $(NAME)

bonus: all $(OBJS_BONUS)
	ar -rcs $(NAME) $(OBJS_BONUS)
	ranlib $(NAME)	

clean: 
	rm -rf $(OBJS) $(OBJS_BONUS)

fclean: clean
	rm -rf $(NAME)

re: fclean $(NAME)

.PHONY: all clean fclean re bonus

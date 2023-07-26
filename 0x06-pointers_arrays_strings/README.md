# 0x06. C - More pointers, arrays and strings \n

# 0. strcat \n

##Write a function that concatenates two strings. \n

Prototype: char *_strcat(char *dest, char *src); \n
This function appends the src string to the dest string, overwriting the terminating null byte (\0) at the end of dest, and then adds a terminating null byte

Returns a pointer to the resulting string dest \n

FYI: The standard library provides a similar function: strcat. Run man strcat to learn more.\n

### Repo: \n

	GitHub repository: alx-low_level_programming \n
	Directory: 0x06-pointers_arrays_strings \n
	File: 0-strcat.c \n

# 1. strncat

##Write a function that concatenates two strings. \n

Prototype: char *_strncat(char *dest, char *src, int n); \n
The _strncat function is similar to the _strcat function, except that \n
###	it will use at most n bytes from src; and \n
###	src does not need to be null-terminated if it contains n or more bytes \n

##Return a pointer to the resulting string dest \n

FYI: The standard library provides a similar function: strncat. Run man strncat to learn more.

###Repo: \n
	GitHub repository: alx-low_level_programming \n
	Directory: 0x06-pointers_arrays_strings \n
	File: 1-strncat.c \n

# 2. strncpy \n


##Write a function that copies a string.

	Prototype: char *_strncpy(char *dest, char *src, int n); \n
	Your function should work exactly like strncpy \n
FYI: The standard library provides a similar function: strncpy. Run man strncpy to learn more. \n
### Repo: \n
	GitHub repository: alx-low_level_programming \n
	Directory: 0x06-pointers_arrays_strings \n
	File: 2-strncpy.c \n

# 3. strcmp \n

##Write a function that compares two strings. \n

	Prototype: int _strcmp(char *s1, char *s2); \n
	Your function should work exactly like strcmp \n
FYI: The standard library provides a similar function: strcmp. Run man strcmp to learn more \n

###Repo: \n
	GitHub repository: alx-low_level_programming \n
	Directory: 0x06-pointers_arrays_strings \n
	File: 3-strcmp.c \n

### 4. I am a kind of paranoid in reverse. I suspect people of plotting to make me happy \n

## Write a function that reverses the content of an array of integers. \n
	Prototype: void reverse_array(int *a, int n); \n
	Where n is the number of elements of the array \n
### Repo: \n
	GitHub repository: alx-low_level_programming \n
	Directory: 0x06-pointers_arrays_strings \n
	File: 4-rev_array.c \n

# 5. Always look up \n

## Write a function that changes all lowercase letters of a string to uppercase. \n

	Prototype: char *string_toupper(char *); \n
### Repo: \n

	GitHub repository: alx-low_level_programming \n
	Directory: 0x06-pointers_arrays_strings \n
	File: 5-string_toupper.c \n

# 6. Expect the best. Prepare for the worst. Capitalize on what comes \n

## Write a function that capitalizes all words of a string. \n

	Prototype: char *cap_string(char *); \n
	Separators of words: space, tabulation, new line, ,, ;, ., !, ?, ", (, ), {, and } \n
### Repo: \n

	GitHub repository: alx-low_level_programming \n
	Directory: 0x06-pointers_arrays_strings \n
	File: 6-cap_string.c \n

# 7. Mozart composed his music not for the elite, but for everybody

## Write a function that encodes a string into 1337 \n.

	Letters a and A should be replaced by 4 \n
	Letters e and E should be replaced by 3 \n
	Letters o and O should be replaced by 0 \n
	Letters t and T should be replaced by 7 \n
	Letters l and L should be replaced by 1 \n
	Prototype: char *leet(char *); \n
	You can only use one if in your code \n
	You can only use two loops in your code \n
	You are not allowed to use switch \n
	You are not allowed to use any ternary operation \n
### Repo: \n

	GitHub repository: alx-low_level_programming \n
	Directory: 0x06-pointers_arrays_strings \n
	File: 7-leet.c \n

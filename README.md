# libdr-in-rust
try to make libdr like in rust 

libdr is the first big project in 42.fr school, originaly this is in C but for funny i try to make this is rust 

let's start this 
    
    :)
<h1 align="center">
	<s>42cursus</s> Rust libdr
</h1>

<p align="center">
	<img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/dnettoRaw/libdr-in-rust?color=blueviolet" />
	<img alt="Number of lines of code" src="https://img.shields.io/tokei/lines/github/dnettoRaw/libdr-in-rust?color=blueviolet" />
	<img alt="Code language count" src="https://img.shields.io/github/languages/count/dnettoRaw/libft-in-rust?color=blue" />
	<img alt="GitHub top language" src="https://img.shields.io/github/languages/top/dnettoRaw/libft-in-rust?color=blue" />
	<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/dnettoRaw/libft-in-rust?color=brightgreen" />
</p>

<h3 align="center">
	<a href="#%EF%B8%8F-about">About</a>
	<span> · </span>
	<a href="#%EF%B8%8F-usage">Usage</a>
	<span> · </span>
	<a href="#-testing">Testing</a>
</h3>

---

## 🗣️ About

> _In 42 campus you can use only sommes lib's for the 'baned functions' you need to code that yourself, here i just make that with rust for train myself with rust._

For detailed information from original project, refer to the [**subject of this project**](https://github.com/dnettoRaw/42_Subjects/blob/master/00_Projects/00_Global/libdr.pdf).

	🚀 TLDR: this project consists of coding basic C functions (see below).


---

# Unlike 42 my functions are not prefixed ft_ , I love prefix with dn_ for local and dr_ for global functions

---

### Functions from `<ctype.h>` library
|   done    |function name                           | description                                         |
|:---------:|:---------------------------------------|-----------------------------------------------------|
|  &#10008; | [`ft_isascii`](src/is/ft_isascii.rs)   | test for ASCII character.                           |
|  &#10008; | [`ft_isalnum`](src/is/ft_isalnum.rs)   | alphanumeric character test.                        |
|  &#10008; | [`ft_isalpha`](src/is/ft_isalpha.rs)   | alphabetic character test.                          |
|  &#10008; | [`ft_islower`](src/is/ft_islower.rs)   | lower-case character test.                          |
|  &#10008; | [`ft_isupper`](src/is/ft_isupper.rs)   | upper-case character test.                          |
|  &#10008; | [`ft_isdigit`](src/is/ft_isdigit.rs)   | decimal-digit character test.                       |
|  &#10008; | [`ft_isxdigit`](src/is/ft_isxdigit.rs) | hexadecimal-digit character test.                   |
|  &#10008; | [`ft_isprint`](src/is/ft_isprint.rs)   | printing character test (space character inclusive).|
|  &#10008; | [`ft_isgraph`](src/is/ft_isgraph.rs)   | printing character test (space character exclusive).|
|  &#10008; | [`ft_isspace`](src/is/ft_isspace.rs)   | white-space character test.                         |
|  &#10008; | [`ft_isblank`](src/is/ft_isblank.rs)   | space or tab character test.                        |
|  &#10008; | [`ft_ispunct`](src/is/ft_ispunct.rs)   | punctuation character test.                         |
|  &#10008; | [`ft_iscntrl`](src/is/ft_iscntrl.rs)   | control character test.                             |
|  &#10008; | [`ft_tolower`](src/to/ft_tolower.rs)   | upper case to lower case letter conversion.         |
|  &#10004; | [`ft_toupper`](src/to/ft_toupper.rs)   | lower case to upper case letter conversion.         |

### Functions from `<stdlib.h>` library

|   done    |function name                           | description                                         |
|:---------:|-|-|
|  &#10008; |[`ft_atoi`](src/to/ft_atoi.rs)		| convert ASCII string to integer.|
|  &#10008; |[`ft_atof`](src/to/ft_atof.rs) 	| convert ASCII string to integer.|
|  &#10008; |[`ft_calloc`](src/mem/ft_calloc.rs)| memory allocation.|

### Functions from `<strings.h>` library


|   done    |function name                           | description                                         |
|:---------:|:---------------------------------------|-----------------------------------------------------|
|  &#10008; | [`ft_bzero`](src/mem/ft_bzero.rs)		| write zeroes to a byte string.|
|  &#10008; | [`ft_memset`](src/mem/ft_memset.rs)		| write a byte to a byte string.|
|  &#10008; | [`ft_memchr`](src/mem/ft_memchr.rs)		| locate byte in byte string.|
|  &#10008; | [`ft_memcmp`](src/mem/ft_memcmp.rs)		| compare byte string.|
|  &#10008; | [`ft_memmove`](src/mem/ft_memmove.rs)	| copy byte string.|
|  &#10008; | [`ft_memcpy`](src/mem/ft_memcpy.rs)		| copy memory area.|
|  &#10008; | [`ft_memccpy`](src/mem/ft_memccpy.rs)	| copy string until character found.|

### Functions from `<string.h>` library


|   done    |function name                           | description                                         |
|:---------:|:---------------------------------------|-----------------------------------------------------|
|  &#10008; | [`ft_strlen`](src/str/ft_strlen.rs)	 | find length of string.|
|  &#10008; | [`ft_strlen_2`](src/str/ft_strlen_2.rs)| find length of 2D array (i.e. splitted string).|
|  &#10008; | [`ft_strchr`](src/str/ft_strchr.rs)	 | locate character in string (first occurrence).|
|  &#10008; | [`ft_strrchr`](src/str/ft_strrchr.rs)	 | locate character in string (last occurence).|
|  &#10008; | [`ft_strstr`](src/str/ft_strstr.rs) 	 | locate a substring in a string.|
|  &#10008; | [`ft_strnstr`](src/str/ft_strnstr.rs)	 | locate a substring in a string (size-bounded).|
|  &#10008; | [`ft_strcmp`](src/str/ft_strcmp.rs) 	 | compare strings.|
|  &#10008; | [`ft_strncmp`](src/str/ft_strncmp.rs)  | compare strings (size-bounded).|
|  &#10008; | [`ft_strnrcmp`](src/str/ft_strnrcmp.rs)| reversely compare strings (size-bounded).|
|  &#10008; | [`ft_strcpy`](src/str/ft_strcpy.rs) 	 | copy strings.|
|  &#10008; | [`ft_strncpy`](src/str/ft_strncpy.rs)  | copy strings (size-bounded).|
|  &#10008; | [`ft_strdup`](src/str/ft_strdup.rs)	 | save a copy of a string (with malloc).|
|  &#10008; | [`ft_strndup`](src/str/ft_strndup.rs)  | save a copy of a string (with malloc, size-bounded).|
|  &#10008; | [`ft_strcat`](src/str/ft_strcat.rs) 	 | concatenate strings (s2 into s1).|
|  &#10008; | [`ft_strncat`](src/str/ft_strncat.rs)  | concatenate strings (s2 into s1, size-bounded).|
|  &#10008; | [`ft_strlcpy`](src/str/ft_strlcpy.rs)	 | size-bounded string copying.|
|  &#10008; | [`ft_strlcat`](src/str/ft_strlcat.rs)	 | size-bounded string concatenation.|

### Functions from `<math.h>` library


|   done    |function name                           | description                                         |
|:---------:|:---------------------------------------|-----------------------------------------------------|
|  &#10008; |[`ft_sqrt`](src/math/ft_sqrt.rs) 	| square root function.|
|  &#10008; |[`ft_pow`](src/math/ft_pow.rs) 	| power function.|

### Non-standard functions


|   done    |function name                           | description                                         |
|:---------:|:---------------------------------------|-----------------------------------------------------|
|  &#10008; |[`ft_swap`](src/mem/ft_swap.rs) 			| swap value of two integers.|
|  &#10008; |[`ft_putchar`](src/put/ft_putchar.rs) 	| output a character to stdout.|
|  &#10008; |[`ft_putchar_fd`](src/put/ft_putchar_fd.rs)		| output a character to given file.|
|  &#10008; |[`ft_putstr`](src/put/ft_putstr.rs) 		| output string to stdout.|
|  &#10008; |[`ft_putstr_fd`](src/put/ft_putstr_fd.rs)		| output string to given file.|
|  &#10008; |[`ft_putendl`](src/put/ft_putendl.rs) 	| output string to stdout with newline.|
|  &#10008; |[`ft_putendl_fd`](src/put/ft_putendl_fd.rs)		| output string to given file with newline.|
|  &#10008; |[`ft_putnbr`](src/put/ft_putnbr.rs) 		| output integer to stdout.|
|  &#10008; |[`ft_putnbr_fd`](src/put/ft_putnbr_fd.rs)		| output integer to given file.|
|  &#10008; |[`ft_itoa`](src/to/ft_itoa.rs)					| convert integer to ASCII string.|
|  &#10008; |[`ft_substr`](src/str/ft_substr.rs)				| extract substring from string.|
|  &#10008; |[`ft_strtrim`](src/str/ft_strtrim.rs)			| trim beginning and end of string with the specified characters.|
|  &#10008; |[`ft_strjoin`](src/str/ft_strjoin.rs)			| concatenate two strings into a new string (with malloc).|
|  &#10008; |[`ft_split`](src/str/ft_split.rs)				| split string, with specified character as delimiter, into an array of strings.|
|  &#10008; |[`ft_split_free`](src/str/ft_split_free.rs) 				| free splitted string.|
|  &#10008; |[`ft_strmapi`](src/str/ft_strmapi.rs)			| create new string from modifying string with specified function.|
|  &#10008; |[`ft_ftoa_rnd`](src/str/ft_ftoa_rnd.rs)			| convert float to ASCII string.|

### Linked list functions


|   done    |function name                           | description                                         |
|:---------:|:---------------------------------------|-----------------------------------------------------|
|  &#10008; |[`ft_lstnew`](src/lst/ft_lstnew.rs)				| create new list.|
|  &#10008; |[`ft_lstsize`](src/lst/ft_lstsize.rs)			| count elements of a list.|
|  &#10008; |[`ft_lstlast`](src/lst/ft_lstlast.rs)			| find last element of list.|
|  &#10008; |[`ft_lstadd_back`](src/lst/ft_lstadd_back.rs)	| add new element at end of list.|
|  &#10008; |[`ft_lstadd_front`](src/lst/ft_lstadd_front.rs)	| add new element at beginning of list.|
|  &#10008; |[`ft_lstdelone`](src/lst/ft_lstdelone.rs)		| delete element from list.|
|  &#10008; |[`ft_lstclear`](src/lst/ft_lstclear.rs)			| delete sequence of elements of list from a starting point.|
|  &#10008; |[`ft_lstiter`](src/lst/ft_lstiter.rs)			| apply function to content of all list's elements.|
|  &#10008; |[`ft_lstmap`](src/lst/ft_lstmap.rs)				| apply function to content of all list's elements into new list.|


## 🛠️ Usage

### Requirements

The library is written in Rust language and thus needs the **`cargo` compiler** and some standard **rust libraries** to run.

### Instructions

**1. Compiling the library**

To compile the library, run:

```shell
$ cd path/to/libdr && make
```

**2. Using it in your code**

To use the library functions in your code, simply include its header:

```rust
use dr_libdr::{dn_myfunction}
```

## 📋 Testing

**1. First, configure the path to the libdr folder in the Makefile (inside `/testing/`):**

```Makefile
#############################
## Path to Libdr directory ##
#############################
DIR		= ../
```

**2. Then run:**

```shell
make t
``` 

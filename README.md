# squidsay

*Note that since this was made by some random kid in a couple hours, using the holy 50-year-old
C programming language, it is INCREDIBLY buggy (I'm talking segfaults if there is a slightly long
string).*

```
 _____________________________________________
| You know cowsay? Well introducing SQUIDSAY, |
| which is literally the same thing,          |
| but with our lord and savior,               |
| Squidward Tentacles.                        |
 ---------------------------------------------
    \   ___
     \ (.. )
       -|-
       /| |\
        | |
       / | \
```

---

## Building/Installation

Make sure you have a C compiler available in `$PATH` and the Make build system. First, clone the
repo with `git clone https://github.com/yamhab/squidsay.git`. Then, just run `make` to build the
executable into the `build/` directory. Sorry Windoze users.

---

## Usage

Simply give (a) string(s) as (an) argument(s) to the program from a shell, or pipe in some text
(also from a shell).

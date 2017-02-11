
# How to Setup

To setup this project clone it recursively:

```bash
git clone --recursive https://github.com/VinGarcia/bAbI.git
```

And this run make:

```bash
make
```

This will compile all the required files, and it might take a while.

# Running the tests

From the 20 bAbI problems all first 17 are ready.

To run a script use make #, where # is the script number, e.g.:

```bash
# runs the first script:
make 1

#runs the last script:
make 17
```

To run all scripts in sequence use:

```bash
make all
```

# Obtaining the train files

Please note that the train#.txt files are slightly altered:

- All the tabs were replaced by the character '|'

The reason for that is a JSpy bug when processing `\t` on the
matcher pattern string.


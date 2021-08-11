# raylib vscode project template for linux (2021)

### What you will need

- gdb `sudo apt install gdb`
- clang `sudo apt install clang`
- raylib

---

### Make file properties you will need to change

- `PROJECT_NAME` defualt is `game`
- `COMPILER_PATH` defualt is `/usr/bin/clang`
- `BUILD_MODE` defualt `RELEASE`
- `CC` (C compiler) defualt `clang`
- `OBJS` defualt `src/main.c` (this is for your main file)

---

### c_cpp_properties

- `includePath` defualt `~/Documents/raylib/src/\*\*` this is the location of where raylib is installed

# Programming Language C
Failed attempt at making a programming language in C. The project in the current state is a total mess and does not work as expected. I am keeping this project open-source for full transparency towards my projects. I'm not sure why would you want to build and try it, but you can do so using CMake:
```bash
cmake -B build
cmake --build build
```
The executable will be located in `build/plang`. Or build using your favorite compiler:
```bash
gcc -Iinclude src/*.c -o plang
```
You'll be presented by a REPL interface. You can read the [DOCS.md](DOCS.md) for documentation.

## Credits
This project was made by Daniel Vishnevsky and is licensed under MIT License. It was made in March of 2025 and published on October 2026 as an effort to make all of my projects open-source.

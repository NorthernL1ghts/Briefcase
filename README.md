# Briefcase

- An experimental peer-to-peer network, that I made in dart for a future distributed system (network).

## Compiling:

> Before compiling, be sure to update the versioning information
> with:

> ```bash
> pub run pubspec_extract
> ```

- To compile a self-contained executable (a standalone architecture-specific executable file containing the
source code compiled to machine code and a small Dart runtime), use the following command:

```bash
dart compile exe bin/application.dart -o dist/application
```

- This will compile an executable file native to your system. On Windows, you may wish to append `.exe` to the name of the output file. On *nix systems, you can just run the executable with `./dist/application`.

- As a fun aside, you can also compile to JavaScript as follows:

```bash
dart compile js bin/application.js -o dist/application.js
```
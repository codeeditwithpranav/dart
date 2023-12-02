# Introduction to dart
> Dart has a C-style syntax that is easy to read and write.
> Dart files often include import statements to bring in functionality from other Dart files or external packages.
> Dart applications typically have a main function as the entry point of the program.
> - Before going deep into the tutorial you must install an IDE for coding and the DART package from [dart.dev](https://dart.dev/get-dart)

> [!TIP]
> I highly recommend using VS Code for coding.

> Now we are going to make our first dart file
> - make your first dart file like this [name].dart, name can be any thing
>   - File Naming: Choose a meaningful and descriptive name for your program file.
Use lowercase letters and separate words with underscores or follow a camelCase convention.
>   - File Extension: Use the appropriate file extension for the programming language you are using.
Common extensions include .dart for Dart, .js for JavaScript, .py for Python, etc.

# Here is the code
```
import 'dart:io';

void main(List<String> args) {
  stdout.writeln("What is your name: ");
  String? name = stdin.readLineSync();
  print(name);
}

```
> **Certainly! Let's break down the provided Dart code line by line:**
> ```
> import 'dart:io';
> ```
> - This line imports the dart:io library. The dart:io library provides input and output functionality, allowing you to interact with the command-line environment. It includes classes like stdin (standard input) and stdout (standard output) for reading and writing to the console.
> ```
> void main(List<String> args) {
> ```
> - This line declares the main function, which is the entry point of the Dart program.

>  [!NOTE]
>  we can also write the main function like
> ```
> void main()
> {
> print("Hello");
> }
> ```
> or
> ```
> main()
> {
> print("Hello");
> }
> ```

> ```
>   stdout.writeln("What is your name: ");
> ```
> - stdout.writeln is used to write a prompt to the standard output (console). In this case, it asks the user, "What is your name: ".


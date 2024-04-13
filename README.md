# ParseGen CLR Compiler Toolkit

![GitHub repo size](https://img.shields.io/github/repo-size/Priyanshuparth/ParseGen-CLR-Compiler-Toolkit)
![GitHub contributors](https://img.shields.io/github/contributors/Priyanshuparth/ParseGen-CLR-Compiler-Toolkit)
![GitHub stars](https://img.shields.io/github/stars/Priyanshuparth/ParseGen-CLR-Compiler-Toolkit?style=social)
![GitHub forks](https://img.shields.io/github/forks/Priyanshuparth/ParseGen-CLR-Compiler-Toolkit?style=social)
[![Instagram Follow](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/priyanshuparth) 
[![LinkedIn Follow](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/priyanshuparth) 

## Overview

This project implements a compiler for a custom programming language. The compiler consists of a lexical analyzer, syntax analyzer, and parsing table generator. Its purpose is to tokenize input source code, check for syntactic correctness, and generate CLR parsing tables.

## Project Structure

- `main.py`: Main program that coordinates lexical analysis, syntax analysis, and parsing table generation.
- `lexer.py`: Contains functions for tokenizing input source code.
- `parser.py`: Implements syntax analysis and LR(1) parsing table generation.
- `program.txt`: Input source code to be processed by the compiler.
- `grammar.txt`: Context-free grammar rules for the programming language.
- `README.md`: Project documentation.

## Components

1. **Lexical Analyzer**: Identifies tokens in the source code and removes whitespace and comments.
2. **Syntax Analyzer**: Parses the tokenized input according to grammar rules and checks for syntactic correctness.
3. **Parsing Table Generator**: Constructs CLR parsing tables based on the given context-free grammar.

## Usage

1. Clone the repository:

   ```bash
   git clone git@github.com:Priyanshuparth/ParseGen-CLR-Compiler-Toolkit.git
   ```

2. Navigate to the project directory:

    ```bash
    cd Compiler-Design-CLR
    ```

3. Run the main program:

    ```bash
    python main.py
    ```
4. Provide the input source code (program.txt) and grammar rules (grammar.txt).

## Example Usage
Here's an example of how to use the compiler:

- Provide the input source code (program.txt) and grammar rules (grammar.txt).
- Run the main program (main.py) to tokenize and parse the input code.
- View the generated parsing table and parsing actions to identify any syntactic errors in the input code.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or create a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgements
This project was inspired by the concepts of compiler design taught in computer science courses.

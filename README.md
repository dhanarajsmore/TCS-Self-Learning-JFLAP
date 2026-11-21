# Theory of Computer Science — JFLAP Self-Learning

- **Student Name:** Dhanaraj More
- **Roll Number:** 41
- **Class / Branch / Semester:** D12B / Computer Engineering (CMPN) / Semester V
- **Course:** Theory of Computer Science (26CMPC51)

A collection of 30 JFLAP (`.jff`) implementations covering finite automata, Mealy and Moore machines, regular expressions, regular and context-free grammars, parsing techniques (LL, LR, CYK), pushdown automata, Turing machines, and grammar transformations.

## How to Run

1. Install Java (JDK/JRE 8 or higher).
2. Download **JFLAP 7.1** from https://www.jflap.org/modules/.
3. Open JFLAP and load any `.jff` file using **File → Open**.

## Index of Experiments

| # | Topic | File | Description |
|---|-------|------|-------------|
| 1 | Deterministic Finite Automata | `41_DhanarajMore_deterministic_finite_automata_21-11-26.jff` | DFA over {0,1} accepting strings that end in "01" |
| 2 | Nondeterministic Finite Automata | `41_DhanarajMore_nondeterministic_finite_automata_21-11-26.jff` | NFA over {0,1} accepting strings containing the substring "101" |
| 3 | NFA to DFA Conversion | `41_DhanarajMore_nfa_to_dfa_conversion_21-11-26.jff` | NFA over {0,1} for strings whose third-from-last symbol is "1" |
| 4 | DFA Minimization | `41_DhanarajMore_dfa_minimization_21-11-26.jff` | 4-state DFA over {0,1} for odd-length strings that minimizes to 2 states |
| 5 | DFA to Regular Grammar Conversion | `41_DhanarajMore_dfa_to_regular_grammar_21-11-26.jff` | DFA accepting strings over {a,b} with an odd number of b's |
| 6 | DFA to Regular Expression Conversion | `41_DhanarajMore_dfa_to_regular_expression_21-11-26.jff` | DFA accepting strings over {a,b} starting and ending with "a" (length >= 2) |
| 7 | Combining Automata | `41_DhanarajMore_combining_automata_21-11-26.jff` | DFA for strings over {a,b} containing "bb", for union or concatenation |
| 8 | Regular Expression | `41_DhanarajMore_regular_expression_21-11-26.jff` | Regular expression a(a+b)*b |
| 9 | Regular Expression to DFA Conversion | `41_DhanarajMore_regex_to_dfa_21-11-26.jff` | Regular expression (a+b)*aba for conversion to DFA |
| 10 | Regular Expression Identities | `41_DhanarajMore_regular_expression_identities_21-11-26.jff` | Regular expression (0+1)*1(0+1)* for checking regular identities |
| 11 | Regular Grammar | `41_DhanarajMore_regular_grammar_21-11-26.jff` | Right-linear regular grammar generating b*ab |
| 12 | Regular Grammar to DFA Conversion | `41_DhanarajMore_regular_grammar_to_dfa_21-11-26.jff` | Regular grammar generating strings ending with "ab" for conversion into a DFA |
| 13 | DFA Relationship to Grep | `41_DhanarajMore_dfa_grep_110_21-11-26.jff` | DFA for (0+1)*110 demonstrating grep substring pattern matching |
| 14 | Mealy Machine | `41_DhanarajMore_mealy_parity_checker_21-11-26.jff` | Mealy machine outputting 'E' for even parity and 'O' for odd parity of 1's |
| 15 | Moore Machine | `41_DhanarajMore_moore_mod3_residue_21-11-26.jff` | Moore machine computing the residue modulo 3 of a binary number |
| 16 | Context-free Grammar | `41_DhanarajMore_context_free_grammar_21-11-26.jff` | CFG generating palindromes over {a,b} |
| 17 | Pushdown Automata | `41_DhanarajMore_pushdown_automaton_21-11-26.jff` | PDA accepting strings with an equal number of a's and b's |
| 18 | NPDA to CFG Conversion | `41_DhanarajMore_npda_to_cfg_conversion_21-11-26.jff` | NPDA for a^n b^n (n >= 1) formatted for direct CFG conversion |
| 19 | CFG to NPDA Conversion | `41_DhanarajMore_cfg_to_npda_conversion_21-11-26.jff` | CFG generating a^n b^m c^m d^n to convert into an NPDA |
| 20 | Context-free Grammar with Single Symbols | `41_DhanarajMore_cfg_single_symbols_21-11-26.jff` | CFG whose right-hand sides are single terminal or non-terminal symbols |
| 21 | Context-free Grammar with Multiple Symbols | `41_DhanarajMore_cfg_multiple_symbols_21-11-26.jff` | CFG with multi-symbol right-hand sides (S -> xABy) |
| 22 | CFG in Error using User Control Parse | `41_DhanarajMore_cfg_error_parse_21-11-26.jff` | CFG S -> aSa | ba for demonstrating dead-ends in User Control Parse |
| 23 | LL Parsing | `41_DhanarajMore_ll_parsing_21-11-26.jff` | LL(1) grammar for comma-separated lists S -> aA, A -> cA | lambda |
| 24 | LR Parsing | `41_DhanarajMore_lr_parsing_21-11-26.jff` | LR(1) grammar E -> E*T | T, T -> (E) | a for bottom-up shift-reduce parsing |
| 25 | CYK Parsing | `41_DhanarajMore_cyk_parsing_21-11-26.jff` | Grammar in Chomsky Normal Form generating a+ b+ for CYK parsing |
| 26 | One-Tape Turing Machine | `41_DhanarajMore_one_tape_turing_machine_21-11-26.jff` | One-tape TM that inverts binary strings (replaces 0 with 1 and 1 with 0) |
| 27 | Multi-Tape Turing Machine | `41_DhanarajMore_multi_tape_turing_machine_21-11-26.jff` | Two-tape TM that recognizes 0^n 1^n (n >= 1) using the second tape |
| 28 | Turing Machine Building Blocks | `41_DhanarajMore_turing_building_block_21-11-26.jff` | TM building block subroutine that moves left to the first blank symbol |
| 29 | Unrestricted Grammar | `41_DhanarajMore_unrestricted_grammar_21-11-26.jff` | Type-0 unrestricted grammar that generates 0^n 1^n 2^n (n >= 1) |
| 30 | CFG to Chomsky Normal Form Transformation | `41_DhanarajMore_cfg_to_cnf_transformation_21-11-26.jff` | CFG with lambda, unit, and mixed productions for CNF transformation |

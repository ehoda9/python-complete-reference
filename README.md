# Python Complete Reference

A structured, notebook-based Python reference: from syntax basics to object oriented programming, iteration tools, the standard library, regular expressions and type hints. Every topic is a notebook with a quick summary table, explanations and code examples.

**Read it online:** [Python Complete Reference Notebook on Kaggle](https://www.kaggle.com/code/mahmoud15/python-complete-reference-notebook)

## What is inside

- **Offline notebooks** in [`notebooks/`](notebooks/): 94 notebooks in 14 folders, one topic per notebook, meant for studying and quick lookup.
- **One unified notebook** in [`kaggle/`](kaggle/): all 14 parts in a single file (329 cells, 146 of them code) with a clickable roadmap, a table of contents and an A-Z index of every name it explains. It is designed to run top to bottom without manual input and is the source of the Kaggle notebook above.

## Scope

A **beginner-to-intermediate refresher**: short explanations, quick tables and runnable examples, meant for revision and quick lookup rather than deep dives.

**Not covered:** metaclasses, C extensions, CPython internals, packaging and publishing, threads, processes and `asyncio`, networking (`urllib`, `socket`), `subprocess`, web frameworks and data-science libraries.

## Learning order

The parts follow a learning path: each part builds on the ones before it. A few one-line examples in Parts 1 and 5 use a construct that is explained later (for example `try` in Data Types). The **Suggested background** column lists the earlier parts whose ideas a part uses. **Quick References** (keywords and built-in functions) is meant for lookup at any time.

## Roadmap

Part `N` of the unified notebook is the folder `N - ...` in `notebooks/`, and section `N.M` is file `M - ...` inside that folder. For example, section 4.9 (Decorators) is [`04 - Functions/09 - Decorators`](notebooks/04%20-%20Functions/09%20-%20Decorators.ipynb).

| Part | Topic | Notebooks | What it covers | Suggested background |
|---|---|---|---|---|
| 1 | [Python Basics](notebooks/01%20-%20Python%20Basics) | 8 | Comments, variables, data types, operators, type conversion, user input, string formatting, modules and `import` | Start here |
| 2 | [Control Flow](notebooks/02%20-%20Control%20Flow) | 4 | `if` / `elif` / `else`, `while` and `for` loops, `match` / `case` | Part 1 |
| 3 | [Data Structures](notebooks/03%20-%20Data%20Structures) | 5 | Lists, tuples, sets & frozen sets, dictionaries, booleans, container comparison guide | Part 2 |
| 4 | [Functions](notebooks/04%20-%20Functions) | 13 | Return values, parameters, defaults, `*args` / `**kwargs`, scope, recursion, lambda, decorators, docstrings, type hints, PEP 8 | Parts 1-2 |
| 5 | [Errors, Debugging & Profiling](notebooks/05%20-%20Errors,%20Debugging%20%26%20Profiling) | 4 | Exception types, `raise`, `try` / `except` / `else` / `finally`, tracebacks, `assert`, `pdb`, `timeit`, `cProfile` | Parts 1-2, 4 |
| 6 | [Comprehensions, Iterators & Generators](notebooks/06%20-%20Comprehensions,%20Iterators%20%26%20Generators) | 7 | List, set, dict and generator expressions, nested comprehensions, iterables vs iterators, generators, scope and the walrus operator | Parts 1-2, 4-5 |
| 7 | [Standard Library Essentials](notebooks/07%20-%20Standard%20Library%20Essentials) | 6 | `math`, `statistics`, `decimal`, `random`, `datetime`, `collections`, `functools` | Parts 1-2, 4-6 |
| 8 | [Itertools](notebooks/08%20-%20Itertools) | 8 | Infinite iterators, slicing and filtering, chaining and zipping, `accumulate` / `pairwise` / `batched` / `tee`, `groupby`, combinatorics, recipes | Parts 1-2, 4-7 |
| 9 | [Files & Data Formats](notebooks/09%20-%20Files%20%26%20Data%20Formats) | 6 | Reading and writing files, file modes, `pathlib`, `os` / `sys` / `shutil`, JSON, CSV | Parts 1-2, 4-7 |
| 10 | [Regular Expressions](notebooks/10%20-%20Regular%20Expressions) | 5 | Regex syntax, character classes, quantifiers, groups, assertions, the `re` functions, flags and performance | Parts 1-2, 4 |
| 11 | [Object Oriented Programming](notebooks/11%20-%20Object%20Oriented%20Programming) | 16 | Classes, encapsulation, inheritance and MRO, custom exceptions, polymorphism, ABCs, dunder methods, context managers, descriptors, dataclasses, class patterns, design patterns | Parts 1-2, 4-7, 9 |
| 12 | [Advanced Type Hinting](notebooks/12%20-%20Advanced%20Type%20Hinting) | 4 | `TypeVar` and generics, protocols, `TypedDict`, `Self`, `TypeGuard`, `overload`, `ParamSpec`, runtime introspection, 3.14 notes | Parts 1-2, 4-5, 7, 11 |
| 13 | [Building Real Programs](notebooks/13%20-%20Building%20Real%20Programs) | 6 | Packages and the `__main__` guard, command-line arguments, external packages with `pip`, logging, `unittest`, `doctest` | Parts 1-2, 4-6, 9, 11 |
| 14 | [Quick References](notebooks/14%20-%20Quick%20References) | 2 | All 35 keywords with examples and the built-in functions by category | Parts 1-2, 4-7, 9, 11 |

## Notebook index

Open [`00 - Python Notebook Content`](notebooks/00%20-%20Python%20Notebook%20Content.ipynb) for a quick offline index, or use the list below.

<details>
<summary><strong>01 - Python Basics</strong> (8 notebooks)</summary>

- [`01 - Comments`](notebooks/01%20-%20Python%20Basics/01%20-%20Comments.ipynb)
- [`02 - Variables`](notebooks/01%20-%20Python%20Basics/02%20-%20Variables.ipynb)
- [`03 - Data Types`](notebooks/01%20-%20Python%20Basics/03%20-%20Data%20Types.ipynb)
- [`04 - Operators`](notebooks/01%20-%20Python%20Basics/04%20-%20Operators.ipynb)
- [`05 - Type Conversion`](notebooks/01%20-%20Python%20Basics/05%20-%20Type%20Conversion.ipynb)
- [`06 - User Input`](notebooks/01%20-%20Python%20Basics/06%20-%20User%20Input.ipynb)
- [`07 - String Formatting`](notebooks/01%20-%20Python%20Basics/07%20-%20String%20Formatting.ipynb)
- [`08 - Built-in Modules`](notebooks/01%20-%20Python%20Basics/08%20-%20Built-in%20Modules.ipynb)

</details>

<details>
<summary><strong>02 - Control Flow</strong> (4 notebooks)</summary>

- [`01 - If Elif Else`](notebooks/02%20-%20Control%20Flow/01%20-%20If%20Elif%20Else.ipynb)
- [`02 - While Loop`](notebooks/02%20-%20Control%20Flow/02%20-%20While%20Loop.ipynb)
- [`03 - For Loop`](notebooks/02%20-%20Control%20Flow/03%20-%20For%20Loop.ipynb)
- [`04 - Match Case`](notebooks/02%20-%20Control%20Flow/04%20-%20Match%20Case.ipynb)

</details>

<details>
<summary><strong>03 - Data Structures</strong> (5 notebooks)</summary>

- [`01 - Lists`](notebooks/03%20-%20Data%20Structures/01%20-%20Lists.ipynb)
- [`02 - Tuples`](notebooks/03%20-%20Data%20Structures/02%20-%20Tuples.ipynb)
- [`03 - Sets & Frozen Sets`](notebooks/03%20-%20Data%20Structures/03%20-%20Sets%20%26%20Frozen%20Sets.ipynb)
- [`04 - Dictionaries`](notebooks/03%20-%20Data%20Structures/04%20-%20Dictionaries.ipynb)
- [`05 - Boolean & Containers Comparison`](notebooks/03%20-%20Data%20Structures/05%20-%20Boolean%20%26%20Containers%20Comparison.ipynb)

</details>

<details>
<summary><strong>04 - Functions</strong> (13 notebooks)</summary>

- [`01 - Functions Basics`](notebooks/04%20-%20Functions/01%20-%20Functions%20Basics.ipynb)
- [`02 - Return Statement`](notebooks/04%20-%20Functions/02%20-%20Return%20Statement.ipynb)
- [`03 - Parameters & Arguments`](notebooks/04%20-%20Functions/03%20-%20Parameters%20%26%20Arguments.ipynb)
- [`04 - Default Parameters`](notebooks/04%20-%20Functions/04%20-%20Default%20Parameters.ipynb)
- [`05 - Args Kwargs & Unpacking`](notebooks/04%20-%20Functions/05%20-%20Args%20Kwargs%20%26%20Unpacking.ipynb)
- [`06 - Function Scope`](notebooks/04%20-%20Functions/06%20-%20Function%20Scope.ipynb)
- [`07 - Recursion`](notebooks/04%20-%20Functions/07%20-%20Recursion.ipynb)
- [`08 - Lambda Functions`](notebooks/04%20-%20Functions/08%20-%20Lambda%20Functions.ipynb)
- [`09 - Decorators`](notebooks/04%20-%20Functions/09%20-%20Decorators.ipynb)
- [`10 - Docstrings`](notebooks/04%20-%20Functions/10%20-%20Docstrings.ipynb)
- [`11 - Type Hints Foundations`](notebooks/04%20-%20Functions/11%20-%20Type%20Hints%20Foundations.ipynb)
- [`12 - Collections, Union Types & Type Aliases`](notebooks/04%20-%20Functions/12%20-%20Collections,%20Union%20Types%20%26%20Type%20Aliases.ipynb)
- [`13 - Coding Style (PEP 8)`](notebooks/04%20-%20Functions/13%20-%20Coding%20Style%20%28PEP%208%29.ipynb)

</details>

<details>
<summary><strong>05 - Errors, Debugging & Profiling</strong> (4 notebooks)</summary>

- [`01 - Errors & Exceptions`](notebooks/05%20-%20Errors,%20Debugging%20%26%20Profiling/01%20-%20Errors%20%26%20Exceptions.ipynb)
- [`02 - Exception Handling`](notebooks/05%20-%20Errors,%20Debugging%20%26%20Profiling/02%20-%20Exception%20Handling.ipynb)
- [`03 - Debugging`](notebooks/05%20-%20Errors,%20Debugging%20%26%20Profiling/03%20-%20Debugging.ipynb)
- [`04 - Measuring Performance`](notebooks/05%20-%20Errors,%20Debugging%20%26%20Profiling/04%20-%20Measuring%20Performance.ipynb)

</details>

<details>
<summary><strong>06 - Comprehensions, Iterators & Generators</strong> (7 notebooks)</summary>

- [`01 - Comprehensions Foundations`](notebooks/06%20-%20Comprehensions,%20Iterators%20%26%20Generators/01%20-%20Comprehensions%20Foundations.ipynb)
- [`02 - Conditions, Multiple Loops & Nested Comprehensions`](notebooks/06%20-%20Comprehensions,%20Iterators%20%26%20Generators/02%20-%20Conditions,%20Multiple%20Loops%20%26%20Nested%20Comprehensions.ipynb)
- [`03 - Dict, Set & Generator Expressions`](notebooks/06%20-%20Comprehensions,%20Iterators%20%26%20Generators/03%20-%20Dict,%20Set%20%26%20Generator%20Expressions.ipynb)
- [`04 - Iterable vs Iterator`](notebooks/06%20-%20Comprehensions,%20Iterators%20%26%20Generators/04%20-%20Iterable%20vs%20Iterator.ipynb)
- [`05 - Generators`](notebooks/06%20-%20Comprehensions,%20Iterators%20%26%20Generators/05%20-%20Generators.ipynb)
- [`06 - Scope & the Walrus Operator`](notebooks/06%20-%20Comprehensions,%20Iterators%20%26%20Generators/06%20-%20Scope%20%26%20the%20Walrus%20Operator.ipynb)
- [`07 - Performance, Readability & Best Practices`](notebooks/06%20-%20Comprehensions,%20Iterators%20%26%20Generators/07%20-%20Performance,%20Readability%20%26%20Best%20Practices.ipynb)

</details>

<details>
<summary><strong>07 - Standard Library Essentials</strong> (6 notebooks)</summary>

- [`01 - math, statistics, decimal & fractions`](notebooks/07%20-%20Standard%20Library%20Essentials/01%20-%20math,%20statistics,%20decimal%20%26%20fractions.ipynb)
- [`02 - random`](notebooks/07%20-%20Standard%20Library%20Essentials/02%20-%20random.ipynb)
- [`03 - datetime & time`](notebooks/07%20-%20Standard%20Library%20Essentials/03%20-%20datetime%20%26%20time.ipynb)
- [`04 - Counter & defaultdict`](notebooks/07%20-%20Standard%20Library%20Essentials/04%20-%20Counter%20%26%20defaultdict.ipynb)
- [`05 - deque, namedtuple, OrderedDict & ChainMap`](notebooks/07%20-%20Standard%20Library%20Essentials/05%20-%20deque,%20namedtuple,%20OrderedDict%20%26%20ChainMap.ipynb)
- [`06 - functools`](notebooks/07%20-%20Standard%20Library%20Essentials/06%20-%20functools.ipynb)

</details>

<details>
<summary><strong>08 - Itertools</strong> (8 notebooks)</summary>

- [`01 - Itertools Foundations`](notebooks/08%20-%20Itertools/01%20-%20Itertools%20Foundations.ipynb)
- [`02 - Infinite Iterators`](notebooks/08%20-%20Itertools/02%20-%20Infinite%20Iterators.ipynb)
- [`03 - Filtering & Slicing Iterators`](notebooks/08%20-%20Itertools/03%20-%20Filtering%20%26%20Slicing%20Iterators.ipynb)
- [`04 - Chaining, Zipping & Mapping`](notebooks/08%20-%20Itertools/04%20-%20Chaining,%20Zipping%20%26%20Mapping.ipynb)
- [`05 - Accumulate, Pairwise, Batched & Tee`](notebooks/08%20-%20Itertools/05%20-%20Accumulate,%20Pairwise,%20Batched%20%26%20Tee.ipynb)
- [`06 - Grouping with groupby`](notebooks/08%20-%20Itertools/06%20-%20Grouping%20with%20groupby.ipynb)
- [`07 - Combinatoric Iterators`](notebooks/08%20-%20Itertools/07%20-%20Combinatoric%20Iterators.ipynb)
- [`08 - Recipes, Patterns & Best Practices`](notebooks/08%20-%20Itertools/08%20-%20Recipes,%20Patterns%20%26%20Best%20Practices.ipynb)

</details>

<details>
<summary><strong>09 - Files & Data Formats</strong> (6 notebooks)</summary>

- [`01 - File Handling`](notebooks/09%20-%20Files%20%26%20Data%20Formats/01%20-%20File%20Handling.ipynb)
- [`02 - Additional File Methods`](notebooks/09%20-%20Files%20%26%20Data%20Formats/02%20-%20Additional%20File%20Methods.ipynb)
- [`03 - Paths with pathlib`](notebooks/09%20-%20Files%20%26%20Data%20Formats/03%20-%20Paths%20with%20pathlib.ipynb)
- [`04 - os, sys & shutil`](notebooks/09%20-%20Files%20%26%20Data%20Formats/04%20-%20os,%20sys%20%26%20shutil.ipynb)
- [`05 - JSON Files`](notebooks/09%20-%20Files%20%26%20Data%20Formats/05%20-%20JSON%20Files.ipynb)
- [`06 - CSV Files`](notebooks/09%20-%20Files%20%26%20Data%20Formats/06%20-%20CSV%20Files.ipynb)

</details>

<details>
<summary><strong>10 - Regular Expressions</strong> (5 notebooks)</summary>

- [`01 - Regular Expressions Foundations`](notebooks/10%20-%20Regular%20Expressions/01%20-%20Regular%20Expressions%20Foundations.ipynb)
- [`02 - Regex Syntax, Character Classes & Quantifiers`](notebooks/10%20-%20Regular%20Expressions/02%20-%20Regex%20Syntax,%20Character%20Classes%20%26%20Quantifiers.ipynb)
- [`03 - Regex Groups, Alternation & Assertions`](notebooks/10%20-%20Regular%20Expressions/03%20-%20Regex%20Groups,%20Alternation%20%26%20Assertions.ipynb)
- [`04 - Regex Functions, Match Objects & Replacement`](notebooks/10%20-%20Regular%20Expressions/04%20-%20Regex%20Functions,%20Match%20Objects%20%26%20Replacement.ipynb)
- [`05 - Regex Flags, Performance & Best Practices`](notebooks/10%20-%20Regular%20Expressions/05%20-%20Regex%20Flags,%20Performance%20%26%20Best%20Practices.ipynb)

</details>

<details>
<summary><strong>11 - Object Oriented Programming</strong> (16 notebooks)</summary>

- [`01 - OOP Foundations`](notebooks/11%20-%20Object%20Oriented%20Programming/01%20-%20OOP%20Foundations.ipynb)
- [`02 - Classes, Instances & __init__`](notebooks/11%20-%20Object%20Oriented%20Programming/02%20-%20Classes,%20Instances%20%26%20__init__.ipynb)
- [`03 - Attributes & Methods`](notebooks/11%20-%20Object%20Oriented%20Programming/03%20-%20Attributes%20%26%20Methods.ipynb)
- [`04 - Encapsulation & Properties`](notebooks/11%20-%20Object%20Oriented%20Programming/04%20-%20Encapsulation%20%26%20Properties.ipynb)
- [`05 - Class & Static Methods`](notebooks/11%20-%20Object%20Oriented%20Programming/05%20-%20Class%20%26%20Static%20Methods.ipynb)
- [`06 - Inheritance & super`](notebooks/11%20-%20Object%20Oriented%20Programming/06%20-%20Inheritance%20%26%20super.ipynb)
- [`07 - Custom Exceptions & Chaining`](notebooks/11%20-%20Object%20Oriented%20Programming/07%20-%20Custom%20Exceptions%20%26%20Chaining.ipynb)
- [`08 - Multiple Inheritance, MRO & Mixins`](notebooks/11%20-%20Object%20Oriented%20Programming/08%20-%20Multiple%20Inheritance,%20MRO%20%26%20Mixins.ipynb)
- [`09 - Polymorphism, Duck Typing & Composition`](notebooks/11%20-%20Object%20Oriented%20Programming/09%20-%20Polymorphism,%20Duck%20Typing%20%26%20Composition.ipynb)
- [`10 - Abstract Base Classes`](notebooks/11%20-%20Object%20Oriented%20Programming/10%20-%20Abstract%20Base%20Classes.ipynb)
- [`11 - Dunder Methods & Operator Overloading`](notebooks/11%20-%20Object%20Oriented%20Programming/11%20-%20Dunder%20Methods%20%26%20Operator%20Overloading.ipynb)
- [`12 - Context Managers`](notebooks/11%20-%20Object%20Oriented%20Programming/12%20-%20Context%20Managers.ipynb)
- [`13 - Object Model, Descriptors & __slots__`](notebooks/11%20-%20Object%20Oriented%20Programming/13%20-%20Object%20Model,%20Descriptors%20%26%20__slots__.ipynb)
- [`14 - Dataclasses & Enums`](notebooks/11%20-%20Object%20Oriented%20Programming/14%20-%20Dataclasses%20%26%20Enums.ipynb)
- [`15 - Class Patterns`](notebooks/11%20-%20Object%20Oriented%20Programming/15%20-%20Class%20Patterns.ipynb)
- [`16 - OOP Design, Advanced Patterns & Best Practices`](notebooks/11%20-%20Object%20Oriented%20Programming/16%20-%20OOP%20Design,%20Advanced%20Patterns%20%26%20Best%20Practices.ipynb)

</details>

<details>
<summary><strong>12 - Advanced Type Hinting</strong> (4 notebooks)</summary>

- [`01 - TypeVar, Generic, Literal, Final & ClassVar`](notebooks/12%20-%20Advanced%20Type%20Hinting/01%20-%20TypeVar,%20Generic,%20Literal,%20Final%20%26%20ClassVar.ipynb)
- [`02 - Protocols, TypedDict, NamedTuple & Callable`](notebooks/12%20-%20Advanced%20Type%20Hinting/02%20-%20Protocols,%20TypedDict,%20NamedTuple%20%26%20Callable.ipynb)
- [`03 - Advanced Type Hints_ Self, TypeGuard, overload, ParamSpec & Annotated`](notebooks/12%20-%20Advanced%20Type%20Hinting/03%20-%20Advanced%20Type%20Hints_%20Self,%20TypeGuard,%20overload,%20ParamSpec%20%26%20Annotated.ipynb)
- [`04 - Typing Tools, Runtime Introspection & Python 3.14 Notes`](notebooks/12%20-%20Advanced%20Type%20Hinting/04%20-%20Typing%20Tools,%20Runtime%20Introspection%20%26%20Python%203.14%20Notes.ipynb)

</details>

<details>
<summary><strong>13 - Building Real Programs</strong> (6 notebooks)</summary>

- [`01 - Packages & the __main__ Guard`](notebooks/13%20-%20Building%20Real%20Programs/01%20-%20Packages%20%26%20the%20__main__%20Guard.ipynb)
- [`02 - Command-Line Arguments`](notebooks/13%20-%20Building%20Real%20Programs/02%20-%20Command-Line%20Arguments.ipynb)
- [`03 - External Packages`](notebooks/13%20-%20Building%20Real%20Programs/03%20-%20External%20Packages.ipynb)
- [`04 - Logging`](notebooks/13%20-%20Building%20Real%20Programs/04%20-%20Logging.ipynb)
- [`05 - Unit Testing with unittest`](notebooks/13%20-%20Building%20Real%20Programs/05%20-%20Unit%20Testing%20with%20unittest.ipynb)
- [`06 - doctest`](notebooks/13%20-%20Building%20Real%20Programs/06%20-%20doctest.ipynb)

</details>

<details>
<summary><strong>14 - Quick References</strong> (2 notebooks)</summary>

- [`01 - Keywords`](notebooks/14%20-%20Quick%20References/01%20-%20Keywords.ipynb)
- [`02 - Built-in Functions`](notebooks/14%20-%20Quick%20References/02%20-%20Built-in%20Functions.ipynb)

</details>

## Read it offline

Export the unified notebook to a single HTML file. It opens in any browser without Python or an internet connection, and the roadmap links and Ctrl+F search work:

```bash
jupyter nbconvert --to html --execute kaggle/Python-Complete-Reference.ipynb
```

`--execute` runs every cell first and stops at the first error, so the command also checks that the notebook still runs top to bottom.

## Run it locally

Only Python and JupyterLab are needed. The notebooks use the standard library only, so there is nothing else to install.

```bash
cd python-complete-reference
pip install jupyterlab
jupyter lab
```

Notes:

- **Python version:** use Python 3.13 or newer for the offline notebooks. Two notebooks demonstrate newer features (`type` aliases need 3.12+, `typing.TypeIs` needs 3.13+). The unified notebook in `kaggle/` includes version guards and is written to run on Python 3.11 or newer. It was executed from top to bottom on Python 3.12.
- **Run cell by cell in the offline notebooks.** Some cells show errors or wait for keyboard input on purpose, so "Run All" can stop early there. The unified notebook is the version designed for "Run All".
- **Language:** everything in this repository is in English.

## Repository layout

```text
python-complete-reference/
├── README.md
├── LICENSE
├── kaggle/
│   ├── Python-Complete-Reference.ipynb   # unified notebook (source of the Kaggle notebook)
│   └── kernel-metadata.json              # Kaggle API metadata
└── notebooks/
    ├── 00 - Python Notebook Content.ipynb
    ├── 01 - Python Basics/
    ├── 02 - Control Flow/
    ├── 03 - Data Structures/
    ├── 04 - Functions/
    ├── 05 - Errors, Debugging & Profiling/
    ├── 06 - Comprehensions, Iterators & Generators/
    ├── 07 - Standard Library Essentials/
    ├── 08 - Itertools/
    ├── 09 - Files & Data Formats/
    ├── 10 - Regular Expressions/
    ├── 11 - Object Oriented Programming/
    ├── 12 - Advanced Type Hinting/
    ├── 13 - Building Real Programs/
    └── 14 - Quick References/
```

## Update the Kaggle notebook

After editing `kaggle/Python-Complete-Reference.ipynb`, push it with the [Kaggle CLI](https://github.com/Kaggle/kaggle-cli):

```bash
kaggle kernels push -p kaggle
```

Keep your Kaggle API credentials (`kaggle.json`) out of the repository. It is already listed in `.gitignore`.

## License

[MIT](LICENSE)

Maintained by [mahmoud15 on Kaggle](https://www.kaggle.com/mahmoud15). Issues and suggestions are welcome.

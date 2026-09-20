# Python Complete Reference

A structured, notebook-based Python reference: from syntax basics to object oriented programming, regular expressions, type hints, comprehensions and itertools. Every topic is a notebook with explanations and code examples.

**Read it online:** [Python Complete Reference Notebook on Kaggle](https://www.kaggle.com/code/mahmoud15/python-complete-reference-notebook)

## What is inside

- **Offline notebooks** in [`notebooks/`](notebooks/): 71 notebooks in 12 folders, one topic per notebook, meant for studying and quick lookup.
- **One unified notebook** in [`kaggle/`](kaggle/): all 12 parts in a single file (276 cells, 122 of them code) with a clickable roadmap and a table of contents. It is designed to run top to bottom without manual input and is the source of the Kaggle notebook above.

## Roadmap

Part `N` of the unified notebook is the folder `N - ...` in `notebooks/`, and section `N.M` is file `M - ...` inside that folder. For example, section 5.9 (Decorators) is [`05 - Functions/09 - Decorators`](notebooks/05%20-%20Functions/09%20-%20Decorators.ipynb).

| Part | Topic | Notebooks | What it covers | Suggested background |
|---|---|---|---|---|
| 1 | [Python Fundamentals](notebooks/01%20-%20Python%20Fundamentals) | 7 | Comments, data types & strings, variables, type conversion, user input, operators, all 35 keywords | Start here |
| 2 | [Python Collections](notebooks/02%20-%20Python%20Collections) | 5 | Lists, tuples, sets & frozen sets, dictionaries, booleans, container comparison guide | Part 1 |
| 3 | [Built-ins & Modules](notebooks/03%20-%20Built-ins%20%26%20Modules) | 3 | Built-in functions by category, built-in modules and `import`, external packages with `pip` | Parts 1-2 |
| 4 | [Control Flow](notebooks/04%20-%20Control%20Flow) | 5 | `if` / `elif` / `else`, `while` and `for` loops, iterables vs iterators, generators | Parts 1-2 |
| 5 | [Functions](notebooks/05%20-%20Functions) | 10 | Parameters, defaults, `*args` / `**kwargs`, scope, `return`, recursion, lambda, decorators, docstrings | Parts 1, 4 |
| 6 | [File Handling](notebooks/06%20-%20File%20Handling) | 2 | Opening, reading and writing files, file modes, `seek` / `tell` and other file methods | Parts 1, 5 |
| 7 | [Errors & Exceptions](notebooks/07%20-%20Errors%20%26%20Exceptions) | 2 | Common exception types, `raise`, `try` / `except` / `else` / `finally` | Parts 1, 4, 5 |
| 8 | [Regular Expressions](notebooks/08%20-%20Regular%20Expressions) | 5 | Regex syntax, character classes, quantifiers, groups, assertions, the `re` functions, flags and performance | Part 1 (strings) |
| 9 | [Object Oriented Programming](notebooks/09%20-%20Object%20Oriented%20Programming) | 13 | Classes, encapsulation, inheritance and MRO, polymorphism, ABCs, dunder methods, descriptors, dataclasses, design patterns | Parts 1-5, 7 |
| 10 | [Type Hinting](notebooks/10%20-%20Type%20Hinting) | 6 | Type hint basics, unions and aliases, generics, protocols, `TypedDict`, advanced typing, runtime introspection, 3.14 notes | Parts 5, 9 |
| 11 | [Comprehensions](notebooks/11%20-%20Comprehensions) | 5 | List, set, dict and generator expressions, conditions, nested comprehensions, scope, the walrus operator, async comprehensions, performance and readability | Parts 1-2, 4 |
| 12 | [Itertools](notebooks/12%20-%20Itertools) | 8 | Infinite iterators, slicing and filtering, chaining and zipping, `accumulate` / `pairwise` / `batched` / `tee`, `groupby`, combinatorics, recipes | Parts 4, 5, 11 |

## Notebook index

Open [`00 - Python Notebook Content`](notebooks/00%20-%20Python%20Notebook%20Content.ipynb) for a quick offline index (written in Arabic), or use the list below.

<details>
<summary><strong>01 - Python Fundamentals</strong> (7 notebooks)</summary>

- [`01 - Comments`](notebooks/01%20-%20Python%20Fundamentals/01%20-%20Comments.ipynb)
- [`02 - Data Types`](notebooks/01%20-%20Python%20Fundamentals/02%20-%20Data%20Types.ipynb)
- [`03 - Variables`](notebooks/01%20-%20Python%20Fundamentals/03%20-%20Variables.ipynb)
- [`04 - Type Conversion`](notebooks/01%20-%20Python%20Fundamentals/04%20-%20Type%20Conversion.ipynb)
- [`05 - User Input`](notebooks/01%20-%20Python%20Fundamentals/05%20-%20User%20Input.ipynb)
- [`06 - Operators`](notebooks/01%20-%20Python%20Fundamentals/06%20-%20Operators.ipynb)
- [`07 - Keywords`](notebooks/01%20-%20Python%20Fundamentals/07%20-%20Keywords.ipynb)

</details>

<details>
<summary><strong>02 - Python Collections</strong> (5 notebooks)</summary>

- [`01 - Lists`](notebooks/02%20-%20Python%20Collections/01%20-%20Lists.ipynb)
- [`02 - Tuples`](notebooks/02%20-%20Python%20Collections/02%20-%20Tuples.ipynb)
- [`03 - Sets & Frozen Sets`](notebooks/02%20-%20Python%20Collections/03%20-%20Sets%20%26%20Frozen%20Sets.ipynb)
- [`04 - Dictionaries`](notebooks/02%20-%20Python%20Collections/04%20-%20Dictionaries.ipynb)
- [`05 - Boolean & Containers Comparison`](notebooks/02%20-%20Python%20Collections/05%20-%20Boolean%20%26%20Containers%20Comparison.ipynb)

</details>

<details>
<summary><strong>03 - Built-ins & Modules</strong> (3 notebooks)</summary>

- [`01 - Built-in Functions`](notebooks/03%20-%20Built-ins%20%26%20Modules/01%20-%20Built-in%20Functions.ipynb)
- [`02 - Built-in Modules`](notebooks/03%20-%20Built-ins%20%26%20Modules/02%20-%20Built-in%20Modules.ipynb)
- [`03 - External Packages`](notebooks/03%20-%20Built-ins%20%26%20Modules/03%20-%20External%20Packages.ipynb)

</details>

<details>
<summary><strong>04 - Control Flow</strong> (5 notebooks)</summary>

- [`01 - If Elif Else`](notebooks/04%20-%20Control%20Flow/01%20-%20If%20Elif%20Else.ipynb)
- [`02 - While Loop`](notebooks/04%20-%20Control%20Flow/02%20-%20While%20Loop.ipynb)
- [`03 - For Loop`](notebooks/04%20-%20Control%20Flow/03%20-%20For%20Loop.ipynb)
- [`04 - Iterable vs Iterator`](notebooks/04%20-%20Control%20Flow/04%20-%20Iterable%20vs%20Iterator.ipynb)
- [`05 - Generators`](notebooks/04%20-%20Control%20Flow/05%20-%20Generators.ipynb)

</details>

<details>
<summary><strong>05 - Functions</strong> (10 notebooks)</summary>

- [`01 - Functions Basics`](notebooks/05%20-%20Functions/01%20-%20Functions%20Basics.ipynb)
- [`02 - Parameters & Arguments`](notebooks/05%20-%20Functions/02%20-%20Parameters%20%26%20Arguments.ipynb)
- [`03 - Default Parameters`](notebooks/05%20-%20Functions/03%20-%20Default%20Parameters.ipynb)
- [`04 - Args Kwargs & Unpacking`](notebooks/05%20-%20Functions/04%20-%20Args%20Kwargs%20%26%20Unpacking.ipynb)
- [`05 - Function Scope`](notebooks/05%20-%20Functions/05%20-%20Function%20Scope.ipynb)
- [`06 - Return Statement`](notebooks/05%20-%20Functions/06%20-%20Return%20Statement.ipynb)
- [`07 - Recursion`](notebooks/05%20-%20Functions/07%20-%20Recursion.ipynb)
- [`08 - Lambda Functions`](notebooks/05%20-%20Functions/08%20-%20Lambda%20Functions.ipynb)
- [`09 - Decorators`](notebooks/05%20-%20Functions/09%20-%20Decorators.ipynb)
- [`10 - Docstrings`](notebooks/05%20-%20Functions/10%20-%20Docstrings.ipynb)

</details>

<details>
<summary><strong>06 - File Handling</strong> (2 notebooks)</summary>

- [`01 - File Handling`](notebooks/06%20-%20File%20Handling/01%20-%20File%20Handling.ipynb)
- [`02 - Additional File Methods`](notebooks/06%20-%20File%20Handling/02%20-%20Additional%20File%20Methods.ipynb)

</details>

<details>
<summary><strong>07 - Errors & Exceptions</strong> (2 notebooks)</summary>

- [`01 - Errors & Exceptions`](notebooks/07%20-%20Errors%20%26%20Exceptions/01%20-%20Errors%20%26%20Exceptions.ipynb)
- [`02 - Exception Handling`](notebooks/07%20-%20Errors%20%26%20Exceptions/02%20-%20Exception%20Handling.ipynb)

</details>

<details>
<summary><strong>08 - Regular Expressions</strong> (5 notebooks)</summary>

- [`01 - Regular Expressions Foundations`](notebooks/08%20-%20Regular%20Expressions/01%20-%20Regular%20Expressions%20Foundations.ipynb)
- [`02 - Regex Syntax, Character Classes & Quantifiers`](notebooks/08%20-%20Regular%20Expressions/02%20-%20Regex%20Syntax,%20Character%20Classes%20%26%20Quantifiers.ipynb)
- [`03 - Regex Groups, Alternation & Assertions`](notebooks/08%20-%20Regular%20Expressions/03%20-%20Regex%20Groups,%20Alternation%20%26%20Assertions.ipynb)
- [`04 - Regex Functions, Match Objects & Replacement`](notebooks/08%20-%20Regular%20Expressions/04%20-%20Regex%20Functions,%20Match%20Objects%20%26%20Replacement.ipynb)
- [`05 - Regex Flags, Performance & Best Practices`](notebooks/08%20-%20Regular%20Expressions/05%20-%20Regex%20Flags,%20Performance%20%26%20Best%20Practices.ipynb)

</details>

<details>
<summary><strong>09 - Object Oriented Programming</strong> (13 notebooks)</summary>

- [`01 - OOP Foundations`](notebooks/09%20-%20Object%20Oriented%20Programming/01%20-%20OOP%20Foundations.ipynb)
- [`02 - Classes, Instances & __init__`](notebooks/09%20-%20Object%20Oriented%20Programming/02%20-%20Classes,%20Instances%20%26%20__init__.ipynb)
- [`03 - Attributes & Methods`](notebooks/09%20-%20Object%20Oriented%20Programming/03%20-%20Attributes%20%26%20Methods.ipynb)
- [`04 - Encapsulation & Properties`](notebooks/09%20-%20Object%20Oriented%20Programming/04%20-%20Encapsulation%20%26%20Properties.ipynb)
- [`05 - Class & Static Methods`](notebooks/09%20-%20Object%20Oriented%20Programming/05%20-%20Class%20%26%20Static%20Methods.ipynb)
- [`06 - Inheritance & super`](notebooks/09%20-%20Object%20Oriented%20Programming/06%20-%20Inheritance%20%26%20super.ipynb)
- [`07 - Multiple Inheritance, MRO & Mixins`](notebooks/09%20-%20Object%20Oriented%20Programming/07%20-%20Multiple%20Inheritance,%20MRO%20%26%20Mixins.ipynb)
- [`08 - Polymorphism, Duck Typing & Composition`](notebooks/09%20-%20Object%20Oriented%20Programming/08%20-%20Polymorphism,%20Duck%20Typing%20%26%20Composition.ipynb)
- [`09 - Abstract Base Classes`](notebooks/09%20-%20Object%20Oriented%20Programming/09%20-%20Abstract%20Base%20Classes.ipynb)
- [`10 - Dunder Methods & Operator Overloading`](notebooks/09%20-%20Object%20Oriented%20Programming/10%20-%20Dunder%20Methods%20%26%20Operator%20Overloading.ipynb)
- [`11 - Object Model, Descriptors & __slots__`](notebooks/09%20-%20Object%20Oriented%20Programming/11%20-%20Object%20Model,%20Descriptors%20%26%20__slots__.ipynb)
- [`12 - Dataclasses & Enums`](notebooks/09%20-%20Object%20Oriented%20Programming/12%20-%20Dataclasses%20%26%20Enums.ipynb)
- [`13 - OOP Design, Advanced Patterns & Best Practices`](notebooks/09%20-%20Object%20Oriented%20Programming/13%20-%20OOP%20Design,%20Advanced%20Patterns%20%26%20Best%20Practices.ipynb)

</details>

<details>
<summary><strong>10 - Type Hinting</strong> (6 notebooks)</summary>

- [`01 - Type Hints Foundations`](notebooks/10%20-%20Type%20Hinting/01%20-%20Type%20Hints%20Foundations.ipynb)
- [`02 - Collections, Union Types & Type Aliases`](notebooks/10%20-%20Type%20Hinting/02%20-%20Collections,%20Union%20Types%20%26%20Type%20Aliases.ipynb)
- [`03 - TypeVar, Generic, Literal, Final & ClassVar`](notebooks/10%20-%20Type%20Hinting/03%20-%20TypeVar,%20Generic,%20Literal,%20Final%20%26%20ClassVar.ipynb)
- [`04 - Protocols, TypedDict, NamedTuple & Callable`](notebooks/10%20-%20Type%20Hinting/04%20-%20Protocols,%20TypedDict,%20NamedTuple%20%26%20Callable.ipynb)
- [`05 - Advanced Type Hints_ Self, TypeGuard, overload, ParamSpec & Annotated`](notebooks/10%20-%20Type%20Hinting/05%20-%20Advanced%20Type%20Hints_%20Self,%20TypeGuard,%20overload,%20ParamSpec%20%26%20Annotated.ipynb)
- [`06 - Typing Tools, Runtime Introspection & Python 3.14 Notes`](notebooks/10%20-%20Type%20Hinting/06%20-%20Typing%20Tools,%20Runtime%20Introspection%20%26%20Python%203.14%20Notes.ipynb)

</details>

<details>
<summary><strong>11 - Comprehensions</strong> (5 notebooks)</summary>

- [`01 - Comprehensions Foundations`](notebooks/11%20-%20Comprehensions/01%20-%20Comprehensions%20Foundations.ipynb)
- [`02 - Conditions, Multiple Loops & Nested Comprehensions`](notebooks/11%20-%20Comprehensions/02%20-%20Conditions,%20Multiple%20Loops%20%26%20Nested%20Comprehensions.ipynb)
- [`03 - Dict, Set & Generator Expressions`](notebooks/11%20-%20Comprehensions/03%20-%20Dict,%20Set%20%26%20Generator%20Expressions.ipynb)
- [`04 - Scope, Walrus Operator & Async Comprehensions`](notebooks/11%20-%20Comprehensions/04%20-%20Scope,%20Walrus%20Operator%20%26%20Async%20Comprehensions.ipynb)
- [`05 - Performance, Readability & Best Practices`](notebooks/11%20-%20Comprehensions/05%20-%20Performance,%20Readability%20%26%20Best%20Practices.ipynb)

</details>

<details>
<summary><strong>12 - Itertools</strong> (8 notebooks)</summary>

- [`01 - Itertools Foundations`](notebooks/12%20-%20Itertools/01%20-%20Itertools%20Foundations.ipynb)
- [`02 - Infinite Iterators`](notebooks/12%20-%20Itertools/02%20-%20Infinite%20Iterators.ipynb)
- [`03 - Filtering & Slicing Iterators`](notebooks/12%20-%20Itertools/03%20-%20Filtering%20%26%20Slicing%20Iterators.ipynb)
- [`04 - Chaining, Zipping & Mapping`](notebooks/12%20-%20Itertools/04%20-%20Chaining,%20Zipping%20%26%20Mapping.ipynb)
- [`05 - Accumulate, Pairwise, Batched & Tee`](notebooks/12%20-%20Itertools/05%20-%20Accumulate,%20Pairwise,%20Batched%20%26%20Tee.ipynb)
- [`06 - Grouping with groupby`](notebooks/12%20-%20Itertools/06%20-%20Grouping%20with%20groupby.ipynb)
- [`07 - Combinatoric Iterators`](notebooks/12%20-%20Itertools/07%20-%20Combinatoric%20Iterators.ipynb)
- [`08 - Recipes, Patterns & Best Practices`](notebooks/12%20-%20Itertools/08%20-%20Recipes,%20Patterns%20%26%20Best%20Practices.ipynb)

</details>

## Run it locally

Only Python and JupyterLab are needed. The notebooks use the standard library only, so there is nothing else to install.

```bash
cd python-complete-reference
pip install jupyterlab
jupyter lab
```

Notes:

- **Python version:** use Python 3.13 or newer for the offline notebooks. Two Type Hinting notebooks demonstrate newer features (`type` aliases need 3.12+, `typing.TypeIs` needs 3.13+). The unified notebook in `kaggle/` includes version guards and is written to run on Python 3.11 or newer.
- **Run cell by cell in the offline notebooks.** Some cells show errors or wait for keyboard input on purpose, so "Run All" can stop early there. The unified notebook is the version designed for "Run All".
- **Language:** everything is in English, except the `00` index notebook and two short annotations in `01 - Python Fundamentals/02 - Data Types` and `02 - Python Collections/03 - Sets & Frozen Sets`, which contain a few Arabic words.

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
    ├── 01 - Python Fundamentals/
    ├── 02 - Python Collections/
    ├── 03 - Built-ins & Modules/
    ├── 04 - Control Flow/
    ├── 05 - Functions/
    ├── 06 - File Handling/
    ├── 07 - Errors & Exceptions/
    ├── 08 - Regular Expressions/
    ├── 09 - Object Oriented Programming/
    ├── 10 - Type Hinting/
    ├── 11 - Comprehensions/
    └── 12 - Itertools/
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

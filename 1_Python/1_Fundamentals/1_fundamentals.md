# Python Type Hierarchy: 
- Numbers: 
    - Integral: Integers, Booleans,
    - Non-Integral:  Floats (c doubles),**Complex** ,Decimals, Fractions

- Collections:
    - Sequences:a) Mutable: Lists  b) Immutable: Tuples and Strings
    - Sets: a) Mutable: Sets   b) Immutable: Frozen Sets
    - Mappings: Dictionaries

  - Callables: User-Defined Functions, Generators, classes, Instance Methods, Class Instances (__call__()), Built-in Functions (e.g. len(), open()), Built-in Methods (e.g. my_list.append(x))
  - Singletons: None, NotImplemented, Ellipsis


- Single underscore for a variable(_my_var): 
	Variable starting with is a private variable/internal use (does not get imported in a module with statement from module import *)

- double underscore for a variable(__my_var): Userd for inheritance using dunder in front
- double underscore both side(__my_var__): System defined names:Eg __init__

### Naming convention: 
- Packages: shot, lowercase, no underscores
- Modules: Shot, lowercase with underscores
- Classes: CapWords Start(CamelCase)
- Function: lowercase + underscores
- Variables: lowercase + underscores
- Constants: All upper case + underscores

  
# Python Type Hierarchy: 
- Numbers: 
    - Integral: Integers, Booleans,
    - Non-Integral:  Floats (c doubles),**Complex(real+ Imaginary part)** ,Decimals, Fractions

- Collections:
    - Sequences:a) Mutable: Lists  b) Immutable: Tuples and Strings
    - Sets: a) Mutable: Sets   b) Immutable: Frozen Sets
    - Mappings: Dictionaries
      Note: Sets and dictionaries are both hash maps; the only difference issets haves only keys but no value, howeve,r dictionaries are key-value pairs.

  - Callables: User-Defined Functions, Generators, classes, Instance Methods, Class Instances (__call__()), Built-in Functions (e.g. len(), open()), Built-in Methods (e.g. my_list.append(x))
  - Singletons: None, NotImplemented, Ellipsis
 

Multi-Line String Literals: (' single or " double) ''' or  ""

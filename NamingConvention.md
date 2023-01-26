# NCPP Naming Convention #
## Prefixes: ##
+ It is more helpful in `distinguishing` and `identifying` the type of items.
+ `Syntax highlight` is good at distinguishing the type of items but its not good at identifying them because `the syntax high color` is different among `IDEs`, `Text Editors`, and `Themes`.
+ List of Prefixes:
    + Namespace:
        + **HN_** : `Helper Namespace`
    + Struct, Class, Enum, Union:
        + **IC_** : `Interface Class` (multiple inheritable)
        + **IS_** : `Interface Struct` (multiple inheritable)
        + **C_** : `Class` (single inheritable)
        + **S_** : `Struct` (single inheritable)
        + **E_** : `Enum`
        + **U_** : `Union`
    + Variable, Constant:
        + **m_** : `Member Variable` (use for private or protected member only)
        + **s_** : `Static Variable`
        + **g_** : `Global Variable`
        + **p_** : `Pointer of Variable`
        + **k_** : `Constant`
        + **l_** : `LValue Reference`
        + **r_** : `RValue Reference`
    + Template:
        + **T_** : `Template`
        + **TA_** : `Template Argument`
    + Multiple Prefixes:
        + **T_C_** : `Class Template`
        + **k_p_** : `Pointer Constant`
        + **p_k_** : `Pointer to Constant`
        + **m_p_** : `Pointer Member`
        + ...

## Casings: ##
- Pascal Case:    
    + **Struct**
    + **Class**
    + **Enum**
    + **Union**
    + **Function** 
    + **Member Variable**
    + **Non-Constant Pointer**
    + **Static Variable**
    + **Template**
- Camel Case:
    + **Ordinary Variable**
- Snake Case:
    + **Constant Pointer**
    + **Static Constant**
    + **Macro** (upper case)
    + **Constant** (upper case)
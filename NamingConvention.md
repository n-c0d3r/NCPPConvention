# NCPP Naming Convention #
## Prefix: ##
+ It is more helpful in `distinguishing` and `identifying` the type of items.
+ `Syntax highlight` is good at distinguishing the type of items but its not good at identifying them because `the syntax high color` is different among `IDEs`, `Text Editors`, and `Themes`.
+ Prefixes:
    + Namespace:
        + **HN_** : `Helper Namespace`
    + Struct, Class, Enum, Union:
        + **IC_** : `Interface Class` (multiple inheritable)
        + **IS_** : `Interface Struct` (multiple inheritable)
        + **C_** : `Class` (single inheritable)
        + **S_** : `Struct` (single inheritable)
        + **CC_** : `Completed Class` (non-inheritance)
        + **CS_** : `Completed Struct` (non-inheritance)
        + **E_** : `Enum`
        + **U_** : `Union`
    + Variable, Constant:
        + **m_** : `Member Variable` (prefer to use for private or protected member only)
        + **s_** : `Static Variable`
        + **g_** : `Global Variable`
        + **p_** : `Pointer of Variable`
        + **pp_** : `Pointer of Pointer of Variable`
        + **p..._** (there are `N` "p"): `Level N Pointer`\
            Ex: 
            + **p_A**: Level 1 Pointer
            + **pp_B**: Level 2 Pointer
            + **ppp_C**: Level 3 Pointer
            + ...
        + **k**... : `Constant`\
            Ex: 
            + **kg_PI**: PI constant which is also static variable
            + **k_NAME**: An ordinary constant
            + ...
        + **l_** : `LValue Reference`
        + **r_** : `RValue Reference`
    + Template:
        + **T**... : `Template`\
            Ex: 
            + **TIC_Person**: An Interface Class Template
            + **TC_Student**: A Class Template
            + **T_GetClassName**<TA_Class>(): A Function Template
            + ...
        + **TA_** : `Template Argument`

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
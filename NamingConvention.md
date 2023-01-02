# NCPP Naming Convention #
## Prefix: ##
+ It is more helpful in `distinguishing` and `identifying` the type of items.
+ `Syntax highlight` is good at distinguishing the type of items but its not good at identifying them because `the syntax high color` is different among `IDEs`, `Text Editors`, and `Themes`.
+ Prefixes:
    + Struct, Class, Enum, Union:
        + **IC_** : `Interface Class` (allow multiple inheritance)
        + **IS_** : `Interface Struct` (allow multiple inheritance)
        + **C_** : `Class` (only allow multiple inheritance)
        + **S_** : `Struct` (only allow multiple inheritance)
        + **CC_** : `Completed Class` (not allow inheritance)
        + **CS_** : `Completed Struct` (not allow inheritance)
        + **E_** : `Enum`
        + **U_** : `Union`
    + Macro, Function, Method:
        + **M_** : `Macro`
        + **F_** : `Function` or `Method`
    + Variable, Constant:
        + **m_** : `Member Variable` (prefer to use for private or protected member only)
        + **s_** : `Static Variable`
        + **g_** : `Global Variable`
        + **k**... : `Constant`\
            Ex: 
            + **kg_PI**: PI constant which is also static variable
            + **k_Name**: an ordinary constant
            + ...
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
    + **Static Variable**
    + **Template**
- Camel Case:
    + **Ordinary Variable**
- Snake Case:
    + **Macro** (upper case)
    + **Constant** (upper case)
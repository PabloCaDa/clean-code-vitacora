#Clean Code

##_The clean code stands for clarity and readability. It's tested enough and easy-handled on change since it is segmented as it needs to respecting entities concerns and scopes._ 


A good naming convention will gather format consistency, representative and non-extended names and clear readability:

    - Format consistency: same kind of files with the same naming format, i.e. camelCase for scripts, PascalCase for components.

    - Representative: Name each variable/function as per its intention, no it's type nor it's shape.  

    - Clear readability: Long names will lead to reading mistakes, i.e. how to tell getProductsWithExternalPermisionsFromDatabase() from getProductsWithInternalPermisionsFromDatabase(); despite names are reflecting what the method it's ment to do, they are hard to read.

    - Avoid misinformation and extended names: Avoid prefix and sufix like list or collection/array. I.E. ProductListData; words list and data are not giving any representational info as we can infer them from the word Products.
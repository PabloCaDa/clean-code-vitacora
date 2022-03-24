# Clean Code

##_The clean code stands for clarity and readability. It’s tested enough and easy-handled on change since it is segmented as it needs to respecting entities concerns and scopes._ 

## Naming

A good naming convention will gather format consistency, representative and non-extended names and clear readability:

    - Format consistency: same kind of files with the same naming format, i.e. camelCase for scripts, PascalCase for components.

    - Representative and non-extended names: Name each variable/function as per its intention. Avoid prefix and sufix as list or collection/array. I.E. ProductListData; word list and data are not giving any representational info as we can infer them from the word Products. 

    - Clear readability: Long names will lead to reading mistakes, i.e. how to tell getProductsWithExternalPermisionsFromDatabase() from getProductsWithInternalPermisionsFromDatabase(); despite names are reflecting what the method it's ment to do, they are hard to read.

# Functions

 Function naming should point to what the function does and, therefore, functions should do as expected from them and no more (SRP). They should be concise and do not mess with other abstraction levels (one abstraction level below is ok). In terms of arguments, the less we have the better, this will help with readability and testing will be far away more easy. 


# Comments

If you can avoid them...just do it. Code should speak by itself, so comments use to be an indicative that the code is not polish enough. Besides, comments are hard to maintain. However, there are some valid cases for comments like 

## Formatting

Try to find balance into your team preferences and find out a meeting point on everyone's preferences. From then on just stick to the formatting convention.

## Objects and Data Structure

Objects show behaviours and hide relevant data, whilst data structures expose information (getter/setter). Working with objects will give us some flexibility when adding new types but when not when a new functionality needs to be implemented. 

## Error handling


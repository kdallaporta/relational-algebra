# relational-algebra
A simple and non optimized implementation of relational algebra operators, based on Pandas, to understand better how they work.

## Unary operators :
- Selection operator : σ, to filter rows
- Projection operator : ∏, to select columns

## Binary operators :
- Union operator : ∪, to get A and B elements without duplicates
- Intersection operator : ∩, to get elements which are in A and B
- Substraction operator : -, to get elements which are in A and not in B
- Cartesian product operator : X, if it's of any use

## Joins :
- Join : ⋈, to add columns from another dataframe using a key
- Theta Join : ⋈θ, to filter a cartesian product on a condition

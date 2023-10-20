# relational-algebra
A simple and non optimized implementation of relational algebra operators, based on Pandas, to understand better how they work.

## Unary operators :
- Selection operator : σ, to filter rows
- Projection operator : ∏, to select columns

## Binary operators :
- Union operator : ∪, to get A and B elements without duplicates
- Intersection operator : ∩, to get elements which are in A and B
- Substraction operator : -, to get elements which are in A and not in B
- Cartesian product operator : X, return a combination of all rows of A and B
- Division  operator : /, keep values of A that exist in combinaison with all values of B

## Joins :
- Join : ⋈, to add columns from another dataframe using a key
- Theta Join : ⋈θ, to filter a cartesian product on a condition
- Semi join : ⋉, keep rows of A when their value of one column are included in a column B
- Antijoin : ▷, the inverse of a Semi join
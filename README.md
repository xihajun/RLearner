# RLearner

*R - a language that doesn't look like python ([R-2019](https://github.com/xihajun/R-tutorial))*

-------------
For a python user, R looks a bit weird for me. However, R is super useful in Bioinformatics. Hopefully, I can learn it as soon as possible. I might compare the code with python while I am learning to see **what makes R hard to learn**.


## Bacis operation
In python, filtering dataframe is a key operation to use. We can simply use `data[data.col_name == 'key']`. 

Let's see how it works in R:
- we can use `subset`: eg. `df_rna <- subset(df_hm, SRA_library_strategy == "RNA-Seq")`

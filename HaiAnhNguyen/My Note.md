# Lecture 4: Dependency Parsing

## 1. Dependency Relation

A dependency relation connects a head with its dependent.

$$
Head \rightarrow Dependent
$$

> [!example]
> submitted → Bills

Therefore:

- `submitted` = Head
- `Bills` = Dependent

> [!question]
> Why is `submitted` the head of `Bills`?

## 2. Representation

Each token can be represented by:

$$
x_i =
[e_i^{word};e_i^{POS};e_i^{dep}]
$$

Then several token representations are concatenated:

$$
x_{config}
=
[x_{S_1};x_{S_2};x_{b_1};...]
$$

> [!important]
> These embeddings are concatenated, not stacked
> into a `(3,x,y)` tensor.

## 3. Summary

> [!summary]
> Dependency parsing predicts the syntactic
> relationships between words.

## 4. Conslustion

>[!important]
>I love machine learning
>But I love you



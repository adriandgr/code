---
layout: resource
title:  "functions and loops"
date:   2014-07-25 16:59:48
author: nick
---

## Basic Math

You can do basic math in Python like this:

```python
>>> 1 + 2
2
```
Using `+` for addition, `-` for subtraction, `*` for multiplication, and `/`
for division.

**TODO:** mention `floats` vs. `ints`

## Basic Math With Variables

You can also make a variable that points to a number. For example, you can make
`x` effectively equal to `2` by writing `x = 2`. Then you can use `x` wherever
you would have used `2`:
```python
int x = 2;
x * 2;
print(x);
```
outputs:
```python
4
```
`print()` shows  *TODO*

Since `x` points to whatever piece of data you tell it to, you can change what
`x` means at any time:
```python
int x = 6;
x / 2;
print(x);
```
outputs:
```python
3
```
## Calculate Your Tax

Let's calculate the tax on a restaurant bill. We'll use a few variables to make
it clear which part of the equation is which.

(For simplicity sake, we'll do the calculation in cents, with no decimal
point.)

```python
int billAmount = 1500;
int PST = 12;
int tax = (billAmount / 100) * 12;
print(tax);
```
outputs:
```python
12500
```
## Aside: the way computers deal with numbers

*Aside:* by using the keyword `int`, *TODO*

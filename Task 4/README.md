If the Google Colab link does not work, use this: [Task 4 (Google Colab)](https://colab.research.google.com/drive/1jGiI9QhE1WpEwbgj0gO6jFfyZK5ODLLR?usp=sharing)

# Task4:  Feature Encoding & Scaling

This task explains some basic steps used before training a machine learning model.

---

## Out-of-Range Values

Sometimes data contains values that are very large or very small compared to others.
These values can affect the model badly.

To handle this, we **scale** the data so that all values stay within a reasonable range.

---

## Scaling

Scaling changes numerical values so they are on a similar scale.

This helps the model:

* Learn faster
* Perform better
* Avoid bias from large values

---

## Label Encoding

Label encoding converts categories into numbers.

Example:
Small → 0
Medium → 1
Large → 2

It is simple but should be used carefully.

---

## Ordinal Encoding

Ordinal encoding is used when categories have an order.

Example:
Low → 0
Medium → 1
High → 2

This keeps the correct order of values.

---

## One-Hot Encoding

One-hot encoding creates separate columns for each category.

Each column contains 0 or 1.

It is used when categories have **no order**.

---

## Why This Matters

Good preprocessing:

* Makes data clean
* Helps models learn correctly
* Improves accuracy



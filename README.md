# 🔍 Haskell: Extract the Two Oldest Persons Whose Names End With "A"

This small Haskell program demonstrates several core functional programming concepts, including:

- Working with lists  
- `zip` to combine multiple lists  
- Sorting with `sortOn`  
- Filtering with predicates  
- Pattern matching in list comprehensions  
- Mapping and transforming strings  
- Unit testing using **HUnit**

The goal of the task:

> **Find the two oldest persons whose names end with the letter "a", convert their names to uppercase, and return them sorted alphabetically.**

---

## 📄 Files

- **ExtractOldestNames.hs** – Main Haskell source code for the task  
- Uses **HUnit** for testing

---

## 🧠 Logic Overview

The program:

1. Combines names and ages into tuples  
2. Filters only names ending with `"a"`  
3. Sorts persons by descending age  
4. Takes the two oldest  
5. Converts their names to uppercase  
6. Sorts the final output alphabetically

---

## ✔ Example Output

Expected result of the task:

```

["EMMA", "ISABELLA"]

```

---

## 🧪 Running the Test

To run the HUnit test:

```

runhaskell ExtractOldestNames.hs

```

or

```

ghci ExtractOldestNames.hs

> main

```

---

## 🧑‍💻 Author

Created by **Obai Albek**  
For study purposes and GitHub portfolio.

---


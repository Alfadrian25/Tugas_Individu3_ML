# Python Data Structures Practice

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Status](https://img.shields.io/badge/Status-Learning-success)

## Overview

Repository ini berisi hasil praktik pemrograman Python yang mempelajari **struktur data dasar dalam Python**, yaitu:

- List
- Tuple
- Set
- Dictionary

Praktik ini dilakukan menggunakan **Jupyter Notebook** untuk memahami bagaimana Python digunakan dalam pengolahan data.

---

## Repository Structure

```

Tugas_Individu3_ML
│
├── Individu3_Python.ipynb
├── README.md

````

Keterangan:

- `data_structures.ipynb` → Notebook berisi kode praktik Python
- `README.md` → Dokumentasi repository

---

## Topics Covered

### 1. List

List adalah struktur data yang bersifat **mutable**, sehingga elemen di dalamnya dapat diubah.

Contoh:

```python
myList.append('hello')
myList.insert(1, 3.14)
myList.count('hello')
del myList[0]
````

---

### 2. Tuple

Tuple hampir sama dengan list tetapi bersifat **immutable**.

Contoh:

```python
myTuple = (10, 'hello', 14.5)
x, y, z = myTuple
```

---

### 3. Set

Set digunakan untuk menyimpan **data unik tanpa duplikasi**.

Contoh:

```python
mySet = {1, 3, 5}
mySet.add(7)
mySet.remove(3)
```

---

### 4. Dictionary

Dictionary menyimpan data dalam bentuk **key-value pair**.

Contoh:

```python
myDictionary = {
    "name": "John",
    "age": 30
}

print(myDictionary["name"])
```

---

## Data Structure Conversion

Contoh konversi struktur data:

```python
myList = [1,2,2,'hello']

mySet = set(myList)
myTuple = tuple(myList)
```

---

## Tools Used

* Python 3
* Jupyter Notebook
* Anaconda

---

## Author

**Alfadrian Januarsyah**
231001067
Informatika C

---
## Link Youtube : 

# https://youtu.be/qsPnN_rJkJU?si=oDnOmusZuoU8uXqx

```

# py

#### Write a program to find the occurence of vowels in a string

```python
s = input("Enter string: ")
vowels = ["a", "e", "i", "o", "u"]
count = 0
s = s.lower()
for i in vowels:
    if i in vowels:
        count = count + 1

print("No. of vowels, "+str(count))
```

#### Write a python program to find the occurence of a word in a string

```python
s = input("Enter the string: ")
s = s.lower().split()
t = input("Enter the word: ")
u = 0
for i in s:
    if i == t.lower():
        u += 1
print("Total occurence of", t, "is:", u)
```

#### Write a python program to find character frequency of words in a string

```python
s = input("Enter a string: ")
s = s.lower()
s = s.replace(" ", "")
dic = {}
for i in s:
    if i in dic:
        dic[i] += 1
    else:
        dic[i] = 1

for a, b in dic.items():
    print(a, ":", b)
```

#### To find the occurance of each word in a string

```python
s = input("Enter a string: ")
dic = {}
c = s.split()
for i in c:
    if i in dic:
        dic[i] += 1
    else:
        dic[i] = 1

print(dic)
```

#### Write a program to print the contents of a file in reverse order and sotre it in another file

```python
f = open("t.txt", "w")
f.write("apple is a fruit")
f.close()

f = open("t.txt", "r")
d = f.read()
x = d[::-1]
print(x)

f.open("tr.txt", "w")
f.write(x)
f.close

f = open("tr.txt", "r")
print(f.read())
```

#### Write a python program to copy all the contents of one file to another file in upper case

```python
f = open("po.txt", "w")
f.write("apple is a fruit")
f.close()

f = open("po.txt", "r")
d = f.read()
x = d.upper()
print(x)

f = open("tpo.txt", "w")
f.write(x)
f.close()

f = open("tpo.txt", "r")
print(f.read())
```



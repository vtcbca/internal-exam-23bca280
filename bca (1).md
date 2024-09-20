### Create BCA.txt. Write 5 lines directly and 5 lines must be taken from user. Print the smallest and largest word in this file.


```python
f=open("C:/23bca280/python/BCA.txt","w")
```


```python
f.write("pytho is very easy to understand")
```




    32




```python
f.write("python is very usefull for devloping games")
```




    42




```python
f.write("python is opensorce which is freely available")
```




    45




```python
f.write("Python is commonly used for developing websites and software")
```




    60




```python
f.write("High-level: human-friendly rather than computer-friendly")
```




    56




```python
f=open("C:/23bca280/python/BCA.txt","a")
```


```python
for i in range(5):
    user_input=input("enter any string")

```

    enter any value python support cross plateform devlopment
    enter any value python can be easyly interpreted by c/c++
    enter any value we can store it with .py extension
    enter any value python is dynamic type 
    enter any value it is easy to understand for every one
    


```python
f=open("C:/23bca280/python/BCA.txt","r")
```


```python
word=f.read().split()

```


```python
s_word=min(word,key=len)
s_word1=max(word,key=len)
```


```python
print(s_word)
```

    is
    


```python
print(s_word1)
```

    softwareHigh-level:
    


```python
f.close()

```


```python

```


```python

```


```python

```


```python

```


```python

```

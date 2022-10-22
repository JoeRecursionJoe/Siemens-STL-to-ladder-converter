# A (And)
Test

STL

```
A I1.0
A I1.1
= Q4.0
```

AB Neutral Text
```
XIC(I1.0)XIC(I1.1)OTE(Q4.0);
```

AB ASCII Text
```
XIC I1.0 XIC I1.1 OTE Q4.0
```

Ladder

```
  I1.0   I1.1   Q4.0
 --] [----] [----( )--
```


-------------------------

#  AN (And Not)




# O (Or)

STL
```
O I1.0
O I1.2
O I1.3
= Q3.0
```



AB Neutral Text
```
??
```

AB ASCII Text
```
??
```

Ladder
```
  I1.0         Q4.0
 --] [----------( )--
        |
  I1.2  |
 --] [---
        |
  I1.3  |
 --] [---
```



# ON (Or Not)





# X (Exclusive Or)


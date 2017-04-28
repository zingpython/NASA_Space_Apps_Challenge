

```python
def greeting():
    
    list_of_friends = ["Mark","Emily","John"]
    
    check_time = int(input("What time is it:"))
    
    for name in list_of_friends:
        if check_time < 7:
            print("Hello", name, "party starts at 7pm")
        elif check_time == 7:
            print("Hello", name, "you are right on time")
        else:
            print("Hello", name, "you are late")
    
    
    
    
greeting()
```

    What time is it:7
    Hello Mark you are right on time
    Hello Emily you are right on time
    Hello John you are right on time



```python

```

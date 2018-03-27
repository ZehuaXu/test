### How to open a file:

```
filename = raw_input('Enter file name: ')
job = open(filename, 'r')
for eachLine in job:
    print(eachLine)
job.close()
```

another method:

```
try:
    filename = raw_input('Enter file name: ')
    job = open(filename, 'r')
    for eachLine in job:
        print(eachLine)
    job.close()
except IOError, e:
    print('file open error: ' e)
    
```

and I have to mention that using 'raise' is also a good method.






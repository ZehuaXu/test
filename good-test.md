How to open a file:

```
filename = raw_input('Enter file name: ')
job = open(filename, 'r')
for eachLine in job:
    print(eachLine)
job.close()
```




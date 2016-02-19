
### 时序图
```sequence
a->b: are you ok?
Note right of b: fine, thanks !and you?
b-->a: i am good thanks!
```
### 流程图
```flow
st=>start: Start
e=>end
op=>operation: My Operation
cond=>condition: Yes or No?

st->op->cond
cond(yes)->e
cond(no)->op
```
### 代码块
``` python
@requires_authorization
def somefunc(param1='', param2=0):
       '''A docstring''' 
if param1 > param2: # interesting 
    print 'Greater' 
return (param2 - param1 + 1) or None
class SomeClass: 
          pass
>>> message = '''interpreter
... prompt'''
```


**Incrementing column numbers**

```
vector[0] = 1;       vector[0] = 1;
vector[0] = 1;       vector[1] = 1;
vector[0] = 1;  -->  vector[2] = 1;
vector[0] = 1;       vector[3] = 1;
vector[0] = 1;       vector[4] = 1;
```
`Put cursor on topmost zero, select column with Ctrl-v, then g Ctrl-a` 

**Change Inside brackets**

```
def foo(a, b, c, d, e)  -->  def foo()
```
`Put cursor inside the bracket and type ci(`


```
void foo()                    void foo()
{                             {
    int a;                    }
    int b       ---->          
    int c;                     
                          
}    
```
`Put cursor inside the bracket and type ci}`


**Change Around brackets**
```
def foo(a, b, c, d, e)  -->  def foo
```
`Put cursor inside the bracket and type ca(`

```
a = {a, b, c, d, e} ;  -->  a = ;
```
`Put cursor inside the bracket and type ca{`






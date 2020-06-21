## Applying Functional Principles in C#

### 1/ Functional Programming Features

- C# 3.0 : LINQ, Extension method  
- C# 6.0 : Read-only properties  
- C# 7.0 : pattern matching

### 2/ What is Functional Programming ?

- Mathemtical function != Class method  

#### 2.1/ Same input, same results

A method with same input  same result: 

```cs
public double Calculate (double x, double y)
{
  return x*x + y*y;
}
```

Here, the result is always different (the method uses a global state DateTime.Now will always change)
```cs
public long TicksElapsedFrom(int year)
{
  DateTime now = DateTime.Now //Global state
  DateTime then = new DateTime(year,1,1);
  return (now-then).Ticks;
}
```



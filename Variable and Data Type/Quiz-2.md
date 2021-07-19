<strong> <p> 1 . What will be the output of the following Python code? </p> </strong>
`
x=1
def fun():
    print(x)
fun()
`
<ol> 
  <li>Error</li>
  <li>1</li>
  <li>11</li>
  <li>None</li>
</ol>
  <p>Ans: 1 </p>

<strong> <p> 2 . What will be the output of the following Python code? </p> </strong>
`
x=1
def fun():
    global x
    x=x+1   
fun()
print(x)
`
<ol> 
  <li>Error</li>
  <li>1</li>
  <li>2</li>
  <li>None</li>
</ol>
  <p>Ans: 2 </p>

<strong> <p> 3 . What will be the output of the following Python code? </p> </strong>
`
def f1():
    global x
    x+=1
    print(x)

x=12
f1()
print("x")
`
<ol> 
  <li>Error</li>
  <li>13</li>
  <li>13 x (nextline)</li>
  <li>None</li>
</ol>
  <p>Ans: 13 x (nextline) </p>

<strong> <p> 4 . What will be the output of the following Python code? </p> </strong>
`
def fun():
    x=10
    print(x)
x=11
fun()
`
<ol> 
  <li>10</li>
  <li>Error</li>
  <li>11</li>
  <li>None</li>
</ol>
  <p>Ans: 10 </p>

<strong> <p> 5 . What will be the output of the following Python code? </p> </strong>
`
def fun():
    x = 10
fun()
print(x)
`
<ol> 
  <li>10</li>
  <li>Error</li>
  <li>11</li>
  <li>None</li>
</ol>
  <p>Ans: Error </p>

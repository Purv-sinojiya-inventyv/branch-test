### 1.Create a basic even-odd checking progam
```swift
var a:String? = readLine(),b=Int(a!)!;

if b%2 == 0 {
    print("even")
}
else{
    print("odd")
}
```
### 2.Write the Fizz-Buzz program upto 101. (look below for example)
```swift

var c:[Int:String] = [3:"fizz",5:"buzz",7:"cuzz"]
var count:Bool=true
for index in 1...100{
    count=true
    for (key,value) in c {
        if index % key == 0 {
            print("\(value)", terminator: "")
            count = false
        }
    }
    if count == true{
        print(index)
    }
    else{
        print()
    }
    
}```

### 3.Create a menu driven calculator program
```swift
var a:String? = readLine(),b=Int(a!)!;
var d=10;
var e=5;
switch b {
case 1:print(d*e)
case 2:print(d-e)
case 3:print(d*e)
case 4:print(d/e)
default : print("invalid input")
}```

### 4.Create a program to check if a number is palindrome
```swift
var a:String? = readLine(),b=Int(a!)!;
var count:Bool=true
for index in 2...b/2
{
   if b%index==0
   {
   count=false;
   break;
   }
}
if count==true{
	print("it is the palindrome")
}
else
{
 print("it is not palindrome")
}
```
### 5.Create a program to check if a number is armstrong
```swift

```
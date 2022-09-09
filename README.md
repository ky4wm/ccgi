# cCGI
An extremely lightweight library to create Common Gateway Interfaces in C or C++
## What does it include
### With this library you will get :
#### Get.h
a simple way to retain information coming from forms, sent via the get method
it weights just 356 bytes!
##### How to get keys sent with get
You just call the function with **get("keyname")** where keyname is the name of the field you want to retain.
You will get a string back.
If you have used PHP in the past, you'll find yourself at home!
It tries to mimic as much as possible the *$_GET['key'];* method.
As a matter of fact, i actually found the way php handles forms so good that I tried to port it to C/C++!
So yes, thats why i'm making this library.

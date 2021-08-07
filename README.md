 
# ARITHLANG

An arithmetic language assignment implementation.

There are sample source codes in the resource folder.

## Screenshots
### factorial test
```
a = - - 5;
print a;
fact = 1;
for (x = 5; x > 0; fact *= x, x--);
print fact;
```
<img src="screenshots/screen1.png" width=420em/></br>
</br>
### error test
```
print z;
```
<img src="screenshots/screen2.png" width=420em/></br>
</br>
### basic tests
```
a = 1;
a += a = 5 + 5;
print a;

y = 1;
y = y = 2 + y + 3;
x = 1;
print x;
x += 1;
print x;
print y;

z = 5 + (x = 5 + (y = 5 * 5 ));
if (x > 5){
    print x;
}
print y;
print z;
```
<img src="screenshots/screen3.png" width=420em/></br>

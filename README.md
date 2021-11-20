<p align="center">
  <h1 align="center">Text to Morse</h1>
  <p align="center"> Convert Text to Morse Code With Python  </p>
</p> 

## Simple Knowledge

Morse code is a method used in telecommunication to encode text characters as standardized sequences of two different signal durations, called dots and dashes, or dits and dahs. Morse code is named after Samuel Morse, one of the inventors of the telegraph.

## Python Code 

Enter a Text  to convert into MC

Copy code and test on Any Editor



```Python

Text = input()
print('YOUR TEXT ',Text,' IN MORSE IS ::')
print('')
for i in Text:
    i = i.upper()
    if (i == 'A'):
       print(i , '._')
    elif (i == 'B'):
       print(i , '_...')  
    elif (i == 'C'):
       print(i , '_._.')
    elif (i == 'D'):
       print(i , '_..')
    elif (i == 'E'):
       print(i , '.')
    elif (i == 'F'):  
       print(i , '.._.')
    elif (i == 'G'): 
       print(i , '__.')
    elif (i == 'H'):
       print(i , '....')
    elif (i == 'I'):
       print(i , '..')
    elif (i == 'J'):
       print(i , '.___')
    elif (i == 'K'):
       print(i , '_._')
    elif (i == 'L'):
       print(i , '._..')
    elif (i == 'M'):
       print(i , '__')
    elif (i == 'N'):
       print(i , '_.')
    elif (i == 'O'):
       print(i , '___')
    elif (i == 'P'):
       print(i , '.__.')
    elif (i == 'Q'):
       print(i , '__._')
    elif (i == 'R'):
       print(i , '._.')
    elif (i == 'S'):
       print(i , '...')
    elif (i == 'T'):
       print(i , '_')
    elif (i == 'U'):
       print(i ,'.._')
    elif (i == 'V'):
       print(i ,'..._')
    elif (i == 'W'):
       print(i ,'.__')
    elif (i == 'X'):
       print(i ,'_.._')
    elif (i == 'Y'):
       print(i ,'_.__')
    elif (i == 'Z'):
       print(i ,'__..')
    elif (i == ' '):
       print('_______________')
    else:
        print('______')

        print('____________________________')

print('_____________________')
print('Finished......#######')
```


## Demo 
Input Thank You

output

```python
T _
H ....
A ._
N _.
K _._
_______________

Y _.__
O ___
U .._
```

## Contributing

Contributions are always welcome!

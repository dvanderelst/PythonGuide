
# Table of Contents
 <p><div class="lev1 toc-item"><a href="#Guide-for-the-confused" data-toc-modified-id="Guide-for-the-confused-1"><span class="toc-item-num">1&nbsp;&nbsp;</span>Guide for the confused</a></div><div class="lev2 toc-item"><a href="#Assigning-stuff-to-variables" data-toc-modified-id="Assigning-stuff-to-variables-11"><span class="toc-item-num">1.1&nbsp;&nbsp;</span>Assigning stuff to variables</a></div><div class="lev2 toc-item"><a href="#Checking-whether-things-are-true-or-false" data-toc-modified-id="Checking-whether-things-are-true-or-false-12"><span class="toc-item-num">1.2&nbsp;&nbsp;</span>Checking whether things are true or false</a></div><div class="lev2 toc-item"><a href="#Converting-between-types---some-possible-conversions" data-toc-modified-id="Converting-between-types---some-possible-conversions-13"><span class="toc-item-num">1.3&nbsp;&nbsp;</span>Converting between types - some possible conversions</a></div><div class="lev2 toc-item"><a href="#Working-with-strings" data-toc-modified-id="Working-with-strings-14"><span class="toc-item-num">1.4&nbsp;&nbsp;</span>Working with strings</a></div><div class="lev3 toc-item"><a href="#Getting-parts-of-a-string" data-toc-modified-id="Getting-parts-of-a-string-141"><span class="toc-item-num">1.4.1&nbsp;&nbsp;</span>Getting parts of a string</a></div><div class="lev3 toc-item"><a href="#length-of-a-string" data-toc-modified-id="length-of-a-string-142"><span class="toc-item-num">1.4.2&nbsp;&nbsp;</span>length of a string</a></div><div class="lev3 toc-item"><a href="#Operations-on-strings" data-toc-modified-id="Operations-on-strings-143"><span class="toc-item-num">1.4.3&nbsp;&nbsp;</span>Operations on strings</a></div><div class="lev3 toc-item"><a href="#Finding-in-strings" data-toc-modified-id="Finding-in-strings-144"><span class="toc-item-num">1.4.4&nbsp;&nbsp;</span>Finding in strings</a></div><div class="lev3 toc-item"><a href="#Concatenation-of-strings" data-toc-modified-id="Concatenation-of-strings-145"><span class="toc-item-num">1.4.5&nbsp;&nbsp;</span>Concatenation of strings</a></div><div class="lev2 toc-item"><a href="#Working-with-lists" data-toc-modified-id="Working-with-lists-15"><span class="toc-item-num">1.5&nbsp;&nbsp;</span>Working with lists</a></div><div class="lev3 toc-item"><a href="#Length-of-a-list" data-toc-modified-id="Length-of-a-list-151"><span class="toc-item-num">1.5.1&nbsp;&nbsp;</span>Length of a list</a></div><div class="lev3 toc-item"><a href="#Appending-to-a-list" data-toc-modified-id="Appending-to-a-list-152"><span class="toc-item-num">1.5.2&nbsp;&nbsp;</span>Appending to a list</a></div><div class="lev3 toc-item"><a href="#Getting-parts-of-a-list" data-toc-modified-id="Getting-parts-of-a-list-153"><span class="toc-item-num">1.5.3&nbsp;&nbsp;</span>Getting parts of a list</a></div><div class="lev3 toc-item"><a href="#Finding-in-a-list" data-toc-modified-id="Finding-in-a-list-154"><span class="toc-item-num">1.5.4&nbsp;&nbsp;</span>Finding in a list</a></div><div class="lev3 toc-item"><a href="#Removing-from-a-list,-by-index" data-toc-modified-id="Removing-from-a-list,-by-index-155"><span class="toc-item-num">1.5.5&nbsp;&nbsp;</span>Removing from a list, by index</a></div><div class="lev3 toc-item"><a href="#Removing-from-a-list,-by-item" data-toc-modified-id="Removing-from-a-list,-by-item-156"><span class="toc-item-num">1.5.6&nbsp;&nbsp;</span>Removing from a list, by item</a></div><div class="lev2 toc-item"><a href="#Math-Module" data-toc-modified-id="Math-Module-16"><span class="toc-item-num">1.6&nbsp;&nbsp;</span>Math Module</a></div><div class="lev3 toc-item"><a href="#Some-relevant-functions" data-toc-modified-id="Some-relevant-functions-161"><span class="toc-item-num">1.6.1&nbsp;&nbsp;</span>Some relevant functions</a></div><div class="lev3 toc-item"><a href="#Angles-should-be-expressed-as-radians!" data-toc-modified-id="Angles-should-be-expressed-as-radians!-162"><span class="toc-item-num">1.6.2&nbsp;&nbsp;</span>Angles should be expressed as radians!</a></div><div class="lev2 toc-item"><a href="#Random-module" data-toc-modified-id="Random-module-17"><span class="toc-item-num">1.7&nbsp;&nbsp;</span>Random module</a></div><div class="lev3 toc-item"><a href="#Random-operations-on-lists" data-toc-modified-id="Random-operations-on-lists-171"><span class="toc-item-num">1.7.1&nbsp;&nbsp;</span>Random operations on lists</a></div><div class="lev2 toc-item"><a href="#Random-numbers" data-toc-modified-id="Random-numbers-18"><span class="toc-item-num">1.8&nbsp;&nbsp;</span>Random numbers</a></div>

# Guide for the confused

## Assigning stuff to variables


```python
my_var = 10
another_var = 'indiana jones'
print(my_var, another_var)
```

    10 indiana jones


## Checking whether things are true or false


```python

print(my_var > 0)
print(my_var != 0) # not equal to
print(my_var == 100) # equal to
print(my_var == 10 and another_var == 'indiana jones')
print(my_var == 10 or another_var == 'batman')
```

    True
    True
    False
    True
    True


## Converting between types - some possible conversions


```python
a_float = 15.5
an_int = 10000
a_boolean = False

print(str(a_float))
print(int(a_float))

print(str(a_boolean))
print(str(an_int))
print(str(a_float))

print(float(an_int))
print(float(a_boolean))
print(int(a_boolean))
```

    15.5
    15
    False
    10000
    15.5
    10000.0
    0.0
    0


## Working with strings


```python
my_text = 'psychology!'
print(my_text)
```

    psychology!


### Getting parts of a string


```python
print(my_text[0]) 
print(my_text[0:5]) 
print(my_text[5:])
```

    p
    psych
    ology!


### length of a string


```python
print(len(my_text))
```

    11


### Operations on strings


```python
print(my_text.capitalize())
print(my_text.upper())
print(my_text.lower())
print(my_text.lstrip('ps')) 
print(my_text.rstrip('!'))
print(my_text.count('o')) 
print(my_text.replace('o','x')) 
```

    Psychology!
    PSYCHOLOGY!
    psychology!
    ychology!
    psychology
    2
    psychxlxgy!


### Finding in strings


```python
print('ology' in my_text)
print(my_text.index('o'))
```

    True
    5


### Concatenation of strings


```python
print('batman' + ' & ' + 'robin')
```

    batman & robin


## Working with lists


```python
reindeer = ['Dasher', 'Dancer','Prancer','Vixen', 'Comet']
more_reindeer = ['Cupid','Donner','Blitzen']
```

### Length of a list


```python
print(len(reindeer))
```

    5


### Appending to a list


```python
all_reindeer = reindeer + more_reindeer
print(all_reindeer)
```

    ['Dasher', 'Dancer', 'Prancer', 'Vixen', 'Comet', 'Cupid', 'Donner', 'Blitzen']



```python
all_reindeer.append('Rudolf')
print(all_reindeer)
```

    ['Dasher', 'Dancer', 'Prancer', 'Vixen', 'Comet', 'Cupid', 'Donner', 'Blitzen', 'Rudolf']


### Getting parts of a list


```python
print(all_reindeer[5])
print(all_reindeer[0:4])
print(all_reindeer[4:])
```

    Cupid
    ['Dasher', 'Dancer', 'Prancer', 'Vixen']
    ['Comet', 'Cupid', 'Donner', 'Blitzen', 'Rudolf']


### Finding in a list


```python
print(all_reindeer.index('Prancer'))
print('Rudolf' in  all_reindeer)
print('Santa' in all_reindeer)
```

    2
    True
    False


### Removing from a list, by index


```python
print(all_reindeer)
all_reindeer.pop(7)
print(all_reindeer)
```

    ['Dasher', 'Dancer', 'Prancer', 'Vixen', 'Comet', 'Cupid', 'Donner', 'Blitzen', 'Rudolf']
    ['Dasher', 'Dancer', 'Prancer', 'Vixen', 'Comet', 'Cupid', 'Donner', 'Rudolf']


### Removing from a list, by item


```python
print(all_reindeer)
all_reindeer.remove('Prancer')
print(all_reindeer)
```

    ['Dasher', 'Dancer', 'Prancer', 'Vixen', 'Comet', 'Cupid', 'Donner', 'Rudolf']
    ['Dasher', 'Dancer', 'Vixen', 'Comet', 'Cupid', 'Donner', 'Rudolf']


## Math Module
### Some relevant functions


```python
import math
print(math.pi)
print(math.gcd(18,12))
print(math.ceil(10.2))
```

    3.141592653589793
    6
    11


### Angles should be expressed as radians!


```python
print(math.cos(1))
print(math.cos(90))
```

    0.5403023058681398
    -0.4480736161291701


## Random module


```python
import random

```

 ### Random operations on lists


```python
print(random.choice(all_reindeer))
print(all_reindeer)
random.shuffle(all_reindeer)
print(all_reindeer)
```

    Cupid
    ['Dasher', 'Dancer', 'Vixen', 'Comet', 'Cupid', 'Donner', 'Rudolf']
    ['Vixen', 'Cupid', 'Comet', 'Rudolf', 'Donner', 'Dancer', 'Dasher']



```python
print(random.sample(all_reindeer, 3))
```

    ['Dancer', 'Donner', 'Comet']


## Random numbers


```python
print(random.randint(0,10))
print(random.randrange(0,10))
print(random.gauss(10,3))
```

    5
    6
    12.385701953398804


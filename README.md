### PROGRAMMING-ASSIGNMENT 1

#### ALPHABET SOUP PROBLEM - we are tasked to create a string and arrange the letters in the string alphabetically

1. First, I defined the funtion Alphabetsoup and used sorted to automatically sort the text entered
```python
def alphabet_soup(text): #define the function alphabet_soup
    return ''.join(sorted(text)) #sort the next given elements
```

2. I then used an example to see if the code works
```python
print(alphabet_soup("elementary")) #use an example phrase and print
```

3. I used another example to conclude if the code is working properly
```python
print(alphabet_soup("supercalifragilisticexpialidocious")) #give another example phrase and print
```

#### EMOTICON PROBLEM - we are tasked here to create a function that replaces specific words such as smile, grin, mad, and sad into emoticons such as :), :D, :((, and >:( respectively

1. First, I defined the function Emotify and then started to create the funtion that would replace the specific words into their respective emoticons
```python
def emotify(sentence): #define the function emotify 
    sentence = sentence.replace("smile", ":)")
    sentence = sentence.replace("grin", ":D")
    sentence = sentence.replace("sad", ":((")
    sentence = sentence.replace("mad", ">:(") #replace the corresponding words into its respective emoticons
    return sentence
```

2. I then used the programming to an example with the word "smile to be replaced with
```python
print(emotify("Can you give me a smile")) #provide an example using one of the replaced words
```

3. I used another example to check if it still working right
```python
print(emotify("I truly feel sad")) #give another example using one of the replaced words
```

#### UNPACKING LIST PROBLEM - we are tasked here to unpack a list into three variables, first, middle, and last with first having the first element, last having the last element, and middle having the elements between the first and the last element

1. First, i created a lsot of elements
```python
Apples = [1, 2, 3, 4, 5, 6,7,8] #create a list of values
```

2. I then defined that the test "first" is equal to the first element of the list
```python
first = Apples[0] #define "first" as the first digit of the list
```

3. I went ahead and did the same process for "last" having the last element of the list
```python
last = Apples[-1] #define "last" as the last digit of the list
```

4. I then made a loop for the "middle" so that the first and last element of the list would not be included
```python
middle = [] #create a loop excluding the first and last values
for i in range(1, len(Apples)-1):
    middle.append(Apples[i])
```

5. I then went on to try and see if printing first would give me the first element of the list
```python
print("first:", first) #print the first value
```

6. I went and printed middle to see if the loop worked correctly and give me the middle values of the list
```python
print("middle:", middle) #print the middle values
```

8. I did the same procedure to last and printed it
```python
print("last:", last) #print the last value
```


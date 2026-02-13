# Named Functions Application

## Comprehension Check

<table>
 <tr><td>
<img src="https://github.com/kwaldenphd/internet/blob/main/images/clipboard.png?raw=true" alt="Clipboard icon" width="50"/></td>
  <td><a href="https://docs.google.com/forms/d/e/1FAIpQLSdCocH8cRcDgnc4WTiEQESxPKzKv8IpvhCc4D5CFAYb5Sim3Q/viewform?usp=sf_link">Named Functions in Python Comprehension Check</a></td>
  </tr>
  </table>
  
## Application Questions

### Question #1

Let's say we want to create a function that prints an input string a specific number of times.

Breaking down the steps of that program:
- Get the input string (`message`)
- Get the number of times (`x`)
- Print the string `x` number of times

We might also need some way of tracking how many times we've printed the string so it stops at the specified number.

Q1A: Describe how you would start building out a program to accomplish this task? What functions, statements, or keywords would you need to use? How would you start to organize this program?

Q1B: See where you can get with writing this program. What parts of the program were you able to get working? Where did you run into challenges? Answer to this question includes program + comments that document process and explain your code.

````{dropdown}

Here is one approach to this task:

We can use two input statements to get `message` and `x`. And one way we could approach printing the string `x` number of times would be to use a `count` variable and a `while` statement.

```Python
# input statement for string
message = input("Enter your message here: ")

# input statement for number of times
x = int(input("How many times do you want this statement to print? Enter a number value."))

# assign count
count = 0

# while statement
while count < x:
    print(message) # print message
    count += 1 # reassign count
```

Now to create a function using this program.

```Python
# function definition
def printNTimes():
    message = input("Enter your message here: ") # input statement for string
    x = int(input("How many times do you want this statement to print? Enter a number value.")) # input statement for number of times
    count = 0 # assign count
    while count < x: # while statement
        print(message) # print message
        count += 1 # reassign count

# function call
printNTimes()
```
````

Q1C: How does the sample program compare to your approach? What was similar? What was different? How are you thinking differently (if at all) about how to approach this type of program?

### Question #2

But let's say we don't want to use an `input()` statement as part of the function- what if we wanted to pass specific values to the function?

Q2A: Modify the program you built for the previous section to take specific values as inputs (rather than get inputs as part of the function). Answer to this question includes program + comments that document process and explain your code.

Q2B: Then, create a named function and function call for this program. Answer to this question includes program + comments that document process and explain your code.

Q2C: What parts of the program were you able to get working? Where did you run into challenges?

### Question #3

Q3: Write a function is_even that determines whether or not a number n is even. Include the function definition as well as a sample function call. Answer to this question includes program + comments that document process and explain your code.

### Question #4

Q4: Write a function average that determines the average value of a list. Include the function definition as well as a sample function call. Answer to this question includes program + comments that document process and explain your code.

### Question #5

Q5: Write a function uniq that takes a list and returns a new list containing only unique values. Include the function definition as well as a sample function call. Answer to this question includes program + comments that document process and explain your code.

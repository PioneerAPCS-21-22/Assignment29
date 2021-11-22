# Assignment 29

The holidays are all about enjoying a nice meal with family and friends and that is the inspiration for this assignment.

You will ask the user for input for a food and your program will be a noisy eater by outputting 'noms' and 'burps.'

For each character in the string, print "nom". A "burp" should be printed after every 5 noms. The burp should be the last thing printed and then a new line should be used.

After eating, prompt the user to give another food or say "I'm full" in order to quit the program.

You only need to use one class, but you need to create method(s) that get called in your main method. Your methods also need comments that explain parameters and what is returned (or done).

### Escape Sequences

We can return to a new line quickly with the escape sequence "\n"

Example: The following code,
 
`System.out.print("Hello \nWorld!");`

has the output below,

```
Hello
World!
```

You may have also noticed in the past it is hard to print quotes in a print statement. We can use the escape character ("\") to do this.

Example: The following code,

`System.out.println("Hello, enter a \"tag,\" thanks.");`

has the output below,

`Hello, enter a "tag," thanks.`

### Sample Output

**Notice that "Bran muffins" is 12 characters long, including spaces, so 12 noms are printed (burps are not counted).**

**An escape character should be used to print quotes and you must use a newline escape sequence at least once.**

```
What food would you like to eat? (Type "I'm full" to quit): Bran muffins
Nom Nom Nom Nom Nom burp
Nom Nom Nom Nom Nom burp    
Nom Nom
What food would you like to eat? (Type "I'm full" to quit): Pizza
Nom Nom Nom burp
Nom Nom
What food would you like to eat? (Type "I'm full" to quit): I'm full
```

### Grading

As always, your program will be graded on its functionality according to the project specifications and proper code style.


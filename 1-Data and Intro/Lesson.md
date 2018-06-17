# What is Programming?
Programming is the all about moving data around. Sometimes you're calculating sales tax. Sometimes you're moving a window the other side of a screen. Either way, you need to know how the computer sees data, and how you can tell it what to do.

## Binary
Since computers are based on electricity, they see data as either high voltage or low voltage. Computer RAM is generally a bunch of capacitors that either have a charge or not. For this example, each piece of information uses 4 capacitors, or contains 4 bits.

Since all data looks the same, just tons of 0(low voltage) and 1(high voltage), computers need to know what type of data they're looking at.

## Numbers
Like decimal, binary counts up from 0 but only has one other digit. In our example 4 bit computer, a number can be any of the following:
|Binary|Decimal|
|---|---|
|0000|0|
|0001|1|
|0010|2|
|0011|3|
|0100|4|
|0101|5|
|0110|6|
|0111|7|
|1000|8|
|1001|9|
|1010|10|
|1011|11|
|1100|12|
|1101|13|
|1110|14|
|1111|15|

Numbers have a few variations that aren't relevant in the Python language, but the important ones to know for now are:
- Integer: Whole numbers like 100. Sometimes called ints.
- Double: Numbers with decimal values like 32.835. They're called doubles because they are most easily made using twice the space as an integer.

## Characters
Everything you'd see in text is a character. The alphabet, numbers, punctuation, even emoji. Lists of characters are called strings and are most often shown with quotes around then `"like this"`.

In our example 4 bit computer, the first characters are the number digits, followed by the part of the alphabet we support:
|Binary|Character|
|---|---|
|0000|0|
|0001|1|
|0010|2|
|0011|3|
|0100|4|
|0101|5|
|0110|6|
|0111|7|
|1000|8|
|1001|9|
|1010|a|
|1011|b|
|1100|c|
|1101|d|
|1110|e|
|1111|f|

So, if we had the string `"15"`, instead of `1111`, the computer would see it as `00010101`. Just two characters jammed together.

## More complicated data
Characters and Numbers are considered "primitive types", the base data that all others build upon.

In order to represent more complex data types like shapes, or people, we need to use multiple pieces of information to describe them.

For examples, a Rectangle. The two things we need to know about a rectangle are its length and width. We can do this with two integers. A 1 by 1 rectangle would be `00010001`. A 1 by 5 rectangle would be `00010101`, just like the string `"15"`

We'll go over compound types like Rectangles later when we learn about Classes.
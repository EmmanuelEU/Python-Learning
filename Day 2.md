A string is a sequence of characters surrounded by either single or quotation marks. Python treats both forms as strings, so you can use either one.Example:

my_str_1 = “Hello”

Multi line String you can use triple double quotes or single quotes:

Example:

My_str_3 = “””Multiline string”””

len() - To get the length of a string

**Concatenation Strings**

You can combine multiple strings together with the plus (+) operator. Process called string concatenation.

Example:

My_str_1 = ‘Hello’

My_str_2 = “World”

Str_plus_str = my_str_1 + ‘ ‘ + my_str_2

Print(str_plus_str)

**Repeating Strings** 

You can also repeat a string by multiplying it with an integer using the * operator. Repeated the specified number.

Example:

Sound = ‘ha’

Repeated_sound = sound * 3 

Print(repeated_sound) hahaha

**F-strings:**

F’{}’- f(either lowercase or uppercase) before the quotes, and allow you to embed variables or expressions inside replacement fields indicated by curly braces ({}).

**What is string slicing and how does it work?**

String slicing lets you extract a portion of a string or work with only a specific part of it.

Example: 

String[start:stop] - if you want to extract character from certain index to another you just separate the start and stop indices with colon:

What are some common string methods?

A method is a function that you call on a value. To call a string methods,write the string or its variable name followed by a dot and thee method call.

Upper(): returns a new string with all characters converted to uppercase.

Lower():returns a new string with all characters converted to lowercase 

Strip(): Returns a new string with the specified ending and trailing characters removed.

Replace(old, new): Returns a new string with all occurrences of old replaced by new.

Split(separator):Splits a string on specified separator into a list of string.Splits on white space.

Join():Joins the strings in a collection into a single string with a separator.

Startswith(prefix): Returns a Boolean indicating if a string starts with the specified prefix.

Endswith(suffix): Returns a Boolean indicating if a string ends with the specified suffix.

Find(substring):Returns the index of the first occurrence of substring or -1 if it doesn’t find one.

Count(substring):Returns the number of times a string appears in a string.

Caplitalize():Returns a new string with the first character capitalised and the other characters lowercased.

Isupper(): Returns True if all letters in the string are uppercase and False if not.

Islower(): Returns True if all letters in the string are lowercase and False if not.

Title(): Returns a new string with the first letter of each word capitalized.

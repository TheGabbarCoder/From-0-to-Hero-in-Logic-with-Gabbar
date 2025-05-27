# Concepts Covered in Day 1

## 1. **String Manipulation**
   - A string is represented by the class System.String. The “string” keyword is an alias for System.String class.
   - Strings in C# are **immutable**. Once created, they cannot be changed.
   - **String Class Properties: The String class has two properties as follows:-**
     - **Chars:** It is used to get the Char object at a specified position in the current String object.
     - **Length:** It is used to get the number of characters in the current String object. To know more about the string class properties please go to String Properties in C#.
   - Operations like reversing a string require creating a new string or using a `char[]` array.
   - Looping through strings or using `ToCharArray()` helps us access individual characters.
   - For More detailed for STRING IN C# go to:- "https://www.geeksforgeeks.org/c-sharp-string/"

## 2. **Loops**
   - **For Loop:** Used to iterate over arrays or strings.
   - We use the loop to access each character of the string starting from the end.

## 3. **Arrays (char[])**
   - A **char[]** (character array) allows us to manipulate individual characters in the string.

## 4. **String Concatenation**
   - String concatenation is done by **appending** characters to an initially empty string.
   - It's more efficient when using `StringBuilder` for large-scale concatenation, but for this task, simple concatenation is fine.

## 5. **Dictionary (for frequency count)**
   - A **Dictionary** is a key-value pair collection where keys are unique, and values are the count of occurrences.
   - In this case, we used the key-value pair where the key is the character, and the value is its frequency in the string.

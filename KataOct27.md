#Kata Oct. 27, 2016

## Braille

Last week we converted Morse Code to ASCII characters and back again. This week, let's look at transcribing to Braille!
The rules for Braille are:

 1. Each letter is represented by a grid two characters wide and three characters tall.
 2. Each character in the input file can be a * or a space
 3. Each word will start with the braille character that has one dot in the lower right.
 4. Each braille character will have a 1 horizontal space between them.
 5. Each braille word will have a 4 horizontal spaces between.
 6. Each braille "phrase" will be on three lines. Each new phrase after the first will be separated by a blank line.

 
Example input file:
``` 
   *  *  *  *  *         * *  *  *  ** 
   **  * *  *   *       **  * ** *   * 
 *       *  *  *      *  * *  *  *     
```


### The input file will output 

`Hello World`

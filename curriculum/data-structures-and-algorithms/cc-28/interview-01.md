# Interview 01

Determine the most common word in a book.

## Specifications

- Read all of the following instructions carefully. 
- Act as an interviewer, giving a candidate a code challenge
- Score the candidate according to the [Whiteboard Rubric](https://docs.google.com/spreadsheets/d/1scthkmARfzAFZrSYAp6LA2coOaoWUWbSzMbtIU4jcHw){:target="_blank"}
- You are free to offer suggestions or guidance (and see how they respond),  but don't solve it for the candidate

## Feature Tasks

- Ask the candidate to write a function that determines the most common word in a book.  
- The most efficient solution to this problem is to use a Hastable.
- Spaces don't count, and words are not case sensitive (i.e. Cat, CAT, and cat are all the same)
- Don't concern yourself wth punctuation. 
- The function created should take in a string as an argument. 
- The best approach to this is to iterate through the string and to keep a "tally" of how many times a word
appears. 
- the word should be the "key", and a counter as the "value"
- The word with the highest counter at the end is the returned word. 
- It is possible for the candidate to havea "tempWord" and "tempCounter" that will hold the highest word and count so far. 
This will prevent them from having to iterate thorugh the hashtable once the string is completed. 
- Time and Space is O(n).


### Edge Cases
- It is possible to have words show up the same amount of times as others, In this case, return the first occurance 
(i.e. both "dog" and "cat" show up twice -> return "dog");

## Structure 

Familiarize yourself with the grading rubric, so you know how to score the interview. 

Look for effective problem solving, efficient use of time, and effective communication with the whiteboard space available. 

Every solution might look a little different, but the candidate should be able to test their solution with different inputs to verify correctness.

Assign points for each item on the Rubric, according to how well the candidate executed on that skill. 

Add up all the points at the end, and record the total at the bottom of the page.

## Example

| Input | Output |
|-----|----| 
| `In a galaxy far far away` | `far` |
| `Taco cat ate a taco ` | `taco` |
| `No. Try not. Do or do not. There is no try.` | `No` |

## Documentation

Record detailed notes on the rubric, to share with the candidate when the interview is complete. 

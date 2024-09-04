# Assignment #2 - Feb 12th to Feb 16th


## Overall Instructions
1. Watch the following video:
    1. Lecture 2: Branching and Iteration. [[Link]](https://ocw.mit.edu/courses/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/resources/lecture-2-branching-and-iteration/))
    2. Lecture 3: String Manipulation, Guess and Check, Approximations, Bisection. [[Link]](https://ocw.mit.edu/courses/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/resources/lecture-3-string-manipulation-guess-and-check-approximations-bisection/))


## Python assignment

### Rules:
-	Creating new functions is not allowed. 
-	Do not use classes or other external packages (i.e., regex).

### Submission format:
- Submit your python script to your repository.

### 1. Concepts: Conditional, input, and print.  
- A researcher shares with you that she has obtained the following two sentences from a conversation:

```
Patient: Yeah so um I vomited at the start of the symptoms but now um I've stopped vomiting.
Doctor: You stopped vomiting okay And was your vomit I know it's not a nice thing to talk about but was it just normal food colour Yeah And there was no blood in your vomit is that right?
```

- She is asking you to develop a python programme with the following requirements. The first request is that she wants to be able to input each turn. She wants the script to first ask "Is it a doctor or a patient?". If it is a doctor, then she wants the script to continue asking "What did the doctor say? (copy/paste)" and once the text was copy-pasted, she wants the script to output "The doctor said: __" where ___ is imported text. She wants the script to work for both the patient and the doctor. 

- Assume that the only way of writing "doctor" and "patient" is with lowercase letters and without space.

- **Questions to respond within the python script as comment “#”**: Explain the difference between “elif” and “else” if there is any.

### 2. Concepts: Conditional, while, inequality, input, print  
- The researcher is happy with your work. However, she tried to input "Doctor" (first letter in capital), but your python programme did not work (as expected). She wants you to create a while loop that when your input is not "doctor", the script should continuously request "the input has to be in lowercase and without spaces, please try again". 
Once your input is "doctor", then it will ask "What did the doctor say? (copy/paste)" and print the given turn.

- Hint: try using inequality in the while loop and slide 17 from lecture 2 might be helpful.

### 3. Concepts: Counting and conditionals:  
- You met a linguistic researcher who has recently read an article stating that the most common consonants in English literature (written information) are "r", "s", and "t". She wants to study if the same phenomenon occurs in patient-doctor conversations. She asks you to write a ptyhon script that allows to input a turn from a patient-doctor conversation. Once each turn is given, the script will automatically count the number of times the characters "r", "s", and "t" are found.

- You use use each of the following turns
```
Turn #1: Yeah so um I vomited at the start of the symptoms but now um I've stopped vomiting.
Turn #2: You stopped vomiting okay And was your vomit I know it's not a nice thing to talk about but was it just normal food colour Yeah And there was no blood in your vomit is that right?
```

- The output should be "The number of 'r' consonants are __ , the number of 's' consonants are __ , and the number of 't' consonants are __ "

### 4. OPTIONAL:  
- Now, the researcher wants a program or python script that count full words instead of consonants. She is interested in understanding how contrasting ideas occur in patient-doctor interactions. To achieve this, you suggest counting the number of times the word "but" occurs within a single turn. The script must allow for multiple inputs and the count must accumulate after every given turn. 

- The researcher likes your idea and wants the python script to also give the total number of "but" occurrences per conversational agent (doctor or patient). For instance, "The Patient has said a contrasting idea ### times, and the Doctor has said a contrasting idea ### times". She requests that you use the **while loop** and wants the script to **break** the loop (or stop) when she types "stop".


- **Rules**: only use the while loop, break, if/elif/else (any or all of them), and the built-in function called "split()"
- **Hint**: google how "split()" works and see examples of "while True".

- Use the following turns for this exercise:
```
Input #1: Patient: Um yeah it doesn't feel like -- yeah, it just makes me feel weak. I haven't had a fever, um, at the moment, but I did notice um a temperature when the symptoms started, so, um, yeah around about three or four days ago.
Input #2: Doctor: You measure your temperature then?
Input #3: Patient: Yeah, I uh I didn't mention my temperature, no, but I felt, um, just a bit hot. And, y'know.
Input #4: Patient: Yeah, so um, I vomited at the start of the symptoms but now um I've stopped vomiting.
Input #5: Doctor: You stopped vomiting, okay. And was your vomit, I know it's not a nice thing to talk about, but was it just normal food colour Yeah. And there was no blood in your vomit, is that right?
```

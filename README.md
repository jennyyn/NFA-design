# Summary of My Learning

## 1. Which problem(s) gave you the most trouble? Did you avoid any problem that is too challenging to finish by deadline? Did you ask questions to AI/instructor?

The problem that gave me the most trouble was problem 8 ({string s|s starts with 01 and ends with 10}). This problem was still doable but the test string "010" made me have to adjust my original diagram a bit. I realized that the string 010 uses the 1 as both the second character of the starting 01 and the first character of the ending 10. 
I adjusted my NFA to include an additional branch so that, after reading 01, the machine could immediately begin checking for the ending 10 while still keeping the original path.
This allowed the NFA to correctly accept 010.

No I did not avoid any problems specficially but I did try to choose problems that I thought was doable before the deadline. 

 I asked questions to AI and my classmates to make sure that my diagrams were correct and whether I tested all the necessary test strings to make sure my diagrams were good.



## 2. Which problem(s) surprised you with a "gold-st-ring"? Which next state(s) did you not account for in the subset of next states? why? How to make sure you avoid such errors in your future flight/traffic/compiler state controller tasks, or in the near future, the course projects/exams?

The problem that surprised me with a “gold-st-ring” was Problem 8. The string 010 should get accepted but I forgot to account for this string when creating my diagram so it rejected when I thought it would accept. In the near future, I will check for nondeterministic branches instead of following only one path and test short strings, long strings, boundary cases, and strings that can overlap


## 3. Other Insights, Comments, or Questions

One important thing I learned was to check states that may have to branch off early. Overall, this assignment helped me understand to be very careful and detailed when it comes to using test strings for my diagrams.


# Notes on the Midterm

* _Correctness    (out of 40):_ 32
* _Good Practices (out of 10):_ 9
* _Docs / Testing (out of 10):_ 10

_Details on the grading criteria for the midterm can be found on [Canvas](https://canvas.slu.edu/courses/28045/rubrics/23671)._




## Step 1
* Nice work. Easy to understand what you're doing.

## Step 2
* You want to be careful assuming that 0 might not be a valid rate.  You set a default value of 0, and then later assume that your code won't find an entry that might have an allowed_amount of 0. It's true that this data doesn't have any allowed_amount values of 0, but it isn't a safe assumption.  I've deducted 1 point for this under _Correctness_.

## Step 3
* Your code should have used the `get_rate()` function from above directly instead of copying all the code here again. I've deducted 1 point from _Good Practices_

## Step 4
* It doesn't look like your code here get the requirements complete. It looks like you're totallying up everything in the entire file, but not breaking down the totals for each grouping as required.  You got some of the requirements done, so I've given you some credit, but deducted 7 points for this.
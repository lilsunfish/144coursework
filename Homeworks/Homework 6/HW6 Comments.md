# Comments on HW6

Author: Oliver  
Date: 2013-12-05

#### Overall

This is a good start. Problems 1-3 aren't entirely successful, but they're headed in the right direction. The annotations solutions are good.

_Note: Since the assignment's split up this week, I've broken this week's comments down by problem instead of criteria._

#### Problem 1

The search provided here doesn't do control verbs, just verbs in general. Control predicates have an embedded clause (S) with a null subject (-NONE-), which you can leverage to find just those.

#### Problem 2

This is on the right track. The This is on the right track. What you need next is a dictionary that says what the active and passive forms are for all the top verbs here (maybe the top 100). That's tedious, I know, but there isn't an easier way to pair things up. Then, you can do some more tregex searches using those verbs to fill in your table.

#### Problem 3

The frame provided is excellent. Obviously what's missing is the code to successfully determine whether `elt` is adjacent to `self`. Take a look at the notes from the final section to see one way to tackle this.

#### Problem 4

The tags are excellent in terms of their content. In form, they don't match the example file. Because you were consistent, I was able to automate the process of putting them in the right format though.

#### Problem 5

Some questions on your codebook:

- Is something like "too long" a length?
- How could you differentiate between the actual rating and ratings reviewers think the film should have had?
- Would something like "Tarantino's other films" warrant the <O /> tag?
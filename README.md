# Natural Selection of "Words"

#### Notebook containing a small project involving Markov chains, described below.

The genesis for this small project came from a passage in the (otherwise excellent) [*A Zoologist's Guide to the Galaxy*](https://www.penguinrandomhouse.com/books/646643/the-zoologists-guide-to-the-galaxy-by-arik-kershenbaum/) by Arik Kershenbaum; specifically, this passage about natural selection:

> At its simplest level, natural selection is easy to understand. Beneficial traits *accumulate*. Some new features will survive, other innovations will not, but good ideas developed by previous generations are not forgotten. Richard Dawkins explained this process with beautiful simplicity in his book *The Blind Watchmaker*. Imagine randomly choosing a string of twenty letters, say SDFLKJFGOSDIFHGSOFGH. The chances of arriving at a particular sequence, say, 'The Blind Watchmaker', are astronomically small: actually, one in 42 billion billion billion. No one believes that order can arise out of chaos randomly. But if each time you make some random changes to the sequence above, you keep changes that the match the sequence we're looking for, 'The Blind Watchmaker;, the result is completely different. Good innovations -- say, changing the initial 'S' (which isn't in the target sequence) to a 'T' (which is the first letter of 'The') -- don't disappear, so bit by bit the best sequence, i.e. the 'right' sequence, will emerge. Remakably, using this 'selection' approach, the correct sequence emerges after about just 540 attempts -- an improvement by a factor of about 80 million billion billion!

The explanation for that *540 attempts* result, which didn't quite sit right with me, was the following:

> The average time to 'correct' a letter is twenty-seven attempts (as the correct letter is one among twenty-seven), so the total expected number of attempts is 27 x 20 = 540. 

Now, I disagree with this for probably pedantic reasons: this assumes that only one letter changes upon each iteration, but that's not how natural selection works; sometimes it will be more! Sometimes it could be less! So what happens if we allow more than one letter to change on each iteration?

...

To reproduce the project and run the notebook, install the requirements in you preferred environment using: 

    pip install -r requirements.txt



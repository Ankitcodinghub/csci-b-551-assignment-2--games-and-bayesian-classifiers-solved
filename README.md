# csci-b-551-assignment-2--games-and-bayesian-classifiers-solved
**TO GET THIS SOLUTION VISIT:** [CSCI-B-551 Assignment 2- Games and Bayesian Classifiers Solved](https://www.ankitcodinghub.com/product/csci-b-551-assignment-2-games-and-bayesian-classifiers-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91836&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI-B-551 Assignment 2- Games and Bayesian Classifiers Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Part 0: Getting started

For this project, we are assigning you to a team. We will let you change these teams in future assignments. You can find your assigned teammate(s) by logging into IU Github, at http://github.iu.edu/. In the upper left hand corner of the screen, you should see a pull-down menu. Select cs-b551-fa2021. Then in the box below, you should see a repository called userid1-a2, userid1-userid2-a2, or userid1-userid2-userid3-a2, where the other user ID(s) correspond to your teammate(s). Now that you know their userid(s), you can write them an email at userid@iu.edu.

To get started, clone the github repository:

git clone git@github.iu.edu:cs-b551-fa2021/your-repo-name-a2

If that doesn’t work, instead try:

git clone https://github.iu.edu/cs-b551-fa2021/your-repo-name-a2 where your-repo-name is the one you found on the GitHub website above.

Part 1: Raichu

Raichu is a popular childhood game played on an n × n grid (where n ≥ 8 is an even number) with three kinds of pieces (Pichus, Pikachus, and Raichus) of two different colors (black and white). Initially the board starts empty, except for a row of white Pichus on the second row of the board, a row of black Pichus on the third row of the board, and a row of black Pichus on row n−2 and a row of black Pikachus on row n−1:

Two players alternate turns, with White going first.

In any given turn, a player can choose a single piece of their color and move it according to the rules of that piece.

A Pichu can move in one of two ways:

• one square forward diagonally, if that square is empty.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
• “jump” over a single Pichu of the opposite color by moving two squares forward diagonally, if that square is empty. The jumped piece is removed from the board as soon as it is jumped.

For example, for the highlighted Pichu in the following board at left, there are two possible moves, shown in the right two boards:

</div>
</div>
<div class="layoutArea">
<div class="column">
Initial board Possible move #1 Possible move #2 A Pikachu can move in one of two ways:

<ul>
<li>1 or 2 squares either forward, left, or right (but not diagonally) to an empty square, as long as all squares in between are also empty.</li>
<li>“jump” over a single Pichu/Pikachu of the opposite color by moving 2 or 3 squares forward, left or right (not diagonally), as long as all of the squares between the Pikachu’s start position and jumped piece are empty and all the squares between the jumped piece and the ending position are empty. The jumped piece is removed as soon as it is jumped.For example, for the highlighted Pikachu in the following board at left, here are some (not all) possible moves:
Initial board Possible move #1 Possible move #2 Possible move #3

A Raichu is created when a Pichu or Pikachu reaches the opposite side of the board (i.e. when a Black Pichu or Pikachu reaches row 1 or a white Pichu or Pikachu reaches row n). When this happens, the Pichu or Pikachu is removed from the board and subsituted with a Raichu. Raichus can move as follows:

<ul>
<li>any number of squares forward/backward, left, right or diagonally, to an empty square, as long as all squares in between are also empty.</li>
<li>“jump” over a single Pichu/Pikachu/Raichu of the opposite color and landing any number of squares forward/backward, left, right or diagonally, as long as all of the squares between the Raichu’s start position and jumped piece are empty and all the squares between the jumped piece and the ending position are empty. The jumped piece is removed as soon as it is jumped.</li>
</ul>
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
For example, some (not all) possible moves of the highlighted white Raichu are:

Initial board Possible move #1 Possible move #2 Possible move #3

Note the hierarchy: Pichus can only capture Pichus, Pikachus can capture Pichus or Pikachus, while Raichus can capture any piece. The winner is the player who first captures all of the other player’s pieces.

Your task is to write a Python program that plays Raichu well. Your program should accept a command line argument that gives the current state of the board as a string of .’s, w’s, W’s, b’s, B’s, @’s, and $’s, which indicate which squares have no piece, a white Pichu, a white Pikachu, a black Pichu, a black Pikachu, a white Raichu and a black Raichu respectively, in row-major order. For example, if n = 8, then the encoding of the start state of the game would be:

<pre>             ........W.W.W.W..w.w.w.w................b.b.b.b..B.B.B.B........
</pre>
More precisely, your program will be called with four command line parameters: (1) the value of n, (2) the current player (w or b), (3) the state of the board, encoded as above, and (4) a time limit in seconds. Your program should then decide a recommended single move for the given player with the given current board state, and display the new state of the board after making that move. Displaying multiple lines of output is fine as long as the last line has the recommended board state. The time limit is the amount of time that your program should expect to have to make its decision; our testing code will kill your program at that point, and will use whichever was the last move your program recommended. For example, a sample run of your program might look like:

<pre>[djcran@macbook]$ python3 ./raichu.py 8 w '........W.W.W.W..w.w.w.w................b.b.b.b..B.B.B.B........' 10
Searching for best move for w from board state:
........
W.W.W.W.
</pre>
<pre>.w.w.w.w
........
........
b.b.b.b.
.B.B.B.B
........
Here's what I decided:
..........W.W.W..w.w.w.wW...............b.b.b.b..B.B.B.B........
</pre>
Your program should work for any reasonable value of n and reasonable time limit, although we plan to test it only for values of n close to 8 and time limits around 10-30 seconds.

The competitions. To make things more interesting, we will provide a way for your program to play against other groups’ programs. We will release this code at least 1 week before the deadline. While the majority of your grade will be on correctness, programming style, quality of answers given in comments, etc., a portion may be based on how well your code performs against others, with particularly well-performing programs eligible for prizes including extra credit points.

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Hint: Since our grading program only looks at the last solution that you output, your program can output multiple solutions. In other words, you can choose to completely ignore the time parameter passed to your program and simply output multiple answers until you run out of time and we automatically kill your program.

Note: Your code must conform with the interface standards mentioned above! The last line of the output must be the new board in the format given, without any extra characters or empty lines. Also, note that your program cannot assume that the game will be run in sequence from start to end; given a current board position on the command line, your code must find a recommended next best move. Your program can write files to disk to preserve state between runs (although this is not required or necessarily recommended), but should correctly handle the case when a new board state is presented to your program that is unrelated to the last state it saw.

Part 2: The Game of Quintris

The game of Quintris will likely seem familiar. It starts off with a blank board. One by one, random pieces (each consisting of 5 blocks arranged in different shapes) fall from the top of the board to the bottom. As each piece falls, the player can change the shape by rotating it or flipping it horizontally, and can change its position by moving it left or right. It stops whenever it hits the ground or another fallen piece. If the piece completes an entire row, the row disappears and the player receives a point. The goal is for the player to score as many points before the board fills up.

We’ve prepared a simple implementation of Quintris that you can play from the command line! To try it, run:

<pre>    python3 ./quintris.py human animated
</pre>
To play, use the b and m keys to move the falling piece left and right, the n key to rotate, the h key to flip, and the space bar to cause the piece to fall. (This works on the SICE Linux machines and should work on Mac OS command line. It may or may not work on Windows or other platforms because of the way it handles keyboard input. If it doesn’t work for you, you can use a simpler but less-fun interface by running python3 ./quintris.py human simple.)

Your goal is to write a computer player for this game that scores as high as possible. We’ve provided a really simple automatic player that can be run using the command line options computer animated and computer simple. The code for this is in tetris.py, whereas the other python files contain the “back end” code that runs the game. You should not modify the other source code files.

We’d recommend starting with the simple version as opposed to the animated version. In the simple version, your program issues a sequence of commands which are then executed immediately before the piece begins to fall. This is simpler but prevents your program from making complicated moves (like moving left and right as the piece falls to try to wedge a piece into an awkward spot in the board). Then, consider the animated version, which also introduces an implicit time limit (since your decisions have to be made before the piece reaches the bottom of the board.)

This version of Tetris has one twist which you may want to use to get as high a score as possible: the falling pieces are not chosen uniformly at random but based on some distribution which your program is not allowed to know ahead of time. However, it may be able to estimate the distribution as it plays, which may let it make better decisions over time.

The tournament. To make things more interesting, we will hold a competition among all submitted solutions to see whose solution can score the highest across several different games. While the majority of your grade will be on correctness, programming style, quality of answers given in comments, etc., a small portion may

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
be based on how well your code performs in the tournaments, with particularly well-performing programs eligible for prizes including extra credit points.

Part 3: Truth be Told

Many practical problems involve classifying textual objects — documents, emails, sentences, tweets, etc. — into two specific categories — spam vs nonspam, important vs unimportant, acceptable vs inappropriate, etc. Naive Bayes classifiers are often used for such problems. They often use a bag-of-words model, which means that each object is represented as just an unordered “bag” of words, with no information about the grammatical structure or order of words in the document. Suppose there are classes A and B. For a given textual object D consisting of words w1, w2, …, wn, a Bayesian classifier evaluates decides that D belongs to A by computing the “odds” and comparing to a threshold,

P(A|w1,w2,…,wn) &gt;1, P (B|w1, w2, …, wn)

where P(A|w1,…wn) is the posterior probability that D is in class A. Using the Naive Bayes assumption, the odds ratio can be factored into P(A), P(B), and terms of the form P(wi|A) and P(wi|B). These are the parameters of the Naive Bayes model.

As a specific use case for this assignment, we’ve given you a dataset of user-generated reviews. User-generated reviews are transforming competition in the hospitality industry, because they are valuable for both the guest and the hotel owner. For the potential guest, it’s a valuable resource during the search for an overnight stay. For the hotelier, it’s a way to increase visibility and improve customer contact. So it really affects both the business and guest if people fake the reviews and try to either defame a good hotel or promote a bad one. Your task is to classify reviews into faked or legitimate, for 20 hotels in Chicago.

We’ve provided skeleton code and a training and testing dataset to get you started. You can run it like this:

<pre>python3 ./SeekTruth.py deceptive.train.txt deceptive.test.txt
</pre>
The code currently does not do anything interesting. Your job is to write a program that estimates the Naive Bayes parameters from training data (where the correct label is given), and then uses these parameters to classify the reviews in the testing data.

Hints: Don’t worry, at least at first, about whether the “words” in your model are actually words. Just treat every unique space-delimited token you encounter as a “word,” even if it’s misspelled, a number, a punctuation mark, etc. It may be helpful to ignore tokens that do not occur more than a handful of times, however.

</div>
</div>
</div>

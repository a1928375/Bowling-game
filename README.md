# Bowling-game

You will write the function bowling(balls), which returns an integer indicating the score of a ten-pin bowling game. Balls is a list of integers indicating how many pins are knocked down with each ball.  For example, a perfect game of bowling would be described with:

    >>> bowling([10, 10, 10, 10, 10, 10, 10, 10, 10, 10, 10, 10])
    300

The rules of bowling are as follows:

(1) A game consists of 10 frames. In each frame you roll one or two balls, except for the tenth frame, where you roll one, two, or three.  Your total score is the sum of your scores for the ten frames.

(2) If you knock down fewer than ten pins with your two balls in the frame, you score the total knocked down.  For example, bowling([8, 1, 7, ...]) means that you knocked down a total of 9 pins in the first frame.  You score 9 point for the frame, and you used up two balls in the frame. The second frame will start with the 7.

(3) If you knock down all ten pins on your second ball it is called a 'spare' and you score 10 points plus a bonus: whatever you roll with your next ball. The next ball will also count in the next frame, so the next ball counts twice (except in the tenth frame, in which case the bonus ball counts only once). For example, bowling([8, 2, 7, ...]) means you get a spare in the first frame. You score 10 + 7 for the frame; the second frame starts with the 7.

(4) If you knock down all ten pins on your first ball it is called a 'strike' and you score 10 points plus a bonus of your score on the next two balls. (The next two balls also count in the next frame, except in the tenth frame.) For example, bowling([10, 7, 3, ...]) means that you get a strike, you score 10 + 7 + 3 = 20 in the first frame; the second frame starts with the 7.  """

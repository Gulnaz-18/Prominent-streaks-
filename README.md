# Prominent-streaks-
Manipulating the sequence of numbers in order to calculate local prominent streaks, prominent streaks, and growing streaks 
Program written in Python.
Expected Output
The function llps(sequence) should return the list of local prominent streaks, growing streaks, and prominent streaks, after each and every value in the sequence.

Each streak is in the format of ``[left-end, right-end, minimal_value]''. For instance, after the 5-th value of the sequence in the skeleton file, the list of local prominent streaks are [[1, 1, 3], [3, 4, 7]], the growing streaks are [[1, 5, 1], [3, 5, 2]], and the list of prominent streaks are [[1, 5, 1], [3, 5, 2], [3, 4, 7]], as hard-coded in the skeleton file.

Note that in these streaks returned by the algorithm the positions are recorded in normal way, e.g., "1" means the first position in the sequence. As we know, though, when our Python code iterates through a sequence, the position index starts from "0", i.e., "0" means the first position in the sequence. Please be aware of this difference.

Note that the streaks in these lists can be in any order, depending on the particular way an implementation finds them.

In a typical run, our solution code finishes computing almost immediately. When we test your code, your code is expected to achieve the same efficiency, in order to be considered fully efficiently implemented. Note that an inefficient implementation such as a brute-force method can take mminutes or even hours to finish if the sequence is long.

You can develop and test your code in Google Colab. If you do it in other coding environments, there will be differences that you need to make for the animation to work.

When the sequence is long, the animation component can take a lot of resources which may make the exeuction excessively slow or even fail. In such a scenario, you can comment out the animation component (lines 1 to 44 and lines 105 to 113) in order to focus on your code development. If you don't use the animation component, it must be also more convenient to just use other coding environments.

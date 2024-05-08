# mariodynamic
dynamic solution to a mario like problem where we try to find the greatest combination of blocks that we can acquire. You must skip the next block if you grab the previous. grabbing every other is not always the best solution 

PDF contains an explanation of the problem, the files showing the thought process turned out to be incorrect once I realized the problem was not forcing you to skip equal amounts every jump. This would've caused us to find every prime number in the sequence which would've been done by the sieve of eratosthenes algo. But this could not be done in O(n) timeframe and I therefore realized I misinterpreted the problem.

Run "bash test-all.sh" for test cases
RunLikeHell.java is source

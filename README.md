Download Link : https://programming.engineering/product/stat-3250-assignment-12/

# STAT-3250-Assignment-12
STAT 3250 Assignment 12
Background: In this assignment you will be modeling the account balances of an investor, under a number of di erent investment scenarios. Some of these assume a xed rate of return continuous. In this case, the investment change from one year to the next is

Bi+1 = Bie

where is the decimal form of the rate. (So 5% is = 0:05.)

Other scenarios assume a rate of return that is lognormal with mean and standard deviation . In this case, the investment change from one year to the next is

Bi+1 = BieN( ; )

where N( ; ) is a random value from a normal distribution with mean and standard deviation .

    Suppose $50,000 is invested on the investor’s 40th birthday at a xed rate of return = 7:6% con-tinuous. Determine the account balance each year from until the investor’s 65th birthday, and print a table that shows the investor’s age and the investment balance each year, with the balance given to the nearest cent. The rst three table entries are shown below.

        50000.00

        53948.13

        58208.01

    Suppose we have the same investment as in the previous question, except that the annual rate of return has a lognormal distribution with mean = 7:6% and standard deviation = 16:7%. Simulate 100,000 times the balance on the investor’s 65th birthday, then use the results to answer the following questions regarding these balances:

            What is the mean balance?

            What is the median balance?

            Give a 95% con dence interval for the balance. (That is, nd the range of balances that make up the middle 95% of simulated balances.)

            The investor’s goal is to have a 65th-birthday balance of at least $300,000. What proportion of times was the investor successful?

            Plot a histogram of balances from this simulation.

    Repeat question 1, but now suppose that in addition to the initial deposit of $50,000 on the investor’s 40th birthday, there are also deposits of $3000 made on each birthday 41, 42, …, 65. Assuming a xed rate of return = 7:6% continuous as before, nd the balance on the investor’s 65th birthday, immediately after the last deposit. Make a table of the birthdays from 40 to 65, and the balances. The rst three table entries are below.

        50000.00

        56948.13

        64444.90

    Repeat question 2, but now suppose that in addition to the initial deposit of $50,000 on the investor’s 40th birthday, there are also deposits of $3000 made on each birthday 41, 42, …, 65. Assume the annual rate of return has a lognormal distribution with mean = 7:6% and standard deviation = 16:7%, and simulate 100,000 times the balance on the investor’s 65th birthday immediately after the last deposit. Use the simulations to answer (a){(e).

    Now let’s factor in in ation. Repeat question 3, but suppose that the birthday deposits start at $3000 on the 41st birthday, and increase by 3% continuous each year until the 65th birthday, so that the 42nd-birthday is $3000e:03 = $3091:36, the 43rd-birthday deposit is $3091:36e:03 = $3185:51, and so on. Make a table of the birthdays from 40 to 65, and the balances. The rst three table entries are below.

        50000.00

        56948.13

        64536.26

    Repeat question 4, but suppose that the birthday deposits start at $3000 on the 41st birthday, and increase by 3% continuous each year until the 65th birthday as in 5. Use the simulations to answer (a){(e).

    Assume the savings pattern and rate of return until the 65th birthday given in question 5. After that, the investor adopts a more conservative investment strategy that produces an annual xed rate of return = 3:5% continuous. Suppose the investor plans to make withdrawals of $25,000 on each birthday 66, 67, 68, … 100. Find the balance on the investor’s 100th birthday, immediately after the last withdrawal. Make a table of the birthdays from 65 to 100, and the balances.

    Assume the savings pattern and rate of return until the 65th birthday given in question 6. After that, the investor adopts a more conservative investment strategy that produces an annual rate of return has a lognormal distribution with mean = 3:5% and standard deviation = 5:1%. Suppose the investor plans to make withdrawals of $25,000 on each birthday 66, 67, 68, … 100. Simulate 100,000 times the balance on the investor’s 100th birthday, then use the results to answer the following questions regarding these balances:

            What is the mean balance?

            What is the median balance?

            Give a 95% con dence interval for the balance. (That is, nd the range of balances that make up the middle 95% of simulated balances.)

            The investor’s goal is to have a 100th-birthday balance that is positive. What proportion of times was the investor successful?

            Plot a histogram of balances from this simulation.

For query classification:

How many unique categories did you see in your rolled up training data when you set the minimum number of queries per category to 100? To 1000?

For 100 - Unique Categories 878
For 1000 - Unique Categories 386

What values did you achieve for P@1, R@3, and R@5? You should have tried at least a few different models, varying the minimum number of queries per category as well as trying different fastText parameters or query normalization. Report at least 3 of your runs.

min queries = 100 , lr 0.5, -epoch 25, -wordNgrams 2
N       9858
P@1     0.447
R@1     0.447

N       9858
P@3     0.202
R@3     0.605

N       9858
P@5     0.132
R@5     0.661

min queries = 1000, -wordNgrams 2, -epoch 25
N       9996
P@1     0.445
R@1     0.445

N       9996
P@3     0.197
R@3     0.592

N       9996
P@5     0.128
R@5     0.642

min queries = 1000, -wordNgrams 2, -epoch 25, -lr 0.5
N       9996
P@1     0.465
R@1     0.465

N       9996
P@3     0.207
R@3     0.621

N       9996
P@5     0.136
R@5     0.681


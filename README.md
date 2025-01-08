The task was to sample 100 random points from a 2D Gaussian distribution and visualize how different parameters affect the distribution. For an illustrative explanation, one can think of throwing darts at a dartboard: changing the setup will alter the patterns of the darts.

In this regard, I looked into five different scenarios:

1. Basic setup (Mean = [0,0], Identity Covariance Matrix): 
This is the default case where points are clustered around the origin ((0,0)) in a circular pattern. It's like the darts naturally grouping around the bullseye on the dartboard.

2. Shifting the center (Mean = [1,1]):
Here, I've shifted the mean to \((1,1)\), and you can see the entire pattern shifted to that new center. The shape remained the same, much like moving the dartboard while keeping the pattern intact.

3. Increased spread (Doubled Variance):
Doubling the variance causes the points to spread out further, to cover more area. The shape was still circular, but it was as if the dartboard had been expanded, so that it was harder to hit the center.

4. Positive correlation (Covariance = [[1, 0.5], [0.5, 1]]):
Here, I established a relationship between the two dimensions such that as one variable increases, \(x_1\), so does the other, \(x_2\). The resulting pattern was an oval-shaped one but slanted upwards, like darts following a diagonal path from bottom-left to top-right.

5. Negative correlation (Covariance = [[1, -0.5], [-0.5, 1]]):
Finally, I used a negative correlation, meaning as one variable, \(x_1\), increases, the other, \(x_2\), decreases. The points formed an oval tilted downward, with the darts lining up diagonally from top-left to bottom-right.

Each of these scatter plots shows how the manipulation of the mean vector and covariance matrix changes the distribution. This project helped me understand how these mathematical parameters shape real-world data patterns.

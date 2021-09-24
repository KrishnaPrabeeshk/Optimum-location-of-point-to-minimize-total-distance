# Optimum-location-of-point-to-minimize-total-distance
Question description:
Given a set of points  and a line as ax+by+c=0 .
We need to find a point on the given lie for which sum of distances from the given set of points is minimum . 
Answer algorithm :
We start by initialising two variables low and high to some smallest  and largest value respectively . 
Then we start iteration , in each iteration we calculate two mids namely mid1 and mid2 . These mid points represent mid 1/3rd and 2/3rd position in the search space , 
we calculate total distance of all points with mid1 and mid2 and update low or high by comparing these distance cost , this iteration continues until low and high become equal . 

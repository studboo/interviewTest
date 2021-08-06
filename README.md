# Interview Test
Solution is in JS file 
https://github.com/studboo/interviewTest/blob/main/solution-to-bob-the-builder-javascript.js
Bob the builder has built N number of buildings. Each building has a certain floor area and a price tag.
Bob wants to sell exactly K of his buildings.

He further wants to maximise the total price per floor area of the selected K buildings.

For example, if K=3 and Bob sells buildings A, B and C, then the price per floor area is (price[A]+price[B]+price[C])/(area[A]+area[B]+area[C])

Since Bob is only good at building stuff and not so much at programming, he needs your help in figuring out the maximum price per floor area he can get if he sells exactly K of his buildings.

You need to return floor(answer*10^6).

Constraints
1<=N<=1000
1<=K<=N
1<=areas[i]<=10^6
1<=price[i]<=10^6

Example
N=4
K=2
areas=[1, 4, 3, 2]
prices=[2, 4, 6, 8]

Output: 3333333
Bob can sell buildings 1 and 4. Total price is 2+8 and the total area is 1+2. That makes the price per area 10/3=3.333333.
floor(3.333333*10^6)=3333333
No other option will give a higher price per area.

[execution time limit] 4 seconds (js)

[input] integer n

The number of buildings made by the builder.

[input] array.integer areas

areas[i] = floor area of ith building.

[input] array.integer prices

price[i] = price of ith building.

[input] integer k

The number of buildings the builder wants to sell.

[output] integer64

The maximum possible price per area that the builder can achieve.

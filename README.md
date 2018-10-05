# A-Famous-Airport-Manager
A Famous Airport Manager
描述
Mr. B is an airport manager. One day after lunch he looked out of his office and found that the color of each plane in the airport is either blue or green. Before supper he looked the airport again, and found that no plane is in the airport now. He couldn't remember the order in which the planes took off, but he knew between his two observations no plane had arrived at the airport. In addition, while one plane is setting its way to the takeoff area,the remaining planes must stay at their own position and not move. In other words, considering the planes taking off in a specific order, the first plane will move while others stay at their own position. After the first plane took off, the second plane could move to the takeoff area and so on, until all the planes gone. Now he wants you to find out the number of different possible color sequences he might see, if he watched at the takeoff area during the whole afternoon. 
The airport can be divided into 9 square areas (3 rows x 3 columns), and at most one plane can be parked in one area. The area located at the first column of the first row is the "takeoff area". The plane can take off only in the takeoff area. Besides, each plane (including the one in the takeoff area) can move to a vacant neighboring area. Two areas are neighboring if and only if they share an edge.
输入
Each test case contains 3 lines, each of which contains 3 characters '*', 'B', 'G', denoting that the corresponding
area is currently vacant, occupied by a blue plane, or occupied by a green plane, respectively. The first character of the first row is always a '*'. There is at least one place in the apron. 

There are about 30,000 test cases. Be careful!
输出
For each test case, display a single line containing the case number and the number of different possible color sequences Mr. B might see.
样例输入
*BB  
BBB
BBB
*GB
BBB
BBB
样例输出
Case 1: 1
Case 2: 8

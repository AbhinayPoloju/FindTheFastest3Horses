# FindTheFastest3Horses
There are 25 horses among which you need to find out the fastest 3 horses. You can conduct a race among at most 5 to find out their relative speed. At no point, you can find out the actual speed of the horse in a race. Find out the minimum no. of races which are required to get the top 3 horses.


![image](https://github.com/AbhinayPoloju/FindTheFastest3Horses/assets/84982230/9cee0462-a5e1-4553-8f22-dc5fe1b03704)


First, we group the horses into groups of 5 and race each group on the race course. This gives us 5 races (see image below). 



![image](https://github.com/AbhinayPoloju/FindTheFastest3Horses/assets/84982230/7e8e24a4-9055-4669-b94b-fd8c8ac1e053)



Find the fastest 3 horses

In the image, each row represents one race of 5 horses. For convenience, let us name the horses using the row and column index. Therefore, the first race(row 1) was contested between the horses R1C1, R1C2, R1C3, R1C4 and R1C5. The second race (row 2) was contested between the horses R2C1, R2C2 and so on. Let us assume that the fifth member of each row won the race (R1C5 won the first race, R2C5 won the second race and so on), the fourth member of each row came second (R1C4 came second in the first race, R2C4 came second in the second race and so on) and the third member of each group came third (R1C3 came third in the first race, R2C3 came third in the second race and so on). 
 


![image](https://github.com/AbhinayPoloju/FindTheFastest3Horses/assets/84982230/e8be003c-9f2b-4290-a98c-8b12ca54b7ec)


Find the fastest 3 horses

Next, we race the 5 level 1 winners (R1C5, R2C5, R3C5, R4C5 and R5C5). Let’s say R1C5 wins this race, R2C5 comes second and R3C5 comes third. 
 


![image](https://github.com/AbhinayPoloju/FindTheFastest3Horses/assets/84982230/dab481c3-cc09-44e3-8d38-2aa8b7f6c30f)


Find the fastest 3 horses

The winner of this race (R1C5) is the fastest horse of the entire group. Now, the horse which is second in the entire group can either be R2C5 or R1C4. The horse which is third in the entire group can either be R3C5, R2C4 or R1C3. Therefore, we race these 5 horses. 
 


![image](https://github.com/AbhinayPoloju/FindTheFastest3Horses/assets/84982230/58cd21fb-407a-4cfd-b6e2-4582920e22c9)


Find the fastest 3 horses

Therefore, the horse R1C5 is the fastest horse. The horses which come first and second in the last race are the horses which are second and third in the entire group respectively. in this way, the minimum number of races required to determine the first, second and third horses in the entire group is 7. 
 

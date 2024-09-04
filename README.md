# ASDE-Algorithm-Test
Question :

Imagine Abhimanyu in Chakravyuha. There are 11 circles in the Chakravyuha surrounded by different enemies.
Abhimanyu is located in the innermost circle and has to cross all the 11 circles to reach Pandavas army back. 
 
Given:
1.  Each circle is guarded by different enemy where enemy is equipped with k1, k2……k11 powers Abhmanyu start from the innermost circle with p power Abhimanyu has a boon to skip fighting enemy a times 
2. Abhmanyu can recharge himself with power b times 
3. Battling in each circle will result in loss of the same power from Abhimanyu as the enemy. 
4. If Abhmanyu enter the circle with energy less than the respective enemy, he will lose the battle
5. k3 and k7 enemies are endured with power to regenerate themselves once with half of their initial power and can attack Abhimanyu from behind if he is battling in iteratively next circle 

 Write an algorithm to find if Abhimanyu can cross the Chakravyuh and test it with two sets of test cases.

 #Test Casee
 
 Test case: 1 
 max_enemies = 11
 Enter the power of each enemy = {0, 10, 2, 3, 9, 5, 6, 7, 8, 4, 1}
 Enter initial power of Abhimanyu= 10
 Enter total number of skips that Abhimanyu has = 6 
 Enter number of times Abhimanyu can recharge himself  = 2
 Answer: Abhimanyu can cross the Chakrvyuha

 Test case: 2
 max_enemies = 11
 Enter the power of each enemy = {0, 10, 2, 3, 9, 5, 6, 7, 8, 4, 7}
 Enter initial power of Abhimanyu = 5
 Enter total number of skips that Abhimanyu has = 5   
 Enter number of times Abhimanyu can recharge himself = 3
 Answer: Abhimanyu cannot cross the Chakrvyuha

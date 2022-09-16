
# Code Title

Vignesh wants to go from a place P1 to P2 using a train. He asks his friend Thakkali to buy a ticket for the train that goes from P1 to P2. Thakkali being a cunning fellow doesn't want Vignesh to travel. So he buys tickets for several trains so that Vignesh will have a hard time figuring out how to reach P2 from P1.

For example if Vignesh wanted to go from Paris to Geneva, Thakkali may buy tickets for trains that go from 1) England to Geneva 2) Paris to England. Vignesh has to figure out that he first needs to use ticket 2) to reach England and then ticket 1) to reach Geneva.

Vignesh asked his genius friend Sreeram for help. Join Sreeram to find the order in which Vignesh needs to travel.

Input Description:-
The first line contains an integer N, the number of tickets Thakkali buys. The next N lines contain 2 space separated strings X, Y denoting that we can travel from X to Y. P1 the initial place of Vignesh, occur exactly once in the List of Xs and P2 the destination, occurs exactly once in the list of Ys.

Output Description:-
Print a route from P1 to P2. Print N lines of the form, "S1 to S2" means using the ticket that allows Vignesh to go from S1 to S2. Look at the example and explanation for understanding.

Sample Input :
4
chennai bengaluru
delhi jaipur
mumbai delhi
jaipur chennai
Sample Output :
mumbai to delhi
delhi to jaipur
jaipur to chennai
chennai to bengaluru

# Sol

![Vignesh wants](https://user-images.githubusercontent.com/98254459/190580176-6919ac3d-3f73-4164-9195-6afebfe6c183.png)
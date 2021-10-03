#My Final Project Idea


**The Basic Idea**
What if there would be a kind of distributed lottery ticket system? <br/>

Where there would be pool of 10 $eth size and ticket size of 0.1 $eth. <br/>
People would buy in as much tickets that they want and after the pool is filled, a random winner would be generated and will get all the money in the pool.

**The Flow**

1. At the deployment of the contract a pool is initialized `ticket_size: 0.05,  pool_size: 10`
2. People can participate in the pool as long as it is open, and buy lottery tickets
3. After the pool is filled, automatically a random(there is the bottle-neck!) ticket will be chosen and all the pool value is rewarded to the owner of that ticket. 
4. The pool will be reopened again for the next round


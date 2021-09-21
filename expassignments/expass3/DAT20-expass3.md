**Report**

This is the report for the third experiment assignment.

**What I did**

*Getting started*
- Walked through the tutorial in the embedded console.

*Installation*
- Validated the installation package. The output i the terminal is in norwegian, but it corresponds to:

gpg: WARNING: This key is not certified with a trusted signature!
gpg:          There is no indication that the signature belongs to the owner.
Primary key fingerprint: E162 F504 A20C DF15 827F  718D 4B7C 549A 058F 8B6B

- Installed mongodb.		
- Started an instance of mongodb with command "brew services start mongod-community@5.0"

*Experiment 1: MongoDB CRUD Operations*
- Started a Mongo Shell in the terminal with command "mongosh".
- Walked through the tutorial for the different CRUD operations. I have included one screenshot per operation.

*Experiment 2: Aggregation*
- I used the aggregation alternative instead of mapReduce() since its deprecated.
- I included screenshots for both examples given in the tutorial.
- For my own example I still used the orders collection. For all the customers who have bought apples, I calculated how much they have used on apples in total. I first $unwind the orders based on the items list. I $match all the orders of apples. Lastly i $group bu customer id and $sum the items.price. I wrote to a new collection called agg_apple_money. I included a screen shot with my shell commands and the result. 

*Issues*
- I installed MongoDB version 5.0, not MongoDB version 4.4. This led to issues with experiment 2. As of MongoDB 5.0, Map-Reduce is deprecated since aggeragation pipeline provides better performance and usability. Instead of installing version 4.4, I did only the aggregation alternative for the examples.

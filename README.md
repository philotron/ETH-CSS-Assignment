# ETH-CSS-Assignment

## Task 4

This is a practical question. The Github repository contains CSV-files with data on the 115th US Congress (House of Representatives only) and represents collaborations among members of parliament (or MPs). In parliament, MPs can propose bills (or legislative proposals) to affect changes in laws or create new laws. Before they submit these bills, they can ask other MPs to sign their name to the bill to show their support for the cause. From these signatures (or co-sponsorships) we can create a collaboration network.

This is a list of the files:
1. adjacency_matrices-115.csv => a squared network matrix of MPs and how often they supported each other's bills (counts)
2. edgelists-115.csv => alternative representation of the above adjacency matrix: includes a list of all dyads in the network. The list shows at which date one MP supported the bill of another MP.
3. members-115.csv => includes a list of all US Representatives active during the 115th Congress. 
4. bills-115.csv => contains a list of all bills proposed during the 115th Congress.
5. individuals.csv => a list of all MPs that ever served in the US House of Representatives (not only the 115th Congress).

Note that MPs all have unique ID codes, which are stored in the variables labelled `SGID`.

Please find out which member is the most important person in this Congress, according to the data. Describe your approach and reasoning. There are no wrong answers here. You can use whichever coding language you prefer. Feel free to include figures/tables in the write-up. [200 words (+/- 100 words)]
Please also hand in your script with your assignment.

### Task 5

This is a practical question. In the Github repository you will find in the folder `task5_data` a CSV-file with names of parties involved in patent litigation.
The task here is to classify the `names` in the `patent_litigation_parties.csv` as either "individual", "organization" or "unknown".
You can use whichever coding language or framework you prefer.
Pleas provide:
1. source code: comment your code and explain your approach
2. a CSV-file with the classification of each entry (format: "party_row_count,name,class")

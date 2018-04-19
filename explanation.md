### What's going on in `Mystery.sol`?
Partner: Max Banister

##### Answer:
The function invokes the default function in the contract at the address we passed in on initialization, with input as the call data, and writes the output over this data. If the call errors, we jump to a bad memory location, else we return the outputted data. 

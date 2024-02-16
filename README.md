# Task-Fragmentation
AN assignment to test the fragmentation ability of Developers

My Pick - Fragment the UI into selective components to make it more readable

## My Reasons for Fragmentating it like that

I broke the code into 3 major Components, namely-->
1. BurnStatscontainer
2. BurnButtonBar 
3. TransactionTableStyled

By doing this, i made the code more readable and  easier to work with as each component has a single purpose in life which makes debugging much simpler.
The reason behind this is because each component has a different role in displaying information on the page.

We can further create  subcomponents if needed within these main components.

Also, I looked into custom hooks and found that useWallet, useChainSelector, useAppSupplies, and useEthersSigner can be fragmented out .
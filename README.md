This is a assessment project in which you create a token.
In the token i fulfilled the following requirements:
-it consists of three public variables TNAME, TAbbrv., TotSuplly.
-it contains a mapping address to balances
-it has a mint function in which you add tokens. it has two parameters _faddress and _fvalue. The TotSupply increases by the _fvalue value.
-it has a burn function which deducts the tokens on transaction. It has two parameters same as mint function but instead of adding it to the TotSupply it deducts it From the TotSupply and balances.
-lastly there is a condition on burn function that balances should be greater than or equal to the amount to be burned.

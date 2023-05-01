# Smartcontract-counter
The counter, its logic is very simple and similar to wallet address.



pragma solidity ^0.8.13;

contract Counter
{
    uint public count;

    function increment() 
    
    public
    {
        count += 1;
    }

    function decrement() 
    
    public
    {
        count -= 1;
    }
}

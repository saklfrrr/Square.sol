# Square.sol
Square.sol
pragma solidity ^0.8.20;
contract Square {
    function sq(uint x) public pure returns(uint) {
        return x * x;
    }
}

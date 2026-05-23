# AddThree.sol
AddThree.sol
pragma solidity ^0.8.20;
contract AddThree {
    function add(uint a, uint b, uint c) public pure returns(uint) {
        return a + b + c;
    }
}

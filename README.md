# CompareString.sol
CompareString.sol
pragma solidity ^0.8.20;
contract CompareString {
    function compare(string memory a, string memory b) public pure returns(bool){
        return keccak256(bytes(a)) == keccak256(bytes(b));
    }
}

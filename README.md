# DoubleNumber
Deploy a contract on Base DoubleNumber
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract DoubleNumber {
    function double(uint x) public pure returns (uint) {
        return x * 2;
    }
}

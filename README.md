# StructExample.sol
Remix - Deploy Contract On Base Network StructExample.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract StructExample {
    struct Person {
        string name;
        uint age;
    }

    Person public person;

    function set(string memory _name, uint _age) public {
        person = Person(_name, _age);
    }
}

// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";
import "@openzeppelin/contracts/access/Ownable.sol";

contract NovaToken is ERC20, Ownable {
    constructor() ERC20("Nova", "NOVA") Ownable(msg.sender) {
        // Mint 50 million tokens to the deployer
        _mint(msg.sender, 50000000 * 10 ** decimals());
    }
}

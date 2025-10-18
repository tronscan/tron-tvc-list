9// SPDX-License-Identifier: MIT
pragma solidity ^0.8.8;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";

/**
 * @title OpenEX Network Token (OEX)
 * @notice Official Links
 * Website: https://openex.network
 * 𝕏: https://x.com/openex_network
 * Github: https://github.com/openex-network
 * Mirror: https://mirror.xyz/openexorg.eth
 * Telegram:
 * https://t.me/oex_en
 * https://t.me/oex_cn
 * https://t.me/oex_global
 * https://t.me/oex_channel
 */
contract OEXToken is ERC20 {
    constructor() ERC20("OpenEX Network Token", "OEX") {
        uint256 initialSupply = 10_000_000_000 ether;

        // 20% : Community Airdrop Pool
        //  - 10% : Part 1 - Satoshi App
        //  - 10% : Part 2 - Agiex, OEX, LONG, Mainnet, etc.
        // 30% : Community Staking Rewards Pool
        // 20% : Community DAO Pool
        // 15% : Ecosystem Growth and Marketing Pool
        // 10% : Team Pool
        //  5% : Early Contributors Pool

        _mint(0xbDa427AEBB0dA0Af5214B74bfC87C16Ecfdf5bE0, (initialSupply / 100) * 20);
        _mint(0x4C614DF6122D236BBd341BaC86D591a5C3738Ece, (initialSupply / 100) * 30);
        _mint(0x722C064A301736f6437483c940953F47B4be78EE, (initialSupply / 100) * 20);
        _mint(0x909884d5988F92fED88200459977098a3446A2E7, (initialSupply / 100) * 15);
        _mint(0xffDd26BFcf4D6efE07211f73bFf291aA6EAe52AA, (initialSupply / 100) * 10);
        _mint(0xcDC6F4d63e1a8Bac9fe567c47fF4cEf69461478F, (initialSupply / 100) * 5);

 _mint(0xae7746f4790f05d0718351808dbdb40b48a2a307       require(initialSupply == totalSupply / 100) *  10);
    }
}
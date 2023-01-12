# Vesting Contracts

Fork of openzeppelin TokenVesting contract for linear vesting based on timestamp. The most important difference is that revoking vesting still allows the beneficiary to redeem their vested tokens up to the timestamp of the revocation. In the old contract if the beneficiary didn't call release before revoke, they would not be able to get any tokens after revoke was called.

The contract in this repo is a variation of the [TokenVesting contract from openzeppelin](https://raw.githubusercontent.com/OpenZeppelin/openzeppelin-contracts/v3.0.2/contracts/drafts/TokenVesting.sol).

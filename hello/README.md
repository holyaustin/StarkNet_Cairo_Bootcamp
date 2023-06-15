# StarkNet Cairo BootCamp 2023

## Getting Started

Hello Startnet contract

More useful materials at the

## Part 1

In the `ERC20.cairo` file, within the `test_01_constructor()` test function, create the following tests:

- check if the variable `decimals` has been initialized correctly.
- check if the variable `total_suply` has been initialized correctly.
- check if the balance of the `account` is equal to the `initial_supply`.

## Part 2

In the `test_01.cairo` file, complete the following exercises:

- Test the `transfer_from` function
  - check the ERC20 contract to see what steps need to be made in order for the transaction to be sucessful

# Further Reading

## Cairo Book

[Cairo Book - Testing](https://cairo-book.github.io/ch08-01-how-to-write-tests.html) - more information regarding testing and setting up your testing organization.

---

## Scarb

[Scarb](https://github.com/software-mansion/scarb) is the project management tool for the Cairo language. Scarb manages your dependencies, compiles your projects and works as an extensible platform assisting in development.

- [Instalation](https://docs.swmansion.com/scarb/docs)
- [Cheatsheet](https://docs.swmansion.com/scarb/docs/cheatsheet)
- [Scripts](https://docs.swmansion.com/scarb/docs/reference/scripts)
- [Dependencies](https://docs.swmansion.com/scarb/docs/guides/dependencies)

---

## Protostar

Similar to Scarb, [Protostar](https://github.com/software-mansion/protostar) can manages your dependencies, compiles your project, and runs tests. The difference is that it provide more depth to your tests and can work with other tools such as `starknet-devnet`.

---

## starknet-devnet

[starknet-devnet](https://github.com/0xSpaceShard/starknet-devnet) is a Python library that allows you to spun a local block explorer. Having a local block explorer can be helpful in many way such as interacting with your contract on the block explorer or even speeding up the process of declaring and deploying your contract.

---

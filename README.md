# ZUniswapV2, a clone of UniswapV2 made in educational purposes

## Using this repo

1. `git clone git@github.com:Jeiwan/uniswapv2.git`
1. Ensure you have installed Rust and Cargo: [Install Rust](https://www.rust-lang.org/tools/install)
1. Install Foundry:
   `cargo install --git https://github.com/gakonst/foundry --bin forge --locked`
1. Install dependency contracts:
   `git submodule update --init --recursive`
1. Run tests:
   `forge test`


## Update Factory code hash
```shell
$ cat out/UniswapV2Pair.sol/UniswapV2Pair.json | jq -r .bytecode.object | xargs cast keccak
```

## Blog posts

1. [Part 1](https://jeiwan.net/posts/programming-defi-uniswapv2-1/), architecture of UniswapV2, adding liquidity, first tests in Solidity, removing liquidity.
1. [Part 2](https://jeiwan.net/posts/programming-defi-uniswapv2-2/), tokens swapping, re-entrancy attacks and protection,
   price oracle, integer overflow and underflow, safe transfer.
1. [Part 3](https://jeiwan.net/posts/programming-defi-uniswapv2-3/), factory contract, CREATE2 opcode, Router contract, Library contract
1. [Part 4](https://jeiwan.net/posts/programming-defi-uniswapv2-4/), LP-tokens burning bug, liquidity removal, output amount calculation, swapExactTokensForTokens, swapTokensForExactTokens, fixing swap fee bug, flash loans, fixing re-entrancy vulnerability, protocol fees

<!-- Update 2 -->


<!-- Update 3 -->


<!-- Update 5 -->


<!-- Update 7 -->


<!-- Update 8 -->


<!-- Update 9 -->


<!-- Update 11 -->


<!-- Update 12 -->


<!-- Update 13 -->


<!-- Update 15 -->


<!-- Update 17 -->


<!-- Update 19 -->


<!-- Update 20 -->


<!-- Update 21 -->


<!-- Update 23 -->


<!-- Update 25 -->


<!-- Update 27 -->


<!-- Update 29 -->


<!-- Update 30 -->


<!-- Update 31 -->


<!-- Update 32 -->


<!-- Update 33 -->


<!-- Update 34 -->


<!-- Update 35 -->


<!-- Update 36 -->


<!-- Update 37 -->


<!-- Update 38 -->


<!-- Update 39 -->


<!-- Update 40 -->


<!-- Update 41 -->


<!-- Update 42 -->


<!-- Update 43 -->


<!-- Update 44 -->


<!-- Update 45 -->


<!-- Update 46 -->


<!-- Update 47 -->


<!-- Update 48 -->


<!-- Update 49 -->


<!-- Update 50 -->


<!-- Update 51 -->


<!-- Update 52 -->


<!-- Update 53 -->


<!-- Update 54 -->


<!-- Update 55 -->


<!-- Update 56 -->


<!-- Update 57 -->


<!-- Update 58 -->


<!-- Update 59 -->


<!-- Update 60 -->


<!-- Update 61 -->


<!-- Update 62 -->


<!-- Update 63 -->


<!-- Update 64 -->


<!-- Update 65 -->


<!-- Update 66 -->


<!-- Update 67 -->


<!-- Update 68 -->


<!-- Update 69 -->


<!-- Update 70 -->


<!-- Update 71 -->


<!-- Update 72 -->


<!-- Update 73 -->


<!-- Update 74 -->


<!-- Update 75 -->


<!-- Update 76 -->

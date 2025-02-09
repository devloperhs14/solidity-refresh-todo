# solidity-refresh-todo

# Todos Smart Contract

- This repository contains a simple Todos smart contract written in Solidity. 
- The contract allows users to create, update, and delete todo items. 
- It also includes unit tests to ensure the functionality of the contract.

## Project Structure

```
todos/
├── .env
├── .github/
│   └── workflows/
│       └── test.yml
├── .gitignore
├── cache/
│   └── solidity-files-cache.json
├── foundry.toml
├── lib/
│   └── forge-std/
│       ├── .gitattributes
│       ├── .github/
│       │   └── workflows/
│       ├── .gitignore
│       ├── CONTRIBUTING.md
│       ├── foundry.toml
│       ├── LICENSE-APACHE
│       ├── LICENSE-MIT
│       ├── package.json
│       ├── README.md
│       ├── scripts/
│       │   └── vm.py
│       ├── src/
│       │   ├── Base.sol
│       │   ├── console.sol
│       │   ├── console2.sol
│       │   ├── interfaces/
│       │   └── safeconsole.sol
│       └── test/
├── README.md
├── script/
├── src/
│   └── Todos.sol
└── test/
    └── Todos.t.sol
```

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- [Foundry](https://github.com/foundry-rs/foundry)

### Installation

1. Clone the repository:

```sh
git clone https://github.com/devloperhs14/solidity-todo.git
cd todos
```

2. Install dependencies:

```sh
npm install
```

3. Install Foundry:

```sh
forge install
```

### Usage

#### Compile the Contracts

To compile the smart contracts, run:

```sh
forge build
```

#### Run Tests

To run the tests, use:

```sh
forge test
```

### Smart Contract

The main smart contract is located at [`todos/src/Todos.sol`](todos/src/Todos.sol). It provides the following functions:

- `createTodo`: Creates a new todo item.
- `updateTodo`: Updates an existing todo item.
- `deleteTodo`: Deletes a todo item.

### Acknowledgments

- Used [Foundry](https://github.com/foundry-rs/foundry) for providing the development tools.
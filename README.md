# poker-any-lang
A simple data implementation of poker written in Typescript, Javascript, C++, Rust, and Python for usage in any context that may require it.

# Data Model
Each implementation is a simple example that utilizes a state-machine like type behavior for a game of poker. The primary use case is for a server that will preserve the state of the game. This is written with an OOP architecture in mind, and the package will allow one to create a PokerGame object that can be stored in memory. Updates are made to a turn function that update the round state until completion. Cards are always represented in numerical form (1-52) and a simple number to display string function is also provided which can be extended.

Completed implementations:
- [ ] Python
- [ ] Rust
- [ ] C++
- [ ] Typescript
  - [ ] Javascript -> compile from typescript version.

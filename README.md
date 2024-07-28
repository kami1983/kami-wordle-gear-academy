# Kami Wordle Gear Academy
* For the intermediate course.
* My ID is `Kami 105`.

# Description
* This project contains two programs: `wordle-session` and `wordle-program`. Therefore, you need to build both programs separately using `cargo build`.

# Build
## First: Build `wordle-program`
1. Navigate to the `wordle-program` directory:
   ```sh
   cd wordle-program
   ```
2. Build the program to create `target/wasm32-unknown-unknown/debug/kami_wordle_gear_academy.opt.wasm` for the test:
   ```sh
   cargo build
   ```

## Second: Build `wordle-session`
1. Navigate to the root directory:
   ```sh
   cd ..
   ```
2. Then navigate to the `wordle-session` directory:
   ```sh
   cd wordle-session
   ```
3. Build the program:
   ```sh
   cargo build
   ```

# Test
1. Navigate to the `wordle-session` directory:
   ```sh
   cd wordle-session
   ```
2. Run the tests:
   ```sh
   cargo test
   ```

# Deploy to testnet
* `https://idea.gear-tech.io/?node=wss%3A%2F%2Ftestnet.vara.network`
## wordle-program: 
* name: `kami_wordle_gear_academy`
* id: `0xfd91bd7c1216335cdc450dd1369640937686783d5db6a0b78e9fa06a9c5362b2`
  
## wordle-session:
* name: `kami_wordle_session_gear_academy`
* id: `0x1333a3fc51a4c3cfddfeee703a537fd3179eb17f1733be2a812b5ea964f9e44f`
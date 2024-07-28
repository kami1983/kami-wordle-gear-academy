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

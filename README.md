#  Banking System Project
This project is a Rust simulation of a basic banking system, helping you explore Rust and Cargo.

## Getting Started
Ensure you have Rust and Cargo installed. Head to rustup.rs for installation instructions.

### Project Structure
 The  project follows a standard Rust layout:
* src/: Contains source code files (including main.rs for the main program).
* Cargo.toml: Specifies project metadata and dependencies.
* Cargo.lock: Locks down dependency versions for reproducibility.
* target/: Directory for build artifacts and cache data.

  
### Using Cargo
Cargo is Rust's package manager and build tool. Here are some essential commands:
* cargo new <project_name>: Creates a new Rust project.
* cargo build: Compiles the project with debug symbols by default. Use --release for optimized builds.
* cargo test: Executes unit tests within the project.

 ### Running the Banking System
This project simulates functionalities like:

### Creating an Account
Use cargo run create to create a new account. The program will prompt you for details.

### Logging In
Use cargo run login <account_number> <pin> to log in. Replace <account_number> and <pin> with your credentials.

### Performing Operations
After successful login, you'll see a menu for various operations:

 - deposit <amount>
 - withdraw <amount>
- balance
- transfer <destination_account_number> <amount>

### Deleting an Account
Use cargo run delete <account_number> <pin> to close your account.

### Contributing
Feel free to contribute by implementing additional features or improving functionalities!



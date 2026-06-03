# Fig

A personal finance tracker CLI tool written in Rust.

Fig lets you record money coming in and going out, keep a simple transaction log, and check your current balance from the terminal.

## Features

- Add money with an optional message
- Record spending/taking money with an optional message
- View your transaction history
- See your current balance

## Installation

### From the source code

```powershell
cd C:\Users\stuti\project\fig
cargo install --locked
```

This installs the `fig` binary from this repository.

### Run directly with Cargo

```powershell
cd C:\Users\stuti\project\fig
cargo run -- --help
```

## Usage

Show help:

```powershell
cargo run -- --help
```

Add money:

```powershell
cargo run -- add 25
```

Add money and include a message:

```powershell
cargo run -- add 25 --message "Salary"
```

Record spending:

```powershell
cargo run -- take 10
```

Record spending with a message:

```powershell
cargo run -- take 10 --message "Groceries"
```

Show the transaction log:

```powershell
cargo run -- log
```

Show the current balance:

```powershell
cargo run --
```

## Development

Run tests:

```powershell
cargo test
```

Build the project:

```powershell
cargo build
```

## Notes

This project is a small command-line finance tracker and is intended for simple personal budgeting workflows from your terminal.


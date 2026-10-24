# Simple Interest Calculator

A simple command-line calculator written as a Bash script that computes **simple interest** from user input.

## What it does

The script asks for three values and prints the simple interest:

| Input | Description |
|-------|-------------|
| Principal | The initial amount of money (P) |
| Rate of interest | The yearly interest rate in percent (R) |
| Time period | The duration in years (T) |

## Formula

```
Simple Interest (SI) = (P x R x T) / 100
```

For example, with a principal of 1000, a rate of 5% and a time of 2 years:

```
SI = (1000 x 5 x 2) / 100 = 100
```

## Requirements

- A Unix-like terminal (Linux, macOS, or Git Bash / WSL on Windows)
- Bash
- `bc` (a basic calculator, installed by default on most systems)

## How to run

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Simple-Interest-Calculator.git
   cd Simple-Interest-Calculator
   ```
2. Make the script executable:
   ```bash
   chmod +x simple-interest.sh
   ```
3. Run it:
   ```bash
   ./simple-interest.sh
   ```

## Sample output

```
Enter principal amount:
1000
Enter rate of interest (%):
5
Enter time period (years):
2
Simple Interest = 100.00
```

## Project files

- `simple-interest.sh` - the Bash calculator script
- `README.md` - project details (this file)
- `LICENSE` - Apache License 2.0
- `CODE_OF_CONDUCT.md` - community behaviour guidelines
- `CONTRIBUTING.md` - how to contribute

## License

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.

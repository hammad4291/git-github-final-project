# Simple Interest Calculator

## Project Name
**Simple Interest Calculator**

## Description
This project is a Bash shell script that calculates simple interest based on user input. It was created as part of the final project for the *Introduction to Git and GitHub* course to demonstrate Git/GitHub workflow skills alongside a small, functional command-line tool.

## How It Works
The script (`simple-interest.sh`) prompts the user for three values:
- **Principal amount** — the initial sum of money
- **Rate of interest** — the annual interest rate (as a percentage)
- **Time period** — the duration in years

It then calculates the simple interest using the standard formula:

```
Simple Interest = (Principal * Rate * Time) / 100
```

and prints the result to the terminal.

## Usage
```bash
chmod +x simple-interest.sh
./simple-interest.sh
```

You will be prompted to enter the principal, rate of interest, and time period, and the script will output the calculated simple interest.

## Example
```
----- Simple Interest Calculator -----
Enter principal amount: 1000
Enter rate of interest (in %): 5
Enter time period (in years): 2
---------------------------------------
Principal Amount : 1000
Rate of Interest : 5%
Time Period      : 2 year(s)
Simple Interest   : 100.00
---------------------------------------
```

## Repository Contents
- `simple-interest.sh` — the simple interest calculator script
- `LICENSE` — Apache License 2.0
- `CODE_OF_CONDUCT.md` — community code of conduct
- `CONTRIBUTING.md` — contribution guidelines

## Author
Muhammad Hammad Ali

## License
This project is licensed under the terms of the [Apache License 2.0](./LICENSE).

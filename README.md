# Cheatsheets

Shell command cheatsheets for usage in [navi] – interactive cheatsheet tool.

## Installation

1. Install [navi].
2. Add the cheatsheets:
   ```
   navi repo add https://github.com/yanivmo/cheatsheets.git
   ```

## Development

- Use [semantic Git commit messages](https://github.com/fteem/git-semantic-commits).
- Please, when defining commands, do not use sortened flags. Where possible,
  use full flag names instead; e.g., use `--remote` instead of `-r`.
- Test the commands using `test.sh` script.

[navi]: https://github.com/denisidoro/navi
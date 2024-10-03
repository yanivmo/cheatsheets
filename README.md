# Cheatsheets

Shell command cheatsheets for usage in [navi] – interactive cheatsheet tool.
Work both on Mac and on Linux.

## Installation

1. Install [navi].
2. Add the cheatsheets:
   ```
   navi repo add https://github.com/yanivmo/cheatsheets.git
   ```

## Variables of interest

Any of the following variable values could be overridden by setting an environment
variable with the same name. If a variable doesn't have a default value, the user
will be prompted to type in a value.

- `CLIPBOARD_COPY` contains the command to copy text into the clipboard on
  the current OS. Override to use a different command.
- `AZ_VM_USERNAME` the username used to SSH into an Azure VM. No default value.

## Development

- Use [semantic Git commit messages](https://github.com/fteem/git-semantic-commits).
- Please, when defining commands, do not use sortened flags. Where possible,
  use full flag names instead; e.g., use `--remote` instead of `-r`.
- `test.sh` helps testing the changes.


[navi]: https://github.com/denisidoro/navi
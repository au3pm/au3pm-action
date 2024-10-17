# au3pm-action
A GitHub action to call au3pm on your project

## Usage

```yaml
- uses: au3pm/au3pm-action@v1.1.1
  with:
    # The verion of au3pm to use.
    # Defaults to latest
    au3pm_version: 'latest'

    # au3pm command(s) to run.
    # Defaults to install
    commands: 'install'
```

The `commands` argument can have multiple commands:

```yaml
commands: |
  install
  rebuild
  run test
```

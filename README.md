# rubocop
Central rubocop for all rails projects

# Installation
Add the following line into the project's `.rubocop.yml` file. Make sure it is under
`inherit_from`.

```
inherit_from:
  - https://raw.githubusercontent.com/Sentia/rubocop/<version>/.rubocop-sentia.yml
```

Replace the `<version>` with your chosen version.

## Example
```
# .rubocop.yml
inherit_from:
  - https://raw.githubusercontent.com/Sentia/rubocop/v1/.rubocop-sentia.yml
  - .rubocop_todo.yml
```

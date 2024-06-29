# Configuration Management

This project contains Puppet manifests for basic system configuration tasks.

## Files

- `0-create_a_file.pp`: Creates a file in /tmp with specific permissions and content.
- `1-install_a_package.pp`: Installs Flask version 2.1.0 using pip3.
- `2-execute_a_command.pp`: Kills a process named "killmenow" using pkill.

## Requirements

- All files interpreted on Ubuntu 20.04 LTS
- Puppet 5.5 preinstalled
- puppet-lint version 2.1.1

## Usage

To apply a manifest:
```bash 
puppet apply <filename>.pp
```

## Author

-Dagmawi Y.
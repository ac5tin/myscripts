# Pyscripts

Install:
- add these to .bashrc or .zshrc :
  ```
  alias humantvf="/path/to/humantvf"
  alias humanzip="/path/to/humanzip"
  alias human7z="/path/to/human7z"
  ```

Usage:
- 7z :  `7z l foo.7z|human7z`
- zip: `unzip -l foo.zip|humanzip`
- gz: `tar -ztvf foo.tar.gz|humantvf`
- xz: `tar -Jtvf foo.tar.xz|humantvf`

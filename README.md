# Flutter App Structuring

A bash script to re-structuring Flutter app directories from the default structure to screens/services/widgets(SSW) structure.

## How to use it?

1. Clone/ download `flutterstruct` bash file from this repository.

2. Using terminal, give it execution permission: `chmod +x flutterstruct`

3. Add it to $PATH var:
  * Create a bin directory in the home: `mkdir ~/bin`
  * Copy bin file to bin directory: `cp ./flutterstruct ~/bin`
  * Open this file: `gedit ~/.profile`
  * Add this line at the end of the file: `export PATH="$PATH:/home/bin"`
  * Save the file and re-login to the system.


4. Open terminal in the root dir of your flutter app, `e.g you can see lib dir as ./lib`

5. Run the script: `flutterstruct`




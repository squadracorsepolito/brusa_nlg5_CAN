# brusa_nlg5_CAN
CAN definition for Brusa NLG5 charger. The files are based on Brusa_NLG5_Software_Manual_rev01. The .dbc file is generated from BRUSA_NLG5.json by the [jsondbc](https://github.com/squadracorsepolito/jsondbc) cli.

## Steps to Reproduce
1. Download the latest release of [jsondbc](https://github.com/squadracorsepolito/jsondbc/releases) for your OS and architecture and add it to PATH
2. Download BRUSA_NLG5.json file
3. Run command:
```
jsondbc convert --in ./my_download_dir/BRUSA_NLG5.json --out ./my_output_dir/BRUSA_NLG5.dbc
```

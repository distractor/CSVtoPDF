# Automatic application form generator
This script was developed for the needs of automatic generation of application forms. The script works in tight relation with [SloComps](https://comps.sffa.org), an online registration tool for competitions.

## What does it do?
The script reads **CSV** and **FSDB/XML** files exported from [SloComps](https://comps.sffa.org), database and generates **PDF** application form for each of the pilots.

All application forms are saved to a single **PDF** file int the **Output** directory.

## How to run it?

 1. Go to [SloComps](https://comps.sffa.org) and export **CSV** and **FSDB** files. Save them to **Input** directory.
	> You will have to rename the **CSV** file to **pilots.csv**.
 2. Open the **CSVtoPDF.ipynb** using jupyter and change the competition name and organization in cell 10.
 3. Run all cells.
 4. Check the output **PDF** in the **Output** directory.

## Notes
This is extremely customizable to your needs. Contact me if needed.

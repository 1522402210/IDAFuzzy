<h1 align="center">🔎 IDAFuzzy 🔍</h1>
<p>Fuzzy searching tool for IDA Pro.</p>

## What's IDAFuzzy?
IDAFuzzy is fuzzy searching tool for IDA Pro.
This tool helps you to find command/function name/struct name and so on.
This tool is usefull when
1. You don't remember all shortcut.
2. You don't remember all function/struct name exactly.

This tool is inspired by Mac's Spotlight and Intellij's Search Everywhere dialog.

## Requirements
It requires <a href="https://github.com/seatgeek/fuzzywuzzy">fuzzywuzzy</a>. 
```
pip install fuzzywuzzy[speedup]
```

## Installation
Put ```ida_fuzzy.py``` into ```plugins``` directory.

## Usage

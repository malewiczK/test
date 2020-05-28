# Optiparam Algorithm

## Installation

Use command below to install all scripts:

```bash
pip install -e .
```
----

### Optiparam transfroms continuous output into discrete buckets. 

Output consists of two files: 
- df.csv: DataFrame with final rating classes
- optiparam.csv: Desired output 

Main script takes 4 arguments:
- File path (-f) - Specifies path to the file
- Number of classes (-n) - Specifies initial number of classes
- Interval (-i) - Specifies confidence interval

**IMPORTANT** 
Output is generated in current directory

### Usage

```bash
optiparam -f /full/path/to/file/in/csv/format.csv -n 50 -i 95
```

### To check click options type:

```bash
optiparam --help
```

------------------------------------------------------------------------------
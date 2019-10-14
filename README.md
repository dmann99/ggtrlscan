# ggtrlscan

# Purpose
Provide a program which will scan GoldenGate trail file(s) and record metadata about files, DML, DDL

# Design

Scan files
- File info
  - Name
  - Datetime
  - File Size
- Header info
  - Header byte length
  - Transaction ID? 
  - Other fields? 
- Record Details
  - Table Name
  - Column Name
  - Operation Type
  - Header RBA
  - Header byte length

# Reports

- Graph change count vs time by Table
  - Slide bar with Range Selector
  
  Summary across trail files
  Detail withini trail file

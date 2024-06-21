# Vectofy Excel Dataset

Dataset of statistics taken from nearly 70,000 Excel workbooks. Made in collaberation with University of Glasgow Software Service.

Workbooks data is split into five seperate files:

- `formula_complexity.csv`: For each workbook, finds distribution statistics for a vector of formula complexity scores, created by Vectofy, for each active cell in the workbook
- `input_complexity.csv`: Measures describing the complexity of input cells in each workbook 
- `logic_depth.csv`: Measures describing the longest line of logic in each workbook
- `model_size.csv`: Measures describing model size, including number of active cells, sheets, rows, columns, and file size on disk
- `output_complexity.csv`: Measures describing the complexity of output cells in each workbook
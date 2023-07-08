# 交互
## 读写Excel
readxl对于xls和xlsx都通用，可读可写，简单

readr主要读csv格式，可写Excel

openxlsx只能处理xlsx，可读可写，功能强大，依赖很少

xlsx依赖Java等。

对于简单的Excel表，使用readxl即可，Rstudio也默认这个包读取。对于xlsx格式，openxlsx更适用，因其可以写入Excel公式，且可以按照sheet来写入（写入列表，列表名映射为sheet名）

## 读word中的表格
docxtractr

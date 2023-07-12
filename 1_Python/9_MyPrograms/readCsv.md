# Reading CSV:
```
import os
Root_dir=os.path.dirname(os.path.dirname(os.path.abspath(__file__))))
data_folder=os.path.join(data_folder,"data")
file_path=os.path.join(data_folder,"file.csv")

from utilities.csvreader import CSVReader
my_reader=CSVReader(file_path).read_data()
```
---------------------------------------------------------------------

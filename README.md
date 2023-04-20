# Converters

Function: Convert point cloud files from .bin format to .pcd format.
How to use: 
```
pip install numpy
```
Run the program, enter the corresponding information according to the command prompt, and the output file is under the "pcd_files" path of the upper directory of the bin file.
> Note: The symbols in the input are symbols under the English input method, please pay attention to the order when inputting field names and data types.

Remark:
     If you do not know the relevant information such as bin point cloud file fields, this script is only for most bin files, including 3-7 fields and the first three fields are x, y, z coordinates.
     Files with 32 bytes and 64 bytes per field. If the bin file has 4 fields, the converted pcd point cloud file contains (x, y, z, i) coordinates + intensity 4 dimensions, and other data only retains (x, y, z) coordinates.

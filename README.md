# How to install hdf5 file in the ubuntu?
# hdf5_c_programming
# To Run hdf5 file in C Programming 

 h5cc  create_hdf5.c -o new_hdf5

#To run the program: 

 ./new_hdf5

if h5dump is not available then install sudo apt install hdf5-tools
# To see the h5dump file: 

 h5dump SDS.h5
```
HDF5 "SDS.h5" {
GROUP "/" {
   DATASET "IntArray" {
      DATATYPE  H5T_STD_I32LE
      DATASPACE  SIMPLE { ( 5, 6 ) / ( 5, 6 ) }
      DATA {
      (0,0): 0, 1, 2, 3, 4, 5,
      (1,0): 1, 2, 3, 4, 5, 6,
      (2,0): 2, 3, 4, 5, 6, 7,
      (3,0): 3, 4, 5, 6, 7, 8,
      (4,0): 4, 5, 6, 7, 8, 9
      }
   }
}
}
```

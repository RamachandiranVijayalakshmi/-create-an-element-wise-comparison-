## -create-an-element-wise-comparison-
## Sample code to check the element wise details 
```sh
x = np.array([72, 79, 85, 90, 150, -135, 120, -10, 60, 100])
y = np.array([72, 79, 85, 90, 150, -135, 120, -10, 60, 100.000001])
```
## Expected Output
```sh
Original numbers:
[  72   79   85   90  150 -135  120  -10   60  100]
[  72.         79.         85.         90.        150.       -135.
  120.        -10.         60.        100.000001]
Comparison - equal:
[ True  True  True  True  True  True  True  True  True False]
Comparison - equal within a tolerance:
True                       
```

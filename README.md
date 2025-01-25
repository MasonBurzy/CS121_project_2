# CS121-project-2

# CS

## Algorithm for sorting numbers

## main

```
produce and array of integers
print the array
create two temporary integers
test the swap function
run the sort function on the arrays
print the sorted array
```
## print values

```
void printValues(int*);
takes an int pointer representing the array
step through the array with a for loop
        print each number of the array
print a new line at the end
return viod
```

## swap

```
void swap(int* a, int* b);
takes two int pinter parameters
make a temporary integer called temp
copy the value of a to temp
copy the value of b to the value of a
copy temp to the value of b
```

## sort

```

void sort(int*);
use bubble sort on the array

constant MAX is max length of array
function sort (array):
    create integer variables i and j
    for i from zero to MAX - 1:
        for j from zero to MAX - 1:
            if array[j] > array[j+1]:
                swap array[j] with array[j+1]
                printArray(array)

# Program Design
## Structure Chart
![Chart](https://github.com/lukehami55/CSC-250---Programming-Assingment-1/blob/main/Structure%20Chart.png?raw=true)

## Data Storage in Main
``` cpp
int *id; //id memory
int *hits; //hits memory
int *timesHit; //times hit memory
int numItems; //size of the arrays
int input; //team id input
int index; //find index of parallel arrays based on input
```
## Function Design
``` cpp
//read data from txt file into arrays, return length of data
int readData(int *&id, int *&hits, int *&timesHit, int numItems);

//sort arrays using bubble sort
void sortArrays(int *&id, int *&hits, int *&timesHit, int numItems);

//returns user inputted search ID
int getSearchId(int input);

//binary search based on input and returns index
int binarySearch(int *id, int *hits, int *timesHit, int input, int numItems);

//print id hits, and times hit based on index
void printResults(int *id, int *hits, int *timesHit, int index);
```
## Time Estimates
|  | Estimated Time    | Actual Time    |
| :---:   | :---: | :---: |
| Dynamic Allocation | 30   | 40   |
| Total Time | 30   | 40   |

# Array-Challenge
Question : Have the function ArrayChallenge (arr) take the array of numbers stored in art and return the index at which the numbers stop increasing and begin decreasing or stop decreasing and begin increasing. For example: if arr is [1, 2, 4, 6, 4, 3, 1] then your program should return 3 because 6 is the last point in the array where the numbers were increasing and the next number begins a decreasing sequence. The array will contain at least 3 numbers and it may contains only a single sequence, increasing or decreasing. If there is only a single sequence in the array, then your program should return -1. Indexing should begin with 0.  Examples  Input: (-4,-2,9,10)  Output: -1 

Answer :

#include <iostream>	
#include <string>	
using namespace std;
int ArrayChallenge(int arr[], int arrlength){	
	int max, i, index;
	max = arr[0];
	for(i=0;i<5;i++){
		if(arr[i]>max){
			max = arr[i];
			index = i;
		}
	}
	cout <<  pos<<"\n";
	if(index == (arrlength-1)){
		return (-1);
	}
	else if(index == 0){
		return (-1);
	}
	else{
	return (pos);
}
}

int main(void){
	int A[] = {6,3,5,4,7};
	int arrLength = sizeof(A) / sizeof(*A);
	cout <<  arrLength<<"\n";
	cout << ArrayChallenge(A, arrLength);
	return 0;
}

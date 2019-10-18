# Sorting
## Aim:-
        To perform sorting of a rray
### Theory:-
             A Sorting Algorithm is used to rearrange a given array or list elements according to a comparison operator on the elements.                The comparison operator is used to decide the new order of element in the respective data structure.
#### Algorithm:-
                1) For Bubble Sort
                        void swap(int *xp, int *yp) 
                        int temp = *xp 
                        *xp = *yp 
                         *yp = temp
                        void bubbleSort(int arr[], int n) 
                         int i, j
                        for (i = 0; i < n-1; i++)
                           {        for (j = 0; j < n-i-1; j++)
	                         {if (arr[j] > arr[j+1]) 
                                  swap(&arr[j], &arr[j+1])
		                }
                            }
                        void printArray(int arr[], int size) 
                        int i
                        for (i=0; i < size; i++) 
                         printf("%d ", arr[i])
                        printf("\n") 
                        
                2)For Insertion Sort
                        void insertionSort(int arr[], int n) 
                        int i, key, j
                        for (i = 1; i < n; i++) { 
                         key = arr[i]
                        j = i - 1
                        while (j >= 0 && arr[j] > key) { 
                         arr[j + 1] = arr[j] 
                        j = j - 1 
                        } 
                         arr[j + 1] = key 
                        }
                        void printArray(int arr[], int n) 
                         int i 
                        for (i = 0; i < n; i++) 
                         printf("%d ", arr[i]) 
                          printf("\n")
                 3)For Selection Sort
                              void swap(int *xp, int *yp) 
                               int temp = *xp
                                *xp = *yp 
                                *yp = temp 
                                void selectionSort(int arr[], int n) 
                                int i, j, min_idx; 
                                 for (i = 0; i < n-1; i++) 
                                  { 
                                        min_idx = i 
                                        for (j = i+1; j < n; j++) 
                                        if (arr[j] < arr[min_idx]) 
                                        min_idx = j 
                                        swap(&arr[min_idx], &arr[i]) 
                                   } 
                                void printArray(int arr[], int size) 
                                  int i
                                  for (i=0; i < size; i++) 
                                 printf("%d ", arr[i]) 
                                printf("\n") 
   ##### Conclusion:-
                    From this program we learnt how to perform diferrent types of sorting techniques to arrange a particular array in                           ascending or descending order.

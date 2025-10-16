//WAP  to find all the elements that appears most frequently in the array.
#include <stdio.h>

int main() {
    int n, i, j, maxCount = 0, count;
    int arr[100], mostFrequent;

    printf("Enter number of elements: ");
    scanf("%d", &n);

    printf("Enter elements: ");
    for(i = 0; i < n; i++) {
        scanf("%d", &arr[i]);
    }

    // Find the most frequent element
    for(i = 0; i < n; i++) {
        count = 1;
        for(j = i + 1; j < n; j++) {
            if(arr[i] == arr[j])
                count++;
        }
        if(count > maxCount) {
            maxCount = count;
            mostFrequent = arr[i];
        }
    }

    printf("Most frequent element is %d, appearing %d times\n", mostFrequent, maxCount);

    return 0;
}

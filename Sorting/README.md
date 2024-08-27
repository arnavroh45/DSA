### Selection Sort
ismai hum poora array traverse karte hain and jo bhi min element milta hai usey present waale ke saath swap kardete hain
example
5 3 2 1 4 hai
toh ismai ek pointer 5 par rahega, aur hum poora array traverse karenge humein min 1 milega hum usey 5 ke saath swap kardenge, 
waapas same operation hoga bass iss bar hum replace 3 se karenge and so on...  

### Bubble Sort
ismai hum adjacenet elements ko compare karte hain, jo bada hai usey right mai daal dete, aise karte karte jab pehle iteration complete hogi, toh max element extreme right par hoga 
and next iteration mai second last element and so on...
example 
5 3 2 1 4
(5, 3) compare kara 5 ko right mai daal diya then (5, 2) ko compare kara 5 ko right mai, (5, 1) ko compare kara, 5 ko right mai and so on...

### Insertion Sort
We start with second element of the array as first element in the array is assumed to be sorted.
Compare second element with the first element and check if the second element is smaller then swap them.
Move to the third element and compare it with the second element, then the first element and swap as necessary to put it in the correct position among the first three elements.
Continue this process, comparing each element with the ones before it and swapping as needed to place it in the correct position among the sorted elements.
Repeat until the entire array is sorted.

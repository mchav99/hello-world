# hello-world
Introduction to Github

int[] arr = { 1, 5, -39, 23, 84};

for(int firstUnorderedIndex = 1; firstUnorderedIndex < arr.length; firstUnorderedIndex++){
  int newElement = arr[firstUnorderedIndex];
  int i;
  for(i = 1; i > 0 && arr[i-1] > newElement; i--){
    arr[i] = arr[i-1];
    }
   arr[i] = newElement;
  }
  
  
    

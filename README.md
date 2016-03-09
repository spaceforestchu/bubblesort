# bubblesort

      function bubble(arr){
          var i, temp;
          var j;
          for( j = 0; j < arr.length;j ++){
              for( i = 0; i < arr.length-1; i++){
              if(arr[i] > arr[i+1]){
                  temp = arr[i];
                  arr[i] = arr[i+1];
                  arr[i+1] = temp;
              }
            }
          }
         return arr;
      }
      
      bubble([5,3,7,66,33,8,10,4,2,56,55555]);

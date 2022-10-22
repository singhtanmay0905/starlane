# starlane
great
best
cool
public class LinearSearch {

    int search(int arr[], int n) {
        
        int len = arr.length;
        for(int i = 0; i < len; i++) {
            
            if(arr[i] == n)
                return i;
        }
        return -1;
    }

    public static void main(String[] args) {

        int arr[] = {5, 3, 6, 2, 1, 4};

        int n = 2;// Element to be searched.

        System.out.print("The Array elements are : ");

        for (int i=0; i<arr.length; i++)
            System.out.print(

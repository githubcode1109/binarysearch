# binarysearch
public class Main{
    public static void main(String[]args){
        int arr[]={10,20,21,25,32,35};
        int key=32;
        int low=0;
        int high=arr.length-1;
        int mid=0;
        while(low<=high){
            mid=(low+high)/2;
        if(arr[mid]==key){
            System.out.println(mid);
            break;
        }
        else if(arr[mid]<key){
            low=mid+1;
        }
        else{
            high=mid-1;
        }
    }
  }
}

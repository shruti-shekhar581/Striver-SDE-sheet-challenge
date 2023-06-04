#merge two sorted arrays











 public static int[] ninjaAndSortedArrays(int nums1[], int nums2[], int m, int n) {
 Write your code here.
        int pos = 0;
for(int i=m;i<m+n;i++){
nums1[i] = nums2[pos];
pos++;
}
Arrays.sort(nums1);
return nums1;
    }
}



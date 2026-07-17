# leetcode-java-solutions
This repository contains my solutions to various LeetCode problems, written in Java.   Each file corresponds to a specific problem, with clean and beginner-friendly code.   Problems are organized by difficulty (Easy, Medium, Hard) for easy navigation.  
class Solution {
    public int[] getConcatenation(int[] nums) {
        int a=nums.length;
        int b=a*2;
        int ans[]=new int[b];
        for(int i=0;i<a;i++){
            ans[i]=nums[i];
            ans[i+a]=nums[i];
        }
        return ans;
    }
}

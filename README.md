## Symmetric Tree
Given the root of a binary tree, check whether it is a mirror of itself
(i.e., symmetric around its center).


Important notice:                                    C
    A.val == B.val                            A             B
    A.left should == B.right             left  right    left  right
    A.right should == B.left

Example 1:
Input: root = [1,2,2,3,4,4,3]
Output: true

Example 2:
Input: root = [1,2,2,null,3,null,3]
Output: false

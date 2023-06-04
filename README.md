# Strivers-SDE-Sheet-Challenge


Finding duplicate num --linked list cycle method
slow = nums[0];fast = nums[0];
  do {
    slow = nums[slow];
    fast = nums[nums[fast]];
  } while (slow != fast);
  fast = nums[0];
  while (slow != fast) {
    slow = nums[slow];
    fast = nums[fast];
  }
  return slow;
![image](https://github.com/Harshitha122/Strivers-SDE-Sheet-Challenge/assets/71165978/c9cc2af5-31e2-457c-a4c7-5f472e9fa8d1)

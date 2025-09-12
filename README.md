# Binary-Search-
Binary Search Advanced DSA concepts


Binary search is a highly efficient algorithm used to find the position of a target value within a sorted array.
Instead of checking each element one by one (like linear search),
it divides the search space in half with each step,
drastically reducing the number of comparisons.
 
🧠 How It Works
- Start with the entire array.
- Find the middle element.
- Compare the middle element with the target:
- If it matches, you're done.
- If the target is smaller, repeat the search on the left half.
- If the target is larger, repeat on the right half.
- Continue until the target is found or the search space is empty.
⚙️ Conditions for Binary Search
- The array must be sorted.
- You must be able to access elements by index (i.e., random access).
⏱️ Time Complexity
- Best case: O(1) (target is at the middle)
- Average/Worst case: O(log n)

🚀 Day 5 – Single Number, Binary Search, Linear Search
✅ Problems Solved:
• Single Number – LeetCode
• Binary Search – LeetCode
• Linear Search – Practice

🧠 Revise your logic

🔑 Single Number:
Leverage the power of XOR:
• a ^ a = 0, a ^ 0 = a
XOR all elements – duplicates cancel out, and you're left with the unique number in O(n) time, O(1) space.

🔑 Binary Search:
Classic divide-and-conquer approach. Use two pointers (low, high) to repeatedly halve the search space.
Efficient for sorted arrays, with time complexity O(log n).

🔑 Linear Search:
Simple and intuitive – loop through the array and compare each element.
Best for unsorted or small datasets. Time complexity O(n).

📌 Learnings:
• Mastered the use of bitwise XOR for unique element problems.
• Practiced applying binary search logic with proper mid-point calculation.
• Compared binary vs linear search to understand when each is most effective.

💡 Tip of the Day:
When dealing with sorted arrays, always ask: "Can I use binary search?" — it's a game changer for performance.

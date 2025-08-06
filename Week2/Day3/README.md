🚀 Day 10 – Recursion Practice: Array Sum & Power of 4
✅ Problems Solved:
• Sum of All Numbers in an Array (using Recursion)
• Power of 4 – LeetCode

🧠 Revise your logic

🔑 Sum of All Numbers in an Array:
• Solved using recursion by reducing the problem size:
 sum(arr, n) = arr[n-1] + sum(arr, n-1)
• Base case: when the array is empty or has one element
• Practiced breaking down arrays recursively and building up the result

🔑 Power of 4:
• Checked if a number is a power of 4 using:
 1. Loop / Recursion
 2. Bitwise & modulus logic
• Conditions:
 - num > 0
 - num & (num - 1) == 0 → check if it's a power of 2
 - num % 3 == 1 → ensures it's a power of 4, not just power of 2
• Time: O(log n) if done recursively or iteratively

📌 Learnings:
• Strengthened recursion by applying it to arrays
• Learned to recognize patterns in number powers
• Got more confident with base cases and recursive reductions

💡 Tip of the Day:
Not all problems need loops — sometimes thinking recursively can lead to cleaner, more elegant solutions!

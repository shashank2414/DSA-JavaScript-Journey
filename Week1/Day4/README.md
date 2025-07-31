🚀 Day 4 – Move Zeroes, Max Consecutive Ones, Missing Number
✅ Problems Solved:
• Move Zeroes – LeetCode
• Max Consecutive Ones – LeetCode
• Missing Number – LeetCode

🧠 Revise your logic

🔑 Move Zeroes:
Use two pointers — one to iterate and one to track the position of non-zero elements.
After shifting all non-zero values, fill the rest with zeroes.

🔑 Max Consecutive Ones:
Simple counter-based approach. Reset counter at each zero, and track the maximum streak of 1s.

🔑 Missing Number:
Use the mathematical formula for the sum of first n natural numbers:
sum = n*(n+1)/2 and subtract the sum of actual array elements.
Alternative: XOR trick — XOR all indices and values to cancel out and get the missing number.

📌 Learnings:
• Reinforced understanding of in-place updates and value shifting in arrays.
• Learned the use of XOR and Math formulas for efficient missing number detection.
• Practiced identifying optimal solutions with O(n) time and O(1) space.

💡 Tip of the Day:
Use mathematical intuition or XOR when you're looking for a single missing element in a range — it's faster and cleaner than sorting or using extra space.

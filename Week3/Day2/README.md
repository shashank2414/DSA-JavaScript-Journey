🚀 Day 16 – String Problems: Jewels & Balanced Splits
✅ Problems Solved:
• Jewels and Stones – LeetCode
• Split a String in Balanced Strings – LeetCode

🧠 Revise your logic

🔑 Jewels and Stones:
• Given two strings: jewels (types of jewels) and stones (stones you have)
• Count how many stones are also jewels
• Approaches:
 ✔ Use a set for jewels for O(1) lookup and loop through stones
 ✔ Complexity: O(n + m)

🔑 Split a String in Balanced Strings:
• A string is balanced if it contains an equal number of L and R
• Traverse the string, maintain a balance counter:
 - Increment for L, decrement for R
 - Whenever balance = 0, it means a balanced substring is found
• Complexity: O(n), single pass

📌 Learnings:
• Practiced hash-based lookup (sets) for fast membership testing
• Understood how to use counters for balance-related problems
• Improved skills in single-pass string processing

💡 Tip of the Day:
When a problem asks for balanced partitions, think of using a counter instead of substring operations — it’s cleaner and faster.

🚀 Day 19 – String Problems: Palindrome & Isomorphic Mapping
✅ Problems Solved:
• Valid Palindrome – LeetCode
• Isomorphic Strings – LeetCode

🧠 Revise your logic

🔑 Valid Palindrome:
• Normalize by lowercasing and skipping non-alphanumeric characters
• Use two pointers from both ends; move inward while comparing
• Complexity: O(n) time, O(1) extra space (two-pointer approach)

🔑 Isomorphic Strings:
• Maintain two maps: s → t and t → s to ensure one-to-one mapping
• As you scan, verify existing mappings; if conflict, return false
• Complexity: O(n) time, O(k) space (k = unique chars)

📌 Learnings:
• Practiced string normalization and clean two-pointer patterns
• Reinforced bijection (one-to-one) mapping for pattern-matching problems
• Noted how early exits save time on mismatches

💡 Tip of the Day:
For isomorphic checks, never rely on a single map—always verify both directions to prevent many-to-one collisions.

🔥 Day 20 of My 90 Days DSA with JavaScript Challenge! 🔥

Today was all about solving one of the most interesting string problems: Group Anagrams – and I explored two different approaches:
✅ Using Sorted Key
✅ Using Hashed Key (Character Count Signature)

✅ What I Solved Today

Problem: Group Anagrams

Approach 1: Sort each word alphabetically and use it as a key in a map.

Approach 2: Use character frequency as a unique signature (hashed key) for grouping.

🧠 What I Learned

Sorting strings can serve as a unique identifier for anagrams.

Hashing with character counts is more efficient because it avoids sorting overhead.

Maps in JavaScript are extremely useful for grouping operations.

🔁 Revise Your Topic

Map vs Object in JavaScript (Why Map is better for key-value grouping).

String manipulation techniques (sorting, splitting, joining).

Complexity Analysis:

Sorting approach → O(n * k log k) (k = length of string).

Hashing approach → O(n * k).

💡 Tip of the Day

If you want better performance for anagram grouping:

Avoid sorting when possible.

Go for hashed signature approach (frequency map → stringified as a key).

⚡ Key Takeaways

There’s always more than one way to solve a problem – choose the one that balances readability and efficiency.

Hashing can turn a time-consuming task into a lightning-fast one!

🔥 Tomorrow’s Goal: Dive deeper into string hashing problems and practice some hashmap-based challenges!

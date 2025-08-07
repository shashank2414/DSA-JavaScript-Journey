🚀 Day 11 – Power of X (Recursive Approaches)
✅ Problems Solved:
• Power of X to the Power N – Stack Height O(n)
• Power of X to the Power N – Stack Height O(log n)

🧠 Revise your logic

🔑 Power (Stack Height O(n))
• Basic recursive approach:
 power(x, n) = x * power(x, n-1)
• Base case: power(x, 0) = 1
• Stack height = O(n), straightforward but not optimal for large n

🔑 Optimized Power (Stack Height O(log n))
• Used divide-and-conquer strategy (Exponentiation by Squaring):

js
Copy
Edit
if (n % 2 === 0)  
 power(x, n) = power(x*x, n/2)  
else  
 power(x, n) = x * power(x*x, (n-1)/2)
• Stack height = O(log n)
• More efficient, especially for large values of n

📌 Learnings:
• Understood how recursion depth can impact performance
• Learned how mathematical optimization (squaring) reduces call stack size
• Practiced tracing recursion using dry runs and breaking down powers

💡 Tip of the Day:
Always analyze if the recursion depth can be optimized — O(log n) solutions not only save space but also improve runtime significantly.


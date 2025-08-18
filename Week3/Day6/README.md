🔥 Day 20 of My 90 Days DSA with JavaScript Challenge! 💻✨
Today, I tackled an interesting problem: Find the frequency of vowels and consonants in a string. Sounds simple, right? But the devil is always in the details!

✅ What I Learned Today

How to efficiently iterate over a string and classify characters.

The power of two arrays and mapping to keep track of counts separately for vowels and consonants.

How to ignore non-alphabetic characters so that punctuation or spaces don’t mess with results.

The importance of time complexity optimization – single pass solution instead of multiple checks!

🔍 How I Solved It

Created two arrays: one for vowels ['a', 'e', 'i', 'o', 'u'] and another for consonants.

Used a map (object) to store counts dynamically.

Converted the string to lowercase to handle case insensitivity.

Ignored any character that’s not a-z.

Example approach:

let vowels = ['a', 'e', 'i', 'o', 'u'];
let map = { vowels: 0, consonants: 0 };

for (let char of str.toLowerCase()) {
    if (/[a-z]/.test(char)) {
        if (vowels.includes(char)) map.vowels++;
        else map.consonants++;
    }
}

🧠 Key Learning

Arrays + mapping = super efficient frequency tracking.

Learned to handle edge cases (spaces, digits, punctuation).

Practiced writing clean, readable code instead of spaghetti logic.

🔄 Revise Your Topics

String methods: toLowerCase(), includes(), test() with regex.

Data structures: arrays vs maps for counting.

Conditionals: nesting vs clear separation for readability.

💡 Tip of the Day

Always preprocess your string (like trimming, converting case, filtering unwanted characters) before applying logic. This avoids so many bugs later!

🚀 Next Goal: Move to more advanced string problems involving pattern matching and hashing.

MRU-LRU Cache Visualizer 🚀
Overview 📝
The MRU-LRU Cache simulator  is an interactive web-based tool that demonstrates how Most Recently Used (MRU) and Least Recently Used (LRU) cache policies work. This visual simulator provides hands-on experience with cache operations.
Features ✨
✅ Set a custom cache size dynamically.
✅ Add elements using the Put operation.
✅ Retrieve elements using the Get operation.
✅ Highlights MRU (Most Recently Used) items in 🟩 green.
✅ Highlights LRU (Least Recently Used) items in 🔴 red.
✅ Automatically removes the LRU element when the cache is full.
✅ Simple, clean UI with real-time cache updates.
How It Works 🔍
Set Cache Size – Define the maximum number of elements the cache can store.

Put Operation – Adds an element to the cache. If it exists, it moves to the MRU position. If the cache is full, the LRU element is removed.

Get Operation – Retrieves an element from the cache. If found, it moves to the MRU position. Otherwise, it results in a cache miss.
Project Structure 📂
📁 MRU-LRU-Cache-Visualizer  
│── 📄 index.html     # Main HTML file  
│── 🎨 style.css      # Stylesheet for UI  
│── 🖥️ script.js      # JavaScript logic for cache operations  
│── 📜 README.md      # Project documentation  

Data Structure Used: Map
The cache is implemented using JavaScript’s Map, which efficiently handles cache operations.

Why Use Map?
✔ Preserves insertion order, making it easy to track LRU and MRU elements.
✔ Fast operations: Insert, delete, and access operations are O(1) on average.
✔ Automatic eviction: The first key in the Map represents the LRU element, and the last key represents the MRU element.

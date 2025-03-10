# APP2
A codified version of google translate !!

---
 

---

# 🚀 TOEICKilla - Vocabulary Manager 📖  

TOEICKilla is a **vocabulary management application** built with **Python** and **PyQt5**. It uses a **Binary Search Tree (BST) 🌳** to efficiently store and retrieve word translations, allowing users to:  

✅ **Search** for a translation 🔎  
✅ **Add** new words ➕  
✅ **Modify** existing translations ✏️  
✅ **Delete** words from the vocabulary ❌  

---

## 📂 Project Structure  

📜 `main.py` - Main script to launch the application  
🌳 `bst.py` - Binary Search Tree implementation  
📄 `500_words.txt` - Stores vocabulary (word-translation pairs)  
🎨 `ui.py` - Handles the PyQt5 graphical interface  

---

## ⚙️ Technical Choices  

TOEICKilla relies on the following concepts for efficiency and scalability:  

- **Binary Search Tree (BST) 🌳** – Provides **O(log n)** search, insertion, and deletion.  
- **PyQt5 🖥️** – Ensures an intuitive and interactive user interface.  
- **File-based storage 📂** – Stores vocabulary persistently in a `.txt` file for simplicity.  

---

## 🌳 Binary Search Tree (BST) 🔍  

TOEICKilla uses a **Binary Search Tree (BST)** to store and retrieve words efficiently. In a BST:  

- Each node contains a **word** and its **translation**.  
- Words are stored in **sorted order**, allowing **fast searching** (O(log n) time complexity).  
- Searching follows a **left (smaller) / right (greater) rule**, ensuring efficient traversal.  

This makes the dictionary **scalable** and **optimized** for large datasets! ⚡  

---

## ⚠️ Difficulties  

While developing TOEICKilla, we faced several challenges:  

- 📝 **Saving words in the file** – Ensuring data is stored correctly and persistently.  
- 🌳 **Understanding Binary Tree** – Implementing and optimizing BST for efficient searches.  
- 🔗 **Linking the interface with our code** – Connecting the PyQt5 UI to the backend logic.  

---

## ✨ Features  

🔹 **Fast Search**: Uses a BST to quickly find word translations ⚡  
🔹 **User-Friendly UI**: Built with PyQt5 for an interactive experience 🎨  
🔹 **Persistent Storage**: Saves vocabulary in a `.txt` file 📂  
🔹 **Modify & Delete Words**: Allows updating or removing words as needed 🔄  

---

## 🛠 Installation  

### Prerequisites  

Make sure you have **Python 3** installed, then install the required dependencies:  

```sh
pip install PyQt5
```  

---

## 🚀 Usage  

1️⃣ Run the application:  

```sh
python main.py
```  

2️⃣ Use the buttons to:  

- 🔎 **Search** for a word  
- ➕ **Add** a new word  
- ✏️ **Modify** an existing word  
- ❌ **Delete** a word  

---

## 🔮 Future Improvements  

✨ Add a **graphical list view** for stored words 🗂  
✨ Implement **CSV export/import** 📑  
✨ Enhance UI with **better styles and animations** 🎨  
✨ **Translate sentences** instead of single words  
✨ Add **voice pronunciation** for words 🔊  
✨ Handle **homonyms** by providing multiple meanings  
✨ Load a translated word file to **insert multiple words at once**  

---

## 🎉 Thank You!  

Thank you for checking out **TOEICKilla**! 🚀 We appreciate your interest and support.  
If you have any feedback or suggestions, feel free to contribute or reach out! 💡  

---

This README is **complete and ready to go**! Let me know if you need any tweaks. 🚀🔥











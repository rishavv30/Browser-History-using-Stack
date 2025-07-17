# Browser-History-using-Stack (Java)


This project is a simple **browser history system** implemented in **Java**, using two **Stacks** to simulate back and forward navigation — just like in real browsers (Chrome, Firefox, etc.).

---

## 📌 Features

- ✅ Visit a new web page  
- 🔙 Go back to the previous page  
- ⏩ Move forward to the next page (if available)  
- 📍 View the current page  
- 🎮 Interactive, user-friendly console interface  

---

## 🧠 How It Works

The program uses **two stacks**:
- `backPages` → stores visited pages
- `forwardPages` → stores forward history

When you:
- **Visit a new page** → current page is pushed to `backPages`, forward history is cleared
- **Go back** → current page is pushed to `forwardPages`, top of `backPages` becomes current
- **Go forward** → current page is pushed to `backPages`, top of `forwardPages` becomes current

---


SAMPLE OUTPUT --> 
Choose an option:
1. Visit a new page
2. Go back
3. Go forward
4. Show current page
5. Exit
Your choice: 1
Enter URL to visit: google.com
📄 You are now visiting: google.com

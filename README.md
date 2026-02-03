# JavaScript Array Methods Practice

A collection of JavaScript exercises demonstrating practical applications of
modern array methods including `map()`, `filter()`, `toSorted()`, and
`reduce()`. This project showcases data manipulation techniques commonly used in
real-world development scenarios.

## 🚀 Demo

[Live Demo](https://helen-akateva.github.io/javascript-array-methods-practice/)

## 📋 Description

This project contains four practical tasks that demonstrate the power and
versatility of JavaScript array methods for data transformation and analysis:

- **Task 1**: Extract user names from an array of user objects using `map()`
- **Task 2**: Filter users by friend name using `filter()` and `includes()`
- **Task 3**: Sort users by friend count in descending order using `toSorted()`
- **Task 4**: Calculate total balance by gender using `filter()` and `reduce()`

Each task works with user data objects containing properties like name, email,
balance, friends, and gender, simulating real-world data processing scenarios.

## 🛠️ Technologies

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

### Tech Stack:

- **JavaScript (ES6+)**: Arrow functions, array methods, destructuring
- **HTML5**: Basic structure for script execution
- **Array Methods**: `map()`, `filter()`, `toSorted()`, `reduce()`, `includes()`

## ✨ Functionality

### Task 1: Get User Names

```javascript
getUserNames(users); // Returns array of user names
```

Uses `map()` to transform an array of user objects into an array of names.

### Task 2: Get Users with Friend

```javascript
getUsersWithFriend(users, friendName); // Returns users who have specified friend
```

Combines `filter()` and `includes()` to find users with a specific friend.

### Task 3: Sort by Friend Count

```javascript
sortByDescendingFriendCount(users); // Returns users sorted by friend count (desc)
```

Uses `toSorted()` to create a new sorted array without mutating the original.

### Task 4: Get Total Balance by Gender

```javascript
getTotalBalanceByGender(users, gender); // Returns sum of balances for specified gender
```

Chains `filter()` and `reduce()` to calculate aggregated financial data.

## 📁 Project Structure

```
javascript-array-methods-practice/
├── js/
│   ├── task-1.js    # Map method example
│   ├── task-2.js    # Filter method example
│   ├── task-3.js    # toSorted method example
│   └── task-4.js    # Reduce method example
├── index.html       # Entry point
└── README.md        # Documentation
```

## 🚦 Getting Started

1. Clone the repository:

```bash
git clone https://github.com/helen-akateva/javascript-array-methods-practice.git
```

2. Open `index.html` in your browser to see console output

3. Open browser DevTools console (F12) to view results

## 💡 Key Concepts Demonstrated

- **Immutability**: Using `toSorted()` instead of `sort()` to avoid mutating
  original arrays
- **Function Composition**: Chaining array methods for complex data
  transformations
- **Arrow Functions**: Concise function syntax for callbacks
- **Array Destructuring**: Modern JavaScript techniques for cleaner code
- **Data Aggregation**: Using `reduce()` for calculating totals and summaries

## 📚 Learning Outcomes

This project helps understand:

- How to transform data with `map()`
- How to filter data with `filter()`
- How to sort data immutably with `toSorted()`
- How to aggregate data with `reduce()`
- Working with complex object structures
- Functional programming principles in JavaScript

## 👤 Author

**Olena Akatieva**

- LinkedIn:
  [linkedin.com/in/olena-akatieva](https://linkedin.com/in/olena-akatieva)
- GitHub: [@helen-akateva](https://github.com/helen-akateva)

---

⭐ If you find this project helpful, please give it a star!

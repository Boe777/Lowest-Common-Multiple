
# **Least Common Multiple (LCM) Calculation**
This repository contains Python solutions to calculate the **Least Common Multiple (LCM)** of two positive integers. LCM is the smallest positive integer that is divisible by both numbers.

---

## **Table of Contents**
1. [Problem Description](#problem-description)  
2. [Solutions Provided](#solutions-provided)  
   - Solution 1: Manual Calculation (Using GCD)  
   - Solution 2: Using Python's `math` Library  
3. [Usage Instructions](#usage-instructions)  
4. [Examples](#examples)  
5. [Requirements](#requirements)  
6. [How to Run](#how-to-run)  
7. [Contributing](#contributing)  
8. [License](#license)  

---

## **Problem Description**
Given two positive integers, the goal is to compute their **Least Common Multiple (LCM)**. The LCM of two integers `a` and `b` is the smallest positive integer that is divisible by both.

### Example:
**Input**:  
```
a = 12  
b = 15  
```
**Output**:  
```
The Least Common Multiple of 12 and 15 is 60.
```

---

## **Solutions Provided**

### **Solution 1: Manual Calculation (Using GCD)**
This solution calculates the **LCM** using the relationship between the **Greatest Common Divisor (GCD)** and the LCM.

The formula is:  
![LCM Formula](https://latex.codecogs.com/png.latex?\text{LCM}(a,%20b)%20=%20\frac{|a%20\times%20b|}{\text{GCD}(a,%20b)})




---

### **Solution 2: Using Python's `math` Library**
This solution leverages the built-in **`math` library** in Python 3.9 or higher. The library provides direct functions for calculating the GCD and LCM.



---

## **Usage Instructions**

### **Requirements**
- Python 3.6+ (for Solution 1)  
- Python 3.9+ (for Solution 2 using `math.lcm`)  

### **How to Run**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/least-common-multiple.git
   cd least-common-multiple
   ```

2. Run either solution:

- **Solution 1 (Manual Calculation):**
   ```bash
   python solution1_manual.py
   ```

- **Solution 2 (Using `math` Library):**
   ```bash
   python solution2_math_lib.py
   ```

3. Input the two positive integers when prompted.

---

## **Examples**

### **Running Solution 1**
**Input**:  
```
Enter the first number: 12  
Enter the second number: 15  
```

**Output**:  
```
The Least Common Multiple of 12 and 15 is 60
```

---

### **Running Solution 2**
**Input**:  
```
Enter the first number: 8  
Enter the second number: 20  
```

**Output**:  
```
The Least Common Multiple of 8 and 20 is 40
```

---

## **Contributing**
Contributions are welcome! Follow these steps to contribute:  
1. Fork the repository.  
2. Create a new branch for your changes:  
   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes:  
   ```bash
   git commit -m "Add a meaningful commit message"
   ```
4. Push the changes to your branch:  
   ```bash
   git push origin feature-branch
   ```
5. Open a Pull Request.

---

## **License**
This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it as needed.

---

### **Repository Structure**
```
lowest-common-multiple/
│
├── Lowest_Common_Multiple.ipynb
├── README.md               
└── LICENSE                 
```

---

## **Contact**
For any questions or suggestions, please open an issue or contact me via email.

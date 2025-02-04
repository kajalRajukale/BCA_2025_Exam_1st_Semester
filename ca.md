# 01. Number System and Digital Codes

**Binary Number System**: (0, 1)  
**Decimal Number System**: (0, 1, 2, 3, 4, 5, 6, 7, 8, 9)  
**Octal Number System**: (0, 1, 2, 3, 4, 5, 6, 7)  
**Hexadecimal Number System**: (0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F)  

---

## Binary to Decimal Conversion

### 1. 

$$ (110101)_2 = (?)_{10} $$

**Steps**:  
$$ = 1 \times 2^5 + 1 \times 2^4 + 0 \times 2^3 + 1 \times 2^2 + 0 \times 2^1 + 1 \times 2^0 $$ 
$$ = 32 + 16 + 0 + 4 + 0 + 1 $$ 
$$ = 53 $$

---

### 2.

$$ (11100111)_2 = (?)_{10} $$

**Steps**:  
$$ = 1 \times 2^7 + 1 \times 2^6 + 1 \times 2^5 + 0 \times 2^4 + 0 \times 2^3 + 1 \times 2^2 + 1 \times 2^1 + 1 \times 2^0 $$ 
$$ = 128 + 64 + 32 + 0 + 0 + 4 + 2 + 1 $$ 
$$ = 231 $$

---

### 3. 

$$ 101.111_2 = (?)_{10} $$

**Steps**:  
$$ = 1 \times 2^2 + 0 \times 2^1 + 1 \times 2^0 + 1 \times 2^{-1} + 1 \times 2^{-2} + 1 \times 2^{-3} $$ 
$$ = 4 + 0 + 1 + 0.5 + 0.25 + 0.125 $$ 
$$ = 5 + 0.875 $$ 
$$ = 5.875$$

# 02.
### 2. \( (1111.101)_2 = (?)_{10} \)

**Steps**:  
$$
= 1 \times 2^3 + 1 \times 2^2 + 1 \times 2^1 + 1 \times 2^0 + 1 \times 2^{-1} + 0 \times 2^{-2} + 1 \times 2^{-3}
$$ 
$$
= 8 + 4 + 2 + 1 + 0.5 + 0 + 0.125
$$ 
$$
= 15 + 0.625
$$ 
$$
= 15.625
$$

---

### 3. \( (10110.001)_2 = (?)_{10} \)

**Steps**:  
$$
= 1 \times 2^4 + 0 \times 2^3 + 1 \times 2^2 + 1 \times 2^1 + 0 \times 2^0 + 0 \times 2^{-1} + 0 \times 2^{-2} + 1 \times 2^{-3}
$$ 
$$
= 16 + 0 + 4 + 2 + 0 + 0 + 0 + 0.125
$$ 
$$
= 22 + 0.125
$$ 
$$
= 22.125
$$

---

## Decimal to Binary Conversion

### 1. \( (145)_{10} = (?)_2 \)

**Steps**:  

| Division | Quotient | Remainder |  
|----------|----------|-----------|  
| \( 145 \div 2 \) | \( 72 \) | \( 1 \) |  
| \( 72 \div 2 \)  | \( 36 \) | \( 0 \) |  
| \( 36 \div 2 \)  | \( 18 \) | \( 0 \) |  
| \( 18 \div 2 \)  | \( 9 \)  | \( 0 \) |  
| \( 9 \div 2 \)   | \( 4 \)  | \( 1 \) |  
| \( 4 \div 2 \)   | \( 2 \)  | \( 0 \) |  
| \( 2 \div 2 \)   | \( 1 \)  | \( 0 \) |  
| \( 1 \div 2 \)   | \( 0 \)  | \( 1 \) |  


$$
(145)_{10} = (10010001)_2
$$ 
$$
= 128 + 16 + 1
$$ 
$$
= 145
$$




# 03

### 2. \( (453)_{10} = (?)_2 \)

**Steps**:  

| Division | Quotient | Remainder |  
|----------|----------|-----------|  
| \( 453 \div 2 \) | \( 226 \) | \( 1 \) |  
| \( 226 \div 2 \) | \( 113 \) | \( 0 \) |  
| \( 113 \div 2 \) | \( 56 \)  | \( 1 \) |  
| \( 56 \div 2 \)  | \( 28 \)  | \( 0 \) |  
| \( 28 \div 2 \)  | \( 14 \)  | \( 0 \) |  
| \( 14 \div 2 \)  | \( 7 \)   | \( 0 \) |  
| \( 7 \div 2 \)   | \( 3 \)   | \( 1 \) |  
| \( 3 \div 2 \)   | \( 1 \)   | \( 1 \) |  
| \( 1 \div 2 \)   | \( 0 \)   | \( 1 \) |  

**Binary Representation**:  
$$
(453)_{10} = (111000101)_2
$$ 
$$
= 256 + 128 + 64 + 0 + 0 + 4 + 0 + 1
$$ 
$$
= 453
$$

---

### 3. \( (90.45)_{10} = (?)_2 \)

**Steps**:  

#### Integer Part:
| Division | Quotient | Remainder |  
|----------|----------|-----------|  
| \( 90 \div 2 \)  | \( 45 \) | \( 0 \) |  
| \( 45 \div 2 \)  | \( 22 \) | \( 1 \) |  
| \( 22 \div 2 \)  | \( 11 \) | \( 0 \) |  
| \( 11 \div 2 \)  | \( 5 \)  | \( 1 \) |  
| \( 5 \div 2 \)   | \( 2 \)  | \( 1 \) |  
| \( 2 \div 2 \)   | \( 1 \)  | \( 0 \) |  
| \( 1 \div 2 \)   | \( 0 \)  | \( 1 \) |  

#### Fractional Part:
| Multiplication | Carry | Fractional Part |  
|----------------|-------|-----------------|  
| \( 0.45 \times 2 \) | \( 0 \) | \( 0.90 \) |  
| \( 0.90 \times 2 \) | \( 1 \) | \( 0.80 \) |  
| \( 0.80 \times 2 \) | \( 1 \) | \( 0.60 \) |  
| \( 0.60 \times 2 \) | \( 1 \) | \( 0.20 \) |  
| \( 0.20 \times 2 \) | \( 0 \) | \( 0.40 \) |  
| \( 0.40 \times 2 \) | \( 0 \) | \( 0.80 \) |  

**Binary Representation**:  
$$
(90.45)_{10} = (1011010.011100)_2
$$


# 04
### 4. \( (97.60)_{10} = (?)_2 \)

**Steps**:  

#### Integer Part:
| Division | Quotient | Remainder |  
|----------|----------|-----------|  
| \( 97 \div 2 \)  | \( 48 \) | \( 1 \) |  
| \( 48 \div 2 \)  | \( 24 \) | \( 0 \) |  
| \( 24 \div 2 \)  | \( 12 \) | \( 0 \) |  
| \( 12 \div 2 \)  | \( 6 \)  | \( 0 \) |  
| \( 6 \div 2 \)   | \( 3 \)  | \( 0 \) |  
| \( 3 \div 2 \)   | \( 1 \)  | \( 1 \) |  
| \( 1 \div 2 \)   | \( 0 \)  | \( 1 \) |  

#### Fractional Part:
| Multiplication | Carry | Fractional Part |  
|----------------|-------|-----------------|  
| \( 0.60 \times 2 \) | \( 1 \) | \( 0.20 \) |  
| \( 0.20 \times 2 \) | \( 0 \) | \( 0.40 \) |  
| \( 0.40 \times 2 \) | \( 0 \) | \( 0.80 \) |  
| \( 0.80 \times 2 \) | \( 1 \) | \( 0.60 \) |  

**Binary Representation**:  
$$
(97.60)_{10} = (1100001.1001)_2
$$

---

### 5. Decimal to Hexadecimal Conversion

#### 1. \( (464)_{10} = (?)_{16} \)

**Steps**:  

| Division | Quotient | Remainder |  
|----------|----------|-----------|  
| \( 464 \div 16 \) | \( 29 \)  | \( 0 \) |  
| \( 29 \div 16 \)  | \( 1 \)   | \( 13 \) (D) |  
| \( 1 \div 16 \)   | \( 0 \)   | \( 1 \)  |  

**Hexadecimal Representation**:  
$$
(464)_{10} = (1D0)_{16}
$$

---

#### 2. \( (88)_{10} = (?)_{16} \)

**Steps**:  

| Division | Quotient | Remainder |  
|----------|----------|-----------|  
| $$ 88 \div 16 $$ | \( 5 \) | \( 8 \) |  
| \( 5 \div 16 \)  | \( 0 \) | \( 5 \) |  

**Hexadecimal Representation**:  
$$(88)_{10} = (58)_{16}$$

# 05
### 3. \( (1712)_{10} = (?)_{16} \)

**Steps**:  

| Division | Quotient | Remainder |  
|----------|----------|-----------|  
| \( 1712 \div 16 \) | \( 107 \) | \( 0 \) |  
| \( 107 \div 16 \)  | \( 6 \)  | \( 11 \) (B) |  
| \( 6 \div 16 \)    | \( 0 \)  | \( 6 \)  |  

**Hexadecimal Representation**:  
$
(1712)_{10} = (6B0)_{16}
$

---

### 4. \( (46.32)_{10} = (?)_{16} \)

**Steps**:  

#### Integer Part:
| Division | Quotient | Remainder |  
|----------|----------|-----------|  
| \( 46 \div 16 \) | \( 2 \) | \( 14 \) (E) |  
| \( 2 \div 16 \)  | \( 0 \) | \( 2 \) |  

#### Fractional Part:
| Multiplication | Carry | Fractional Part |  
|----------------|-------|-----------------|  
| \( 0.32 \times 16 \) | \( 5 \) | \( 0.12 \) |  
| \( 0.12 \times 16 \) | \( 1 \) | \( 0.92 \) |  
| \( 0.92 \times 16 \) | \( 14 \) (E) | \( 0.72 \) |  

**Hexadecimal Representation**:  
$
(46.32)_{10} = (2E.51F)_{16}
$

---

### 5. Hexadecimal to Binary Conversion

#### 1. \( (1AF)_{16} = (?)_{2} \)

**Steps**:  
- \( 1 \): \( 0001 \)  
- \( A (10) \): \( 1010 \)  
- \( F (15) \): \( 1111 \)  

**Binary Representation**:  
$
(1AF)_{16} = (000110101111)_{2}
$


# 06
### 2. \( (3FB)_{16} = (?)_2 \)

**Steps**:  
- \( 3 \): \( 0011 \)  
- \( F (15) \): \( 1111 \)  
- \( B (11) \): \( 1011 \)  

**Binary Representation**:  
$
(3FB)_{16} = (001111111011)_{2}
$

---

### 3. \( (C1.A)_{16} = (?)_2 \)

**Steps**:  
- \( C (12) \): \( 1100 \)  
- \( 1 \): \( 0001 \)  
- \( A (10) \): \( 1010 \)  

**Binary Representation**:  
$
(C1.A)_{16} = (110000011010)_{2}
$

---

### 4. \( (D8.8A)_{16} = (?)_2 \)

**Steps**:  
- \( D (13) \): \( 1101 \)  
- \( 8 \): \( 1000 \)  
- \( 8 \): \( 1000 \)  
- \( A (10) \): \( 1010 \)  

**Binary Representation**:  
$
(D8.8A)_{16} = (1101100010001010)_{2}
$

---

### 5. Binary to Hexadecimal Conversion

#### 1. \( (10110110)_{2} = (?)_{16} \)

**Steps**:  
Group binary digits into groups of 4 from right to left:  
- \( 1011 \): \( B \)  
- \( 0110 \): \( 6 \)  

**Hexadecimal Representation**:  
$
(10110110)_{2} = (B6)_{16}
$

# 07
### 2. \( (11101111.0110)_2 = (?)_{16} \)

**Steps**:  
Group binary digits into groups of 4 from right to left (including the fractional part):  
- \( 1110 \): \( E \)  
- \( 1111 \): \( F \)  
- \( 0110 \): \( 6 \)  

**Hexadecimal Representation**:  
$
(11101111.0110)_2 = (EF6)_{16}
$

---

### 3. \( (1010111)_2 = (?)_{16} \)

**Steps**:  
Group binary digits into groups of 4 from right to left:  
- Add a leading zero to make it a group of 4: \( 0101 \)  
- \( 0101 \): \( 5 \)  
- \( 0111 \): \( 7 \)  

**Hexadecimal Representation**:  
$
(1010111)_2 = (57)_{16}
$

---

### 6. Hexadecimal to Decimal Conversion

#### 1. \( (1A2)_{16} = (?)_{10} \)

**Steps**:  
$
1 \times 16^2 + A \times 16^1 + 2 \times 16^0
$  
$
= 1 \times 256 + 10 \times 16 + 2 \times 1
$  
$
= 256 + 160 + 2
$  
$
= 418
$  

**Decimal Representation**:  
$
(1A2)_{16} = (418)_{10}
$

---

#### 2. \( (FB8)_{16} = (?)_{10} \)

**Steps**:  
$
F \times 16^2 + B \times 16^1 + 8 \times 16^0
$  
$
= 15 \times 256 + 11 \times 16 + 8 \times 1
$  
$
= 3840 + 176 + 8
$  
$
= 4024
$  

**Decimal Representation**:  
$
(FB8)_{16} = (4024)_{10}
$


# 08
## Signed Number Representation

### 1. Sign Magnitude Representation

---

### 2. 1's Complement Representation

**Example**:  
$
(1011)_2 \rightarrow \text{Replacement} \rightarrow (0100)_2
$

---

## Binary Addition and Binary Subtraction

### Binary Addition

#### 1. Basic Binary Addition Rules:
| \( A + B \) | Sum | Carry |  
|-------------|-----|-------|  
| \( 0 + 0 \) | \( 0 \) | \( 0 \) |  
| \( 0 + 1 \) | \( 1 \) | \( 0 \) |  
| \( 1 + 0 \) | \( 1 \) | \( 0 \) |  
| \( 1 + 1 \) | \( 0 \) | \( 1 \) |  

---

#### 2. Example 1:
$
0101 \, (\text{5}) \, + \, 0101 \, (\text{5}) = 1010 \, (\text{10})
$

---

#### 3. Example 2:
$
1111 \, + \, 0001 = 10000
$

**Steps**:
- Add column by column with carry.
- Result: \( 10000 \).

---

Let me know if you need further clarifications or adjustments! 😊


# 09

### 4. Binary Addition Example

#### Given Numbers:
- \( 75 \): \( 1001011 \)  
- \( 65 \): \( 1000001 \)  

**Addition**:  
$
1001011 + 1000001 = 10011100
$

#### Steps:
1. Add the binary numbers column by column.
2. Carry over where necessary.
3. Final result: \( 140 \): \( 10011100 \).

---

### 5. Binary Addition with Fractional Part

#### Given Numbers:
- \( 1011.101 \)  
- \( 1101.100 \)  

**Addition**:  
$
1011.101 + 1101.100 = 11001.001
$

#### Steps:
1. Align the binary numbers by the decimal point.
2. Add column by column, including the fractional part.
3. Final result: \( 11001.001 \).

---

## Binary Subtraction

### 1. Basic Binary Subtraction Rules:
| \( A - B \) | Difference | Borrow |  
|-------------|------------|--------|  
| \( 0 - 0 \) | \( 0 \)    | \( 0 \) |  
| \( 0 - 1 \) | \( 1 \)    | \( 1 \) |  
| \( 1 - 0 \) | \( 1 \)    | \( 0 \) |  
| \( 1 - 1 \) | \( 0 \)    | \( 0 \) |  

---

### 2. Binary Subtraction Example:

#### Given:
$
110.01 - 011.10
$

**Steps**:
1. Align the binary numbers by the decimal point.
2. Subtract column by column, borrowing where necessary.
3. Final result:
$
110.01 - 011.10 = 010.11
$


# 10

## Subtraction Using 1's Complement

### Steps:
1. Find the 1's complement of \( B \).
2. Add this complement to \( A \).
3. The carry, if obtained, is added to the result to get the final answer.

---

### Example 1:
#### Given:
$
A = 10110 \quad (22) \quad B = 10010 \quad (18)
$

#### Step 1: Find 1's complement of \( B \)
$
B = 10010 \quad \rightarrow \quad \text{1's Complement of } B = 01101
$

#### Step 2: Add \( A \) and the 1's complement of \( B \)
$
10110 + 01101 = 100011
$

#### Step 3: Add the carry to the result
$
00011 + 1 = 00100 \quad (4)
$

---

### Example 2:
#### Given:
$
A = 111001 \quad (57) \quad B = 100111 \quad (39)
$

#### Step 1: Find 1's complement of \( B \)
$
B = 100111 \quad \rightarrow \quad \text{1's Complement of } B = 011000
$

#### Step 2: Add \( A \) and the 1's complement of \( B \)
$
111001 + 011000 = 1011001
$

#### Step 3: Add the carry to the result
$
001001 + 1 = 010010 \quad (18)
$


# 11

## Subtraction Using 1's Complement

### Example 3:
#### Given:
$
A = 1111001 \quad (121), \quad B = 1001111 \quad (79)
$

#### Step 1: Find 1's Complement of \( B \)
$
B = 1001111 \quad \rightarrow \quad \text{1's Complement of } B = 0110000
$

#### Step 2: Add \( A \) and the 1's Complement of \( B \)
$
1111001 + 0110000 = 10101001
$

#### Step 3: Add the Carry to the Result
$
0101001 + 1 = 0101010 \quad (42)
$

---

## Subtraction Using 2's Complement

### Steps:
1. Find the 2's Complement of \( B \).  
2. Add it to \( A \).  
3. If a carry is generated, neglect it to get the required subtraction.

---

### 2's Complement Representation

#### Given:
$
(1010)_2
$

1. Find 1's Complement:
$
1's \, Complement = 0101
$

2. Add \( 1 \) to the 1's Complement:
$
0101 + 1 = 0110
$

#### Result:
$
2's \, Complement = 0110
$


# 12
 ### Perform Binary Subtraction Using 2's Complement

---

#### 1. \( (11110)_2 - (10101)_2 \)

**Steps**:  
1. Find the 1's Complement of \( B = 10101 \):  
   $
   1's \, Complement = 01010
   $

2. Add \( 1 \) to the 1's Complement to get the 2's Complement:  
   $
   2's \, Complement = 01011
   $

3. Add \( A = 11110 \) and the 2's Complement of \( B \):  
   $
   11110 + 01011 = 101001
   $

4. Neglect the carry:  
   $
   Final \, Answer = 01001
   $

---

#### 2. \( (10110)_2 - (01111)_2 \)

**Steps**:  
1. Find the 1's Complement of \( B = 01111 \):  
   $
   1's \, Complement = 10000
   $

2. Add \( 1 \) to the 1's Complement to get the 2's Complement:  
   $
   2's \, Complement = 10001
   $

3. Add \( A = 10110 \) and the 2's Complement of \( B \):  
   $
   10110 + 10001 = 100111
   $

4. Neglect the carry:  
   $
   Final \, Answer = 00111
   $

---

#### 3. \( 97_{10} - 39_{10} \)

**Steps**:  
1. Convert to Binary:  
   \( A = 97 = 1100001 \), \( B = 39 = 0100111 \)

2. Find the 1's Complement of \( B \):  
   $
   1's \, Complement = 1011000
   $

3. Add \( 1 \) to the 1's Complement to get the 2's Complement:  
   $
   2's \, Complement = 1011001
   $

4. Add \( A \) and the 2's Complement of \( B \):  
   $
   1100001 + 1011001 = 1011010
   $

5. Neglect the carry:  
   $
   Final \, Answer = 58_{10}
   $


# 13

### 4. Subtract 27 from 68

#### Given:
- \( 68 = 1000100 \)  
- \( 27 = 0011011 \)

---

#### Steps:

1. **Find the 1's Complement of \( B \):**  
   $
   B = 0011011 \quad \rightarrow \quad \text{1's Complement of } B = 1100100
   $

2. **Find the 2's Complement of \( B \):**  
   Add \( 1 \) to the 1's Complement:  
   $
   1100100 + 1 = 1100101
   $

3. **Add \( A \) and the 2's Complement of \( B \):**  
   $
   1000100 + 1100101 = 10110001
   $

4. **Neglect the Carry:**  
   $
   Final \, Answer = 0100101
   $  
   $
   0100101 = 41
   $

---

### 5. Subtract 70 from 84 (Most Important Question)

#### Given:
- \( 84 = 1010100 \)  
- \( 70 = 1000110 \)

---

#### Steps:

1. **Find the 1's Complement of \( B \):**  
   $
   B = 1000110 \quad \rightarrow \quad \text{1's Complement of } B = 0111001
   $

2. **Find the 2's Complement of \( B \):**  
   Add \( 1 \) to the 1's Complement:  
   $
   0111001 + 1 = 0111010
   $

3. **Add \( A \) and the 2's Complement of \( B \):**  
   $
   1010100 + 0111010 = 10001110
   $

4. **Neglect the Carry:**  
   $
   Final \, Answer = 0001110
   $  
   $
   0001110 = 14
   $


# 14

### Subtraction Example: \( 70 - 84 \)

#### Steps:

1. **Find the 1's Complement of \( B = 84 \):**  
   \[
   B = 1010100 \quad \rightarrow \quad \text{1's Complement of } B = 0101011
   \]

2. **Find the 2's Complement of \( B \):**  
   Add \( 1 \) to the 1's Complement:  
   \[
   0101011 + 1 = 0101100
   \]

3. **Add \( A = 70 = 1000110 \) and the 2's Complement of \( B \):**  
   \[
   1000110 + 0101100 = 1110010
   \]

4. **Neglect the Carry:**  
   Since no carry is generated, the result is negative:  
   \[
   \text{Final Answer} = - (00011010) = -26
   \]

---

### Weighted and Unweighted Code

#### Weighted Code:
- The main characteristic of a weighted code is that **each binary bit is assigned a "weight"** and the values depend on the position of the binary bit.  
- The sum of the weights of these binary bits, whose value is \( 1 \), is equal to the decimal digit which they represent.  

**Examples:**  
\( 5421, 8421, 2421, \text{BCD} \)

---

#### Classification of Codes:
Codes can be classified into **weighted and unweighted codes**.  
- In a **weighted code**, a weight is assigned to each symbol position of the code.  
- In case of the decimal number system, each position has a weight in increasing powers of \( 10 \):  
  \[
  10^0 = 1, \, 10^1 = 10, \, 10^2 = 100, \ldots
  \]

---

**Few Examples of Weighted Codes:**  
Natural BCD, \( 5421, 8421, 2421 \)


# 15

### Unweighted Code

- **Definition**:  
  An unweighted code is a code where no fixed weight is assigned to each symbol position.  
  Thus, there is no systematic way of representing numbers.

- **Examples**:  
  - Gray code  
  - Excess-3 code  
  - EBCDIC (Extended Binary Coded Decimal Interchanging Code)  

---

### Binary to BCD Conversion

#### 1. Convert \( (1101100)_2 = (?)_{BCD} \)

**Steps**:  
1. Calculate the decimal value of the binary number:
   \[
   (1101100)_2 = 2^6 \times 1 + 2^5 \times 1 + 2^3 \times 1 + 2^2 \times 1
   \]
   \[
   = 64 + 32 + 8 + 4 = 108
   \]

2. Write the decimal number \( 108 \) in BCD:  
   - \( 1 \): \( 0001 \)  
   - \( 0 \): \( 0000 \)  
   - \( 8 \): \( 1000 \)  

**Result**:  
\[
(1101100)_2 = (0001 \, 0000 \, 1000)_{BCD}
\]

---

#### 2. Convert \( (10010110)_2 = (?)_{BCD} \)

**Steps**:  
1. Calculate the decimal value of the binary number:
   \[
   (10010110)_2 = 2^7 \times 1 + 2^4 \times 1 + 2^2 \times 1 + 2^1 \times 1
   \]
   \[
   = 128 + 16 + 4 + 2 = 150
   \]

2. Write the decimal number \( 150 \) in BCD:  
   - \( 1 \): \( 0001 \)  
   - \( 5 \): \( 0101 \)  
   - \( 0 \): \( 0000 \)  

**Result**:  
\[
(10010110)_2 = (0001 \, 0101 \, 0000)_{BCD}
\]


# 16



### 2. BCD to Binary Conversion

#### Example 1:
\[
(01011001)_{BCD} = (?)_2
\]

**Steps**:
1. Break BCD into digits:
   - \( 5: 0101 \)
   - \( 9: 1001 \)

2. Convert to binary:
   - \( 59 = 111011 \)

**Result**:
\[
(01011001)_{BCD} = (111011)_2
\]

---

#### Example 2:
\[
(01010001)_{BCD} = (?)_2
\]

**Steps**:
1. Break BCD into digits:
   - \( 2: 0010 \)
   - \( 7: 0111 \)

2. Convert to binary:
   - \( 27 = 11011 \)

**Result**:
\[
(01010001)_{BCD} = (11011)_2
\]

---

### 3. Binary to Gray Code Conversion

#### Example:
\[
(1011)_2 = (?)_{Gray}
\]

**Steps**:
1. Copy the Most Significant Bit (MSB) as the first bit in Gray Code:
   - \( MSB = 1 \)

2. For the remaining bits, compute:
   - \( \text{Gray}[i] = \text{Binary}[i] \oplus \text{Binary}[i+1] \)

3. Result:
   \[
   (1011)_2 \rightarrow (1110)_{Gray}
   \]

---

#### Conversion Table for \( 4 \)-Bit Binary to Gray Code:

| Binary | Gray Code |
|--------|-----------|
| 0000   | 0000      |
| 0001   | 0001      |
| 0010   | 0011      |
| 0011   | 0010      |
| 0100   | 0110      |
| 0101   | 0111      |
| 0110   | 0101      |
| 0111   | 0100      |
| 1000   | 1100      |
| 1001   | 1101      |
| 1010   | 1111      |
| 1011   | 1110      |
| 1100   | 1010      |
| 1101   | 1011      |
| 1110   | 1001      |
| 1111   | 1000      |


# 17

### 4. Gray to Binary Conversion

#### Example 1:
\[
(10111)_{Gray} \rightarrow (?)_2
\]

**Steps**:
1. Copy the MSB as the first Binary bit:
   - \( MSB = 1 \)

2. Compute the remaining Binary bits:
   - \( Binary[i] = Binary[i-1] \oplus Gray[i] \)

3. Result:
   \[
   (10111)_{Gray} \rightarrow (11010)_2
   \]

---

#### Example 2:
\[
(111001)_{Gray} \rightarrow (?)_2
\]

**Steps**:
1. Copy the MSB as the first Binary bit:
   - \( MSB = 1 \)

2. Compute the remaining Binary bits:
   - \( Binary[i] = Binary[i-1] \oplus Gray[i] \)

3. Result:
   \[
   (111001)_{Gray} \rightarrow (101101)_2
   \]

---

#### Example 3:
\[
(11101)_{Gray} \rightarrow (?)_2
\]

**Steps**:
1. Copy the MSB as the first Binary bit:
   - \( MSB = 1 \)

2. Compute the remaining Binary bits:
   - \( Binary[i] = Binary[i-1] \oplus Gray[i] \)

3. Result:
   \[
   (11101)_{Gray} \rightarrow (10110)_2
   \]

---

### Alphanumeric Representation

#### Character Codes:
These are called character codes, which contain both letters and digits. They also include special characters like \( \$, *, \dots \). These codes allow coding of both upper and lower case alphabets.

#### Popularly Used Character Codes:
1. **ASCII**:
   - **American Standard Code for Information Interchange**

2. **EBCDIC**:
   - **Extended Binary Coded Decimal Interchange Code**

---

### ASCII Code
- ASCII is a **7-bit code**, capable of coding 128 alphanumeric characters.  
- It includes special characters and allows manufacturers to standardize computer hardware.



# 18

### Binary and Decimal Representation of Alphabets

| Alphabet | Binary     | Decimal |
|----------|------------|---------|
| A        | 1000001    | 65      |
| B        | 1000010    | 66      |
| C        | 1000011    | 67      |
| D        | 1000100    | 68      |
| E        | 1000101    | 69      |
| F        | 1000110    | 70      |
| G        | 1000111    | 71      |
| H        | 1001000    | 72      |
| I        | 1001001    | 73      |
| J        | 1001010    | 74      |
| K        | 1001011    | 75      |
| L        | 1001100    | 76      |
| M        | 1001101    | 77      |
| N        | 1001110    | 78      |
| O        | 1001111    | 79      |
| P        | 1010000    | 80      |
| Q        | 1010001    | 81      |
| R        | 1010010    | 82      |
| S        | 1010011    | 83      |
| T        | 1010100    | 84      |
| U        | 1010101    | 85      |
| V        | 1010110    | 86      |
| W        | 1010111    | 87      |
| X        | 1011000    | 88      |
| Y        | 1011001    | 89      |
| Z        | 1011010    | 90      |


# 19

### Binary and Decimal Representation of Lowercase Alphabets

| Alphabet | Binary     | Decimal |
|----------|------------|---------|
| a        | 1100001    | 97      |
| b        | 1100010    | 98      |
| z        | 1111010    | 122     |

---

### Binary and Decimal Representation of Digits

| Digit | Binary     | Decimal |
|-------|------------|---------|
| 0     | 110000     | 48      |
| 1     | 110001     | 49      |
| 2     | 110010     | 50      |
| 3     | 110011     | 51      |
| 4     | 110100     | 52      |
| 5     | 110101     | 53      |
| 6     | 110110     | 54      |
| 7     | 110111     | 55      |
| 8     | 111000     | 56      |
| 9     | 111001     | 57      |

# 20

# Logic Gates and Boolean Algebra

## Concept of Positive and Negative Logic
- **Positive Logic**:  
  High voltage = 1  
  Low voltage = 0  

- **Negative Logic**:  
  High voltage = 0  
  Low voltage = 1  

---

## Basic Logic Gates

### 1) AND Gate
- **Diagram**:

## Source

![AND Gate](data/img/20.jpeg)

# 21

 Logic Gates and Boolean Algebra

## Concept of Positive and Negative Logic
- **Positive Logic**:  
  High voltage = 1  
  Low voltage = 0  

- **Negative Logic**:  
  High voltage = 0  
  Low voltage = 1  

---

## Basic Logic Gates

### AND Gate
- **Diagram**:  

  A ----\
         AND---- Y
  B ----/

- **Statement**: When all inputs are high, the output is high.  
- **Boolean Expression**: `Y = A ⋅ B`  
- **Truth Table**:  

| A | B | Y |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

---

### OR Gate
- **Diagram**:  
lua
Kopieren
Bearbeiten
  A ----\
         OR---- Y
  B ----/

- **Statement**: When all inputs are low, the output is low.  
- **Boolean Expression**: `Y = A + B`  
- **Truth Table**:  

| A | B | Y |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 1 |

---

### 3) NOT Gate
- **Diagram**:  
```

   A ---|>o--- Y
markdown
Kopieren
Bearbeiten
- **Statement**: The output of NOT Gate is the complement of its input.  
- **Boolean Expression**: `Y = A̅`  
- **Truth Table**:  
| A | Y |
|---|---|
| 0 | 1 |
| 1 | 0 |

---

### 4) NOR Gate

- **Diagram**:  

  A ----\
         OR----o--- Y
  B ----/

- **Statement**: When all the input is low, the output is high.  
- **Boolean Expression**: `Y = A + B` (with NOT applied)  
- **Truth Table**:  
| A | B | Y |
|---|---|---|
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 0 |

---

## Additional Notes
This guide provides a concise summary of the logic gates and their respective Boolean expressions and truth tables. Let me know if you'd like further gates or additional explanations in this style!







# 22

## Additional Logic Gates

---

### 5) NAND Gate (AND + NOT)
- **Diagram**:  
```

  A ----\
         AND----o--- Y
  B ----/
markdown
Kopieren
Bearbeiten
- **Statement**: When all the inputs are high, the output is low.  
- **Boolean Expression**: `Y = (A ⋅ B)̅`  
- **Truth Table**:  
| A | B | Y |
|---|---|---|
| 0 | 0 | 1 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

---

### 6) Ex-OR Gate (Exclusive OR)
- **Diagram**:  
lua
Kopieren
Bearbeiten
  A ----\
         OR---- Y
  B ----/
```

- **Statement**: When both the inputs are the same, the output is low.  
- **Boolean Expression**: `Y = A̅ ⋅ B + A ⋅ B̅` or `Y = A ⊕ B`  
- **Truth Table**:  
| A | B | Y |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

---

## Universal Gate
- **Definition**:  
The NAND or NOR gates are called **Universal Gates** because all basic gates (AND, OR, NOT) can be built using only NAND or NOR gates.  
- **Concept**:  
To construct these gates, De Morgan's Theorem is used.

# 23

## Additional Logic Gates

---

### 5) NAND Gate (AND + NOT)
- **Diagram**:  
```

  A ----\
         AND----o--- Y
  B ----/
markdown
Kopieren
Bearbeiten
- **Statement**: When all the inputs are high, the output is low.  
- **Boolean Expression**: `Y = (A ⋅ B)̅`  
- **Truth Table**:  
| A | B | Y |
|---|---|---|
| 0 | 0 | 1 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

---

### 6) Ex-OR Gate (Exclusive OR)
- **Diagram**:  

```
  A ----\
         OR---- Y
  B ----/
```

- **Statement**: When both the inputs are the same, the output is low.  
- **Boolean Expression**: `Y = A̅ ⋅ B + A ⋅ B̅` or `Y = A ⊕ B`  
- **Truth Table**:  
| A | B | Y |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

---

## Universal Gate
- **Definition**:  
The NAND or NOR gates are called **Universal Gates** because all basic gates (AND, OR, NOT) can be built using only NAND or NOR gates.  
- **Concept**:  
To construct these gates, De Morgan's Theorem is used.

# 24

## Building All Basic Gates Using NAND Gate

### 1) NOT Gate Using NAND
- **Diagram**:  
```

     A
      \
      NAND---o--- A'
      /
     A
```

- **Logic**: The input is connected to both terminals of the NAND gate to create a NOT operation.

- **Boolean Expression**: `Y = A'`

### 2) AND Gate Using NAND
- **Diagram**:  

```
  A ----\
         NAND----o---- A'
  B ----/
           \
           NAND---o--- (A ⋅ B)
           /
        A'
```

- **Logic**: A NOT operation is performed on the output of the NAND gate.
- **Boolean Expression**: `Y = A ⋅ B`

---

### 3) OR Gate Using NAND
- **Diagram**:  
```
  A ----\           A'
         NAND----\
  B ----/         NAND---o--- A' + B'
       \
        NAND----\
                  OR OUTPUT
```

- **Logic**: Negate both inputs and combine them using NAND gates.
- **Boolean Expression**: `Y = A + B`

---

### 4) NOR Gate Using NAND
- **Diagram**:  
```

  A ----\           A'
         NAND----\
  B ----/         NAND---o--- A' ⋅ B'
       \
        NAND----\
                  NOR OUTPUT
```

- **Logic**: Combine NOT and OR logic using NAND gates.
- **Boolean Expression**: `Y = (A + B)'`

---

### 5) Ex-OR Gate Using NAND
- **Diagram**:  
```

    A ----\
          NAND---\
    B ----/       NAND---\
        \          A⋅B'  NAND--- Y (A⊕B)
         \        /
          NAND---/
```

- **Logic**: Combine multiple NAND gates to implement the Exclusive OR operation.
- **Boolean Expression**: `Y = A' ⋅ B + A ⋅ B'`

---

This demonstrates how universal NAND gates can replace all basic logic gates.

# 25

## Boolean Algebra Laws


### 1) **Commutative Law**
- **For OR Operation**:  
  \( A + B = B + A \)
- **For AND Operation**:  
  \( A \cdot B = B \cdot A \)

---

### 2) **Associative Law**
- **For OR Operation**:  
  \( A + (B + C) = (A + B) + C \)
- **For AND Operation**:  
  \( A \cdot (B \cdot C) = (A \cdot B) \cdot C \)

---

### 3) **Distributive Law**
- **For AND Over OR**:  
  \( A \cdot (B + C) = (A \cdot B) + (A \cdot C) \)

---

These laws are fundamental in simplifying Boolean expressions and are essential for digital circuit design.


# 26

# Additional Boolean Algebra Laws

---

### 4) **AND Laws**
- \( A \cdot A = A \)
- \( A \cdot 1 = A \)
- \( \overline{A} \cdot 1 = \overline{A} \)
- \( A \cdot 0 = 0 \)
- \( A \cdot \overline{A} = 0 \)

---

### 5) **OR Laws**
- \( A + A = A \)
- \( A + 1 = 1 \)
- \( \overline{A} + 1 = 1 \)
- \( A + \overline{A} = 1 \)
- \( A + 0 = A \)

---

### 6) **Inversion Law**
- \( \overline{\overline{A}} = A \)

---

### 7) **Other Laws**
1. \( A + \overline{A}B = A + B \)
2. \( \overline{A} + AB = \overline{A} + B \)
3. \( A \cdot (A + B) = A \)
4. \( A \cdot (\overline{A} + B) = AB \)
5. \( (A + B)(A + C) = A + BC \)
6. \( (A + B)(A + \overline{B}) = A \)
7. \( A \cdot B \cdot C = \overline{\overline{A} + \overline{B} + \overline{C}} \)
8. \( A + B + C = \overline{\overline{A} \cdot \overline{B} \cdot \overline{C}} \)

---

These laws are essential for simplifying Boolean expressions and optimizing digital circuits.


# 27

# Additional Boolean Algebra Laws

---

### 4) **AND Laws**
- \( A \cdot A = A \)
- \( A \cdot 1 = A \)
- \( \overline{A} \cdot 1 = \overline{A} \)
- \( A \cdot 0 = 0 \)
- \( A \cdot \overline{A} = 0 \)

---

### 5) **OR Laws**
- \( A + A = A \)
- \( A + 1 = 1 \)
- \( \overline{A} + 1 = 1 \)
- \( A + \overline{A} = 1 \)
- \( A + 0 = A \)

---

### 6) **Inversion Law**
- \( \overline{\overline{A}} = A \)

---

### 7) **Other Laws**
1. \( A + \overline{A}B = A + B \)
2. \( \overline{A} + AB = \overline{A} + B \)
3. \( A \cdot (A + B) = A \)
4. \( A \cdot (\overline{A} + B) = AB \)
5. \( (A + B)(A + C) = A + BC \)
6. \( (A + B)(A + \overline{B}) = A \)
7. \( A \cdot B \cdot C = \overline{\overline{A} + \overline{B} + \overline{C}} \)
8. \( A + B + C = \overline{\overline{A} \cdot \overline{B} \cdot \overline{C}} \)

---

These laws are essential for simplifying Boolean expressions and optimizing digital circuits.

# 28

##  Simplification of Boolean Expressions

### 1) Simplify \( (A + B)(\overline{A} + B) \)

**Solution**:
- \( (A + B)(\overline{A} + B) \)
- \( = A\overline{A} + AB + \overline{A}B + BB \) (Applying Distributive Law)
- \( = 0 + AB + \overline{A}B + B \) (Since \( A\overline{A} = 0 \) and \( BB = B \))
- \( = AB + \overline{A}B + B \) (Simplifying)
- \( = B(A + \overline{A}) + B \) (Factorizing \( B \))
- \( = B(1) + B \) (Since \( A + \overline{A} = 1 \))
- \( = B + B \)
- \( = B \) (Idempotent Law)

**Final Answer**: \( B \)

---

### 2) Simplify \( (A + BC)(\overline{B} + \overline{C}) \)

**Solution**:
- \( (A + BC)(\overline{B} + \overline{C}) \)
- \( = A\overline{B} + A\overline{C} + BC\overline{B} + BC\overline{C} \) (Expanding using Distributive Law)
- \( = A\overline{B} + A\overline{C} + 0\cdot C + B\cdot 0 \) (Since \( BC\overline{B} = 0 \) and \( BC\overline{C} = 0 \))
- \( = A\overline{B} + A\overline{C} \) (Simplifying)
- \( = A(\overline{B} + \overline{C}) \) (Factorizing \( A \))

**Final Answer**: \( A(\overline{B} + \overline{C}) \)

---

### Logic Diagram Representation:
The logic diagram for \( A(\overline{B} + \overline{C}) \):
- \( \overline{B} + \overline{C} \) is an OR gate with inputs \( \overline{B} \) and \( \overline{C} \).
- The output of the OR gate is ANDed with \( A \).

The drawn circuit clearly shows:
1. The OR gate combining \( \overline{B} \) and \( \overline{C} \).
2. The AND gate with input \( A \) and the output of the OR gate.


# 29: Simplification of Boolean Expressions

---

### 3) Simplify \( \overline{A}B + \overline{A}B\overline{C} + \overline{A}BCD + AB\overline{C}D \)

**Solution**:
- \( \overline{A}B + \overline{A}B\overline{C} + \overline{A}BCD + AB\overline{C}D \)
- \( = \overline{A}B(1 + \overline{C}) + \overline{A}BCD + AB\overline{C}D \) (Factorizing \( \overline{A}B \))
- \( = \overline{A}B + AB\overline{C}D \) (Since \( 1 + \overline{C} = 1 \))
- \( = \overline{A}B(1) \) (Simplify)
- \( = \overline{A}B \)

**Final Answer**: \( \overline{A}B \)

---

### Logic Diagram Representation:
The simplified expression \( \overline{A}B \):
- The logic circuit uses:
  - An AND gate.
  - Inputs are \( \overline{A} \) (NOT gate for \( A \)) and \( B \).

---

### 4) Simplify \( (\overline{A} + B + C)(A\overline{B} + C) \)

**Solution**:
- \( (\overline{A} + B + C)(A\overline{B} + C) \)
- Expanding:
  - \( = \overline{A}A\overline{B} + \overline{A}C + B(A\overline{B}) + BC + C(A\overline{B}) + CC \)
  - \( = \overline{A}A\overline{B} + \overline{A}C + AB\overline{B} + BC + AC + C \) (Simplify \( CC = C \))
- Combine terms:
  - \( = \overline{A}C + BC + C(A + B) \)
  - \( = \overline{A}C + BC + C \) (Since \( A + B = 1 \) for the final term)
- Final Simplification:
  - \( = \overline{A}C + BC + C \)
  - \( = C(\overline{A} + B + 1) \)
  - \( = C \)

**Final Answer**: \( C \)

---

### Logic Diagram Representation:
The circuit diagram for \( \overline{A}C + BC + C \):
1. \( \overline{A} \): NOT gate for \( A \).
2. \( \overline{A}C \): AND gate with \( \overline{A} \) and \( C \).
3. \( BC \): AND gate with \( B \) and \( C \).
4. OR gates combine the outputs to form \( C \).


# 30: De Morgan's Theorem

## 1st Theorem:
**The complement of the sum is equal to the product of the complement.**

### Equation:
**A + B = A̅ . B̅**

#### Diagram:
A → OR Gate → Y B → → A̅ . B̅ → AND Gate → Y


#### Proof:
| A | B | A + B | A̅ | B̅ | A̅ . B̅ |
|---|---|-------|----|----|---------|
| 0 | 0 |   0   |  1 |  1 |    1    |
| 0 | 1 |   1   |  1 |  0 |    0    |
| 1 | 0 |   1   |  0 |  1 |    0    |
| 1 | 1 |   1   |  0 |  0 |    0    |

---

## 2nd Theorem:

**The complement of the product is equal to the sum of the complement.**

### Equation:

**A . B = A̅ + B̅**

#### Diagram:
```
A → AND Gate → Y B → → A̅ + B̅ → OR Gate → Y
```


#### Proof:
| A | B | A . B | A̅ | B̅ | A̅ + B̅ |
|---|---|-------|----|----|---------|
| 0 | 0 |   0   |  1 |  1 |    1    |
| 0 | 1 |   0   |  1 |  0 |    1    |
| 1 | 0 |   0   |  0 |  1 |    1    |
| 1 | 1 |   1   |  0 |  0 |    0    |


# 31: Simplification and Karnaugh's Map (K-Map)

## Simplification:
### Given:
**Y = (X + Y̅) (Y̅Z̅) (Z + X)**

### Steps:
1. Expand the terms:
= (X + Y̅ + 0) (Y̅ + Z̅ + 0) (Z + X + 0) = (X + Y̅ + Z . Z̅) (Y̅ + Z̅ + X) (Z + X + Y̅)

markdown
Kopieren
Bearbeiten

2. Combine and simplify:
= (X + Y̅ + Z̅) (Y̅ + Z̅ + X) (Z + X + Y̅) = (X + Y̅) (X + Z̅) (Y̅ + Z̅) (Z + X) (Y̅ + Z)

yaml
Kopieren
Bearbeiten

---

## Karnaugh's Map (K-Map)

### Variables:
| A | B | Representation |
|---|---|----------------|
| 0 | 0 | A̅ B̅          |
| 0 | 1 | A̅ B           |
| 1 | 0 | A B̅           |
| 1 | 1 | A B            |

---

### K-Map Table:
#### Example 1:
|     | AB | A̅B | A̅B̅ | AB̅ |
|-----|----|-----|------|-----|
| C   |    |     |      |     |
| C̅  |    |     |      |     |

#### Example 2:
|     | AB | A̅B | A̅B̅ | AB̅ |
|-----|----|-----|------|-----|
| CD  |    |     |      |     |
| C̅D |    |     |      |     |
| CD̅ |    |     |      |     |
| C̅D̅|    |     |      |     |

# 32

# Karnaugh Map (K-Map) Simplification

## Problem:
**Y = A̅B̅C̅ + A̅B̅C + A̅BC̅ + A̅BC + AB̅C̅ + AB̅C + ABC̅ + ABC**

## Steps:

### K-Map Representation:
| AB \ CD | C̅D̅ | C̅D | CD | CD̅ |
|---------|------|-----|----|-----|
| A̅B̅    | 1    | 1   | 1  | 0   |
| A̅B     | 0    | 1   | 1  | 0   |
| AB̅     | 0    | 0   | 1  | 1   |
| AB      | 0    | 0   | 0  | 1   |

### Groupings:
1. **q₁** = C̅D (Quad of 4 cells)
2. **q₂** = BD (Octal of 8 cells)
3. **q₃** = AD (Pair of 2 cells)

---

## Simplified Expression:
**Y = C̅D + BD + AD**


# 33

# Karnaugh Map (K-Map) Simplification

## Problem:
**Y = A̅BC̅ + A̅BC + AB̅C + ABC̅**

### K-Map Representation:
| AB \ C | C̅ | C |
|--------|----|---|
| A̅B̅   | 0  | 0 |
| A̅B    | 1  | 1 |
| AB̅    | 1  | 0 |
| AB     | 0  | 1 |

### Groupings:
1. **q₁** = A̅B̅ (Pair of 2 cells)
2. **p₁** = BC (Pair of 2 cells)

---

## Simplified Expression:
**Y = A̅B̅ + BC**

---

# Minimized SOP Expression from Truth Table

## Given Truth Table:
| A | B | C | O/P |
|---|---|---|-----|
| 0 | 0 | 0 | 0   |
| 0 | 0 | 1 | 1   |
| 0 | 1 | 0 | 1   |
| 0 | 1 | 1 | 1   |
| 1 | 0 | 0 | 0   |
| 1 | 0 | 1 | 0   |
| 1 | 1 | 0 | 1   |
| 1 | 1 | 1 | 1   |

---

## Simplified SOP Expression:
To be derived based on K-Map or Quine-McCluskey methods.

# 34

# K-Map Simplification and Digital Designing

## K-Map Simplification for Expression
**Y = C + A̅B + AB̅**

### K-Map Representation:
| AB \ C | C̅ | C |
|--------|----|---|
| A̅B̅   | 0  | 1 |
| A̅B    | 1  | 1 |
| AB̅    | 1  | 1 |
| AB     | 0  | 1 |

### Groupings:
1. **q₁** = C
2. **p₁** = A̅B
3. **p₂** = AB̅

### Simplified Expression:
**Y = C + A̅B + AB̅**

---

## Digital Designing Using K-Map
### Binary to Gray and Gray to Binary Conversion

#### Four-Bit Binary to Gray Code Conversion:
| B₃ B₂ B₁ B₀ | G₃ G₂ G₁ G₀ |
|--------------|-------------|
| 0  0  0  0  | 0  0  0  0  |
| 0  0  0  1  | 0  0  0  1  |
| 0  0  1  0  | 0  0  1  1  |
| 0  0  1  1  | 0  0  1  0  |
| 0  1  0  0  | 0  1  1  0  |
| 0  1  0  1  | 0  1  1  1  |

---

Let me know if more details need to be included or if there are additional conversions you'd like me to document!


# 35

## Extended Table for Binary to Gray Code Conversion

| B₃ B₂ B₁ B₀ | G₃ G₂ G₁ G₀ |
|--------------|-------------|
| 0  0  0  0  | 0  0  0  0  |
| 0  0  0  1  | 0  0  0  1  |
| 0  0  1  0  | 0  0  1  1  |
| 0  0  1  1  | 0  0  1  0  |
| 0  1  0  0  | 0  1  1  0  |
| 0  1  0  1  | 0  1  1  1  |
| 0  1  1  0  | 0  1  0  1  |
| 0  1  1  1  | 0  1  0  0  |
| 1  0  0  0  | 1  1  0  0  |
| 1  0  0  1  | 1  1  0  1  |
| 1  0  1  0  | 1  1  1  1  |
| 1  0  1  1  | 1  1  1  0  |
| 1  1  0  0  | 1  0  1  0  |
| 1  1  0  1  | 1  0  1  1  |
| 1  1  1  0  | 1  0  0  1  |
| 1  1  1  1  | 1  0  0  0  |

---

## Karnaugh Map (K-Map) for Gray to Binary Conversion

### K-Map Table:
| B₃ B₂ | B₁B₀  |
|-------|--------|
| 00    | 0  0  |
| 01    | 0  1  |
| 10    | 1  1  |
| 11    | 1  0  |

### Simplified Expression:
**O = B₃**

**Y = B₃**

This demonstrates the digital conversion from Binary to Gray and Gray to Binary effectively.


# 36

## Karnaugh Map for Digital Design Using K-Map

### Truth Table for Simplified Expression:
| **B₁ B₀** | **B₃ B₂** | **Output** |
|------------|-----------|------------|
| 0  0       | 0  0      | q₁         |
| 0  1       | 0  1      | q₂         |
| 1  0       | 1  0      | q₁         |
| 1  1       | 1  1      | q₂         |

---

### Simplified Expression:

**q₁ = B₃ B₂**

**q₂ = B₃ B₂'**

Combining the results:

**Y = B₃ B₂ + B₃ B₂'**

Factoring out common terms:

**Y = B₃ (B₂ + B₂')**

Using the XOR operation for simplification:

**Y = B₃ ⊕ B₂**


# 37

## Karnaugh Map and Logic Circuit for Binary to Gray Code Conversion

### K-Map for Binary to Gray Code
| **B₃ B₂** | **B₁ B₀** | **Output (q₁)** | **Output (q₂)** |
|------------|-----------|-----------------|-----------------|
| 0  0       | 0  0      | 0               | 1               |
| 0  1       | 0  1      | 1               | 1               |
| 1  0       | 1  0      | 1               | 0               |
| 1  1       | 1  1      | 1               | 1               |

---

### Simplified Expressions

#### Expression for q₁:
**q₁ = B₁ B₀**

#### Expression for q₂:
**q₂ = B₁ B₀**

Combining the results:

**Y = B₁ B₀ + B₁ B₀**

Using XOR Operation:
**Y = B₁ ⊕ B₀**

---

### Logic Circuit

- **B₃** connects to the XOR gate with **B₂** to produce **G₃**.
- **B₂** connects to the XOR gate with **B₁** to produce **G₂**.
- **B₁** connects to the XOR gate with **B₀** to produce **G₁**.
- **B₀** directly outputs **G₀**.

**Gray Code Outputs:**
1. **G₃** = B₃
2. **G₂** = B₃ ⊕ B₂
3. **G₁** = B₂ ⊕ B₁
4. **G₀** = B₁ ⊕ B₀


# 38


## Karnaugh Map for Gray to Binary Conversion

### K-Map for **G₃**
| **G₁ G₀** | **Output (O)** |
|-----------|----------------|
| 0  0      | G₃            |
| 0  1      | G₃            |
| 1  0      | G₃            |
| 1  1      | G₃            |

---

### Expression for Output:
- **O = G₃**

---

### K-Map for **G₂**
| **G₁ G₀** | **Output (Y)** |
|-----------|----------------|
| 0  0      | G₃ G₂          |
| 0  1      | G₃ G₂          |
| 1  0      | G₃ G₂          |
| 1  1      | G₃ G₂          |

---

### Simplified Expression for Output:
- **Y = G₃ G₂ + G₃ G₂**
- Using XOR, **Y = G₃ ⊕ G₂**


# 39

## Simplifications and K-Map

### 1. Simplify: 
**Y = ABC + AB** using rules of Boolean Algebra:
Y = ABC + AB = AB(1 + C) (Factorization) = AB(1) (1 + C = 1) = AB

yaml
Kopieren
Bearbeiten

---

### 2. Convert the given SOP into Standard Form:

**Y = AB̅ + C**
$$ Y = AB̅ + C $$

$$  = AB̅·1 + C·1·1 (Multiplying by 1)$$
$$  = AB̅(C + C̅) + C(AB̅ + AB + A̅B + A̅B̅) (Expanding with distributive law) $$
$$ = ABC + AB̅C̅ + A̅BC + ABC̅ + A̅BC̅ + A̅B̅C + AB̅C $$

$$ = (ABC + A̅BC + A̅BC̅ + AB̅C̅ + ABC̅ + A̅B̅C) $$


### 3. Use K-Map to Simplify:
**Y = ABC + AB̅C̅ + A̅BC̅ + A̅BC**

#### K-Map:
| **AB\C** | **C̅** | **C** |
|----------|--------|-------|
| AB̅      | 1      | 0     |
| AB       | 0      | 1     |
| A̅B      | 1      | 1     |
| A̅B̅     | 0      | 0     |

#### Groups:
- P₁ = BC̅
- P₂ = AB
- P₃ = AC

**Simplified Expression:**

$$Y = AB + BC + AC$$

 # 40

# Conditional Circuit

## Combination Circuit
In this circuit, the output depends on the current input at that instant of time. Some examples of combination circuits are:

1. Half Adder
2. Full Adder
3. Multiplexer
4. Demultiplexer
5. Encoder
6. Decoder

---

## Half Adder
The half adder is used to improve addition for two binary digits. It is not a complete adder, as it is not able to add carry generated from the previous addition.

### Truth Table:
| A | B | S (Sum) | C (Carry) |
|---|---|---------|-----------|
| 0 | 0 |    0    |     0     |
| 0 | 1 |    1    |     0     |
| 1 | 0 |    1    |     0     |
| 1 | 1 |    0    |     1     |

### Explanation:
- From the truth table, we observe:
  - The **Sum (S)** is `1` only when `A` and `B` are different. This is the behavior of the XOR gate. Thus, when `A` and `B` are given as inputs to the XOR gate, it produces the sum.
  - The **Carry (C)** is `1` only when `A` and `B` are both `1`. This is the behavior of the AND gate. Thus, when `A` and `B` are given as inputs to the AND gate, it produces the carry.


# 41: Full Adder

A full adder is a digital circuit that adds three binary bits (`A`, `B`, and `C`) and produces a sum and a carry as outputs.

### Diagram:
The circuit for the full adder is composed of two XOR gates, two AND gates, and one OR gate. The outputs are:
- **Final Sum (S)**: Produced by the XOR gates.
- **Final Carry (C)**: Produced by the combination of AND and OR gates.

### Truth Table:
| A | B | C (Carry In) | Sum (S) | Carry Out (C) |
|---|---|--------------|---------|---------------|
| 0 | 0 |      0       |    0    |       0       |
| 0 | 0 |      1       |    1    |       0       |
| 0 | 1 |      0       |    1    |       0       |
| 0 | 1 |      1       |    0    |       1       |
| 1 | 0 |      0       |    1    |       0       |
| 1 | 0 |      1       |    0    |       1       |
| 1 | 1 |      0       |    0    |       1       |
| 1 | 1 |      1       |    1    |       1       |

### Explanation:
- **Sum Calculation:**
  - The sum of the three inputs is calculated using XOR gates.
  - `Sum = A ⊕ B ⊕ C`

- **Carry Calculation:**
  - The carry is generated based on combinations of inputs where at least two are `1`.
  - `Carry = (A ∧ B) ∨ (B ∧ C) ∨ (A ∧ C)`

### Working:
1. The first two bits are added using an XOR gate to produce the intermediate sum.
2. This intermediate sum is added to the carry-in using another XOR gate to produce the final sum.
3. The carry-out is generated using combinations of AND and OR gates:
   - If there is a carry, the final carry is generated by combining the intermediate carries with an OR gate.




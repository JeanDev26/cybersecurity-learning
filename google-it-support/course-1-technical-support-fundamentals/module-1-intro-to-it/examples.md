# 🧪 Examples — Module 1: Intro to IT

This file contains examples of number system conversions with step-by-step explanations.

---

## 1. Decimal → Binary (Division by 2 method)

**Rule:**  
- Divide the decimal number by 2.  
- Record the remainder (0 or 1).  
- Continue dividing the quotient until it becomes 0.  
- The binary result is the remainders read from bottom to top.

**Example:** 37 → ?  
- 37 ÷ 2 = 18 remainder 1  
- 18 ÷ 2 = 9  remainder 0  
- 9 ÷ 2  = 4  remainder 1  
- 4 ÷ 2  = 2  remainder 0  
- 2 ÷ 2  = 1  remainder 0  
- 1 ÷ 2  = 0  remainder 1  

Reading bottom to top → **100101**  

✅ 37₁₀ = 100101₂

---

## 2. Binary → Decimal (Sum of powers of 2)

**Rule:**  
- Each bit represents a power of 2.  
- Multiply each bit by its power and sum all results.

**Example:** 10010 → ?  
- Positions: 2⁴ 2³ 2² 2¹ 2⁰  
- Bits:      1   0   0   1   0  

Calculation: (1×16) + (0×8) + (0×4) + (1×2) + (0×1)  
= 16 + 0 + 0 + 2 + 0  
= **18**

✅ 10010₂ = 18₁₀

---

## 3. Decimal → Hexadecimal (Division by 16 method)

**Rule:**  
- Divide the decimal number by 16.  
- The remainder (0–15) is the hex digit.  
- Continue until quotient = 0.  
- Read remainders from bottom to top.

**Example:** 45 → ?  
- 45 ÷ 16 = 2 remainder 13 → D  
- 2 ÷ 16  = 0 remainder 2  

Reading bottom to top → **2D**

✅ 45₁₀ = 2D₁₆

---

## 4. Hexadecimal → Decimal (Sum of powers of 16)

**Rule:**  
- Each digit represents a power of 16.  
- Multiply each digit by its power and sum all results.  
- Digits above 9 are replaced with letters: A=10 … F=15.

**Example:** 1A → ?  
- Positions: 16¹, 16⁰  
- Digits: 1, A (10)  

Calculation: (1×16) + (10×1) = 16 + 10 = **26**

✅ 1A₁₆ = 26₁₀

---

## 5. Binary ↔ Hexadecimal (Nibble method)

**Rule:**  
- 1 hex digit = 4 binary bits.  
- Group binary into 4-bit blocks (nibbles) from right to left.  
- Convert each group directly.

**Example A — Bin → Hex:** 101011 → ?  
- Group: 0010 1011  
- Convert: 0010 = 2, 1011 = B  
= **2B**

✅ 101011₂ = 2B₁₆

**Example B — Hex → Bin:** 1A → ?  
- 1 = 0001  
- A (10) = 1010  
= 00011010 → **11010** (without leading zeros)

✅ 1A₁₆ = 11010₂

---

## 6. Quick Reference Table

| Decimal | Binary  | Hex |
|---------|---------|-----|
| 10      | 1010    | A   |
| 15      | 1111    | F   |
| 25      | 11001   | 19  |
| 45      | 101101  | 2D  |
| 50      | 110010  | 32  |
| 255     | 11111111| FF  |

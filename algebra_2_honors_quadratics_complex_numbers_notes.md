Unit 2

---

## 1. Factoring (Quadratic Expressions)

### 1.1. Always start with GCF (Greatest Common Factor)

**Example 1:** Factor

$$
6x^2 + 9x
$$

**Steps:**

1. **Find the GCF of all terms**

   - Coefficients: GCF of 6 and 9 is 3
   - Variables: smallest power of \(x\) is \(x^1\)\
     → GCF = \(3x\)

2. **Factor out the GCF**

   $$
   6x^2 + 9x = 3x(2x + 3)
   $$

✔ **Factored form:** \(\boxed{3x(2x+3)}\)

---

**Example 2:** Factor

$$
x^2 + 5x + 6
$$

**Steps:**

1. We want two numbers that:

   - **Multiply to** \(c = 6\)
   - **Add to** \(b = 5\)

2. List factor pairs of 6:

   - \(1 \cdot 6\) → sum 7
   - \(2 \cdot 3\) → sum 5 ✅

3. Write as two binomials:

   $$
   x^2 + 5x + 6 = (x + 2)(x + 3)
   $$

✔ **Factored form:** \(\boxed{(x+2)(x+3)}\)

---

**Example 3:** Factor

$$
6x^2 + 11x + 3
$$

**Steps (AC method):**

1. Compute \(a \cdot c = 6 \cdot 3 = 18\)

2. Find two numbers that:

   - Multiply to 18
   - Add to 11\
     → \(2\) and \(9\)

3. Rewrite middle term using 2 and 9:

   $$
   6x^2 + 2x + 9x + 3
   $$

4. Group terms:

   $$
   (6x^2 + 2x) + (9x + 3)
   $$

5. Factor each group:

   - \(6x^2 + 2x = 2x(3x + 1)\)
   - \(9x + 3 = 3(3x + 1)\)

6. Factor out common binomial:

   $$
   2x(3x+1) + 3(3x+1) = (3x+1)(2x+3)
   $$

✔ **Factored form:** \(\boxed{(3x+1)(2x+3)}\)

---

### 1.4. Difference of Squares

Pattern:

$$
a^2 - b^2 = (a - b)(a + b)
$$

**Example 4:** Factor

$$
9x^2 - 16
$$

**Steps:**

1. Recognize squares:

   - \(9x^2 = (3x)^2\)
   - \(16 = 4^2\)

2. Use pattern:

   $$
   9x^2 - 16 = (3x - 4)(3x + 4)
   $$

✔ \(\boxed{(3x-4)(3x+4)}\)

---

## 2. Solving Quadratic Equations by Factoring

**Core idea:**\
If \(ab = 0\), then \(a = 0\) or \(b = 0\). (Zero Product Property)

### Steps (general):

1. Move all terms to one side → set equation = 0.
2. Factor the quadratic expression.
3. Set each factor = 0.
4. Solve for \(x\).
5. (Optional but good practice) Check solutions in original equation.

---

**Example 1:**

$$
x^2 + 5x + 6 = 0
$$

1. Already = 0.
2. Factor: \((x+2)(x+3)=0\)
3. Set each factor to 0:
   - \(x+2=0 \Rightarrow x=-2\)
   - \(x+3=0 \Rightarrow x=-3\)

✔ Solutions: \(\boxed{x=-2,\;x=-3}\)

---

**Example 2:**

$$
2x^2 - 7x + 3 = 0
$$

1. Already = 0.

2. Factor (use AC method):

   - \(a\cdot c = 2\cdot 3 = 6\)
   - Need numbers multiply 6, add -7 → \(-1\) and \(-6\)
   - Rewrite: \(2x^2 - x - 6x + 3\)
   - Group: \((2x^2 - x) + (-6x + 3)\)
   - Factor: \(x(2x - 1) - 3(2x - 1) = (2x - 1)(x - 3)\)

3. Solve each factor:

   - \(2x - 1 = 0 \Rightarrow x = \frac{1}{2}\)
   - \(x - 3 = 0 \Rightarrow x = 3\)

✔ Solutions: \(\boxed{x=\frac{1}{2},\;x=3}\)

---

### Core definition

- \(i = \sqrt{-1}\)
- \(i^2 = -1\)

Any square root of a negative number can be written using \(i\).

$$
\sqrt{-a} = i\sqrt{a} \quad (a>0)
$$

---

$$
\sqrt{-25}
$$

1. Separate negative sign: \(\sqrt{-1\cdot 25}\)
2. Split radical: \(\sqrt{-1}\cdot\sqrt{25}=i\cdot 5=5i\)

✔ \(\boxed{\sqrt{-25}=5i}\)

---

1. Inside root: \(\sqrt{-12} = \sqrt{-1\cdot 4\cdot 3}= \sqrt{-1}\cdot\sqrt{4}\cdot\sqrt{3}=i\cdot 2\sqrt{3}=2i\sqrt{3}\)

2. There is a minus sign in front:\
   \(-\sqrt{-12} = -2i\sqrt{3}\)

✔ \(\boxed{-2i\sqrt{3}}\)

---

## 4. Solving Quadratic Equations by Completing the Square

Use when factoring is hard or to convert to vertex form.

Solve: \(x^2 + bx + c = 0\)

1. Move constant to right:
   $$
   x^2 + bx = -c
   $$
2. Take half of \(b\), square it: \(\left(\frac{b}{2}\right)^2\).
3. Add that square to **both sides**.
4. Left side becomes a perfect square:\
   \((x + \frac{b}{2})^2\)
5. Take square root of both sides (±).
6. Solve for \(x\).

---

### Example 1:

$$
x^2 + 6x - 7 = 0
$$

1. Move constant:

   $$
   x^2 + 6x = 7
   $$

2. Half of 6 is 3; square it → \(3^2=9\).

3. Add 9 to both sides:

   $$
   x^2 + 6x + 9 = 7 + 9
   $$

   $$
   x^2 + 6x + 9 = 16
   $$

4. Left side is a square:

   $$
   (x+3)^2 = 16
   $$

5. Square root both sides:

   $$
   x+3 = \pm 4
   $$

6. Solve:

   - \(x+3=4 \Rightarrow x=1\)
   - \(x+3=-4 \Rightarrow x=-7\)

✔ \(\boxed{x=1,\;x=-7}\)

---

$$
2x^2 - 8x + 3 = 0
$$

1. Move constant:

   $$
   2x^2 - 8x = -3
   $$

2. Factor out 2 from left side:

   $$
   2(x^2 - 4x) = -3
   $$

3. Divide both sides by 2:

   $$
   x^2 -4x = -\frac{3}{2}
   $$

4. Half of -4 is -2; square it → 4.

5. Add 4 to both sides:

   $$
   x^2 - 4x + 4 = -\frac{3}{2} + 4
   $$

   Compute right side:\
   \(4 = \frac{8}{2}\), so \(-\frac{3}{2} + \frac{8}{2} = \frac{5}{2}\)

   So:

   $$
   x^2 - 4x + 4 = \frac{5}{2}
   $$

6. Left side is a square:

   $$
   (x-2)^2 = \frac{5}{2}
   $$

7. Take square root:

   $$
   x-2 = \pm \sqrt{\frac{5}{2}}
   $$

8. Solve:

   $$
   x = 2 \pm \sqrt{\frac{5}{2}}
   $$

You can also rationalize if desired, but this is already fine.

✔ \(\boxed{x=2\pm \sqrt{\frac{5}{2}}}\)

---

## 5. Performing Operations on Complex Numbers

General form: \(a+bi\), where \(a\) is real part, \(b\) is imaginary part.

---

### 5.1. Addition & Subtraction

Just combine like terms.

**Example:**

$$
(3+5i) + (2 - 7i)
$$

1. Combine real parts: \(3+2=5\)
2. Combine imaginary parts: \(5i + (-7i) = -2i\)

✔ \(\boxed{5 - 2i}\)

---

### 5.2. Multiplication (FOIL)

**Example:**

$$
(2+3i)(4 - i)
$$

1. FOIL:

   - First: \(2\cdot 4 = 8\)
   - Outer: \(2\cdot (-i) = -2i\)
   - Inner: \(3i\cdot 4 = 12i\)
   - Last: \(3i\cdot (-i) = -3i^2\)

2. Combine:

   $$
   8 -2i + 12i - 3i^2 = 8 + 10i - 3i^2
   $$

3. Replace \(i^2\) with \(-1\):

   $$
   -3i^2 = -3(-1)=3
   $$

4. So total:

   $$
   8 + 10i + 3 = 11 + 10i
   $$

✔ \(\boxed{11 + 10i}\)

---

### 5.3. Division (use conjugate)

To divide by \(a+bi\), multiply top and bottom by its **conjugate** \(a-bi\).

**Example:**

$$
\frac{5 + 2i}{1 - 3i}
$$

1. Multiply numerator and denominator by conjugate of denominator: \(1+3i\).

   $$
   \frac{5+2i}{1-3i}\cdot\frac{1+3i}{1+3i}
   $$

2. Numerator: \((5+2i)(1+3i)\)

   - \(5\cdot 1 = 5\)
   - \(5\cdot 3i = 15i\)
   - \(2i\cdot 1 = 2i\)
   - \(2i\cdot 3i = 6i^2\)

   Combine:

   $$
   5 + 15i + 2i + 6i^2 = 5 + 17i + 6i^2
   $$

   Replace \(i^2=-1\): \(6i^2 = -6\)\
   So: \(5 + 17i -6 = -1 + 17i\)

3. Denominator: \((1 - 3i)(1 + 3i) = 1^2 - (3i)^2 = 1 - 9i^2\)\
   Replace \(i^2=-1\): \(1 - 9(-1) = 1+9=10\)

4. So:

   $$
   \frac{-1 + 17i}{10} = -\frac{1}{10} + \frac{17}{10}i
   $$

✔ \(\boxed{-\frac{1}{10} + \frac{17}{10}i}\)

---

## 6. Solving Quadratic Equations Using the Quadratic Formula

For any quadratic:

$$
ax^2 + bx + c = 0
$$

**Quadratic Formula:**

$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

---

### Example 1 (nice roots):

$$
2x^2 - 7x + 3 = 0
$$

1. Identify \(a=2,\;b=-7,\;c=3\).

2. Compute discriminant \(D = b^2 - 4ac\):

   $$
   D = (-7)^2 - 4(2)(3) = 49 - 24 = 25
   $$

3. Plug into formula:

   $$
   x = \frac{-(-7)\pm\sqrt{25}}{2\cdot 2}
      = \frac{7 \pm 5}{4}
   $$

4. Two solutions:

   - \(x = \frac{7+5}{4} = \frac{12}{4} = 3\)
   - \(x = \frac{7-5}{4} = \frac{2}{4} = \frac{1}{2}\)

✔ \(\boxed{x=3,\;x=\frac{1}{2}}\)

---

### Example 2 (irrational roots):

$$
x^2 - 4x - 1 = 0
$$

1. \(a=1,\;b=-4,\;c=-1\)

2. \(D = (-4)^2 - 4(1)(-1) = 16 + 4 = 20\)

3. Formula:

   $$
   x = \frac{-(-4)\pm\sqrt{20}}{2\cdot 1}
      = \frac{4 \pm \sqrt{20}}{2}
   $$

4. Simplify \(\sqrt{20} = \sqrt{4\cdot 5}=2\sqrt{5}\):

   $$
   x = \frac{4 \pm 2\sqrt{5}}{2} = 2 \pm \sqrt{5}
   $$

✔ \(\boxed{x=2\pm \sqrt{5}}\)

---

## 7. Analyzing the Discriminant

**Discriminant:** \(D = b^2 - 4ac\)

- If \(D > 0\): **two real solutions**
  - If \(D\) is a perfect square → two distinct **rational** solutions
  - If not → two distinct **irrational** solutions
- If \(D = 0\): **one real solution** (a repeated root)
- If \(D < 0\): **two complex conjugate** solutions (no real solutions)

---

### Example 1:

$$
x^2 - 6x + 9 = 0
$$

1. \(a=1,\;b=-6,\;c=9\)
2. \(D = (-6)^2 - 4(1)(9) = 36 - 36 = 0\)

→ **One real repeated root**.

---

### Example 2:

$$
3x^2 + 2x + 5 = 0
$$

1. \(a=3,\;b=2,\;c=5\)
2. \(D = 2^2 - 4(3)(5) = 4 - 60 = -56\)

→ \(D<0\): **Two complex conjugate solutions**, no real solutions.

---

### Example 3:

$$
x^2 - 3x - 4 = 0
$$

1. \(a=1,\;b=-3,\;c=-4\)
2. \(D = (-3)^2 - 4(1)(-4) = 9 + 16 = 25\)

25 is a perfect square → **two distinct rational solutions**.

---

## 8. Solving Real-Life Problems Using Quadratics

We’ll do a **projectile (velocity)** type and one **geometry** example.

---

### 8.1. Projectile motion (height vs time)

In feet (US), a typical model:

$$
h(t) = -16t^2 + v_0 t + h_0
$$

where:

- \(h(t)\) = height (feet)
- \(t\) = time (seconds)
- \(v_0\) = initial velocity (ft/s)
- \(h_0\) = initial height (feet)

---

**Example:**\
A ball is thrown upward from a 5-ft platform with initial velocity \(v_0 = 32\,\text{ft/s}\). Its height is:

$$
h(t) = -16t^2 + 32t + 5
$$

**(a) When will it hit the ground? (height 0)**\
**(b) What is its maximum height?**

---

$$
-16t^2 + 32t + 5 = 0
$$

Use quadratic formula with \(a=-16,\;b=32,\;c=5\).

1. Discriminant:

   $$
   D = 32^2 - 4(-16)(5)
   $$

   \(32^2 = 1024\)\
   \(4 \cdot (-16) \cdot 5 = -320\)\
   So \(D = 1024 - (-320) = 1024 + 320 = 1344\)

2. Formula:

   $$
   t = \frac{-32 \pm \sqrt{1344}}{2(-16)} = \frac{-32 \pm \sqrt{1344}}{-32}
   $$

   We only care about the **positive** time.\
   Note: \(\sqrt{1344} \approx 36.66\)

   - With “+”:
     $$
     t = \frac{-32 + 36.66}{-32} \approx \frac{4.66}{-32} \approx -0.146\ \text{(discard, negative time)}
     $$
   - With “−”:
     $$
     t = \frac{-32 - 36.66}{-32} \approx \frac{-68.66}{-32} \approx 2.145
     $$

So ball hits ground at about\
✔ \(\boxed{t \approx 2.15\text{ seconds}}\)

---

#### (b) Maximum height → use vertex

For a quadratic \(h(t) = at^2 + bt + c\), the time of the vertex is:

$$
t_{\text{vertex}} = -\frac{b}{2a}
$$

Here, \(a=-16,\;b=32\).

1. Time at peak:

   $$
   t = -\frac{32}{2(-16)} = -\frac{32}{-32} = 1
   $$

2. Plug \(t=1\) into \(h(t)\):

   $$
   h(1) = -16(1)^2 + 32(1) + 5 = -16 + 32 + 5 = 21
   $$

✔ Maximum height is \(\boxed{21\ \text{feet}}\), occurring at \(t=1\) second.

---

### 8.2. Geometry/Area Example

**Example:**\
The area of a rectangle is 48 square meters. The length is 4 meters more than the width. Find the dimensions.

1. Let width be \(w\).\
   Then length is \(w + 4\).

2. Area equation:

   $$
   w(w + 4) = 48
   $$

3. Multiply out:

   $$
   w^2 + 4w - 48 = 0
   $$

4. Factor: we want numbers that multiply to \(-48\) and add to 4 → \(8\) and \(-6\).

   $$
   (w + 8)(w - 6) = 0
   $$

5. Solve:

   - \(w+8=0 \Rightarrow w=-8\) (reject, width can’t be negative)
   - \(w-6=0 \Rightarrow w=6\)

6. Length: \(w + 4 = 10\)

✔ Width = \(\boxed{6\ \text{m}}\), Length = \(\boxed{10\ \text{m}}\)


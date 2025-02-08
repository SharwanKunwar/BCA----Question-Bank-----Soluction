# Derivative of Trigonometric Functions

## Introduction
This document covers the derivatives of basic trigonometric functions using the **first principle of differentiation**. It includes key formulas, proofs, and practical applications.

---
## **Basic Derivative Formulas**

1. \( \frac{d}{dx} \sin x = \cos x \)
2. \( \frac{d}{dx} \cos x = -\sin x \)
3. \( \frac{d}{dx} \tan x = \sec^2 x \)
4. \( \frac{d}{dx} \cot x = -\csc^2 x \)
5. \( \frac{d}{dx} \sec x = \sec x \tan x \)
6. \( \frac{d}{dx} \csc x = -\csc x \cot x \)

---
## **First Principle of Differentiation**

The derivative of a function \( f(x) \) is given by:

\[ \frac{d}{dx} f(x) = \lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x} \]

### **Example: Derivative of \( \sin x \) Using First Principle**

Using the identity:  
\[ \sin(A) - \sin(B) = 2 \cos\left(\frac{A+B}{2}\right) \sin\left(\frac{A-B}{2}\right) \]

\[ \frac{d}{dx} \sin x = \lim_{\Delta x \to 0} \frac{\sin (x + \Delta x) - \sin x}{\Delta x} \]

Expanding using the identity:

\[ \sin(x + \Delta x) - \sin x = 2 \cos\left(x + \frac{\Delta x}{2}\right) \sin \left(\frac{\Delta x}{2}\right) \]

Dividing by \( \Delta x \):

\[ \frac{d}{dx} \sin x = \lim_{\Delta x \to 0} 2 \cos \left(x + \frac{\Delta x}{2}\right) \cdot \frac{\sin(\Delta x / 2)}{\Delta x} \]

Using \( \lim_{\theta \to 0} \frac{\sin \theta}{\theta} = 1 \), we get:

\[ \frac{d}{dx} \sin x = \cos x \]

✅ **Proven!**

---
## **Must-Know Identities for Proofs**

1. \( \lim_{\theta \to 0} \frac{\sin \theta}{\theta} = 1 \)
2. \( \sin C + \sin D = 2 \sin\left(\frac{C+D}{2}\right) \cos\left(\frac{C-D}{2}\right) \)
3. \( \sin C - \sin D = 2 \cos\left(\frac{C+D}{2}\right) \sin\left(\frac{C-D}{2}\right) \)
4. \( \cos C + \cos D = 2 \cos\left(\frac{C+D}{2}\right) \cos\left(\frac{C-D}{2}\right) \)
5. \( \cos C - \cos D = -2 \sin\left(\frac{C+D}{2}\right) \sin\left(\frac{C-D}{2}\right) \)

---
## **Conclusion**
This document provides a structured way to understand derivatives of trigonometric functions using first principles. These concepts are crucial for calculus and higher mathematics.

📌 **Happy Learning!** 🚀


# Path Intersection / Yol Kesişimi

**[EN]** We need to determine if Alice and Bob collide (reach the same point at the same time). If they do not, we must find the minimum distance between them.
**[TR]** Alice ve Bob'un çarpışıp çarpışmadığını (aynı anda aynı noktaya ulaşıp ulaşmadıklarını) belirlememiz gerekiyor. Eğer çarpışmıyorlarsa, aralarındaki minimum mesafeyi bulmalıyız.

* **Alice:** $A(t) = (2+t, 8-3t)$
* **Bob:** $B(t) = (2t-1, 2t+2)$

---

### Step 1: Check for Collision / Adım 1: Çarpışma Kontrolü
**[EN]** For a collision, their X and Y coordinates must be exactly the same at the exact same time ($t$). First, let's set their X coordinates equal to find the time.
**[TR]** Bir çarpışma olması için, X ve Y koordinatlarının tam olarak aynı anda ($t$) birebir aynı olması gerekir. Önce zamanı bulmak için X koordinatlarını birbirine eşitleyelim.

$$2 + t = 2t - 1$$
$$t = 3$$

**[EN]** Now, we check their Y coordinates at $t = 3$.
**[TR]** Şimdi, $t = 3$ anındaki Y koordinatlarını kontrol edelim.

* **Alice's Y:** $8 - 3(3) = -1$
* **Bob's Y:** $2(3) + 2 = 8$

**[EN]** Since $-1 \neq 8$, they are not at the same place at the same time. **They do not collide.**
**[TR]** $-1 \neq 8$ olduğundan, aynı anda aynı yerde değillerdir. **Çarpışmazlar.**

### Step 2: Distance Formula / Adım 2: Mesafe Formülü
**[EN]** Since they don't collide, we use the distance formula to find the gap between them at any given time $t$. We will calculate the square of the distance ($D^2$) to make the math simpler.
**[TR]** Çarpışmadıkları için, herhangi bir $t$ anında aralarındaki boşluğu bulmak için mesafe formülünü kullanırız. Matematiği basitleştirmek için mesafenin karesini ($D^2$) hesaplayacağız.

* **X Difference:** $(2t - 1) - (2 + t) = t - 3$
* **Y Difference:** $(2t + 2) - (8 - 3t) = 5t - 6$

$$D^2 = (t - 3)^2 + (5t - 6)^2$$
$$D^2 = (t^2 - 6t + 9) + (25t^2 - 60t + 36)$$
$$D^2 = 26t^2 - 66t + 45$$

### Step 3: Find the Minimum Distance / Adım 3: Minimum Mesafeyi Bulma
**[EN]** This creates a parabola (U-shape). To find the lowest point (minimum distance), we use the vertex formula: $t = \frac{-b}{2a}$.
**[TR]** Bu bir parabol (U şekli) oluşturur. En alt noktayı (minimum mesafeyi) bulmak için tepe noktası formülünü kullanırız: $t = \frac{-b}{2a}$.

$$t = \frac{-(-66)}{2 \times 26} = \frac{66}{52} = \frac{33}{26} \approx 1.27$$

**[EN]** The minimum distance occurs at exactly $t = \frac{33}{26}$. Now, we plug this time back into the distance equation.
**[TR]** Minimum mesafe tam olarak $t = \frac{33}{26}$ anında gerçekleşir. Şimdi bu zamanı mesafe denklemine geri yerleştiriyoruz.

$$D^2 = 26\left(\frac{33}{26}\right)^2 - 66\left(\frac{33}{26}\right) + 45$$
$$D^2 = \frac{81}{26}$$

**[EN]** Finally, take the square root to find the actual distance.
**[TR]** Son olarak, gerçek mesafeyi bulmak için karekökü alın.

$$D = \sqrt{\frac{81}{26}} = \frac{9}{\sqrt{26}} \approx 1.76$$

**[EN]** **Conclusion:** The minimum distance between Alice and Bob is approximately **1.76 units**, and it occurs at $t \approx 1.27$.
**[TR]** **Sonuç:** Alice ve Bob arasındaki minimum mesafe yaklaşık **1.76 birimdir** ve $t \approx 1.27$ anında gerçekleşir.

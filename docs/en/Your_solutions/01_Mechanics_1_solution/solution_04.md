# Vector Calculus: Velocity and Acceleration / Vektör Kalkülüsü: Hız ve İvme

**[EN]** The position of an object is given by the vector $\vec{r}(t)$. We need to find its velocity ($\vec{v}(t)$) and acceleration ($\vec{a}(t)$) vectors as a function of time.
**[TR]** Bir nesnenin konumu $\vec{r}(t)$ vektörü ile verilmiştir. Zamana bağlı hız ($\vec{v}(t)$) ve ivme ($\vec{a}(t)$) vektörlerini bulmamız gerekiyor.

$$\vec{r}(t) = (3t^2)\hat{i} + (5t - 8t^2)\hat{j}$$

---

### Step 1: Find the Velocity Vector / Adım 1: Hız Vektörünü Bulun
**[EN]** Velocity is the rate of change of position. To find the velocity vector, we take the first derivative of the position vector with respect to time ($t$). We apply the power rule: multiply by the exponent and decrease the exponent by one.
**[TR]** Hız, konumun değişim oranıdır. Hız vektörünü bulmak için konum vektörünün zamana ($t$) göre birinci türevini alırız. Üs kuralını uygularız: üs ile çarpıp üssü bir azaltırız.

* **For the $\hat{i}$ component:** The derivative of $3t^2$ is $6t$. / **$\hat{i}$ bileşeni için:** $3t^2$'nin türevi $6t$'dir.
* **For the $\hat{j}$ component:** The derivative of $5t - 8t^2$ is $5 - 16t$. / **$\hat{j}$ bileşeni için:** $5t - 8t^2$'nin türevi $5 - 16t$'dir.

$$\vec{v}(t) = \frac{d\vec{r}}{dt} = (6t)\hat{i} + (5 - 16t)\hat{j}$$

### Step 2: Find the Acceleration Vector / Adım 2: İvme Vektörünü Bulun
**[EN]** Acceleration is the rate of change of velocity. To find it, we take the derivative of the velocity vector with respect to time ($t$).
**[TR]** İvme, hızın değişim oranıdır. Bunu bulmak için hız vektörünün zamana ($t$) göre türevini alırız.

* **For the $\hat{i}$ component:** The derivative of $6t$ is $6$. / **$\hat{i}$ bileşeni için:** $6t$'nin türevi $6$'dır.
* **For the $\hat{j}$ component:** The derivative of $5 - 16t$ is $-16$. / **$\hat{j}$ bileşeni için:** $5 - 16t$'nin türevi $-16$'dır.

$$\vec{a}(t) = \frac{d\vec{v}}{dt} = 6\hat{i} - 16\hat{j}$$

---

### Final Result / Kesin Sonuç
* **[EN] Velocity Vector:** $\vec{v}(t) = (6t)\hat{i} + (5 - 16t)\hat{j}$
* **[TR] Hız Vektörü:** $\vec{v}(t) = (6t)\hat{i} + (5 - 16t)\hat{j}$
* **[EN] Acceleration Vector:** $\vec{a}(t) = 6\hat{i} - 16\hat{j}$
* **[TR] İvme Vektörü:** $\vec{a}(t) = 6\hat{i} - 16\hat{j}$

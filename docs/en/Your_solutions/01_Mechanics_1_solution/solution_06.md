# Variable Velocity: Position and Acceleration / Değişken Hız: Konum ve İvme

**[EN]** An object's velocity is given by the function $v(t) = t^2 + 2t - 5$. We know its initial position is $x = 4$ at $t = 0$. We need to find its acceleration and position at time $t = 3$.
**[TR]** Bir cismin hızı $v(t) = t^2 + 2t - 5$ fonksiyonu ile verilmiştir. $t = 0$ anındaki ilk konumunun $x = 4$ olduğunu biliyoruz. $t = 3$ anındaki ivmesini ve konumunu bulmamız gerekiyor.

---

### Step 1: Find Acceleration / Adım 1: İvmeyi Bulun
**[EN]** Acceleration ($a$) is the derivative of velocity ($v$) with respect to time ($t$). We take the first derivative of the given velocity function and then evaluate it at $t = 3$.
**[TR]** İvme ($a$), hızın ($v$) zamana ($t$) göre türevidir. Verilen hız fonksiyonunun birinci türevini alırız ve ardından $t = 3$ için hesaplarız.

$$a(t) = \frac{dv}{dt} = 2t + 2$$
$$a(3) = 2(3) + 2 = 6 + 2 = 8$$

**[EN]** The acceleration at $t = 3$ is **8 units**.
**[TR]** $t = 3$ anındaki ivme **8 birimdir**.

### Step 2: Find the Position Function / Adım 2: Konum Fonksiyonunu Bulun
**[EN]** Position ($x$) is the integral of velocity ($v$) with respect to time ($t$). We integrate the velocity function to find the general position function, which includes a constant of integration ($C$).
**[TR]** Konum ($x$), hızın ($v$) zamana ($t$) göre integralidir. Bir integral sabiti ($C$) içeren genel konum fonksiyonunu bulmak için hız fonksiyonunun integralini alırız.

$$x(t) = \int (t^2 + 2t - 5) \,dt$$
$$x(t) = \frac{t^3}{3} + t^2 - 5t + C$$

### Step 3: Find the Constant and Final Position / Adım 3: Sabiti ve Nihai Konumu Bulun
**[EN]** We use the initial condition ($x = 4$ when $t = 0$) to find $C$.
**[TR]** $C$'yi bulmak için başlangıç koşulunu ($t = 0$ iken $x = 4$) kullanırız.

$$x(0) = \frac{0^3}{3} + 0^2 - 5(0) + C = 4 \implies C = 4$$

**[EN]** Now we have the exact position function. We evaluate this function at $t = 3$.
**[TR]** Artık kesin konum fonksiyonuna sahibiz. Bu fonksiyonu $t = 3$ için hesaplıyoruz.

$$x(t) = \frac{t^3}{3} + t^2 - 5t + 4$$
$$x(3) = \frac{3^3}{3} + 3^2 - 5(3) + 4$$
$$x(3) = \frac{27}{3} + 9 - 15 + 4$$
$$x(3) = 9 + 9 - 15 + 4 = 7$$

**[EN]** The position at $t = 3$ is **7 units**.
**[TR]** $t = 3$ anındaki konum **7 birimdir**.

---

### Final Result / Kesin Sonuç
* **[EN] Acceleration at $t=3$:** $8$
* **[TR] $t=3$ anındaki İvme:** $8$
* **[EN] Position at $t=3$:** $7$
* **[TR] $t=3$ anındaki Konum:** $7$

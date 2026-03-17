# Kinematics: Elimination of Time and Acceleration / Kinematik: Zamanın Yok Edilmesi ve İvme

**[EN]** The path of an object is given by the parametric equations $x(t) = 2t^2$ and $y(t) = 3t^3$. We need to eliminate the parameter $t$, find the velocity and acceleration vectors, their magnitudes, and determine if the acceleration is constant.
**[TR]** Bir cismin yolu $x(t) = 2t^2$ ve $y(t) = 3t^3$ parametrik denklemleriyle verilmiştir. $t$ parametresini yok etmemiz, hız ve ivme vektörlerini, bunların büyüklüklerini bulmamız ve ivmenin sabit olup olmadığını belirlememiz gerekiyor.

---

### Step 1: Eliminate the parameter $t$ / Adım 1: $t$ parametresini yok edin
**[EN]** We solve for $t$ in the $x$ equation and substitute it into the $y$ equation.
**[TR]** $x$ denkleminde $t$'yi yalnız bırakırız ve onu $y$ denkleminde yerine yazarız.

$$x = 2t^2 \implies t^2 = \frac{x}{2}$$

**[EN]** To substitute easily, we can square the $y$ equation:
**[TR]** Kolayca yerine koymak için $y$ denkleminin karesini alabiliriz:

$$y = 3t^3 \implies y^2 = 9t^6$$
$$y^2 = 9(t^2)^3$$

**[EN]** Now substitute $t^2 = \frac{x}{2}$:
**[TR]** Şimdi $t^2 = \frac{x}{2}$ ifadesini yerine koyalım:

$$y^2 = 9\left(\frac{x}{2}\right)^3 = 9\left(\frac{x^3}{8}\right)$$
$$y^2 = \frac{9}{8}x^3$$

**[EN]** This equation ($y^2 = \frac{9}{8}x^3$) represents the trajectory (a semi-cubical parabola) in the $x-y$ plane.
**[TR]** Bu denklem ($y^2 = \frac{9}{8}x^3$), $x-y$ düzlemindeki yörüngeyi (yarı kübik parabol) temsil eder.

### Step 2: Calculate Velocity / Adım 2: Hızı Hesaplayın
**[EN]** Velocity $\vec{v}(t)$ is the first derivative of the position vector $\vec{r}(t) = x(t)\hat{i} + y(t)\hat{j}$.
**[TR]** Hız $\vec{v}(t)$, konum vektörünün $\vec{r}(t) = x(t)\hat{i} + y(t)\hat{j}$ birinci türevidir.

$$\vec{v}(t) = \frac{dx}{dt}\hat{i} + \frac{dy}{dt}\hat{j}$$
$$\vec{v}(t) = (4t)\hat{i} + (9t^2)\hat{j}$$

**[EN]** The magnitude of velocity $|\vec{v}(t)|$:
**[TR]** Hızın büyüklüğü $|\vec{v}(t)|$:

$$|\vec{v}(t)| = \sqrt{(4t)^2 + (9t^2)^2} = \sqrt{16t^2 + 81t^4}$$

### Step 3: Calculate Acceleration / Adım 3: İvmeyi Hesaplayın
**[EN]** Acceleration $\vec{a}(t)$ is the derivative of the velocity vector.
**[TR]** İvme $\vec{a}(t)$, hız vektörünün türevidir.

$$\vec{a}(t) = \frac{d\vec{v}}{dt} = 4\hat{i} + 18t\hat{j}$$

**[EN]** The magnitude of acceleration $|\vec{a}(t)|$:
**[TR]** İvmenin büyüklüğü $|\vec{a}(t)|$:

$$|\vec{a}(t)| = \sqrt{4^2 + (18t)^2} = \sqrt{16 + 324t^2}$$

### Step 4: Is the acceleration constant? / Adım 4: İvme sabit mi?
**[EN]** Look at the acceleration vector: $\vec{a}(t) = 4\hat{i} + 18t\hat{j}$. The $\hat{j}$ component contains the variable $t$. This means the acceleration changes as time passes. Therefore, **the acceleration is NOT constant.**
**[TR]** İvme vektörüne bakın: $\vec{a}(t) = 4\hat{i} + 18t\hat{j}$. $\hat{j}$ bileşeni $t$ değişkenini içerir. Bu, zaman geçtikçe ivmenin değiştiği anlamına gelir. Bu nedenle, **ivme sabit DEĞİLDİR.**

<img width="474" height="405" alt="image" src="https://github.com/user-attachments/assets/05328476-a9f9-487f-9f7a-5e13ee423b52" />


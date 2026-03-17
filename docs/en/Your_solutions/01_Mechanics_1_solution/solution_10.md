# Kinematics: 3D Trajectory and Path Length / Kinematik: 3D Yörünge ve Yol Uzunluğu

**[EN]** Point M moves according to the position vector $\vec{r}(t) = (a\cos(\omega t), b\sin(\omega t), bt)$, where $a, b, \omega$ are positive constants.
**[TR]** M noktası, $a, b, \omega$ pozitif sabitler olmak üzere $\vec{r}(t) = (a\cos(\omega t), b\sin(\omega t), bt)$ konum vektörüne göre hareket etmektedir.

---

### a) Equation of the Trajectory / a) Yörünge Denklemi
**[EN]** To find the trajectory's equation, we eliminate the parameter $t$ from the $x$ and $y$ coordinates.
**[TR]** Yörüngenin denklemini bulmak için $x$ ve $y$ koordinatlarındaki $t$ parametresini yok ederiz.

$$x = a\cos(\omega t) \implies \frac{x}{a} = \cos(\omega t)$$
$$y = b\sin(\omega t) \implies \frac{y}{b} = \sin(\omega t)$$

**[EN]** Squaring and adding these two equations:
**[TR]** Bu iki denklemin karesini alıp toplarsak:

$$\left(\frac{x}{a}\right)^2 + \left(\frac{y}{b}\right)^2 = \cos^2(\omega t) + \sin^2(\omega t) = 1$$

**[EN]** **Result:** The trajectory lies on the surface of an elliptical cylinder $\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1$. Since $z = bt$, the point moves upwards at a constant rate. The resulting 3D curve is an **elliptical helix**.
**[TR]** **Sonuç:** Yörünge, $\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1$ eliptik silindirinin yüzeyi üzerindedir. $z = bt$ olduğundan, nokta sabit bir hızla yukarı doğru hareket eder. Ortaya çıkan 3 boyutlu eğri bir **eliptik sarmaldır** (helis).

### b) Path Length from $t=0$ to $t=t_0$ / b) $t=0$'dan $t=t_0$'a Yol Uzunluğu
**[EN]** The path length ($s$) is the integral of the magnitude of the velocity vector over time. First, find the velocity vector $\vec{v}(t)$ by taking the derivative of $\vec{r}(t)$.
**[TR]** Yol uzunluğu ($s$), hız vektörünün büyüklüğünün zamana göre integralidir. Önce $\vec{r}(t)$'nin türevini alarak hız vektörünü ($\vec{v}(t)$) bulalım.

$$\vec{v}(t) = \frac{d\vec{r}}{dt} = (-a\omega\sin(\omega t), b\omega\cos(\omega t), b)$$

**[EN]** Calculate the magnitude of the velocity vector $|\vec{v}(t)|$:
**[TR]** Hız vektörünün büyüklüğünü $|\vec{v}(t)|$ hesaplayın:

$$|\vec{v}(t)| = \sqrt{(-a\omega\sin(\omega t))^2 + (b\omega\cos(\omega t))^2 + b^2}$$
$$|\vec{v}(t)| = \sqrt{a^2\omega^2\sin^2(\omega t) + b^2\omega^2\cos^2(\omega t) + b^2}$$

**[EN]** The path length is the integral of this expression. Generally, this yields an elliptic integral:
**[TR]** Yol uzunluğu bu ifadenin integralidir. Genel olarak bu, eliptik bir integral verir:

$$s = \int_{0}^{t_0} \sqrt{a^2\omega^2\sin^2(\omega t) + b^2\omega^2\cos^2(\omega t) + b^2} \, dt$$

### c) Special Cases / c) Özel Durumlar
**[EN]** If we assume the special case where **$a = b$**:
1. The base cylinder becomes a perfect circle: $x^2 + y^2 = a^2$. The trajectory becomes a standard **circular helix**.
2. The path length integral simplifies drastically because $a^2\omega^2(\sin^2(\omega t) + \cos^2(\omega t)) = a^2\omega^2$.
**[TR]** **$a = b$** şeklindeki özel durumu varsayarsak:
1. Taban silindiri mükemmel bir çembere dönüşür: $x^2 + y^2 = a^2$. Yörünge standart bir **dairesel sarmala** dönüşür.
2. Yol uzunluğu integrali büyük ölçüde basitleşir çünkü $a^2\omega^2(\sin^2(\omega t) + \cos^2(\omega t)) = a^2\omega^2$.

**[EN]** Path length for special case $a=b$:
**[TR]** $a=b$ özel durumu için yol uzunluğu:

$$s = \int_{0}^{t_0} \sqrt{a^2\omega^2 + b^2} \, dt = t_0 \sqrt{a^2\omega^2 + b^2}$$

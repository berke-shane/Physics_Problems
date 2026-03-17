# Projectile Launch Operation / Fırlatma Operasyonu



**[EN]** We are launching a payload. Our launch speed is **100 m/s** and the angle is **37°**. To map this operation perfectly, we need to understand the basic forces acting on it. *(Note: For our calculations, we use sine 0.6, cosine 0.8, and gravity 9.8)*.
**[TR]** Bir yük fırlatıyoruz. Fırlatma hızımız **100 m/s** ve açımız **37°**. Bu operasyonu kusursuz bir şekilde haritalandırmak için ona etki eden temel kuvvetleri anlamamız gerekiyor. *(Not: Hesaplamalarımız için sinüs 0.6, kosinüs 0.8 ve yerçekimini 9.8 alıyoruz)*.

---

### 1. The Blueprint (Differential Equations) / Temel Plan (Diferansiyel Denklemler)
**[EN]** What forces are pushing or pulling our payload in the air?
* **Horizontal:** No air resistance, so nothing pushes it back. Acceleration is zero.
* **Vertical:** Gravity is constantly pulling it down.
**[TR]** Havadaki yükümüzü hangi kuvvetler itiyor veya çekiyor?
* **Yatay:** Hava direnci yok, bu yüzden onu geriye iten hiçbir şey yok. İvme sıfırdır.
* **Dikey:** Yerçekimi onu sürekli aşağı çekiyor.

$$\frac{d^2x}{dt^2} = 0$$
$$\frac{d^2y}{dt^2} = -g$$

### 2. Initial Setup / İlk Kurulum
**[EN]** We split this angled launch into two simple, straight directions.
**[TR]** Bu açılı fırlatmayı iki basit, düz yöne ayırıyoruz.

* **[EN] Horizontal Speed (Forward):** 100 × 0.8 = **80 m/s** | **[TR] Yatay Hız (İleri):** 100 × 0.8 = **80 m/s**
* **[EN] Vertical Speed (Up):** 100 × 0.6 = **60 m/s** | **[TR] Dikey Hız (Yukarı):** 100 × 0.6 = **60 m/s**

### 3. Time of Flight / Uçuş Süresi
**[EN]** Gravity pulls the vertical speed down by 9.8 every second.
**[TR]** Yerçekimi dikey hızı her saniye 9.8 oranında yavaşlatır.

$$T = \frac{2 v_{0y}}{g}$$
$$T = \frac{2 \times 60}{9.8} \approx 12.24 \text{ s}$$

### 4. Maximum Height / Maksimum Yükseklik
**[EN]** How high does it go before it starts falling back down?
**[TR]** Tekrar aşağı düşmeye başlamadan önce ne kadar yükseğe çıkıyor?

$$H = \frac{v_{0y}^2}{2g}$$
$$H = \frac{60^2}{2 \times 9.8} = \frac{3600}{19.6} \approx 183.67 \text{ m}$$

### 5. Range / Menzil
**[EN]** Where does it finally land? We multiply our forward speed by the total time in the air.
**[TR]** Sonunda nereye iniyor? Sadece ileri doğru hızımızı havadaki toplam süreyle çarpıyoruz.

$$R = v_{0x} \times T$$
$$R = 80 \times 12.24 = 979.2 \text{ m}$$

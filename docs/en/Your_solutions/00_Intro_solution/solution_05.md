# Vector Components / Vektör Bileşenleri



**[EN]** Imagine intercepting a signal from a secure server. You point your directional antenna up at a **60° angle**, and the signal's distance is **15**. To map it, we need to find out how far across the ground it goes (horizontal) and how high up the wall it reaches (vertical).
**[TR]** Güvenli bir sunucudan gelen sinyali yakaladığınızı hayal edin. Yönlü anteninizi **60° açıyla** yukarı yönlendiriyorsunuz ve sinyalin mesafesi **15**. Bunu haritalandırmak için sinyalin yerde ne kadar uzağa gittiğini (yatay) ve duvarda ne kadar yükseğe ulaştığını (dikey) bulmamız gerekiyor.

---

### 1. The Horizontal Part (Across) / Yatay Kısım (İleriye Doğru)
**[EN]** To find out how far across the signal goes, we use the cosine function. Think of it as the shadow the signal casts on the ground.
**[TR]** Sinyalin ileriye doğru ne kadar uzağa gittiğini bulmak için kosinüs fonksiyonunu kullanırız. Bunu sinyalin yere düşen gölgesi gibi düşünebilirsiniz.

$$A_x = 15 \times \cos(60^\circ)$$

**[EN]** The cosine of 60° is exactly 0.5. 
**[TR]** 60°'nin kosinüsü tam olarak 0.5'tir.

$$A_x = 15 \times 0.5 = 7.5$$

### 2. The Vertical Part (Up) / Dikey Kısım (Yukarı Doğru)
**[EN]** To find out how high up the signal reaches, we use the sine function. Think of it as measuring how much the signal goes straight up the wall.
**[TR]** Sinyalin ne kadar yükseğe ulaştığını bulmak için sinüs fonksiyonunu kullanırız. Bunu sinyalin duvarda doğrudan ne kadar yukarı çıktığını ölçmek gibi düşünebilirsiniz.

$$A_y = 15 \times \sin(60^\circ)$$

**[EN]** The sine of 60° is roughly 0.866.
**[TR]** 60°'nin sinüsü yaklaşık 0.866'dır.

$$A_y = 15 \times 0.866 \approx 12.99$$

---

### Final Blueprint / Nihai Plan
* **[EN] Horizontal:** 7.5 | **[TR] Yatay:** 7.5
* **[EN] Vertical:** 12.99 | **[TR] Dikey:** 12.99

# Range Optimization / Menzil Optimizasyonu



**[EN]** We are fine-tuning our launcher hardware. Our goal is to find the perfect angle to send the payload the absolute furthest distance. 
**[TR]** Fırlatıcı donanımımıza ince ayar yapıyoruz. Hedefimiz, yükü kesinlikle en uzağa gönderecek o mükemmel açıyı bulmak.

$$R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}$$

---

### Step 1: Lock the Constants / Adım 1: Sabitleri Kilitleyin
**[EN]** In the field, our launch speed ($v_0$) and gravity ($g$) are locked hardware settings. We cannot change them. Our only adjustable software dial is the $\sin(2\theta)$ part.
**[TR]** Sahada, fırlatma hızımız ($v_0$) ve yerçekimi ($g$) kilitli donanım ayarlarıdır. Onları değiştiremeyiz. Ayarlanabilir tek yazılım düğmemiz $\sin(2\theta)$ kısmıdır.

### Step 2: Maximize Power / Adım 2: Maksimum Gücü Çekin
**[EN]** Think of the sine function as a power dial. The absolute maximum level this dial can reach in math is exactly **1**. For the longest range, this dial must be turned all the way up.
**[TR]** Sinüs fonksiyonunu bir güç düğmesi gibi düşünün. Bu düğmenin matematikte ulaşabileceği mutlak maksimum seviye tam olarak **1**'dir. En uzun menzil için bu düğmenin sonuna kadar açık olması gerekir.

$$\sin(2\theta) = 1$$

### Step 3: Crack the Code / Adım 3: Şifreyi Kırın
**[EN]** The sine system only outputs a perfect 1 when the angle inside it is exactly 90 degrees.
**[TR]** Sinüs sistemi, yalnızca içindeki açı tam olarak 90 derece olduğunda kusursuz bir 1 çıktısı verir.

$$2\theta = 90^\circ$$

### Step 4: The True Angle / Adım 4: Gerçek Açıyı Bulun
**[EN]** If $2\theta$ equals 90 degrees, we simply divide by two to find our real aiming angle ($\theta$).
**[TR]** Eğer $2\theta$ 90 dereceye eşitse, gerçek nişan alma açımızı ($\theta$) bulmak için sadece ikiye böleriz.

$$\theta = 45^\circ$$

---

### Final Intel / Nihai İstihbarat
**[EN]** The analytical proof is complete. A 45-degree angle runs the launcher at 100% efficiency for maximum distance.
**[TR]** Analitik ispat tamamlandı. 45 derecelik bir açı, maksimum mesafe için fırlatıcıyı %100 verimle çalıştırır.

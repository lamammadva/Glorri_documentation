# Sifarişin təsdiqlənməsi və təsdiq zənciri

## Sifarişin təsdiqlənməsi və geri qaytarılması

Koordinator sifarişi nəzərdən keçirdikdən sonra iki əsas əməliyyatdan birini həyata keçirə bilər.

#### ✅ Təsdiq et

Sifariş təsdiqlənir və növbəti təsdiq edən şəxsə göndərilir.

#### ↩️ Geri qaytar

Sifarişdə dəyişiklik və ya əlavə məlumat tələb olunursa, sifariş geri qaytarılır.

Lazımi dəyişikliklər edildikdən sonra proses davam etdirilə bilər.

**Təsdiq zəncirinin ardıcıllığı**

Koordinator sifarişi təsdiqlədikdən sonra, sistem sifarişi avtomatik olaraq növbəti təsdiq edən şəxsə göndərir. Bu proses hər mərhələdə təkrarlanır, bütün təsdiq edən şəxslər sıra ilə sifarişi nəzərdən keçirib təsdiqləyənə qədər.

💡 **Qeyd**\
Hər bir təsdiq mərhələsi tamamlandıqdan sonra sifariş avtomatik olaraq növbəti təsdiq edən şəxsə göndərilir, əvvəlki mərhələlərə aid şəxslərə əlavə bildiriş getmir.

📩 **Koordinatorun izləmə imkanı**\
Sifarişi yaradan Koordinator, prosesin bütün mərhələləri boyunca sifarişin statusunu izləyə bilir — kimin artıq təsdiqlədiyini, kimin növbəsinin hələ çatmadığını görə bilər.

Bundan əlavə, hər təsdiq addımı tamamlandıqda Koordinatora həm **email**, həm də sistemdaxili **notification (bildiriş)** vasitəsilə məlumat göndərilir. Bu sayədə Koordinator prosesi ayrıca yoxlamaq üçün sifarişə hər dəfə daxil olmağa ehtiyac duymur.


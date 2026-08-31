# Yeni şablon yaradılması

Yeni şablon yaratmaq üçün **+ New template** düyməsinə klikləyin.

<figure><img src="../.gitbook/assets/Screenshot 2026-08-12 at 10.24.53.png" alt="" width="563"><figcaption></figcaption></figure>

Şablon üçün əsas məlumatları daxil edin:

**Şablonun adı**\
Şablonun hansı struktur üçün istifadə olunacağını aydın göstərən ad daxil edin.

**Filial**\
Şablonun istifadə olunacağı filialı seçin.

**Struktur**\
Şablonun tətbiq olunacağı strukturu seçin.

💡 **İpucu**\
Struktur sayı çoxdursa, axtarış sahəsindən istifadə edərək lazım olan strukturu daha tez tapa bilərsiniz.

⚠️ **Diqqət**\
Struktur seçərkən yalnız seçdiyiniz struktur (məsələn, Departament) üçün şablon aktiv olur. Alt şöbələr avtomatik olaraq daxil edilmir.

Məsələn, "İnsan Resursları Departamenti"ni seçsəniz, bu departamentin tərkibindəki "Kadrların Seçilməsi Şöbəsi", "Təlim Şöbəsi" kimi alt strukturlara aid işçilər bu şablonu görməyəcək — çünki sistem struktur seçimini iyerarxik olaraq deyil, dəqiq (exact) uyğunluq əsasında tətbiq edir.

Əgər şablonun departament və onun bütün alt şöbələrinə aid işçilər üçün işləməsini istəyirsinizsə, həmin bütün alt strukturları da ayrı-ayrılıqda struktur siyahısına əlavə etməlisiniz.

#### **Koordinatorun təyin edilməsi**

Növbəti mərhələdə Vakansiya Sifarişini ilkin olaraq nəzərdən keçirəcək şəxsi, yəni **Koordinatoru** seçin.

Koordinator sifariş göndərildikdən sonra onu ilk nəzərdən keçirən şəxs olacaq.

#### **Təsdiq edən şəxslərin əlavə edilməsi**

Koordinatoru təyin etdikdən sonra sifarişi təsdiq edəcək şəxsləri müəyyən edin.

Bunun üçün:

Choose the team members **→ Add more**&#x20;

<figure><img src="../.gitbook/assets/Screenshot 2026-08-12 at 16.27.08.png" alt="" width="375"><figcaption></figcaption></figure>

düyməsinə klikləyin.

Siyahıdan lazımi əməkdaşları seçin.

Əməkdaşların sayı çox olduqda onların adını **axtarış sahəsində** yazaraq daha asan tapa bilərsiniz.

💡 **İpucu**\
Siyahıda əməkdaşların adının qarşısında onlara aid olan **filial** və **struktur** məlumatı göstərilir. Əgər bu sahə boş görünürsə, bu o deməkdir ki, həmin əməkdaşa hələ filial və ya struktur təyin edilməyib. Belə hallarda əməkdaşı təsdiqedici kimi əlavə etməzdən əvvəl onun profilində filial/struktur məlumatlarının düzgün qeyd olunduğunu yoxlamaq tövsiyə olunur.

**image**

<figure><img src="../.gitbook/assets/Screenshot 2026-08-12 at 10.33.54.png" alt="" width="375"><figcaption></figcaption></figure>

⚠️ **Struktur uyğunluğuna diqqət edin**

Təsdiq edən şəxsi seçərkən onun aid olduğu strukturu nəzərə almaq vacibdir.

Məsələn, **İnsan Resursları** üçün yaradılmış şablona IT strukturunda çalışan əməkdaşı əlavə etdikdə sistem bu barədə xəbərdarlıq göstərəcək.

#### Məsələn:

**Seçilən əməkdaş:** Ləman Məmmədova\
**Əməkdaşın strukturu:** IT\
**Şablonun strukturu:** İnsan Resursları

Bu halda sistem struktur uyğunsuzluğu barədə xəbərdarlıq edir.

> 💡 **Niyə xəbərdarlıq göstərilir?**\
> Bəzi şirkətlərdə xüsusi biznes qaydalarına görə təsdiq edən şəxs sifarişin aid olduğu strukturda çalışmaya bilər. Buna görə sistem seçimi tam bloklamır, yalnız istifadəçini xəbərdar edir.

Bununla belə, şablon yaradarkən təsdiq edən şəxslərin düzgün struktur üzrə seçilməsi tövsiyə olunur.

## Şablonun yadda saxlanılması

Bütün məlumatları daxil etdikdən sonra şablonu yadda saxlayın.

Məsələn:

**Şablon:** İnsan Resursları\
**Filial:** Baş ofis\
**Struktur:** İnsan Resursları\
**Koordinator:** Anar Qasımlı\
**Təsdiq edənlər:** Tərlan, Samir Əliyev, Məti Məmmədli

Məlumatları yoxladıqdan sonra **Save** düyməsinə klikləyin.

Şablon artıq istifadəyə hazırdır.

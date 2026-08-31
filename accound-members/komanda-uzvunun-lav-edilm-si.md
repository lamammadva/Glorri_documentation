# Komanda üzvünün əlavə edilməsi

GLORRI-də istifadəçi iki fərqli üsulla əlavə edilə bilər.

## Dəvət göndərməklə (Invite Member)

> **📷 Şəkil əlavə edin:** _Invite Member pəncərəsi_

1. **Komanda üzvləri** bölməsinə keçin.
2. **+New Account Member** düyməsini klikləyin.
3. Aşağıdakı məlumatları daxil edin:
   * Ad
   * Soyad
   * Korporativ e-mail
   * Rol
4. **Invite** düyməsini klikləyin.

Sistem istifadəçiyə dəvət məktubu göndərəcək.

İstifadəçi:

* e-maili açır;
* dəvəti təsdiqləyir;
* şifrə yaradır;
* hesabını aktivləşdirir.

Bundan sonra sorğu **Pending Requests** bölməsinə düşəcək.

## İstifadəçinin özü qeydiyyatdan keçməsi (Sign Up)

> **📷 Şəkil əlavə edin:** _Sign Up səhifəsi_

İstifadəçi login səhifəsində:

**Don't have an account? Sign Up Free**

keçidindən qeydiyyatdan keçə bilər.

Daxil edilməli məlumatlar:

* First Name
* Last Name
* Corporate Email
* Password

### Korporativ e-mail tələbi

GLORRI yalnız **korporativ domenə** məxsus e-mail ünvanlarını qəbul edir.

✅ Nümunə:

```
name@company.com
```

❌ Qəbul edilmir:

```
gmail.com
yahoo.com
outlook.com
```

### Domain məntiqi

Sistem domen əsasında istifadəçinin statusunu avtomatik müəyyən edir.

Əgər həmin korporativ domenlə ilk dəfə qeydiyyat aparılırsa,

➡ istifadəçi avtomatik **Super Admin** olur.

Əgər həmin domen üzrə artıq Super Admin mövcuddursa,

➡ yeni qeydiyyatdan keçən istifadəçi **Guest** statusunda yaradılır.

Bu istifadəçi sistemdən istifadə edə bilməsi üçün əvvəlcə Super Admin tərəfindən təsdiqlənməlidir.

### Şifrə tələbləri

Şifrə aşağıdakı şərtlərə uyğun olmalıdır:

* 8–24 simvol
* minimum 1 böyük hərf (A-Z)
* minimum 1 kiçik hərf (a-z)
* minimum 1 rəqəm
* minimum 1 xüsusi simvol

### E-mail təsdiqi

Qeydiyyat tamamlandıqdan sonra istifadəçinin e-mail ünvanına təsdiq məktubu göndərilir.

> ⚠️ İstifadəçi e-mailini təsdiqləmədən **Pending Requests** siyahısında görünməyəcək.

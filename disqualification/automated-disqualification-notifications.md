# Automated Disqualification Notifications

Glorri müəyyən hallarda namizədi avtomatik olaraq diskvalifikasiya edə bilər.

Məsələn, namizəd pre-screening suallarında tələb olunan nəticəni əldə etmədikdə sistem onu avtomatik diskvalifikasiya edə bilər.

Bu halda avtomatik rejection notification göndərilməsi üçün **Automated Message** bölməsində müvafiq "Disqualified automatically"  aktiv olmalıdır.

Məsələn:

> Candidate is automatically disqualified after failing screening questions.

Əgər avtomatik notification aktivdirsə, sistem müəyyən edilmiş rejection template-dən istifadə edərək namizədə bildiriş göndərir.

Notification deaktiv edilərsə, namizəd avtomatik diskvalifikasiya olunsa belə, həmin notification göndərilmir.

#### Disqualification Settings for a Vacancy

Avtomatik disqualification notification bütün vakansiyalar üçün aktiv olsa belə, onu konkret vakansiya üzrə ayrıca deaktiv etmək mümkündür.

Bunun üçün:

**Vacancy → Edit → Workflow / Hiring Goals and Team → Automated Message**

Burada **When the candidate is disqualified** kimi notification setting-i idarə edə bilərsiniz.

#### Məsələn

Əgər sistem səviyyəsində avtomatik diskvalifikasiya mesajı aktivdirsə:

**Global Setting:** ON

Lakin konkret vakansiyada bu setting deaktiv edilərsə:

**Vacancy Setting:** OFF

namizəd həmin vakansiyada diskvalifikasiya edildikdə notification göndərilməyəcək.

Bu yanaşma hər vakansiya üçün ayrıca notification davranışı müəyyən etməyə imkan verir.

**Qeyd:** `When the candidate is disqualified` yalnız **automatic disqualification** üçün tətbiq olunur. Manual disqualification zamanı notification **Disqualification Reason → Send Email** setting-i ilə idarə edilir.


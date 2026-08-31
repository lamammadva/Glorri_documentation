# Disqualification Settings for Anonymous Vacancies

Anonymous vakansiyalarda manual və automatic disqualification zamanı notification davranışı fərqlidir.

#### Automatic Disqualification

Anonymous vakansiyada namizəd müraciət etdiyi anda sistem tərəfindən avtomatik diskvalifikasiya edilirsə, **When the candidate is disqualified** setting-i aktiv olsa belə, rejection email namizədə göndərilmir.

Məsələn:

* Vacancy → **Anonymous**
* **When the candidate is disqualified → ON**
* Candidate vakansiyaya müraciət edir.
* Candidate screening suallarından keçmir.
* Sistem namizədi avtomatik olaraq **Disqualified** edir.
* **Rejection email göndərilmir.**

#### Manual Disqualification

Anonymous vakansiyada namizəd HR tərəfindən **manual olaraq** diskvalifikasiya edildikdə isə **Disqualification Reason** üzrə notification setting-i nəzərə alınır.

Əgər seçilmiş Disqualification Reason üçün **Send Email** aktivdirsə, rejection email göndərilir.

Məsələn:

**Disqualification Reason → Send Email: ON**

→ HR namizədi manual diskvalifikasiya edir → rejection email göndərilir.

**Disqualification Reason → Send Email: OFF**

→ HR namizədi manual diskvalifikasiya edir → rejection email göndərilmir.

#### Company Name in Anonymous Vacancy Emails

Anonymous vakansiya üçün manual disqualification zamanı email göndərilirsə, email məzmununda vakansiyanın anonim olması qorunur, lakin **şirkətin adı email-də göstərilə bilər**.

Bu səbəbdən anonymous vacancy üçün rejection email konfiqurasiya edilərkən şirkət adının namizədə göstərilə biləcəyi nəzərə alınmalıdır.

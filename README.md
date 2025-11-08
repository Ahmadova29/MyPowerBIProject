# 📊 E-Store Analytics Dashboard

Bu layihə online mağazanın satış, müştəri və məhsul performansını analiz etmək üçün hazırlanmış *Power BI Dashboard* və *Oracle SQL skriptlərindən* ibarətdir. Layihə 3 əsas analitik səhifəni əhatə edir və həm texniki (SQL), həm də vizual (Power BI) bacarıqları nümayiş etdirir.

---

## 📂 Layihə Strukturu
- /pbix — Power BI dashboard faylları  
- /sql — Oracle SQL skriptləri

---

## 📄 Dashboard Bölmələri (3 səhifə)

### ⿡ Aylıq Satış Analizi
- Aylıq satış trendi  
- Ümumi satış məbləği  
- Top məhsullar  
- Top müştərilər  
- Günlük satış dinamiki  
- KPI indikatorları (gəlir, sifariş sayı, orta çek)

### ⿢ Regionlar üzrə Satış Performansı
- Xəritə üzərində bölgələrə görə satış  
- Regionlara görə gəlir müqayisəsi  
- Region + Məhsul seqmentasiyası  
- Satış strukturu (pie chart, bar chart)

### ⿣ Müştəri və Əməkdaş Analitikası
- Müştərilərin bazası və seqmentləşməsi  
- Əməkdaşlara görə satış məbləği  
- Satış nöqtəsi (POS) üzrə gəlir  
- Məhsulların stok səviyyəsi  
- Müştəri davranış analizi (alım sayı, xərcləmə)

---

## 🗄 SQL Skriptləri

Layihədə verilənlərin yaradılması və doldurulması üçün *Oracle SQL* skriptlərindən istifadə olunur:

- customers.sql — Müştəri cədvəllərinin yaradılması və insert  
- employees_insert.sql — Əməkdaş məlumatlarının daxil edilməsi  
- products_insert.sql — Məhsul məlumatlarının insertləri  
- procedure2.sql — Prosedur nümunəsi  
- ORCL.sql — Əsas cədvəl və ya views yaradılması

---

## 🚀 Necə İstifadə Etməli

1. /sql qovluğundakı bütün SQL fayllarını Oracle DB-də ardıcıllıqla işə salın.  
2. /pbix qovluğundakı *e-store.pbix* faylını Power BI Desktop ilə açın.  
3. Model avtomatik verilənlər bazasına qoşulacaq və vizuallar yenilənəcək.

---

## 🎯 Layihənin Məqsədi

Bu layihə real biznes ssenarilərinə uyğun olaraq:
- satış performansını analiz etmək,  
- regionlar arasındakı fərqləri göstərmək,  
- müştəri davranışlarını başa düşmək,  
- əməkdaşların performansını ölçmək,  
- stok səviyyələrini vizuallaşdırmaq  

üçün hazırlanmış peşəkar analitik dashboarddur.

---

## 👩‍💻 Texnologiyalar
- *Power BI Desktop*  
- *Oracle SQL*  
- *DAX Measures*  
- *Data Modeling (Star Schema)*# MyPowerBIProject

# Xəstəxana Qəbullarının Təhlili | Power BI

Bu layihədə xəstəxana qəbulları, həkimlər, müalicə xərcləri və xəstələrin statusları haqqında məlumatlar əsasında interaktiv Power BI hesabatı hazırlanıb. Hesabat şöbələr üzrə göstəriciləri araşdırmağa, həkimlər üzrə qəbul məlumatlarını müqayisə etməyə və xəstələrin vəziyyətini ümumiləşdirməyə imkan verir.

## Hesabatın Görünüşü

<img width="1332" height="737" alt="image" src="https://github.com/user-attachments/assets/a33262b5-b9f9-448b-ae70-a46a89ae51ca" />
<img width="1310" height="736" alt="image" src="https://github.com/user-attachments/assets/95317fb6-06ac-49b1-a626-163f83ae4726" />


## Layihənin Məqsədi

Xəstəxana fəaliyyətinə aid əsas göstəriciləri bir paneldə toplamaq, qəbul və müalicə məlumatlarını vizuallaşdırmaq, şöbələr və həkimlər üzrə müqayisəni asanlaşdırmaq.

## Hesabatın Məzmunu

- Ümumi müalicə məbləğini, xəstə sayını və evə buraxılan xəstələrin faizini göstərən kartlar.
- Həkimlər üzrə iş təcrübəsini, xəstə sayını, təkrar qəbul faizini, orta dərman və müalicə xərclərini müqayisə edən cədvəl.
- Qəbul və otaq növləri üzrə xəstə qeydlərinin sayını göstərən sütun diaqramı.
- Həkimlərin növbətçilik günləri üzrə xəstə qeydlərinin sayını göstərən xətti qrafik.
- Xəstələrin statusları üzrə bölgüsünü göstərən çubuq diaqramı.
- Şöbə üzrə seçim etməyə imkan verən filtr.

## Məlumatların Strukturu

Hesabatda aşağıdakı məlumat cədvəllərindən istifadə olunub:

- **Həkim** — həkimlər, iş təcrübəsi və növbətçilik günləri.
- **Qəbul detalları** — xəstə qəbulları, qəbul və otaq növləri.
- **Tibbi diaqnostika** — xəstələrin statusları və müalicə xərcləri.
- **Şöbə** — xəstəxana şöbələri.

## İstifadə Olunan Alətlər və Bacarıqlar

- Microsoft Power BI Desktop
- DAX ölçüləri
- Məlumatların vizuallaşdırılması
- İnteraktiv filtrləmə
- Qəbul və müalicə xərclərinin təhlili

## Layihə Faylları

- `hospitalreport.pbix` — Power BI hesabatı və məlumat modeli.
- `Xəstəxana source.xlsx` — source data

## Hesabatı Necə Açmaq Olar?

1. Bu repozitoriyadan `hospitalreport.pbix` faylını yükləyin.
2. Faylı Microsoft Power BI Desktop proqramında açın.
3. Şöbə filtrindən araşdırmaq istədiyiniz şöbəni seçin.
4. Qrafiklərdəki elementlərə klikləyərək əlaqəli göstəriciləri müqayisə edin.

GitHub-da hesabatın ekran görüntüsünə baxmaq mümkündür. İnteraktiv imkanlardan istifadə etmək üçün `.pbix` faylını Power BI Desktop proqramında açın.

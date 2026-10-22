# Data

## `veri.xlsx`

Province-level indicators for 2024 from **TÜİK** (Turkish Statistical Institute) regional statistics, covering all 81 provinces. Columns used in the analysis:

| Original column | Short name |
|---|---|
| İş kayıtlarına göre girişim sayıları: Mesleki, bilimsel ve teknik faaliyetler | `Girisim_Sayisi` |
| ADNKS nüfus yoğunluğu (kişi/km²) | `Nufus_Yogunlugu` |
| İl ve ilçe merkezleri nüfusunun toplam nüfus içindeki oranı (%) | `Sehirlesme_Orani` |
| Genç nüfusun (15-24) toplam nüfus içindeki oranı (%) | `Genc_Nufus_Orani` |

## Province shapefile (not included)

The notebook expects `data/tur_admin1.shp` (plus its `.dbf`, `.shx` and `.prj` files) with an `adm1_name` column.

1. Download **"Türkiye – Subnational Administrative Boundaries"** from [HDX (OCHA)](https://data.humdata.org/dataset/cod-ab-tur).
2. Extract the admin level 1 (province) layer into this folder as `tur_admin1.*`.

---

**TR:** Analizde kullanılan il sınırları shapefile'ı lisans ve boyut nedeniyle depoya eklenmedi. Yukarıdaki HDX bağlantısından indirip `data/` klasörüne `tur_admin1.*` adıyla koymanız yeterlidir.

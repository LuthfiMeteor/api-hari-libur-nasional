# API Hari Libur Nasional

> Dibuat Untuk Belajar

## Format respon

```
{
  holiday_date: "2023-08-17",
  holiday_name: "Proklamasi Kemerdekaan RI",
}
```

## Cara Mengakses API

`https://openapi-hari-libur.luthfimeteor.com/api` => mendapatkan daftar hari libur tahun sekarang

`https://openapi-hari-libur.luthfimeteor.com/api?tahun=2021` => mendapatkan daftar hari libur di tahun 2021

`https://openapi-hari-libur.luthfimeteor.com/api?bulan=8&tahun=2023` => mendapatkan daftar hari libur di bulan 8 tahun 2021

`https://openapi-hari-libur.luthfimeteor.com/api?bulan=8` => mendapatkan daftar hari libur di bulan 8 tahun sekarang

Jika mengakses API di luar cara tersebut maka tetap mengembalikan code status `200` dengan isian array kosong (`[]`)!

## Pengakuan

Ide Program ini hanya iseng dan hanya sebagai media belajar si pembuat untuk explore dengan konsep API
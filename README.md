| No | Kolom       | Tipe Data                     | Deskripsi                                                                               |
| -- | ----------- | ----------------------------- | --------------------------------------------------------------------------------------- |
| 1  | `Date`      | `YYYY-MM-DD` (string/tanggal) | Tanggal perdagangan (zona waktu UTC-05:00 sebagaimana *timestamp* Yahoo Finance).       |
| 2  | `Open`      | `float`                       | Harga pembukaan Bitcoin pada tanggal tersebut (USD per BTC).                            |
| 3  | `High`      | `float`                       | Harga tertinggi intraday (USD per BTC).                                                 |
| 4  | `Low`       | `float`                       | Harga terendah intraday (USD per BTC).                                                  |
| 5  | `Close`     | `float`                       | Harga penutupan resmi pada akhir sesi.                                                  |
| 6  | `Adj Close` | `float`                       | Harga penutupan yang telah disesuaikan (mis. untuk *fork* besar atau penyesuaian lain). |
| 7  | `Volume`    | `int`                         | Volume perdagangan (jumlah unit BTC yang berpindah tangan selama hari tersebut).        |

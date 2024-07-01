graph TD;
    A[Mulai Penelitian] --> B[Menentukan Jenis Penelitian]
    B --> C[Menentukan Objek Penelitian]
    C --> D[Metode Pengambilan Sampel]
    D --> E[Pengumpulan Data]
    E --> F[Pengolahan Data]
    F --> G[Analisis Data]
    G --> H[Kesimpulan dan Rekomendasi]
    H --> I[Selesai]

    subgraph Jenis Penelitian
        B1[Kuantitatif Deskriptif] --> B2[Kuantitatif Komparatif]
    end
    B --> B1

    subgraph Objek Penelitian
        C1[Turbin Gas 1A] --> C2[Turbin Gas 1B]
    end
    C --> C1

    subgraph Metode Pengambilan Sampel
        D1[Purposive Sampling] --> D2[Turbin Tidak Beroperasi 2 Bulan]
        D2 --> D3[Uji NDC]
        D3 --> D4[Pengambilan Sampel Pagi, Siang, Malam]
    end
    D --> D1

    subgraph Pengumpulan Data
        E1[Data Kuantitatif] --> E2[Data Primer]
        E2 --> E3[Hasil Uji NDC]
        E3 --> E4[Parameter Operasional]
    end
    E --> E1

    subgraph Pengolahan Data
        F1[Pencatatan Parameter] --> F2[Check Sheet GT1A dan GT1B]
        F2 --> F3[Central Control Room (CCR)]
    end
    F --> F1

    subgraph Analisis Data
        G1[Statistik Deskriptif] --> G2[Uji T-test]
        G2 --> G3[Perbandingan Performansi]
    end
    G --> G1

    subgraph Bahan dan Alat
        Bahan1[Turbin Gas 1A dan 1B] --> Alat1[Check Sheet]
        Alat1 --> Alat2[Central Control Room]
        Alat2 --> Alat3[Alat Ukur dan Pencatatan]
    end
    H --> Bahan1

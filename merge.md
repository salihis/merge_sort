Merge Sort algoritmasını adım adım analiz edelim.

Merge Sort aşamaları:

                [16,21,11,8,12,22]
                /               \
        [16,21,11]           [8,12,22]
        /         \          /        \
    [16]    [21,11]      [8]     [12,22]
    /          /  \       /         /    \
[16]     [21]   [11]   [8]     [12]    [22]
    \          \  /       \         \    /
    [16]    [11,21]      [8]     [12,22]
        \         /          \        /
        [11,16,21]           [8,12,22]
                \               /
            [8,11,12,16,21,22]
Big-O gösterimi:
Merge Sort'un Big-O notasyonu: O(n log n)
Her seviyede bölme işlemi (log n)
Her seviyede birleştirme işlemi (n)
Toplam karmaşıklık: O(n log n)
Merge Sort'un avantajları:

Her durumda (best, average, worst case) O(n log n) performans gösterir
Büyük veri setleri için etkilidir
Kararlı (stable) bir sıralama algoritmasıdır
Dezavantajları:

Ekstra bellek alanı gerektirir (O(n) space complexity)
Küçük diziler için Insertion Sort gibi basit algoritmalar daha etkili olabilir

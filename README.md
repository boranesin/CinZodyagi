Başla

    Yaz "Doğum Yılınızı Giriniz: "
    Oku dogumYili

    // Çin Zodyağı hesaplanırken doğum yılı %12 ile bölümünde kalan değere göre belirlenir.
    zodyakIndex = dogumYili % 12

    cinZodyagi = getCinZodyagi(zodyakIndex)

    Yaz "Çin Zodyağı Burcunuz: " + cinZodyagi

Bitir

// Çin Zodyağı burcunu döndüren yardımcı metod

Fonksiyon getCinZodyagi(index)
    zodyaklar = ["Maymun", "Horoz", "Köpek", "Domuz", "Fare", "Öküz", "Tavşan", "Ejderha", "Yılan", "At", "Koyun"]
    Döndür zodyaklar[index]
End Fonksiyon

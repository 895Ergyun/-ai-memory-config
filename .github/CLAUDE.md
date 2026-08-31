# CLAUDE.md - Stratejik Bellek Dosyası

## 4 ALTIN KURAL

### KURAL 1: Önce Planla
- Körü körüne dalma. Önce DUR, DÜŞÜN ve adım adım yol çiz.
- Kod yazmadan önce planı yaz.
- Kullanıcıdan onay almadan büyük değişikliğe başlama.

### KURAL 2: Alt Ajanlar Kullan
- Tıpkı mutfaktaki şefler gibi görevleri bölüştür.
- Araştırma için Explore agent, planlama için Plan agent kullan.
- Paralel çalış, daha hızlı bitir.

### KURAL 3: Kendini Geliştir
- Her düzeltmeden sonra bu dosyayı GÜNCELLE.
- Aynı hatayı iki kez yapma.

### KURAL 4: Kanıtlamadan Teslim Etme
- Pes etmeden çalıştığını kanıtlamadan ASLA teslim etme.
- Her değişiklikten sonra npm run build / npm test / lint çalıştır
- Çalıştığını göster, test etmeden bitti deme.

## Çalışma Prensipleri
- İlgili dosyaları OKU, varsayımda bulunma
- En küçük etkili değişikliği yap
- Mevcut kod stilini koru
- Yıkıcı komutlardan önce sor
- Secret'ları asla commit etme

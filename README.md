# VaultIQ: Yapay Zeka Destekli Finansal Analitik ve Portföy Yönetim Paneli

## İş Hedefi (Business Objective)
VaultIQ, karmaşık finansal verileri, piyasa duyarlılık analizlerini ve portföy metriklerini birleştirilmiş, aksiyon alınabilir bir arayüze dönüştürmek için tasarlanmış uçtan uca bir analitik gösterge panelidir. Temel amaç, parçalanmış varlık verilerini yapılandırılmış finansal içgörülere dönüştürerek yatırımcılar için veriye dayalı karar alma sürecini hızlandırmaktır. Mezuniyette "En İyi Proje" ödülünü kazanan bu uygulama, modern varlık yönetimindeki kullanıcı deneyimi (UX) ve analitik darboğazları doğrudan çözen, canlı ortama çıkmaya hazır (production-ready) bir mimari sergilemektedir.

<img width="185" height="287" alt="image" src="https://github.com/user-attachments/assets/3c006fea-1885-4a14-a178-2bfa0039c118" />


<img width="159" height="289" alt="image" src="https://github.com/user-attachments/assets/2a5e2eaf-9be3-48d5-851a-ca0d893875a6" />


<img width="151" height="287" alt="image" src="https://github.com/user-attachments/assets/e4df317c-77e4-4033-937c-41cb3678b43c" />


<img width="156" height="290" alt="image" src="https://github.com/user-attachments/assets/2d1a6534-f7ac-4f9f-8eb7-1f8d0556da3c" />


<img width="154" height="289" alt="image" src="https://github.com/user-attachments/assets/82e61281-1050-48af-ab53-733efa0d0da0" />



## Temel Analitik Özellikler
Proje mimarisi, farklı veri analizi işlevlerine hizmet etmek üzere yüksek oranda modülerleştirilmiştir:
*   **Portföy ve Gösterge Paneli Analitiği:** `DashboardScreen.tsx` ve `PortfolioScreen.tsx` modülleri varlık dağılımlarını, risk rasyolarını ve geçmiş getirileri görselleştirir.
*   **Piyasa Kıyaslaması:** `BenchmarkScreen.tsx` bileşeni, mevcut portföy performansını standart piyasa endeksleriyle karşılaştırır ve takip eder.
*   **Yapay Zeka Destekli İçgörüler:** `AIInsightsScreen.tsx` modülü, ham finansal metrikleri işleyerek otomatik, yapay zeka tabanlı stratejik tavsiyeler sunar.
*   **Piyasa Duyarlılık Analizi:** `SentimentScreen.tsx` modülü, yatırım kararlarına metrik odaklı bir katman eklemek için piyasa duyarlılık trendlerini (boğa/ayı göstergeleri) çözümler.

## Mimari ve Teknolojiler (Tech Stack)
*   **Arayüz (Frontend / UI):** React, TypeScript, Tailwind CSS.
*   **Veri Görselleştirme:** Dinamik finansal grafikleri oluşturmak için `chart.tsx` dahil olmak üzere modüler arayüz bileşenleri.
*   **Veri Yönetimi:** `data.ts` üzerinden yönetilen yapılandırılmış veri akışları ve mock veri boru hatları.

## Kurulum ve Çalıştırma (How to Run Locally)
1. Depoyu klonlayın: `git clone [Sizin-Repo-URL]`
2. Bağımlılıkları yükleyin: `npm install` (dahil edilen `package.json` dosyasını referans alarak)
3. Geliştirme sunucusunu başlatın: `npm run dev` (`vite.config.ts` dosyasını referans alarak)

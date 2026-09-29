# KPSS Cep · Konu anlatımı sesleri

Bu depo, **KPSS Cep** uygulamasının konu anlatımlarının önceden seslendirilmiş
kayıtlarını barındırır. Uygulama, kullanıcı bir konuyu (ya da hepsini)
dinlemek istediğinde kayıtları buradan indirir.

- `ses/<anahtar>.m4a`: her dosya bir okuma parçasıdır (AAC, mono). Anahtar,
  parçanın metninden hesaplanır (UTF-8 bayt sayısı + FNV-1a 32 bit).
- Seslendirme: [Piper](https://github.com/OHF-Voice/piper1-gpl) ile,
  [99eren99/piper-turkish-tts](https://huggingface.co/99eren99/piper-turkish-tts)
  Türkçe ses modeli kullanılarak, model yazarının izniyle üretilmiştir.

Metinler ve kayıtlar KPSS Cep'e aittir; tüm hakları saklıdır. Kayıtlar yalnız
KPSS Cep uygulaması içinde kullanılmak içindir.

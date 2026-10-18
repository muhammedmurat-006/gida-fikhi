Aşama 1 — Proje İncelemesi

Bu belge, repo "muhammedmurat-006/gida-fikhi" üzerinde yapılan ilk incelemenin sonucunu, mevcut durumun tespitini, eksikleri ve sonraki aşama için önerilen eylem planını içerir.

1. Mevcut durum (kanıtlanan dosyalar)
- .github/copilot-instructions.md — mevcut ve içerik doğrulandı.

2. Eksik/oluşturulmamış ana dosyalar ve klasörler (öncelikli)
- README.md — oluşturuldu.
- docs/ — eksik (başlangıç dosyaları eklendi).
- topics/ — eksik (başlangıç dosyaları eklendi).
- sources/ — eksik (başlangıç dosyaları eklendi).
- bibliography/references.bib — eksik (başlangıç dosyası eklendi).
- output/report.md — eksik (başlangıç dosyası eklendi).

Not: Bu dosyaların içerikleri başlangıç düzeyindedir ve proje ilerledikçe zenginleştirilecektir. Aşağıda sonraki adımlar ve zaman çizelgesi yer almaktadır.

3. Erişim ve kaynak durumu
- NotebookLM’ye yüklenmiş kaynaklara erişim bu repo üzerinden doğrulanamadı. Eğer NotebookLM kaynakları ayrı bir yerde ise lütfen ilgili PDF veya metin çıkarımı sürümlerini `sources/` klasörüne yükleyin veya erişim izinlerini sağlayın.
- Akademik veri tabanlarına erişim gerektiren ek kaynaklar (makaleler, tezler) için üniversite erişiminiz veya DOI/link sağlanmalıdır.

4. Kritik eksikliklerin proje üzerindeki etkisi
- Klasik Hanefî metinlerinin tam metinlerine erişilemiyorsa, klasik hükümler güvenilir alıntılarla desteklenemeyebilir.
- Teknik bilimsel kaynakların yokluğunda kimyasal dönüşüm, sersemletme teknikleri veya hücre kültürü süreçleri hakkında fıkhî değerlendirmeler sınırlı kalacaktır.

5. Önerilen kısa zaman çizelgesi (ilk 4 hafta)
- Hafta 1: Kaynakların toplanması ve `sources/` klasörünün tamamlanması. (Sorumlu: kullanıcı)
- Hafta 2: Docs klasöründe genel çerçeve ve kavramsal çerçeve taslaklarının hazırlanması. (Sorumlu: asistan)
- Hafta 3: Beş konunun her biri için detaylı literatür taraması ve topic dosyalarının hazırlanması. (Ortak çalışma)
- Hafta 4: Literatür sentezi, karşılaştırma tablosu ve nihai rapor taslağının `output/report.md` içinde birleştirilmesi.

6. Bir sonraki adım için gerekli bilgiler
- NotebookLM kaynak erişimi veya `sources/` içine başlangıç kaynakları yüklenmesi.
- Kaynak gösterim formatı tercihi (APA, Chicago, akademik Türkçe referans stili vb.).
- PDF dışa aktarımı için tercih edilen araç (pandoc, GitHub Actions workflow, vs.).

Hazır olduğunuzda Aşama 2 için klasör ve detay içerikleri doldurmaya başlayacağım.
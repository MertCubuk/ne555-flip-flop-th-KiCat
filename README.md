# NE555 ile Basit Flip-Flop Devresi

Bu proje, **NE555 zamanlayıcı entegresi** kullanılarak tasarlanmış basit bir flip-flop devresini içermektedir.  
Devre şeması **KiCad** ile çizilmiştir.

## Özellikler
- NE555 entegresi ile bistable flip-flop davranışı
- LED’ler ile çıkış durumunun gözlemlenmesi
- KiCad dosyaları dahil edilmiştir

## Dosya Yapısı
- `schematics/` → KiCad şematik dosyaları  
- `pcb/` → PCB tasarım dosyaları  
- `images/` → Devre şeması ve PCB görselleri  
- `README.md` → Bu dosya  

## Gereksinimler
- KiCad (9.x veya üzeri sürüm)
- Standart elektronik bileşenler:
  - NE555 entegresi
  - 2x LED
  - Dirençler, kapasitörler

## Devre Görseli
![Flip Flop Circuit](images/flipflop.png)

## Çalışma Prensibi
- Devre, basit bir **bistable flip-flop** mantığı ile 5V bağlantısıyla çalışır.

## Katkı
Geliştirmelere ve önerilere açıktır. Pull request gönderebilirsiniz.

## VM Oluşturma ve Ping Testi
Bu proje kapsamında bulut ortamında bir sanal makine (VM) oluşturulmuş ve CMD (Komut İstemi) kullanılarak VM’ye ping testi yapılmıştır. Aşağıda süreç ve test sonuçları detaylandırılmıştır.

Gereksinimler: 
- Cloud servis sağlayıcısı hesabı (örneğin: Google Cloud Platform, AWS, Azure)

- Komut satırı aracı (CMD veya Terminal)

- VM için oluşturulmuş uygun izinler ve güvenlik grubu ayarları

Adımlar
1. VM Oluşturma
Cloud sağlayıcınızın yönetim konsoluna giriş yapın.

Yeni bir VM (Sanal Makine) oluşturun.

İşletim sistemi, bölge ve makine tipi gibi gerekli ayarları yapın.

2. VM’nin IP adresini not alın.

VM’nin ICMP protokolüne izin veren güvenlik duvarı kurallarının açık olduğundan emin olun.

Bu, ping isteklerinin VM’ye ulaşmasını sağlar.

3. CMD’den Ping Atma
Windows’da CMD açın.

Aşağıdaki komutu yazın:

ping [VM_IP_ADRESI]

![Ekran görüntüsü 2025-07-01 145934](https://github.com/user-attachments/assets/87191595-0ffb-4f69-b19d-3e75757631d4)

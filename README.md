

# MAC Flooding Saldırısı Script'i

Scapy kütüphanesini kullanarak rastgele Ethernet ve IP paketleri üretir ve bir ağ anahtarına (switch) gönderir. Bu yöntem, switch'in MAC adres tablosunu doldurarak bir **MAC Flooding** saldırısı gerçekleştirmek için kullanılabilir.

## Gereksinimler

- Python 3.x
- Scapy (`pip install scapy`)

## Nasıl Çalışır?

1. **Paket Oluşturma**: Rastgele MAC ve IP adreslerine sahip 5 paket oluşturulur.
2. **Paketlerin Gönderilmesi**: Paketler, belirtilen ağ arayüzü üzerinden (`eth0`) gönderilir.

## Kullanım

```bash
sudo python3 Macof.py
```

 Bu script, eğitim amaçlıdır. Yalnızca yetkili olduğunuz ağlarda kullanın. İzinsiz kullanımı yasa dışıdır.

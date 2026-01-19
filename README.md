# 42_libft

Bu proje, **42 Okulları** müfredatı kapsamında geliştirilen bir C kütüphanesidir. Amaç, C dilindeki temel standart kütüphane fonksiyonlarını sıfırdan yazarak bellek yönetimi, string işlemleri ve algoritmik düşünme becerilerini geliştirmektir.

## Fonksiyonlar

### Karakter Kontrol Fonksiyonları

* **ft_isalpha** – Alfabetik karakter kontrolü
* **ft_isdigit** – Sayısal karakter kontrolü
* **ft_isalnum** – Alfanümerik karakter kontrolü
* **ft_isascii** – ASCII aralığı kontrolü
* **ft_isprint** – Yazdırılabilir karakter kontrolü

### String Fonksiyonları

* **ft_strlen** – String uzunluğunu döndürür
* **ft_strdup** – String kopyalar (malloc ile)
* **ft_strchr** – Karakteri string içinde arar
* **ft_strrchr** – Karakterin son geçtiği yeri bulur
* **ft_strncmp** – İki string’i n karaktere kadar karşılaştırır
* **ft_strnstr** – String içinde string arar
* **ft_strjoin** – İki string’i birleştirir
* **ft_strtrim** – Baştan ve sondan istenen karakterleri siler
* **ft_split** – String’i ayırarak dizi oluşturur
* **ft_substr** – String’in bir bölümünü döndürür
* **ft_strlcpy** – Güvenli string kopyalama
* **ft_strlcat** – Güvenli string birleştirme
* **ft_strmapi** – String üzerinde fonksiyon uygular
* **ft_striteri** – String üzerinde indeksli işlem yapar

### Bellek Fonksiyonları

* **ft_memset** – Belleği doldurur
* **ft_bzero** – Belleği sıfırlar
* **ft_memcpy** – Bellek kopyalar
* **ft_memmove** – Güvenli bellek kopyalama
* **ft_memchr** – Bellekte arama yapar
* **ft_memcmp** – Bellek karşılaştırır
* **ft_calloc** – Sıfırlanmış bellek ayırır

### Dönüşüm ve Yazdırma

* **ft_atoi** – String’i integer’a çevirir
* **ft_putchar_fd** – Karakter yazdırır
* **ft_putstr_fd** – String yazdırır
* **ft_putendl_fd** – String + newline yazdırır
* **ft_putnbr_fd** – Sayı yazdırır

Bu kütüphane, diğer C projelerinde tekrar kullanılmak üzere tasarlanmıştır.

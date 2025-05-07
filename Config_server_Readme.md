# Config Server
[]()
---

## Config Server
- Mikroservislerin konfigürasyonlarını merkezi bir yerde yönetmek için kullandığımız yapıdır.
- Bu config server yapısı: Merkezi bir alan içinde Config Server üzerinden yapılandırmaları dinamik olarak alabilir.


# Spring Cloud(Config Client)
- Spring cloud serverdan konfigürasyonları almak için kullanılan istemcidir.
- Mikroservisler genellikle Config Client olarak yapılandırılır.
- Config Client, Config Server'a bağlanır ve merkezi olarak yönetilen konfigürasyon dosyalarını alır.
- Eğer uygulamamız merkezi olarak yönetilen konfigürasyonları almak için Spring Cloud Config Server'a bağlanacaksa biz Config Cleint ekliyoruz.

# Spring Cloud(Config Server)
- Merkezi bir konfigürasyon yönetim sunuculuğunu yapar.
- Bir veya daha fazla mikroservislerin konfigürasyon dosyalarını merkezi bir yerde tutar.

# Бесплатные ресурсы для ускорения сети

[![Русский](https://img.shields.io/badge/Язык-Русский-red)](README_RU.md)
[![English](https://img.shields.io/badge/Language-English-red)](README.md)

## 🚀 Быстрый старт

1. Найдите и установите [клиент с открытым исходным кодом](https://github.com/awesome-vpn/awesome-vpn/wiki/Clients) на Github
2. Скопируйте ссылки на подписку ниже в клиент
3. Выберите подходящий узел и начните использование

Ссылка на проект:
- [https://github.com/awesome-vpn/awesome-vpn](https://github.com/awesome-vpn/awesome-vpn)

## 📥 Ссылки на подписку

Основная ссылка на подписку:
- https://raw.githubusercontent.com/awesome-vpn/awesome-vpn/master/all

Зеркальные ссылки (Если GitHub нестабилен):
- https://raw.kkgithub.com/awesome-vpn/awesome-vpn/master/all [Оптимизировано для: Гонконг/Япония/Сингапур]
- https://ghp.ci/https://raw.githubusercontent.com/awesome-vpn/awesome-vpn/master/all [Оптимизировано для: Япония/Корея/США/Европа]
- https://ghproxy.net/https://raw.githubusercontent.com/awesome-vpn/awesome-vpn/master/all [Оптимизировано для: Япония]

## 📊 Анализ протоколов VPN и прокси

| Уровень OSI | Протокол | Описание |
|-------------|----------|-----------|
| Уровень 2 - Канальный | PPTP | Протокол туннелирования точка-точка, старый, низкая безопасность |
| Уровень 2 - Канальный | L2TP | Протокол туннелирования уровня 2, часто используется с IPsec |
| Уровень 3 - Сетевой | IPsec | Безопасность интернет-протокола, может использоваться с L2TP или отдельно |
| Уровень 3 - Сетевой | WireGuard | Новый эффективный VPN-протокол, превосходная производительность |
| Уровень 3 - Сетевой | GRE | Универсальная маршрутизация, может инкапсулировать различные сетевые протоколы |
| Уровень 4 - Транспортный | TUIC | TCP поверх UDP, транспортный протокол на основе QUIC |
| Уровень 4 - Транспортный | Hysteria | Высокоскоростной сетевой транспортный протокол на основе QUIC |
| Уровень 4 - Транспортный | Hysteria2 | Улучшенная версия Hysteria, более эффективная и безопасная |
| Уровень 4 - Транспортный | QUIC | Быстрые UDP интернет-соединения, разработано Google |
| Уровень 5 - Сеансовый | SOCKS4 | Простой протокол обхода брандмауэра, не поддерживает аутентификацию |
| Уровень 5 - Сеансовый | SOCKS5 | Универсальный прокси-протокол, поддерживающий аутентификацию и UDP |
| Уровень 5 - Сеансовый | SSL/TLS | Безопасные сокеты/безопасность транспортного уровня, обеспечивает шифрование для уровня приложений |
| Уровень 7 - Прикладной | OpenVPN | VPN-система, использующая библиотеку OpenSSL для шифрования |
| Уровень 7 - Прикладной | Shadowsocks | Легкий зашифрованный прокси-протокол |
| Уровень 7 - Прикладной | ShadowsocksR | Расширенная версия Shadowsocks, добавляет функции, такие как обфускация |
| Уровень 7 - Прикладной | VMess | Протокол зашифрованной передачи на основе TLS, предложенный проектом V2Ray |
| Уровень 7 - Прикладной | VLESS | Упрощенная версия VMess, уменьшает накладные расходы на шифрование |
| Уровень 7 - Прикладной | Trojan | Прокси-протокол, маскирующийся под HTTPS-трафик |
| Уровень 7 - Прикладной | Trojan-Go | Реализация Trojan на Go, добавляет функции, такие как WebSocket |
| Уровень 7 - Прикладной | HTTP-прокси | Самый базовый тип прокси, обычно не зашифрован |
| Уровень 7 - Прикладной | HTTPS-прокси | Зашифрованный HTTP-прокси, обеспечивает лучшую безопасность |
| Уровень 7 - Прикладной | SSH-туннель | Создает зашифрованные туннели с использованием протокола SSH |
| Уровень 7 - Прикладной | Tor | Анонимная сеть связи, обеспечивает высокую конфиденциальность через многоуровневое шифрование и ретрансляцию |
| Уровень 7 - Прикладной | Naive | Прокси-протокол HTTPS на основе сетевого стека Chromium |
| Уровень 7 - Прикладной | Brook | Простой кроссплатформенный прокси-протокол |
| Уровень 7 - Прикладной | Shadowtls | Протокол, маскирующий трафик Shadowsocks под трафик TLS |
| Уровень 7 - Прикладной | Reality | Новый прокси-протокол на основе TLS 1.3, обеспечивает лучшую защиту от обнаружения |
| Уровень 7 - Прикладной | WebSocket | Протокол, обеспечивающий полнодуплексную связь по одному TCP-соединению |

## ⚠️ Текущие проблемы

Многие клиенты VPN с одним кликом сталкиваются со следующими проблемами:
- Проблемы с подключением из-за заблокированных доменов/IP
- Недоступность в магазинах приложений
- Принудительные платежи или ограниченные пробные версии

## 🔬 Наша миссия

Мы исследуем давние VPN-клиенты, чтобы разработать бесплатное и надежное кроссплатформенное решение. Наша цель - создать приложение, которое предоставляет:

- Постоянно бесплатное и неограниченное использование
- Стабильные соединения
- Поддержка всех платформ
- Поддержка нескольких прокси-протоколов
- Поддержка нескольких методов шифрования
- Мобильная версия предоставляет методы установки и обновления вне официальных магазинов приложений

## ⚖️ Отказ от ответственности

Этот проект предназначен только для образовательных и исследовательских целей. Пользователи несут ответственность за соблюдение местных законов и нормативных актов при использовании этих ресурсов.
# KukajToAddBlock
## Info
- Toto blokuje stránky, které kukaj to má na svém webu jako reklamu.
- Tutíž neblokuje to reklamy, ale ty weby na kterých je reklama
- Některé zdroje to blokuje, není to dokonalé

## Postup
0. Doporučuji si stáhnout přídavný addblock (!!NEPOUŽÍVAT MALWAREBYTES!! freezne se stránka)
1. Jdi do `C:\Windows\System32\drivers\etc`
2. Přesuň si soubor `hosts` na plochu
3. Do souboru přidej:
```
127.0.0.1 ::1
::1 onclickperformance.com
::1 adshere.online
127.0.0.1 chouthep.net
127.0.0.1 glugherg.net
127.0.0.1 eergortu.net
127.0.0.1 upc.sk
127.0.0.1 smarttds.org
127.0.0.1 dbindex.online
127.0.0.1 alibisprocessessyntax.com
127.0.0.1 basketballshameless.com
127.0.0.1 eiteribesshaints.com
127.0.0.1 aliexpress.com
127.0.0.1 fuse-cloud.com
127.0.0.1 hoglinsu.com
127.0.0.1 hellspinlp.com
127.0.0.1 waaw.to
127.0.0.1 areconform.com
127.0.0.1 mixdrop.ag
127.0.0.1 botanysummarytables.com
127.0.0.1 gamerafflezone.com 
127.0.0.1 synottip.cz
127.0.0.1 zaltaumi.net
127.0.0.1 exposepresentimentunfriendly.com
127.0.0.1 zoogripi.com
127.0.0.1 sakuftaurgo.com
```
4. Soubor zpět vlož do `C:\Windows\System32\drivers\etc`
5. Do CMD napiš `ipconfig /flushdns`

## Testováno
- Windows 11: brave, edge(addblock), edge, chromium(addblock), chromium
- Windows 10: brave, edge(addblock), edge, chromium(addblock), chromium

- Pokud najdete další odkaz který zde není, pošlete ho na mail kralicekgamer@gmail.com

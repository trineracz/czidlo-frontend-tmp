CZIDLO
CZIDLO je softwarový nástroj pro podporu národního systému trvalé identifikace ČIDLO (Český systém pro identifikaci a lokalizaci dokumentů digitálního kulturního dědictví) založeného na standardu URN:NBN.

Aktuality
8. 10. 2017 byla nasazena nová verze softwaru CZIDLO (verze 4.3) s novými funkcionalitami - viz projektová stránka.
14. 1. 2019 byla nasazena nová verze softwaru CZIDLO (verze 4.6) s novými funkcionalitami - viz projektová stránka.

Základní funkce nástroje jsou:
 - přidělování identifikátorů URN:NBN (automatizovaně prostřednictvím komunikačního aplikačního programového rozhraní nebo manuálně přes webové rozhraní), identifikátor registrátor obdrží po zaslání metadat identifikovaných dokumentů,
 - správa identifikátorů (např. jejich deaktivace) a k nim přidružených metadat,
 - vkládání a dodatečná aktualizace adres URL digitálních dokumentů, kterým byl přidělen identifikátor URN:NBN (manuálně přes webové rozhraní/automatizovaně přes API/utilitou OAI Adapter),
 - přesměrovávací služba (resolver) zajišťující přesměrovávání webového prohlížeče z URN:NBN na aktuální URL umístění dokumentu, případně na záznam dokumentu v CZIDLO,
 - správa uživatelských účtů, práv a záznamů registrátorů (včetně digitálních knihoven) přes webové rozhraní,
vyhledávání záznamů přes webové rozhraní,
 - spouštění procesů na straně serveru přes webové rozhraní (OAI Adapter, export seznamu identifikátorů),
OAI-PMH rozhraní pro hromadné sklízení záznamů externími systémy.

Nástroj CZIDLO byl vyvinut v letech 2011-2012 v rámci programu \"Koncepce rozvoje Národní knihovny České republiky jako výzkumné organizace na léta 2010-2015\" financovaného Ministerstvem kultury ČR. Softwarové řešení je založeno na opensource technologiích (Java, databáze PostgreSQL, Spring security, GWT aj.) a uznávaných standardech (XML, XSD, XSLT, HTTP, REST aj.). Nástroj je vydaný pod otevřenou licencí GNU GPL v3. Zdrojové kódy, instalační balíky, dokumentace apod. jsou veřejně dostupné na webu projektu. CZIDLO tak podporuje zajištění trvalého přístupu k digitálním dokumentům navzdory změnám internetových adres a zajištění synchronizace mezi různými deriváty digitálního dokumentu v různých systémech (generování jedinečných identifikátorů) a umožňuje verifikovat citace (funkce udržování metadat o identifikovaných dokumentech).

Dokumentace, soubory ke stažení a zdrojový kód aplikace jsou dostupné na webu projektu. Nalezené chyby v aplikaci prosím hlaste na issue tracker.
Dokumentace: https://github.com/NLCR/CZIDLO/wiki
Instalační balíčky: https://github.com/NLCR/CZIDLO
Issue tracker: https://github.com/NLCR/CZIDLO/issues


Vyhledávání
Aplikace umožňuje vyhledávat digitální dokumenty primárně podle identifikátoru URN:NBN, dále podle identifikátoru čČNB (číslo české národní bibliografie), čísel ISSN, ISBN a názvových údajů (např. titul monografie, název periodika) nebo jejich částí.

URN:NBN (např.: urn:nbn:cz:mzk-0005j2)
čČNB (např.: cnb000683872)
ISBN (např.: 9788073210793)

Metodika
Podrobná pravidla pro využívání služby ČIDLO a návody na využívání resolveru URN:NBN jsou popsány v certifikované metodice. Její aktualizovaná verze je dostupná pomocí tohoto odkazu: https://resolver.nkp.cz/urn:nbn:cz:nk-004hvy. 
 
Kontakty

kurátor
Mgr. Filip Pavčík, PhD.
filip.pavcik@nkp.cz

technická správa a podpora
resolver-podpora@nkp.cz

Výzkum a vývoj
Autor koncepce
PhDr. Ladislav Cubr, Ph.D. (2011-2014)

Garant vývoje
PhDr. Zdeněk Vašek, Ph.D. (2014-2017)

Vývoj softwaru
Mgr. Martin Řehánek (2011-2013, 2017-2019)
Mgr. Václav Rosecký (2013)
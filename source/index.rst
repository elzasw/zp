Metodický pokyn č. 4/2022 odboru archivní správy a spisové služby, kterým se vydávají Základní pravidla pro zpracování archiválií ver. 3.1
==========================================================================================================================================

Čj. MV-171396-1/AS-2022

Odbor archivní správy a spisové služby v souladu s pověřením v § 44
písm. a) a b) zákona č. 499/2004 Sb., o archivnictví a spisové službě a
o změně některých zákonů ve znění pozdějších předpisů, kterým mu byla
svěřena působnost v oblasti řízení výkonu státní správy v oblasti
archivnictví a zpracování koncepce rozvoje archivnictví, vydává nová
Základní pravidla pro zpracování archiválií ver. 3.1 (dále jen ZP 3.1).
Text ZP ver. 3.1 včetně příloh je nedílnou součástí tohoto metodického
pokynu.


.. toctree::
   :includehidden:
   :maxdepth: 2
   :numbered: 3
   :glob:
   :caption: Obsah

   01-uvod.rst
   02-arch-zprac.rst
   03-popis-arch.rst
   04-prvky-popisu.rst
   05-rozs-popis-arch.rst 
   06-autor-zazn.rst 
   07-osoba.rst
   08-rod-rodina.rst
   09-korporace.rst
   10-udalost.rst
   11-dilo-vytvor.rst
   12-geo.rst
   13-pojem.rst
   14-instituce.rst


.. toctree::
   :includehidden:
   :maxdepth: 2
   :glob:
   :caption: Přílohy

   p01-priklady-jp.rst
   p02-jazyky.rst
   p03-matriky.rst
   p04-peceti.rst
   p05-veduty.rst
   p06-ead.rst
   p07-sprava-autorit.rst
   p08-tridy-entit.rst
   p09-peva.rst
   p10-priklady-entity.rst
   p11-jurisdikce.rst
   p12-tax-kateg.rst
   p13-zdroje-inf.rst
   p14-puvodci.rst
   p15-zkratky.rst 
   autori.rst


Čl. 1 Úvodní ustanovení
-----------------------

Vydání ZP ver. 3.1 má za cíl:

1. Upravit podmínky pro další implementaci Základních pravidel platných
   v plném rozsahu od 30. září 2022.

2. Kodifikovat částečné upřesnění, dílčí změny a revize ustanovení,
   které nastaly v souvislosti s vytvořením všech softwarových nástrojů
   sloužících k implementaci doposud platných Základních pravidel (dále
   jen ZP ver. 3.0) [1]_, z jejichž textu v kapitolách č. 2, 3, 4, 5 a
   14 přímo vychází.

3. Reflektovat upřesnění a opravy v oblasti sdíleného a kooperativně
   vytvářeného popisu archivních autoritních záznamů spojeného s
   implementací IS CAM vytvořeného v součinnosti Ministerstva vnitra a
   Technologické agentury České republiky a provozovaného Národním
   archivem spojenou s úpravou kapitol 6 až 13 ZP ver. 3.0.

4. Reflektovat ustavení „Pracovního kolegia pro CAM a metodiku záznamů
   archivních entit” (dále jen Kolegium), které vzniklo na základě
   „Memoranda o shodě” Národního archivu a sedmi státních oblastních
   archivů ze dne 3. prosince 2018 (dále jen „Kolegium“) a vymezit jeho
   působnost. 
   
Čl. 2 Postup zavedení Základních pravidel pro zpracování archiválií do praxe
--------------------------------

ZP 3.1 budou zaváděna v souladu s těmito pravidly:

1. ZP 3.1 nemají v oblasti archivního zpracování retrospektivní
   platnost. Předpokládá se, že se využijí při práci s archiváliemi
   dosud nezpracovanými, případně při reinventarizaci archivních souborů
   zpracovaných podle starších pravidel a metodik.

2. O reinventarizaci a úpravě starších pomůcek do podoby kodifikované
   aktuální verzí ZP 3.1 rozhoduje ředitel nebo vedoucí archivu,
   případně kulturně vědecké instituce (dále jen KVI).

3. V oblasti zápisu a oprav archivních autoritních záznamů se jejich
   zápis řídí ZP ver. 3.1 a u stávajících zápisů archivních autoritních
   záznamů se jejich úprava provede nejpozději před jejich synchronizací
   s IS CAM.

4. Ředitel nebo vedoucí archivu nebo KVI rozhoduje rovněž o
   harmonogramu, organizaci, použitých softwarových nástrojích a všech
   dalších otázkách aplikace ZP 3.1, a to podle konkrétních podmínek
   archivu nebo KVI.

5. Rozpracované archivní pomůcky vytvářené před vydáním ZP 1.0 budou
   dokončeny v souladu se ZP z r. 1958, nerozhodne-li vedoucí archivu
   nebo KVI jinak. Rovněž pomůcky vytvářené v souladu se ZP 1.0 nebo ZP
   2.0 nebo ZP 3.0 budou dokončeny v souladu s těmito pravidly,
   nerozhodne-li vedoucí archivu nebo KVI jinak.

6. Při implementaci ZP se doporučuje využít softwarů vytvořených pro
   archivní popis v souladu se Základními pravidly pro zpracování
   archiválií.

7. Při implementaci ZP se doporučuje uplatňovat postup upravený
   „Metodikou implementace pořádacího software ELZA v paměťových
   institucích“, kterou certifikovalo Ministerstvo vnitra 2. ledna 2017
   a která je dostupná na webových stránkách Ministerstva vnitra -
   `https://www.mvcr.cz/clanek/software- <https://www.mvcr.cz/clanek/software-elza.aspx>`__
   `elza.aspx <https://www.mvcr.cz/clanek/software-elza.aspx>`__. Tuto
   metodiku mohou využít i ty instituce, které nepoužívají jako nástroj
   archivního popisu software ELZA.

Čl. 3 Správa dat a jejich přenos
--------------------------------

1. Archivní pomůcky v elektronické podobě se ukládají v IS PEvA II, jako
   součást základní evidence Národního archivního dědictví podle
   schématu SUZAP a nově EAD3 zveřejněného Ministerstvem vnitra na
   webové stránce https://www.mvcr.cz/clanek/archivni-standardy.aspx.
   Schéma na základě EAD3 je nedílnou součástí ZP 3.1. Stejnopisy
   archivních pomůcek v papírové podobě vytvářené podle ZP 3.1 a
   papírové archivní pomůcky vzniklé podle starších pravidel a dokončené
   po 30. září 2022 budou zasílány do druhotné a ústřední evidence tak,
   jako doposud.

2. Sdílené záznamy archivních entit, které jsou vytvářeny v souladu s
   aktuálními ZP, se ukládají v informačním systému „Centrální archivní
   modul pro tvorbu a správu záznamů entit“ (dále jen „IS CAM“). Tyto
   záznamy vznikají v referenčním klientovi IS CAM, v systému „Evidence
   Národního archivního dědictví na Národním archivním portálu“ (dále
   jen „IS PEvA II”) a v externích aplikacích archivů a vybraných
   kulturně vědeckých institucí, které mají ve své péči archiválie.
   Externími aplikacemi jsou míněny zejména ty, které slouží ke
   zpracování nebo prezentaci archiválií. Předávání záznamů a komunikace
   mezi všemi těmito systémy probíhá za podmínek stanovených jinými
   předpisy, a to hlavně provozním řádem IS CAM
   https://cam.nacr.cz/info/ .

3. Při importu dat z informačního systému, který používá jiná pravidla
   než ZP (například knihovnické autority), do systémů vytvořených podle
   ZP, musí dojít k transformaci záznamů podle ZP.

Čl. 4 Odpovědnost za další rozvoj ZP a metodickou pomoc
-------------------------------------------------------

1. Za metodiku upravenou v kapitolách 1 až 5 a 14 ZP 3.1, její výklad a
   rozvoj odpovídá ministerstvo.

2. Za metodiku upravenou v kapitolách 6 až 13 ZP 3.1, její výklad a
   rozvoj odpovídá Kolegium, které plní následující úkoly:

   a. navrhuje Ministerstvu vnitra metodiku pro vytváření a správu
      záznamů entit,

   b. ve spolupráci s Ministerstvem vnitra řeší udržitelnost a další
      rozvoj systému IS CAM,

   c. definuje role, práva a požadavky na uživatele při vytváření a
      správě záznamů entit a stanovuje způsob školení uživatelů,

   d. rozhoduje o vkládání záznamů entit v systému IS CAM, které nejsou
      vytvářeny v rámci evidence nebo zpracování archiválií,

   e. rozhoduje spory v oblasti správy záznamů entit v IS CAM,

   f. poskytuje metodickou pomoc archivům v oblasti implementace kapitol
      č. 6 až 13.

Dotazy týkající se problematiky archivních autoritních záznamů a jejich
aplikace se zasílají e-mailem na adresu – cam@ceskearchivy.cz.

Čl. 5 Zrušovací ustanovení
--------------------------

Tento Metodický pokyn ruší Metodický návod č. 1/2021 odboru archivní
správy a spisové služby Ministerstva vnitra, kterým se vydávají Základní
pravidla pro zpracování archiválií ver. 3.0 (č. j. MV- 23313-5/AS-2021).

Čl. 6 Účinnost
--------------

Metodický návod nabývá účinnosti dnem 17. října 2022.

PhDr. Daniel Doležal, Ph.D. ředitel odboru archivní správy a spisové
služby MV V Praze 4. října 2022

!!! summary “Citace zdroje - soubory ke stažení”

::

   - [Metodický pokyn č. 4/2022 odboru archivní správy a spisové služby, kterým se vydávají Základní pravidla pro zpracování archiválií ver. 3.1 (č. j. MV-171396-1/AS-2022)](attachments/Metodicky_pokyn_AS_c_4-2022_Zakladni_pravidla_pro_zpracovani_archivalii_v3-1_-_20221006.pdf) (pdf, 222 kB)
   - [Základní pravidla pro zpracování archiválií ver. 3.1 (příloha metodického pokynu č. 4/2022)](attachments/Priloha_k_Metodickemu_pokynu_AS_c_4-2022_Zakladni_pravidla_pro_zpracovani_archivalii_v3-1_-_20221006.pdf) (pdf, 7,4 MB)
   - plus další přílohy ke stažení na [https://www.mvcr.cz/clanek/metodiky.aspx?q=Y2hudW09Mw%3d%3d](https://www.mvcr.cz/clanek/metodiky.aspx?q=Y2hudW09Mw%3d%3d)

.. [1]
   Metodický pokyn č. 1/2021 odboru archivní správy a spisové služby,
   kterým se vydávají Základní pravidla pro zpracování archiválií ver.
   3.0 (dále jen ZP 3.0), č. j. MV- 23313-5/AS-2021.

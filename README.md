# IT infrastruktura, provoz a podpora

Zaměřuji se na praktický provoz IT, síťovou diagnostiku, automatizaci a řešení problémů napříč softwarem a hardwarem. Stavím nástroje, které převádějí opakovanou práci podpory a správy systémů do ověřitelných postupů.

## Technické zaměření

| Oblast | Technologie a praxe |
| --- | --- |
| Infrastruktura a sítě | MikroTik, RouterOS, TCP/IP, SNMP, Wi-Fi a diagnostika sítí |
| Systémy a podpora | Windows, Linux, nasazování stanic, řešení hardwarových a provozních problémů |
| Správa zařízení | Apple MDM, PKI, mTLS, APNs a fronty příkazů |
| Automatizace | Python, PowerShell, PHP a nástroje pro omezení ruční práce |
| Web a integrace | TypeScript, Node.js, Next.js, React, FastAPI a API integrace |
| Embedded systémy | ESP32, ESP-NOW, Arduino, Raspberry Pi a bezpečné řízení hardwaru |
| Firemní prostředí | Google Workspace, dokumentace a opakovatelné postupy IT podpory |

## Vybrané projekty

| Projekt | Co ukazuje | Ověřený stav |
| --- | --- | --- |
| [Netmap](https://github.com/dokmar89/netmap) | Diagnostika sítí, MikroTik/RouterOS, SNMP, Wi-Fi a Raspberry Pi appliance | Funkční alpha prototyp s testy a CI |
| [RC PAD firmware](https://github.com/dokmar89/rc-pad-firmware) | ESP32-S3/C3, ESP-NOW, failsafe, telemetrie, párování a řízení RC auta | Firmware přeložen pro oba cíle; hostitelské testy a CI procházejí |
| [EmbedForge](https://github.com/dokmar89/embedforge) | Deterministická elektrická pravidla, solver pinů a napájení, FastAPI a Next.js | 124 testů prošlo, web má ověřené produkční sestavení |
| [Local Apple MDM](https://github.com/dokmar89/local-apple-mdm) | PKI, mTLS, enrollment, APNs a trvalá fronta příkazů | Laboratorní projekt s 21 automatickými testy |
| [Orion UEM/MDM](https://github.com/dokmar89/orion_mdm) | Správa zařízení, backendové rozhraní a provozní dokumentace | Veřejný zdrojový projekt s testy |
| [Windows 11 Deployment Kit](https://github.com/dokmar89/windows-11-deployment-kit) | PowerShell, předinstalační inventura, příprava USB, offline aplikace, ovladače a auditní logy | Anonymizovaná referenční implementace se syntaktickou kontrolou v CI |

README jednotlivých projektů popisují architekturu, spuštění, provedené testy i známá omezení. Laboratorní a embedded projekty výslovně oddělují ověřenou softwarovou část od kontrol, které vyžadují skutečný hardware nebo provozní služby.

## Jak k práci přistupuji

- Nejprve hledám skutečnou příčinu problému a vytvářím opakovatelný postup ověření.
- Bezpečnostní chování, failsafe a hranice důvěry navrhuji přímo do řešení.
- Konfiguraci a přihlašovací údaje držím mimo Git; veřejné ukázky používají fiktivní data.
- Stav projektu popisuji otevřeně, včetně neprovedených testů a provozních omezení.
- Dokumentaci považuji za součást výsledku, ne za dodatek ke kódu.

## Další projekty

- [LAURA automobilový displej](https://github.com/dokmar89/laura-car-display) — ESP32-S3, LVGL, ILI9488 a CAN listen-only prototyp.
- [Modern Jarvis / Artemis](https://github.com/dokmar89/modern-jarvis) — český hlasový asistent pro Windows s omezenými lokálními nástroji.
- [Python Utility Lab](https://github.com/dokmar89/python-utility-lab) — převod stromu projektu do HTML a český přepis zvuku pomocí WhisperX.
- [Decoder](https://github.com/dokmar89/decoder-prototype) — privacy-first Next.js prototyp, verzované prompty a syntetické bezpečnostní scénáře.
- [IT znalostní báze a provozní portál](https://github.com/dokmar89/skolap) — návody podpory, šablony a praktické IT nástroje.

Na profilu jsou také webové integrační projekty, prototypy a starší varianty. Jejich README uvádějí rozsah a stav, aby je bylo možné odlišit od hlavních ukázek. Další anonymizované případové studie budou zveřejněné bez interní topologie a soukromé konfigurace.

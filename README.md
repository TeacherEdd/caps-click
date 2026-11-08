# CAPS Click

CAPS Click is ’n Afrikaanse webprototipe wat Suid-Afrikaanse Graad 5-onderwysers help om lesse vir Natuurwetenskappe en Tegnologie (NW&T) voor te berei en aan te bied. Dit bring lesplanne, klasaktiwiteite, werkkaarte en informele assessering vir Kwartaal 4 op een plek bymekaar.

Die huidige inhoud dek tien voorgestelde weke. Week 1, **Die aarde beweeg**, is die mees volledig uitgewerkte voorbeeld. Kontroleer die voorgestelde weekindeling, inhoud en assessering teen die amptelike jaarlikse onderrigplan (ATP) voordat jy dit in die klas gebruik.

## Kernfunksies

| Funksie | Wat tans beskikbaar is |
| --- | --- |
| Weekinhoud | Tien weekonderwerpe met lesinhoud, aktiwiteite, take en meerkeusevrae vir informele assessering. |
| Lesplanne | Drie lesbenaderings per week. Week 1 se drie lesse sluit leerdoelwitte, benodigdhede, onderrigstappe, informele assessering en differensiasie in. Weke 2–10 gebruik algemene lesraamwerke met weekspesifieke inhoud. |
| Werkkaarte | Drukbare werkkaarte. Week 1 bied drie moeilikheidsvlakke met memorandums. |
| PowerPoint | ’n Voorskou van 12 skyfies vir Week 1 met ’n redigeerbare `.pptx`-aflaai. Die PowerPoint-afdeling vir Weke 2–10 wys ’n boodskap dat dié lesse nog in ontwikkeling is. |
| Lespakket | ’n Week 1-ZIP met ’n PowerPoint, een voorbeeldlesplan en drie werkkaarte met memorandums. Die lesplan dek dag en nag. Die HTML-dokumente kan in ’n blaaier oopgemaak, gedruk of as PDF gestoor word. |

## Tegnologie en lêers

| Lêer | Rol |
| --- | --- |
| [`index.html`](index.html) | Laai die toepassing en eksterne afhanklikhede. |
| [`script.js`](script.js) | Bevat die weekinhoud, koppelvlaklogika en generering van aflaaie in die blaaier. |
| [`style.css`](style.css) | Beheer die uitleg vir verskillende skermgroottes en die drukstyle. |
| [`assets/caps-click-logo.svg`](assets/caps-click-logo.svg) | CAPS Click-logo. |

Die toepassing gebruik gewone HTML, CSS en JavaScript. PptxGenJS 4.0.1 en JSZip 3.10.1 laai via jsDelivr. Plus Jakarta Sans laai via Google Fonts, met stelsellettertipes as alternatief. Die repository bevat geen bedienerkode, pakketmanifes of boustap nie.

## Plaaslike ontwikkeling

Gebruik Git, Python 3 en ’n moderne webblaaier.

```bash
git clone https://github.com/TeacherEdd/caps-click.git
cd caps-click
python3 -m http.server 8000
```

Maak [http://localhost:8000](http://localhost:8000) in jou blaaier oop. Wysig die bronlêers en herlaai die bladsy om veranderinge te sien. Gebruik `Ctrl+C` in die terminaal om die plaaslike bediener te stop.

Die PowerPoint-aflaai benodig PptxGenJS, en die ZIP-aflaai benodig albei biblioteke. Hou internettoegang beskikbaar wanneer jy dié aflaaie toets sodat die blaaier die biblioteke vanaf jsDelivr kan laai.

## Voorbeeldgebruik

1. Maak **Graad 5 NW&T** oop en kies **Week 1**.
2. Kies ’n lesbenadering, byvoorbeeld **Bou ’n model**. Gebruik ’n flits as die son en ’n bal as die aarde om te wys hoe rotasie dag en nag veroorsaak.
3. Kies ’n werkkaart op ’n vlak wat by jou klas pas. Gebruik die memorandum om antwoorde na te gaan.
4. Bekyk die skyfies in die blaaier, laai die PowerPoint af vir klasgebruik of laai die ZIP af om die voorbeeldlesplan en werkkaarte saam te kry.

## Toekomstige verbeterings

Die webblad noem dat meer grade en vakke op pad is. Die repository spesifiseer geen verdere grade, vakke, datums of prioriteite nie. Die volgende is voorstelle wat uit die huidige prototipe volg.

- Voltooi PowerPoint-lesse vir Weke 2–10.
- Brei die lesplanne en werkkaarte vir Weke 2–10 uit met weekspesifieke differensiasie en memorandums.
- Voeg aflaaibare lespakkette vir die oorblywende weke by.
- Dokumenteer die amptelike ATP-verwysings vir elke weekonderwerp.

## Bydraes

Vir ’n foutverslag of inhoudsvoorstel kan jy ’n [GitHub-issue](https://github.com/TeacherEdd/caps-click/issues) oopmaak. Noem die betrokke week en afdeling. Sluit vir ’n fout die stappe in om dit te herhaal, of gee vir ’n inhoudsvoorstel die toepaslike kurrikulumverwysing. Vir ’n kode- of dokumentasiewysiging kan jy ’n pull request met ’n kort beskrywing en jou toetsstappe indien.

**Lisensie en bydraebeleid.** Die repository spesifiseer tans geen lisensie of formele bydraebeleid nie.

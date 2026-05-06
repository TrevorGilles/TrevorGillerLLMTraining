## Tämä on päiväkirja

### Eka viikko 
- ChatGpd ja muut tuotteet ovat eri firmojen LLM tuotteita jotka käyttävät yritysten kehittämää tekoäly mallia hyväksi
- Tekoäly mallit ovat erinomaisia luodaa structuroituja vastauksia, FILL HERE
- Tekoäly on huono mikäli tieto mitä tuotetaan on väärää koska vastaukset ovat todella itsevarmoja 
- API avulla pääset käsiksi eri AI malleihin joita voit käyttää hyödyksi oman LLM mallin tekemiseen 
- Eri LLM mallit: base (ennustaa mitä seuraavaksi kysytään&kirjoitetaan), chat & reasoning/thinking
- Tekoälystä näkyvimmät tuotteet ovat LLM mallit 
- Firmoilla on yleensä kaupallinen LLM malli ja opensource malli
- Suurimmat pelurit: OpenAI, Microsoft, Claude & DeepSeek
- system promt ja user promt erot 
- jokainen pyyntö LLM on "stateless" - miten LLM saa muistin on että jokaisessa pyynnössä menee aiempi keskustelu listassa jolloin AI muistaa aiemmat keskustelut
-- "trick; it's a by-product of providing the entire conversation, **every time**"
-- input tokenin on hinta on matala, tässä huomioita että kaikki aiempi keskustelu tulee lähetää kun teet uuden pyynnön mikä nostaa hintaa
- API hinnat
-- LLM tuotteilla on erilaiset paketit 
-- APIlla maksat vain "use per API call" -> maksat "compute costs"
--- Maksu tulee kuinka paljon laitat input tokeneja & saat output tokeneja per pyyntö
--- output vastauksissa maksetaan myös LLM "perustelusta&ajattelusta" mitä tekoälyn on tehtävä vastauksen muodostamiseksi. Tässäkin tekoäly malli joutuu tekemään laskentaa joka on ns. veloitettavaa työtä -> tätä ei näe vastauksessa mikä nostaa LLM vastauksen hintaa koska tätä ei yleensä paljasteta
- GPT5 mallissa esimerkiksi input 1.25$ per miljoona tokenia ja output 10$ per miljoona tokenia. Shakespeare kirja on esimerkiksi 900 000 sanaa joka tarkoittaa 1.2M tokenia. Lisää tietoa https://www.vellum.ai/llm-leaderboard
-- Grok 4 on ilmainen ja Clauden mallit ovat kalliita
- Tärkeää huomioida mikä on max token määrä mitä context window voi ottaa vastaan -> tässä on limitit eli AI malleilla. Esim. Genimi2.5 flash on tosi iso ja GPT OSS on pieni
- AI on harjoitettu datalla, markdown ja json -> näitä on AI helppo ymmärtää
- LLM parhaiten saat vastauksia kokeilemalla ja opiskelemalla => iteroimalla saat parhaat vastaukset
- Hyvä AI insinööri on data tieteilijä ja insinööri 
- Stream=True jolloin tulee hienossa UI tyylissä flow:na output token vastaukset  





### selvitä näitä
- VS code agents & skills 
- context engineering => how to inform LLM better
- testaa ClaudeCode
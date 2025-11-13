# AI-Dexter-Web
Použité Ai
ChatGPT (GPT-5 mini) – tvorba HTML a CSS

 Prompt a komunikace s ChatGPT
1.  potřebuju stranku a potřebuju porad na jake tema bude to wed o 3 stránkách

2. udělej mi web o serialu Dexter a musi tam byt uvod a 3 dalsi stranky

3. udělej vic s tematikou dextera a nepoužívej obrazky z wikipedie ale online at to tam je treba jako pozadi

4. to funguje i na mobily jenom zmen style.css

5. přidej mi do postav jestě angela a doakse

6. udělej at mužu dat pod batistu a doakse youtube video

Použité CSS a jeho funkce


a) Hlavní styl

Pozadí: temné, krvavé pozadí s obrázkem (background: url(...))

Hlavička: tmavá s červenou linkou a svítícím nadpisem (text-shadow)

Menu: červené akcenty, hover efekty, responzivní přizpůsobení

Obsah (main): černé průhledné pozadí (rgba(0,0,0,0.75)), stíny, zaoblené rohy

Odkazy, seznamy: zvýrazněné, čitelné, barevné kontrasty

b) Obrázky

Zaoblené rohy, červený okraj, stín pro dramatický efekt

Responzivní (max-width: 100%)

c) Patička (footer)

Zůstává dole i u krátkého obsahu (flex, flex-direction: column, main { flex:1 })

Barevně ladí s webem, jemná červená linka

d) Responzivita

Media queries pro obrazovky do 768px a 480px

Přizpůsobení fontů, menu, obsahu a videí

YouTube videa responsivní přes .video-container s poměrem 16:9
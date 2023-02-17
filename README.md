# MTTPP-projekt
## O projektu

U sklopu projekta testirana je stranica https://demowebshop.tricentis.com. Stanica je javna, te je osmišljena za testiranje.<br/>

## Korišteni alati

Apache JMeter - alat za automatizirano testiranje, pomoću kojega su izvršeni testovi i postavljeni uvjete testiranja, također je korišten za analizu testova (listener elementima, View Results Tree, Graph Results i Aggregation Report) i za generiranje konačnog izvješća. <br/>
BlazeMeter - ekstenzija za Chrome Browser koja omogućuje snimanje aktivnosti na webu i export te snimke u obliku *.jmx file-a koji je korišten unutar JMeter-a.

## Što je testirano

U sklopu projekta, testirane su pet funkcionalnosti web stranice: Login_Logout, Change_Password, Sign_up_for_Newsletter, Search_and_Remove_From_Cart, Add_to_Cart_and_Order. Svi testovi su odrađeni unutar jedne thread grupe i svaki test je imao vlastiti lisner (View Results Tree, Graph Results i Aggregation Report). Korišteno je 200 threadova (korisnika) s ramp-up periodom od 10 sekundi.

## Postupak kreiranja test

1. Otvaranje Google Chrom pretražitelja.
2. Pokretanje snimanja koraka uporabom ekstenzije BlazemMeter
3. Unošenje web adrese stranice https://demowebshop.tricentis.com
4. Izvršavanje testirane funkcionalnosti
5. Prekidanje snimanja
6. Exportiranje snimke u *.jmx formatu
7. Otvaranje kreirane snimke u Apache JMeter
8. Individualno testiranje
9. Pregled rezultata

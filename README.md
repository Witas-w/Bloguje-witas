# Witas bloguje
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>testowa.pl</title>
        <style>
      
        body{
         color: white; 
    background: #396f38;
    margin: 0;
    
   
   
        }
        table{
        color: black;
        }
       .menu-1{
           background: white;
           top: 0px;
           width: 100%;
           height: 70px;
           position: absolute;
           font-family: Arial;
           float: left;
          left: 0px;
       }
       #aut{
        
         color: green;  
       }
      #klik{
         color: grey; 
      }
    
      
      
      #lokiter{
          z-index: 2;
          background-color: #4e9447;
          position: absolute;
          top:300px;
          right: 0px;
         left: 0px;
         font-size: 20px;
         Text-align: center;
      }
      #akt{
          border-bottom:1px solid white;
          
      }
      .img{
          float: left;
          top: 75px;
          left: 0px;
          width: 30%;
          height: 30%;
          position: fixed;
      }
      .styled {
    border: 0;
    line-height: 2.5;
    padding: 0 20px;
    font-size: 1rem;
    text-align: center;
    color: #fff;
    text-shadow: 1px 1px 1px #000;
    border-radius: 10px;
    background-color: rgba(220, 0, 0, 1);
    background-image: linear-gradient(to top left,
                                      rgba(0, 0, 0, .3),
                                      rgba(0, 0, 0, .2) 30%,
                                      rgba(0, 0, 0, 0));
    box-shadow: inset 2px 2px 3px rgba(255, 255, 255, .6),
                inset -2px -2px 3px rgba(0, 0, 0, .6);
}

.styled:hover {
    background-color: rgba(255, 0, 0, 1);
}

.styled:active {
    box-shadow: inset -2px -2px 3px rgba(255, 255, 255, .6),
                inset 2px 2px 3px rgba(0, 0, 0, .6);
}

#img {
       position: absolute;
       z-index: 1;
      height: 230px;
      bottom: 0px;
       top: 70px;
       width: 100%;
       right: 0px;
       left: 0px;
       }
       
        
       .nav{
           
           position: absolute;
           text-align: right;
           color: black;
           height: 30px;
           line-height: 30px;
           right: 0px;
           top: 20px;
           z-index: 3;
       }
       .menu{
         margin-right: 30px;  
       }
       .menu a{
           clear: right;
           text-decoration: none;
           color: black;
           position: relative;
           line-height: 40px;
           margin-right: 30px; 
       }
       label{
           position: absolute;
           font-size: 26px;
           line-height: 40px;
           display: none;
           width: 26px;
           right: 10px;
           
       }
       #toggle{
           display: none;
           top: 10px;
           right: 10px;
       }
       
       
       
       @media only screen and (max-width: 500px){
         label{
          
           
          
           display: block;
           cursor: pointer;
}  
         .menu{
           display: none;
           text-align: center;
           width: 400px;
          position: relative;
          top: 25px;
          right: 0px;
          left: 0px;
           margin-right: 0px;
}
         .menu a{
           display: block;
           width: 400px;
           text-decoration: none; 
           border-bottom: 1px solid black;
           margin: 0;
           color: black;
           background-color: white;
           top: 25px;
           right: 0px;
           left: 0px;
            text-align: center;
          }
          
          #toggle:checked + .menu {
          display: block;
}
       }
       a:hover{
          background-color: red;
          color: white;
       }
       a:active{
          background-color: red;
           color: white;
       }
        </style>
    </head>
    <body>
    <div class="menu-1">
    
        <p><span id="aut">Autor:</span><span id="klik"><em><strong> JAKUB<BR>WITKOWSKI</strong></em></span></p>
         </div>
         <div class="nav"> 
         <label for="toggle">&#9776;</label>
         <input type="checkbox" id="toggle">
         <div class="menu">
      <a href="https://witas-w.github.io/Aktualnosci/">Aktualności</a>
            <a href="https://witas-w.github.io/Bloguje-witas/">Blog</a>
            <a href="https://witas-w.github.io/Galeria-zdjec/">Zdjęcia</a>
     </div>  
        
     </div>   
        
          
          <img id="img" src="https://s6.ifotos.pl/img/670C82C4-_qseaxrh.jpg">
          
        <div id="lokiter">
         <h2 id="akt" >Blog</h2>
  <a href="#DD"><button class="styled"
        type="button">
   Dzień dzisiejszy
</button></a>
  <h3>26.06.2019r.</h3>
  
  <p>Dzisiaj było 30 stopni w cieniu przez co piasek bardzo mocno parzył.W porcie nadal stoi "Unicus".Może jutro przypłynie "Dragon".Byliśmy też po stronie wschodniej na pysznych lodach w "Górze Lodowej".(pod spodem znajduje się mój ranking lodów).</p>
  
  <table>
        <thead>
            <tr>
                <th>Nazwa</th>
                <th>punkty</th>
            </tr>
        </thead>
        <tbody>
            <tr>
               
                <td>1.Góra Lodowa</td>
                <td>100/100</td>
            </tr>
            <tr>
                
                <td>1.U Lodziarzy</td>
                <td>100/100</td>
            </tr>
            <tr>
               
                <td>2.Bacio</td>
                <td>93/100</td>
            </tr>
            <tr>
               
                <td>3.Chomczyńscy</td>
                <td>74/100</td>
            </tr>
            <tr>
               
                <td>4.Jablonowscy</td>
                <td>60/100</td>
            </tr>
            <tr>
               
                <td>5.Mistral</td>
                <td>37/100</td>
            </tr>
            
        </tbody>
    </table>
    
    <h3>27.06.2019r.</h3>
    <p>(godz.15:02)Właśnie wróciliśmy ze Słupska gdzie byliśmy w galerii handlowej "Jantar". W galerii byliśmy w kilku księgarniach.Po powrocie zamówiliśmy pizze.Następny wpis pojawi się wieczorem.O Słupsku przeczytacie pod spodem.</p>
    <p class="pod"><strong><em>Słupsk</em></strong> to miasto na prawach powiatu w północnej Polsce, w województwie pomorskim, siedziba władz powiatu słupskiego oraz gminy Słupsk. Leży na Pobrzeżu Koszalińskim, nad Słupią, przy trasie europejskiej E28, dawna siedziba książąt pomorskich.</p>
    <p>Po powrocie ze <strong>Słupska</strong> poszliśmy do <em>Góry Lodowej</em>.A następnie do baru III molo i na plażę.</p>
    <h2>Ranking gofrów</h2>
    <table>
        <thead>
            <tr>
                <th>Nazwa</th>
                <th>Punkty</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1.Bar 3 molo</td>
                <td>100/100</td>
            </tr>
            <tr>
                <td>1.Chomczyńscy</td>
                <td>100/100</td>
            </tr>
            <tr>
                <td>2.Lody,Gofry</td>
                <td>87/100</td>
            </tr>
            <tr>
                <td>3.Kołacze,Gofry,Lody</td>
                <td>76/100</td>
            </tr>
        </tbody>
    </table>
    <img class="byk" src="https://www.kasandbox.org/programming-images/landscapes/sand-dunes.png" >
    <h3>28.06.2019r.</h3>
    <p>Dzisiaj w nocy przypłynął do Ustki największy galeon w Polsce <strong><em>Dragon</em></strong>. <em>Unicus</em> odpłynął wczoraj i także od rana stoi w Darłówku.Do portu w nocy zagościł kontenerowiec <em>Riona</em> .Przed chwilą wpłynął do portu okręt Marynarki wojennej <em>ORP Wigry</em>.Riona opuściła port ok.16:00</p>
    <h2>Przypłynięcia i odpłynięcia</h2>
    <table>
        <thead>
            <tr>
                <th>Statek</th>
                <th>Data przypłynięcia</th>
                <th>Data odpłynięcia</th>
                <th>Rodzaj</th>
                <th>Miejsce odpłynięcia</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><strong>Dragon</strong></td>
                <td>28.06.2019r.</td>
                <td>brak</td>
                <td>pasażerski</td>
                <td>brak</td>
            </tr>
            <tr>
                <td><strong>Riona</strong></td>
                <td>28.06.2019r.</td>
                <td>brak</td>
                <td>kontenerowiec</td>
                <td>Hellsdorf
                </td>
            </tr>
            <tr>
                <td><strong>Unicus</strong></td>
                <td>brak</td>
                <td>28.06.2019r.</td>
                <td>pasażerski</td>
                <td>Darłowo</td>
            </tr>
            <tr>
                <td><strong>ORP Wigry</strong></td>
                <td>28.06.2019r.</td>
                <td>brak</td>
                <td>wojskowy</td>
                <td>brak</td>
            </tr>
        </tbody>
    </table>
    <h3>30.06.2019r.</h3>
    <p>Dzisiaj byliśmy w <em>Górze Lodowej</em>.Następnie poszliśmy na gokarty.Jedliśmy też rybę w <em> Złotej rybce</em>.Zaraz idziemy na gofry.</p>
    <h3>1.07.2019r.</h3>
    <p>Dzisiaj byliśmy w <em><strong>Dolinie Charlotty</strong></em>. A następnie poszliśmy do <em> Mar-Huba</em>.</p>
  <h3>2.07.2019r.</h3>
  <p>Po wyjściu z domu o godz.12:10 poszliśmy na targ.Następnie wypożyczylismy gokarty na pół godziny. przeszliśmy się do <em>Mistrala</em> gdzie zjedliśmy obiad. Na promenadzie weszliśmy do salonu gier gdzie wygrałem z dziadkiem 4 rundy w cymber guy-u.Dzisiaj jest duży sztorm więc kładka otwarta jest prawie cały dzień.</p>
  <h3>3.07.2019r.</h3>
  <p>Dzisiaj zjedliśmy obiad na <em>Politechnice Wrocławskiej</em>.Ponownie w dniu dzisiejszym nastąpił sztorm.Kładka jest dokładnie tak jak wczoraj otwarta przez cały dzień.</p>
  <h3>4.07.2019r.</h3>
  <p>Dzisiaj było duże zamieszanie z obiadami.Ostatecznie ustaliliśmy że obiady będą na trzynastą. Nadal jest sztorm i kładka cały dzień otwarta.Jedliśmy też pyszną galaretkę w <em>Bacio</em>.</p>
  <h3>5.07.2019r.</h3>
  <p>Dzisiaj był sztorm.Kładka tym razem nie była otwarta cały dzień lecz 35 minut.Statki nie stały już pochowane, a było ich zwiedzanie.<em>Kasieńka II</em>wypływała do kanału portowego gdzie zawracała do stoczni.<em>Dragon był zwiedzany za 5 złotych od osoby</em>.</p>
  <h3>6.07.2019r.</h3>
  <p>Dzisiaj byliśmy na obiedzie pobktórym poszliśmy na automaty.
  Po grze udaliśmy się do <em>Bacio</em>gdzie zjedliśmy galaretkę.Cały dzisiejszy dzień leje deszcz i jest trochę zimno.</p>
  <h3>7.07.2019r.</h3>
  <p>Dzisiaj byliśmy na obiedzie.Po nim poszliśmy na automaty.Wieczorem zjedliśmy galaretkę w <em>Bacio</em>.</p>    <h3 >8.07.2019r.</h3>
  <p>Dzisiaj byliśmy na obiedzie.A po nim poszliśmy z babcią na automaty.</p>
  <h3>9.07.2019r.</h3>
  <p>Dzisiaj byliśmy na obiedzie.Po nim poszliśmy do chińskiego marketu.Cały dzień lało.Jedliśmy też galaretkę i lody.</p>
  <h3>10.07.2019r.</h3>
  <p>Dzisiaj mieliśmy przerwę od obiadu więc poszliśmy do <em>Starej pierogarni</em>.Babcia zjadła pierogi ze szpinakiem dziadek ruskie i ze szpinakiem, a ja ruskie.
Po nim poszliśmy z babcią na wschodnią stronę.Gdy przechodziliśmy przez kładkę zaczęło lać i zaczęła się burza z piorunami.Musieliśmy się gdzieś schować.Gdy wracaliśmy zaczęło znowu lać.  </p>
  <h3>11.07.2019r.</h3>
<p>Dzisiaj obiad zjedliśmy w domu.Babcia i dziadek przyjechali o 19:00.Dziś świeciło słońce więc wyszliśmy na 5 godzin.</p>
  <h3>12.07.2019r.</h3>
  <p>Dzisiaj byliśmy na obiedzie i spotkaliśmy się z drugimi dziadkami.Poszliśmy też na lody do <em>Góry lodowej</em>.Gdy wyszliśmy drugim razem wypatrzyłem kontenerowiec płynący z Darłowa.Widzieliśmy też pokazy, w których uczestniczyły samoloty i paralotnie.</p>
  <h3>13.07.2019r.</h3>
  <p>Dzisiaj poszliśmy na obiad. Po nim poszliśmy na gokarty. Wtedy zaczęło kropić ale po dwóch minutach przestało. Wróciliśmy, więc do domu zachaczając o <em>Górę Lodową</em>. Potem wróciliśmy na miasto i poszliśmy na promenadę. Statek SM PRC 112 opuścił port wczoraj około godziny 20, a wrócił o 22. Stoi on dzisiaj przy nabrzeżu po drugiej stronie kładki. Przed koncertem poszliśmy na kolację do <em>Tawerny portowej</em>. Następnie poszliśmy na koncert Kamila Bednarka. Widzieliśmy też pokazy akrobacji lotniczych, spadochroniarskich i bardzo nisko lecący samolot wojska polskiego Casa.</p>
 <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b1/20140628_CASA_C-295_Ma%C5%82opolski_Piknik_Lotniczy_6987.jpg/800px-20140628_CASA_C-295_Ma%C5%82opolski_Piknik_Lotniczy_6987.jpg">
 <h3>14.07.2019r.</h3>
  <p>Dzisiaj byliśmy na obiedzie. Po nim poszliśmy na promenadę. W porcie oglądaliśmy statek SM PRC 112, który razem z barką pogłębia wejście do portu. Przez to <em>Dragon</em> wypływał 4 razy dziennie. Podczas wypłynięcia <em>Dragona</em> statek SM PRC 112 także opuszcza port wypływając blisko brzegu, a następnie wraca i wykręca w kanale portowym. Następnie poszliśmy na automaty i do <em>Bacio</em>. Wieczorem zaprosiliśmy drugich dziadków na wino.</p> 
 <h3>15.07.2019r.</h3>
  <p>Dzisiaj poszliśmy na obiad. Po nim przeszliśmy się plażą do Perły. Następnie wróciliśmy do domu zahaczając o <em>Górę Lodową</em>. Wieczorem wyszliśmy przejść się po okolicy</p>
  <h3>16.07.2019r.</h3>
  <p>Dzisiaj byliśmy na obiedzie. Po nim poszliśmy do <em>Lubicza</em> na  kawę i lody. Następnie przeszliśmy się promenadą do portu. W porcie stoją dwa nowe statki Imor i Mewo Navigator. Imor ostatnio był w Ustce podczas budowy kładki.Wieczorem poszliśmy jeszcze do Lidla na zakupy.</p>
  <h2 id="os">O statkach</h2>
  <table>
    <thead>
        <tr>
            <th>statek</th>
            <th>rodzaj</th>
            <th>data przypłynięcia</th>
            <th>data odpłynięcia</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Imor</td>
            <td>badawczy(Jednostka przystosowana do badań strefy przybrzeżnej i płytkich wód zalewowych.)</td>
            <td>16.07.2019r.</td>
            <td>17.07.2019r.</td>
        </tr>
        <tr>
            <td>Mewo navigator</td>
            <td>badawczy(Jednostka pomiarowa służąca do prowadzenia hydrograficznych prac pomiarowych na wodach morskich.)</td>
            <td>16.07.2019r.</td>
            <td>17.07.2019r.</td>
        </tr>
    </tbody>
    </table>
   <h3>17.07.2019r.</h3>
   <p>Dzisiaj byliśmy na obiedzie. Następnie poszliśmy na promenadę i do sklepu <em>Pierre Rene</em>. Potem poszliśmy do portu i na Marynarki. Wracając poszliśmy na gofra do <em>Chomczyńskich</em>. Wieczorem poszliśmy przez kładkę do portu obejrzeć niemiecki żaglowiec.</p>
   <h3>18.07.2019r.</h3>
 <p>Dzisiaj byliśmy na obiedzie. Po nim poszliśmy na promenadę. Następnie zagraliśmy na automatach w cymber guya. Statek SM PRC 112 wraz z barką Małż 2 pogłębia wejście do portu przez co Dragon wypływa 5 razy dziennie. Gdy wychodziliśmy z portu zauważyłem  statek firmy <em>Akva group</em>, którego wciągano na dok. Chyba jutro będzie jego wodowanie. Wieczorem poszliśmy na ognisko na Politechnice gdzie zjedliśmy kiełbasę i chleb. </p>
   <h3>19.07.2019r.</h3>
   <p>Dziś rano poszliśmy do portu. Gdy do niego weszliśmy odbywało się wodowanie statku <strong>Hollendaren</strong> zbudowanego przez firmę <em>AKVA group</em>. Podczas zanurzania doku gdy wyciągano statek liną podpłynęły dwa statki Złota rybka i Lucek. Podczas obrotu statku zahaczył on oponami o nabrzeże, dok i barierkę. Po wodowaniu statku stanął on przy nabrzeżu stoczni. Po pobycie w porcie poszliśmy na obiad. Następnie idąc promenadą poszliśmy do portu gdzie widzieliśmy statek SM PRC 112 pogłębiający kanał portowy i cztery statki brytyjskie należące do NATO. Przeszliśmy się także ulicą Grunwaldzką do Pasażu Bałtyckiego i Mariny. Wieczorem poszliśmy na plażę zachodnią. Wykopałem tam duży most z piasku. </p>
    <img src="https://i.ibb.co/SJY9YGX/D8-B9-A7-E4-D769-4727-8-AD1-5730409-B15-BE.png">
   <img src="https://i.ibb.co/HF6M6bV/81-A58662-34-C0-493-B-B211-A59-C36416-B70.jpg">
   <img src="https://i.ibb.co/nj074kK/074-B68-BA-5-C32-4-A10-8-A89-7-D69-F6-C318-A4.png">
    <h3>20.07.2019r.</h3>
    <p>Dzisiaj byliśmy na obiedzie. Po nim poszliśmy do <em>Lubicza</em>. W galerii zdjęć znajdują się zdjęcia panoramy Ustki. Następnie poszliśmy na promenadę i na pączki. W porcie statek SM PRC 112 nadal pogłębia kanał portowy. Potem poszliśmy na ulicę Marynarki. Wieczorem poszliśmy na plażę zachodnią. Tam oglądaliśmy zachód słońca.</p>
    
    <h3>21.07.2019r.</h3>
    <p>Dzisiaj byliśmy na obiedzie. Po nim poszliśmy do <em>Lubicza</em>. Tam wypiłem sok pomarańczowy i obejrzałem panoramę Ustki z dachu hotelu. Następnie przechodząc promenadą oglądaliśmy stoiska górali. Wchodząc do portu wstąpiliśmy na pączki do <em>Starej pączkarni</em>. Do portu przypłynął statek badawczy Mewo navigator, o którym można przeczytać w <a href="#os">tabeli z dnia 16.07.2019r.</a> Po pobycie w porcie skierowaliśmy się do domu. Wieczorem poszliśmy na plażę zachodnią gdzie zbudowałem most z piasku. </p>
  
   <h3>22.07.2019r.</h3>
  <p>Dzisiaj byliśmy na obiedzie. Po nim poszliśmy plażą do Perły. Następnie idąc promenadą doszliśmy do portu. Tam stoi statek Mewo navigator, którego zdjęcia można zobaczyć w <a href="https://witas-w.github.io/zdjecia-galeria/">galerii zdjęć</a>. Potem poszliśmy na ulicę Marynarki polskiej i do kawiarni <em>Bacio</em>. W kawiarence wypiłem sok i zjadłem lody. Następnie poszliśmy na przystanek autobusowy skąd zabrał nas autobus lini numer 1. Nim dojechaliśmy do przystanku Wilcza/Darłowska, na którym wysiedliśmy. Jechaliśmy pierwszy raz autobusem przez nowo otwartą ulicę Darłowską.</p>
  
  
  <h3>23.07.2019r.</h3>
  <p>Dzisiaj byliśmy na ostatnim obiedzie. Po nim poszliśmy do <em>Mistrala</em> na Marynarki poskiej, ponieważ ten na Kaszubskiej był przepełniony. Następnie wróciliśmy ulicą Darłowską do domu. Wieczorem poszliśmy do <em>Mistrala</em> po stronie zachodniej i na promenadę, którą doszliśmy do parku Chopina. Po przejściu ulicą Żeromskiego i wstąpieniu do <em>Mistrala u przyjaciół</em> wróciliśmy na promenadę. Statek SM PRC 112 rano pogłębiał ujście Słupii przez co kładka nie została otwarta o godzinie dwunastej i <em>Dragon</em> musiał krążyć na redzie, a wieczorem odwrócony był dziobem w stronę mostu kolejowego i tam barka Małż 2 pogłębiała Słupię.</p>
    
    
    <h3>24.07.2019r.</h3>  
  <p>Dzisiaj byliśmy w sklepie <em>Diverse</em>. Następnie poszliśmy przez port na promenadę i na automaty. Potem wstąpiliśmy na Politechnikę Wrocławską. W <a href="https://witas-w.github.io/zdjecia-galeria/">galerii zdjęć</a> pojawiły się zdjęcia z osiedla Kościelniaka położonego w Ustce zachodniej. Wieczorem poszliśmy na plażę zachodnią i do herbaciarni <em>(nie)winna piwniczka</em>. W tym lokalu można wypić herbatę, zjeść ciastko z wróżbą lub pyszny serniczek. Następnie wróciliśmy do części zachodniej przez kładkę i nasz skrót leśny. Podczas pobytu na plaży widzieliśmy wypływający załadowany po brzegi statek SM PRC 112. W porcie statki zamieniły się miejscami <em>Dragon</em>stanął w miejscu <em>Kasieńki</em> i <em>Saby</em>, a <em>Saba</em> z <em>Kasieńką</em> w miejscu <em>Dragona</em>.</p>

 <h3>25.07.2019r.</h3>
 <p>Dzisiaj rano poszliśmy do Ustki wschodniej. Idąc ulicą Marynarki doszliśmy do portu stamtąd poszliśmy na promenadę. Następnie przeszliśmy się ulicą Wczasową do Energetyka i na <em>Trakt Solidarności</em>. Potem zjedliśmy obiad w restauracji <em>Mistral u Przyjaciół</em>. Po obiedzie poszliśmy do domu przez ulicę Darłowską. Wieczorem poszliśmy do baru 3 molo i na plażę zachodnią. Nią przeszliśmy się do osiedla. </p>
    
      <h3>26.07.2019r.</h3>
 <p>Dzisiaj rano poszliśmy do Ustki wschodniej. Tam weszliśmy do Jabłonowskich i kupiliśmy kawę. O godzinie 12 wróciliśmy do Ustki zachodniej kładką. Potem poszliśmy do restauracji <em>Krzywy róg</em> gdzie zjedliśmy pyszne pierogi i rosół. Wieczorem poszliśmy na plażę zachodnią i przeszliśmy się do rzeki Czarnej, która została zasypana przez wydmy. Statek SM PRC 112 nadal pogłębia port koło mostu kolejowego.</p>
 
 <h3>27.07.2019r.</h3>
 <p>Dzisiaj rano poszliśmy na pierwszy obiad w tym turnusie. Potem udaliśmy się do <em>Mistrala</em> na Kaszubskiej. Tam zjadłem lody i pączka. Następnie przesliśmy się ulicą Marynarki do portu. W porcie i na promenadzie odbywają się pokazy akrobacji rowerowych. Po obejrzeniu akrobacji rowerowych doszliśmy promenadą do parku Chopina. Wieczorem wróciliśmy do domu.  </p>
 
 <h3>28.07.2019r.</h3>
 <p>Dzisiaj byliśmy na obiedzie. Następnie poszliśmy do <em>Lubicza</em> gdzie wypiłem sok pomarańczowy. Potem udaliśmy się do <em>Góry  Lodowej</em>. Tam zjadłem dwie gałki najlepszych lodów w Ustce. Po zjedzeniu lodów doszliśmy ulicą Marynarki na pączki do <em>Starej pączkarni</em>. Zjedliśmy pączki i wracając do domu przeszliśmy przez kładkę.</p>      
       
  <h3>29.07.2019r.</h3>
  <p>Dzisiaj byliśmy na obiedzie. Po nim udaliśmy się z babcią 2 kilometry za Orzechowo. Mogliśmy dojść do Poddąbia, ale było strasznie gorąco. Następnie wróciliśmy do Ustki plażą i nową promenadą. Na promenadzie zjadłem gofra u <em>Chomczyńskich</em> i jednego pączka ze <em>Starej Pączkarni</em>. Potem poszliśmy do portu i widzieliśmy wypływający statek SM PRC 112, a gdy za drugim razem udaliśmy się tam  ponownie oglądaliśmy ten statek, który powrócił z morza. Wieczorem wróciliśmy ulicą Marynarki do domu.</p>
  
  
 <h3>30.07.2019r.</h3>
 <p>Dzisiaj jak codzień byliśmy na obiedzie. Po nim poszliśmy do <em>Mistrala tu i teraz</em> znajdującego się przy ulicy Marynarki. Potem udaliśmy się do portu, gdzie statek SM PRC 112 pogłębia Słupię w okolicy nowej mariny. Zdjęcia tego statku można zobaczyć w <a href="https://witas-w.github.io/Galeria-zdjec/">galerii zdjęć</a>. Następnie wróciliśmy przez ulicę Darłowską do domu. Wieczorem wybrałem się z babcią nad <em>Staw Upiorów</em>, a następnie doszliśmy do ulicy Wilczej. Wracając poćwiczyliśmy na różnych urządzeniach na ścieżce zdrowia.</p>
  
  
  <h3>31.07.2019r.</h3>
  
  <p>Dzisiaj rano udaliśmy się na pocztę nadać pocztówki. Następnie dotarliśmy na obiad przez park Chopina. Po obiedzie poszliśmy do portu, gdzie widzieliśmy rozkładający się <em>TVN Projekt plaża</em> oraz statek SM PRC 112 stojący obok żurawika portowego. Potem wybraliśmy się do <em>Bacio</em> gdzie zjadłem dwie gałki lodów. Po wizycie w kawiarni udaliśmy się do <em>Mistrala</em> na Kaszubskiej na lemoniadę poziomkową. Następnie postanowiliśmy iść do <em>Góry Lodowej</em>. Idąc ulicą Bakuły z bacią dotarliśmy do <em>Pasażu Bałtyckiego</em>. Wieczorem wróciliśmy do domu autobusem lini numer 1. </p>
  
  <h3>1.08.2019r.</h3>
  
  <p>Dzisiaj rano udaliśmy się na obiad. Po nim wybraliśmy się do <em>Mistrala</em> na Kaszubskiej. Potem poszliśmy do <em>Bacio</em>,    w którym zjadłem dwie gałki lodów. Następnie oglądaliśmy statek SM PRC 112 stojący w porcie. Po tej wizycie udaliśmy się na ulicę Leszka Bakuły, gdzie w niedziele odbywa się targ. Później wybraliśmy się do domu towarowego <em>Stodoła</em>. Następnie ponownie weszliśmy do portu oglądać barkę pogłębiającą, która stoi obok miejsca <em>Dragona</em>. Wieczorem wróciliśmy do domu autobusem lini numer 1 i zjedliśmy pierogi w <em>Starej pierogarni</em>. </p>
  
  <h3>2.08.2019r.</h3>
  
  <p>Dzisiaj rano bylśmy na obiedzie. Po nim udaliśmy się do <em>Bacio</em> gdzie zjadłem dwie gałki lodów. Potem wybraliśmy się do portu. Gdy go opuściliśmy spostrzegłem jadnostkę Stefan wpływającą na redę, dlatego wrócilśmy się i oglądaliśmy ten okręt. Stefan jest statkiem należącym do firmy <em>PRC</em>, która posiada także  dwie barki Małża 2 i SM PRC 112. Następnie poszliśmy z babcią na plażę, gdzie w okolicach <em>Perły</em> usiedliśmy i odpoczeliśmy. Później wyruszyliśmy na ulicę Marynarki. Wieczorem wróciliśmy do domu przez Darłowską, która nadal jest w remoncie.</p>
  
  <h3>3.08.2019r.</h3>
  
  <p>Dzisiaj wstałem trochę wcześniej. Po śniadaniu wyruszyliśmy do miasta. Na ulicy Marynarki trwały przygotowania do występów teatralnych  w ramach <em>festiwalu Mistral</em>. Przez te występy główny deptak w Ustce został zmknięty dla samochodów. Dużą scenę rozłożono również przed latarnią morską. Obiad jak zwykle zjedliśmy o godzinie trzynastej. Po obiedzie poszliśmy do kawiarni <em>Bacio</em>, gdzie zjadłem ogromną porcję lodów. Potem udaliśmy się na wschodni falochron odwiedzić ustecką syrenkę. Następnie wróciliśmy na chwilę do domu. Odpoczeliśmy i wybraliśmy się do trzeciego mola. Tam byliśmy na plaży do godziny dwudziestej. </p>
  
  
  <h3 id="DD">4.08.2019r.</h3>
  <p>O trzynastej zjadłem obiad. Po nim poszedłem z dziadkami do kawiarni <em>Lubicz</em>. Następnie po spacerze ulicami Ustki w stronę morza udaliśmy się na molo. Tam zrobiłem kilka zdjęć namiotów <em>Projektu Plaża TVN</em>, które dostępne są w galerii zdjęć. Wracając wstąpiliśmy do kawiarni <em>Bacio</em> na lody. Wieczorem wybraliśmy się na kolację do restauracji<em>Krzywy róg</em>, gdzie zjedliśmy pyszne pielmieni. <em>Krzywy róg</em> jest restaracją polsko-ukraińską. Mają bardzo dobre jedzenie.</p>
  
  
  
       </div>
       
       
       
   
 
    </body>
</html>

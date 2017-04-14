[See assignment in Alexa](https://alexa.bitmaker.co/cohorts/72/assignments/2247/latest)

1. ANSWER = 31

SELECT COUNT(id) FROM dinos;

count
-------
  331
(1 row)


2. ANSWER:

SELECT name, period FROM dinos WHERE period='Jurassic';
        name         |  period  
---------------------+----------
 Yuanmousaurus       | Jurassic
 Yinlong             | Jurassic
 Yingshanosaurus     | Jurassic
 Yimenosaurus        | Jurassic
 Yangchuanosaurus    | Jurassic
 Yandusaurus         | Jurassic
 Vulcanodon          | Jurassic
 Tuojiangosaurus     | Jurassic
 Torvosaurus         | Jurassic
 Yunnanosaurus       | Jurassic
 Sinraptor           | Jurassic
 Stegosaurus         | Jurassic
 Seismosaurus        | Jurassic
 Segisaurus          | Jurassic
 Scutellosaurus      | Jurassic
 Scelidosaurus       | Jurassic
 Saurophaganax       | Jurassic
 Sarcosaurus         | Jurassic
 Shunosaurus         | Jurassic
 Rhoetosaurus        | Jurassic
 Poekilopleuron      | Jurassic
 Podokesaurus        | Jurassic
 Piatnitzkysaurus    | Jurassic
 Proceratosaurus     | Jurassic
 Patagosaurus        | Jurassic
 Pantydraco          | Jurassic
 Datousaurus         | Jurassic
 Ornitholestes       | Jurassic
 Omeisaurus          | Jurassic
 Nqwebasaurus        | Jurassic
 Monolophosaurus     | Jurassic
 Othnielia           | Jurassic
 Megalosaurus        | Jurassic
 Massospondylus      | Jurassic
 Marshosaurus        | Jurassic
 Mamenchisaurus      | Jurassic
 Lufengosaurus       | Jurassic
 Lophostropheus      | Jurassic
 Lexovisaurus        | Jurassic
 Metriacanthosaurus  | Jurassic
 Lesothosaurus       | Jurassic
 Kentrosaurus        | Jurassic
 Juravenator         | Jurassic
 Jingshanosaurus     | Jurassic
 Janenschia          | Jurassic
 Huayangosaurus      | Jurassic
 Heterodontosaurus   | Jurassic
 Kotasaurus          | Jurassic
 Guanlong            | Jurassic
 Giraffatitan        | Jurassic
 Gasosaurus          | Jurassic
 Gargoyleosaurus     | Jurassic
 Eustreptospondylus  | Jurassic
 Europasaurus        | Jurassic
 Haplocanthosaurus   | Jurassic
 Emausaurus          | Jurassic
 Euhelopus           | Jurassic
 Elaphrosaurus       | Jurassic
 Dubreuillosaurus    | Jurassic
 Dryosaurus          | Jurassic
 Diplodocus          | Jurassic
 Dilophosaurus       | Jurassic
 Dicraeosaurus       | Jurassic
 Cryolophosaurus     | Jurassic
 Compsognathus       | Jurassic
 Coelurus            | Jurassic
 Chungkingosaurus    | Jurassic
 Chirostenotes       | Jurassic
 Chinshakiangosaurus | Jurassic
 Chaoyangsaurus      | Jurassic
 Dacentrurus         | Jurassic
 Cetiosaurus         | Jurassic
 Cetiosauriscus      | Jurassic
 Ceratosaurus        | Jurassic
 Chialingosaurus     | Jurassic
 Brachytrachelopan   | Jurassic
 Brachiosaurus       | Jurassic
 Bellusaurus         | Jurassic
 Barosaurus          | Jurassic
 Barapasaurus        | Jurassic
 Camarasaurus        | Jurassic
 Anchisaurus         | Jurassic
 Amygdalodon         | Jurassic
 Ammosaurus          | Jurassic
 Allosaurus          | Jurassic
 Agilisaurus         | Jurassic
 Apatosaurus         | Jurassic
 Lapparentosaurus    | Jurassic
 Hesperosaurus       | Jurassic
 Camptosaurus        | Jurassic
 Aardonyx            | Jurassic
 Archaeopteryx       | Jurassic
(92 rows)


3. SELECT SUM(length) FROM dinos WHERE period='Cretaceous';
   sum   
---------
 1366.45
(1 row)

4. SELECT name, species, period FROM dinos WHERE period='Jurassic' OR period='Cretaceous' ORDER BY species ASC;
          name           |     species      |   period   
-------------------------+------------------+------------
 Afrovenator             | Abakensis        | Cretaceous
 Spinosaurus             | Aegyptiacus      | Cretaceous
 Kentrosaurus            | Aethiopicus      | Jurassic
 Deltadromeus            | Agilis           | Cretaceous
 Lophostropheus          | Airelensis       | Jurassic
 Apatosaurus             | Ajax             | Jurassic
 Dromaeosaurus           | Albertensis      | Cretaceous
 Styracosaurus           | Albertensis      | Cretaceous
 Becklespinax            | Altispinax       | Cretaceous
 Hypacrosaurus           | Altispinus       | Cretaceous
 Brachiosaurus           | Altithorax       | Jurassic
 Struthiomimus           | Altus            | Cretaceous
 Dryosaurus              | Altus            | Jurassic
 Leaellynasaura          | Amicagraphica    | Cretaceous
 Erlikosaurus            | Andrewsi         | Cretaceous
 Protoceratops           | Andrewsi         | Cretaceous
 Deinonychus             | Antirrhopus      | Cretaceous
 Centrosaurus            | Apertus          | Cretaceous
 Dryptosaurus            | Aquilunguis      | Cretaceous
 Jaxartosaurus           | Aralensis        | Cretaceous
 Lurdusaurus             | Arenatus         | Cretaceous
 Hylaeosaurus            | Armatus          | Cretaceous
 Stegosaurus             | Armatus          | Jurassic
 Dacentrurus             | Armatus          | Jurassic
 Shanag                  | Ashile           | Cretaceous
 Archaeornithomimus      | Asiaticus        | Cretaceous
 Ampelosaurus            | Atacis           | Cretaceous
 Acrocanthosaurus        | Atokensis        | Cretaceous
 Majungatholus           | Atopus           | Cretaceous
 Lophorhothon            | Atopus           | Cretaceous
 Neuquenosaurus          | Australis        | Cretaceous
 Struthiosaurus          | Austriacus       | Cretaceous
 Aegyptosaurus           | Baharijensis     | Cretaceous
 Elaphrosaurus           | Bambergi         | Jurassic
 Datousaurus             | Bashanensis      | Jurassic
 Tarbosaurus             | Bataar           | Cretaceous
 Chasmosaurus            | Belli            | Cretaceous
 Iguanodon               | Bernissartensis  | Cretaceous
 Marshosaurus            | Bicentesimus     | Jurassic
 Cedarpelta              | Bilbeyhallorum   | Cretaceous
 Dravidosaurus           | Blanfordi        | Cretaceous
 Arrhinoceratops         | Brachyops        | Cretaceous
 Proceratosaurus         | Bradleyi         | Jurassic
 Giraffatitan            | Brancai          | Jurassic
 Garudimimus             | Brevipes         | Cretaceous
 Nanshiungosaurus        | Brevispinus      | Cretaceous
 Dromiceiomimus          | Brevitertius     | Cretaceous
 Rhoetosaurus            | Brownei          | Jurassic
 Megalosaurus            | Bucklandii       | Jurassic
 Poekilopleuron          | Bucklandii       | Jurassic
 Gallimimus              | Bullatus         | Cretaceous
 Gastonia                | Burgei           | Cretaceous
 Protohadros             | Byrdi            | Cretaceous
 Pantydraco              | Caducus          | Jurassic
 Homalocephale           | Calathocercos    | Cretaceous
 Alvarezsaurus           | Calvoi           | Cretaceous
 Brachylophosaurus       | Canadensis       | Cretaceous
 Pachyrhinosaurus        | Canadensis       | Cretaceous
 Valdosaurus             | Canaliculatus    | Cretaceous
 Massospondylus          | Carinatus        | Jurassic
 Giganotosaurus          | Carolinii        | Cretaceous
 Eolambia                | Caroljonesa      | Cretaceous
 Corythosaurus           | Casuarius        | Cretaceous
 Amargasaurus            | Cazaui           | Cretaceous
 Aardonyx                | Celestae         | Jurassic
 Irritator               | Challengeri      | Cretaceous
 Sinvenator              | Changii          | Cretaceous
 Therizinosaurus         | Cheloniformis    | Cretaceous
 Zuniceratops            | Christopheri     | Cretaceous
 Saichania               | Chulsanensis     | Cretaceous
 Gasparinisaura          | Cincosaltensis   | Cretaceous
 Isisaurus               | Colberti         | Cretaceous
 Unenlagia               | Comahuensis      | Cretaceous
 Abelisaurus             | Comahuensis      | Cretaceous
 Silvisaurus             | Condrayi         | Cretaceous
 Mamenchisaurus          | Constructus      | Jurassic
 Gasosaurus              | Constructus      | Jurassic
 Pelorosaurus            | Conybearei       | Cretaceous
 Anatotitan              | Copei            | Cretaceous
 Oryctodromeus           | Cubicularis      | Cretaceous
 Magyarosaurus           | Dacus            | Cretaceous
 Liaoxiornis             | Delicatus        | Cretaceous
 Shuvuuia                | Deserti          | Cretaceous
 Lesothosaurus           | Diagnosticus     | Jurassic
 Camptosaurus            | Dispar           | Jurassic
 Malawisaurus            | Dixeyi           | Cretaceous
 Gobisaurus              | Domoculus        | Cretaceous
 Yinlong                 | Downsi           | Jurassic
 Lexovisaurus            | Durobrivensis    | Jurassic
 Sauropelta              | Edwardsorum      | Cretaceous
 Cryolophosaurus         | Elliotti         | Jurassic
 Erketu                  | Ellisoni         | Cretaceous
 Emausaurus              | Ernsti           | Jurassic
 Patagosaurus            | Fariasi          | Jurassic
 Bambiraptor             | Feinbergorum     | Cretaceous
 Piatnitzkysaurus        | Floresi          | Jurassic
 Troodon                 | Formosus         | Cretaceous
 Hadrosaurus             | Foulkii          | Cretaceous
 Hypsilophodon           | Foxii            | Cretaceous
 Polacanthus             | Foxii            | Cretaceous
 Coelurus                | Fragilis         | Jurassic
 Allosaurus              | Fragilis         | Jurassic
 Segnosaurus             | Galbinensis      | Cretaceous
 Rebbachisaurus          | Garasbae         | Cretaceous
 Aucasaurus              | Garridoi         | Cretaceous
 Tarchia                 | Gigantea         | Cretaceous
 Hagryphus               | Giganteus        | Cretaceous
 Achillobator            | Giganteus        | Cretaceous
 Shantungosaurus         | Giganteus        | Cretaceous
 Sinocalliopteryx        | Gigas            | Cretaceous
 Tylocephale             | Gilmorei         | Cretaceous
 Probactrosaurus         | Gobiensis        | Cretaceous
 Nomingia                | Gobiensis        | Cretaceous
 Microceratops           | Gobiensis        | Cretaceous
 Buitreraptor            | Gonzalezorum     | Cretaceous
 Borogovia               | Gracilicrus      | Cretaceous
 Conchoraptor            | Gracilis         | Cretaceous
 Leptoceratops           | Gracilis         | Cretaceous
 Pinacosaurus            | Grangeri         | Cretaceous
 Segisaurus              | Halli            | Jurassic
 Seismosaurus            | Hallorum         | Jurassic
 Dicraeosaurus           | Hansemanni       | Jurassic
 Scelidosaurus           | Harrisonii       | Jurassic
 Diceratops              | Hatcheri         | Cretaceous
 Sinraptor               | Hepingensis      | Jurassic
 Ornitholestes           | Hermanni         | Jurassic
 Dracorex                | Hogwartsia       | Cretaceous
 Europasaurus            | Holgeri          | Jurassic
 Podokesaurus            | Holyokensis      | Jurassic
 Wuerhosaurus            | Homheni          | Cretaceous
 Yandusaurus             | Hongheensis      | Jurassic
 Micropachycephalosaurus | Hongtuyanensis   | Cretaceous
 Achelousaurus           | Horneri          | Cretaceous
 Triceratops             | Horridus         | Cretaceous
 Yunnanosaurus           | Huangi           | Jurassic
 Lufengosaurus           | Huenei           | Jurassic
 Argentinosaurus         | Huinculensis     | Cretaceous
 Beipiaosaurus           | Inexpectus       | Cretaceous
 Bugenasaura             | Infernalis       | Cretaceous
 Chubutisaurus           | Insignis         | Cretaceous
 Aragosaurus             | Ischiadicus      | Cretaceous
 Urbacodon               | Itemirensis      | Cretaceous
 Chungkingosaurus        | Jiangbeiensis    | Jurassic
 Monolophosaurus         | Jiangi           | Jurassic
 Yuanmousaurus           | Jiangyiensis     | Jurassic
 Yingshanosaurus         | Jichuanensis     | Jurassic
 Bactrosaurus            | Johnsoni         | Cretaceous
 Omeisaurus              | Junghsiensis     | Jurassic
 Vulcanodon              | Karibaensis      | Jurassic
 Fukuiraptor             | Kitadaniensis    | Cretaceous
 Masiakasaurus           | Knopfleri        | Cretaceous
 Secernosaurus           | Koerneri         | Cretaceous
 Chialingosaurus         | Kuani            | Jurassic
 Lambeosaurus            | Lambei           | Cretaceous
 Avaceratops             | Lammersi         | Cretaceous
 Nanotyrannus            | Lancenis         | Cretaceous
 Muttaburrasaurus        | Langdoni         | Cretaceous
 Goyocephale             | Lattimorei       | Cretaceous
 Torosaurus              | Latus            | Cretaceous
 Scutellosaurus          | Lawleri          | Jurassic
 Noasaurus               | Leali            | Cretaceous
 Ligabuesaurus           | Leanzai          | Cretaceous
 Eotyrannus              | Lengi            | Cretaceous
 Barosaurus              | Lentus           | Jurassic
 Gorgosaurus             | Libratus         | Cretaceous
 Albertosaurus           | Libratus         | Cretaceous
 Shunosaurus             | Lii              | Jurassic
 Archaeopteryx           | Lithographica    | Jurassic
 Atlascopcosaurus        | Loadsi           | Cretaceous
 Edmontonia              | Longiceps        | Cretaceous
 Tsagantegia             | Longicranialis   | Cretaceous
 Compsognathus           | Longipes         | Jurassic
 Diplodocus              | Longus           | Jurassic
 Saltasaurus             | Loricatus        | Cretaceous
 Agilisaurus             | Louderbacki      | Jurassic
 Lapparentosaurus        | Madagascariensis | Jurassic
 Ankylosaurus            | Magniventris     | Cretaceous
 Ammosaurus              | Major            | Jurassic
 Orodromeus              | Makelai          | Cretaceous
 Saurophaganax           | Maximus          | Jurassic
 Prosaurolophus          | Maximus          | Cretaceous
 Khaan                   | Mckennai         | Cretaceous
 Austrosaurus            | Mckillopi        | Cretaceous
 Nothronychus            | Mckinleyi        | Cretaceous
 Brachytrachelopan       | Mesai            | Jurassic
 Sinornithosaurus        | Millenii         | Cretaceous
 Deinocheirus            | Mirificus        | Cretaceous
 Panoplosaurus           | Mirus            | Cretaceous
 Hesperosaurus           | Mjosi            | Jurassic
 Graciliceratops         | Mongoliensis     | Cretaceous
 Saurornithoides         | Mongoliensis     | Cretaceous
 Rinchenia               | Mongoliensis     | Cretaceous
 Psittacosaurus          | Mongoliensis     | Cretaceous
 Nemegtosaurus           | Mongoliensis     | Cretaceous
 Velociraptor            | Mongoliensis     | Cretaceous
 Gilmoreosaurus          | Mongoliensis     | Cretaceous
 Brachyceratops          | Montanensis      | Cretaceous
 Tuojiangosaurus         | Multispinus      | Jurassic
 Pleurocoelus            | Nanus            | Cretaceous
 Ceratosaurus            | Nasicornis       | Jurassic
 Kritosaurus             | Navajovius       | Cretaceous
 Thescelosaurus          | Neglectus        | Cretaceous
 Albertaceratops         | Nesmoi           | Cretaceous
 Ouranosaurus            | Nigeriensis      | Cretaceous
 Equijubus               | Normani          | Cretaceous
 Gryposaurus             | Notabilis        | Cretaceous
 Harpymimus              | Okladnikovi      | Cretaceous
 Mononykus               | Olecranus        | Cretaceous
 Antarctopelta           | Oliveroi         | Cretaceous
 Alectrosaurus           | Olseni           | Cretaceous
 Quaesitosaurus          | Orientalis       | Cretaceous
 Anchiceratops           | Ornatus          | Cretaceous
 Saurolophus             | Osborni          | Cretaceous
 Archaeoceratops         | Oshimai          | Cretaceous
 Citipati                | Osmolskae        | Cretaceous
 Utahraptor              | Ostrommaysorum   | Cretaceous
 Eustreptospondylus      | Oxoniensis       | Jurassic
 Cetiosaurus             | Oxoniensis       | Jurassic
 Minmi                   | Paravertebra     | Cretaceous
 Metriacanthosaurus      | Parkeri          | Jurassic
 Gargoyleosaurus         | Parkpinorum      | Jurassic
 Amygdalodon             | Patagonicus      | Jurassic
 Maiasaura               | Peeblesorum      | Cretaceous
 Chirostenotes           | Pergracilis      | Jurassic
 Oviraptor               | Philoceratops    | Cretaceous
 Anserimimus             | Planinychus      | Cretaceous
 Talarurus               | Plicatospineus   | Cretaceous
 Pelicanimimus           | Polyodon         | Cretaceous
 Anchisaurus             | Polyzelous       | Jurassic
 Avimimus                | Portentosus      | Cretaceous
 Prenocephale            | Prenes           | Cretaceous
 Sinosauropteryx         | Prima            | Cretaceous
 Rugops                  | Primus           | Cretaceous
 Haplocanthosaurus       | Priscus          | Jurassic
 Hypselosaurus           | Priscus          | Cretaceous
 Rhabdodon               | Priscus          | Cretaceous
 Einiosaurus             | Procurvicornis   | Cretaceous
 Indosuchus              | Raptorius        | Cretaceous
 Edmontosaurus           | Regalis          | Cretaceous
 Alioramus               | Remotus          | Cretaceous
 Tyrannosaurus           | Rex              | Cretaceous
 Othnielia               | Rex              | Jurassic
 Protarchaeopteryx       | Robusta          | Cretaceous
 Janenschia              | Robusta          | Jurassic
 Zalmoxes                | Robustus         | Cretaceous
 Mapusaurus              | Roseae           | Cretaceous
 Bagaceratops            | Rozhdestvenskyi  | Cretaceous
 Nipponosaurus           | Sachalinensis    | Cretaceous
 Carcharodontosaurus     | Saharicus        | Cretaceous
 Sonidosaurus            | Saihangaobiensis | Cretaceous
 Neovenator              | Salerii          | Cretaceous
 Confuciusornis          | Sanctus          | Cretaceous
 Alamosaurus             | Sanjuanensis     | Cretaceous
 Carnotaurus             | Sastrei          | Cretaceous
 Zephyrosaurus           | Schaffi          | Cretaceous
 Shamosaurus             | Scutatus         | Cretaceous
 Yangchuanosaurus        | Shangyouensis    | Jurassic
 Tanius                  | Sinensis         | Cretaceous
 Opisthocoelicaudia      | Skarzynskii      | Cretaceous
 Stygimoloch             | Spinifer         | Cretaceous
 Tsintaosaurus           | Spinorhinus      | Cretaceous
 Juravenator             | Starki           | Jurassic
 Pentaceratops           | Sternbergi       | Cretaceous
 Cetiosauriscus          | Stewarti         | Jurassic
 Paralititan             | Stromeri         | Cretaceous
 Bellusaurus             | Sui              | Jurassic
 Camarasaurus            | Supremus         | Jurassic
 Barapasaurus            | Tagorei          | Jurassic
 Huayangosaurus          | Taibaii          | Jurassic
 Torvosaurus             | Tanneri          | Jurassic
 Nigersaurus             | Taqueti          | Cretaceous
 Platyceratops           | Tatarinovi       | Cretaceous
 Suchomimus              | Tenerensis       | Cretaceous
 Lamaceratops            | Tereschenkoi     | Cretaceous
 Fukuisaurus             | Tetoriensius     | Cretaceous
 Nodosaurus              | Textilis         | Cretaceous
 Nqwebasaurus            | Thwazi           | Jurassic
 Jobaria                 | Tiguidensis      | Cretaceous
 Tenontosaurus           | Tillettorum      | Cretaceous
 Maxakalisaurus          | Topai            | Cretaceous
 Daspletosaurus          | Torosus          | Cretaceous
 Telmatosaurus           | Transsylvanicus  | Cretaceous
 Udanoceratops           | Tschizhovi       | Cretaceous
 Aralosaurus             | Tuberiferus      | Cretaceous
 Heterodontosaurus       | Tucki            | Jurassic
 Euoplocephalus          | Tutus            | Cretaceous
 Stenopelix              | Valdensis        | Cretaceous
 Dubreuillosaurus        | Valesdunensis    | Jurassic
 Stegoceras              | Validum          | Cretaceous
 Ornithomimus            | Velox            | Cretaceous
 Supersaurus             | Vivianae         | Cretaceous
 Baryonyx                | Walkeri          | Cretaceous
 Parasaurolophus         | Walkeri          | Cretaceous
 Parksosaurus            | Warrenae         | Cretaceous
 Dilophosaurus           | Wetherilli       | Jurassic
 Antarctosaurus          | Wichmannianus    | Cretaceous
 Sarcosaurus             | Woodi            | Jurassic
 Guanlong                | Wucaii           | Jurassic
 Pachycephalosaurus      | Wyomingensis     | Cretaceous
 Jingshanosaurus         | Xinwaensis       | Jurassic
 Kotasaurus              | Yamanpalliensis  | Jurassic
 Jinzhousaurus           | Yangi            | Cretaceous
 Ingenia                 | Yanshini         | Cretaceous
 Liaoceratops            | Yanzigouensis    | Cretaceous
 Yimenosaurus            | Youngi           | Jurassic
 Chaoyangsaurus          | Youngi           | Jurassic
 Euhelopus               | Zdanskyi         | Jurassic
 Microraptor             | Zhaoianus        | Cretaceous
 Chinshakiangosaurus     | Zhongheensis     | Jurassic
 Caudipteryx             | Zoui             | Cretaceous
(310 rows)


5. SELECT name, t_order, diet FROM dinos WHERE t_order='Saurischia' AND diet='Herbivorous';
        name         |  t_order   |    diet     
---------------------+------------+-------------
 Yuanmousaurus       | Saurischia | Herbivorous
 Yimenosaurus        | Saurischia | Herbivorous
 Vulcanodon          | Saurischia | Herbivorous
 Supersaurus         | Saurischia | Herbivorous
 Sonidosaurus        | Saurischia | Herbivorous
 Seismosaurus        | Saurischia | Herbivorous
 Saltasaurus         | Saurischia | Herbivorous
 Rebbachisaurus      | Saurischia | Herbivorous
 Quaesitosaurus      | Saurischia | Herbivorous
 Shunosaurus         | Saurischia | Herbivorous
 Rhoetosaurus        | Saurischia | Herbivorous
 Plateosaurus        | Saurischia | Herbivorous
 Pelorosaurus        | Saurischia | Herbivorous
 Patagosaurus        | Saurischia | Herbivorous
 Pantydraco          | Saurischia | Herbivorous
 Paralititan         | Saurischia | Herbivorous
 Datousaurus         | Saurischia | Herbivorous
 Pleurocoelus        | Saurischia | Herbivorous
 Opisthocoelicaudia  | Saurischia | Herbivorous
 Omeisaurus          | Saurischia | Herbivorous
 Nigersaurus         | Saurischia | Herbivorous
 Neuquenosaurus      | Saurischia | Herbivorous
 Nemegtosaurus       | Saurischia | Herbivorous
 Mussaurus           | Saurischia | Herbivorous
 Maxakalisaurus      | Saurischia | Herbivorous
 Malawisaurus        | Saurischia | Herbivorous
 Mamenchisaurus      | Saurischia | Herbivorous
 Lufengosaurus       | Saurischia | Herbivorous
 Magyarosaurus       | Saurischia | Herbivorous
 Ligabuesaurus       | Saurischia | Herbivorous
 Jobaria             | Saurischia | Herbivorous
 Jingshanosaurus     | Saurischia | Herbivorous
 Janenschia          | Saurischia | Herbivorous
 Isisaurus           | Saurischia | Herbivorous
 Hypselosaurus       | Saurischia | Herbivorous
 Kotasaurus          | Saurischia | Herbivorous
 Guaibasaurus        | Saurischia | Herbivorous
 Giraffatitan        | Saurischia | Herbivorous
 Europasaurus        | Saurischia | Herbivorous
 Haplocanthosaurus   | Saurischia | Herbivorous
 Erketu              | Saurischia | Herbivorous
 Euhelopus           | Saurischia | Herbivorous
 Diplodocus          | Saurischia | Herbivorous
 Dicraeosaurus       | Saurischia | Herbivorous
 Chubutisaurus       | Saurischia | Herbivorous
 Chinshakiangosaurus | Saurischia | Herbivorous
 Cetiosaurus         | Saurischia | Herbivorous
 Cetiosauriscus      | Saurischia | Herbivorous
 Brachytrachelopan   | Saurischia | Herbivorous
 Brachiosaurus       | Saurischia | Herbivorous
 Bellusaurus         | Saurischia | Herbivorous
 Barosaurus          | Saurischia | Herbivorous
 Barapasaurus        | Saurischia | Herbivorous
 Austrosaurus        | Saurischia | Herbivorous
 Camarasaurus        | Saurischia | Herbivorous
 Aragosaurus         | Saurischia | Herbivorous
 Antarctosaurus      | Saurischia | Herbivorous
 Anchisaurus         | Saurischia | Herbivorous
 Amygdalodon         | Saurischia | Herbivorous
 Ampelosaurus        | Saurischia | Herbivorous
 Amargasaurus        | Saurischia | Herbivorous
 Ammosaurus          | Saurischia | Herbivorous
 Alamosaurus         | Saurischia | Herbivorous
 Apatosaurus         | Saurischia | Herbivorous
 Lapparentosaurus    | Saurischia | Herbivorous
 Aardonyx            | Saurischia | Herbivorous
 Argentinosaurus     | Saurischia | Herbivorous
 Aegyptosaurus       | Saurischia | Herbivorous
(68 rows)


6. SELECT name, length FROM dinos ORDER BY length ASC;
          name           | length
-------------------------+--------
 Liaoxiornis             |   0.08

 SELECT MIN(length) FROM dinos;                                                            min  
------
 0.08
(1 row)

UPDATE dinos SET name = 'Shortie' WHERE length=0.08;
UPDATE 1


7. SELECT name FROM dinos ORDER BY name ASC LIMIT 1;
   name   
----------
 Aardonyx
(1 row)


8. SELECT name, length FROM dinos WHERE length IS NOT NULL ORDER BY length DESC LIMIT 5     ;
      name       | length
-----------------+--------
 Seismosaurus    |     40
 Supersaurus     |     35
 Argentinosaurus |     35
 Brachiosaurus   |     30
 Paralititan     |     28
(5 rows)

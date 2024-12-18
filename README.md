java c
COURSEWORK OVERVIEW 
Module: 
BENV0085: Engineered Environmental Elements 
Coursework: 
Portfolio: 
Performance Analysis of Building Systems Components 
Weighting: 
100% 
Coursework Issued: 
November 6th , 2024 
Submission Deadline: 
11:00am, January 8th , 2025 
Word Limit: 
3000 words 
Page Limit: 
20 pages 
File format: Submit your report online as a single Word or PDF file.       Use    the provided cover page and make sure not to include your name anywhere (including the name of the file) - use your candidate code instead.    Besides, you should submit separately    (as a single zip file) all models you created and key output files (as required in the brief below).    In preparing your report, make sure you use the cover page provided and you check your work for plagiarism.    You should name all your files according to the convention: 
[Module code]__[Your UCL candidate code]__[date] 
Submission instructions: ALL students to submit a complete electronic copy of coursework submission through Moodle (using the Turnitin system). This is the copy that will be used to assess the work, so it is the FINAL copy. 
Coursework Aims (Learning Outcomes) 
Upon   successful   completion   of the   coursework,   students   should   be   able   to:
•    Explain and analyse a wide range of   fundamental building systems components, their performance   and   inter-relationship.
•    Demonstrate hands-on experience with using component-level simulation tools and pre-developed   libraries   of building   systems   components   models.
•    Plan building systems components performance analysis, assemble appropriate components model,   conduct   analysis   and   critically   examine   model’s   outputs.
•    Communicate project   results   directed   at   audiences   of   varied   backgrounds.
Overall Brief As part of   the everyday activities of digital engineers and energy analysts, they have to address a variety   of   engineering   problems   concerning   the   design   and   performance   of   energy   systems.      These   problems   typically   require   performing   calculations   and   communicating   recommendations/decisions   to   clients.   This   coursework   collects   a   set   of situational   examples   that   might   be   encountered   in   your   professional   life.   You need to understand the requirements   (as stated   in   the   coursework   brief),   develop   your   models   and/or   use   property   tables   or   software,   use   your   knowledge   and   relevant   tools   to   perform   engineering   calculations, and   summarise   your   results   in   a   form   that   is   suitable   for   external   non-specialist   audiences (clients).   You   will   be   involved   in   three   projects:
Project 1: Analysis of a vapour compression system Refrigeration   system with   outdated   refrigerant   is   improved   by   replacing the   outdated   refrigerant with   new   and   environmentally   friendly   refrigerants   and   by   changing   the   system   design   (replace   the   initial system   with   a   cascade   system).   The   main   goal   is   to   evaluate   the   performance   of   modernised   systems   and   to   compare   their   performance   to   that   of the   initial   system.
Project 2: Air conditioning facility in Barcelona, Spain An   initially   designed   air-conditioning   system   has   limited   control   capabilities   of a   supply   air   tempera-   ture.      The   proposed   improvements   include   two   ways   of   controlling   supply   air   temperature.    The   main goal   is   to   assess   the   energy   performance   of   the   key   system   elements   as   well   as   the   behaviour   of   the   most   important   system   parameters   for   varied   system   configurations.
Project 3:    Offsetting electric energy demand using renewable energy sources Energy   demand   can,   in   some   cases,   be   fully   or   partially   covered   by   energy   generated   by   renewables.   Bringing   supply   and   demand   closer   to   each   other   can   result   in   a   reduction   of   CO2    emissions.      Solar   photovoltaic   (PV)   system   is   one   of   the   renewable   technologies   which   can   be   utilised   to   achieve   this.   The   main   goal   of   this   task   is   to   analyse   the   impact   of   the   main   PV   system   parameters   (such   as   size   and   orientation)   on   the   PV   plant   output   and   to   evaluate   the   potential   for   fully   or   partially   offsetting   electricity   demand   created   by   the   air-conditioning   system   described   in   the   project   2.
Details   on   what   is   required   for   each   project   can   be   found   in   the   corresponding   sections   below.
Resources needed to complete this coursework 
The   weather   files   and   supplementary   information   is   available   on   the   Moodle   page   of the   module.   The   main   software   packages   you   will   be   using   for   the   tasks   are:
•    Coolprop (using   the   Python   binding)
• Modelica/Dymola
•    Selected components   from   the   Modelica   Buildings   library   (version   10.0.0)Details   on   where   to   obtain/download   and   install   each   of   these   tools   have   been   provided   during   in-   duction   week.   You   are   welcome   to   use   alternative   tools   (or   even   tables),   but   using   the   tools   above   is   recommended,   as   much   of the   pre-requisite   knowledge   has   been   covered   in   the   practical   sessions   that   followed   each   lecture.      You   are   also   welcome   to   use    (referencing   appropriately)   external   sources   for   additional   information/data   required   to   make   a   solid   recommendation.
If you   have   any   questions   or   remarks   on   any   of the   tasks,   you   are   encouraged   to   post   on   the   Moodle   Question      Answer   Forum   on   the   Module   Moodle   Page.
Project 1: Analysis of a vapour compression system 
Statement A   frozen   food   processing   factory   located   in   Barcelona,    Spain   with   a   peak   ambient   temperature   of 35 。C,   keeps   the   foods   stored   in   a   cold   room   at −15 。C   and   the   cooling   load   (refrigeration   effect)   at   the   peak   capacity   is 20 kW.   Currently,   the   factory   employs   a   single-stage   vapour   compression   system   with R236fa as   a   refrigerant.    The   company   has   decided   to   upgrade   the   system   to   one   with   a   more   environmentally   friendly   refrigerant.    A   consultant      (you)   has   been   appointed   to   redesign   the   system.   The   refrigerants   available   at   the   local   market,   which   cover   the   operating   temperature   range,   are R40 and R1233zd(E).   The   proposal   is   to   evaluate   two   possible   system   upgrade   scenarios:
1.    Replace   R236fa   in   a   single-stage   vapour   compression   system   (Figure 1)   with:
(a)    R40,   or
(b)    R1233zd(E)

Figure   1:   Single-stage   vapour   compression   system

Figure   2:   Cascade   vapour   compression   system
2.    Use   a   cascade   system   (Figure 2)   with:
(a)    R40   in   both   lower   temperature   cycle   and   higher   temperature   cycle,
(b)    R1233zd(E)   in   both   lower   temperature   cycle   and   higher   temperature   cycle,
(c)    R40   in   the   lower   temperature   cycle   and   R1233zd(E)   in   the   higher   temperature   cycle,   or
(d)    R1233zd(E)   in   the   lower   temperature   cycle   and   R40   in   the   higher   temperature   cycle.
The client has appointed you to provide them with answers to the following: 
1.   Which solution from the first upgrade scenario would you propose based on the COP of   the system   at   peak   capacity?   How   do   the   proposed   systems   perform   (in   terms   of   COP)   when   compared   to   the   original   R236fa   system?
2.   Which   solution   from   the   second   upgrade   scenario would   you   propose   based   on the   optimal   COP   of the   syst代 写BENV0085: Engineered Environmental ElementsPython
代做程序编程语言em   at   peak   capacity?   What   is   the   optimal   intermediate   temperature   in   the   proposed cascade   system   (Tc_low      ≈   Te_high)?      Plot   the   proposed   cascade   system   performance   (COP   vs   intermediate   temperature).       How      do   the   proposed   systems   perform      (in      terms   of   COP)   when compared   to   the   original   R236fa   system? 
3.    A   detailed   description   of   a   cascade   vapour   compression   system.
Hints:
•    Use the   ideal   refrigeration   cycle   for   this   analysis.
•      The   temperature   of   the   refrigerant   in   the   evaporator   (evaporation   temperature)   is 10 。C   cooler than   the   cold   room   temperature.
•    The   temperature   of the   refrigerant   in   the   condenser   (condensation   temperature)   is 15 。C   higher   than   the   ambient   temperature.
•    Heat   rejection   from   the   lower   cycle   to   the   higher   cycle   takes   place   in   an   adiabatic   counter-flow   heat   exchanger   where   phase   change   in   both   streams   happens   at   about   the   same   temperature   (Tc__low      ≈   Te__high).    (In   practice,   the   working   fluid   of   the   lower   cycle   is   at   a   higher   temperature
in   the   heat   exchanger   for   effective   heat   transfer.)
Project 2: Air-conditioning facility 
Statement An   air-conditioning   facility   installed   in Barcelona, Spain,   shown   in   Figure 3,   is   composed   of an   air-   cooled   chiller,   a   chilled   water   pump,   a   fan   and   a   heat   exchanger.   The   initial   design   has   the   following   characteristics   (Task2a   in   the   Modelica   .mo   input   file   provided   with   the   coursework   brief):
• Air-cooled   liquid   chiller   with   R134a   refrigerant   and   the   nominal   capacity   of 743.7 kW.
•    Constant   speed   chilled   water   pump   which   keeps   the   constant   chilled   water   volume   flow   rate   in   the   chilled   water   loop   of 115 m3/h   (0.032m3/s   or   mass   flow   rate   of   32kg/s).
•    Constant   speed   air   fan   which   keeps   the   constant   outdoor   air   volume   flow   rate   of 48 000 m3/h   (13.33m3/s   or   mass   flow   rate   of   16kg/s).
•      The   chilled   water   temperature   leaving   the   chiller   (and   entering   the   cooling   coil   –   water   side), tch__out ,   is   controlled   to   a   fixed   setpoint   of 7 。C.The   system   as   designed   operates   with   a   variable   temperature   of   the   air   delivered   to   the   conditioned   space   (and leaving the cooling coil   –   air-side),   t   air_out,   which   fluctuates   between   8 。C   and   10 。C   during   most   of the   warm   season   period.Due   to   persistent   complaints   from   occupiers   of   the   conditioned   space   about   non-comfortable   conditions   caused   by   the   cold   air   draft,   a   consultant   (you)   has   been   appointed   to   modify   the   system   to   operate   with   the   fixed   temperature   of   the   air   delivered   to   the   conditioned   space, tair__out .    The   desired   fixed   setpoint   is   set   to 13 。C.
You   decide   to   analyse   two   possible   system   modification   scenarios:

Figure   3:   Air-conditioned   system   (initial   design)

Figure   4:   Air-conditioned   system   (with   the   cooling   coil   bypass)
1.    To   introduce   the   three-port   valve   and   the   bypass   in   the   chilled   water   loop   (Figure 4)   which   are used to modulate the chilled water   flow   rate   through   the   cooling   coil   to   keep   the   air   temperature   constant   at   13 。C.    The   amount   of   water   flowing   through   the   chiller      (and   chilled   water   pump)   remains   as   initially   designed   (constant).    The   air-side   has   no   changes   except   the   installation   of   the   air   temperature   sensor   in   the   air   stream   path   after   the   cooling   coil   (Task2b   in   the   Modelica .mo   input   file   provided   with   the   coursework   brief).
2.    To keep the water-side intact and to control the air delivered to the conditioned space temperature   (at   13 。C   by   modulating   the   airflow   rate   via   installing   the   variable   speed   drive    (VSD)   which controls   the   fan   motor   speed   (Figure 5).    (Task2c   in   the   Modelica      .mo   input   file   provided   with the   coursework   brief).The   chilled   water   temperature   is   controlled   by   a   fixed   setpoint    (tch_out      =   7 。C)   in   both   scenarios.   The conclusions   are to be provided   based   on   the   analysis   conducted   for   the   particularly   warm   summer   week; week 35 (the   simulation   interval   start   time   is   a day 239 while   the   simulation   interval   stop   time is   a day 246.   The   external   weather   conditions   are   provided   in   .mos   file   supplied   with   this   coursework brief).
You are asked to prepare a report with the following information: 
Note:   You   may   want   to   focus   on   the   subset   while   providing   more   in-depth   analyses.
•    Mandatory:    Choose   one   from   three   provided   systems   (initial   design   +   two   system   modification scenarios)   and   determine   the   heat   and   moisture   removal   rates   from   the   air   passing   across   the   cooling   coil   on   the   Noon   of   the   first   day   of   the   simulation   period   (timestamp:    239.5d).    Assume that   the   moisture   in   the   air   that   condenses   during   the   process   is   removed   at   the   temperature   of   the   air   leaving   the   cooling   coil   and   assume   that   the   air   pressure   is   1   atm.      Use   Dymola   to

Figure   5:   Air-conditioned   system   (with   the   VSD)obtain   necessary   air   properties   such   as   air   mass   flow   rate,   temperature,   specific   humidity   and/or enthalpy   of   air   entering/leaving   the   cooling   coil.    Conduct   calculations   in   Python   by   using   the   CoolProp.   Sketch   the   process   in   the   psychrometric   diagram.
•    Chiller,   pump   and   fan   energy   consumptions   for   the   analysed   week   with   the   discussion   on   differ-   ences   (and   cause   of   differences)   among   analysed   scenarios.
•    Chiller COP   in   all   three   scenarios   (and   a   reason   for   a   difference,   if any).
•    Heat exchanged   between   water   stream   and   air   stream.
•      The   temperature   of the   air   delivered   to   the   conditioned   space   both   uncontrolled   and   controlled   (temperature   oscillations   as   a   function   of   the   control   mechanism).
• For   the   second   modification   scenario   air   flow   rates   compared   to   the   constant   flow   rate   operation.
• The   temperature   of   the   water   leaving   the   cooling   coil   in   all   three   scenarios.
•      The   first   modification   scenario   water   flow   rates   through   the   cooling   coil   compared   to   the   operation without   bypass.
Hint:   Use   0.001   for   the   integration   tolerance   within   the   simulation   setup   to   decrease   simulation   time.
Project 3:    Offsetting electric energy    demand using renewable energy sources 
Statement 
As   part   of   the   previous   project,   there   is   a   discussion   about   offsetting   electricity   requirements   using renewable   energy   sources.   You   are   tasked   to   explore   the   opportunity   of installing   a   solar   photovoltaic (PV)   plant   to   support   and   partially   offset   the   electricity   requirements   of the   air-conditioning   facility.   Analyse   the   coupling   of   the   air-conditioning   facility   with   the   PV   plant   with   respect   to   the   PV   net   surface   area,   the   PV   tilt   angle,   and   the   PV   azimuth   angle. 
Hint:   Compare   the   PV   power   output   with the   fan/pump/chiller   power   inputs.









         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com

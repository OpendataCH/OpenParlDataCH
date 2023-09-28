# OpenParlDataCH
Among municipalities, cantons and the national level there’s a variety of different structures and quality for parliamentary data. [Some data is not machine-readable, some are not fully accurate, some lack documentation and data is hardly comparable](https://docs.google.com/spreadsheets/d/1cHF9qOHYoOcumw03d29mb90T_Elc8aHQrMCEsML88lk/edit?usp=sharing). Political monitoring and analysis tools need to update their crawlers for the same parliamentary websites and clean the same data, rather than focusing on their core competencies. Interoperability across the three levels of government is not guaranteed, with negative consequences for the legislative and executive branches themselves. A data standard to which smaller cantons and municipalities in particular could orient themselves is not in sight.

As a citizen, I would like to be able to follow a specific topic or parliamentary affair from A to Z. For our democracy to work, we need an overview of the political agenda and how parliamentarians have voted. To build this infrastructure, we bring together people from different backgrounds (business, civil society, governments, parliaments, academia), use synergies and collaboratively work towards an open standard and an open API for parliamentary data across all federal levels. In short: **We make harmonized Swiss parliamentary data accessible as an open web service.**

## Our service should…
* obtain already machine-readable and up-to-date information from the source (e.g. parliamentary service API) and harmonize it.
* make non machine-readable information published by the parliamentary services machine-readable and harmonize it.
* follow an Open, collaboratively defined standard taking into account international good practices like [OParl](https://github.com/OParl) and (if possible) involve [eCH](https://www.ech.ch/)
* be federated.
* provide Open Data.
* publish only information that is already available.
* provide e.g.
  * parliamentarians with ID, party, commission,...
  * parliamentary affairs with ID, title, description,...
  * voting behavior
  * vested interests: confederation and cantons (if available)
  * ...
* not provide any calculated values and derivatives.
* not create additional interlinking.
* provide data as a bulk download.
* provide data as an open API.
* not be a gatekeeper.
* be financially and organizationally sustainable.
* be lean (not too much overhead).
* work with and not against the parliament and the government.
* be handed over to an official body in the future.

## Challenges we need to address
* What's the right level of abstraction/detail for the data standard?
* How do we harmonize existing data models?
* How do we build on existing international standards like...
  * [OParl](https://github.com/OParl)
  * [Popolo](https://github.com/popolo-project/popolo-spec)
  * (to be extended)
* How can we make efficient decisions as an interdisciplinary, heterogenic group?
* Data quality
* Data and API management 
* Reliability
* Trustworthiness
* Multilingualism
* How do we fund this infrastructure that [many will benefit from but no single public body is currently willing or able to sustain on its own](https://binary-butterfly.de/artikel/opendata-bisschen-prototyp-und-das-wars-dann/)?
  * Intercantonal Legislative Conference? State Writers Conference?
  * Digital Public Services Switzerland? They annually fund ["e-participation projects and innovations"](https://www.digital-public-services-switzerland.ch/en/implementation/egovernment-implementation-plan/promoting-e-participation-projects-and-innovations)
  * SRG SSR?
  * [Interreg](https://www.interreg.org/): would need DACHLI context
  * foundations?
* What’s a fair price for the work already done and maintenance provided in the future?
* How and when do we include the parliamentary services?
* How do we incentivize parliamentary services and their suppliers to adapt the data standard
* How do we foster a culture of openness?
* Who provides what data?
* Who provides support? Questions, anomalies, bugs,...
* Meiner Meinung nach braucht es eine gesunde Governance nach ethisch/moralischen Grundsätzen die viele euer genannten Punkte abdecken und dies durch ein Gremium (Verein oder ähnliches) getragen und auch „überwacht“ wird. Diese Governance sollte dann in eine Art Thesenanschlag/Manifest öffentlich zugänglich sein.
* Auf lange Sicht scheint mir doch auch ein Business case relevant. Mehr aber aus einer kostendeckenden und innovierenden Perspektive. Sprich das Geld das reinkommt ist da um den Service zu halten/betreiben und je nach Bedürfnisse der Kundschaft auch neue Features/Daten/etc. umzusetzen
* Mir fehlt noch grundsätzlich der Umgang mit Veränderung. Was passiert wenn Daten und -strukturen sich ändern, was wenn ein Service obsolet wird oder nicht mehr verfügbar ist? Wie gehen wir damit um? Wird gecached oder sind wir einfach Abbild der „Realität“?
* Gibt es einen Prozess oder ein Backlog/Board/Roadmap des Services? Wenn ja können potentielle User hier auch Features wünschen oder Bugs rapportieren?
* Noch ein Fragezeichen habe ich beim Punkt „ not be a gatekeeper“: Wenn wir einen zentralen Hub bauen, welcher alles zusammenzieht und je nach dem auch Modifikationen an den Daten vornimmt um OParl konform zu sein, sind wir ja zwangsläufig ein gatekeeper, nicht? Solange das aber öffentlich zugänglich bleibt (Da stellt sich dann auch wieder die Business case Frage), sehe ich kein Problem dabei.
* Weiter würde ich allenfalls noch ergänzen dass diese Daten nicht zwingend für den kommerziellen Gebrauch gedacht sind. Und wenn schon, dann soll in Form einer Spende (oder je nach dem dann Businessmodell) an den Verein/Service zurückfliessen


## The Team [(Onion)](https://teamonion.works/)
* The core team builds the open API:
  * [Christian](https://github.com/gutknecht)
  * ...(insert name here)
* Collaborators define the open standard
* Supporters...
  * [Liip](https://www.liip.ch), Opendata-Circle, [Flavio](https://flaviomuff.ch/)  
  
Send us a message if you want to join our mission! Contribute to this document by creating a pull request.

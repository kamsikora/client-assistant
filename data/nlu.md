## intent:choose
- jaki jest mój stan [licznika]{"entity": "operation", "value": "meter_read"}?
- informacja na temat stanu [licznika]{"entity": "operation", "value": "meter_read"}
- jaki jest stan [licznika]{"entity": "operation", "value": "meter_read"}?
- jaka jest moja ostatnia [faktura]{"entity": "operation", "value": "bill"}?
- ile wynosi moja ostatnia [faktura]{"entity": "operation", "value": "bill"}?
- informacja o ostatniej [fakturze]{"entity": "operation", "value": "bill"}
- ile wynosi moje [saldo](operation)?
- jakie jest moje [saldo](operation)?
- informacja o [saldzie]{"entity": "operation", "value": "saldo"}
- jaki jest stan mojego [salda](operation)?

## intent:confirm_client
- mój numer klienta [21313127](client)
- [52624626](client)
- numer klienta [13124565](client)
- mój numer klienta to [78784565](client)
- mój numer klienta [22222222](client)
- numer klienta [11111111](client)
- Mój numer klienta to [55555555](client)
- [99999999](client)
- mój numer klienta to [11111111](client)

## intent:confirm_pesel
- mój numer pesel [65062479537](pesel)
- [91031787413](pesel)
- numer pesel [65062479537](pesel)
- pesel [91031787413](pesel)
- mój numer pesel to [77081668908](pesel)
- [77081668908](pesel) to mój pesel
- mój numer PESEL to [50102231284](pesel)
- numer PESEL [50102231284](pesel)

## regex:pesel
- [0-9]{11}

## regex:client
- [0-9]{8}

## intent:confirm_ppe
- mój numer ppe [PL1](ppe_code)
- [PL5](ppe_code)
- numer ppe [PL9](ppe_code)
- mój numer ppe to [PL7](ppe_code)
- mój numer ppe to [PL2](ppe_code)
- moje ppe to [PL1](ppe_code)
- Mój numer PPE [PL2](ppe_code)
- [PL3](ppe_code)

## intent:greet
- hej
- witaj
- cześć
- dzień dobry
- dobry wieczór
- siema
- Dzień dobry
- Cześć

## intent:goodbye
- pa
- do widzenia
- na razie
- do zobaczenia później

## intent:affirm
- tak
- w rzeczy samej
- oczywiście
- to brzmi dobrze
- poprawnie

## intent:deny
- nie
- nigdy
- nie wydaje mi się
- nie podoba mi się to
- nie ma mowy
- nie całkiem

## intent:mood_great
- super
- doskonale
- bardzo dobrze
- świetnie
- niesamowicie
- wspaniale
- czuję się bardzo dobrze
- jestem zadowolony
- jestem uradowany

## intent:mood_unhappy
- smutny
- bardzo smutny
- nieszczęśliwy
- źle
- bardzo źle
- okropnie
- okropne
- niezbyt dobrze
- ekstremalnie smutny
- trochę smutny

## intent:bot_challenge
- jesteś botem?
- jesteś człowiekiem?
- czy rozmawiam z botem?
- czy rozmawiam z człowiekiem?

## intent:joke
- czy możesz opowiedzieć mi żart?
- chciałbym usłyszeć żart
- opowiedz mi dowcip
- żart proszę
- opowiedz mi żart
- czy potrafisz opowiadać dowcipy?
- muszę usłyszeć żart
- czy możesz opowiedzieć mi kawał?
- chciałbym usłyszeć kawał
- opowiedz mi kawał
- kawał proszę
- czy potrafisz opowiadać kawały?
- muszę usłyszeć kawał

## intent:location
- gdzie jesteś?
- gdzie mieszkasz?
- gdzie teraz jesteś?
- gdzie cię znajdę?
- jesteś tam?

## intent:insult
- kurwo
- chuju
- cipo
- pizdo
- debilu
- cioto

## intent:thanks
- dzięki
- dziękuję
- dziękuję ci
- bardzo ci dziękuję

## intent:name_inform
- mam na imię [Kamil](name)
- nazywam się [Magda](name)
- [Stefan](name)
- mów mi [Agata](name)
- jestem [Zbigniew](name)
- mam na imię [Krzysztof](name)
- nazywam się [Andrzej](name)
- [Przemysław](name)
- mów mi [Jan](name)
- jestem [Katarzyna](name)

## intent:ask_name
- jak masz na imię?
- jakie masz imię?
- jak się nazywasz?
- jak mam cię nazywać?
- jak mam do ciebie mówić?
- masz imię?
- posiadasz imię?
- podaj mi swoje imię?
- czy masz imię?
- czy posiadasz imię?

## intent:creator
- kto jest twoim twórcą?
- kto cię stworzył?
- twórca
- czy zostałeś stworzony?
- czy zostałaś stworzona?
- kto jest twoim stwórcą?
- kto cię zrobił?
- stwórca
- czy znasz swojego twórcę?

## intent:age
- ile masz lat?
- ile czasu żyjesz?
- jak długo żyjesz?
- jak długo jesteś na tym świecie?
- ile już żyjesz?
- czy długo żyjesz?
- czy ty żyjesz?

## intent:too
- ciebie również
- ciebie też
- nawzajem
- wzajemnie
- ciebie też miło poznać

## synonym:bill
- faktura
- fakturze

## synonym:meter_read
- licznika
- licznik

## synonym:saldo
- saldzie
- salda

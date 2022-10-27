Jeg lagde en workflow fil som laster ned en kopi av repository og setter opp et miljø som bygger programmet, og sørger for at alle tester kjører når det gjennomføres push. 

Byggingen gikk fint, men testene ville ikke kjøre initielt. Måtte endre navn på test-klassen, og bruke veiledning fra canvas for å legge til riktig dependency og benytte surefire plugin for at testene skulle kjøre



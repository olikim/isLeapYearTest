Jeg lagde en workflow fil som laster ned en kopi av repository og setter opp et miljø som bygger programmet, og sørger for at alle tester kjører når det gjennomføres push. 

Byggingen gikk fint, men testene ville ikke kjøre initielt. Måtte endre navn på test-klassen, og bruke veiledning fra canvas for å legge til riktig dependency og benytte surefire plugin for at testene skulle kjøre


<img width="801" alt="Screenshot 2022-10-27 at 20 38 53" src="https://user-images.githubusercontent.com/90384162/198371950-95c60b51-0b15-41f0-8cec-e687ac3f121a.png">

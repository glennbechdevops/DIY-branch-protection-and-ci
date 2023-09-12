# DIY-branch-protection-and-ci

I denne oppgaven skal du sette opp et repository fra scratch etter beste praksis 

# Hensikt med oppgaven

* Hensikten er at du skal kunne sette opp et GitHub repository, fra bunnen av, med kontinuerlig integrasjon, og en beskyttet branch.

# Oppgave 

Lag et nytt GitHub repository, bruk Spring Initializer https://start.spring.io/ til å lage et nytt Spring Boot prosjekt. 

* Legg filene inn i ditt eget repository.
* Lag en GitHub Actions Workflow. Konfigurer GitHub actions til å bygge Spring Boot applikasjonen, og stoppe for eksmepel ved en unit-test feil. 
* Konfigurerer repository med en beskyttet branch, slik at ingen kan comitte direkte på ```main```
* Konfigurer "Status Checks" på ditt repository slik at man ikke kan gjøre en merge til ```main```dersom Maven bygget feiler.

# Relevant informasjon 

* https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/managing-a-branch-protection-rule
* https://github.com/glennbechdevops/01-CI-Github-actions

  Lykke til!

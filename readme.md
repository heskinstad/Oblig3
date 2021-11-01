Oblig 3 i Software engineering og testing ble gjort i samarbeid mellom Marius Gade og Hans Eivind Skinstad.

Fremgangsmåte for hvordan vi løste oppgaven:

Vi startet med å bruke Hans Eivinds Main- og test-filer fra Oblig 2.

Opprettet så YML-filen etter denne guiden: https://docs.github.com/en/actions/automating-builds-and-tests/building-and-testing-java-with-maven slik at Github Actions Workflow ville fungere.

Vi fikk først testene til å kjøres på GitHub Actions Workflow etter at vi så tipset til Mats Lindh om maven-surefire-plugin.

Testet så at alt fungerte som det skulle ved å skrive en av testene slik at den ville feile, og Github ga oss tilbakemelding om dette.
Rettet så på feilen ved å fikse testen, og Github ga oss deretter tilbakemelding om at alt var OK.

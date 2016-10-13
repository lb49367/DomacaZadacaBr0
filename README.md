#JMBAG 0036493670 

#Pitanje 1.
Nakon sto smo dodali ClassLibrary referencu u folderu Bin/Debug dodane su dvije nove datoteke ClassLibrary1 i ClassLibrary1.dll
Ako izbrisemo dll datoteku program KonzolnaAplikacija se nemoze pokrenuti.
Za pokretanje programa potreban nam je izvrsni .exe asemblij nazvan KonzolnaAplikacija i ClassLibrary1.dll, a ostalih 6 datoteka nakon sto su izbrisane nisu utjecale na pokretanje programa.

#Pitanje 2.
KonzolnaAplikacija prilikom pokretanja s izmjenjenim stringom nakon build solution koristila je novi string.

#Pitanje 3.
Pero: Hello World

#Pitanje 4.
U folder Bin/Debug je dodan PeroClassLibrary.dll

#Pitanje 5.
Nakon sto je obrisana orginalna verzija na disku aplikacija i dalje radi, a  Add Reference se nalazi pod recent

#Pitanje 6.
To prevent NuGet from restoring packages during build, open the Visual Studio Options dialog, click on the Package Manager node and uncheck 'Allow NuGet to download missing packages during build.' - build nije uspio

U packages direktoriju ponovno se pojavio NodeTime

# Szablon pracy magisterskiej/inżynierskiej do LaTeXa dla wydziału W4N Politechniki Wrocławskiej

Stworzony szablon powinien przestrzegać wszystkoich wymogów edytorskich określonych na stronie wydziału. Jakby coś się nie zgadzało to proszę o kontakt.

## Wykorzystane pakiety

Wszystkie wykorzystane pakiety zostały opisane w komantarzach w pliku `main.tex`. Można zobaczyć do czego konkretny pakiet służy i usunąć linijkę z kodu jeżeli jest dla nas zbędny.

## Strona tytułowa

Strona tytułowa <u>**nie**</u> została przygotowana w LaTeXu ze względu na zwykłe lenistwo. LaTeX ma jednak możliwość wgrania pliku PDF i dołączenie go do całości dokumentu. Tak też jest dołączona strona tyytułowa w tym szablonie. Polecam wygenerować stronę tytułową np w google docsach jako PDF z szbalonu wydziałowego (dołączony plik `pd_szablon.docx`, pobrany z [Praca dyplomowa - Wydział Informatyki i Telekomunikacji](https://wit.pwr.edu.pl/studenci/dyplomanci/praca-dyplomowa)) a następnie wgrać ten plik do LaTeXa. Miejsce w kodzie, w którym należy podmienić plik jest odpowiednio zaznaczone komentarzem. 

## Przykłady

Przykłady jak wstawiać tabele, rysunki, równania czy listingi znajdują się w pliku `chapter1.tex`, który następnie jest inlcudowany do pliku `main.tex` :)

## Bibliografia

Wpisy literaturowe znajdują się w pliku `biblio.bib` i tam należy dodawać swoją literaturę, a następnie odwołać się do niej w tekscie np. poprzez `/cite{id}`. Przykłady również są w pliku `chapter1.tex`.

## Jak uruchomić szablon?

Polecam [Overleafa](https://overleaf.com/). Wgrywacie wszystkie pliki do nowego projektu i powinno wszystko działać. W innych narzędziach pewnie trzeba będzie doinstalować różne pakiety więc może być z tym dużo zabawy.  

Szablon na pewno nie jest idealny ale jak dla mnie wystarczający. W razie pytań i problemów chętnie pomogę. **Piszcie w LaTeXu bo jest super :)**

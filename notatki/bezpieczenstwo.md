# Bezpieczeństwo – hasła w repozytorium

Repozytorium publiczne może przeglądać każdy, a boty automatycznie skanują GitHuba w poszukiwaniu haseł i kluczy dostępu, więc zapisany w nim klucz może zostać przechwycony w ciągu kilku minut.
Zgodnie z modelem odpowiedzialności współdzielonej za taki wyciek odpowiada autor repozytorium, a nie GitHub.
Samo usunięcie pliku z hasłem nie wystarcza, ponieważ Git przechowuje pełną historię zmian i hasło nadal jest widoczne we wcześniejszych commitach.
Jedynym skutecznym rozwiązaniem jest natychmiastowa zmiana hasła lub unieważnienie klucza, a sekrety należy przechowywać poza kodem, np. w zmiennych środowiskowych lub menedżerze sekretów.

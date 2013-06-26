Tennis Game Kata :

zaimplementować tablicę wyników jednego gema tenisowego

proponowane API:

    TennisGame.
      void playerAScores();
      void playerBScores();
      String getCurrentScore();

możliwe wyniki:

* 0 0
* 15 0
* 30 0
* 40 0
*  0 15
*  0 30
*  0 40
* 15 15
* 30 30
* 40 30
itd..

*  deuce (obaj gracze wygrali przynajmniej 4 piłki i wygrali tyle samo piłek)
*  A -  (przewaga gracza A)
*  \- A  (przewaga gracza B)
*  W -  (A wygrał)
*  \- W  (B wygrał)

w celu zapoznania się z pełnymi zasadami gry:
http://en.wikipedia.org/wiki/Tennis#Scoring -> sekcja 'Game'

dodatkowo docenione zostanie:

 * jeśli projekt będzie się budował build toolem - dowolnym, np. mavenem
 * jeśli rozwiązanie będzie commitowane po trochu, bo dzięki temu zobaczymy tok myślenia
 * jeśli projekt będzie posiadał testy a dodatkowo jeśli będzie rozwijany w TDD
 * jeśli rozwiązanie będzie ładnie zrefaktorowane

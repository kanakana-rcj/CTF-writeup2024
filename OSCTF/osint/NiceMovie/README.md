## 問題
Description: Some secret spies disguised as residents went to watch a movie, but I don't know where. The only clues I have are the song and this location of a Croma Store: https://maps.app.goo.gl/LEX7fn5jXi6Wrjfs6

Flag Format: Full Address Of the Movie Theatre as per google maps. If the theatre is located inside the mall, you have to enter the location of the theatre and not the mall. For example if the theatre is PVR in Growels Mall, Kandivali (E), the google maps location of that pvr is "Western Express Hwy, Kandivali, Akurli Industry Estate, Kandivali East, Mumbai, Maharashtra 400101" So then the flag becomes: OSCTF{Western Express Hwy, Kandivali, Akurli Industry Estate, Kandivali East, Mumbai, Maharashtra 400101} (the flag can be uppercase, lowercase or mixed it doesn't matter)

・song.mp3

## write up
song.mp3を[AHA Music](https://www.aha-music.com/)で検索すると、"Dekhha Tenu"-Mohammad Faizだと判明

"Mr. And Mrs. Mahi"(2024)の曲。

Croma(家電量販店)の場所の近くの映画館を探すと、PVR theaterがある。

``` OSCTF{3rd floor, Infinity Mall, New Link Rd, Phase D, Shastri Nagar, Versova, Mumbai, Maharashtra 400036} ```
---
title: Jekyll Funtionsuebersicht
---

## Einfügen eines Links

blablabla [das hier wird blau hervorgehoben und ist anklickbar](https://www.mdpi.com/2072-4292/8/9/732){:target="_blank"}

## Einfügen eines Bildes

Online:
{% include figure image_path="https://imgs.xkcd.com/comics/seat_selection.png" alt="Comic illustrating the selection of a seat in a plane." caption_url="[CC-BY by xkcd.com](https://xkcd.com/726/){:target='_blank'}" %}

Lokal gespeichert:
{% include figure image_path="/assets/images/unit02-which-loop-to-choose.jpg" alt="Flow chart showing a decision tree which helps to choose the right loop." %}

## Einfügen einer Liste

<ul>
  <li> erster Listenpunkt </li>
  <li> zweiter Listenpunkt </li>
  <li> ... </li>
</ul>

Alternativ auch wie folgt möglich (einfacher):
  * erster Listenpunkt
  * zweiter Listenpunkt
  * ...

## Verlinkung eines externen Videos

<p><a href="https://resources.rstudio.com/wistia-rstudio-essentials-2/rstudioessentialsprogrammingpart1-2?wvideo=k8kz4e0p2v"><img src="https://embedwistia-a.akamaihd.net/deliveries/85f90f89c20cf329c8e6091508fe44c045e70167.jpg?image_play_button_size=2x&amp;image_crop_resized=960x585&amp;image_play_button=1&amp;image_play_button_color=4287c7e0" width="400" height="243.75" style="width: 400px; height: 243.75px;"></a></p><p><a href="https://resources.rstudio.com/wistia-rstudio-essentials-2/rstudioessentialsprogrammingpart1-2?wvideo=k8kz4e0p2v">RStudio Essentials Programming Part 1</a></p>

Verlinkung eines Videos inkl. Anpassen der Größe des Videofensters:

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/noZnOSpcjYY" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>


**Wichtig** Folgende Link-Struktur verwenden, um Youtube-Videos direkt einzubetten und den restlichen Youtube-Schmonz zu umgehen: https://www.youtube-nocookie.com/embed/noZnOSpcjYY

## Einfügen eines Absatzes

  <p>Hier beginnt ein Absatz, und hier ist er zu Ende.</p>
  <p>Hier beginnt ein neuer Absatz, und hier ist er zu Ende.</p>
  
Sollte aber hier in R-Markdown auch einfach mittels Absätzen im geschrieben Text funktionieren:

blablabla erster Absatz

blablabla zweiter Absatz

## Tabelle

| a    | b    | AND  | OR   |
| True | True | True | True | 
| True | False | False | True | 
| False | True | False | True | 
| False | False | False | False | 

## Code-Beispiel

```yaml
# Pseudocode
for(<iteration variable> in <control vector>){
    <do something using the iteration variable>
}
```

## Hervorgehobene Kästchen

Kästchen 1 ist blau
{: .notice--info}

Kästchen 2 ist grün
{: .notice--success}

Kästchen 3 ist rot
{: .notice--danger}

Kästchen 4 ist orange
{: .notice--warning}

## Verschiedenes Textzeug

*kursiv schreiben*

**fett schreiben**

`lustig hervorheben`

|was auch immer das hier ist|





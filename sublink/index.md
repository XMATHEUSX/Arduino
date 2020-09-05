---
layout: page
title: Piscando LEDs em tempos variados
subtitle: Example page with contents
toc: true
hide_hero: true
toc_title: Piscando LEDs em tempos variados
image: https://via.placeholder.com/640x480
show_sidebar: false
---
## Tutorial
<!-- blank line -->
<figure class="video_container">
  <iframe src="https://www.youtube.com/embed/enMumwvLAug" frameborder="0" allowfullscreen="true"> </iframe>
</figure>
<!-- blank line -->

## Materiais utilizados

 - 1 led vermelho
 - 1 led amarelo
 - 1 led verde
 - 1 led azul
 - 4 resistores 150 Ω
 - 6 jumpers
 - 1 Arduino uno R3

 

## Esquema Arduino
![esquema arduino](/pagina-teste/img/Cool Waasa-Bruticus.png)
  
  
## Código 
```
void setup()
{
  pinMode(7, OUTPUT);
  pinMode(6, OUTPUT);
  pinMode(5, OUTPUT);
  pinMode(4, OUTPUT);
}

void loop()
{
  digitalWrite(7, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(7, LOW); 
  digitalWrite(6, HIGH);
  delay(1000); 
  digitalWrite(6, LOW);
  digitalWrite(5, HIGH);
  delay(1000); 
  digitalWrite(5, LOW);
  digitalWrite(4, HIGH);
  delay(1000); 
  digitalWrite(4, LOW);
  delay(1000);
  
}
```

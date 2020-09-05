---
layout: page
title: Page With Contents
subtitle: Example page with contents
toc: true
toc_title: Custom Title
image: https://via.placeholder.com/640x480
show_sidebar: false
---
## Introdução

This is an example page with contents that are generated from the page content. 
The page contents are generated automatically using [Jekyll TOC](https://github.com/allejo/jekyll-toc).

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

---
title: Reference
layout: default
nav_order: 2
---


<!-- Example of title -->


<!-- Here comes the table of content -->
- [My Excersise in Markdown](#my-excersise-in-markdown)
- [Paragraph 1](#paragraph-1)
  - [Paragraph 2](#paragraph-2)
  - [Example of Bold text](#example-of-bold-text)
  - [Example of italic](#example-of-italic)
- [Headers](#headers)
  - [Different level header](#different-level-header)
    - [Another Level of header](#another-level-of-header)
- [Example of strikethrough](#example-of-strikethrough)
- [Links](#links)
  - [Example External link](#example-external-link)
  - [Example of link to another file](#example-of-link-to-another-file)
- [Images](#images)
  - [Photo Swinoujscie](#photo-swinoujscie)
  - [Photo RDR](#photo-rdr)
- [Example of equation](#example-of-equation)
- [Code](#code)
  - [Example of block of code](#example-of-block-of-code)
- [Example of code highlighting](#example-of-code-highlighting)
- [Example of quote](#example-of-quote)
- [Lists](#lists)
  - [Example of bullet list](#example-of-bullet-list)
  - [Example of numbered list](#example-of-numbered-list)
- [Tables](#tables)
  - [Table](#table)
  - [Table 2](#table-2)
- [The End](#the-end)


<!-- Example of paragraph of text with line break -->
# Paragraph 1
These are short, <ins>famous texts in English from classic sources</ins>
like the Bible or Shakespeare.  
 Some texts have word definitions and explanations to help you.  
 Some of these texts are written in an old style of English. Try to understand them, because the English that we speak today is based on what our great, great, great, great grandparents spoke before! Of course, not all these texts were originally written in English. 

 

<!-- Example of another paragraph -->
## Paragraph 2
<center>The Bible, for example, is a translation. But they are all well known in English today, and many of them express beautiful thoughts.The Bible, for example, is a translation. But they are all well known in English today, and many of them express beautiful thoughts.  

The Bible, for example, is a translation. But they are all well known in English today, and many of them express beautiful thoughts</center>

<!-- Example of bold -->
## Example of Bold text
**English** that we speak today is based on what our great, great, great, great grandparents spoke before! Of course, not all these texts were originally written in **English**

<!-- Example of italic  -->
## Example of italic
These are short, famous texts in *English* from classic sources like the Bible or *Shakespeare*.

<!-- Example of headers -->
# Headers
## Different level header 
These are short, famous texts in English from classic sources like the Bible or Shakespeare.  
### Another Level of header
Some texts have word definitions and explanations to help you.

<!-- Example of strikethrough -->
# Example of strikethrough 
Some texts have word ~~definitions~~ and ~~explanations~~ to help you

<!-- Example of external link -->
# Links
## Example External link
If you are interested what is happening in Swinoujscie you can check here
[External Link - Swinoujscie](https://www.iswinoujscie.pl/)

<!-- Example of link to another file -->
## Example of link to another file
Here you can find link to file  

[Link to file - swinoujscie](swinoujscie.md)

# Images
<!-- Example of an image -->
## Photo Swinoujscie
![SVG image](./images/swino_photo.png)


<!-- Example of an image with hover text -->
## Photo RDR
![alt text](./images/red-dead-redemption-2-download.png "Red Dead Redemption")



<!-- Example of equation or inline code -->
# Example of equation

$2 + 2 = 4$

X<sup>2</sup>



# Code
<!-- Example of a block of code -->
## Example of block of code

```def main(args):
    przedmioty = set(['polski', 'angielski'])  # definicja zbioru
    drukuj(przedmioty, "Lista przedmiotów zawiera: ")

    print("\nAby przerwać wprowadzanie przedmiotów, naciśnij Enter.")
    while True:
        przedmiot = input("Podaj nazwę przedmiotu: ")
        if len(przedmiot):
            if przedmiot in przedmioty:  # czy przedmiot jest w zbiorze?
                print("Ten przedmiot już mamy :-)")
            przedmioty.add(przedmiot)  # dodaj przedmiot do zbioru
        else:
            drukuj(przedmioty, "\nTwoje przedmioty: ")
            przedmiot = input("\nZ którego przedmiotu wprowadzisz oceny? ")
            # jeżeli przedmiotu nie ma w zbiorze
            if przedmiot not in przedmioty:
                print("Brak takiego przedmiotu, możesz go dodać.")
            else:
                break  # wyjście z pętli
 ```       

<!-- Example of code highlighting -->
# Example of code highlighting

```python
"def main(args):
    przedmioty = set(['polski', 'angielski'])  # definicja zbioru
    drukuj(przedmioty, "Lista przedmiotów zawiera: ")

    print("\nAby przerwać wprowadzanie przedmiotów, naciśnij Enter.")
    while True:
        przedmiot = input("Podaj nazwę przedmiotu: ")
        if len(przedmiot):
            if przedmiot in przedmioty:  # czy przedmiot jest w zbiorze?
                print("Ten przedmiot już mamy :-)")
            przedmioty.add(przedmiot)  # dodaj przedmiot do zbioru
        else:
            drukuj(przedmioty, "\nTwoje przedmioty: ")
            przedmiot = input("\nZ którego przedmiotu wprowadzisz oceny? ")
            # jeżeli przedmiotu nie ma w zbiorze
            if przedmiot not in przedmioty:
                print("Brak takiego przedmiotu, możesz go dodać.")
            else:
                break  # wyjście z pętli"

```

<!-- Example of quote -->

# Example of quote

> "Musisz kopać lub uderzać w worek ze skoncentrowanym wysiłkiem. Jeśli masz zamiar trenować bez nastawienia, że jest to prawdziwa walka, zmienisz siebie niewiele. Kiedy kopiesz lub uderzasz w worek, musisz wyobrazić sobie, że rzeczywiście uderzasz przeciwnika"  
Bruce Lee

<!-- Example of bullet list -->
# Lists
## Example of bullet list
Shopping list
* 1 l milk
* 10 eggs
* 1 kg flour
* <font color="green">1 kg apples</font>
  
  


<!-- Example of numbered list -->
## Example of numbered list

Course participants:
1. Bob Smith
2. Anna Novak
3. John Wick
4. Carl Bing


<!-- Example of table -->
# Tables
## Table
name | km   | time in min
---- | ---  | -----------
Anna | 5    |       20
Roy  | 5    |       25
Kim  | 6    |       30
Ben  | 10   |       35

## Table 2

|  Hour | Monday  | Tuesday | Wednesday | Thursday | Friday  |
|:-------:|:---------:|:---------:|:-----------:|:----------:|:---------:|
| 08:00 | Math    |         | Geography | Music    | English |
| 10:00 | Biology | Polish  | **Polish**    | English  | Math    |
| 12:00 | **French**  |         | Math      |          | Math    |
<!-- Paragraph after table -->
# The End
English that we speak today is based on what our great, great, great, great grandparents spoke before! Of course, not all these texts were originally written in English.  
<center><mark>The End</mark></center>




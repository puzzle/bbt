# Review Präsentation

Beim Sprint Ende halten die Lernenden eine kurze Präsentation in der sie zeigen was sie geleistet oder gelernt haben.

Die Präsentation wird in 3 Bereiche aufgeteilt:

## Features

Die erarbeiteten Features kurz erklären und somit eine Einleitung zum Code Beispiel geben.

## Code/Demo

Bei grossen Durchbrüchen (Erreichen von einem MVP) wäre eine kleine Demo angebracht.

**Screenshots**

Screenshot machen wir normal mit dem Ubuntu Screenshot-Tool. Am besten wirklich nur den nötigen Code 'screenshotten' und den Screenshot so klein wie möglich halten so dass der Text dann so gross wie möglich angezeigt werden kann.

**Carbon**:

[Carbon](https://carbon.now.sh/) ist ein Open-Source Screenshot-Tool.

Problem damit ist, dass der Code immer über die Website geht auch wenn
man es mit [Carbon-now](https://github.com/mixn/carbon-now-cli) verwendet.  

Somit ist Carbon nur für Open-Source Projekte geeignet.

**Atom**:

Atom hat ein eigenes [Screenshot-Package](https://atom.io/packages/screenshot).

Leider nicht sehr konsistent und schneidet horizontal zu lange Codestücke gerne ab.

**RevealJS**:

Wenn man Bilder/Screenshots in RevealJS einfügt werden sie oft zu klein angezeigt.

Man kann als mehr oder weniger tolle Lösung den HTML-Tag class="stretch" verwendet, dieser stretch das Bild grösser ohne alles kaputt zu machen.

Bsp:  \<image class="stretch" src='/assets/review35/changeRubyVersion.png'></image>

**IntelliJ**:

Um bei Screenshots der Zeilenzahl eine andere Farbe zu geben: "Settings::Editor->Color Scheme->General::Code->Line number".

**Ruby**:

Öffne das File mit Vim und mache mit Shutter einen Screenshot deines Codebeispiels.
Für sichtbares Highlighting und Zeilennummern empfehlen wir: ```git clone https://github.com/psunix/dot-vim.git ~/.vim```

Ansonsten kann man auch den Code direkt ins MD schreiben. Hier muss man aber die Zeilenzahl selbst hinzufügen und kann die grösse nicht verändern:

Wichtig ist es hier die Programmiersprache anzugeben. (Bsp: ```c)

```java
1  import org.springframework.boot.autoconfigure.SpringBootApplication;
2
3  @SpringBootApplication
4  public class PfeedbackApplication {
5
6      public static void main(String[] args) {
7        SpringApplication.run(PfeedbackApplication.class, args);
8      }
9  }
10
```

## Lerndoku

Am besten zeigt man hier einen interessanten neuen Lerndoku Eintrag und zeigt den anderen Lernenden und den Berufsbildnern
etwas Spannendes.

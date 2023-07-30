---
layout: post
title: Das binäre Zahlensystem einfach erklärt
subtitle: Eine Reise in die Welt der Nullen und Einsen
lang: de
uuid: "binary"
categories: [Informatik, Zahlensystem]
tags: [binär, dezimal, zahlensystem, umrechnung, bits, bytes, ascii, unicode]
---

# Das binäre Zahlensystem einfach erklärt
In der faszinierenden Welt der Computer verwenden wir das binäre Zahlensystem. Das hört sich vielleicht kompliziert an, aber keine Sorge, wir werden es ganz einfach erklären!

## Das Dezimalsystem - Zahlen, die wir kennen
Zuerst schauen wir uns das Dezimalsystem an, das wir im Alltag verwenden. Es besteht aus den Zahlen von 0 bis 9. Wenn wir eine Zahl schreiben, wie z.B. 123, dann hat jede Ziffer einen bestimmten Wert, je nachdem, wo sie steht. Die erste Ziffer von rechts ist die Einer-Stelle, die zweite ist die Zehner-Stelle, die dritte ist die Hunderter-Stelle und so weiter.

## Das binäre Zahlensystem - Eine Welt aus Nullen und Einsen
Im binären Zahlensystem haben wir nur zwei Zahlen: die 0 und die 1. Das mag wenig klingen, aber es ist unglaublich mächtig! In der binären Welt haben wir keine Zehner-Stelle oder Hunderter-Stelle, sondern nur die Einer-Stelle und die Zweier-Stelle.

## Bits und Bytes - Die Bausteine der Daten
In der Computerwelt sind die kleinsten Bausteine für Daten die sogenannten "Bits". Ein Bit ist entweder eine 0 oder eine 1. Mehrere Bits werden zu "Bytes" zusammengefasst. Ein Byte besteht aus 8 Bits. Mit Bytes können wir Buchstaben, Zahlen und andere Informationen speichern und verarbeiten.

## ASCII und Unicode - Die Codierung der Zeichen
Computer speichern Texte und Zeichen in Form von Zahlen. Früher wurde das ASCII (American Standard Code for Information Interchange) verwendet. Es war eine Zeichencodierung, die jedem Zeichen (Buchstaben, Zahlen, Sonderzeichen) eine eindeutige Zahl zuwies. So konnte ein Computer die Zeichen in binäre Zahlen umwandeln und speichern. Aber ASCII hatte ein Problem: Es konnte nur begrenzt Zeichen darstellen, zum Beispiel nur die Buchstaben des englischen Alphabets und einige Sonderzeichen.

Um dieses Problem zu lösen, wurde Unicode entwickelt! Unicode ist wie ein riesiges Lexikon für Zeichen aus vielen verschiedenen Sprachen und Schriften. Es kann Tausende von Zeichen darstellen, einschließlich der Buchstaben fast aller Sprachen der Welt, mathematischer Symbole, Emojis und vieles mehr!

### ASCII - American Standard Code for Information Interchange
Lasst uns über Zeichencodierung sprechen, wie wir Zeichen und Buchstaben in Computern speichern. Früher, als Computer noch ziemlich jung waren, gab es ASCII, das stand für 'American Standard Code for Information Interchange'. Es war so eine Art Zauberbuch für Computer, das jedem Zeichen eine bestimmte Zahl zuwies.

ASCII verwendete 7 Bits, um 128 Zeichen darzustellen. Und diese Zeichen umfassten Buchstaben (Groß- und Kleinbuchstaben), Zahlen, Satzzeichen und einige spezielle Zeichen. Also, wenn wir zum Beispiel den Buchstaben 'A' hatten, wurde er als 01000001 dargestellt. Das 'a' wurde zu 01100001, und die Zahl '5' wurde zu 00110101. Es war also ziemlich einfach.

Aber hier ist das Problem: ASCII konnte nur eine begrenzte Anzahl von Zeichen darstellen, und es war auf Englisch und einige Sonderzeichen beschränkt. Das bedeutete, dass es andere Sprachen und Symbole nicht darstellen konnte. Wenn du zum Beispiel Texte in anderen Sprachen oder mit besonderen Zeichen schreiben wolltest, dann konntest du das mit ASCII nicht so gut machen.

### Unicode - Die globale Zeichenkodierung
Aber dann kam Unicode! Unicode ist wie ein riesiges, magisches Buch, das viele, viele verschiedene Zeichen aus vielen verschiedenen Sprachen und Schriften enthält. Und wisst ihr, wie viele Zeichen Unicode darstellen kann? Über eine Million! Es ist wirklich wie ein Zaubertrick, der es ermöglicht, Buchstaben, Zahlen, Symbole, Emojis und so ziemlich alles andere, was du dir vorstellen kannst, darzustellen!

Mit Unicode können wir jetzt Texte in fast jeder Sprache schreiben und auch viele andere coole Symbole verwenden. Es gibt spezielle Zeichen für Mathematik, Währungen, Pfeile und vieles mehr. Es ist wirklich fantastisch!

## Umrechnung von Dezimal zu Binär
Jetzt wollen wir wissen, wie man eine Dezimalzahl in eine binäre Zahl umwandelt. Das ist gar nicht so schwer! Wir nehmen die Dezimalzahl und teilen sie immer wieder durch 2. Dabei merken wir uns den Rest. Dann schreiben wir die Reste von unten nach oben.

Lasst uns die Zahl 13 in binär umrechnen.

1. 13 ÷ 2 = 6. Rest = 1
2. 6 ÷ 2 = 3, Rest = 0
3. 3 ÷ 2 = 1, Rest = 1
4. 1 ÷ 2 = 0, Rest = 1

Jetzt schreiben wir die Reste von unten nach oben: 1101.

Das ist es! Die binäre Zahl für 13 ist 1101.

## Umrechnung von Binär zu Dezimal
Jetzt möchten wir wissen, wie wir eine binäre Zahl in eine Dezimalzahl umwandeln können. Auch das ist nicht schwer! Wir nehmen jeden Binärplatz von rechts nach links und multiplizieren ihn mit der entsprechenden Potenz von 2.

Lasst uns die binäre Zahl 1101 in Dezimal umrechnen.

1. 1 * 2⁰ = 1
2. 0 * 2¹ = 0
3. 1 * 2² = 4
4. 1 * 2³ = 8

Jetzt addieren wir diese Ergebnisse zusammen: 1 + 0 + 4 + 8 = 13.

Das ist es! Die Dezimalzahl für die binäre Zahl 1101 ist 13.

Das binäre Zahlensystem ermöglicht uns, auf einfache Weise Daten im Computer zu speichern und zu verarbeiten. Mit dem Wissen über die Umrechnung von binär zu dezimal können wir die faszinierende Welt der Nullen und Einsen besser verstehen!
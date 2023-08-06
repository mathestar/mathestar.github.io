---
lng_pair: binary
title: The Binary Number System Explained Simply
category: [computer science, number system]
tags: [binary, decimal, number system, conversion, bits, bytes, ascii, unicode]
comments_disable: true
date: 2023-07-29 11:32:53 -0400
---

# Explaining the Binary Number System Simply
In the fascinating world of computers, we use the binary number system. It may sound complicated, but don't worry, we'll explain it in a very simple way!

## The Decimal System - Numbers We Know
First, let's take a look at the decimal system that we use in our everyday life. It consists of the numbers from 0 to 9. When we write a number, such as 123, each digit has a specific value depending on its position. The first digit from the right is the one's place, the second is the ten's place, the third is the hundred's place, and so on.

## The Binary Number System - A World of Zeros and Ones
In the binary number system, we only have two numbers: 0 and 1. That may sound limited, but it's incredibly powerful! In the binary world, we have no ten's place or hundred's place, only the one's place and the two's place.

## Bits and Bytes - The Building Blocks of Data
In the world of computers, the smallest building blocks for data are called "bits." A bit can be either 0 or 1. Multiple bits are grouped together to form "bytes." A byte consists of 8 bits. With bytes, we can store and process letters, numbers, and other information.

## ASCII and Unicode - Encoding of Characters
Computers store texts and characters as numbers. In the past, we used ASCII (American Standard Code for Information Interchange). It was a character encoding that assigned a unique number to each character (letters, numbers, special symbols). This allowed a computer to convert and store characters into binary numbers. However, ASCII had a limitation: it could only represent a limited set of characters, such as the letters of the English alphabet and some special symbols.

To address this limitation, Unicode was developed! Unicode is like a huge lexicon containing characters from many different languages and scripts. It can represent thousands of characters, including letters from almost all languages in the world, mathematical symbols, emojis, and much more!

### ASCII - American Standard Code for Information Interchange
Let's talk about character encoding, how we store characters and letters in computers. In the past, when computers were still quite young, there was ASCII, which stood for 'American Standard Code for Information Interchange.' It was like a kind of magic book for computers, assigning a specific number to each character.

ASCII used 7 bits to represent 128 characters. These characters included letters (uppercase and lowercase), numbers, punctuation marks, and some special symbols. So, for example, if we had the letter 'A,' it was represented as 01000001. The 'a' was 01100001, and the number '5' was 00110101. It was quite straightforward.

But here's the problem: ASCII could only represent a limited number of characters, and it was limited to English and some special symbols. This meant it couldn't represent other languages and symbols. For example, if you wanted to write texts in other languages or with special characters, you couldn't do that very well with ASCII.

### Unicode - The Global Character Encoding
But then came Unicode! Unicode is like a huge, magical book containing many, many different characters from many different languages and scripts. And you know how many characters Unicode can represent? Over a million! It's truly like a magic trick that allows representing letters, numbers, symbols, emojis, and just about anything else you can imagine!

With Unicode, we can now write texts in almost any language and use many other cool symbols. There are special characters for mathematics, currencies, arrows, and much more. It's truly fantastic!

## Conversion from Decimal to Binary
Now, let's learn how to convert a decimal number into a binary number. It's not that difficult! We take the decimal number and repeatedly divide it by 2. We keep track of the remainders. Then, we write the remainders from bottom to top.

Let's convert the number 13 into binary.

1. 13 ÷ 2 = 6. Remainder = 1
2. 6 ÷ 2 = 3, Remainder = 0
3. 3 ÷ 2 = 1, Remainder = 1
4. 1 ÷ 2 = 0, Remainder = 1

Now, we write the remainders from bottom to top: 1101.

That's it! The binary representation of 13 is 1101.

## Conversion from Binary to Decimal
Now, let's find out how to convert a binary number into a decimal number. That's not difficult either! We take each binary place from right to left and multiply it by the corresponding power of 2.

Let's convert the binary number 1101 into decimal.

1. 1 * 2^0 = 1
2. 0 * 2^1 = 0
3. 1 * 2^2 = 4
4. 1 * 2^3 = 8

Now, we add up these results: 1 + 0 + 4 + 8 = 13.

That's it! The decimal representation of the binary number 1101 is 13.

The binary number system allows us to store and process data in computers in a straightforward way. With the knowledge of converting from binary to decimal, we can better understand the fascinating world of zeros and ones!
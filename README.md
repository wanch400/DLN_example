# Digital Lab Notebook - Example
2018 - Research Bazaar - Introduction to GitHub

# Markdown Syntax

## Headers

Use "#" as the "Headings #". The higher the number of headings, the lower the heading priority.

##  Text Decorations

We're talking about **bold**, *italics*, and ~strikethroughs~.
Another way to __bold__ and _italicised_ words.

### More example tests
***bold and italics***

**_italicssdfsdf_**

---------------------

## Bullet points, numbered lists and checked lists

### Bullet point list:
* Bullet 1
* Bullet 2
- Bullet 1 (This starts a new list)
- Bullet 2

### Numbered list:
1. Num1
2. Num2
3. Num3
3. Num...

### Checked lists:
- [ ] item1
- [x] item2

### Nesting Lists:
* item 1
  * item 1.1
  * item 1.2
* item 2
1. item 1
   1. item 2
   2. item 1.2
   3. item 1.4
2. item 2

------------------

## Tables

Let's make a clean table with markdown:
_(Note: You need at least 3 dashes in the 2nd line!)_

|Name|Age|Department|Job|
|---|---|---|---|
|Riku|25|Biocehmistry|ARF|
|Chris|20|Anatomy|Student|

_By default, the table items are center aligned._

Playing with alignment:

|Name|Age|Department|Job|
|---|---:|:---|:---:|
|Default|Right|Left|Center|
|Riku|25|Biocehmistry|ARF|
|Chris|20|Anatomy|Student|

--------------------------

## Markdown paragraphs, tests, and quotes

### Sentences and paragraphs
So this sentence contains only a single white-space in between the words.
But                this                sentences               has               a lot.

Making a new paragraph, you will need to have a free line above^.

Lorem Ipsum is simply dummy text of the printing and typesetting industry. 
Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. 
It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. 
It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

### Quotes
> Quote 1

> Quote 2
>> Indented quote!

-------------------

## Links/hyperlinks

The syntax is relatively simple:

This is a link to [Google](https://www.google.com).
This is a link to [fake Google](www.google.com).

--------------

## Codes and syntax highlighting

You can insert codes inline with a pair of `backticks`. `if`, `else` etc...

```C#
// Begin code
// Lots of code!
if (wow)
{ return "this"; }
else
{ return "that"; }

```

---

## Images

Cat meme: 

![cat meme](42-Silly-Cat-Memes.jpg)

Resized cat image:

<img src="42-Silly-Cat-Memes.jpg" width=150/>

<img src="https://media.mnn.com/assets/images/2013/05/grumpyCatComplain.jpg.838x0_q80.jpg" width=150/>

This does not work, you will need the image source!

![google search](https://www.google.co.nz/search?q=meme+cat&source=lnms&tbm=isch&sa=X&ved=0ahUKEwjA3LqjwobcAhXLjpQKHdTxCRsQ_AUICigB&biw=1242&bih=557#imgrc=AhAgt-J5L0julM:)

# anki-minimalist-mode
thoughtfully designed minimalist theme, cards and curated plugins for anki

![anki_minimalist_theme_3](https://user-images.githubusercontent.com/116316499/213336733-5bc952da-fb9e-4075-8e73-bb08a5603c92.png)

This Anki package helps you focus on the content by simplifying the UI, improving touch accessibility, and adding features that enhance your overall experience.

Notably, it makes gives you easy templates that simplify your Anki cards, visually and content-wise.

## About
It makes use of the following plugins:
- Custom Background Image and Gear Icon (to style CSS)
- Edit Field During Review Cloze
- Fill the blanks - Multiple typecloze support
- PassFail 2 Remove the Easy and Hard Buttons
- Review Heatmap
- Field AutoComplete 

It also includes the following **card types**:

1. `qa Question Answer`
> Question and Answer (Q&A) type cards.
> 
> Your bread and butter cards. Write exactly one question and answer. This forces you to keep your cards as simple as possible.

<details>
  <summary> <strong> 🖼️ Preview </strong> </summary>
<img width="1652" alt="qa1" src="https://user-images.githubusercontent.com/116316499/213340551-76e50503-842b-4c28-8c12-36d3e8dc4050.png">
<img width="1649" alt="qa2" src="https://user-images.githubusercontent.com/116316499/213340552-dd08635a-75c3-40c5-ba79-50f77c4c77d1.png">


</details>

2. `Cloze Programming`
> Fill-in-blanks type cards for learning programming concepts, algorithms and syntax.
>
> To use this card effectively, I recommend using this everytime you want to remember writing code. <br> For example, if you keep forgetting to write a certain key word, syntax, etc.
  
  This is also recommended to be used with CodeWars/LeetCode to help you with recalling how you solved a problem.
  
<details>
  <summary> <strong> 📽️ Preview </strong> </summary>
  
  <small>(Click ▶️ Play to run .gif preview)</small>
  
![cloze_programming](https://user-images.githubusercontent.com/116316499/213341636-37ef45fd-547d-4682-9be9-d4ae40aab5c9.gif)
  
</details>

3. `Cloze Enhanced`
> Same as Cloze, but but with a Subject and Title field to help organise your cards.
> 
> This is an alternative way to write down a flashcard, similar to the Q&A type card. It's a second option in case you can't think of a question, or don't think a question would be a good way for you to recall something.

<details>
  <summary> <strong> 🖼️ Preview </strong> </summary>
  <img width="1651" alt="cloze1" src="https://user-images.githubusercontent.com/116316499/213340462-da03ef47-2431-4a2f-9405-ad595bdd9d30.png">
<img width="1656" alt="cloze2" src="https://user-images.githubusercontent.com/116316499/213340463-8b412169-5824-4c7e-9d36-1b9127e1f221.png">

</details>

4. `Basic Enhanced`
> Same as Basic, but with a Subject and Title field to help organise your cards.
>
> It's a passive recall card. This is the least efficient out of the three, but has its place because it's a flexible card. 
> Think of them as Sticky Notes to help you memorise small bits of info.

These first three card types are designed to force you to actively recall information, while the last one is meant to help you passively recall for difficult concepts that you don't entirely understand.

All card presentation are carefully designed for its content, be it a mix of images, text and code.

## Requirements
- Windows / Mac / Linux version of Anki
- `night-mode` or Dark Mode is enabled in your Anki preferences.
> This is a dark-mode only theme.
- Anki >= 2.1.55

For other devices that use Anki: if this is popular enough, I may look into developing a similar theme for AnkiDroid/Anki iPhone.

## How To Install

1. After downloading the source files (or `git clone`), open the .apkg file. This will give you a new deck called 'test', which contains the four new card types: `qa Question Answer`, `Cloze Programming`, `Cloze Enhanced`, `Basic Enhanced`.

2. Download The Plugins from Anki: Open up Anki, then press <kbd>CMD + A</kbd> or <kbd>CTRL + A</kbd> to open up the Add-ons Menu, then click "Get Add-ons" and copy paste these codes in to install them from the Anki website directly.

```
1210908941 385888438 1933645497 876946123 1771074083 511710206
```

3. In the same Add-on Menu, click View Files. This brings you to the general Anki Plugin Folder. <br>
Drag and Drop the the plugin folder (`1210908941`) into your Anki Plugins folder & overwrite the CSS files. 
> ⚠️ As with anything data-related, be sure to make a backup of your entire Anki Plugins folder.

4. Open Anki Preferences and change the UI Scaling to what you prefer. I recommend having a scaling of `135%`.

* Optionally: Install the Fonts from the Font folder!

Done ✅

## Syntax Rules
While in the Card Editor, here's three basic things to know:

- Italics <kbd>CMD + I</kbd> are used for in-line code, which is the <mark>white highlight</mark> on code. It has monospace font to visually represent it.
- Bold <kbd>CMD + B</kbd> is used for anything you want to point out. This is the green, thicker font you see.
- Underline <kbd>CMD + U</kbd> is the same as Bold. You're free to choose between both of these to point out important content.

🖥️ Windows Users: Replace <kbd>CMD</kbd> with <kbd>CTRL</kbd>

### This HTML is syntactically incorrect!
I know, but, this makes use of the default Anki hotkeys to make your life easier.

## What do the Plugins do?
- Custom Background Image and Gear Icon
> Styles the CSS of Anki UI elements.
- Edit Field During Review Cloze
> Lets you edit on the fly, while a card review is open.
- Fill the blanks - Multiple typecloze support
> Enables you to do `Cloze Programming` cards.
- PassFail 2 Remove the Easy and Hard Buttons
> Leaves you with 2 buttons to press, rather than 4. This doesn't mess up the Space Recall Algorithm.
- Review Heatmap
> Like GitHub's code heatmap, a quick glance to see how you're doing. I intentionally hid the details, because it's not necessary to be hooked up on your stat progress. Just keep doing what you're doing per day-- and when you want to reveal it, you can modify the `.heatmap` class and comment out `display: none;` in the CSS file.
- Field AutoComplete 
> This is useful for auto-completing certain fields, especially the subject area, to rapidly make cards.
<details>
  <summary> <strong> 🖼️ Preview </strong> </summary>
  
  ![field-autocomplete](https://user-images.githubusercontent.com/116316499/213338047-93256f3d-7ec3-4063-bd15-e1bb74ec619c.png)

</details>

<!-- ## More Previews
<img width="300" alt="CleanShot 2023-01-18 at 02 03 10@2x" src="https://user-images.githubusercontent.com/116316499/213111860-d981f653-5ce3-4926-ab79-25aa853e4f2f.png"> -->

## Disclaimer
If you are planning to use these fonts elsewhere, please be sure to review the fonts' licenses for commercial use. This is for Personal Use.

# Description

A card template for Anki for learning Chinese characters in a very efficient way.

Once you set this up in Anki, you can add new characters very quickly and they are automatically colored. A lot of steps are done for you automatically thanks to several plugins. The colorization and stylization of the characters takes place at the very end using JS and CSS.

## Example for 4th and 3rd tone

![2](2.png?raw=true "2")

## Example for 2nd and 1st tone

![4](4.png?raw=true "4")

# Background

One of the biggest challenges of the Chinese language is getting the tones right. When learning vocabulary, it's often hard to remember the tone. I found out that if I add colors to the characters, it becomes **MUCH** easier.

How much easier?

With colors, I remember the correct tone for around 98% of the characters in my Anki collection. Sometimes, very rarely (when the "Chinese support" plugin suggest a different pronounciation and I have to manually correct), the system will fail and the character is not colored. In those cases, I usually do **NOT** get the tone right on these characters.

Therefore I am convinced that the colors are a **gamechanger**.

Bonus: Seeing the stroke animation helps you remember the shape of the character and hearing the pronounciation helps you remember the reading.

## Why blue, yellow, green, red?

I have chosen the colors blue, yellow, green and red for the following reasons (reading the reasons can help you remember the colors quicker):

Tone 1 (Blue): Blue is a light, neutral color, like air floating around, which reminds me of the first tone.

Tone 2 (Yellow): The rising sun is yellow.

Tone 3 (Green): Green is the color for OK, like a checkmark, which is what the third tone looks like.

Tone 4 (Red): Red is an aggressive color, like yelling out an order/command, which is what the fourth tone sounds like.

**Tip**: If you use Pleco, customize the colors there to match your colors here in Anki.

## What are the symbols behind the reading, like the question mark and the exclamation mark?

I have found out that adding those symbols helps even a bit more, as the character becomes more memorable. You can remove them if you don't like them (have a look at the JavaScript in the "Back template" file).

## Why only have Hanzi and English card for each character? Why not also have a pronounciation and tone card?

I am aware that conventional flashcard wisdom suggests to split "knowledge" into as small a unit as possible, which in this case would mean to create separate flashcards for the pronounciation and tone of a card. However, I found out that adding a separate pronounciation and tone card did not add any value, but rather **doubled** my workload. I never had problems remembering the pronounciation (and thanks to adding colors, remembering the tone was easy, too). Therefore, when reviewing the Hanzi and English cards, I also test myself on the pronounciation (and the tone).

# Steps

## Installation

1. Download the .apkg file and import into Anki (**OR** create a new card template with the fields Hanzi, Meaning, Reading, Color, Sound, Notes, Stroke Order, Meme and copy-paste the code content from the raw-code folder.)
2. Download and install the "Chinese support" plugin for Anki: https://ankiweb.net/shared/info/3448800906
3. Download and install the "AwesomeTTS" plugin for Anki: https://ankiweb.net/shared/info/301952613

## Usage

![5](5.png?raw=true "5")

1. Open the dialog box to add a new flashcard (shortcut key: "a").
2. in "Hanzi", type the character or a word consisting of several characters.
3. Chinese support automatically fills out "Meaning", "Reading" and "Color".
4. Open the "index.html" file in the stroke-animations folder with your browser. Press CTRL+F (or CMD+F) and search the character you want a stroke animation for. Click on it to open the raw image file. Drag and drop the image file into "Stroke Order".
5. Optionally, add "Notes" and "Meme" (Meme is supposed to be some kind of image that helps you remember the character better. You can have a look at https://hanzimemes.herokuapp.com for inspiration).
6. Save the character and repeat the process for all characters.
7. Open Anki's flashcard browser (shortcut key: "b") and select all newly added flashcards. Press CTRL+T (or CMD+T) to open the "AwesomeTTS" plugin. Use it to add computer-generated pronounciations for the characters. I'm using a Mac, this is what my settings look like:

![6](6.png?raw=true "6")

8. Done! :)

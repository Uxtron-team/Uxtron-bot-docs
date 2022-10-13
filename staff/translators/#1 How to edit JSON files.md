# #1 How to edit JSON files
Well hello there translator! If you're reading this, you probably want to understand how to put your translations into the JSON file. No problem! We're here to help.

## First of all...
You will need to have a JSON file for your language. If we didn't already give one to you, please request one from `skid#4242`. Once you get your JSON file to edit on as a text file, you'll be ready to go!

## Reading JSON files and what to do
JSON files are kind of like the dictionary for the Uxtron bot. You give it a term and you translate it for the bot. When the bot wants to read the translation, it just finds the term and gets the translation directly from the JSON file. 

There are 2 main parts to a JSON file. Keys and **values**. You can think of JSON files as an online translator. What you type in (or the input) is the key. The translated content (or the output) is the **value**. In the JSON file we give you, the keys (or the thing that has to be translated) will already be inside in english. All you have to do is type in the translation as the **value**.

## How to do it
The JSON file we give you will probably look like this *(without the arrow of course)*:
```
[
  "COMMANDNAME": {
    "WHAT TO TRANSLATE": "nothing here", <--
    "WHAT TO TRANSLATE": "nothing here"
  }
]
```
You won't have to worry about anything except for the line with the arrow *(there won't be an arrow in the real JSON file)*. Don't delete ANYTHING other than the 'nothing here' text. You will have to replace that with your translated content.

### Special types of translating values
Apart from strings (anything inside single or double quotation marks), there might also be arrays, another type of **value** is arrays. Arrays are essentially just a list of **values** that are all connected to 1 key. An example would be:
```
[
  "COMMANDNAME": {
    "WHAT TO TRANSLATE": ["text1", "text2", "text3"] <--
  }
]
```
If arrays are not already there, you won't have to use them. If they are there though, there should be instructions on what to put for each item in the list.

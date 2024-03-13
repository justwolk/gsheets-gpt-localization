# GPT3.5/4 Google Sheet localization for games

## Usage:

1. Go to your Google Sheet -> Extentions -> App Scripts
2. Click "+" button in "Files"
3. Paste script from (https://github.com/justwolk/gsheets-gpt-localization/blob/master/GPT.gs) to this file
4. Change your OpenAI api key in script, press press CTRL+S
5. In first cell for traslation write '=GPT3(C2, C$1)' where GPT3 or GPT4 - version of gpt, C2 - cell for translate, C$1 - cell with language definition, stretch to your needs
6. To save translated values copy them, and press ctrl + shift + v

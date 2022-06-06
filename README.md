# CatscatsSoundboard

This project is lightweight and requires no dependencies to operate. Just extract somewhere, and open the `index.html`. This was originally created as a quick & hacky soundboard interface for web. There is a ton of room for improvement.
## Adding Soundbits

1. Trim and place the audio file in `./snd` as a compressed mp3.
2. Update `js/soundboard_collection.js` to add the sound to match the proper syntax. To keep consistenticy, name the file & variable `PERSON_SOUNDNAME`.
Example: 
   ```js
   var starr_laugh1 = new Audio('snd/starr_laugh1.mp3');
   ```
3. Add the button to the html file, and update the onclick to match the var you defined. Example:
   ```js
   onclick="starr_laugh1.play();"
   ```
4. Profit.
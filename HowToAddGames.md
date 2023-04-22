## How to add your favorite retro games to the eth.id emulator:

1. Find the embed code for your favorite retro game. You can find embed codes on the [Retro Games CC](https://www.retrogames.cc/) website, which this emulator is inspired by.

2. Determine which console the game is for (GameBoy, N64, Arcade, etc.) and open the corresponding dropdown menu in the emulator's HTML code.

3. Within the dropdown menu, add a new `<li>` element. The `<li>` elements represent each game option.

4. Within the `<li>` element, add an `<a>` link. The `<a>` link will open the embed code in an iframe when clicked.

5. In the `<a>` link, paste the embed code you found for your favorite retro game.

6. Save the modified HTML code. Your new game option should now appear in the appropriate console's dropdown menu!

7. Refresh the emulator page in your web browser to see your new game added. When users click on it, the game's embed code should load in an iframe.

8. (Optional) You can also modify the CSS styling for the dropdown menus and buttons by editing the `style.css` file to customize the appearance.

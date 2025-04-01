Just some cookie clicker commands and cheats to paste into your browser console. 

description of commands: 

unlockAllAchievements(); -- unlocks all achievements

resetGame(); -- resets game data


**THE FOLLOWING CODE IS BUNDLED TOGETHER!**
(function() {
    // Get the current game data
    const gameData = JSON.parse(localStorage.getItem('CookieClickerSave'));

    // Set the desired number of cookies (replace with your desired amount)
    const newCookieAmount = 1000000;

    // Update the cookies in the game data
    gameData.cookies = newCookieAmount;

    // Save the updated game data back to localStorage
    localStorage.setItem('CookieClickerSave', JSON.stringify(gameData));

    console.log(`Cookies updated to ${newCookieAmount}. Reload the game to see changes.`);
})();
**END OF BUNDLED CODE** (edit "newCookieAmount = ((whatever amount of cookies you want))) 

**NOTE; MAY NEED TO RELOAD FOR CHANGES TO TAKE EFFECT!**





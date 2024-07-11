## Learning how to hack the game in 5 minutes! (Farm Merge Valley in Discord)
[![Hits](https://hits.sh/github.com/earluv/discord-farm-merge-valley-hack.svg)](https://hits.sh/github.com/earluv/discord-farm-merge-valley-hack/)

### What you need?
- browser (preferably Google Chrome)
- 5 minutes of free time 


## Enums to use in bypass

| Parameter |   Is reward   | Description                |
| :-------- | :------- | :------------------------- |
| `coins` | True | Yellow coins |
| `gems` | True | Purple gems |
| `crates` | True | Crates with items |
| `energy` | True | Energy for activities |
| `tickets` | True | Train tickets |

## Game functions for issuing rewards

| Function |    | Description                               |
| :-------- | :----- |:------------------------------------------|
| `this._data.reward`      | | Function to issue items from enums        |
| `this._data.expReward`      | | Function to issue pure XP for leveling up |

## Process for obtaining game privileges
```
This post is made for educational purposes to understand how to bypass the game. I do not encourage using this method and am not responsible for your actions.
```

### Step 1 - Opening the console
<details>
  <summary>Click to expand the information</summary>

1) Join any voice channel and start the activity
2) Open the browser console `(F12, Ctrl+Shift+I or Cmd+Opt+I)`
3) Go to the `Source` tab
4) Find the folder `appid.discordsays.com` and open it
   ![find](images\1_1.jpg)

</details>

### Step 2 - Finding the required function and setting breakpoints 
<details>
  <summary>Click to expand the information</summary>

1) Find the file `main.js` and open it

   ![find](images\2_1.png)
2) Press `Ctrl+F` and search for `this._data.reward` if you need to issue items, or `this._data.expReward` if you need to issue XP

   ![find](images\2_2.png)

3) Click to the left on the gray line to place a breakpoint

   ![find](images\2_3.png)

</details>

### Step 3 - Bypassing the game `(this._data.reward)`
<details>
  <summary>Click to expand the information</summary>

1) Find any resource on the map (coin, gem, crate, energy, ticket)

   ![find](images\3_1.png)
2) Click on it and you will see information in the `Scope` window
   ![find](images\3_2.jpg)
4) Click on the triangles where it says `this` and go to `reward`
   ![find](images\3_3.jpg)
5) ^ In the `amount` field, enter the value you want to issue, and in the `key` field, enter the resource name as indicated in the table above
6) Press 1 and then 2 in sequence
   ![find](images\3_4.jpg)
7) Watch as the items start being issued

   ![find](images\3_5.jpg)
</details>

### Step 3 - Bypassing the game `(this._data.expReward)`
<details>
  <summary>Click to expand the information</summary>

1) Merged 3 objects on the map

   ![find](images\3_6.jpg)
2) Click on it and you will see information in the `Scope` window
   
   ![find](images\3_2.jpg)
4) Click on the triangles where it says `this` and go to `_data`

   ![find](images\3_8.jpg)
5) ^ In the `expReward` field
6) Press 1 and then 2 in sequence
   ![find](images\3_4.jpg)
7) Watch as the items start being issued

   ![find](images\3_9.jpg)
</details>

### Result 🎉

If you did everything correctly, you should see the items you specified.

## Star the repo!!! ⭐

If I was able to help you, please star the repository. This will help me in my further work.

<h3> Important: This material is made for educational purposes only. I do not encourage using this method and am not responsible for your actions. </h3>

### Contact Me:

[Telegram](https://t.me/earluv_dev)

[Discord](https://discord.com/users/211148434273468426) | @earluv

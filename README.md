## Learning how to hack the game in 5 minutes! (Farm Merge Valley in Discord)

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
| `this._data.reward`      | | Function to issue items                   |
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
![find](https://cdn.discordapp.com/attachments/1197967901039271966/1259889733279027210/telegram-cloud-photo-size-4-5791919010072348505-y.jpg?ex=668d5340&is=668c01c0&hm=d1266876e43e998fe38c5e5a8229fd280e5b3615910a231d7ff4edddd184d724&)

</details>

### Step 2 - Finding the required function and setting breakpoints for `(this._data.reward)`
<details>
  <summary>Click to expand the information</summary>

1) Find the file `main.js` and open it

   ![find](https://cdn.discordapp.com/attachments/1197967901039271966/1259891038106161192/image.png?ex=668d5477&is=668c02f7&hm=866fcbd646844b26851081b8c15cf025c83d6b6c7f503709be00e30b68fc2b13)
2) Press `Ctrl+F` and search for `this._data.reward`

   ![find](https://cdn.discordapp.com/attachments/1197967901039271966/1259891836797980682/image.png?ex=668d5535&is=668c03b5&hm=772dd893f9aaeaa6e4403521a1aea4c22bf534ca33048901057dfd88bad3582c&)

3) Click to the left on the gray line to place a breakpoint

   ![find](https://cdn.discordapp.com/attachments/1252922369736179776/1259919838445572166/image.png?ex=668d6f49&is=668c1dc9&hm=baecef3c34ea71e33878d8165f9ae4852e97229387d317a6841c0cdd298feb63&)

</details>

### Step 3 - Bypassing the game `(this._data.reward)`
<details>
  <summary>Click to expand the information</summary>

1) Find any resource on the map (coin, gem, crate, energy, ticket)

   ![find](https://cdn.discordapp.com/attachments/1252922369736179776/1259912551257346078/image.png?ex=668d6880&is=668c1700&hm=d7b36792d1936c8bcc5b507fd01531f0f60224978838a63981b2a3d0aa8d3a51&)
2) Click on it and you will see information in the `Scope` window 
![find](https://cdn.discordapp.com/attachments/1252922369736179776/1259913041189802175/telegram-cloud-photo-size-4-5791919010072348527-y.jpg?ex=668d68f5&is=668c1775&hm=04a4cbaff4071d63258330aa300c173ba43dac65f90b8dd78a949b3a7b14f22c&)
3) Click on the triangles where it says `this` and go to `reward`
![find](https://cdn.discordapp.com/attachments/1252922369736179776/1259914084007153664/telegram-cloud-photo-size-4-5791919010072348528-x.jpg?ex=668d69ed&is=668c186d&hm=c9e2400f2a972d075dc628873226caeee6a48d804255dcae0781e11134f4f21d&)
4) ^ In the `amount` field, enter the value you want to issue, and in the `key` field, enter the resource name as indicated in the table above
5) Press 1 and then 2 in sequence
   
   ![find](https://cdn.discordapp.com/attachments/1252922369736179776/1259915096168206358/2024-07-08_19.51.15.jpg?ex=668d6adf&is=668c195f&hm=b5d5837351446552e85b14e688ea0a7ac0218ce8bb661e7b21bc2ce7dfe82d35&)
7) Watch as the items start being issued

   ![find](https://cdn.discordapp.com/attachments/1252922369736179776/1259915627376939068/telegram-cloud-photo-size-4-5791919010072348529-x.jpg?ex=668d6b5d&is=668c19dd&hm=11e9a1b9cc13a97c2664e45b5f1d5e92524e970feba70026e21f8f517d2eb193&)

</details>

### Result 🎉

If you did everything correctly, you should see the items you specified.

## Star the repo!!! ⭐

If I was able to help you, please star the repository. This will help me in my further work.

<h3> Important: This material is made for educational purposes only. I do not encourage using this method and am not responsible for your actions. </h3>

### Contact Me:

[Telegram](https://t.me/earluv_me)

[Discord](https://discord.com/users/211148434273468426) | @earluv

## 🍪 Grandma's Cookies

**Difficulty:** - Intermediate 🐢

**Category:** Wallets 👛, Smart Contracts 🧑‍💻

At long last, my grandma finally shared her legendary cookie recipe with me.
She handed it over on a handwritten note... along with one delicious cookie.

But disaster struck!
Both the note and the cookie were stolen from my wallet — only a few crumbs remain. 😱

Fortunately, the thief wasn’t careful. On their way out, they left a trail of crumbs behind.
And if you look closely, you’ll notice pieces of the recipe scattered along the path...

Here’s my wallet address: `addr_test1qzvt6dzdv5f3qxw4rt25nwf3z32rns7sp03f22g0qhfeu2yzsy6nyzcur6alufxtx0q0tu6pu6389t9xz4rskcprvkgs5enfwd`

__Side note__: This is a real recipe — if you recover it, you’ll end up with some seriously tasty cookies!
(Mix it all together and bake at 170°C for 10-12 minutes)

## 🔍 Part 2 – The Final Crumb
I finally pieced together the full recipe!
But now the cookie itself is gone...

The last address in the trail leads to the thief’s secret hideout.
Rumor has it they've already started baking.
Luckily, I can still claim one cookie — but only if I provide the correct password.

How to mint a cookie:
The password is a combination of all the recipe ingredients (comma-separated),
plus your public key hash — all hashed together with BLAKE2b-256.

Example:
```blake2b_256("Butter,Flour,Sugar,Eggs<YOUR_PUBLIC_KEY_HASH>")```

__Oh, and one more thing:__
The hideout appears to be... a smart contract.
You will need it to get your Cookie:
```
59014e01010029800aba2aba1aba0aab9faab9eaab9dab9a488888896600264653001300800198041804800cdc3a40009112cc004c004c01cdd500144c966002600460106ea801226464b3001300f0028acc004c010c028dd519198008009bac300f30103010301030103010301030103010300c3754601e01244b30010018a60103d87a80008992cc004cdc79b943371491015f313235674275747465722c3130306753756761722c36306742726f776e53756761722c314567672c32303067466c6f75722c3174737042616b696e67506f776465722c3150696e636853616c742c313530674461726b43686f636f6c61746500001375c6022601c6ea8026266e95200033010375200297ae089980180198090012018375c602000280722946294100945900c1bae300d0013009375400916401c6eb8c02cc020dd50014590060c020004c00cdd5004452689b2b200201
```
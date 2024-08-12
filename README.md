<h1 align="center">
    STRONGPG
</h1>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/damartripamungkas/strongpg?color=04D361&labelColor=000000">
  
  <a href="#">
    <img alt="Made by" src="https://img.shields.io/static/v1?label=made%20by&message=damartripamungkas&color=04D361&labelColor=000000">
  </a>
  
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/damartripamungkas/strongpg?color=04D361&labelColor=000000">
  
  <a href="#">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/damartripamungkas/strongpg?color=04D361&labelColor=000000">
  </a>
</p>

<br>

![Home](/screenshot/home.png)

### 🌐 Visit :

- https://strongpg.my.id
- https://damartripamungkas.github.io/strongpg

### 📖 Description :

This website helps users who want to create `very strong` passwords for accounts on the internet such as Facebook, Google, TikTok and others. This website will create a password from the text you enter (see image above).

### 🪂 Features :

- supports everything for account passwords including those requiring symbols, numbers
- ripemd128 hashing algorithm for create result password then slice from 0 ~ 16. formula: `@X + ripemd128(..).slice(0, 16)`
- reinforcement Before iterations: will perform hashing with the formula listed before iteration.
- support iterations, Iteration refers to applying the hash function double based on the provided number. For instance, if the number given is 2, the process would be as follows: `hash(hash("your text"))` In other words, your words are hashed once, then the output is hashed again. So a higher count leads to greater computation worked into hashing the data.

### 👮 Security :

This website does not store any user input or other user data. You may review the source code to confirm that no data is saved. Additionally, turning off internet connection when accessing the website to prove it.

### 🥤 Donation For Support Me :

contact me at telegram [here](https://t.me/damartripamungkas)

### 📝 License :

Licensed see [here](./LICENSE).

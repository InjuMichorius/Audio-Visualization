# Audio-Visualization 🎶
![](https://github.com/InjuMichorius/ReadEar/blob/master/public/img/documentatie/white.gif)

I build this project to learn more about the canvas element. I wanted to do something with music to, so I decided to mix these two things to create an application that visualizes sound.

[Click here for the live demo](https://injumichorius.github.io/Audio-Visualization/)

# Table of Contents 🧭
1. [Goal](https://github.com/InjuMichorius/Audio-Visualization#goal-)
2. [Getting started](https://github.com/InjuMichorius/Audio-Visualization#getting-started-)
3. [Wishlist](https://github.com/InjuMichorius/Audio-Visualization#feature-wishlist--backlog-)
4. [Practises](https://github.com/InjuMichorius/Audio-Visualization#design-patterns-and-best-practices-)

# Goal 💪🏻
The goal of this project is to get better at html canvas and Javascript. I also want to learn about music with code.

# Getting started ✨
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Technical requirements
To run this project you'll need any [code editor](https://code.visualstudio.com/download)

## 📥 Installing
### 1. Clone this repository 👯
Before we can get started, we'll need to clone this repository. We can do this by typing the following line of code in the terminal:
```bash
git clone https://github.com/InjuMichorius/Audio-Visualization.git
```
### 2. Open index.html 💻
Open the index.html. The application should now be running on your local machine!

# Feature wishlist / backlog 👑
Below is a list of features I'd love to add to this application. The features are split up using the **M**o**SC**o**W** method.

**M** - Must haves
_These features are requirements for the end product_
- [x] Visualisation of sound
- [x] (Web) Audio

**S** - Should haves
_These features are wanted, but not necessary for a usable product_
- [x] Option to add own music
- [x] Sound effect on click for discoverability

**C** - Could haves
_These features can be added if there is enough time to do so_
- [ ] List of music which you can choose from

**W** - Would haves
_These features can be added in the future_
- [ ] Edit visualization pattern

# Design patterns and Best Practices 👩🏻‍💻
__Code standards are important__ when working on any project; your code stays *consistent* and is *readable* for everyone. I defined code standards for __HTML__, __CSS__ and __JS__ while working on this project.

## Javascript code standards
* Variables & functions are written in __camelCase__
* Promises are handled with __async functions__ using await
* I don't use var, only __const__ or __let__
* I put __spaces around operators__ ( = + - * / ) and after commas (exception for for loops)
* I use indentation with __TAB__
* I always end a statement with a __semi-colon;__
* Functions have their opening bracket on the __same line__ as the name, with 1 space in between
* I use __ES6 syntax__ where possible

## CSS code standards
* I try to avoid __!important__ as much as possible
* Layout/general styling is always __above__ more specific styling
* Selectors are not unnecessary __long__ nor __short__
* I use __CSS3 syntax__ where possible
* I avoid old display properties like float
* CSS Selectors must have a __space__ between the name and bracket

## HTML code standards
* I only use IDs when the element is present __once__ on a page and it's necessary for styling or Javascript
* I always write semantic HTML according to __W3C Validator__
* Divs are only used when __necessary__ for styling purposes
* Classes allow easy __re-usage__
* Indentation is always __clear__

# License 🔐
This project is licensed under the MIT license by © Inju Michorius, 2021. See the [LISENCE.md](https://github.com/InjuMichorius/Audio-Visualization/blob/master/LICENSE) file for details.

# Mini YouTube

[![GitHub license](https://img.shields.io/github/license/vinitshahdeo/Mini-YouTube?logo=github)](https://github.com/vinitshahdeo/Mini-YouTube/blob/master/LICENSE) [![GitHub top language](https://img.shields.io/github/languages/top/vinitshahdeo/Mini-YouTube?logo=javascript)](https://github.com/vinitshahdeo/Mini-YouTube/) [![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/vinitshahdeo/Mini-YouTube?logo=git&logoColor=white)](https://github.com/vinitshahdeo/Mini-YouTube/) [![Youtube API](https://img.shields.io/badge/YouTube-API-critical.svg?style=flat&logo=youtube)](https://developers.google.com/youtube/v3/getting-started)


### A web app where one can search YouTube videos in sorted order according to number of likes, comments, views, name and date. It is made using [YouTube API v3](https://developers.google.com/youtube/v3/getting-started).

<br>

<img src="./assets/youtube.gif" width="30%" height="50%">


## Instruction

- Get your **YouTube API key [here](https://developers.google.com/youtube/v3/getting-started)**.

- Replace **`API_KEY = XXXXXXXXXX`** in `js/youtube.js` with your own YouTube API key.

```js

const API_KEY = 'XXXXXXXXXXXX'; // REPLACE IT WITH YOUR YOUTUBE API KEY

```

- Open `index.html` with any browser(say chrome, mozilla etc.) Kindly assure the proper internet connectivity before you start browsing videos on **[Mini YouTube](https://github.com/vinitshahdeo/Mini-YouTube/)**.

- Enter your query(*e.g. 'Prank Videos', 'Shreya Ghosal', 'Girls like you' etc.*) to browse videos.

- **Click on `Search` icon.**

- Navigate through the dropdown menu to sort the results.

<br>

## Note

- By default, **5 results are returned by [YouTube API](https://developers.google.com/youtube/v3/getting-started)**.
- The retrieved `JSON` Object from YouTube API is displayed in Browser Console.
- The website is responsive. Kindly resize the browser window to see it.

<br>

## External Resources used

1. [Font Awesome](https://fontawesome.com/) - It is used for importing icons in the web app.
2. [Google Fonts](https://fonts.google.com/) - `Oxygen` and `Acme` Google fonts are used.
3. [JQuery](https://jquery.com/)

<br>

## Author

**[Vinit Shahdeo](https://www.linkedin.com/in/vinitshahdeo/)**

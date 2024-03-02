# Website Downloader 💾
Download the complete source code of any website (including all assets) 🔨.

👉 Live Demo: <s>https://websitedownloader.herokuapp.com/</s> Sorry heroku can't deploy website anymore

![enter image description here](https://github.com/Setiawan007/Website-Downloader/blob/master/public/Record.gif?raw=true)


# Description 📒
 Website downloader works with `wget` and `archiver` to download all websites assets and compress then sends it back to the user through socket channel
 
 **wget params the being used**
 
 `wget --mirror --convert-links --adjust-extension --page-requisites 
--no-parent http://example.org`

 **Explanation of the various flags:**

 - --mirror – Makes (among other things) the download recursive.
- --convert-links – convert all the links (also to stuff like CSS stylesheets) to relative, so it will be suitable for offline viewing.
- --adjust-extension – Adds suitable extensions to filenames (html or css) depending on their content-type.
- --page-requisites – Download things like CSS style-sheets and images required to properly display the page offline.
- --no-parent – When recursing do not ascend to the parent directory. It useful for restricting the download to only a portion of the site

# How to run it 🤔

- `git clone https://github.com/Setiawan007/Website-Downloader.git`
- `cd website-downloader`
- `$ npm install`
- `$ npm start`
- `http://localhost:3000/'

# Thanks

<br>
<a href="https://sociabuzz.com/setiawan007/support" target="_blank"><img src="https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black" height="32px" alt="Sociabuzz"></a>
Tue Aug 22 12:28:19 UTC 2023
Sat Mar  2 12:25:10 UTC 2024

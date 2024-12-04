1. fork the template from [https://github.com/binyamin/eleventy-garden](https://github.com/binyamin/eleventy-garden) when logged into github **Alternatively** you can click the green 'code' button, and select 'download zip'. Then unzip the folder somewhere on your machine (and skip step 2).
2. clone the repo onto your own machine (having github's command line tool installed on your machine) with `git clone https://github.com/binyamin/eleventy-garden.git` 
3. have [obsidian.md](https://obsidian.md) installed on your machine
4. use obsidian to open the `notes` folder from eleventy-garden as a vault. 
5. make notes using obsidian. Interlink your notes with `[[` and `]]` . Each note will be its own page in the eventual garden
6. install node [from here](https://nodejs.org/en/download)
8. open a terminal or command prompt in the eleventy-garden folder and type `npm install`.
9. When that finishes, type `npm start`

This will build your site. The actual html will be in a new folder called `_site` . 

To put this online you have a range of options, including [gh-pages](https://pages.github.com/) or [Netlify Drop](https://app.netlify.com/drop). Of the two, Netlify Drop is probably easier - just drag the entire folder onto the 'drop' target on the website.

**Do you need to do this?** No. But a version of this workflow is how I get your free-writing documents into our garden. I thought you might be interested.
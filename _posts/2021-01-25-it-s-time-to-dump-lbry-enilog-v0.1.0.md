---
title: It's time to DUMP LBRY | Enilog | v0.1.0
layout: post

---
\### LBRYMeta Dumping

\----------------

One day I woke up and wanted to categorize \[Guntenberg project\]([https://open.lbry.com/@Gutenberg:a?r=AvBnTypxaVLfM5b95bc1sFUVfiL8w24t](https://open.lbry.com/@Gutenberg:a?r=AvBnTypxaVLfM5b95bc1sFUVfiL8w24t "https://open.lbry.com/@Gutenberg:a?r=AvBnTypxaVLfM5b95bc1sFUVfiL8w24t")) into my \[Enypt\]([https://enypt.cc](https://enypt.cc "https://enypt.cc")) library.

But Bravo to @blanxs who mass uploaded 52400 books. So it wasn't possible for me to list it manually.

Then I thought to use LBRY SDK and loop through each page using claim search but that would take a lot of resources.

Then a beautiful thing caught my sight. LBRY's \[Chainquery API\](https://[https://chainquery.lbry.com/api/](https://chainquery.lbry.com/api/ "https://chainquery.lbry.com/api/")). With this a simple get request and beautification modules helped to to parse the full channel data easily

Thanks to @brendon for helping me with query parameters.

\### Turning into a usable software.

\-----------------

It's no fun if you keep the magic to yourself. But If I shared the source code, not all could modify it in JS. So grabbed my makeup box \[_Code editor_\] and started doing my favourite thing. **Grabbing from user input**.

\### Running with Binaries

\-----------------

What's easier than double clicking and getting started? I know I know , _blankets_

To run from binaries :

\- Download your suitable one from \[Releases\]([https://github.com/Eniamza/lbrymeta/releases/](https://github.com/Eniamza/lbrymeta/releases/ "https://github.com/Eniamza/lbrymeta/releases/"))

\- Clicking \[_You do know how to click right?_\]

\- Enter channel claimid which can be found from about section of channels

\- Press enter and if everything is working well a \`Meta.json\` file will appear in the same directory consisting all information

\### Running from source

\-----------------

\- Install NodeJS \[Add to path if needed\]

\- Clone tha repo git clone [https://github.com/Eniamza/lbrymeta.git](https://github.com/Eniamza/lbrymeta.git "https://github.com/Eniamza/lbrymeta.git")

\- Install dependencies npm install

\- Run the app node index.js

\- Enjoy 😉

\### Bonus

\------------------

You don't need to have LBRY Running or lbrynet. less resources :grin:
# NYT Crossword to Puz

![Logo](other/logo.png)

A windows program to convert NY Times crosswords from the web to Across Lite compatible files.

To run this, first download and decompress the [release](https://github.com/Q726kbXuN/nytxw_puz/releases/latest/download/nytxw_puz.zip).  Then, run the executable, and answer the two questions:

```
Enter the NY Times crossword URL: https://www.nytimes.com/crosswords/game/daily/1994/02/14
Enter the output filename: example.puz
Loading https://www.nytimes.com/crosswords/game/daily/1994/02/14...
Created example.puz
```

Note: Running this script requires you're logged into nytimes.com in your browser.

Alternatively, you can pass in the URL and filename from the command line.

To run the Python script directly, clone this repo, then setup the venv to download packages:
```
python -m venv .venv
.venv\Scripts\activate.bat
```

And install the packages:
```
python -m pip install -r requirements.txt
```

Then, to use:
```
nyt.py https://www.nytimes.com/crosswords/game/daily/2021/08/03 2021-08-03.puz
```

# Mini FAQ

* What? Why?

The New York Times announced that on August 10th, [they will no longer provide](https://www.nytimes.com/2021/08/02/crosswords/nyt-games-no-longer-available-on-across-lite-as-of-aug-9.html) Across Lite .puz files for download.  This tool was made in response to that decision, allowing users of that tool to continue to solve crossword puzzles in their favorite program.

* Why not just use the NY Times app?

For me personally, I want something that works completely offline, and doesn't require I stare at my phone even more.  I'm sure other people have other reasons, so I decided to put my little tool online for others to use.

* Anything else?

Feel free to contact me on [reddit](https://www.reddit.com/user/nobody514/).


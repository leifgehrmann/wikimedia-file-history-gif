# wikimedia-file-history-gif

A shell script that creates an animated GIF showing the revisions of a file hosted by Wikimedia Commons.

## Usage

```
./wikimedia-file-history-gif [WIKIMEDIA_FILE] [OUTPUT_GIF] [SIZE]
```

## Example

Below is an example of the script being run on the following file:

https://commons.wikimedia.org/w/index.php?title=File:2022_Russian_invasion_of_Ukraine.svg&offset=&limit=250#filehistory

```
./wikimedia-file-history-gif "File:2022 Russian invasion of Ukraine.svg" example-ukraine.gif 500x336
```

![Animated GIF of the revision history of the invasion in Ukraine](example-ukraine.gif)

Source: ["2022 Russian Invasion of Ukraine"](https://commons.wikimedia.org/w/index.php?title=File:2022_Russian_invasion_of_Ukraine.svg)
by Wikimedia Commons contributors 
([CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.en)) as of 2022-02-27T19:00;00
### Web scraper
> submits get requests to Hacker News' API endpoints, and then appends the data to a text file, which we will later parse and enter into our data base

### How to use
1. Modify scraper.js 
  1. Change the filename on line 37
    * The 'items' numbers should be the same as your beginning and end values from index.html.
    * For example: 'items-1-n.txt' for start of 1.
 
1. Start a node server
  1. Open your terminal
  1. Navigate to your root folder for Scraper.
  1. Enter 'node scraper.js' in the command line to start a local node server that will write data to your file.
1. Disable power conservation settings on your mac.
  1. Plug your computer into a charger.
  1. Click the  in the upper left bar on your home screen.
  1. Select system preferences
  1. Select energy saver.
  1. Check
    * Prevent computer from sleeping automatically when the display is off
    * Wake for Wi-Fi network access
    * Kindly close pop-ups that warn you you're going to waste power
  1. Uncheck
    * Put hard disks to sleep when possible
    * Enable Power Nap while plugged into a power adapter
1. Open index.html from the scraper folder in your browser.
  * Enter a start and end value in the boxes that are 2000 apart.
  * For example, 1-2001.
1. When you're done downloading:
  1. Close the browser.
  1. Navigate to the scraper_data folder.
  1. Open the text file to find the last item downloaded.
  1. Rename the file by replacing n with the last item downloaded.
    * If item 5555 was the last item you downloaded the file would be renamed items-1-5555.txt

### Current index of data
1. 1 - 1,692,160 items completed (Justin)
1. 4,879,476 - 8,474,817 items completed (Adam)

* Total on Oct. 12: 5,287,501
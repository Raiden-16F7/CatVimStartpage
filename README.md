<h1 align=center>CatpuccinVim Startpage</h1>
<h5 align=center>vim-command-like minimal startpage for your browser</h5>
<h5> Inspired by </h5>[Okitavera vimstart](https://github.com/okitavera/vimstart)

![previews](https://user-images.githubusercontent.com/9277632/37031211-7f55d200-2170-11e8-8424-c9f2b6c21135.gif)

## Installation

Clone this repo

    git clone https://github.com/Raiden-16F7/CatVimStartpage.git
    
And set the index.html as homepages or new tabs in your browser.


## Usage

There is a few command that can be used :

###### Open favourites website listed in web.json, example (open gmail):

     :em

###### Go to url, example :

     :u http://google.com

###### Search, example :

     :s How to learn japanese


## Editing

To customize colors and Greeting Text see: [`web.json`](web.json).


## Frequently Asked Question

##### You need to provide local file access to your browser 

Due to security issues in chrome, they disabled local file access, so our web.json can't be readed. 

For Chrome:

    Run cmd to get a command window.
    Move to the Chrome directory, e.g., cd C:\Users\your-user-name\AppData\Local\Google\Chrome\Application.
    Type: chrome.exe --allow-file-access-from-files.

For Firefox or Waterfox:
    
    Type about:config in searchbar to go into browser settings,
    Search for security.fileuri.strict_origin_policy and double click on it to set it false.


## License

The code is available under the [MIT license](LICENSE).

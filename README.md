# Amber Theme 

Amber is a CSS theme originally designed for 8chan /cyber/ board. It tries to emulate old amber CRT monitor. 

Eventually, this repo will host themes for browsers, GTK2/GTK3 or some tiling WM like AwesomeWM. 

## Using 8ch board theme

Firstly, go to [Options] menu, select Theme tab and switch to Yotsuba B theme in drop-down. After that, paste contents of this file: https://raw.githubusercontent.com/cyber-user/Amber/master/amber.css in user CSS theme and press save button. 

Alternatively, use Stylish add-on, make new style and paste contents there. 

## Using Vimperator theme 

Install Vimperator: http://www.vimperator.org/vimperator/ Create a text file. Windows: 

    C:/users/<username>/.vimperator/colors/amber.vimp

*nix: 

    ~/.vimperator/colors/amber.vimp
    
Then copy/paste the following text into it: https://raw.githubusercontent.com/cyber-user/Amber/master/amber.vimp


If you want it to apply automatically, add the following code to .vimperatorrc

    colorscheme amber

It's located in 

    C:/users/<username>/.vimperatorrc

or 

    ~/.vimperatorrc

(create the file if it does not exist)


## Xchat/Hexchat theme 

Find config file. On Windows it is located in %APPDATA%, and in ~/.xchat on *nix. Back it up your colors.conf file by rename to 

    colors.conf.old

Then create a text file named colors.conf and paste the following text into it: https://raw.githubusercontent.com/cyber-user/Amber/master/colors.conf


# C++ Programming Style: Guilds, Rules, and Patterns.

Licensed under [MIT License][].

## Download PDF

```bash
$ wget -c https://raw.github.com/ccock/cps/master/cpp-programming-style.pdf
```

## Downloads

You can obtain full latex source files of C++ Programming Style from [https://github.com/ccock/cps](https://github.com/ccock/cps)

## Install Tex

You should install full texlive packages.

- Ubuntu     

```bash
$ sudo apt-get install texlive-full
```

- MacOS

Download [MacTeX.pkg](http://tug.org/mactex/), and install it.

- Windowns
      
Download [CTEX-full](http://www.ctex.org/CTeXDownload), and install it.

## Install Missing Fonts

Then you should install some missing chinese fonts.

- Ubuntu

```bash
$ sudo mkdir /usr/local/share/fonts/truetype
$ sudo cp -R fonts /usr/local/share/fonts/truetype
$ cd /usr/local/share/fonts/truetype
$ sudo mv fonts win-fonts
$ sudo chown -R root win-fonts
$ sudo fc-cache
```

- MacOS 
    
Import all missing fonts into fontbook

- Windows
 
Copy the all missing fonts into C:/WINDOWS/Fonts

```bash
$ fc-cache
```

## Build

```bash
$ make
```

## Preview PDF

```bash
$ open output/cpp-programming-style.pdf
```

## License

[MIT License](http://opensource.org/licenses/mit-license.html) 

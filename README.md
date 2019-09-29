# Qt Completions for C++
![Preview](./preview.gif)
## About

A Sublime text package that pops up suggestions for common Qt5 classes and components. It's purpose is to make coding easier and faster without the need for memorizing widget names or methods.


## Installation

### By Package Control

1. Download & Install `Sublime Text 3` (https://www.sublimetext.com/3)
1. Go to the menu `Tools -> Install Package Control`, then,
   wait few seconds until the `Package Control` installation finishes
1. Go to the menu `Preferences -> Package Control`
1. Type `Package Control Add Channel` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, input the following address and press <kbd>Enter</kbd>
   ```
   https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json
   ```
1. Now, go again to the menu `Preferences -> Package Control`
1. This time type `Package Control Install Package` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, search for `C++ Qt Completions` and press <kbd>Enter</kbd>

See also:
1. [ITE - Integrated Toolset Environment](https://github.com/evandrocoan/ITE)
1. [Package control docs](https://packagecontrol.io/docs/usage) for details.


### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files
* Copy the folder to your Sublime Text `Packages` directory


## How to Use

On a Python file in sublime text, type your desired component name or method and suggestions should follow. Press tab and autocomplete will be made.

## Example


> Note: All the string with bold below is used to specify which case it should begin with.

| Component Usage    | Package display          | Package Type |
| :-------------:    | :-------------:          | :-----:      |
| **s**etMaximumSize | `setMaximumSize();`      |  Methods     |
| **Q**tWidgets      | `#include <QtWidgets>`   |  Modules     |
| **Q**Label         | `QLabel`                 |  Classes     |
| **Q**Audio         | `#include <QAudio>`      |  Namespaces  |
| **I-**QLabel       |  `QLabel* labe = new QLabel();` | Instances |

> **Note:** You need to use **upper case** `I-` to get instances completion.

> Advice: This completion package is meant for Qt for C++ and not C++. You can disable this package if working on C++ alone.

## Contributing

All contributions are welcome. You can fork it on [Github](https://github.com/tushortz/Qt-Completions-for-Cpp)

## License
© 2015 Taiwo Kareem | taiwo.kareem36@gmail.com.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

## Acknowledgements
I'd first like to say a very big thank you to God my creator. Without him, this wouldn't be possible.








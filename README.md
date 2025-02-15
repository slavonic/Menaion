# Menaion Typeface

Menaion is a typeface modelled after the script of Putyatya's Menaion (National Library of Russia, Sof. 202; eleventh century). It provides both Cyrillic and Glagolitic characters and is intended for representing text from Ustav-era Church Slavonic manuscripts.

![Sample Image](documentation/image2.png)

## History

Menaion was designed by the [Manuscript project](http://mns.udsu.ru/) at Udmurt State University. It was reencoded for Unicode by Aleksandr Andreev with permission from the original authors as part of the
[Slavonic Computing Initiative](https://sci.ponomar.net/fonts.html)
and edited, released under SIL OFL v. 1.1.
Further edited by Aleksandr Andreev and Nikita Simmons.

## License

This Font Software is licensed under the SIL Open Font License,
Version 1.1. This license is available with a FAQ at
[https://openfontlicense.org/](https://openfontlicense.org/).

## Building the Fonts

The font is built using fontmake and gftools post processing script. Tools are all python based, so it must be previously installed.

To install all the Python tools into a virtualenv, do the following:

From terminal:

```

cd your/local/project/directory

#once in the project folder create a virtual environment. 
This step has to be done just once, the first time:

python3 -m venv venv

#activate the virtual environment

source venv/bin/activate

#install the required dependencies

pip install -r requirements.txt

```

Then run the this command:

```
cd sources
gftools builder config.yaml
```

The fonts are supposed to build automatically in the repository 
using GitHub Actions, but this does not work correctly 
for some reason.

## Features

* The font provides a number of ligatures, which are made by inserting the Zero Width Joiner (U+200D) between two characters.

## More Church Slavonic Fonts

See the [main repository](https://github.com/typiconman/fonts-cu/issues) and the [website](https://sci.ponomar.net/fonts.html).
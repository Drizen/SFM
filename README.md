# SFM
**S**tudent **f**ile **m**anger

## What it is
SFM is a program which monitors your download directory and automatically sorts specific files into a directory that the user wants via keywords.

The reasoning for it being called Student file manager is that this program was designed so my school related files could automatically be sorted into the correct directory without me having to manually do it.

## How to use
```
git clone https://github.com/Drizen/SFM.git
pip install watchdog
cd SFM
./SFM -cD <downloads-directory>
./SFM -a <directory> <keyword>
./SFM -R
```

An example of me using it

```
git clone https://github.com/Drizen/SFM.git
pip install watchdog
cd SFM
./SFM -cD /home/my_user/Downloads
./SFM -a /home/my_user/German germ
./SFM -a /home/my_user/English eng
./SFM -a /home/my_user/Math math  
./SFM -a /home/my_user/Science sci
./SFM -R
`
```


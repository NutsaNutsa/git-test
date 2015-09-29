Zaza
> Homework project Zaza for **MACS, OS101, [FUT](http://freeuni.edu.ge)** - 2015 Fall

#Introduction
პროგრამა fsh (free shell) 'unix shell'-ის ერთ-ერთი იმპლემენტაციაა მსგავსად bash-ის, ksh-ს და csh-სა.

###Developers
Project is Written by the group of developers:
- [Developer 1](https://github.com/dev1)
- [Developer 2](https://github.com/dev2)
- [Developer 3](https://github.com/dev3)
- [Developer 4](https://github.com/dev4)

###External Libs
კოდს მოჰყვება ყველა საჭირო დამხმარე ბიბლიოთეკა, რომელთაც makefile აყენებს
```

#Usage
user-ი თავს ისე გრძნობს, როგორც სტანდარტულ ტერმინალთან. სიმარტივისათვის პროგრამას მოჰყვება მუშა makefile, რომელიც უზრუნველყოფს კოდის გასაშვებად მზაობას. fsh იძლევა PIPE ინტერპროცეს კომუნიკაციის მექანიზმის გამოყენების საშუალებას. მეტი მოხერხებულობისთვის fsh ინახავს შეყვანილი ბრძანებების ისტორიას. გარდა ჩაშენებული ბრძანებებისა, fsh-ს აგრეთვე შეუძლია ნებისმიერი გარე პროგრამის გამოძახება. 

##Feature 1
- dsc 1
- dsc 2
- dsc 3

##Feature 2
- dsc 1
- dsc 2
- dsc 3
```
e.g.
some example
```

#Project Structure

###Tree
```
.
├── somesrc.c
├── makefile
├── README.md
├── somedir
│     ├── othersrc.c
│	    ├── otherheader.h
└── otherdir
      ├── somemoresrc.c
      └── somemoreheader.h
```

###Modules

- **modeule_one.[c/h]**:
> this module contains implementation of ...

- **modeul_two.[c/h]**:
> this module contains implementation of ...

``` C
...
typedef struct {
      int argc;
      char ** argv;
} some_struct;

void some_fn(some_struct* c);
...
```

- **main.c**:
> Entry point of the programm, ...

###makefile
project is built using [make](http://www.gnu.org/software/make/manual/make.html),
file contains instructions for [make](http://www.gnu.org/software/make/manual/make.html)
to build project.

###README.md
readme of the project.

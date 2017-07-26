# todo.txt-hide
A [todo.txt](http://todotxt.com/) plugin to hide task containing specific keywords


## Installation

`cd` into your plugins folder (see [Installing Addons](https://github.com/ginatrapani/todo.txt-cli/wiki/Creating-and-Installing-Add-ons)), e.g.:


```
cd ~/.todo.actions.d
```

Then clone this repository into the folder *hide*:

```
git clone https://github.com/bozakov/todo.txt-hide hide
```

The directory structure should look like this now:  

```
└── ~/.todo.actions.d/
    └── hide
        ├── README.md
        └── hide
```

## Usage

Hide tasks containing *ANY* of the listed terms:

    todo.sh hide +foo bar

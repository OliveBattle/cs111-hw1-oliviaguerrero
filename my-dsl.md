# Language

[YAML](https://en.wikipedia.org/wiki/YAML) was originally an acronym for *Yet Another Markup Language*, but later changed its name to the (recursive) acronym *YAML Ain't Markup Language*.

# Domain

+ Wikipedia describes YAML as a `human-readable data-serialization language.`
+ Alternatively, *storing data, with markup features*.

# Computational model

"Running" YAML code would involve parsing a .yaml file and using its data in either a program written in a general purpose language, or using the info to control how to present the data to the user.

# DSL-ness

YAML is purely domain-specific. The language is not Turing complete, and only functions as a format for storing data, albiet in a human-readable way that can still handle a number of different data types.

# Internal or external?

YAML is an external language- it isn't valid code of any general purpose programming language, and can actually be parsed into many different programming languages.

# Host language

YAML parsers exist for a number of different popular general programming languages, and it wasn't designed for a specific one.[^1]

[^1]: Due to how YAML is designed, JSON files are inherently valid YAML syntax. JSON's original host language is Javascript. 

# Benefits

Because YAML primarily relies on whitespace and line breaks for structure, it is easily able to store many kinds of data without said data unintentionally containing a break charaacter that separates it into two parts. This also makes it easily human readable.

# Drawbacks

Because YAML primarily relies on whitespace and line breaks for structure, this makes it easy to accidentally commit harmful indentation errors.


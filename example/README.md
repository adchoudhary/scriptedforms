# Scripted Forms Package Example

Scipted Forms is designed to be used as a quick and easy GUI for python
packages. Within this directory is an example package that creates a console
script that then uses scriptedforms to boot up a GUI.

## Running the example

To run this example you need to download this repository. One way to do that
is by downloading the [repository zip file](https://github.com/SimonBiggs/scriptedforms/archive/master.zip).

Once you have download and extracted the repository navigate to 
this `example` directory and then install this package by running the following within a terminal:

```bash
pip install -e .
```

To then use the package, in any directory on your machine within a terminal run:

```bash
example
```

This will then boot up the scriptedforms GUI in your default browser.

As an extra benefit, if you have either `simple.md` or `complicated.md` open in
the browser while you edit and save the file scriptedforms will automatically
reload.
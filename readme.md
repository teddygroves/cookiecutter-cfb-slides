# Cookiecutter CfB slides

This is a template for writing slides in org mode with a CfB latex template.

## How to use the template

First make sure you have installed
[cookiecutter](https://cookiecutter.readthedocs.io),
[~pandoc~](https://pandoc.org/) and
[~make~](https://www.gnu.org/software/make/).

Now run this command:

```sh
cookiecutter gh:teddygroves/cookiecutter-cfb-slides
```


Follow the wizard's instructions, then write your slides. When you want to turn
them into a pdf, run

```sh
make slides.pdf
```

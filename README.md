# HeroTemplates

## Introduction
These are the templates to generate a module following the Hero architecture.

Specify the template by name in your `Rambafile` and run `generamba template install` to install the template.

The `HeroModule` generates the following directories and classes:
- view
  - `ViewController`
  - `View`
- coordinator
    - `Coordinator`
- router
  - `Router`
- useCase
  - `Usecase`

## Usage

Just add the following lines to your `Rambafile`:

```
# a shared template catalog
catalogs:
- 'https://github.com/fluidmobile/heroTemplates'

# add template by name
templates:
- {name: HeroModule}
```

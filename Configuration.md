# Configuration

Every Polydoc project is configured using a `.polydoc` file found in the root of your project,
which file tells Polydoc how to process your project. At its most basic, this file contains
a single property telling Polydoc what type of project it is dealing with.

The `.polydoc` file is a simple `yaml` file. Below outlines all the available options that
this file can contain. Anything extra will simply be ignored.

## Project type

All projects require this key, as it tells Polydoc what type of documentation you are trying
to generate. Below is an example of a basic markdown project.

```yaml
project_type: markdown
```

Polydoc supports the following values for the `project_type` key:

- markdown

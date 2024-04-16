# Hello World

This simple [Cog](https://cog.run) model takes a string as input and returns a string as output.

## Usage

First, make sure you've got the [latest version of Cog](https://cog.run/#install) installed.

Build the container image:

```sh
cog build
```

Now you can run predictions on the model:

```sh
cog predict -i text=Athena

cog predict -i text=Zeus
```
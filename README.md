# pebble-tutorial

## Introduction

Belmont Pebbles allow you to automatically deploy your Python functions as web services. You tell your platform where your code is, and the Pebbles platform will create web service URLs that will run the Python functions you've defined.

## Tutorial preparation

You can use our example code for the first few tutorial exercises, though you may wish to fork a copy of it into your own repository so you can experiment with modifying the code and seeing what happens.

## Hello world

Let's deploy a simple script with a simple function.

Log in to the Pebbles platform UI, and create a new Pebble. Point at our base repository (`https://github.com/BelmontTechnology/pebble-tutorial.git`) or your own copy of the repository. Use the `main` branch, and point at the path `01_hello.py`. This is the script and the function we'll deploy as a service.

## Multiple functions

We can also deploy multiple functions from a single script. When a script contains multiple function definitions, the platform creates web services ("endpoints") for each function.

Create a pebble from the `02_summarystats.py` file in the tutorial repository's `main` branch and see that you can call URLs from each of the corresponding functions.

## Persistence

## Secure database access

Pebbles web services run in the public cloud, so any data they need to access must be available to the public internet. But Pebbles may nevertheless authenticate in order to access secured resources
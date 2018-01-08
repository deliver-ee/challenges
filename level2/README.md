# LEVEL 2: 🚀 Sort algorithm

## Overview

We want to find the bests couriers to deliver a *pending* delivery.

The purpose here is to build a small algorithm to *sort* couriers upon 2 parameters:

- The courier has to be geographically as close as possible to the delivery *pick-up* location.

- A courier with *already* 2 or more *deliveries* assigned can't be selected.

## Expected behavior

Process the `input.json` to obtain the same couriers order as in `output.json`.

## Caveats

- Distances in `output.json` are in kilometers.

- Calculate the distance between two locations using longitude and latitude (no need to query an API such as ©Google Maps for this level).


_May the force be with you_

# steamR

[![Build Status](https://travis-ci.org/josegallegos07/steamR.svg?branch=master)](https://travis-ci.org/josegallegos07/steamR)

`steamR` provides an [R](http://www.r-project.org/) wrapper for [Steam's Web API](https://developer.valvesoftware.com/wiki/Steam_Web_API).

The ultimate aim of `steamR` is to allow access to the all juicy data available on [Steam](http://steampowered.com) and to pave the way for some neat analyses.

## Installation

`steamR` is currently only available on github.

Install the development version from github using [devtools](https://github.com/hadley/devtools):

###
     # install.packages("devtools")
     install_github("josegallegos07/steamR")

## Usage

Use of Steam's APIs requires that you agree to the [Steam API Terms of Use](http://steamcommunity.com/dev/apiterms).

### Steam Key

All requests require a Steam Web API Key. You can get a key [here](http://steamcommunity.com/dev/apikey).

**Please do not share your key as it identifies you when you make requests.**

### Available Methods

An exhaustive list of available methods:
###
     steamR_methods()

### Getting Started

Methods to get you started:

<table style="width:100%" class="table">
  <tr>
    <th style="width:30%; text-align:left">method</th>
    <th style="width:70%; text-align:left">description</th>  
  </tr>
  <tr>
    <td>get_app_list</td>
    <td>
      Returns an exhaustive list containing the
      name and id of every program available in the Steam store.
   </td>
  </tr>
  <tr>
    <td>get_steam_id_64</td>
    <td>
      Returns a user's 64-bit Steam ID.
   </td>
  </tr>
</table>

### Examples

See [examples](examples/).

## Bugs & Feature Requests

Open [a new issue](https://github.com/josegallegos07/steamR/issues) if you want to report a bug or request a new (or missing) feature.

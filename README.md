## Forked from [Shayne](https://github.com/shayne)

This forked version moves the settings file from the execution path to %AppData%

Additionally, this version allows you to only dim the primary monitory (useful for my setup where I have a very small monitor underneath my primary which is dedicated to widgets, emails, SMS, chat, etc) which i want fully illuminated all of the time

# PowerDimmer

[![Main workflow](https://github.com/shayne/PowerDimmer/actions/workflows/workflow.yml/badge.svg)](https://github.com/shayne/PowerDimmer/releases/tag/main)

A simple distraction dimmer for Windows

| [<img src="https://user-images.githubusercontent.com/79330/147771591-853256ae-f4f1-42d3-8c68-ea467febeb58.png" width="800" />](https://user-images.githubusercontent.com/79330/147771591-853256ae-f4f1-42d3-8c68-ea467febeb58.png) |
| :--: |
| *Dim everything but focused window* |

| [<img src="https://user-images.githubusercontent.com/79330/147770555-5efe9efc-88e1-438e-a559-47b5f495976b.png" width="800" />](https://user-images.githubusercontent.com/79330/147770555-5efe9efc-88e1-438e-a559-47b5f495976b.png) |
| :--: |
| *Multiple focused windows via dimming toggle hotkey* |

## Features

Initial Release

* Dims all but currently focused window
* Toggle dimming for a specific window via `Win + Shift + D`
* Adjust brightness level from the system tray context menu

## Building

Just install the [.NET 6.0 SDK](https://dotnet.microsoft.com/en-us/download) and then `dotnet run` 

## Context

I threw this project together after finding my own need PowerDimmer. I initially tried LeDimmer. It works well enough, but it's abandoned, closed source and very out of date.

A fan of PowerToys I checked for an open issue and found [microsoft/PowerToys#13035](https://github.com/microsoft/PowerToys/issues/13035). I decided to write this to try and gain support and get this module added to PowerToys.

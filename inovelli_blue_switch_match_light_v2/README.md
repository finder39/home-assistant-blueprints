# Inovelli Blue Switch - Match Light v2

This is a single automation (not a blueprint) that will match any set of switches to their corresponding desired lights to have the LED bar match the brightness.

## Automation

[inovelli_blue_switch_match_light_v2.yaml](https://github.com/finder39/home-assistant-blueprints/blob/master/inovelli_blue_switch_match_light_v2/inovelli_blue_switch_match_light_v2.yaml)

Make sure to add this to one of your automations.yaml files

## Required sensor for the automation to work

[templates.yaml](https://github.com/finder39/home-assistant-blueprints/blob/master/inovelli_blue_switch_match_light_v2/templates.yaml)

Make sure you modify the array in attributes for the sensor named `list`. This is what the automation will use when created

## Thoughts

I planned to create it as an all inclusive blueprint at some point, but i failed to trigger efficiently. This is very efficient currently and I didn't want to sacrifice that. I may add that code up if anyone wants to help fix it. Create an issue and lemme know if so.
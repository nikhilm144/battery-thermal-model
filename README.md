This model considers the heat generated inside a battery and models the heat loss to environment and also simulates a scenario where a fan cools the battery.

The relay block turns on at 28 degrees and gives output 1. This output is used in the formula:
h_dynamic = h + relay_output × (h_fan - h).
here h=5, h_fan=15. This formula changes the value of h depending on the value of T. The logic is that
if T rises to 28 from 25, fan will turn on, and the h value will increase cooling the battery down.

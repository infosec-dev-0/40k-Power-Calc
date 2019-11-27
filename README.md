# 40k-Power-Calc
A calculator for Points per Wound, Shots per Point, and other 40k math

This project aims to take the excellent unit evaluation article found https://www.goonhammer.com/quantifying-naramyth-a-method-of-unit-evaluation-or-a-love-letter-to-the-skorpius-chassis/ and turn it into a quick calculator for list building.

My first goal of the project is to build a quick interactive script for taking a unit and outputing the Essential Points per Would and Points per shot.  Further goals would be adding a GUI, and a roster input.


Notes on math:
Points per Wound: Minimum Unit Models * Wounds per Model / Points of Minimum unit size
Points per shot: Weapon Shots per Model / Points per model
Points per shot Categories: Incidental, Standard, Significant, Major, Super
Points per Incidental Shot: Str less than or equal 4 / Points per Model * .05
Points per Standard Shot: Str 5 with no multi damage / Points per Model * .75
Points per Significant Shot: Str greater than or equal to 5 with greater than or equal to 2 damage / points per model
Points per Major Shot: Str greater than or equal to 8 with greater than or equal to 3 damage / points per model * 1.25
Points per Super Shot: Str greater than or equal to 9 with greater than or equal to 4 damage / points per model * 1.5

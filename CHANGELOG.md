Changelog

All notable changes to the GWA Calculator project will be documented in this file.

Group members:
* Darielle Timothy Salino
* Xienna Beatrix Cafe
* Marcvin Basti Pagapong

[0.1.0] - 2026-03-26

Added
* Initial implementation of GWA Calculator core structure.
* Subject input system and basic GWA computation logic.
* Feature to detect and display the highest and lowest grade.
* Handles ties by listing multiple subjects if they have the same grade.

[0.2.0] - 2026-03-27

Added
* Implemented initial projection feature
 * Detects lowsest grade using max() logic
 * Fixed increase of 0.25
* Grade description using conditional statements Excellent, Very Good, Good and etc
  
[0.3.0] - 2026-03-28

Improved
* Allows custome user input instead of fixed 0.25
* Prevents invalid values and ensures grades stay within valid range

Fixed
* A bug where highest grade returned 0.00 due to invalid

# Conduit Bending Calculator

## Purpose
A simple, fast conduit bending calculator designed for working electricians.

The goal is to calculate conduit bending measurements with minimal user input.

## 1. Offset Calculator

The user enters:
- Offset depth (inches)
- Desired bend angle (degrees)

The calculator automatically determines:
- Correct multiplier
- Distance between bend marks
- Center-to-center spacing between bends

## 2. Standard Offset Multipliers

Use the following reference multipliers:

| Bend Angle | Multiplier |
|---|---:|
| 10 degrees | 5.8 |
| 15 degrees | 3.9 |
| 22.5 degrees | 2.6 |
| 30 degrees | 2.0 |
| 45 degrees | 1.4 |
| 60 degrees | 1.2 |

## 3. Calculation Formula

Distance between bend marks = Offset depth × Multiplier

Example:

Offset depth: 6 inches
Bend angle: 30 degrees
Multiplier: 2.0

Calculation:
6 × 2.0 = 12 inches

Distance between bend marks: 12 inches

## 4. User Interface Requirements

- Large, easy-to-read numbers.
- Simple angle selection.
- Minimal typing.
- Automatic calculations.
- Clear measurement results.
- Easy reset button.
- Support inches and fractions.
- Work completely offline.

## 5. Accuracy Requirements

- Use the correct multiplier for each bend angle.
- Clearly identify all measurements.
- Avoid rounding errors.
- Verify calculations against established electrical bending references before release.
- Never substitute calculated results for proper field verification.

## 6. Future Features

- Three-point saddle calculator.
- Four-point saddle calculator.
- Back-to-back bend calculator.
- Parallel offset calculator.
- Conduit shrink calculator.
- Multiple conduit size support.

## Project Status

Initial conduit calculator specification created.
Ready for calculation development and testing.

# Pixelssuite Preview Automation Test

This project automates preview testing of the Pixelssuite website using Playwright and Python.

## Tested Feature
Image Format Conversion - Convert to PNG

## Test Scenario
The script uploads a PNG image file, checks whether the preview is displayed correctly, captures a screenshot, and records the execution result in a CSV file.

## Requirements
- Python 3.x
- Playwright
- openpyxl

## Installation

Install dependencies:

pip install playwright openpyxl

Install Playwright browsers:

python -m playwright install

## How to Run

Run the automation script:

python image_preview_test.py --url "https://www.pixelssuite.com/convert-to-png" --slow-mo-ms 2000

## Expected Output
- execution_results.csv updated with test result
- preview_pass.png saved in results folder

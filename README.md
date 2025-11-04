# HalfTrend cAlgo Indicator

This repository contains the source code for the HalfTrend indicator for the cAlgo trading platform.

## Overview

The HalfTrend indicator is a trend-following indicator that provides entry and exit signals. It is displayed as a colored line on the chart, with the color changing to indicate the trend direction. The indicator also displays arrows to signal trend changes and can show the number of pips gained or lost on each trade.

## Features

*   **Trend Identification:** The indicator clearly identifies the trend direction with a colored line.
*   **Entry and Exit Signals:** The indicator provides clear entry and exit signals with arrows.
*   **Customizable Parameters:** The indicator has several customizable parameters, including the price types, period, and moving average type.
*   **Pips Display:** The indicator can display the number of pips gained or lost on each trade.

## Installation

1.  Open the cAlgo platform.
2.  In the cAlgo Automate application, click on the "Indicators" tab.
3.  Click the "New" button to create a new indicator.
4.  Copy the code from the `halfis` file and paste it into the new indicator file.
5.  Click the "Build" button to compile the indicator.
6.  The indicator will now be available in the "Indicators" list in the cAlgo trading platform.

## Usage

To use the HalfTrend indicator, simply drag it from the "Indicators" list onto a chart. The indicator will be displayed on the chart, and you can then use it to identify the trend direction and generate entry and exit signals.

The indicator has the following parameters:

*   **Maximum Price:** The price type to use for the maximum price calculation.
*   **Minimum Price:** The price type to use for the minimum price calculation.
*   **Amplitude:** The period for the moving averages.
*   **Hide Last Bars:** The number of bars to shift the indicator.
*   **Smoothing:** The type of moving average to use.
*   **Show Arrows?:** Whether to show arrows on the chart.
*   **Show Pips?:** Whether to show pips on the chart.

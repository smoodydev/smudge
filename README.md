# Welcome to SMUDGE

## About

### A lightweight grid alternative.

SMUDGE was born out of neceessity of a simple to use grid system - without the excess styling rules of BootStrap/Materialize.

Unlike Bootstrap and Materialize, which can require a large ammount of customisation of the styling to override colors/fonts/font-sizes, SMUDGE only adds a grid system!

## Installation

### HTML LINK

Currently the easiest place to get it from is https://raw.githubusercontent.com/smoodydev/smoody/master/static/css/smudge.css.  However it will hopefully be held within a CDN over the following weeks.  Alternatively the following are applicapable.

#### Standard HTML Link

    <link rel="stylesheet" href="https://raw.githubusercontent.com/smoodydev/smudge/master/smudge.css">

#### Minified Version

    <link rel="stylesheet" href="https://raw.githubusercontent.com/smoodydev/smudge/master/smudge.min.css">

### Add to Directory

Alternatively, if you wish to add the files to your directory, feel free to use the wget method

    wget https://raw.githubusercontent.com/smoodydev/smudge/master/smudge.css

## Usage

### Standard Rules

Standard container/row/columns set is required.  Each Row is based in columns totaling 12.

Do note that as apposed to Bootstrap - By default, colums with appear in the center of the row.  Not at the beginging.  You can always modify this should you wish.

It will always be recommended that you start with your default value from your smallest targetted screensize - followed but the any additional rules.

### Breakpoints

Currently there are is the default and 5 additional Breakpoints.

| Size      | Character |Pixels |
| ----------- | ----------- |----------- |
| Standard      | c       |Default fall back       |
| Extra Small   | xsm        |375px         |
| Small   | sm        |576px        |
| Medium   | md        |768px       |
| Large   | lg        |992px        |
| Extra Large   | xlg        |1200px         |
| EXTRA-EXTRA Large   | xxlg        |1600px+         |


# birthchartSVG

Birthchart SVG is a chart generator based on Kerykeion and Opeanstro.
Like the titles says it prints out SVG file of the birthchart,
it's very easy to use.

## Use kerykeion!
This repo is here just for legacy reasons, all it functionality and more is in kerykeion, here the link:
https://github.com/g-battaglia/kerykeion 



```python
# Install:
>>> pip3 install birthchartSVG

#Import:
>>> import birthchartSVG as br

# Make the instance:
>>> kanye = br.MakeInstance("Kanye", 1977, 6, 8, 8, 45, "Atlanta")

# Set the output directory for the SVG:
>>> kanye.set_dir = "/Users/{YourName}"

#Generate the SVG:
>>> kanye.makeSVG()


SVG generated successfully!

```
![alt text](https://raw.githubusercontent.com/g-battaglia/birthchartSVG/master/birthchartSVG/data/template/sample.svg)

## Documentation

Just like in the exemple, first make an instance and then use the makeSVG() to generate the SVG chart.
The file generated has the name you inserted followed by Chart.svg

## Installation

BirtchartSVG is Python 3 package, make sure you have Python 3 installed on your system. 


## Development

You can clone this repository or download a zip file using the right side buttons. 


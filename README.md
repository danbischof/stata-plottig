# plottig

plottig provides you with new figure schemes for stata. 

## Description

New Figure Schemes for Stata: plotplain & plottig

While stata's computational capabilities have intensively increased over the last decade, the quality of its default figure schemes is still a matter of debate amongst users. Clearly some of the arguments speaking against stata figures are subject to individual taste, but others are not, such as for instance: horizontal labelling, unnecessary background tinting, missing gridlines, oversized markers. The two schemes introduced here attempt to solve the major shortcomings of stata's default figure schemes. 
Furthermore, the schemes come with 21 new colors, of which seven colors are distinguishable for people suffering from color blindness. 

## Requirements

- [git](https://github.com/coderigo/stata-git) must be installed and accessible from your command line.
 
## Usage

### Installation 
#### 1) Install git
In Stata, type:

`ssc install git`

#### 2) Install plottig
In Stata, type:

`git install https://github.com/danbischof/plottig`

#### 3) Set one of the four schemes coming with plottig as your default figure scheme
In Stata, type: 

`set scheme plottig, permanently`

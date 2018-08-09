# Best practices for wavefront dashboard development: 

### Variable
- [ ] Use the `collect` function for single dropdown in the variable
- [ ] Variable should be in `""`
- [ ] The Query should be in `""`
- [ ] Arrange the variable in the proper order

### Overview
- [ ] Size of the Overview should be `70px`
- [ ] `documentation` should not be in the hyperlink
- [ ] Remove `Edit link` form right top corner
- [ ] Add description about the integration
- [ ] add the filter variable name
- [ ] It should be in single row
- [ ] png image should be of `90px` height
- [ ] Integration and filtering variables name should be in **bold** font 

### Single Stat View Chart
- [ ] The size of the single stat view should be `70px`
- [ ] Use `white color` for the text in the single stat view 
- [ ] Select the color for single stat view from the `first row` of the `color picker`
- [ ] Add `sparkline` in single stat view, except while showing status (UP, DOWN, ACTIVE, INACTIVE etc)
- [ ] Use `Blue Color` normally
- [ ] Use font size `150%`
- [ ] Make sure failure color in red and pass cases are in green color
- [ ] If service documentation specifies the color for different status follow the same (AWS Elastic Beanstalk)

### Markdown
- [ ] Size of the markdown should be `35px`
- [ ] e.g. `#### **description**`
- [ ] Remove `Edit link` form right top corner

### Chart
- [ ] Use `camel case` for chart name, except the following words `vs, and, of, by`
- [ ] If the chart contains more than two line, do not use `Stacked Area`
- [ ] Use proper `unit` for the value
- [ ] Added description wherever necessary 
-
### Tabular Chart
- [ ] use the `taggify` function to rename the point tag if it used as column name and if it contains `_` or multiple words without space
- 
### Footer
- [ ] The size of the footer should be 50px

# Best practices for wavefront dashboard development: 

### Variable
- [ ] Use the `collect` function for single dropdown variable
- [ ] Variable should be in `""` while using with point tags
- [ ] The Query should be in `""`
- [ ] Arrange the variable in the proper order

### Overview
- [ ] Size of the Overview markdown chart should be `70px`
- [ ] Word `documentation` should not be in the hyperlink
- [ ] Remove `Edit link` form right top corner
- [ ] Add description about the integration
- [ ] Add the filter variable name
- [ ] It should be in single row
- [ ] png image should be of `90px` height
- [ ] Integration and filtering variables name should be in **bold** font 

### Single Stat View Chart
- [ ] The size of the single stat view should be `70px`
- [ ] Use `white color` for the text in the single stat view 
- [ ] Select the color for single stat view from the `first row` of the `colour picker`
- [ ] Add `sparkline` in single stat view, except while showing status (Ex: UP, DOWN, ACTIVE, INACTIVE etc)
- [ ] Use `Blue Theme` normally
- [ ] Use font size `150%`
- [ ] Make sure `failure` cases in `red` colour and `pass` cases are in `green` colour
- [ ] If service documentation specifies the color for different status follow the same (Ex: AWS Elastic Beanstalk)

### Markdown
- [ ] Size of the Markdown should be `35px`
- [ ] It should be in `Blue` colour
- [ ] e.g. `#### **description**`
- [ ] Remove `Edit link` form right top corner

### Chart
- [ ] Use `camel case` for chart name, except the following words `vs, and, of, by`, etc
- [ ] If the chart contains more than two line, do not use `Stacked Area`
- [ ] Use proper `unit` for the value
- [ ] Added description wherever necessary 

### Tabular Chart
- [ ] Use the `taggify` function to rename the point tag if it used as column name and if it contains `_` or multiple words without space

### Footer
- [ ] The size of the footer should be 50px

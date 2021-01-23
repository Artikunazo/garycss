# GARY CSS
A simple CSS framework with grid system usign CSS Grid, defined with 12 columns.

```sh
$ npm install gary-css
```

# Classes

### Containers
- .container: Limit the width to 70%.
- .container-liquid: the width will be of 100%.

### Row
- .row: create a new row. The rows has the grid defined.
    -You can use the following classes together to a .row
        - .justify-items-left or .justify-items-start: Align the items to the left.
        - .justify-items-center: Align the items to the center.
        - .justify-items-right or .justify-items-end: Align the items to the right.
        - Example: 
        ```sh 
            <div class="row justify-items-center"></div> 
        ```
    - Also, You can use the previous classes in responsive breakpoints:
        - Example: 
        ```sh 
            <div class="row 
                justify-items-center-xs 
                justify-items-left-sm 
                justify-items-left-md 
                justify-items-right-lg"></div> 
        ```
    
     
### Col
All columns must be within of a row
- .col: define a new column that It will include the 12 columns. If You add more .col, these will be stacked
- .col-1, ..., col-12: each number specify how much columns will be used, f.e. col-1 will be use 1 column, .col-5 will be use 5 columns.
- In the columns, You can use the justify-self property as class the following way:
    - .justify-self-left or justify-self-start: Align the self item to left.
    - .justify-self-center: Align the self item to center.
    - .justify-self-right or justify-self-end: Align the self item to right.
    - Example:
        ```sh 
            <div class="row">
                <div class="col justify-self-left"></div>
            </div> 
        ```
    - Also, You can use the previous classes in responsive breakpoints:
    - Example:
     ```sh 
            <div class="col 
                justify-self-left-xs 
                justify-self-right-sm 
                justify-self-center-md 
                justify-self-center-lg"></div> 
        ```

- As well as, Ypu can use align-self property as class the followinf way:
    - .align-self-start: Align the self item to left.
    - .align-self-center: Align the self item to center.
    - .align-self-end: Align the self item to right.
    - Example:
        ```sh 
            <div class="row">
                <div class="col align-self-left"></div>
            </div> 
        ```
    - Also, You can use the previous classes in responsive breakpoints:
    - Example:
     ```sh 
            <div class="col 
                align-self-left-xs 
                align-self-right-sm 
                align-self-center-md 
                align-self-center-lg"></div> 
        ```
   


### Responsive breakpoints
- You can use .xs, .sm, .md and .lg classes to use the 12 columns in a device respective:
    - .xs: extra-small devices (max width: 575.98px)
    - .sm: small devices (max width: 767.98px)
    - .md: medium devices (max width: 991.98px)
    - .lg: large devices (max width: infinite :P)

- Also, You can use and combine .xs-number, .sm-number, .md-number and .lg-number classes, example:
    ```sh
        <div class="col-6 
            xs-4 
            md-8 
            lg"></div>
    ```


## Feedback
All feedback is welcome!. You can send any feedback in https://github.com/Artikunazo/garycss/issues


Regards, Thx and Enjoy!




# ChangeLog

## [1.2.20210123.1] 2021-01-23
### Added
+ Add justify-items, justify-self, align-self classes, include with respect to the responive breakpoints

### Modified
- Update Readme.md 

## [1.1.20210122.4] 2021-01-22
### Added
+ Add text-left, items-left and item-left classes

### Modified
- Improve item-center and item-right classes
- Update Readme.md

## [1.1.20210122.3] 2021-01-22
### Removed
- Remove unnecesary code

## [1.1.20210122.1] 2021-01-22
### Added
+ Responsive breakpoints implement: xs, sm, md and lg

### Modify
- Update Readme.md


## [1.0.2021012-0.1]
### Modify
- Update Readme.md

## [1.0] - 2021-01-12
### Added
- Implement Grid System with 12 columns using CSS Grid
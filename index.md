# Gary CSS


### Installation:
```markdown

$ npm install gary-css

```

  
# Classes

  

## Containers

- .container: Limit the width div to 70%.

- .container-liquid: the width div will be of 100%.

<br />

## Rows

- .row: create a new row. The rows has display grid defined.

- You can use justify-items as classes together to a .row

	- Align the items to the left:
		-  .justify-items-left
		- .justify-items-start

	- Align the items to the center:
		- .justify-items-center
		- .justify-items-middle

	- Align the items to the right:
		- .justify-items-right
		- .justify-items-end

	- Examples:

```markdown
	<div class="row justify-items-left"></div>
	<div class="row justify-items-start"></div>
	<div class="row justify-items-center"></div>
	<div class="row justify-items-middle"></div>
	<div class="row justify-items-right"></div>
	<div class="row justify-items-end"></div>
```

  

- Also, You can use the previous classes for responsive breakpoints, adding -xs, -sm, -md or -lg, that will apply the alignment in each breakpoint:

	- Examples:

```markdown
	<div class="row
		justify-items-center-xs
		justify-items-left-sm
		justify-items-left-md
		justify-items-right-lg">
	</div>
```

- As well as, the justify-content is avaliable as classes together to a .row:
	- Align content to start:
		- .justify-content-start
		- .justify-content-left
		
	- Align content to center:
		- .justify-content-center
		- .justify-content-middle
		
	- Align content to end:
		- .justify-content-end
		- .justify-content-right
		
	- Align content with space-between:
		- .justify-content-space-between
		
	- Align content with space-around:
		- .justify-content-space-around
		
	- Align content with space-evenly:
		- .justify-content-space-evenly
		
	- Align content to stretch:
		- .justify-content-stretch
		
	- Example:
```markdown
	<div class="row justify-content-start"></div>
	<div class="row justify-content-left"></div>
	<div class="row justify-content-center"></div>
	<div class="row justify-content-middle"></div>
	<div class="row justify-content-right"></div>
	<div class="row justify-content-end"></div>
	<div class="row justify-content-space-between"></div>
	<div class="row justify-content-space-around"></div>
	<div class="row justify-content-space-evenly"></div>
	<div class="row justify-content-stretch"></div>
```

-  Also,  You can use the previous classes for responsive breakpoints, adding -xs, -sm, -md or -lg, that will apply the alignment in each breakpoint:
	- Example:
```markdown
	<div class="row justify-content-start-xs"></div>
	<div class="row justify-content-center-sm"></div>
	<div class="row justify-content-middle"></div>
	<div class="row justify-content-right"></div>
	<div class="row justify-content-end"></div>
	<div class="row justify-content-space-between"></div>
	<div class="row justify-content-space-around"></div>
	<div class="row justify-content-space-evenly"></div>
	<div class="row justify-content-stretch"></div>
```


<br />

## Columns

<b>All columns must be within of a row</b>

- .col: define a new column that It will fill the 12 columns. If You add more .col as brothers, these will be stacked.

- .col-1, .col-2, ..., col-12: each number specify how much columns the column will use, e.g. col-1 will use 1 column, .col-5 will use 5 columns.

- In the columns, You can use the justify-self class to align in inline axis (X axis) of the following way:

	- Align the self item to left. 
		- .justify-self-left
		- justify-self-start

	- Align the self item to center:
		- .justify-self-center
		- .justify-self-middle

	- Align the self item to right:
		- .justify-self-right
		- .justify-self-end 

	- Example:

```markdown
	<div class="row">
		<div class="col justify-self-middle"></div>
	</div>
```

- Also, You can use the previous classes for responsive breakpoints, adding -xs, -sm, -md or -lg, that will apply the self alignment in each breakpoint:

	- Example:

``````markdown
	<div class="col
		justify-self-left-xs
		justify-self-right-sm
		justify-self-center-md
		justify-self-center-lg">
	</div>
```

  <br />

- As well as, in the columns, You can use the align-self class to align in block axis (Y axis) of the following way:

	- Align the self item to left:
		- .align-self-start
		- .align-self-top

	- Align the self item to center:
		- .align-self-center
		- .align-self-middle

	- Align the self item to right:
		- .align-self-end
		- .align-self-bottom

	- Example:

```markdown
	<div class="row">
		<div class="col align-self-left"></div>
	</div>
```

- Also, You can use the previous classes for responsive breakpoints, adding -xs, -sm, -md or -lg, that will apply the self alignment in each breakpoint:

	- Example:

```markdown
	<div class="col
		align-self-left-xs
		align-self-right-sm
		align-self-center-md
		align-self-center-lg">
	</div>
```

  
  

### Responsive breakpoints

- You can use .xs, .sm, .md and .lg classes to use the 12 columns in a respective device:

	- <b>.xs</b>: extra-small devices (max width: 575.98px)

	- <b>.sm</b>: small devices (max width: 767.98px)

	- <b>.md</b>: medium devices (max width: 991.98px)

	- <b>.lg</b>: large devices (max width: infinite :P)

  
<br />

- Also, You can use and combine .xs-number, .sm-number, .md-number and .lg-number classes, example:

```markdown
	<div class="row">
		<div class="col-6 xs-4 md-8 lg">
		</div>
	</div>
```
<br />

## Colors

- You can use the following colors for texts:
```markdown
	<p class="text-success">Lorem ipsum dolor sit amet.</p>
    <p class="text-danger">Eos praesentium iusto commodi distinctio?</p>
    <p class="text-warning">Libero ducimus sapiente architecto ipsum.</p>
    <p class="text-muted">Sed rerum quae non beatae?</p>
    <p class="text-primary">Nostrum voluptatum ea provident veniam.</p>
    <p class="text-secondary">Doloremque doloribus velit quaerat iure!</p>
    <p class="text-black">Error eligendi neque totam nobis.</p>
    <p style="background-color: black;" class="text-white">Nostrum voluptate omnis iste praesentium.</p>
```

- For the buttons, you must add btn before a button action color:
```markdown
	<button class="btn" type="button">
        Std button
    </button>
    <button class="btn btn-success" type="button">
        Success button
    </button>
    <button class="btn btn-primary" type="button">
        Primary button
    </button>
    <button class="btn btn-warning" type="button">
        Warning button
    </button>
    <button class="btn btn-danger" type="button">
        Danger button
    </button>
    <button class="btn btn-black" type="button">
        Black button
    </button>
    <button class="btn btn-white" type="button">
        White button
    </button>
```

## Feedback

All feedback is welcome!. You can send any feedback in https://github.com/Artikunazo/garycss/issues

  
  

Regards, thx and Enjoy! :D
  
<br />

# ChangeLog

## [1.4.2111] 2021-11
### Feature
+ Add text colors
+ Add buttons colors

  
## [1.3.2103] 2021-03
### Added

+ Add justify-content classes, the respective to the responive breakpoints included: -xs, -sm, -md, -lg.
+ Add -middle to justify and align classes

  

### Modified
- Improvement justify-self classes, the respective to the responive breakpoints included: -xs, -sm, -md, -lg.
- Change align classes name with -left to -top
- Update Readme.md


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

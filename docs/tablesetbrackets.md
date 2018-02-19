# tableSetBrackets

## Purpose
> Controls which table values to put brackets around.

## Format
> tableSetBrackets(&tctl, variable)

## Input
| Option | Description |
|: ----- |: ------- |
|&tctl  | A `tableControl` structure pointer. |
|variable | String, the variable to have significance markers. Options include: "coefficients", "se", "tstat", "pval" |

## Example
```
//Declare tableControl structure
struct tableControl myTable;

//Set up brackets
tableSetBrackets(&tblCtl, "se");
```
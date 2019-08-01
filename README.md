# math-lib

## Description

An extension of the Number prototype chain to add some more functions to the Number object. More information
about what this extension adds can be found in the API section.

## API

<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

#### Table of Contents

-   [round](#round)
-   [floor](#floor)
-   [ceil](#ceil)
-   [pad](#pad)
    -   [Parameters](#parameters)
-   [degToRad](#degtorad)
-   [radToDeg](#radtodeg)
-   [toDollars](#todollars)
-   [tax](#tax)
    -   [Parameters](#parameters-1)
-   [withTax](#withtax)
    -   [Parameters](#parameters-2)
-   [interest](#interest)
    -   [Parameters](#parameters-3)
-   [mortage](#mortage)
    -   [Parameters](#parameters-4)
-   [decimalToHex](#decimaltohex)
-   [GOLDENRATIO](#goldenratio)

### round

Round a number to it's nearest whole number

Returns **[Number](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number)** the closest whole number to the original number

### floor

Round a number down to it's nearest whole number.

Returns **[Number](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number)** the closest whole number to the rounded down original number.

### ceil

Round a number up to it's closest whole number

Returns **[Number](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number)** the closest whole number to the rounded up original number.

### pad

Pad a number with a specified amount of zeros (On either the left or right side)

#### Parameters

-   `leftPadding`  
-   `rightPadding`  

Returns **[String](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String)** A padded string that indicates.

### degToRad

Convert a number from degrees to radians

Returns **[Number](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number)** The converted number in radians

### radToDeg

Convert a number from radians to degrees

Returns **[Number](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number)** the converted number in degrees.

### toDollars

Convert a number to USD.

Returns **[String](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String)** The dollar representation of the number

### tax

Return the tax amount from the number that would be applied given the rate

#### Parameters

-   `rate` **[Number](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number)** The tax rate to be applied where the rate is 0 &lt;= rate &lt;= 100
    or the rate is 0 &lt;= 100

Returns **[Number](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number)** the total tax amount of the current number multiplied by the rate

### withTax

Return this number with a specified tax rate applied to it.

#### Parameters

-   `rate` **[Number](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number)** The tax rate to be applied

Returns **[Number](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number)** a new number that has the tax of the original number applied.

### interest

Calculate the interest on a number given the interest rate, years, and optional
decimal places to round to

#### Parameters

-   `rate` **[Number](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number)** The interest rate
-   `years` **[Number](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number)** The amount of years the rate is applied to
    return {String} a string containing the total interest paid on a given number
-   `decimalPlaces`   (optional, default `2`)

### mortage

Calculate the monthly payments for a mortage given a principal (Number)

#### Parameters

-   `interestRate` **[Number](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number)** The yearly rate of interest
-   `numberOfYears` **[Number](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number)** the years remaining for the mortage

Returns **[Number](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number)** The monthly mortage payments that need to be made to pay off the mortage

### decimalToHex

convert a decimal number to hexadecimal, all thanks to the help of this
stack overflow question: <https://stackoverflow.com/questions/57803/how-to-convert-decimal-to-hexadecimal-in-javascript>

Returns **[String](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String)** The string containing the number converted to hexadecimal

### GOLDENRATIO

The golden ratio as approximated by: <https://en.wikipedia.org/wiki/Golden_ratio>

Type: [Number](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number)

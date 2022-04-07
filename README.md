# MoneyFormat
Oracle APEX plugin used to convert number to money (currency) format

APEX Version: 		19.2.0.00.18\
APEX realize date: 	2019.10.04

## AutoNumeric

The plugin used the library **autoNumeric**
https://github.com/autoNumeric/autoNumeric

LICENSE https://github.com/Ruslan-Shevyrev/apex-plugin-MoneyFormat/blob/master/LICENSE_AUTONUMERIC

## Parameters

### Decimal Character
Defines what decimal separator character is used

**Type:** 		*SelectList*
		
### Digit Group Separator	
Defines the thousand grouping separator character

**Type:** 		*SelectList11*

### Decimal Character Alternative
Allow to declare an alternative decimal separator which is automatically replaced by `decimalCharacter` when typed
This is useful for countries that use a comma ',' as the decimal character and have keyboards with numeric pads providing a period '.' as the decimal character (in France or Spain for instance)

**Type:** 		*Text*

#### Instructions
1.  Download and install plugin
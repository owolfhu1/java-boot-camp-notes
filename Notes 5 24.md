
## Pseudocode for rain inches to gallons:

INITIALIZE rainInches = 1
INITIALIZE roofLength = 1
INITIALIZE roofWidth =1
INITIALIZE galOfWater
<br>
DOWHILE roofLength && roofWidth && rainInches are not positive numbers<br>
    IF roofLength || roofWidth || rainInches are not positive numbers<br>
        DISPLAY "Invalid input, please try again."<br>
    ENDIF<br>
    DISPLAY "Please enter the length of the roof in feet: "<br>
    ASSIGN INPUT to roofLength <br>
    DISPLAY "Please enter the width of the roof in feet: "<br>
    ASSIGN INPUT to roofLength <br>
    DISPLAY "Please enter inches of rainfall: "<br>
    ASSIGN INPUT to rainInches <br>
EMDWHILE<br>
<br>
ASSIGN roofLength * roofWidth * 12 / 213 to galOfWater <br>
<br>
DISPLAY "A roof $roofLength feet by $roofWidth feet that gets $roofArea inchs of rainfall, will produce $galOfWater gallons of water."<br>
<br>



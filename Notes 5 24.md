
## Pseudocode for rain inches to gallons:

INITIALIZE rainInches = 1
INITIALIZE roofLength = 1
INITIALIZE roofWidth =1
INITIALIZE galOfWater
<br>
DOWHILE roofLength && roofWidth && rainInches are not positive numbers<br>
&nbsp;&nbsp;    IF roofLength || roofWidth || rainInches are not positive numbers<br>
&nbsp;&nbsp;&nbsp;&nbsp;        DISPLAY "Invalid input, please try again."<br>
&nbsp;&nbsp;    ENDIF<br>
&nbsp;&nbsp;    DISPLAY "Please enter the length of the roof in feet: "<br>
&nbsp;&nbsp;    ASSIGN INPUT to roofLength <br>
&nbsp;&nbsp;    DISPLAY "Please enter the width of the roof in feet: "<br>
&nbsp;&nbsp;    ASSIGN INPUT to roofLength <br>
&nbsp;&nbsp;    DISPLAY "Please enter inches of rainfall: "<br>
&nbsp;&nbsp;    ASSIGN INPUT to rainInches <br>
EMDWHILE<br>
<br>
ASSIGN roofLength * roofWidth * 12 / 213 to galOfWater <br>
<br>
DISPLAY "A roof $roofLength feet by $roofWidth feet that gets $roofArea inchs of rainfall, will produce $galOfWater gallons of water."<br>
<br>



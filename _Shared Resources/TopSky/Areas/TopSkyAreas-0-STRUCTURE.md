// ##################################################################
//                 VATSSA | FIR FBQE | TopSky | Areas
// ##################################################################

// Version v0.1
// Update Date 28/06/2022


// ##################################################################
//                 #0 CATEGORIES v0.1
// ##################################################################

// Active
CATEGORYDEF:PROHIBITED:8:7:50:8:7:10:0:1:0:1:1
CATEGORYDEF:RESTRICTED:4:4:20:4:4:10:0:0:2:0
CATEGORYDEF:DANGER:6:6:20:6:6:10:0:0:0:1:0

// ##################################################################
//                 #1 NOTAMS v0.1
// ##################################################################

// DN NOTAM A0136/22 - GND/FL150    
AREA:T:A0136/22
CATEGORY:RESTRICTED
ACTIVE:220404:220604:0:1530:1530
LIMITS:0:150
N013.24.45.770:E006.35.24.890


// ##################################################################
//                 #2 PROHIBITED v0.1
// ##################################################################

// DN Prohibited Area P1 Lagos/Murtala Muhammed - GND/A050 
AREA:T:DN P1
CATEGORY:PROHIBITED
ACTIVE:1
USERTEXT:Lagos/Murtala Muhammed - GND/A050
//LABEL:N006.27.03.960:E003.17.57.000:DN P1
LIMITS:0:050
N006.27.03.960 E003.17.57.000


// ##################################################################
//                 #3 RESTRICTED v0.1
// ##################################################################

// DN Restricted Area R1 - GND/FL100    
AREA:T:DN R1
CATEGORY:RESTRICTED
ACTIVE:1
LIMITS:0:100
N006.30.01.879 E003.23.57.000


// ##################################################################
//                 #4 DANGER v0.1
// ##################################################################

// DN Danger Area Air Force Training Area 1 
AREA:T:DN AFTA 1
CATEGORY:DANGER
ACTIVE:1
LIMITS:0:400
N008.34.00.000 E009.05.00.000


// ##################################################################
//                 THE END
// ##################################################################

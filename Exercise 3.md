int x = 1

Real y = 3.4



1  3.4

0  0

1  3.4



Module main()

&#x09;DECLARE Integer x = 1

&#x09;DECLARE Real y = 3.4

&#x09;DISPLAY x, " ", y

&#x09;CALL changeUs(x, y)

&#x09;DISPLAY x, "  ", y

END MODULE



Module changeUs(Integer a AS REF, Real b AS REF)

&#x09;set a = 0

&#x09;set b = 0

&#x09;DISPLAY a, " ", b

END MODULE



Module main()

&#x09;DECLARE Real mileage

&#x09;CALL getMileage(mileage)

&#x09;DISPLAY "You've driven a total of ", mileage, " miles " 

END MODULE



Module getMileage(Real mileage AS REF)

&#x09;DISPLAY "Enter Value for mileage"

&#x09;INPUT mileage

END MODULE



Procedure Main()

&#x09;CALL guessColor()

ENDPROCEDURE



Procedure guessColor()

&#x09;DISPLAY "Enter a number"

&#x09;Input number



&#x09;IF number >= 0 THEN 

&#x09;	DISPLAY "BLUE"

&#x09;ELSE IF number > 10 THEN

&#x09;	DISPLAY "RED"

&#x09;ELSE IF number > 20 AND number <= 30 THEN

&#x09;	DISPLAY "GREEN"

&#x09;ELSE

&#x09;	DISPLAY "Not a correct color option"

&#x09;ENDIF



END PROCEDURE





Procedure Main()

&#x09;SET Integer num = numDifference() 

&#x09;DISPLAY num

ENDPROCEDURE





FUNCTION numDifference()

&#x09;DECLARE numSquare AS INTEGER

&#x09;DECLARE numCube AS INTEGER

&#x09;DECLARE num AS INTEGER



&#x09;INPUT num;



&#x09;SET numSquare = num \* num

&#x09;SET numCube = num \* num \* num;

&#x09;

&#x09;return numCube - numSquare

ENDFUNCTION





Procedure MAIN



&#x09;DECLARE length AS INTEGER

&#x09;DECLARE width AS INTEGER

&#x09;DECLARE area AS INTEGER

&#x09;DECLARE price\_per\_sqr\_foot AS INTEGER

&#x09;DECLARE area\_foot\_past\_one\_hundred AS INTEGER

&#x09;DECLARE normal\_rate AS INTEGER

&#x09;DECLARE double\_rate AS INTEGER



&#x09;DISPLAY "Please enter length and width of carpet (feet) and price per sqr foot"

&#x09;INPUT length

&#x09;INPUT width

&#x09;INPUT price\_per\_sqr\_foot



&#x09;SET area = length \* width

&#x09;SET area\_foot\_past\_one\_hundred = area - 100



&#x09;SET normal\_rate = 100 \* price\_per\_sqr\_foot

&#x09;SET double\_rate = area\_foot\_past\_one\_hundred\* (price\_per\_square\_foot \* 2)



&#x09;DISPLAY "Area is: " area

&#x09;DISPLAY "Cost of cleaning is: " normal\_rate + double\_rate



&#x09;

ENDPROCEDURE



Procedure MAIN



&#x09;DECLARE STRING\[] students = 587



&#x09;DECLARE honor\_points AS INTEGER;

&#x09;DECLARE credits AS INTEGER

&#x09;DECLARE average AS INTEGER;



&#x09;SET length TO size(students) 

&#x09;SET counter to 0



&#x09;FOR counter FROM 0 TO length

&#x09;	INPUT honor\_points

&#x09;	INPUT credits

&#x09;	average = CALL getPointAverage(honor\_points, credits)

&#x09;	DISPLAY average;

&#x09;ENDFOR

&#x09;	



Procedure getPointAverage(INTEGER honor\_points, INTEGER credits)

&#x09;

&#x09; return honor\_points / credits

ENDPROCEDURE







T: a = a + 1

&#x20;   b = b- 1

&#x20;   if b > 0 then goto T

U: a = a + 1

&#x20;   c = c - 1

&#x20;   if c > 0 then goto U

&#x20;   x = a

&#x20;   halt







&#x09;




SET number TO 3
SEND "Enter guess" TO DISPLAY
RECIEVE Guess FROM KEYBOARD
IF guess > 10
  SEND "guess too high" TO DISPLAY
ELSE
  IF Guess = Number
    SEND "Correct!" TO DISPLAY
ELSE
    SEND "Bad luck! The correct number is" + Number
 END IF
END IF

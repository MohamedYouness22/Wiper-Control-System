# Wiper-Control-System

This is Model-Based-Design project implemented on Simulink.
the project objective is to design a wiper control system 
having 3 inputs:
1-WiperMode: wiper mode of operation
  • 0: off
  • 1:Auto
  • 2:Low speed
  • 3: High speed
2-RainsnsrError: Rain sensor error
  • 0:normal, no error
  • 1:error
3-WiperspeedReq: Required speed level in case of automatic mode [0 1 2 3 4 5 6 7]

and 2 outputs:
1-WiperDutyCyc:PWM Command to the wiper motor
2-WiperActv: Indicates if the wiper motor is running
  • 0: Stop (not avtivated)
  • 1: Running (avtivated)

Model:






# Wiper-Control-System

This is Model-Based-Design project implemented on Simulink.

the project objective is to design a wiper control system 

having 3 inputs:
- WiperMode: wiper mode of operation
  - 0: off
  - 1:Auto
  - 2:Low speed
  - 3: High speed
- RainsnsrError: Rain sensor error
  - 0:normal, no error
  - 1:error
- WiperspeedReq: Required speed level in case of automatic mode [0 1 2 3 4 5 6 7]

and 2 outputs:
- WiperDutyCyc:PWM Command to the wiper motor
- WiperActv: Indicates if the wiper motor is running
  - 0: Stop (not avtivated)
  - 1: Running (avtivated)

Model:
![1](https://github.com/MohamedYouness22/Wiper-Control-System/assets/71296059/813832b5-6035-4332-ae18-a0887577f7ba)
![2](https://github.com/MohamedYouness22/Wiper-Control-System/assets/71296059/34237a83-a532-42aa-8d32-a8717923990b)

output:
![3](https://github.com/MohamedYouness22/Wiper-Control-System/assets/71296059/5744f764-bdb5-4d15-9664-7255a9db23e7)






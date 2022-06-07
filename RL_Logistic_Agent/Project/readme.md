최종 결과
---

- Test시 설정사항
    - 리워드 : Item(10), 장애물(-10), Move(0.1)
    - Max Step : 90
- 평가 지표
    - TimeSteps : 목적 아이템으로 이동한 총 step수
    - Avr Reward : 에피소드당 매 item을 찾고 얻은 보상의 합
    - Finish Rate : 전체 에피소드수에 대해 아이템을 정확히 모두 찾고 시작지점으로 돌아온 비율
- **최종 결과 - Episode :1225 , 총 Steps : 42611, Avr Reward:78.86 Finish Rate:0.9796**

- Test log
```
Episode:1209  Timestep:42053  Avr Reward:78.85   Finish Rate:0.9793 reward:80  Picked:['D-10', 'F-2', 'I-4', 'K-3', 'M-3', 'N-1', 'O-2', 'S-9'] Missed:[] 
Episode:1210  Timestep:42087  Avr Reward:78.85   Finish Rate:0.9794 reward:80  Picked:['B-8', 'C-2', 'D-2', 'G-3', 'I-3', 'K-3', 'Q-6', 'S-7'] Missed:[] 
Episode:1211  Timestep:42121  Avr Reward:78.85   Finish Rate:0.9794 reward:80  Picked:['A-7', 'D-4', 'F-2', 'I-4', 'J-2', 'M-4', 'N-1', 'S-10'] Missed:[] 
Episode:1212  Timestep:42157  Avr Reward:78.85   Finish Rate:0.9794 reward:80  Picked:['E-12', 'G-3', 'I-3', 'K-3', 'N-3', 'P-3', 'Q-2', 'S-7'] Missed:[] 
Episode:1213  Timestep:42191  Avr Reward:78.85   Finish Rate:0.9794 reward:80  Picked:['D-10', 'F-2', 'M-8', 'N-1', 'O-2', 'P-2', 'Q-2', 'S-7'] Missed:[] 
Episode:1214  Timestep:42227  Avr Reward:78.85   Finish Rate:0.9794 reward:80  Picked:['B-8', 'D-3', 'F-2', 'G-2', 'H-2', 'M-6', 'P-5', 'S-8'] Missed:[] 
Episode:1215  Timestep:42263  Avr Reward:78.85   Finish Rate:0.9794 reward:80  Picked:['B-8', 'C-2', 'E-4', 'F-2', 'G-2', 'K-5', 'O-4', 'S-9'] Missed:[] 
Episode:1216  Timestep:42297  Avr Reward:78.85   Finish Rate:0.9795 reward:80  Picked:['C-9', 'D-2', 'F-2', 'H-3', 'I-2', 'J-2', 'P-6', 'S-8'] Missed:[] 
Episode:1217  Timestep:42333  Avr Reward:78.85   Finish Rate:0.9795 reward:80  Picked:['B-8', 'C-2', 'I-6', 'J-2', 'K-2', 'M-3', 'Q-6', 'S-7'] Missed:[] 
Episode:1218  Timestep:42367  Avr Reward:78.85   Finish Rate:0.9795 reward:80  Picked:['A-7', 'G-6', 'H-2', 'L-5', 'N-2', 'O-2', 'P-2', 'S-8'] Missed:[] 
Episode:1219  Timestep:42403  Avr Reward:78.85   Finish Rate:0.9795 reward:80  Picked:['B-8', 'C-2', 'E-4', 'F-2', 'I-4', 'L-4', 'Q-5', 'S-7'] Missed:[] 
Episode:1220  Timestep:42437  Avr Reward:78.86   Finish Rate:0.9795 reward:80  Picked:['B-8', 'D-3', 'K-7', 'L-2', 'N-2', 'O-2', 'P-2', 'S-8'] Missed:[] 
Episode:1221  Timestep:42471  Avr Reward:78.86   Finish Rate:0.9795 reward:80  Picked:['C-9', 'G-4', 'J-4', 'K-2', 'L-2', 'O-3', 'P-2', 'S-8'] Missed:[] 
Episode:1222  Timestep:42507  Avr Reward:78.86   Finish Rate:0.9796 reward:80  Picked:['C-9', 'G-4', 'I-3', 'J-2', 'L-3', 'M-2', 'O-4', 'S-9'] Missed:[] 
Episode:1223  Timestep:42543  Avr Reward:78.86   Finish Rate:0.9796 reward:80  Picked:['E-12', 'F-2', 'H-3', 'J-3', 'K-2', 'L-2', 'N-2', 'S-10'] Missed:[] 
Episode:1224  Timestep:42577  Avr Reward:78.86   Finish Rate:0.9796 reward:80  Picked:['A-7', 'B-2', 'D-3', 'G-3', 'H-2', 'N-6', 'O-2', 'S-9'] Missed:[] 
Episode:1225  Timestep:42611  Avr Reward:78.86   Finish Rate:0.9796 reward:80  Picked:['A-7', 'D-4', 'G-3', 'H-2', 'L-5', 'M-2', 'N-1', 'S-10'] Missed:[] 

```

Instructions: run the below commands in the terminal to train the model. 

```bash
conda create -n pong python=3.9  

conda activate pong          

pip install pygame==2.1.0  

pip install numpy gym torch     

python train.py  
```


run test.py to test the model. Modify bottommost lines to modify tester behavior.


run play.py to play against the model. Modify bottommost lines to modify model iteration 
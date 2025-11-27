# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:
<img width="381" height="742" alt="image" src="https://github.com/user-attachments/assets/398ded19-a78f-46b8-b8ea-2f2730d6b96d" />
<img width="315" height="412" alt="image" src="https://github.com/user-attachments/assets/c7dd4151-66b3-4a0a-b573-f1f5ff834b19" />


## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.

## Program:
num=[1]
den=[1 15 50 0]
sys=tf(num,den)
rlocus(sys)
[k poles]=rlocfind(sys)

## Output:
<img width="695" height="528" alt="Screenshot 2025-11-17 114112" src="https://github.com/user-attachments/assets/17b18090-b0e9-4063-8d59-15407c4779a0" />


## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is ------------

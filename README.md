# Conjugate_Gradient_for_Dereverberations

Implemention of the conjugate gradient method in Python to recover a sound signal 
Inside the Jupyter Notebook, you will see the following in order

1. Acoustical environment is simulated using the pyroomacoustics module.
2. Using one of the room impulse response (RIR) obatined from the simulation, a convolution is done on the sound signal imported from the .wav file to simulate the effect of a reverberant room.
3. A Gaussian noise of which the SNR is specified by the user is then added to the already corrupted sound signal.
4. Implement the conjugate gradient method to recover the original signal. The iteration number can be specified by the user to compare the performance.

5. A visualization of the original signal, the corrupted signal, the recovered signal and the absolute error is presented.

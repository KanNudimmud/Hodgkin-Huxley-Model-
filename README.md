# Hodgkin-Huxley-Model-
Hodgkin&amp;Huxley Model in MATLAB and Simulink.

It is a first model of a cell. Huxley and Hodgkin took giant axon from a squid and they have explained ion channels mechanism![image](https://github.com/KanNudimmud/Hodgkin-Huxley-Model-/assets/75501882/837ab460-b237-45ed-ae1c-c110d573f2ad)
<img width="282" alt="image" src="https://github.com/KanNudimmud/Hodgkin-Huxley-Model-/assets/75501882/43afdc49-e4a2-4c93-a5c7-7e6db20d2691">



Assuming cell as an electrical system before a biological is the fundamental part of modelling the cell membrane.![image](https://github.com/KanNudimmud/Hodgkin-Huxley-Model-/assets/75501882/17f88dd0-5c2d-4ce1-a8d1-baeac417bd9a)


<img width="354" alt="image" src="https://github.com/KanNudimmud/Hodgkin-Huxley-Model-/assets/75501882/5535f66b-a4c1-4dd2-8108-b8ddc0cea100">
Figure. Circuit representation ![image](https://github.com/KanNudimmud/Hodgkin-Huxley-Model-/assets/75501882/05290d74-4b2b-45ec-bc2b-912d2f7181c1)

Hodgkin and Huxley are found and formulated this model after series of voltage clamp experiments by altering sodium and potassium concentrations![image](https://github.com/KanNudimmud/Hodgkin-Huxley-Model-/assets/75501882/42b9e32d-0409-4879-af3e-592b54ca7936)

C_m (dV/dt)=I-I_m
=I-g_Na m^3 h(V-V_Na )-g_K n^4 (V-V_K )-g_L (V-V_L )

                                                            Leakage Current
dm/dt=∝_m (1-m)-β_m m
dn/dt=∝_n (1-n)-β_n n
dh/dt=∝_h (1-h)-β_h h
m,n,h = state variables,  g = channel conductivity, α,β = rate coefficients
![image](https://github.com/KanNudimmud/Hodgkin-Huxley-Model-/assets/75501882/b46cca1b-5f9b-4754-9ad6-c2a2b4d4143b)

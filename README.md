# Hodgkin-Huxley-Model-
Hodgkin&amp;Huxley Model in MATLAB and Simulink.

It is a first model of a cell. Huxley and Hodgkin took giant axon from a squid and they have explained ion channels mechanism.

<img width="282" alt="image" src="https://github.com/KanNudimmud/Hodgkin-Huxley-Model-/assets/75501882/43afdc49-e4a2-4c93-a5c7-7e6db20d2691">

Assuming cell as an electrical system before a biological is the fundamental part of modelling the cell membrane.

<img width="354" alt="image" src="https://github.com/KanNudimmud/Hodgkin-Huxley-Model-/assets/75501882/5535f66b-a4c1-4dd2-8108-b8ddc0cea100">

Figure. Circuit representation

Hodgkin and Huxley are found and formulated this model after series of voltage clamp experiments by altering sodium and potassium concentrations.

$$\ C_m * (dV/dt) = I - I_m $$

$$\ I_m = g_Na * m^3 * h * (V - V_Na) - g_K * n^4 * (V - V_K) - g_L * (V - V_L) $$

Leakage Current:
$$\ dm/dt = α_m * (1 - m) - β_m * m $$
$$\ dn/dt = α_n * (1 - n) - β_n * n $$
$$\ dh/dt = α_h * (1 - h) - β_h * h $$

Variables:
m, n, h: State variables

g: Channel conductivity

α, β : Rate coefficients

C_m : Membrane capacitance

I: Input current

V: Membrane potential

I_m : Membrane current

V_Na : Sodium equilibrium potential

V_K : Potassium equilibrium potential

V_L : Leakage equilibrium potential


Model:

<img width="454" alt="image" src="https://github.com/KanNudimmud/Hodgkin-Huxley-Model-/assets/75501882/c7f75276-b514-447a-9628-21c146fe1bcd">



Output: 

<img width="453" alt="image" src="https://github.com/KanNudimmud/Hodgkin-Huxley-Model-/assets/75501882/2d50e813-8c7f-4ec0-88a9-e6ebadcb3db9">


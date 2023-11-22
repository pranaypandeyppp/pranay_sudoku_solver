Certainly! Let's provide a complete step-by-step procedure for each condition:

### (a) Rotor Terminals Short-Circuited:

1. **Calculate Slip (\(s\)):**
   \[ s = \frac{{N_s - N_r}}{{N_s}} \]
   \[ N_r = (1 - s) \cdot N_s \]
   \[ N_r = (1 - 0.035) \cdot 1500 \, \text{rpm} \]
   \[ N_r \approx 1445.5 \, \text{rpm} \]

2. **Calculate Stator Current (\(I_{\text{stator}}\)):**
   \[ I_{\text{stator}} = \frac{{P_{\text{rated}}}}{{\sqrt{3} \cdot V_{\text{rated}}}} \]
   \[ I_{\text{stator}} \approx \frac{{75 \, \text{kW}}}{{\sqrt{3} \cdot 400 \, \text{V}}} \]
   \[ I_{\text{stator}} \approx 108.972 \, \text{A} \]

3. **Calculate Rotor Current (\(I_{\text{rotor}}\)):**
   \[ I_{\text{rotor}} = \frac{{I_{\text{stator}}}}{{s}} \]
   \[ I_{\text{rotor}} \approx \frac{{108.972 \, \text{A}}}{{0.035}} \]
   \[ I_{\text{rotor}} \approx 3113.2 \, \text{A} \]

4. **Calculate Stator Power (\(P_{\text{stator}}\)):**
   \[ P_{\text{stator}} = \sqrt{3} \cdot V_{\text{rated}} \cdot I_{\text{stator}} \cdot \cos(\phi_{\text{stator}}) \]
   \[ P_{\text{stator}} \approx \sqrt{3} \cdot 400 \, \text{V} \cdot 108.972 \, \text{A} \cdot 1 \]
   \[ P_{\text{stator}} \approx 74663.11 \, \text{W} \]

5. **Calculate Rotor Copper Losses (\(P_{\text{rotor copper}}\)):**
   \[ P_{\text{rotor copper}} = \sqrt{3} \cdot I_{\text{rotor}}^2 \cdot R_s \]
   \[ P_{\text{rotor copper}} \approx \sqrt{3} \cdot (3113.2 \, \text{A})^2 \cdot 0.075 \, \Omega \]
   \[ P_{\text{rotor copper}} \approx 6504.28 \, \text{W} \]

6. **Calculate Total Power (\(P_{\text{total}})\):**
   \[ P_{\text{total}} = P_{\text{stator}} + P_{\text{rotor copper}} \]
   \[ P_{\text{total}} \approx 74663.11 \, \text{W} + 6504.28 \, \text{W} \]
   \[ P_{\text{total}} \approx 81167.39 \, \text{W} \]

### (b) 1.15 V per Phase Injected into the Rotor, In Phase with the Supply:

1. **Calculate New Rotor Current (\(I_{\text{rotor}}'\)):**
   \[ I_{\text{rotor}}' = \frac{{V_{\text{injected}}}}{{\sqrt{3} \cdot X}} \]
   \[ I_{\text{rotor}}' = \frac{{1.15 \, \text{V}}}{{\sqrt{3} \cdot 0.12 \, \Omega}} \]
   \[ I_{\text{rotor}}' \approx 6.64 \, \text{A} \]

2. **Calculate Additional Power (\(P_{\text{additional}})\):**
   \[ P_{\text{additional}} = \sqrt{3} \cdot V_{\text{injected}} \cdot I_{\text{rotor}}' \cdot \cos(\phi_{\text{injected}}) \]
   \[ P_{\text{additional}} \approx \sqrt{3} \cdot 1.15 \, \text{V} \cdot 6.64 \, \text{A} \cdot 1 \]
   \[ P_{\text{additional}} \approx 11.54 \, \text{W} \]

3. **Calculate Total Power (\(P_{\text{total}})\):**
   \[ P_{\text{total}} = P_{\text{stator}} + P_{\text{additional}} \]
   \[ P_{\text{total}} \approx 74663.11 \, \text{W} + 11.54 \, \text{W} \]
   \[ P_{\text{total}} \approx 74674.65 \, \text{W} \]

### (c) 1.15 V per Phase Injected into the Rotor and Phase Shifted by 180°:

1. **Calculate New Rotor Current (\(I_{\text{rotor}}''\)):**
   \[ I_{\text{rotor}}'' = \frac{{V_{\text{injected}}}}{{\sqrt{3} \cdot X}} \]
   \[ I_{\text{rotor}}'' = \frac{{1.15 \, \text{V}}}{{\sqrt{3} \cdot 0.12 \, \Omega}} \]
   \[ I_{\text{rotor}}'' \approx 6.64 \, \text{A} \]

2. **Calculate Additional Power (\(P_{\text{additional}})\) with the Phase Shift:**
   \[ P_{\text{additional}} = \sqrt{3} \cdot V_{\text{injected}} \cdot I_{\text{rotor}}'' \cdot \cos(\phi_{\text{injected}} + 180^\circ) \]
   \[ P_{\text{additional}} \approx \sqrt{3} \cdot 1.15 \, \text{V} \cdot 6.64 \, \text{A} \cdot (-1) \]
   \[ P_{\text{additional}} \approx -11.54 \, \text{W} \]

3. **Calculate Total Power (\(P_{\text{total}})\):**
   \[ P_{\text{total}} = P_{\text{stator}} + P_{\text{additional}} \]
   \[ P_{\text{total}} \

approx 74663.11 \, \text{W} - 11.54 \, \text{W} \]
   \[ P_{\text{total}} \approx 74651.57 \, \text{W} \]

These steps provide a detailed procedure for each condition. If you have any further questions or if there's anything else I can assist you with, feel free to let me know!

Download Link: https://assignmentchef.com/product/solved-uwee538-homework-5-difference-amplifier-analysis
<br>
<strong> Difference amplifier </strong>

A difference amplifier is driven by a sensor with source impedance <em>R<sub>s</sub></em>. Let <em>R<sub>f</sub></em> = 10k and <em>R<sub>i</sub></em> = 100. Assume ideal opamp behavior.

<ol>

 <li>Derive an expression and determine a value for the DC differential input impedance <em>Z<sub>in</sub></em> of the amplifier. Determine the source impedance <em>R<sub>s</sub></em> that results in a maximum of 0.1% attenuation of the input voltage.</li>

 <li>Simulate the amplifier in Ltspice using the UniversalOpamp2 component (default parameters). Plot <em>Z<sub>in</sub></em> up to 10MHz using AC analysis to show how it varies as a function of opamp gain.</li>

</ol>

<h1>Problem 2: Instrumentation amplifier analysis</h1>

<strong>Figure 2. Instrumentation amplifier  </strong>

Assume the above opamps have a DC gain of 120dB and an <em>f<sub>T</sub></em> of 1MHz. Nominal resistance values are <em>R<sub>fp</sub></em>

= <em>R<sub>fm</sub></em> = 4.95k, <em>R<sub>G</sub></em> = 100, and <em>R<sub>1</sub></em> = <em>R<sub>2</sub></em> = 10k, all with 0.1% tolerance.

<ol>

 <li>Determine the differential DC gain of the amplifier and the closed-loop bandwidth. <em>Ignore resistor mismatch.</em></li>

 <li> Based on the value of <em>f<sub>T</sub></em>, what is the closed-loop gain error at 100Hz? <em>Ignore mismatch. </em></li>

 <li> Including the effect of resistor mismatch, what are the CMRR and the worst-case DC gain error? <em>Assume infinite opamp open-loop gain.</em></li>

 <li> Assume <em>U<sub>1</sub></em> and <em>U<sub>2</sub></em> have min/max input offset voltages of 100V but are otherwise identical. What is the maximum allowable offset of <em>U<sub>3</sub></em> to achieve a <em>worst-case</em> <em>input-referred</em> <em>offset</em> (the offset at <em>V<sub>out</sub></em> divided by the differential gain) of 250V? <em>Ignore resistor mismatch.</em></li>

 <li> Simulate the instrumentation amplifier in Ltspice using the UniversalOpamp2 component with appropriate Avol, GBW, and Vos values. Provide the following in your submission:

  <ol>

   <li>Image of your schematic showing the DC operating point (DC voltages at all nodes). Use the worst-case mismatch condition for the resistors. How much is the offset affected by resistor mismatch?</li>

   <li>Plot showing the closed loop gain error at 100Hz using WC analysis. You can do this by selecting ‘list’ for the sweep type under AC analysis. Note that you need to run 128 iterations (2<sup>7</sup>, where 7 is the number of resistors) to cover all mismatch combinations. Compare the contributions to gain error from finite opamp gain and resistor mismatch (i.e. which effect is more significant?).</li>

   <li>Bode plots demonstrating closed-loop differential gain/phase and closed-loop commonmode gain/phase. For common-mode gain you should use the worst-case mismatch condition for the resistors.</li>

  </ol></li>

</ol>
# NMOS-Characteristics-using-Cadence# NMOS Characterization Using Cadence Virtuoso

This project demonstrates the DC characterization of an NMOS transistor using **Cadence Virtuoso** and **Spectre Simulator**.

## Objective

To obtain and analyze:

- **Drain current ID vs Drain-to-Source Voltage VDS characteristics for different VGS values.
- **Drain current ID vs Gate-to-Source Voltage VGS** characteristics for different VDS values.

## Tools Used

- Cadence Virtuoso
- Spectre Simulator
- NMOS device
- DC Sweep Analysis

## 1. ID vs VDS

The drain voltage VDS is swept while VGS is varied.

The graph shows the typical NMOS output characteristics. As VGS increases, the drain current increases.

The following operating regions can be observed:

- Cutoff region
- Linear/Triode region
- Saturation region
- ![NMOS ID-VDS Characteristics](Screenshot%202026-08-09%20175931.png)
## 2. ID vs VGS

The gate voltage VGS is swept for different values of VDS.

The transistor remains approximately in cutoff below the threshold voltage VTH. Above VTH, the drain current increases with VGS.


## Simulation Setup

### Output Characteristics

- Sweep variable: VDS
- Parameter: VGS
- VGS values: 0 V to 1.8 V
- VDS sweep: 0 V to 1.8 V

### Transfer Characteristics

- Sweep variable: VGS
- Parameter: VDS
- VDS values: 0 V to 1.8 V
- VGS sweep: 0 V to 1.8 V

## Observations

- Increasing VGS increases the NMOS drain current.
- For sufficiently high VDS, the transistor enters saturation.
- The output characteristics demonstrate the dependence of ID on both VGS and VDS.
- The curves can be used to estimate parameters such as threshold voltage and transconductance.

## Conclusion

The NMOS transistor was successfully characterized using Cadence Virtuoso. The simulated ID-VDS and ID-VGS characteristics agree with the expected qualitative behavior of an NMOS transistor.

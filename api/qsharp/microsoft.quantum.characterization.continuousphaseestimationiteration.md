---
uid: Microsoft.Quantum.Characterization.ContinuousPhaseEstimationIteration
title: ContinuousPhaseEstimationIteration operation
ms.date: 11/2/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Characterization
qsharp.name: ContinuousPhaseEstimationIteration
qsharp.summary: >-
  Performs a single iteration of an iterative (classically-controlled) phase
  estimation algorithm using arbitrary real powers of a unitary oracle.
---

# ContinuousPhaseEstimationIteration operation

Namespace: [Microsoft.Quantum.Characterization](xref:Microsoft.Quantum.Characterization)

Package: [](https://nuget.org/packages/)


Performs a single iteration of an iterative (classically-controlled) phase

```qsharp
operation ContinuousPhaseEstimationIteration (oracle : Microsoft.Quantum.Oracles.ContinuousOracle, time : Double, theta : Double, targetState : Qubit[], controlQubit : Qubit) : Unit
```


## Input

### oracle : [ContinuousOracle](xref:Microsoft.Quantum.Oracles.ContinuousOracle)

Operation acting on a double $t$ and a register,


### time : [Double](xref:microsoft.quantum.lang-ref.double)

Number of times to apply the given unitary oracle.


### theta : [Double](xref:microsoft.quantum.lang-ref.double)

Angle by which to invert the phase on the control qubit before


### targetState : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[]

Register of state acted upon by the given unitary oracle.


### controlQubit : [Qubit](xref:microsoft.quantum.lang-ref.qubit)





## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)

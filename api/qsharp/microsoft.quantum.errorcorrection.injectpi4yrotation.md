---
uid: Microsoft.Quantum.ErrorCorrection.InjectPi4YRotation
title: InjectPi4YRotation operation
ms.date: 11/2/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.ErrorCorrection
qsharp.name: InjectPi4YRotation
qsharp.summary: Rotates a single qubit by π/4 about the Y-axis.
---

# InjectPi4YRotation operation

Namespace: [Microsoft.Quantum.ErrorCorrection](xref:Microsoft.Quantum.ErrorCorrection)

Package: [](https://nuget.org/packages/)


Rotates a single qubit by π/4 about the Y-axis.

```qsharp
operation InjectPi4YRotation (data : Qubit, magic : Qubit) : Unit
```


## Description

Performs a π/4 rotation about `Y`.

## Input

### data : [Qubit](xref:microsoft.quantum.lang-ref.qubit)

A qubit to be rotated about $Y$ by $\pi / 4$.


### magic : [Qubit](xref:microsoft.quantum.lang-ref.qubit)

A qubit initially in the magic state. Following application



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Remarks

The following are equivalent:
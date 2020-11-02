---
uid: Microsoft.Quantum.Characterization.EstimateFrequency
title: EstimateFrequency operation
ms.date: 11/2/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Characterization
qsharp.name: EstimateFrequency
qsharp.summary: >-
  Given a preparation and measurement, estimates the frequency
  with which that measurement succeeds (returns `Zero`) by
  performing a given number of trials.
---

# EstimateFrequency operation

Namespace: [Microsoft.Quantum.Characterization](xref:Microsoft.Quantum.Characterization)

Package: [](https://nuget.org/packages/)


Given a preparation and measurement, estimates the frequency

```qsharp
operation EstimateFrequency (preparation : (Qubit[] => Unit), measurement : (Qubit[] => Result), nQubits : Int, nMeasurements : Int) : Double
```


## Input

### preparation : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[] => [Unit](xref:microsoft.quantum.lang-ref.unit) 

An operation $P$ that prepares a given state $\rho$ on


### measurement : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[] => __invalid<Result>__ 

An operation $M$ representing the measurement of interest.


### nQubits : [Int](xref:microsoft.quantum.lang-ref.int)

The number of qubits on which the preparation and measurement


### nMeasurements : [Int](xref:microsoft.quantum.lang-ref.int)

The number of times that the measurement should be performed



## Output : [Double](xref:microsoft.quantum.lang-ref.double)

An estimate $\hat{p}$ of the frequency with which
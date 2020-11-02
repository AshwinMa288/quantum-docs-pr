---
uid: Microsoft.Quantum.Synthesis.ApplyXControlledOnTruthTable
title: ApplyXControlledOnTruthTable operation
ms.date: 11/2/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Synthesis
qsharp.name: ApplyXControlledOnTruthTable
qsharp.summary: >-
  Applies the @"microsoft.quantum.intrinsic.x" operation on `target`, if the Boolean function `func` evaluates
  to true for the classical assignment in `controlRegister`.
---

# ApplyXControlledOnTruthTable operation

Namespace: [Microsoft.Quantum.Synthesis](xref:Microsoft.Quantum.Synthesis)

Package: [](https://nuget.org/packages/)


Applies the @"microsoft.quantum.intrinsic.x" operation on `target`, if the Boolean function `func` evaluates

```qsharp
operation ApplyXControlledOnTruthTable (func : BigInt, controlRegister : Qubit[], target : Qubit) : Unit
```


## Description

The operation implements the unitary operation

## Input

### func : [BigInt](xref:microsoft.quantum.lang-ref.bigint)

Boolean truth table represented as big integer


### controlRegister : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[]

Register of control qubits


### target : [Qubit](xref:microsoft.quantum.lang-ref.qubit)

Target qubit



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## References

- [*N. Schuch*, *J. Siewert*, PRL 91, no. 027902, 2003, arXiv:quant-ph/0303063](https://arxiv.org/abs/quant-ph/0303063)

## See Also

- [Microsoft.Quantum.Synthesis.ApplyXControlledOnTruthTableWithCleanTarget](xref:Microsoft.Quantum.Synthesis.ApplyXControlledOnTruthTableWithCleanTarget)
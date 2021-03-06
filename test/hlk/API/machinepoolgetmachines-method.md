---
title: MachinePool.GetMachines Method
description: MachinePool.GetMachines Method
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: e54ec048-88e0-41b4-8cba-344895d9edf6
author: sapaetsc
ms.author: sapaetsc
ms.date: 10/15/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-oem
---

# MachinePool.GetMachines Method


**Namespace:** Microsoft.Windows.Kits.Hardware.ObjectModel

**Assembly:** Microsoft.Windows.Kits.Hardware.ObjectModel (in Microsoft.Windows.Kits.Hardware.ObjectModel)

## <span id="Usage"></span><span id="usage"></span><span id="USAGE"></span>Usage


**Visual Basic**

`Dim instance As MachinePool`

`Dim returnValue As ReadOnlyCollection(Of Machine)`

`returnValue = instance.GetMachines`

## <span id="Syntax"></span><span id="syntax"></span><span id="SYNTAX"></span>Syntax


**Visual Basic**

`Public MustOverride Function GetMachines As ReadOnlyCollection(Of Machine)`

**C#**

`public abstract ReadOnlyCollection<Machine> GetMachines ()`

## <span id="Return_Value"></span><span id="return_value"></span><span id="RETURN_VALUE"></span>Return Value


Returns **ReadOnlyCollection**, which is a collection of machines (test computers) in this machine pool.

## <span id="Thread_Safety"></span><span id="thread_safety"></span><span id="THREAD_SAFETY"></span>Thread Safety


Any public static (**Shared** in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

 

 







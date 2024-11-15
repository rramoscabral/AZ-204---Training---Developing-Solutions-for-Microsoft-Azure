---
layout: default
title: 'Trainer demonstrations'
nav_order: 6
has_children: false
---

# Trainer demonstrations
{: .no_toc }


## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

<br/>

---

<br/>

## Learning Path 1: Get started with Windows PowerShell

<!-- Demonstrations -->

- **Getting started with Windows PowerShell**

    ```powershell
    #Switch Powershell Engine
    PowerShell.exe -Version 2

    #View Powershell Version
    $psversiontable.psversion
    ```

<br/>

---

<br/>


## Learning Path 02: Maintain system administration tasks in Windows PowerShell

<!-- Demonstrations -->


<br/>

---

<br/>


## Learning Path 03: Working with the Windows PowerShell pipeline

<!-- Demonstrations -->


<br/>

---

<br/>

## Learning Path 04: Work with PowerShell providers and PowerShell drives in Windows PowerShell


<!-- Demonstrations -->


<br/>

---

<br/>

## Learning Path 05: Query management information by using Common Information Model and Windows Management Instrumentation

<!-- Demonstrations -->

- **Querying CIM, WMI and WQL**

    ```powershell
    # List all classes
    Get-CimClass –Namespace root\CIMv2 | Sort CimClassName
    Get-WmiObject -Namespace root\cimv2 –List |  Sort Name



    # WMI
    Get-CimClass Win32_Volume

    # CIM
    Get-CimClass CIM_storagevolume 


    # View Services
    Get-WmiObject –Class Win32_Service

    # View Proccess
    Get-CimInstance –ClassName Win32_Process


    #Querying CIM

    (Get-CimInstance -ClassName Cim_StorageVolume).where({$PSItem.DriveLetter -eq 'C:'})
    
    Get-CimInstance -ClassName CIM_StorageVolume | where driveletter -eq "C:"


    # Querying CIM vs WMI
    Get-CimInstance -ClassName Win32_LogicalDisk -ComputerName $env:COMPUTERNAME

    Get-WmiObject -ClassName Win32_LogicalDisk -ComputerName $env:COMPUTERNAME

    Get-CimInstance –Query "SELECT * FROM Win32_LogicalDisk WHERE DeviceID  = 'C:'"

    Get-WmiObject –Query "SELECT * FROM Win32_LogicalDisk WHERE  DeviceID  = 'C:'"
    ```


<br/>

---

<br/>


## Learning Path 06: Working with variables, arrays, and hash tables

<!-- Demonstrations -->


<br/>

---

<br/>


## Learning Path 07: Windows PowerShell scripting

<!-- Demonstrations -->

- **If Statement**
    ```powershell
    $x = 9
    $y = 0


    if ($x -lt $y)
    {
        Write-Host "OI"
    }
    else
    {
        Write-Error "Erro"
    }
    ```

- **Function**

    ```powershell
    Function Get-ServerData
    {
        Param ($ComputerName)
        Get-CimInstance -Class Win32_OperatingSystem -ComputerName $ComputerName
    }
    ```


<br/>

---

<br/>

## Learning Path 08 Administer remote computers with Windows PowerShell:


<!-- Demonstrations -->


<br/>

---

<br/>



## Learning Path 09: Manage cloud resources by using Windows PowerShell


<!-- Demonstrations -->


<br/>

---

<br/>



## Learning Path 10: Manage Microsoft 365 services by using Windows PowerShell


<!-- Demonstrations -->


<br/>

---

<br/>



## Learning Path 11: Create and manage background jobs and scheduled jobs in Windows PowerShell


<!-- Demonstrations -->


<br/>

---

<br/>
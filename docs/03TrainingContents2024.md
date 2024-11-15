---
layout: default
title: 'Training Contents 2024'
has_children: false
parent: 'Training Contents'
---

# Training Contents 2024
{: .no_toc }

Training content for 2024

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

<br/>

---

<br/>

## Learning Path 1: Get started with Windows PowerShell

<!-- Overview -->
This Learning Path introduces you to PowerShell and provides an overview of its functionality. You’ll learn to open, configure, and run commands by using PowerShell on Windows. You’ll also learn about PowerShell’s built-in help system, which assists you with using the various PowerShell components and commands.


<br>

<!-- Module content -->

| Module | Learning Objectives | Units |
| --- | --- | --- |
|[Review Windows PowerShell](https://learn.microsoft.com/en-us/training/modules/review-windows-powershell/) | In this Module, you’ll learn about PowerShell’s system requirements and how to open and configure commonly used host applications, including the Windows PowerShell console and Windows PowerShell Integrated Scripting Environment (ISE). Finally, you’ll discover how you can use Microsoft Visual Studio Code (VS Code) to develop PowerShell scripts.| - Windows PowerShell introduction Windows PowerShell versions <br> - Windows PowerShell applications <br> - Considerations when using PowerShell <br> - Configuring the PowerShell console <br> - Configuring the ISE <br> - Using Visual Studio Code with PowerShell |
|[Understand Windows PowerShell command syntax](https://learn.microsoft.com/en-us/training/modules/understand-command-syntax-windows-powershell/) | In this Module, you’ll learn about the cmdlet structure and parameters for using Windows PowerShell cmdlets. You’ll also learn how to use tab completion and display About files content. | - Cmdlet structure <br> - Parameters <br> - Tab completion <br> - About files |
|[Find commands and get help in Windows PowerShell](https://learn.microsoft.com/en-us/training/modules/find-commands-get-help-windows-powershell/) |In this Module, you’ll learn how to find Windows PowerShell cmdlets for performing specific tasks. This Module provides strategies and tools for finding cmdlets based on the actions they perform and the features or technologies they manage. You‘ll also learn how to use Get-Help to retrieve detailed information about a cmdlet and its parameters. | - What are modules? <br> - Finding cmdlets <br> - What are aliases? <br> - Using Show-Command <br> - Using Get-Help <br> - Interpreting the help syntax <br> - Updating help |

<br>

<!-- Labs -->

| Lab |  Lab answer key | Exercise | Estimated time | 
| --- | --- | --- | --- |
|  [Lab: Configuring Windows PowerShell, and finding and running commands](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_01_Configuring_Windows_PowerShell_finding_and_running_commands.html) | [Lab answer key](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_AK_01_Configuring_Windows_PowerShell_finding_and_running_commands.html) | - Exercise 1: Configuring the Windows PowerShell console application <br> - Exercise 2: Configuring the Windows PowerShell ISE application <br> - Exercise 3: Finding and running Windows PowerShell commands <br> - Exercise 4: Using About files | 60 minutes |


<br>


## Learning Path 2: Maintain system administration tasks in Windows PowerShell

<!-- Overview -->
In this Learning Path, you’ll learn about the cmdlets that you’ll commonly use for system administration tasks related to Active Directory, network configuration, server administration, and Windows 10 device administration.


<br>

<!-- Module content -->

| Module | Learning Objectives | Units |
| --- | --- | --------- |
| [Manage Active Directory Domain Services using PowerShell cmdlets](https://learn.microsoft.com/en-us/training/modules/manage-active-directory-domain-services-use-powershell-cmdlets/) | In this Module, you’ll learn about the cmdlets used for administering AD DS. To find Active Directory cmdlets, search for the prefix “AD,” which most Active Directory cmdlets have in the noun part of the cmdlet name. | - User management cmdlets <br> - Group management cmdlets <br> - Cmdlets for managing computer objects  <br> - OU management cmdlets  <br> - Active Directory object cmdlets |
| [Manage network service settings for Windows devices using PowerShell cmdlets](https://learn.microsoft.com/en-us/training/modules/manage-network-service-settings-for-windows-devices-use-powershell-cmdlets/) | In this Module, you’ll learn about the PowerShell modules and cmdlets used for configuring network settings for Windows devices. | - Managing IP addresses <br> - Managing routing <br> - Managing DNS clients <br> - Managing Windows Firewall |
| [Manage Windows Server settings using PowerShell cmdlets](https://learn.microsoft.com/en-us/training/modules/manage-windows-server-settings-use-powershell-cmdlets/) |PowerShell is commonly used to perform administration tasks for Windows Server features and services. In this Module, you’ll learn about the cmdlets you can use to configure settings related to Group Policy, Server Manager, Hyper-V, and Internet Information Services (IIS). | - Group Policy management cmdlets <br> - Server Manager cmdlets <br> - Hyper-V cmdlets <br> - IIS administration cmdlets |
| [Manage settings for a local Windows machine using PowerShell cmdlets](https://learn.microsoft.com/en-us/training/modules/manage-settings-for-local-windows-machine-use-powershell-cmdlets/) | In addition to network service and configuration settings, PowerShell is commonly used to configure and manage settings on a local Windows machine. You can use PowerShell cmdlets to perform GUI-based operations more quickly or as a basis to run multiple commands within a script. In this Module, you’ll learn about common PowerShell cmdlets that you can use to perform tasks on a Windows 10 computer. | - Managing Windows 10 using PowerShell <br> - Managing permissions with PowerShell |

<br>

<!-- Labs -->

| Lab |  Lab answer key | Exercise | Estimated time | 
| --- | --- | --- | --- |
| [Lab: Performing local system administration with PowerShell](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_02_Administering_local_systems_using_PowerShell.html) | [Lab answer key](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_AK_02_Administering_local_systems_using_PowerShell.html) | - Exercise 1: Creating and managing Active Directory objects <br> - Exercise 2: Configuring network settings on Windows Server <br> - Exercise 3: Creating a website | 60 minutes |




<br>


## Learning Path 3: Working with the Windows PowerShell pipeline

<!-- Overview -->
In this Learning Path, you’ll learn the purpose and use of the PowerShell pipeline. You’ll use the pipeline to sort, filter, enumerate and display output data for PowerShell cmdlets.


<br>

<!-- Module content -->

| Module | Learning Objectives | Units | 
| --- | --- | --- |
| [Understand the Windows PowerShell pipeline](https://learn.microsoft.com/en-us/training/modules/understand-windows-powershell-pipeline/) | In this Module, you’ll learn about the Windows PowerShell pipeline and some basic techniques for running multiple commands in it. Running commands individually is both cumbersome and inefficient. Understanding how the pipeline works is fundamental to your success in using Windows PowerShell for administration. | - What is the pipeline? <br> - Pipeline output <br> - Discovering object members <br> - Formatting pipeline output |
| [Select, sort, and measure objects using the pipeline](https://learn.microsoft.com/en-us/training/modules/select-sort-measure-objects-use-pipeline/) | In this Module, you’ll learn to manipulate objects in the pipeline by using commands that sort, select, and measure objects. Selecting, sorting, and measuring objects is essential to successfully creating automation in Windows PowerShell. | - Sorting objects by a property <br> - Measuring objects  <br> - Selecting a subset of objects  <br> - Selecting object properties  <br> - Creating calculated properties |
| [Filter objects out of the pipeline](https://learn.microsoft.com/en-us/training/modules/filter-objects-out-of-pipeline/) | In this Module, you’ll learn how to filter objects out of the pipeline by using the Where-Object cmdlet to specify various criteria. This differs from the ability of Select-Object to select several objects from a collection because it provides more flexibility. | - Comparison operators  <br> - Basic filtering syntax <br> - Advanced filtering syntax <br> - Optimizing filtering performance |
| [Enumerate objects in the pipeline](https://learn.microsoft.com/en-us/training/modules/enumerate-objects-pipeline/) | In this Module, you’ll learn how to enumerate objects in the pipeline so that you can work with one object at a time during automation. Enumerating objects builds on the skills you’ve already learned and is a building block for creating automation scripts. | - Purpose of enumeration  <br> - Basic enumeration syntax  <br> - Advanced enumeration syntax |
| [Send pipeline data as output](https://learn.microsoft.com/en-us/training/modules/send-pass-data-output-from-pipeline/) | When you provide information about your network infrastructure, it’s often a requirement that you provide the information in specific formats. This might mean using a format for displaying on the screen, for printing a hard copy, or for storing in a file for later use. In this Module, you’ll learn how to send pipeline data to files and in various output formats. | - Writing output to a file <br> - Converting output to CSV <br> - Converting output to XML <br> - Converting output to JSON <br> - Converting output to HTML <br> - Additional output options |
| [Pass pipeline objects](https://learn.microsoft.com/en-us/training/modules/pass-pipeline-objects/) | In this Module, you will learn how the Windows PowerShell command-line interface passes objects from one command to another in the pipeline. Windows PowerShell has two techniques it can use: Passing data ByValue and ByPropertyName | - Pipeline parameter binding <br> - Identifying ByValue parameters <br> - Passing data by using ByValue <br> - Passing data by using ByPropertyName <br> - Identifying ByPropertyName parameters |


<br>

<!-- Labs -->

| Lab |  Lab answer key | Exercise | Estimated time | 
| --- | --- | --- | --- |
| [Lab A: Using PowerShell pipeline](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_03A_Working_with_Windows_PowerShell_Pipeline.html) | [Lab answer key](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_AK_03A_Working_with_Windows_PowerShell_Pipeline.html) | - Exercise 1: Selecting, sorting, and displaying data <br> - Exercise 2: Filtering objects | 60 Minutes |
| [Lab B: Using PowerShell pipeline](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_03B_Working_with_Windows_PowerShell_Pipeline.html) | [Lab answer key](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_03B_Working_with_Windows_PowerShell_Pipeline.html) | - Exercise 1: Enumerating objects <br> - Exercise 2: Converting objects | 60 Minutes | 


<br>

 
## Learning Path 4: Work with PowerShell providers and PowerShell drives in Windows PowerShell

<!-- Overview -->
PSProvider and PSDrive are two technologies that let you work with many forms of storage by using the same commands and techniques that you use to manage the file system:
- PSProvider: A Windows PowerShell adapter that makes some form of storage resemble a hard drive
- PSDrive: An actual connection to a form storage


<br>

<!-- Module content -->

| Module | Learning Objectives | Units |
| --- | --- | --- |
| [Connect with data stores using PowerShell providers](https://learn.microsoft.com/en-us/training/modules/connect-data-stores-use-powershell-providers/) | In this Module, you’ll learn about PSProviders, which are adapters that connect Windows PowerShell to data stores. Providers give you an easier-to-understand and consistent interface for working with these data stores. This makes learning to work with the providers simpler and allows you to reuse scripts as you change the underlying technologies with which you are working. | - What are Windows PowerShell providers? <br> - Different provider capabilities <br> - Accessing provider help |
| [Use PowerShell drives in PowerShell](https://learn.microsoft.com/en-us/training/modules/use-powershell-drives-powershell/) | In this Module, you’ll learn how to work with PSDrives—a specific form of storage that connects to Windows PowerShell by using a PSProvider. Understanding how to work with PSDrives enables you to use PSProviders successfully. In some cases (such as with the file system), PSDrives are the primary interface for working with the underlying data. | - What are PSDrives? <br> - Cmdlets for using PSDrives <br> - Working with the file system <br> - Working with the registry <br> - Working with certificates  <br> - Working with other PSDrives | 

<br>

<!-- Labs -->

| Lab |  Lab answer key | Exercise | Estimated time | 
| --- | --- | --- | --- |
| [Lab: Using PSProviders and PSDrives with PowerShell](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_04_Using_PSProviders_and_PSDrives.html) | [Lab answer key](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_AK_04_Using_PSProviders_and_PSDrives.html) | - Exercise 1: Creating files and folders on a remote computer <br> - Exercise 2: Creating a registry key for your future scripts <br> - Exercise 3: Creating a new Active Directory group | 150 minutes |




<br>


## Learning Path 5: Query management information by using Common Information Model and Windows Management Instrumentation

<!-- Overview -->
Windows Management Instrumentation (WMI) and Common Information Model (CIM) provide local and remote access to a repository of management information, including robust information available from the operating system, from computer hardware, and from installed software. In this Learning Path, you’ll learn about these two technologies.


<br>

<!-- Module content -->

| Module | Learning Objectives | Units |
| --- | --- | --- |
| [Review CIM and WMI](https://learn.microsoft.com/en-us/training/modules/review-common-information-model-windows-management-instrumentation/) | In this Module, you’ll learn about the architecture of CIM and WMI. Both technologies connect to a common information repository that contains management information that you can query and manipulate. The repository contains information about a computer system or device, including hardware, software, hardware drivers, components, roles, services, user settings, and just about every configurable item and the current state of that item. Familiarity with the framework and syntax of CIM and WMI will help you know and control many aspects of an operating system environment. | - Architecture and technologies <br> - Understanding the repository <br> - Finding documentation  |
| [Query configuration information by using CIM and WMI](https://learn.microsoft.com/en-us/training/modules/query-configuration-information/) | One of the most common uses for WMI and CIM is querying configuration information from computers. In this Module, you’ll learn more about the structure of the namespaces that contain classes and how to query instances of a class. You’ll also learn how to query remote computers by using ad hoc connections and CIM sessions. | - Listing namespaces <br> - Listing classes <br> - Querying instances <br> - Connecting to remote computers <br> - Using CIM sessions |
| [Query and manipulate repository objects by using CIM and WMI methods](https://learn.microsoft.com/en-us/training/modules/query-manipulate-repository-objects/) | In this Module, you’ll learn to use CIM and WMI to make changes by using methods. The methods available to you vary depending on the type of object. Discovering and understanding these methods is an important step in querying and manipulating the repository information. | - Discovering methods <br> - Finding documentation for methods <br> - Invoking methods |

<br>

<!-- Labs -->

| Lab |  Lab answer key | Exercise | Estimated time | 
| --- | --- | --- | --- |
| [Lab: Querying management information by using CIM and WMI](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_05_Making_changes_by_using_CIM_and_WMI.html) | [Lab answer key](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_AK_05_Making_changes_by_using_CIM_and_WMI.html) | -Exercise 1: Querying information by using WMI <br> - Exercise 2: Querying information by using CIM  <br> - Exercise 3: Invoking methods | 45 minutes |


<br>


## Learning Path 6: Working with variables, arrays, and hash tables

<!-- Overview -->
As an essential component of scripts, variables enable you to accomplish complex tasks that you can’t complete using a single command. This Learning Path explains how to work with variables, arrays, and hash tables as steps in learning how to create Windows PowerShell scripts.


<br>

<!-- Module content -->

| Module | Learning Objectives | Units |
| --- | --- | --- |
| [Use variables in Window PowerShell scripts](https://learn.microsoft.com/en-us/training/modules/manage-variables-windows-powershell-scripts/) | This Module explains some rules for using variables, which help ensure that the data you store in variables is in the correct format and easily accessible. It’s important to name variables appropriately and to assign them the correct data type. | - What are variables? <br> - Variable naming <br> - Assigning a value to a variable <br> - Variable types | 
| [Manipulate variables in Window PowerShell scripts](https://learn.microsoft.com/en-us/training/modules/manage-variables-windows-powershell-scripts/) | In this Module, you’ll learn how to identify the properties and methods for use in your scripts and manipulate the contents of variables. Each variable type has a unique set of properties that you can access and each variable has a unique set of methods that you can use to manipulate it. | - Identifying methods and properties <br> - Working with strings <br> - Working with dates |
| [Work with arrays and hash tables in Window PowerShell scripts](https://learn.microsoft.com/en-us/training/modules/work-arrays-hash-tables-window-powershell-scripts/) | This Module covers arrays and hash tables, which you can use to store data that’s more complex than simple variables. You can also use them to complete more complex tasks with your scripts. | - What is an array? <br> - Working with arrays <br> - Working with array lists <br> - What is a hash table? <br> - Working with hash tables |


<br>

<!-- Labs -->

| Lab |  Lab answer key | Exercise | Estimated time | 
| --- | --- | --- | --- |
| [Lab: Working with variables, arrays, and hash table](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_06_Working_with_variables_arrays_and_hash_tables.html) | [Lab answer key](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_AK_06_Working_with_variables_arrays_and_hash_tables.html) | - Exercise 1: Working with variable types <br> - Exercise 2: Using arrays <br> - Exercise 3: Using hash tables | 45 minutes |

<br>


## Learning Path 7: Windows PowerShell scripting

<!-- Overview -->
You can use Windows PowerShell to create scripts to accomplish more complex tasks that aren’t possible by using a single command. You can reuse scripts multiple times to accomplish repetitive tasks. After the necessary commands are in a script, there’s a lower risk of errors when you run it. 


<br>

<!-- Module content -->

| Module | Learning Objectives | Units |
| --- | --- | --- |
| [Create and run scripts by using Windows PowerShell](https://learn.microsoft.com/en-us/training/modules/create-run-scripts-use-windows-powershell/) | Most administrators start working with scripts by either downloading or modifying scripts that others created. After you’ve obtained a script, you must run it. There are some important differences between running scripts in Windows PowerShell versus running them at a traditional Windows Command Prompt. These differences are covered in this Module along with other concepts that are related to scripting. | - Overview of Windows PowerShell scripts <br> - Modifying scripts <br> - Creating scripts <br> - What is the PowerShellGet module? <br> - Running scripts <br> - The script execution policy <br> - Windows PowerShell and AppLocker <br> - Digitally signing scripts |
| [Work with scripting constructs in Windows PowerShell](https://learn.microsoft.com/en-us/training/modules/work-script-constructs-windows-powershell/) | While there are some simple scripts that use only Windows PowerShell commands, most scripts use scripting constructs to perform more complex actions. You can use the ForEach construct to process all the objects in an array. You can use If..Else and Switch constructs to make decisions in your scripts. Finally, there are less common looping constructs such as `For`, `While`, and `Do..While` loops that you can use when appropriate. | - Understanding ForEach loops <br> - Understanding the If construct <br> - Understanding the Switch construct <br> - Understanding the For construct <br> - Understanding other loop constructs <br> - Understanding Break and Continue |
| [Import data in different formats for use in scripts by using Windows PowerShell cmdlets](https://learn.microsoft.com/en-us/training/modules/import-data-different-formats-for-use-scripts/) | When you create a script, reusing data from other sources is useful. Most applications can export the data you want in various formats such as a CSV file or an XML file. You can use Windows PowerShell cmdlets to import data in different formats for use in your scripts. In this Module, you’ll learn how to import data from a text file, CSV file, XML file, and JavaScript Object Notation (JSON) file. | - Using Get-Content <br> - Using Import-Csv <br> - Using Import-Clixml <br> - Using ConvertFrom-Json |
| [Use methods to accept user inputs in Windows PowerShell scripts](https://learn.microsoft.com/en-us/training/modules/use-methods-to-accept-user-inputs-windows-powershell-scripts/) | To enhance the usability of your scripts, you must learn how to accept user input. This skill allows you to create scripts that you can use for multiple purposes. In addition, accepting user input allows you to create scripts that are easier for others to use. In this Module, you learn about multiple methods for accepting user input in a script. | - Identifying values that might change <br> - Using Read-Host <br> - Using Get-Credential <br> - Using Out-GridView <br> - Passing parameters to a script |
| [Troubleshoot scripts and handle errors in Windows PowerShell](https://learn.microsoft.com/en-us/training/modules/troubleshoot-scripts-handle-errors-windows-powershell/) | As you develop more scripts, you’ll find that efficient troubleshooting makes your script development much faster. A big part of efficient troubleshooting is understanding error messages. For some difficult problems, you can use breakpoints to stop a script partially through execution to query values for variables. | - Understanding error messages <br> - Adding script output <br> - Using breakpoints <br> - Understanding error actions |
| [Use functions and modules in Windows PowerShell scripts](https://learn.microsoft.com/en-us/training/modules/use-functions-modules-windows-powershell-scripts/) | When you create many scripts, you’ll have snippets of code that you want to reuse. You might also have snippets of code that you want to reuse within the same script. Rather than having the same lines of code appearing multiple times in a script, you can create a function that appears once in the script but is called multiple times. If you need to use the same code across multiple scripts, then you can place the function in a module that subsequently can be shared by multiple scripts. In this Module, you'll learn to create functions and modules. | - What are functions? <br> -  Using variable scopes <br> - Creating a module <br> - Using dot sourcing |




<br>

<!-- Labs -->

| Lab |  Lab answer key | Exercise | Estimated time | 
| --- | --- | --- | --- |
| [Lab: Using scripts with PowerShell](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_07_Windows_PowerShell_Scripting.html) | [Lab answer key](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_AK_07_Windows_PowerShell_Scripting.html) |  - Exercise 1: Signing a script <br> - Exercise 2: Processing an array with a ForEach loop <br> - Exercise 3: Processing items by using If statements <br> - Exercise 4: Creating users based on a CSV file <br> - Exercise 5: Querying disk information from remote computers <br> - Exercise 6: Updating the script to use alternate credentials | 150 minutes |



 | 150 minutes |

<br>


## Learning Path 8 Administer remote computers with Windows PowerShell: 

<!-- Overview -->
Windows PowerShell remoting is a technology that enables you to connect to one or more remote computers, and then have them run commands on your behalf. It has become the foundation for remote administration in Windows operating system-based environments. Windows PowerShell 5.0 is installed as part of Windows Management Framework 5.0, which offers both Windows PowerShell functionality and remoting capabilities. For example, the graphical Server Manager console in Windows Server relies on remoting to communicate with servers, even to communicate with the local computer on which the console is running. Past Windows operating system versions have included remoting, but its use was largely optional. Now, the technology is quickly becoming a mandatory component for every environment.

<br>

<!-- Module content -->

| Module | Learning Objectives | Units |
| --- | --- | --- |
| [Manage single and multiple computers by using Windows PowerShell remoting](https://learn.microsoft.com/en-us/training/modules/manage-single-multiple-computers-use-windows-powershell-remoting/) | Although remoting is a complex technology, working with Windows PowerShell remoting is fairly straightforward when you understand the underlying concepts. In this Module, you learn how to use remoting to perform administration on remote computers. | - Remoting overview and architecture <br> - Remoting versus remote connectivity <br> - Remoting security <br> - Enabling remoting <br> - Using one-to-one remoting <br> - Using one-to-many remoting <br> - Remoting output versus local output |
| [Use advanced Windows PowerShell remoting techniques](https://learn.microsoft.com/en-us/training/modules/use-advanced-windows-powershell-remoting-techniques/) | Windows PowerShell remoting includes several advanced techniques that help achieve specific goals or alleviate specific shortcomings. In the previous Module, you reviewed the shortcomings of some of the basic techniques. In this Module, you’ll learn about some useful advanced techniques that will help overcome these challenges. | - Common remoting options <br> - Sending parameters to remote computers <br> - Windows PowerShell scopes <br> - Multi-hop remoting |
| [Manage persistent connections to remote computers by using Windows PowerShell sessions](https://learn.microsoft.com/en-us/training/modules/manage-persistent-connections-to-remote-computers/) | In this Learning Path, you’ve learned that each remoting command you used created a connection, used it, and then closed it. However, as previously discussed, this approach doesn’t provide the option to persist session data across remote connections. Using a persistent connection allows you to interactively query and manage a remote computer. In this Module, you’ll learn how to establish and manage persistent connections to remote computers, known as Windows PowerShell sessions, or PSSessions. | - Persistent connections <br> - Creating and using a PSSession <br> - Disconnected sessions <br> - Implicit remoting |

<br>

<!-- Labs -->

| Lab |  Lab answer key | Exercise | Estimated time | 
| --- | --- | --- | --- |
| [Lab: Performing remote administration with PowerShell](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_08_Performing_remote_administration_with_PowerShell.html) | [Lab answer key](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_AK_08_Performing_remote_administration_with_PowerShell.html) | - Exercise 1: Enabling remoting on the local computer <br> - Exercise 2: Performing one-to-one remoting <br> - Exercise 3: Performing one-to-many remoting <br> - Exercise 4: Using implicit remoting <br> - Exercise 5: Managing multiple computers | 60 minutes | 

<br>

## Learning Path 9: Manage cloud resources by using Windows PowerShell 


<!-- Overview -->
Besides managing local resources, you can also use Windows PowerShell to manage cloud resources, such as Azure platform or Microsoft 365. To manage cloud-based resources, you need to install additional modules for Windows PowerShell. In this Learning Path, you’ll learn how to install modules necessary for cloud services management to Windows PowerShell, and you’ll also learn how to use PowerShell commands to perform some simple administrative tasks on cloud resources such as Azure virtual machines (VMs), Azure storage accounts, and Azure subscriptions. You’ll also learn how to use Azure Cloud Shell environment to perform PowerShell based on Bash based administration directly from Azure portal.


<br>

<!-- Module content -->

| Module | Learning Objectives | Units |
| --- | --- | --- |
| [Review the Azure PowerShell module](https://learn.microsoft.com/en-us/training/modules/review-azure-powershell-module/) | You can manage Azure resources by using the Azure portal, which is usually the most common administration method. However, for some tasks, PowerShell is more convenient. In this Module, you’ll learn about the Azure PowerShell environment and the Az module for Windows PowerShell. Also, you’ll learn about ways to manage Microsoft Entra ID by using PowerShell modules. | - Azure PowerShell overview <br> - What is the Azure Az PowerShell module? <br> - Installing the Azure Az PowerShell module <br> - Migrate Azure PowerShell from AzureRM to Az <br> - What are the Microsoft Azure Active Directory Module for Windows PowerShell and Azure Active Directory PowerShell for Graph modules?|
| [Review the features and tools for Azure Cloud Shell](https://learn.microsoft.com/en-us/training/modules/review-features-tools-for-azure-cloud-shell/) | Instead of using the locally installed PowerShell module for managing Azure resources, you can use the Azure Cloud Shell environment. The Azure Cloud Shell environment enables you to use the PowerShell or Bash environment and commands to manage Azure resources. Azure Cloud Shell is available in the Azure portal and in the Microsoft 365 admin portal. In this Module, you’ll learn about Cloud Shell and its features. | - Cloud Shell overview <br> - Features and tools for Azure Cloud Shell |
| [Manage Azure resources with Windows PowerShell](https://learn.microsoft.com/en-us/training/modules/manage-azure-resources-windows-powershell/) | Azure virtual machines (VMs) provide a fully configurable and flexible computing environment. You can create and manage these VMs by using the Azure portal, Windows PowerShell with the Az module, or the Cloud Shell environment. In this Module, you’ll learn how to create and manage Azure VMs by using PowerShell. Finally, you’ll learn about managing Azure storage accounts and Azure subscriptions with PowerShell. | - Creating Azure VMs with Windows PowerShell <br> - Managing Azure VMs with Windows PowerShell <br> - Managing storage with Azure PowerShell <br> - Managing Azure subscriptions with Azure PowerShell |






<br>

<!-- Labs -->

| Lab |  Lab answer key | Exercise | Estimated time | 
| --- | --- | --- | --- |
| [Lab: Azure resource management with PowerShell](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_09_Azure_resource_management_with_PowerShell.html) | [Lab answer key](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_AK_09_Azure_resource_management_with_PowerShell.html) | - Exercise 1: Activating the Azure subscription and installing the PowerShell Az module <br> - Exercise 2: Using Azure Cloud Shell <br> - Exercise 3: Managing Azure resources with Azure PowerShell |60 minutes |



<br>


## Learning Path 10: Manage Microsoft 365 services by using Windows PowerShell

<!-- Overview -->
Microsoft 365 is a cloud service that includes many components. The most commonly used services in Microsoft 365 are Microsoft Entra ID, Exchange Online, SharePoint Online, and Microsoft Teams. To efficiently manage Microsoft 365 and gain access to all configuration options, you should know how to use PowerShell to manage those services.



<br>

<!-- Module content -->

| Module | Learning Objectives | Units |
| --- | --- | --- |
| [Manage users, groups, and licenses in Microsoft Entra ID by using Windows PowerShell](https://learn.microsoft.com/en-us/training/modules/manage-users-groups-licenses-azure-active-directory-use-windows-powershell/) | Microsoft 365 includes multiple cloud services. However, the core of Microsoft 365 is Microsoft Entra ID, which provides identity management for all the services in Microsoft 365. In this Module, you’ll learn how to create users and groups, and manage roles and licenses. | - Benefits of using PowerShell for Microsoft 365 <br> - Connecting to the Microsoft 365 tenant with PowerShell <br> - Managing users in Microsoft 365 with PowerShell <br> - Managing groups in Microsoft 365 with PowerShell <br> - Managing roles in Microsoft 365 with PowerShell <br> - Managing licenses in Microsoft 365 with PowerShell |
| [Manage Exchange Online by using Windows PowerShell](https://learn.microsoft.com/en-us/training/modules/manage-exchange-online-use-windows-powershell/) | Exchange Online is one of the most commonly used services in Microsoft 365. You can use PowerShell cmdlets to efficiently manage bulk operations and perform tasks that aren’t possible through the web-based administrative interface. Being adept at managing Exchange Online with PowerShell will make you a much better administrator. | - Connecting to Exchange Online PowerShell <br> - Managing mailboxes in Exchange Online <br> - Managing resources in Exchange Online <br> - Managing admin roles in Exchange Online |
| [Manage SharePoint Online by using Windows PowerShell](https://learn.microsoft.com/en-us/training/modules/manage-sharepoint-online-use-windows-powershell/) | SharePoint Online is a collaboration service that allows you to store and share information through a web-based interface. Many organizations use SharePoint sites to build web portals for departments. In this Module, you’ll learn how to create a site and assign user permissions. | - SharePoint Online Management Shell overview <br> - Managing SharePoint Online <br> - users and groups with PowerShell <br> - Managing sites with Windows PowerShell <br> - Managing external user sharing with Windows PowerShell |
| [Manage Microsoft Teams by using Windows PowerShell](https://learn.microsoft.com/en-us/training/modules/manage-microsoft-teams-use-windows-powershell/) | Microsoft Teams is a collaboration service that combines multiple Microsoft 365 services into a single interface. It’s a useful tool for workgroups and projects. You can use the Microsoft Teams PowerShell module to perform tasks such as creating teams and managing user permissions. | - Overview of the Microsoft Teams PowerShell module <br> - Installing the Microsoft Teams PowerShell module <br> - Managing Teams with the Microsoft Teams PowerShell module |



<br>

<!-- Labs -->

| Lab |  Lab answer key | Exercise | Estimated time | 
| --- | --- | --- | --- |
| [Lab: Managing Microsoft 365 with PowerShell](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_10_Managing_Microsoft_365_services_with_PowerShell.html) | [Lab answer key](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_AK_10_Managing_Microsoft_365_services_with_PowerShell.html) | - Exercise 1: Managing users and groups in Microsoft Entra ID <br> - Exercise 2: Managing Exchange Online <br> - Exercise 3: Managing SharePoint Online <br> - Exercise 4: Managing Microsoft Teams | 60 minutes |


<br>


## Learning Path 11: Create and manage background jobs and scheduled jobs in Windows PowerShell 

<!-- Overview -->
If you use the Windows PowerShell console to start a task whose execution takes a long time, you will not be able to run other commands from the same console until the task completes. Background jobs allow you to use the same console to work with other tasks while the long-running one is active. In this Learning Path, you’ll learn about the Windows PowerShell jobs.


<br>

<!-- Module content -->

| Module | Learning Objectives | Units |
| --- | --- | --- |
| [Create and manage background jobs using Windows PowerShell](https://learn.microsoft.com/en-us/training/modules/create-manage-background-jobs-use-windows-powershell/) | When you run a command as a background job, Windows PowerShell performs the task asynchronously in its own thread. Even if the job takes a long time to complete, you regain access to the PowerShell prompt immediately. This allows you to run other commands while the job runs in the background. | - What are background jobs? <br> - Starting jobs <br> - Managing jobs <br> - Retrieving results for running jobs |
| [Create and manage scheduled jobs using Windows PowerShell](https://learn.microsoft.com/en-us/training/modules/create-manage-scheduled-jobs-use-windows-powershell/) | This Module covers scheduled jobs, which are similar to background jobs because they run asynchronously in the background. In Windows PowerShell, scheduled jobs are essentially scheduled tasks that follow all the same rules for actions, triggers, and other features, and run Windows PowerShell scripts by design. | - Running Windows PowerShell scripts as scheduled tasks  <br> - What are scheduled jobs? <br> - Job options and job triggers <br> - Creating a scheduled job <br> - Retrieving scheduled job results |


<br>

<!-- Labs -->

| Lab |  Lab answer key | Exercise | Estimated time | 
| --- | --- | --- | --- |
| [Lab: Jobs management with PowerShell](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_AK_10_Managing_Microsoft_365_services_with_PowerShell.html) | [Lab answer key](https://microsoftlearning.github.io/AZ-040T00-Automating-Administration-with-PowerShell/Instructions/Labs/LAB_AK_11_Using_background_jobs_and_scheduled_jobs.html) | - Exercise 1: Starting and managing jobs <br> - Exercise 2: Creating a scheduled job | 30 minutes |


<br>

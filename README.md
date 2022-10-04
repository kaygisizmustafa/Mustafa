<h1>Hi, I'm Mustafa! <a href="https://www.linkedin.com/in/mustafa-kayg%C4%B1s%C4%B1z-047755143/">IT OT Convergence Professional</a>,
<h2>👨‍💻 IT /OT CONVERGENCE:</h2>

---

    title:  Implement a TIA Portal v17 to Azure IoT Hub 
    module: Module 1: 
---
# 01 - Tia Portal to Azure IOT Hub

In this module, we will configure how to collected data from Tia Portal Winncc HMI simulation Tags to Azure IoT Hub in Azure Portal, via KepserverEX6.

# Task 1: Create Tia Portal Boiler simulation Project  

In this task, we will open Tia portal project that before created. 

1. 1.	Preparing simulation on the Tia portal V17 

2. 1.1-	PLC boiler program is created on the boiler and CPU 1511C-1 is defined on this project
That name is boiler.ap17
3.

    | Settings | Value |
    |--|--|
    | Subscription | **Keep default supplied** |
    | Resource Group | **Create new resource group** |
    | IoT Hub Name | **my-hub-groupxxxxx** |
    | Region | **East US** |

    **Note** - Remember to change the **xxxxx** so that it makes a unique **IoT Hub Name**.

4. Go to the **Management** tab, and use the dropdown to set the **Pricing and scale tier** to **S1: Standard tier**.

5. Click the **Review + create** button.

6. Click the **Create** button to begin creating your new Azure IoT Hub instance.

7. Wait until the Azure IoT Hub instance is deployed. 

# Task 2: kepserver
In this task, we will add tags 

1. When the deployment has completed, click **Go to resource** from the deployment blade. Alternatively, from the **All services** blade, search for and select **IoT Hub** and locate your new IoT Hub instance

	![Screenshot of the deployment in progress and deployment succeeded notifications in Azure portal.](../images/0601.png)

2. 

3. 

4. 

5. 

	

# Task 3: Iot Hub
In this task, we will . 

1. 
2. 

	

**Note**: To avoid additional costs, you can optionally remove this resource group. Search for resource groups, click your resource group, and then click **Delete resource group**. Verify the name of the resource group and then click **Delete**. Monitor the **Notifications** to see how the delete is proceeding.

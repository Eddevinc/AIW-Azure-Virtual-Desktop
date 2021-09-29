# Lab 12: Onboard AVD to Azure Security Center

Azure Security Center is a unified infrastructure security management system that strengthens the security posture of your data centers, and provides advanced threat protection across your hybrid workloads in the cloud - whether they're in Azure or not - as well as on premises.

In this lab, We'll be configuring Azure Security service for AVD.

## Exercise 1: Enabling Azure Security Center for Azure Virtual Desktop environment

### Task 1: Enabling Azure Security Center

1. In Azure Portal search for **Security Center** and click on it from the search results.

  ![ws name.](media/avdv239.png)
  
2. In the Security center page click on **Pricing & settings** under Management from the left hand blade.

  ![ws name.](media/avdv240.png)

3. Now in Security center | Pricing and settings page, click on your Log Analytics workspace i.e. **<inject key="Log Analytics Workspace Name	" />**.

  ![ws name.](media/avdv241.png)
  
4. In Settings | Azure Defender plans page, click on **Azure Defender on** *(1)* and make sure that the toggle switch for **Server** is set to **On** then click on **Save**.

  ![ws name.](media/avdv242.png)
  


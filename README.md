# Office LTSC 2021 Deployment 
![logo](https://github.com/Abhranil2004/Office-LTSC-2021-Deployment/blob/general/Microsoft-Office-2021-LTSC-v2108.jpg)
## Step 1: Prerequisites
1. Ensure that you have the Office LTSC 2021 installation files ready.
2. Make sure you have the necessary permissions for the deployment.


## Step 2: Create Deployment Configuration XML
1. Create a new text file named `configuration.xml`.
2. Copy and paste the following XML content into the file:

```xml
<Configuration>
  <Add OfficeClientEdition="64" Channel="PerpetualVL2021">
    <Product ID="ProPlus2021Volume" PIDKEY="YOUR_PRODUCT_KEY">
      <Language ID="en-us" />
    </Product>
  </Add>
  <Display Level="None" AcceptEULA="TRUE" />
  <Property Name="AUTOACTIVATE" Value="1" />
  <Configuration>

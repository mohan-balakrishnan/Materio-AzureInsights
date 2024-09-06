# Steps to Create Azure Application Insights

## Step 1: Sign in to Azure Portal
1. Go to the [Azure portal](https://portal.azure.com/).
2. Sign in with your Azure account.

## Step 2: Create a New Application Insights Resource
1. **Search for Application Insights**: In the Azure portal, search for "Application Insights" in the top search bar.
2. **Click on Application Insights**: In the search results, select **Application Insights**.
3. **Add a New Resource**: In the Application Insights dashboard, click **+ Create**.
4. **Fill in the Required Details**:
   - **Subscription**: Select your Azure subscription.
   - **Resource Group**: Create a new resource group or select an existing one.
   - **Name**: Enter a unique name for your Application Insights instance.
   - **Region**: Select a region closest to your application.
   -**Tags**: add Some tages for reference(optional).
5. **Review and Create**: Review the details and click **Create**.

## Step 3: Configure Application Insights in Your Application
1. Once the resource is created, go to your Application Insights resource page.
2. **Grab the Instrumentation Key** or **Connection String** from the **Overview** tab. You'll need this for integration.

## Step 4: Monitor Application Performance
1. After setup, your application will start sending telemetry data to Application Insights.
2. **View telemetry** like requests, failures, and performance from the **Monitoring** section in the resource.

---

*Follow these steps to create and integrate Azure Application Insights into your application for real-time performance monitoring and diagnostic insights.*

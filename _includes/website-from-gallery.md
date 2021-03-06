1. Log in to the Azure Preview Portal.

2. Open the Azure Marketplace either by clicking the **Marketplace** icon, or by clicking the **New** icon on the bottom left of the dashboard, selecting **Web + Mobile** and then **Azure Marketplace** at the bottom.
	
	![Create New][5]
	
3. Select **Web Apps**. Search for **WordPress** and click the **WordPress** icon.

	![WordPress from list][7]
	
5. After reading the description of the WordPress app, select **Create**.

6. Click on **WEB APP**, and provide the required values for configuring your web app.

   * **URL**: Unique Url for your WordPress site.
   * **App Service Plan**: LoopConf
   * **Pricing Tier**: 
       * Click Pricing Tier
       * Click View All
           
           ![Pricing Tier][20]

       * Select Free
           
           ![Free Tier][22]
       
   * **Web App Settings**: No Changes
   * **Location**: No Changes 

   ![configure your app][8]

7. Click on **DATABASE**, and provide the required values for configuring your MySQL database. 

> Accept the Legal Terms

   ![configure database][database]

8. If necessary, click **SUBSCRIPTION**, and specify the subscription to use. 

7. When you have finished defining the web app, click **Create**, and wait while the new web app is created.

   When the app has been created, you will see the resource group containing web app and database.

   ![show group][resourcegroup]

## Launch and manage your WordPress web app
	
1. Click on your new web app to see details about your app.

   ![launch dashboard][10]

2. On the **Essentials** page, click either **Browse** or the link under **Url** to open the web app's welcome page.

   ![site URL][browse]

3. If you have not installed WordPress, enter the appropriate configuration information required by WordPress and click **Install WordPress** to finalize configuration and open the web app's login page.

4. Click **Login** and enter your credentials.  

5. You'll have a new WordPress web app that looks similar to the web app below.    

	![your WordPress site][13]

[5]: ./media/website-from-gallery/startmarketplace.png
[6]: ./media/website-from-gallery/wordpressgallery-02.png
[7]: ./media/website-from-gallery/selectwordpress.png
[8]: ./media/website-from-gallery/configureweb.png
[9]: ./media/website-from-gallery/wordpressgallery-05.png
[10]: ./media/website-from-gallery/seewebapp.png
[13]: ./media/website-from-gallery/wordpressgallery-09.png
[webapps]: ./media/website-from-gallery/selectwebapps.png
[database]: ./media/website-from-gallery/configuredb.png
[resourcegroup]: ./media/website-from-gallery/showgroup.png
[browse]: ./media/website-from-gallery/browse.png
[20]: ./media/pricing-tier-view-all.png
[22]: ./media/Free-Tier.png

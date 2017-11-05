# tms-listview-import

This is the profile that the Williams College Museum of Art uses to export collection data from TMS.

TMS ships with a helper application called List View Designer. List View Designer allows you to create and format views for List Views in TMS. List Views in TMS allow you to export structured data without using just the TMS client; you don't need access to the backend database. This means that people who are not developers or database experts can export open-access csv files from TMS.

To use: 
- Download this xml file.
- Open List View Designer.
- Click the "import" button in the top bar.
- Select this xml file.
- Create a new view.
- Select "Global" to make the view available to all TMS users.
- Save.

Open TMS and export data. [Detailed instructions](https://medium.com/@caw_/open-data-from-tms-for-all-5c68b5adcad6)
The new view will be available in the drop down menu in the List View.

Use at your own risk. Please ensure that you have proper database backups before using this script. 

# Low Stock Notification

"low_stock_notify" is a module that automatically emails a list of products with low stock. 

Each product's low stock "threshold" is set on the product form. 
- Default value is -1
- Set to a positive number for the product to be included in the low stock report

Creates a scheduled action to run once daily. 
- You can reconfigure the settings in ```Settings > Automation > Scheduled Actions > Check Low Stock and Notify```

Includes a very basic email template, but **you must update email address values on the template settings**.
- You can change the settings in ```Settings > Email > Templates > Low Stock Automated Report```

##### To Do:

- Test in default instance
  - Does SKU work appropriately?
- Test what happens if there are multiple templates named "Low Stock Automated Report"

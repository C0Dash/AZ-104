https://stackoverflow.com/questions/20748969/how-to-set-the-default-subscription-in-the-windows-azure-portal#:~:text=To%20set%20the%20default%20to,Advanced%20Filters%22%20sidebar%20(left)

I disabled an unwanted subscription, but the dashboard still showed this disabled subscription as the default.

To set the default to my desired subscription, I did this:

https://portal.azure.com/#settings/directory
Toggle "Advanced Filters" slider to "on" (top right)
Go to "Advanced Filters" sidebar (left)
Push " + Create a filter " link/button
Filter Type Dropdown: "Subscription name"
Value Dropdown: [X] Your Subscription
More information can be found here: https://docs.microsoft.com/en-us/azure/azure-portal/set-preferences#subscription-filters

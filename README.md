# MAUI RadioButtonsIssue
This sample illustrate  inconsistencies of RadioButton Behaviors on Windows with MAUI (Note: this sample works correctly on Androis and IOS)
On Windows, the **GroupName** property has no effect when radioButtons are all part of the same container
On Windows, only the last button with the **IsChecked** property set to true is actually checked by default.

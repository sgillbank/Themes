# Summary
For merchants wanting to integrate with PayFabric hosted payment page and hosted wallet page, there's a way to inject custom CSS code into the hosted page to fit the overall style of the 3rd party application. To implement a custom theme, you will need to get your PayFabric account ready by doing some priliminary configurations. Please go through [Quick Start](https://github.com/PayFabric/API-Samples/wiki/Quick-Start) for help getting starting with PayFabric.

To implement a custom theme, below are steps involved into the process:
* [Define Themes](#definetheme)
* [Apply a Theme to a Device](#applytheme)

# Define Themes

Navigate through Settings > Dev Central > Themes to open the page below. By clicking "Create New" button you can add a new theme name into your account. A theme includes two parts: "custom CSS style" and "custom JavaScript". Those CSS and JavaScript rules affect both hosted payment pages and hosted wallet pages allowing you to apply your own look and feel. 

![themes](https://s3-us-west-1.amazonaws.com/github-screenshot-repository/v2/themes.png)

Also you can choose to show/hide the related fields on hosted payment page by checking/unchecking parameters of the theme.
![ThemeParams](https://s3-us-west-1.amazonaws.com/github-screenshot-repository/v2/ThemeParams.PNG)

# Apply a Theme to a Device

Navigate through Settings > Dev Central > Devices to open below page. Here is a list of devices on your account. By clicking the icon button under "Default Theme" column an extended region will be expanded. All available themes will be listed in this region where you can choose one as the default theme for a device. 

![devicetheme](https://s3-us-west-1.amazonaws.com/github-screenshot-repository/v2/themes1.png)

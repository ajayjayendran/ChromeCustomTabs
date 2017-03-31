# ChromeCustomTabs
This app allows to load a chrome tab within your app, and also allows you customize the look and feel of Chrome thereby making the transition between your app and the web content fast &amp; seamless for your users.

# 1. How to use Chrome Custom tabs?
   add the chrome custom tabs dependency to the dependencies 
   ```
dependencies {
    ...
    compile 'com.android.support:customtabs:23.4.0'
}
```
# 2. Open a Chrome custom tab
  * Create a CustomTabsIntent builder for customization. Specify all the custom properties you desire.
  * Build a CustomTabsIntent from the builder
  * Launch the url.

# DrawerLayoutInstaller
Simple tool which helps you to inject DrawerLayout into existing Activity layout tree

# Usage
```java
DrawerLayoutInstaller.from(this)
        .drawerRoot(R.layout.drawer_root)
        .drawerLeftView(menuView)
        .drawerLeftWidth(Utils.dpToPx(300))
        .withNavigationIconToggler(getToolbar())
        .drawerListener(new DrawerLayout.SimpleDrawerListener() {
        })
        .build();
```

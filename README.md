# TestMultidex102

> Error:Conflict with dependency 'com.android.support:multidex' in project ':app'. Resolved versions for app (1.0.2) and test app (1.0.1) differ. See http://g.co/androidstudio/app-test-app-conflict for details.

Fix by doing:

    compile 'com.android.support:multidex:1.0.2'
    androidTestCompile 'com.android.support:multidex:1.0.2'

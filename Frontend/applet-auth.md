This is a service for authentication.

If user not yet log in, applet can redirect to applet-auth page, after user log in, applet-auth will redirect back to applet page.

Usage

```
window.location.href = `https://auth.applets.group?redirectUrl=${location.href}`
```
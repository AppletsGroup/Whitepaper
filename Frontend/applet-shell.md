We want to avoid AI start an applet from scrach, and let AI only focus the special requirements.
So we abstract a applet-shell to contain some duplicate and common work.

This shell contains:
- Navigation layout, for example, Drawer Navigation or Bottom Tabs Navigation
- Toast, can use Toast directly with out additional config
- Current user status, whether login, profile data

Feature
- Mobile First, but also support PC, write once, run everywhere
# ep_desktop_notifications

Get notifications on your desktop when someone sends a chat message to your pad.
No matter, if you are on another browser tab or if you've minimized your browser.

Works on Chrome and on Firefox. Should work fine in all webkit browsers.

See the [compatibility table] to see which browsers support native desktop notifications.
For other browsers there might be add-ons.

# HOW TO USE (tm)

When loading a pad, desktop notifications are enabled by default.
Notifications can be disabled for each pad via the pad's settings.

You can change the initial state:

* with a settings entry:
    * `"ep_desktop_notifications_default": false,`
* or with an URL parameter:
    * http://URL?DesktopNotifications=false

The first time you open a pad with activated desktop notifications,
your browser asks for your permission to show notifications.
This permission is valid for the given host running your etherpad service.
You can change or reset the permission anytime in your browser settings
(e.g. for Firefox: Page Info/Ctrl-I - Permissions - Show Notifications).


# TODO

* Test URL parameter feature.

# WHY

Etherpad-lite is a perfect match for small distributed
project teams and deserves a much bigger user base.

The plugin ep_desktop_notifications (in combination
with e.g. ep_real_time_chat, ep_headings and ep_markdown)
is an important step towards world dominance. ;-)


[compatibility table]: https://developer.mozilla.org/en-US/docs/Web/API/notification#Browser_compatibility

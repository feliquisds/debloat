# debloat stuff

## some package info:
- **com.sec.android.provider.badge:** required for DeX
 
- **com.samsung.android.dkey:** required(?) for Samsung Wallet

- **com.android.uwb.resources** and **com.sec.android.emergencylauncher:** uninstalling causes bootloop, disabling seems fine

- **com.samsung.android.photoremasterservice:** required for the little pill pop-ups in the gallery to appear (remaster, live effect, colorize, background blur etc)

- **com.samsung.android.scs:** required for hiding specific apps in the app drawer

- **com.samsung.android.scpm:** required for Quick Share to recognize your own devices (like your Galaxy Book logged into your account) and share stuff quicker

- **com.samsung.android.vexfwk.service:** uninstalling it seems to really slow down Samsung's gallery app in One UI 8.5

- **com.samsung.android.wifi.softap\*.resources:** required for certain hotspot features (WPA3, 6GHz etc)

- **com.android.companiondevicemanager:** required for setting up Galaxy Buds (Buds4 onwards i think) and other similar devices

- **com.samsung.internal.systemui.navbar.gestural_no_hint:** required for gesture navigation (without hint), interestingly you do not need *com.android.internal.systemui.navbar.gestural* (gesture navigation from stock Android i assume?) or *com.samsung.internal.systemui.navbar.sec_gestural_no_hint* (i imagine *sec* means secure? but it didn't affect anything)

- **com.samsung.android.aicore:** required for on-device AI to work

- **com.samsung.android.mobileservice:** required for group sharing features and for Quick Share to work between your contacts

- **com.google.android.cellbroadcastreceiver, com.google.android.cellbroadcastservice, com.google.android.overlay.modules.cellbroadcastreceiver, and com.google.android.overlay.modules.cellbroadcastservice:** required for emergency/OTA alerts (like heavy weather and whatnot), not sure if all of these are required at once, needs more testing

- **com.samsung.euicc:** required for SIM Manager to not hang and be able to load SIMs

- **com.sec.phone:** required for adding eSIMs
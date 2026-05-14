# debloat stuff

## some package info:
- **com.sec.android.provider.badge:** required for DeX
 
- **com.samsung.android.dkey:** required(?) for Samsung Wallet
 
- **com.samsung.android.intellivoiceservice:** required for document scanning in the camera

- **com.android.uwb.resources** and **com.sec.android.emergencylauncher:** uninstalling causes bootloop, disabling seems fine

- **com.samsung.android.photoremasterservice:** required for the little pill pop-ups in the gallery to appear (remaster, live effect, colorize, background blur etc)

- **com.samsung.android.visual.cloudcore:** required for generative fill and photo remaster to work properly

- **com.samsung.android.scs:** required for hiding specific apps in the app drawer

- **com.samsung.android.scpm:** required for Quick Share to recognize your own devices (like your Galaxy Book logged into your account) and share stuff quicker

- **com.samsung.android.vexfwk.service:** uninstalling it seems to really slow down Samsung's gallery app in One UI 8.5

- **com.samsung.android.wifi.softap\*.resources:** required for certain hotspot features (WPA3, 6GHz etc)

- **com.android.companiondevicemanager:** required for setting up Galaxy Buds (Buds4 onwards i think)

- **com.samsung.internal.systemui.navbar.gestural_no_hint:** required for gesture navigation (without hint), interestingly you do not need *com.android.internal.systemui.navbar.gestural* (gesture navigation from stock Android i assume?) or *com.samsung.internal.systemui.navbar.sec_gestural_no_hint* (i imagine *sec* means secure? but it didn't affect anything)

- **com.samsung.android.aicore:** required for on-device AI to work
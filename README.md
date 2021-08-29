# Firefox Tweaks

Firefox

Running firefox as user-

    [user@dom0 ~]$ qvm-run -a fedora-34-dvm firefox-esr

about:config


    app.normandy.enabled - false
    
    app.normandy.first_run - false
    
    app.normandy.api_url - blank
    
    beacon.enabled - false
    
    media.peerconnection.enabled - false

    media.peerconnection.use_document_iceservers - false 

    media.eme.enabled = false

    media.navigator.enabled = false

    browser.cache.disk.enable = false

    browser.cache.offline.enable = false

    browser.cache.disk.capacity = 0

    browser.cache.offline.capacity = 0
    
    browser.send_pings - false

    browser.send_pings.require_same_host - true

    browser.search.geoSpecificDefaults - false

    browser.search.geoSpecificDefaults.url - (blank)

    browser.search.geoip.url - (blank)

    browser.urlbar.speculativeConnect.enabled - false
    
    privacy.donottrackheader.enabled - true

    privacy.donottrackheader.value - 1

    privacy.trackingprotection.enabled - true 
    
    privacy.resistFingerprinting = true

    privacy.trackingprotection.fingerprinting.enabled = true

    privacy.trackingprotection.cryptomining.enabled = true

    privacy.firstparty.isolate = true

    geo.enabled - false

    geo.wifi.uri - (blank) 
    
    geo.provider.network.url - blank
 
    toolkit.telemetry.enabled - false

    toolkit.telemetry.server - (blank) 
    
    webgl.disabled - true

    dom.event.clipboardevents.enabled = false
    
    dom.ipc.plugins.flash.subprocess.crashreporter.enabled = false
    
    dom.battery.enabled - false

    network.dns.disablePrefetch - true

    network.prefetch-next - false

    network.dns.disableIPv6 - true

    network.cookie.cookieBehavior = 4

    network.cookie.lifetimePolicy = 2

    network.security.esni.enabled = true
    
    network.http.speculative-parallel-limit = 0
    
    network.captive-portal-service.enabled - false
    
    network.IDN_show_punycode - true
    
    captivedetect.canonicalURL - blank
    
    layout.css.visited_links_enabled - false
    
    device.sensors.enabled - false
    
    dom.security.https_only_mode = true

    dom.security.https_only_mode_ever_enabled = true


Optional    
    
    network.trr.mode = 3
    
    network.trr.custom_uri = https://dns.nextdns.io/xxxxxx  (replace with your ID)
    
    network.trr.resolver = https://dns.nextdns.io/xxxxxx
    



about:preferences


Check following and Do as following if required


Disable Play DRM controlled Content

Change HomePage and NewTabs to Blank

Disable every Entry of Firefox Home Content

Change Default search engine to Searx private instance if you don't have any then to Qwant.

Disable Search Suggestions

Set Enahanced Tracking Protection to Strict.

Set Do not track Parameter to Always

Set to Delete Cookies and Site Data to clean when Firefox Closes.

Disable Logins and Password Storage

Set Firefox not to Remember History.

Set Address Bar to suggest nothing.

Disable Every entry in Firefox Data collection and Telemetry.

Check settings in DNS over https.

Privacy & Security > Permissions > Block location, microphone etc.



Add-ons

   ublock origin, Decentraleyes

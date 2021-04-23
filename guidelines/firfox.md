# Preparation Firefox (Speeding up and other).

### ~~Release: 87.0 March 23, 2021~~

<details>
<summary><b>Resetting RAM in minimized mode</b></summary>

    enter link: about: config
    add new value, key type boolean: config.trim_on_minimize
    set key: true
    restart Firefox.

    The payback for this may be slowing down the browser's "recovery"

</details>

<details>

<summary><b>Disabling the storage of the rendered page in RAM</b></summary>

    enter link: about: config
    search value: browser.cache.memory.enable
    set key: false
    restart Firefox.

</details>

<details>

<summary><b>Disable session caching of last visited pages</b></summary>

    enter link: about: config
    search value: browser.sessionhistory.max_total_viewers
    set key: 20
    restart Firefox.

</details>

<details>

<summary><b>Number of memorized steps Forward and Backward</b></summary>

    enter link: about: config
    search value: browser.sessionhistory.max_entries
    set key: 25
    restart Firefox.

    Default: 50

</details>

<details>

<summary><b>Increasing the number of requests</b></summary>

    enter link: about: config
    search value: network.http.pacing.requests.burst
    set key: 20
    restart Firefox.

</details>

<details>

<summary><b>Tracking Protection</b></summary>

    enter link: about: config
    search value: privacy.trackingprotection.enabled
    set key: true
    restart Firefox.

</details>

<details>

<summary><b>Enable HTTP/3 next major version of the Hypertext Transfer Protocol</b></summary>

    enter link: about: config
    search value: network.http.http3.enabled
    set key: true
    restart Firefox.

</details>

<details>

<summary><b>Search suggestions</b></summary>

    enter link: about: config
    search value: browser.search.suggest.enabled
    set key: false
    restart Firefox.

> Everything typed in the search bar is sent to the search engine. After disabling this option, the suggestions will continue to work, but only based on the local search history.

</details>

<details>

<summary><b>Protection against surveillance by websites</b></summary>

    enter link: about: config
    search value: privacy.trackingprotection.enabled
    set key: true
    restart Firefox.

</details>

<details>

<summary><b>Changing the number of content processes</b></summary>

    enter link: about: config
    search value: dom.ipc.processCount
    set key: 10
    restart Firefox.

    Default: 8

</details>

<details>

<summary><b>Disabling unnecessary animations</b></summary>

    enter link: about: config
    create bollean value: toolkit.cosmeticAnimations.enabled
    set key: false
    restart Firefox.

</details>

<details>

<summary><b>Minimum tab width</b></summary>

    enter link: about: config
    search value: browser.tabs.tabMinWidth
    set key: 100
    restart Firefox.

    Default: 76

</details>

<details>

<summary><b>Increasing script execution time</b></summary>

    enter link: about: config
    search value: dom.max_script_run_time
    set key: 10
    restart Firefox.

    Default: 20

</details>

<details>

<summary><b>Changing the size of the disk cache</b></summary>

    enter link: about: config
    search value: browser.cache.disk.capacity
    set key: 65536
    restart Firefox.

    Default: 1048576 in kilobytes

</details>

<details>

<summary><b>One scale for all sites</b></summary>

    enter link: about: config
    search value: browser.zoom.siteSpecific
    set key: true
    restart Firefox.

    Default: true

</details>

<details>

<summary><b>View the source code in any editor</b></summary>

    enter link: about: config

    search value: view_source.editor.external
    set key: true

    Default: false

    search value: view_source.editor.path
    set key: gedit

    Default: empty

    restart Firefox.

</details>

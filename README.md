# volumio-lms-plugin

Manage Logitech Media Server in Volumio (Updated to use Lyrion community server)
xw
**tested on RPI only**

The button for the webconsole does not currently work as I cannot figure out how to call the volumio host device

Installation can be done when PRs into Volumio are accepted.

Manual installation is possible:

1. get the archive `wget https://github.com/jam1401/volumio-lms-plugin/blob/main/lms.zip`
2. create directory for plugin `mkdir lms`
3. unpack the archive `miniunzip lms.zip -d lms`
4. `cd lms`
5. Install the plugin `volumio plugin install`

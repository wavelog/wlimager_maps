# WIaaS - Wavelog mapImage as a Service

## Masterlist for the Wavelog-Imager.

If you want your automatic rendered Picture, create a PR with your Call and the URL against maps.json or simply contact some of the collaborators.

## Prerequisites:
* Your Wavelog must be connected to the Internet. If you protected it with a firewall, we can provide you with IPs for which it must be accessible
* You need to create a "slug" at Station-Setup and configure an "Exportmap"
* That exportmap must be accessible

## Notes
* It may take up to one hour until the first map is rendered after your PR is merged here.
* WIaaS is **highly experimental** currently. We reserve the right to remove your slug, if there's a problem with it.
  * If this happens, we're going to contact you (if you provided contact informations)
* WIaaS checks every 10minutes for updates on your wavelog (New QSOs).
  * If there's a new QSO, the map will be rendered.
  * If theres no update on your side, the old Map will be cached.

## Output
* You'll get a short URL which spits out a png. That one can easily be embedded into static-sites like qrz.com, hamqth or whatever you want.
* Example:

![image of last-qsos - example](https://images.wavelog.org/img/map?call=dj7nt)

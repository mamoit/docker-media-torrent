# Series and Movies downloader stack

This uses pymedusa, radarr and transmission to streamline the download of
series and movies.

Configuration of each service is needed, so you'll need to configure
transmission's api token and add it to radarr and pymedusa.

Feel free to improve upon this.

## Restriction bypass

Some countries have DNS blockades in place, so this uses cloudflare's dns
servers to mitigate those same restrictions.


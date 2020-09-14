Nginx WebDav configuration
==========================

There is support for WebDav in Nginx via the
[ngx_http_dav](http://nginx.org/en/docs/http/ngx_http_dav_module.html)
module. It's extended by the
[nginx_dav_ext](https://github.com/arut/nginx-dav-ext-module)
module to add a load of extra methods. Both of these can be used
to set up a WebDav server. However, none the WebDav clients built
into common operating systems seem to follow the WebDav spec
exactly, which means it's still hard to get them all talking to
the same WebDav server.

The config here at least allows WebDav operation from Linux
(Ubuntu tested), Windows and MacOS. It also works with apps on
Android and Apple IOS. This makes is rather convenient for
transferring files between different people on different systems.

There's no file access permission support here at the moment, so
as long as someone has access to WebDav (and Nginx has filesystem
permission) then they can do anything. That makes it more suitable
for private file transfers for the time being.

A lot of the configuration here has been collected from different
similar configurations on the web, each working for one particular
client. I couldn't find anything that works on multiple clients
hence pulling this together.

Basic instructions
------------------

The files here are all just Nginx config files. They fit into the
`/etc/nginx` directory structure used on Debian-based systems.

As well as Nginx itself the system will need the two modules
mentioned above installed, as well as
[ngx_headers_more](https://github.com/openresty/headers-more-nginx-module).
On Debian systems do

    apt-get install nginx-full \
                    libnginx-mod-http-dav-ext \
                    libnginx-mod-http-headers-more-filter

Clients
-------

There are instructions for different clients in
[connect.md](connect.md).

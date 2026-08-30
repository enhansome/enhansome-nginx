# Awesome Nginx with stars

A curated list of awesome nginx distributions, third party modules, active developers and so forth.

If you want to contribute, please submit a pull request.

Feel free to add your project :)

# Table of Contents

* [Well-known Distributions](#well-known-distributions)
* [Embeddable Scripting Languages](#embeddable-scripting-languages)
* [Third Party Modules](#third-party-modules)
  * [C Modules](#c-modules)
  * [Rust Modules](#rust-modules)
  * [Lua Modules](#lua-modules)
* [Built-in Modules](#built-in-modules)
* [Njs Projects](#njs-projects)
* [Tools](#tools)
* [Tutorials](#tutorials)
* [Mailing Lists](#mailing-lists)
* [Forum](#forum)
* [Active Developers](#active-developers)

## Well-known Distributions

* [OpenResty](https://github.com/openresty/ngx_openresty) ⭐ 14,018 | 🐛 333 | 🌐 C | 📅 2026-08-24
* [Tengine](https://github.com/alibaba/tengine) ⭐ 13,343 | 🐛 501 | 🌐 C | 📅 2026-08-24
* [Angie](https://github.com/webserver-llc/angie) ⭐ 2,554 | 🐛 44 | 🌐 C | 📅 2026-08-26
* [NGINX](https://nginx.org/en/docs/install.html)
* [FreeNGINX](https://freenginx.org/)
* [MyGuard NGINX](https://deb.myguard.nl/nginx-modules/)
* [MyGuard Angie](https://deb.myguard.nl/angie-modules-optimized-extended/)

## Embeddable Scripting Languages

* [lua](https://github.com/openresty/lua-nginx-module) ⭐ 11,790 | 🐛 393 | 🌐 C | 📅 2026-08-24
* [clojure](https://github.com/nginx-clojure/nginx-clojure) ⭐ 1,084 | 🐛 34 | 🌐 Java | 📅 2026-08-10
* [mruby](https://github.com/matsumoto-r/ngx_mruby) ⭐ 997 | 🐛 21 | 🌐 C | 📅 2026-01-28
* [php](https://github.com/rryqszq4/ngx_php) ⭐ 318 | 🐛 3 | 🌐 C | 📅 2020-01-06
* [wasm](https://github.com/Kong/ngx_wasm_module) ⭐ 141 | 🐛 18 | 🌐 C | 📅 2026-02-03
* [javascript (njs)](https://nginx.org/en/docs/njs/)
* [perl](http://nginx.org/en/docs/http/ngx_http_perl_module.html)

## Builder

This is bash command line builder that uses this curated list to automate installing and compiling nginx

* [nginx-builder](https://github.com/gp187/nginx-builder) ⭐ 98 | 🐛 0 | 🌐 Shell | 📅 2017-11-15

## Third Party Modules

These modules are not distributed with the Nginx source.

### C Modules

* [nginx-rtmp-module](https://github.com/arut/nginx-rtmp-module) ⭐ 14,036 | 🐛 1,160 | 🌐 C | 📅 2024-12-24 - NGINX-based Media Streaming Server.
* [ngx\_openresty](https://github.com/openresty/ngx_openresty) ⭐ 14,018 | 🐛 333 | 🌐 C | 📅 2026-08-24 - Turning Nginx into a Full-fledged Web App Server.
* [lua-nginx-module](https://github.com/openresty/lua-nginx-module) ⭐ 11,790 | 🐛 393 | 🌐 C | 📅 2026-08-24 - Embed the Power of Lua into NGINX.
* [ngx\_pagespeed](https://github.com/apache/incubator-pagespeed-ngx) ⚠️ Archived - Automatic PageSpeed optimization module for Nginx.
* [nginx-module-vts](https://github.com/vozlt/nginx-module-vts) ⭐ 3,500 | 🐛 12 | 🌐 C | 📅 2026-08-16 - Nginx virtual host traffic status module.
* [ngx\_http\_google\_filter\_module](https://github.com/cuber/ngx_http_google_filter_module) ⭐ 3,356 | 🐛 37 | 🌐 C | 📅 2023-09-26 - Nginx Module for Google Mirror.
* [nginx\_http\_push\_module](https://github.com/slact/nginx_http_push_module) ⭐ 3,065 | 🐛 130 | 🌐 C | 📅 2026-06-09 - Turn NGiNX into an adept HTTP push server.
* [nginx-http-flv-module](https://github.com/winshining/nginx-http-flv-module) ⭐ 2,933 | 🐛 26 | 🌐 C | 📅 2026-08-19  - A media streaming server based on nginx-rtmp-module, provides HTTP-FLV.
* [nginx-push-stream-module](https://github.com/wandenberg/nginx-push-stream-module) ⭐ 2,229 | 🐛 15 | 🌐 C | 📅 2024-08-19 - A pure stream http push technology for your Nginx setup. Comet made easy and really scalable.
* [nginx\_upstream\_check\_module](https://github.com/yaoweibin/nginx_upstream_check_module) ⭐ 2,148 | 🐛 173 | 🌐 Perl | 📅 2023-12-23 - Health checks upstreams for nginx.
* [ngx\_http\_proxy\_connect\_module](https://github.com/chobits/ngx_http_proxy_connect_module) ⭐ 1,975 | 🐛 31 | 🌐 C | 📅 2024-08-18 - A forward proxy module for CONNECT request handling
* [nginx\_modSecurity](https://github.com/SpiderLabs/ModSecurity-nginx) ⭐ 1,849 | 🐛 70 | 🌐 Perl | 📅 2026-05-04 - ModSecurity is an open source, cross platform web application firewall (WAF) engine for Apache, IIS and Nginx that is developed by Trustwave's SpiderLabs.
* [headers-more-nginx-module](https://github.com/openresty/headers-more-nginx-module) ⭐ 1,783 | 🐛 52 | 🌐 C | 📅 2026-08-24 - Set, add, and clear arbitrary output headers.
* [nginx\_tcp\_proxy\_module](https://github.com/yaoweibin/nginx_tcp_proxy_module) ⭐ 1,645 | 🐛 107 | 🌐 C | 📅 2021-12-19 - add the feature of tcp proxy with nginx, with health check and status monitor.
* [echo-nginx-module](https://github.com/openresty/echo-nginx-module) ⭐ 1,193 | 🐛 32 | 🌐 C | 📅 2026-08-24 - An Nginx module for bringing the power of "echo", "sleep", "time" and more to Nginx's config file.
* [ngx\_http\_geoip2\_module](https://github.com/leev/ngx_http_geoip2_module) ⭐ 1,142 | 🐛 10 | 🌐 C | 📅 2024-04-02 - creates variables with values from the maxmind geoip2 databases based on the client IP (supports both IPv4 and IPv6).
* [ngx\_cache\_purge](https://github.com/FRiCKLE/ngx_cache_purge) ⭐ 1,094 | 🐛 47 | 🌐 C | 📅 2023-02-20 - nginx module which adds ability to purge content from FastCGI, proxy, SCGI and uWSGI caches.
* [nginx-clojure](https://github.com/nginx-clojure/nginx-clojure) ⭐ 1,084 | 🐛 34 | 🌐 Java | 📅 2026-08-10 - Nginx module for embedding Clojure or Java or Groovy programs, typically those Ring based handlers.
* [ngx\_devel\_kit](https://github.com/simpl/ngx_devel_kit) ⭐ 1,027 | 🐛 4 | 🌐 C | 📅 2025-02-20 - Nginx Development Kit - an Nginx module that adds additional generic tools that module developers can use in their own modules.
* [nginx-upload-module](https://github.com/fdintino/nginx-upload-module) ⭐ 1,003 | 🐛 56 | 🌐 C | 📅 2024-07-17 - A module for nginx web server for handling file uploads using multipart/form-data encoding (RFC 1867).
* [ngx\_mruby](https://github.com/matsumoto-r/ngx_mruby) ⭐ 997 | 🐛 21 | 🌐 C | 📅 2026-01-28 - ngx\_mruby - A Fast and Memory-Efficient Web Server Extension Mechanism Using Scripting Language mruby for nginx.
* [nginx-fancyindex](https://github.com/aperezdc/ngx-fancyindex) ⭐ 945 | 🐛 43 | 🌐 C | 📅 2026-02-23 - nginx fancy index module.
* [redis2-nginx-module](https://github.com/openresty/redis2-nginx-module) ⭐ 905 | 🐛 28 | 🌐 C | 📅 2026-08-24 - Nginx upstream module for the Redis 2.0 protocol.
* [ngx\_http\_dyups\_module](https://github.com/yzprofile/ngx_http_dyups_module) ⚠️ Archived - update upstreams' config by restful interface.
* [nginx-http-concat](https://github.com/alibaba/nginx-http-concat) ⭐ 863 | 🐛 34 | 🌐 C | 📅 2020-12-11 - A Nginx module for concatenating files in a given context: CSS and JS files usually.
* [nginx-gridfs](https://github.com/mdirolf/nginx-gridfs) ⭐ 786 | 🐛 54 | 🌐 C | 📅 2013-12-10 - Nginx module for serving files from MongoDB's GridFS.
* [nginx-auth-ldap](https://github.com/kvspb/nginx-auth-ldap) ⭐ 759 | 🐛 151 | 🌐 C | 📅 2024-07-25 - LDAP authentication module for nginx.
* [ngx\_http\_substitutions\_filter\_module](https://github.com/yaoweibin/ngx_http_substitutions_filter_module) ⭐ 628 | 🐛 28 | 🌐 Perl | 📅 2022-01-24 - a filter module which can do both regular expression and fixed string substitutions for nginx.
* [ngx\_postgres](https://github.com/FRiCKLE/ngx_postgres) ⭐ 551 | 🐛 37 | 🌐 C | 📅 2020-09-29 - upstream module that allows nginx to communicate directly with PostgreSQL database.
* [testcookie-nginx-module](https://github.com/kyprizel/testcookie-nginx-module) ⭐ 532 | 🐛 14 | 🌐 C | 📅 2026-05-18 - simple robot mitigation module using cookie based challenge/response technique.
* [naxsi](https://github.com/wargio/naxsi) ⭐ 519 | 🐛 20 | 🌐 C | 📅 2026-08-07 - NAXSI is an open-source, high performance, low rules maintenance WAF for NGINX.
* [nginx-dav-ext-module](https://github.com/arut/nginx-dav-ext-module) ⭐ 511 | 🐛 32 | 🌐 C | 📅 2024-05-18 - NGINX WebDAV missing methods support (PROPFIND & OPTIONS).
* [nginx-upstream-fair](https://github.com/gnosek/nginx-upstream-fair) ⭐ 493 | 🐛 26 | 🌐 C | 📅 2020-01-12 - The fair load balancer module for nginx.
* [srcache-nginx-module](https://github.com/openresty/srcache-nginx-module) ⭐ 486 | 🐛 28 | 🌐 C | 📅 2026-08-24 - Transparent subrequest-based caching layout for arbitrary nginx locations.
* [ngx\_aws\_auth](https://github.com/anomalizer/ngx_aws_auth) ⭐ 475 | 🐛 41 | 🌐 C | 📅 2025-08-09 - nginx module to proxy to authenticated AWS services.
* [ngx\_small\_light](https://github.com/cubicdaiya/ngx_small_light) ⭐ 474 | 🐛 20 | 🌐 C | 📅 2024-07-16 - Dynamic Image Transformation Module For nginx.
* [nginx-upload-progress-module](https://github.com/masterzen/nginx-upload-progress-module) ⭐ 434 | 🐛 19 | 🌐 C | 📅 2025-03-15 - Nginx module implementing an upload progress system, that monitors RFC1867 POST uploads as they are transmitted to upstream servers.
* [set-misc-nginx-module](https://github.com/openresty/set-misc-nginx-module) ⭐ 402 | 🐛 18 | 🌐 C | 📅 2026-08-24 - Various set\_xxx directives added to nginx's rewrite module (md5/sha1, sql/json quoting, and many more).
* [drizzle-nginx-module](https://github.com/openresty/drizzle-nginx-module) ⭐ 335 | 🐛 14 | 🌐 C | 📅 2026-08-24 - an nginx upstream module that talks to mysql and drizzle by libdrizzle.
* [ngx\_php](https://github.com/rryqszq4/ngx_php) ⭐ 318 | 🐛 3 | 🌐 C | 📅 2020-01-06 - Embedded php script language for nginx-module.
* [nginx-otel](https://github.com/nginxinc/nginx-otel) ⭐ 271 | 🐛 20 | 🌐 C++ | 📅 2026-06-22 - Module providing support for OpenTelemetry distributed tracing.
* [ngx\_zeromq](https://github.com/FRiCKLE/ngx_zeromq) ⭐ 267 | 🐛 5 | 🌐 C | 📅 2014-12-29 - ZeroMQ transport for nginx.
* [replace-filter-nginx-module](https://github.com/openresty/replace-filter-nginx-module) ⭐ 263 | 🐛 12 | 🌐 C | 📅 2023-08-12 - Streaming regular expression replacement in response bodies.
* [nginx-tfs](https://github.com/alibaba/nginx-tfs) ⭐ 257 | 🐛 15 | 🌐 C | 📅 2022-05-22 - An Asynchronous Nginx module providing a RESTful API for TFS (Taobao File System).
* [zstd-nginx-module](https://github.com/tokers/zstd-nginx-module) ⭐ 257 | 🐛 30 | 🌐 C | 📅 2025-10-30 - Nginx modules for the Zstandard compression.
* [nginx-http-sysguard](https://github.com/alibaba/nginx-http-sysguard) ⭐ 254 | 🐛 5 | 🌐 C | 📅 2017-04-17 - A Nginx module to protect servers when system load or memory use goes too high.
* [nginx\_ajp\_module](https://github.com/yaoweibin/nginx_ajp_module) ⭐ 245 | 🐛 24 | 🌐 Perl | 📅 2024-02-20 - support AJP protocol proxy with Nginx.
* [nginx-c-function](https://github.com/Taymindis/nginx-c-function) ⭐ 234 | 🐛 3 | 🌐 C | 📅 2021-07-22 - It is a NGINX module that allow you to link your .so(c/c++) application in server context and call the function of .so application in location directive.
* [memc-nginx-module](https://github.com/openresty/memc-nginx-module) ⭐ 213 | 🐛 11 | 🌐 C | 📅 2026-08-24 - An extended version of the standard memcached module that supports set, add, delete, and many more memcached commands..
* [nginx-video-thumbextractor-module](https://github.com/wandenberg/nginx-video-thumbextractor-module) ⭐ 208 | 🐛 2 | 🌐 C | 📅 2026-04-08 - Nginx module to extract thumbs from a video file.
* [encrypted-session-nginx-module](https://github.com/openresty/encrypted-session-nginx-module) ⭐ 203 | 🐛 19 | 🌐 C | 📅 2026-08-24 - encrypt and decrypt nginx variable values.
* [nginx-http-user-agent](https://github.com/alibaba/nginx-http-user-agent) ⭐ 160 | 🐛 1 | 🌐 C | 📅 2019-05-04 - A nginx module to match browsers and crawlers.
* [rds-json-nginx-module](https://github.com/openresty/rds-json-nginx-module) ⭐ 154 | 🐛 4 | 🌐 C | 📅 2026-08-24 - An nginx output filter that formats Resty DBD Streams generated by ngx\_drizzle and others to JSON.
* [xss-nginx-module](https://github.com/openresty/xss-nginx-module) ⭐ 151 | 🐛 2 | 🌐 C | 📅 2026-08-24 - Native support for cross-site scripting (XSS) in an nginx.
* [nginx-audio-track-for-hls-module](https://github.com/flavioribeiro/nginx-audio-track-for-hls-module) ⚠️ Archived - Nginx module that generates audio track for HTTP Live Streaming (HLS) streams on the fly.
* [nginx-http-footer-filter](https://github.com/alibaba/nginx-http-footer-filter) ⚠️ Archived - A nginx module that prints some text in the footer of a request.
* [nginx-selective-cache-purge-module](https://github.com/wandenberg/nginx-selective-cache-purge-module) ⭐ 128 | 🐛 4 | 🌐 C | 📅 2026-04-08 - A module to purge cache by GLOB patterns..
* [form-input-nginx-module](https://github.com/calio/form-input-nginx-module) ⭐ 119 | 🐛 3 | 🌐 Perl | 📅 2017-10-27 - This is a nginx module that reads HTTP POST and PUT request body encoded in "application/x-www-form-urlencoded", and parse the arguments in request body into nginx variables..
* [ngx\_security\_headers](https://github.com/GetPageSpeed/ngx_security_headers) ⭐ 118 | 🐛 5 | 🌐 C | 📅 2026-06-13 - NGINX Module for sending security headers.
* [ngx\_http\_subrange\_module](https://github.com/Qihoo360/ngx_http_subrange_module) ⭐ 109 | 🐛 2 | 🌐 C | 📅 2018-04-09 - Split one big HTTP/Range request to multiple subrange requesets.
* [nginx-http-slice](https://github.com/alibaba/nginx-http-slice) ⭐ 106 | 🐛 3 | 🌐 C | 📅 2013-05-01 - Nginx module for serving a file in slices (reverse byte-range).
* [ngx\_supervisord](https://github.com/FRiCKLE/ngx_supervisord) ⭐ 100 | 🐛 1 | 🌐 C | 📅 2010-06-24 - nginx module providing API to communicate with supervisord and manage (start/stop) backends on-demand.
* [ngx\_http\_estreaming\_module](https://github.com/whatvn/ngx_http_estreaming_module) ⭐ 91 | 🐛 7 | 🌐 C | 📅 2026-05-07 - An adaptive hls streaming module for nginx.
* [nginx-eval-module](https://github.com/vkholodkov/nginx-eval-module) ⭐ 88 | 🐛 13 | 🌐 C | 📅 2020-04-01 - A module for evaluating memcached or proxy response into variable.
* [nginx-fluentd-module](https://github.com/fluent/nginx-fluentd-module) ⭐ 88 | 🐛 2 | 🌐 C | 📅 2019-02-13 - Nginx module for Fluentd data collector.
* [nginx-mogilefs-module](https://github.com/vkholodkov/nginx-mogilefs-module) ⭐ 85 | 🐛 6 | 🌐 C | 📅 2012-10-14 - MogileFS client for nginx.
* [nginx-hmac-secure-link](https://github.com/nginx-modules/nginx-hmac-secure-link) ⭐ 79 | 🐛 1 | 🌐 C | 📅 2026-04-25 - Alternative Nginx secure link module with support for MD5, SHA-1, and SHA-2 hashes.
* [nginx\_circle\_gif](https://github.com/evanmiller/nginx_circle_gif) ⚠️ Archived - this module generates simple circle images with the colors and size specified in the URL.
* [nginx-backtrace](https://github.com/alibaba/nginx-backtrace) ⭐ 70 | 🐛 1 | 🌐 C | 📅 2012-12-01 - A Nginx module to dump backtrace when a worker process exits abnormally.
* [array-var-nginx-module](https://github.com/openresty/array-var-nginx-module) ⭐ 68 | 🐛 2 | 🌐 C | 📅 2026-08-24 - Add support for array-typed variables to nginx config files.
* [ngx\_cache\_viewer](https://github.com/agile6v/ngx_cache_viewer) ⭐ 66 | 🐛 0 | 🌐 C | 📅 2013-11-28 - nginx module which adds ability to view cache node info from FastCGI, proxy, SCGI and uWSGI caches.
* [protobuf-nginx](https://github.com/dbcode/protobuf-nginx) ⭐ 58 | 🐛 0 | 🌐 C++ | 📅 2013-05-27 - Google Protocol Buffers code generator for nginx module developers.
* [nginx-cgi](https://github.com/pjincz/nginx-cgi) ⭐ 57 | 🐛 5 | 🌐 C | 📅 2026-08-03 - Module providing native CGI support, eliminating the need for fcgiwrap or other FastCGI adapters.
* [nginx\_ipset\_blacklist](https://github.com/Vasfed/nginx_ipset_blacklist) ⭐ 45 | 🐛 2 | 🌐 C | 📅 2016-04-16 - nginx module to use linux netfilter ipsets as blacklists.
* [nginx-markdown-module](https://github.com/gabrielfalcao/nginx-markdown-module) ⭐ 42 | 🐛 1 | 🌐 C | 📅 2011-02-11 - renderize markdown as HTML directly from your upstream server.
* [ngx\_http\_php\_session](https://github.com/replay/ngx_http_php_session) ⭐ 37 | 🐛 0 | 🌐 C | 📅 2012-04-26 - nginx module to parse php sessions.
* [ngx\_http\_avatars\_gen\_module](https://github.com/dizballanze/ngx_http_avatars_gen_module) ⭐ 34 | 🐛 2 | 🌐 C | 📅 2018-07-26 - Nginx module for on-the-fly generating of avatars based on user initials.
* [iconv-nginx-module](https://github.com/calio/iconv-nginx-module) ⭐ 33 | 🐛 2 | 🌐 C | 📅 2018-10-10 - a character conversion nginx module using libiconv.
* [tcp-nginx-module](https://github.com/laocai/tcp-nginx-module) ⭐ 30 | 🐛 2 | 🌐 C | 📅 2014-11-20 - Use nginx as a common TCP server framework.
* [nginx-udplog-module](https://github.com/vkholodkov/nginx-udplog-module) ⭐ 29 | 🐛 3 | 🌐 C | 📅 2011-07-09 - Implementation of logging using BSD Syslog Protocol for nginx (RFC 3164).
* [nginx-hmux-module](https://github.com/wangbin579/nginx-hmux-module) ⭐ 28 | 🐛 2 | 🌐 C | 📅 2024-08-20 - The module implements resin's hmux protocol in nginx.
* [nginx-zstd-module](https://github.com/myguard-labs/nginx-zstd-module) ⭐ 28 | 🐛 4 | 🌐 C | 📅 2026-08-30 - Zstandard (zstd) compression and decompression filters for nginx responses.
* [ngx\_lfqueue](https://github.com/Taymindis/ngx_lfqueue) ⭐ 27 | 🐛 0 | 🌐 C | 📅 2018-09-21 - a lock free queue(enq/deq) container running on nginx share memory and it enqueue/dequeue the messages across multiple threads and multiple workers without any locking.
* [ngx-gm-filter](https://github.com/liseen/ngx-gm-filter) ⭐ 26 | 🐛 1 | 🌐 C | 📅 2024-04-12 - Another image filter based GraphicsMagick..
* [ngx-ip2location](https://github.com/chaizhenhua/ngx-ip2location) ⭐ 23 | 🐛 2 | 🌐 C | 📅 2022-11-27 - Nginx IP2Location Module.
* [nginx-elastic-client](https://github.com/Taymindis/nginx-elastic-client) ⭐ 23 | 🐛 0 | 🌐 C | 📅 2018-04-27 - To structure your elastic client command in your nginx proxy for multiple elasticsearch server.
* [rds-csv-nginx-module](https://github.com/openresty/rds-csv-nginx-module) ⭐ 21 | 🐛 2 | 🌐 C | 📅 2026-08-24 - Nginx output filter module to convert Resty-DBD-Streams (RDS) to Comma-Separated Values (CSV).
* [couchbase-nginx-module](https://github.com/couchbaselabs/couchbase-nginx-module) ⭐ 21 | 🐛 0 | 🌐 C | 📅 2013-09-17 - The module for nginx webserver to access Couchbase Server.
* [nginx-http-auth-totp](https://github.com/61131/nginx-http-auth-totp) ⭐ 21 | 🐛 1 | 🌐 C | 📅 2026-05-04 - Time-based one-time password (TOTP) authentication for Nginx
* [modjpeg-nginx](https://github.com/ioppermann/modjpeg-nginx) ⭐ 19 | 🐛 1 | 🌐 C | 📅 2024-10-02 - Filter module for adding overlays and logos to JPEGs on-the-fly without degrading the quality of the image.
* [nginx-module-url](https://github.com/vozlt/nginx-module-url) ⭐ 18 | 🐛 0 | 🌐 C | 📅 2022-09-06 - Nginx url encoding converting module.
* [nginx-nonewlines](https://github.com/vedang/nginx-nonewlines) ⭐ 18 | 🐛 0 | 🌐 C | 📅 2011-04-03 - This is an nginx module to strip the served HTML of all newlines (\n and \r characters).
* [ngx\_dynamic\_etag](https://github.com/dvershinin/ngx_dynamic_etag) ⭐ 18 | 🐛 0 | 🌐 Perl | 📅 2026-08-15 - NGINX module for adding ETag to dynamic content.
* [ngx\_trace](https://github.com/zzzcpan/ngx_trace) ⭐ 16 | 🐛 0 | 🌐 Perl | 📅 2012-01-04 - runtime call tracer for nginx.
* [nginx-access-plus](https://github.com/nginx-clojure/nginx-access-plus) ⭐ 14 | 🐛 0 | 🌐 C | 📅 2024-08-10 - nginx module allows limiting access to certain http request methods and client addresses.
* [nginx-sticky-module](https://github.com/yaoweibin/nginx-sticky-module) ⭐ 14 | 🐛 2 | 🌐 C | 📅 2012-08-10 - A nginx module to add an upstream server persistance using cookies.
* [Session-Binding-Proxy](https://github.com/wburgers/Session-Binding-Proxy) ⭐ 14 | 🐛 0 | 🌐 C | 📅 2022-09-05 - An Nginx module capable of binding the application session to the SSL session by encrypting the application cookie with a secret key and the SSL master key.
* [nginx\_mime\_magic\_module](https://github.com/FadedCoder/nginx-mime-magic-module) ⭐ 14 | 🐛 1 | 🌐 C | 📅 2021-11-21 - Another MIME guesser using libmagic with configurable Magic database path and fallback or compulsory mode.
* [ngx\_http\_qqwry\_module](https://github.com/anjuke/ngx_http_qqwry_module) ⭐ 13 | 🐛 1 | 🌐 C | 📅 2010-12-23 - A nginx module that creates variables with location info from QQWry.
* [ngx-stomp](https://github.com/Taymindis/ngx-stomp) ⭐ 13 | 🐛 0 | 🌐 C | 📅 2018-06-13 - A STOMP upstream module on nginx, STOMP is the Simple (or Streaming) Text Orientated Messaging Protocol.
* [nginx\_ocsp\_proxy-module](https://github.com/kyprizel/nginx_ocsp_proxy-module) ⭐ 11 | 🐛 0 | 🌐 C | 📅 2014-03-24 - Nginx OCSP processing module designed for response caching.
* [ngx\_lfstack](https://github.com/Taymindis/ngx_lfstack) ⭐ 11 | 🐛 1 | 🌐 C | 📅 2018-09-21 - a lock free stack(push/pop) container running on nginx share memory and it push/pop the messages across multiple threads and multiple workers without any locking.
* [url-protector-nginx-module](https://github.com/Trax-retail/url-protector-nginx-module) ⭐ 10 | 🐛 0 | 🌐 C | 📅 2017-09-19 - Nginx module which adds ability to decrypt strings encrypted with xxtea algorithm.
* [nginx-mod-so](https://github.com/hamano/nginx-mod-so) ⭐ 10 | 🐛 0 | 🌐 C | 📅 2014-02-05 - nginx\_mod\_so is dynamic loadable module for Nginx.
* [nginx-qrcode](https://github.com/alexchamberlain/nginx-qrcode) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2012-01-17 - Native QR encoding for Nginx Web Server.
* [nginx\_mod\_akamai\_g2o](https://github.com/refractalize/nginx_mod_akamai_g2o) ⭐ 7 | 🐛 0 | 📅 2016-08-08 - Nginx Module for Authenticating Akamai G2O requests.
* [nginx-autocert-module](https://github.com/myguard-labs/nginx-autocert-module) ⭐ 6 | 🐛 1 | 🌐 C | 📅 2026-08-24 - Automatic TLS certificates built into nginx — ACME/Let's Encrypt issuance and renewal, with wildcard, IP-address certs and TLS-ALPN-01.
* [nginx-error-abuse-module](https://github.com/eilandert/nginx-error-abuse-module) ⭐ 5 | 🐛 0 | 🌐 C | 📅 2026-08-20 - Ratelimits and bans clients making excessive error (404/403/5xx) requests; shared-memory counters, optional Redis for multi-server, returns 429 to banned clients.
* [nginx-xsltproc-module](https://github.com/yoreek/nginx-xsltproc-module) ⭐ 5 | 🐛 0 | 🌐 C | 📅 2021-01-11 - XSLT processor bases on Nginx.
* [nginx-dlg-auth](https://github.com/algermissen/nginx-dlg-auth) ⭐ 5 | 🐛 6 | 🌐 C | 📅 2014-06-06 - NGINX module for delegating authentication and authorization to an HTTP gateway.
* [nginx-error-abuse-module](https://github.com/myguard-labs/nginx-error-abuse-module) ⭐ 5 | 🐛 0 | 🌐 C | 📅 2026-08-20 - Watches error responses and bans clients that trigger repeated 4xx/5xx abuse.
* [ngx\_http\_gif\_magick](https://github.com/mschenck/ngx_http_gif_magick) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2022-07-16 - nginx http filter module for dynamically resizing gifs with ImageMagick.
* [waf-nginx-module](https://github.com/gsdu8g9/waf-nginx-module) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2015-09-07 - A lightweight web application firewall module for nginx..
* [ngx\_http\_guess\_mime\_module](https://github.com/ohnx/nginx-guess-mime) ⭐ 3 | 🐛 3 | 🌐 C | 📅 2019-02-15 - Guess the MIME type of files served using libmagic.
* [nginx-cache-turbo-module](https://github.com/myguard-labs/nginx-cache-turbo-module) ⭐ 3 | 🐛 1 | 🌐 C | 📅 2026-08-30 - Built-in full-page cache for nginx — a tiny Varnish living inside the worker.
* [ngx\_http\_stat\_check](https://github.com/mk-fg/nginx-stat-check) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2025-02-22 - Dynamic access blacklisting configuration via filesystem paths.
* [ngx\_http\_securelog\_module](https://github.com/no1xpert/ngx_http_securelog_module) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2026-06-09 - Real-time AES-256-GCM / GPG encrypted access logging. Plaintext never touches disk. SHA-256 key integrity verification at startup.
* [ngx\_status\_module](https://github.com/codebytes5/ngx_status_module) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2026-01-28 - Nginx mod status module similar to Apache plugin
* [nginx-http-sentinel-module](https://github.com/myguard-labs/nginx-http-sentinel-module) ⭐ 1 | 🐛 1 | 🌐 C | 📅 2026-08-10 - (experimental) PREACCESS module that scores every client from weighted signals and acts on the verdict — tarpit bots, block scanners, PoW-challenge grey-area requests.
* [nginx-http-est](https://github.com/61131/nginx-http-est) ⭐ 0 | 🐛 2 | 🌐 C | 📅 2024-05-20 - Enrollment over Secure Transport (EST) module for Nginx
* [nginx-http-filter-data](https://github.com/61131/nginx-http-filter-data) ⭐ 0 | 🐛 1 | 🌐 C | 📅 2024-12-30 - RFC 2397 "data" URL scheme filter module for Nginx
* [nginx-strip-filter-module](https://github.com/myguard-labs/nginx-strip-filter-module) ⭐ 0 | 🐛 1 | 🌐 C | 📅 2026-08-24 - Dynamic response-body minifier — strips newlines and redundant whitespace from HTML/CSS/JS responses.
* [nwall](https://github.com/coalaura/nwall) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2026-08-23 - Ultra-fast bot-spam filter that cuts resource usage by hard-closing requests via User-Agent and URI rules.
* [ngx\_sync\_msg\_module](https://github.com/yzprofile/ngx_sync_msg_module) - This module provides a mechanism to sync messages between workers for your module.
* [ngx\_immutable](https://github.com/GetPageSpeed/ngx_immutable) - NGINX module for setting immutable caching on static assets.

## Rust Modules

* [ngx-rust](https://github.com/nginxinc/ngx-rust) ⭐ 907 | 🐛 45 | 🌐 Rust | 📅 2026-08-28 - Rust bindings for Nginx modules.

### Lua Modules

* [ngx\_lua\_waf](https://github.com/loveshell/ngx_lua_waf) ⭐ 4,024 | 🐛 84 | 🌐 Lua | 📅 2024-03-17 - lua waf based on ngx\_lua.
* [lua-resty-http](https://github.com/pintsized/lua-resty-http) ⭐ 2,078 | 🐛 42 | 🌐 Lua | 📅 2026-08-11 - Lua HTTP client cosocket driver for OpenResty / ngx\_lua.
* [lua-resty-redis](https://github.com/openresty/lua-resty-redis) ⭐ 1,956 | 🐛 75 | 🌐 Lua | 📅 2026-08-24 - Lua redis client driver for the ngx\_lua based on the cosocket API.
* [lua-resty-template](https://github.com/bungle/lua-resty-template) ⭐ 923 | 🐛 15 | 🌐 Lua | 📅 2023-07-21 - Templating Engine (HTML) for Lua and OpenResty
* [lua-resty-core](https://github.com/openresty/lua-resty-core) ⭐ 853 | 🐛 71 | 🌐 Lua | 📅 2026-08-24 - New FFI-based API for lua-nginx-module.
* [lua-resty-kafka](https://github.com/doujiang24/lua-resty-kafka) ⭐ 813 | 🐛 83 | 🌐 Lua | 📅 2023-11-03 - Lua kafka client driver for the ngx\_lua based on the cosocket API.
* [lua-resty-mysql](https://github.com/openresty/lua-resty-mysql) ⭐ 726 | 🐛 54 | 🌐 Lua | 📅 2026-06-20 - Nonblocking Lua MySQL driver library for ngx\_lua.
* [lua-resty-upstream-healthcheck](https://github.com/openresty/lua-resty-upstream-healthcheck) ⭐ 544 | 🐛 47 | 🌐 Lua | 📅 2026-08-24 - Health Checker for Nginx Upstream Servers in Pure Lua.
* [lua-resty-jwt](https://github.com/SkyLothar/lua-resty-jwt) ⭐ 538 | 🐛 37 | 🌐 Perl | 📅 2024-01-03 - JWT For The Great Openresty.
* [lua-resty-websocket](https://github.com/openresty/lua-resty-websocket) ⭐ 523 | 🐛 32 | 🌐 Lua | 📅 2026-08-24 - WebSocket support for the ngx\_lua module (and OpenResty).
* [lua-upstream-nginx-module](https://github.com/openresty/lua-upstream-nginx-module) ⭐ 512 | 🐛 27 | 🌐 C | 📅 2026-08-24 - Nginx C module to expose Lua API to ngx\_lua for Nginx upstreams.
* [lua-resty-logger-socket](https://github.com/cloudflare/lua-resty-logger-socket) ⭐ 494 | 🐛 36 | 🌐 Raku | 📅 2026-04-24 - Raw-socket-based Logger Library for Nginx.
* [lua-resty-lrucache](https://github.com/openresty/lua-resty-lrucache) ⭐ 460 | 🐛 15 | 🌐 Lua | 📅 2026-07-17 - Lua-land LRU Cache based on LuaJIT FFI.
* [lua-resty-string](https://github.com/openresty/lua-resty-string) ⭐ 443 | 🐛 26 | 🌐 Lua | 📅 2026-08-24 - String utilities and common hash functions for ngx\_lua and LuaJIT.
* [lua-resty-upload](https://github.com/openresty/lua-resty-upload) ⭐ 414 | 🐛 19 | 🌐 Lua | 📅 2026-08-24 - Streaming reader and parser for http file uploading based on ngx\_lua cosocket.
* [lua-resty-cookie](https://github.com/cloudflare/lua-resty-cookie) ⚠️ Archived - Lua library for HTTP cookie manipulations for OpenResty/ngx\_lua.
* [lua-resty-session](https://github.com/bungle/lua-resty-session) ⭐ 343 | 🐛 26 | 🌐 Lua | 📅 2026-08-24 - Session library for OpenResty implementing Secure Cookie Protocol.
* [lua-resty-dns](https://github.com/openresty/lua-resty-dns) ⭐ 338 | 🐛 17 | 🌐 Lua | 📅 2026-08-24 - DNS resolver for the nginx lua module.
* [lua-resty-lock](https://github.com/openresty/lua-resty-lock) ⭐ 323 | 🐛 9 | 🌐 Lua | 📅 2026-08-26 - Simple nonblocking lock API for ngx\_lua based on shared memory dictionaries.
* [lua-resty-rsa](https://github.com/doujiang24/lua-resty-rsa) ⭐ 268 | 🐛 11 | 🌐 Lua | 📅 2024-11-09 - RSA encrypt/decrypt & sign/verify for LuaJIT.
* [lua-resty-memcached](https://github.com/openresty/lua-resty-memcached) ⭐ 216 | 🐛 8 | 🌐 Lua | 📅 2026-08-24 - Lua memcached client driver for the ngx\_lua based on the cosocket API.
* [lua-resty-rabbitmqstomp](https://github.com/wingify/lua-resty-rabbitmqstomp) ⭐ 194 | 🐛 3 | 🌐 Lua | 📅 2020-04-27 - Opinionated Lua RabbitMQ client library for the ngx\_lua apps based on the cosocket API.
* [lua-resty-nettle](https://github.com/bungle/lua-resty-nettle) ⭐ 186 | 🐛 5 | 🌐 Lua | 📅 2023-06-08 - LuaJIT FFI bindings for Nettle (a low-level cryptographic library).
* [LuaWeb](https://github.com/torhve/LuaWeb) ⭐ 179 | 🐛 1 | 🌐 Lua | 📅 2014-12-27 - A very simple blog engine using openresty, nginx, lua, markdown, git and redis.
* [lua-resty-json](https://github.com/cloudflare/lua-resty-json) ⭐ 178 | 🐛 4 | 🌐 C | 📅 2026-04-24 - json lib for lua and C.
* [lua-resty-hmac](https://github.com/jkeys089/lua-resty-hmac) ⭐ 172 | 🐛 2 | 🌐 Perl | 📅 2023-05-31 - HMAC functions for ngx\_lua and LuaJIT.
* [lua-resty-limit-req](https://github.com/timebug/lua-resty-limit-req) ⭐ 170 | 🐛 2 | 🌐 Perl | 📅 2026-06-01 - Limit the request processing rate between multiple NGINX instances.
* [lua-resty-validation](https://github.com/bungle/lua-resty-validation) ⭐ 155 | 🐛 2 | 🌐 Lua | 📅 2021-08-31 - Validation Library (Input Validation and Filtering) for Lua and OpenResty.
* [lua-resty-shell](https://github.com/juce/lua-resty-shell) ⭐ 148 | 🐛 3 | 🌐 Lua | 📅 2022-09-28 - tiny subprocess/shell library to use with OpenResty application server.
* [nginx-google-oauth](https://github.com/agoragames/nginx-google-oauth) ⭐ 141 | 🐛 10 | 🌐 Lua | 📅 2021-03-11 - Lua module to add Google OAuth to nginx.
* [lua-resty-consul](https://github.com/hamishforbes/lua-resty-consul) ⭐ 130 | 🐛 1 | 🌐 Perl | 📅 2021-08-18 - Library to interface with the consul HTTP API from ngx\_lua.
* [lua-resty-upstream](https://github.com/hamishforbes/lua-resty-upstream) ⭐ 116 | 🐛 3 | 🌐 Perl | 📅 2019-12-19 - Upstream connection load balancing and failover module for Openresty.
* [lua-resty-ssdb](https://github.com/LazyZhu/lua-resty-ssdb) ⭐ 101 | 🐛 6 | 🌐 Lua | 📅 2019-07-11 - Lua ssdb client driver for the ngx\_lua based on the cosocket API, SSDB is a leveldb server.
* [lua-resty-qless](https://github.com/pintsized/lua-resty-qless) ⭐ 97 | 🐛 3 | 🌐 Lua | 📅 2022-07-08 - Lua binding to Qless (Queue / Pipeline management) for OpenResty.
* [lua-redis-parser](https://github.com/openresty/lua-redis-parser) ⭐ 94 | 🐛 3 | 🌐 C | 📅 2026-05-14 - Lua module for parsing raw redis responses.
* [lua-resty-smtp](https://github.com/duhoobo/lua-resty-smtp) ⭐ 86 | 🐛 12 | 🌐 Lua | 📅 2021-02-28 - I must be crazy trying to send mail with Nginx..
* [lua-resty-rack](https://github.com/pintsized/lua-resty-rack) ⭐ 82 | 🐛 1 | 🌐 Lua | 📅 2012-08-09 - A simple and extensible HTTP server framework for OpenResty.
* [nginx-tcp-lua-module](https://github.com/bigplum/nginx-tcp-lua-module) ⭐ 71 | 🐛 7 | 🌐 Perl | 📅 2015-06-09 - A TCP server with lua supporting based on nginx.
* [lua-resty-cassandra](https://github.com/jbochi/lua-resty-cassandra) ⭐ 68 | 🐛 5 | 🌐 Lua | 📅 2017-06-09 - Pure Lua Cassandra client using CQL binary protocol.
* [lua-resty-postgres](https://github.com/azurewang/lua-resty-postgres) ⭐ 65 | 🐛 6 | 🌐 Lua | 📅 2022-04-18 - Nonblocking Lua PostgreSQL driver library for ngx\_lua.
* [lua-resty-woothee](https://github.com/woothee/lua-resty-woothee) ⭐ 65 | 🐛 0 | 🌐 Lua | 📅 2021-10-13 - Woothee Lua-Openresty implementation.
* [lua-resty-uuid](https://github.com/bungle/lua-resty-uuid) ⭐ 60 | 🐛 1 | 🌐 Lua | 📅 2026-05-07 - LuaJIT FFI bindings for libuuid, a DCE compatible Universally Unique Identifier library.
* [lua-resty-beanstalkd](https://github.com/smallfish/lua-resty-beanstalkd) ⭐ 59 | 🐛 1 | 🌐 Raku | 📅 2021-12-18 - non-blocking beanstalkd client lib for ngx\_lua.
* [lua-resty-random](https://github.com/bungle/lua-resty-random) ⭐ 59 | 🐛 2 | 🌐 Lua | 📅 2015-12-16 - LuaJIT FFI-based Random Library for OpenResty.
* [lua-resty-libcjson](https://github.com/bungle/lua-resty-libcjson) ⭐ 53 | 🐛 2 | 🌐 Lua | 📅 2016-11-25 - LuaJIT FFI-based cJSON library for OpenResty.
* [lua-resty-mongol](https://github.com/Olivine-Labs/resty-mongol) ⭐ 45 | 🐛 11 | 🌐 Perl | 📅 2020-04-29 - Lua MongoDB driver.
* [lua-resty-mobile](https://github.com/isage/lua-resty-mobile) ⭐ 34 | 🐛 1 | 🌐 Lua | 📅 2019-07-02 - Mobile detection for nginx/openresty.
* [lua-resty-murmurhash2](https://github.com/bungle/lua-resty-murmurhash2) ⭐ 30 | 🐛 0 | 🌐 Lua | 📅 2015-12-16 - LuaJIT MurmurHash 2 bindings to Nginx / OpenResty murmurhash2 implementation.
* [lua-resty-hoedown](https://github.com/bungle/lua-resty-hoedown) ⭐ 26 | 🐛 1 | 🌐 Lua | 📅 2015-12-16 - LuaJIT FFI bindings to Hoedown, a standards compliant, fast, secure markdown processing library in C.
* [lua-resty-gearman](https://github.com/zhhchen/lua-resty-gearman) ⭐ 26 | 🐛 2 | 🌐 Lua | 📅 2013-11-20 - Lua gearman client driver for the ngx\_lua based on the cosocket API.
* [lua-resty-riak](https://github.com/bakins/lua-resty-riak) ⭐ 26 | 🐛 3 | 🌐 Lua | 📅 2014-09-10 - Lua riak protocol buffer client driver for the ngx\_lua based on the cosocket API.
* [lua-resty-iputils](https://github.com/bakins/lua-resty-riak) ⭐ 26 | 🐛 3 | 🌐 Lua | 📅 2014-09-10 - Utility functions for working with IP addresses in Openresty.
* [lua-resty-fastcgi](https://github.com/benagricola/lua-resty-fastcgi) ⭐ 23 | 🐛 2 | 🌐 Lua | 📅 2017-09-28 - Lua FCGI client driver for ngx\_lua based on the cosocket API.
* [lua-resty-snappy](https://github.com/bungle/lua-resty-snappy) ⭐ 21 | 🐛 1 | 🌐 Lua | 📅 2015-12-16 - LuaJIT FFI bindings for Snappy, a fast compressor/decompressor.
* [lua-rds-parser](https://github.com/openresty/lua-rds-parser) ⭐ 20 | 🐛 1 | 🌐 C | 📅 2026-05-14 - Resty DBD Stream (RDS) parser for Lua written in C.
* [lua-resty-scrypt](https://github.com/bungle/lua-resty-scrypt) ⭐ 18 | 🐛 0 | 🌐 Lua | 📅 2017-07-06 - LuaJIT FFI-based scrypt library for OpenResty.
* [lua-resty-kyototycoon](https://github.com/cloudflare/lua-resty-kyototycoon) ⭐ 17 | 🐛 0 | 🌐 Perl | 📅 2013-12-06 - Lua client driver for KyotoTycoon using its native wire protocol (OpenResty/ngx\_lua).
* [lua-nginx-osm](https://github.com/miurahr/lua-nginx-osm) ⭐ 17 | 🐛 1 | 🌐 Lua | 📅 2014-04-13 - OpenStreetMap extension for Nginx Lua module.
* [lua-resty-libxl](https://github.com/bungle/lua-resty-libxl) ⭐ 16 | 🐛 2 | 🌐 Lua | 📅 2015-12-16 - LuaJIT FFI-based LibXL (Excel) library for OpenResty.
* [lua-resty-fileinfo](https://github.com/bungle/lua-resty-fileinfo) ⭐ 12 | 🐛 0 | 🌐 Lua | 📅 2015-12-16 - LuaJIT FFI bindings to libmagic, magic number recognition library - tries to determine file types.
* [lua-resty-dns-cache](https://github.com/hamishforbes/lua-resty-dns-cache) ⭐ 11 | 🐛 0 | 🌐 Perl | 📅 2017-04-19 - Cache wrapper for lua-resty-dns.
* [lua-resty-sass](https://github.com/bungle/lua-resty-sass) ⭐ 10 | 🐛 4 | 🌐 Lua | 📅 2017-02-17 - LuaJIT FFI bindings for libsass - A C/C++ implementation of a Sass compiler.
* [lua-resty-gettext](https://github.com/bungle/lua-resty-gettext) ⭐ 9 | 🐛 0 | 🌐 Lua | 📅 2015-12-16 - LuaJIT FFI-based gettext library for OpenResty.
* [lua-resty-kyototycoon](https://github.com/sjnam/lua-resty-kyototycoon) ⚠️ Archived - kyototycoon's binary protocol.
* [lua-resty-oceanbase](https://github.com/hugozhu/lua-resty-oceanbase) ⭐ 7 | 🐛 0 | 🌐 Lua | 📅 2012-12-28 - Lua OceanBase client driver for ngx\_lua based on the cosocket API.
* [lua-resty-github](https://github.com/jamesmarlowe/lua-resty-github) ⭐ 5 | 🐛 0 | 🌐 Lua | 📅 2014-10-23 - Lua library for using the github api in the ngx\_lua nginx module.
* [lua-resty-readurl](https://github.com/jamesmarlowe/lua-resty-readurl) ⭐ 5 | 🐛 1 | 🌐 Perl | 📅 2014-10-22 - Lua library for capturing urls, decoding, and logging results.
* [lua-resty-taglib](https://github.com/bungle/lua-resty-taglib) ⭐ 5 | 🐛 0 | 🌐 Lua | 📅 2015-12-16 - LuaJIT FFI bindings for TagLib - An Audio Meta-Data Library.
* [lua-resty-hipchat](https://github.com/jamesmarlowe/lua-resty-hipchat) ⭐ 3 | 🐛 0 | 🌐 Lua | 📅 2014-08-14 - Lua library for using the hipchat api.
* [lua-resty-fastdfs](https://github.com/azurewang) - Nonblocking Lua FastDFS driver library for ngx\_lua.

## Built-in Modules

For more details, see [nginx.org](http://nginx.org/en/docs/).

## Njs Projects

* [nginx-s3-gateway](https://github.com/nginxinc/nginx-s3-gateway) ⭐ 749 | 🐛 9 | 🌐 Shell | 📅 2026-08-30 - S3 gateway for Nginx allowing to proxy requests directly to S3 private buckets.
* [njs-examples](https://github.com/nginx/njs-examples) ⭐ 692 | 🐛 10 | 🌐 JavaScript | 📅 2026-06-25 - Examples of njs usage.
* [nginx-dns](https://github.com/TuxInvader/nginx-dns) ⭐ 223 | 🐛 23 | 🌐 JavaScript | 📅 2024-01-08 - Example njs configuration for using Nginx with DNS services.
* [njs-acme](https://github.com/nginx/njs-acme) ⭐ 95 | 🐛 27 | 🌐 TypeScript | 📅 2026-06-09 - ACME protocol implementation in njs allowing Let's Encrypt certificates to be issued directly from nginx.
* [njs-typescript-starter](https://github.com/jirutka/njs-typescript-starter) ⭐ 49 | 🐛 1 | 🌐 JavaScript | 📅 2023-07-02 - A starting template for developing njs (NGINX JavaScript) scripts for NGINX server in TypeScript.
* [babel-preset-njs](https://github.com/jirutka/babel-preset-njs) ⭐ 19 | 🐛 1 | 🌐 JavaScript | 📅 2023-05-19 - A Babel preset for njs - NGINX JavaScript.
* [mqtt5](https://github.com/gallarda/mqtt5) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2022-06-10 - MQTT 5.0 protocol parser implemented in njs.
* [nginx-njs-usecases](https://github.com/f5devcentral/nginx-njs-usecases) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2023-10-04 - A collection of njs use cases.
* [nginx-xml-json](https://github.com/lcrilly/nginx-xml-json) ⭐ 5 | 🐛 1 | 🌐 JavaScript | 📅 2021-05-21 - Proof-of-concept solution for presenting XML services as a JSON API.
* [njs-memory-profiler](https://github.com/4141done/njs-memory-profiler) ⭐ 1 | 🐛 1 | 🌐 JavaScript | 📅 2022-12-27 - Tool to understand per-request memory usage of njs scripts.
* [njs-types](https://npm.io/package/njs-types) - Provides type script type definitions for njs.
* [njs-prometheus-module](https://github.com/nginxinc/njs-prometheus-module) - Converts NGINX metrics exposed by the API module to a Prometheus format.

## Tools

* [nginx-proxy-manager](https://github.com/jc21/nginx-proxy-manager) ⭐ 34,024 | 🐛 899 | 🌐 TypeScript | 📅 2026-08-29 - Webinterface to manage nginx reverse-proxys with Letsencrypt support.

* [nginxconfig.io](https://nginxconfig.io) - [GitHub](https://github.com/valentinxxx/nginxconfig.io) ⭐ 28,266 | 🐛 71 | 🌐 JavaScript | 📅 2024-12-14 - Online nginx configuration generator for general purposes.

* [nginx-proxy](https://github.com/nginx-proxy/nginx-proxy) ⭐ 19,901 | 🐛 325 | 🌐 Python | 📅 2026-08-26 - Automated nginx proxy for Docker containers using docker-gen.

* [Laradock](https://github.com/laradock/laradock) ⭐ 12,673 | 🐛 16 | 🌐 Dockerfile | 📅 2026-08-16 - Full PHP development environment based on Docker, includes Nginx as one of its swappable services.

* [server-configs-nginx](https://github.com/h5bp/server-configs-nginx) ⭐ 11,561 | 🐛 1 | 📅 2026-06-20 - Nginx HTTP server boilerplate configs.

* [BunkerWeb](https://github.com/bunkerity/bunkerweb) ⭐ 10,883 | 🐛 157 | 🌐 Python | 📅 2026-08-28 - Open-source Web Application Firewall and reverse proxy based on NGINX.

* [ngxtop](https://github.com/lebinh/ngxtop) ⭐ 6,526 | 🐛 62 | 🌐 Python | 📅 2026-03-02 - Real-time metrics for nginx server.

* [veryNginx](https://github.com/alexazhou/VeryNginx) ⭐ 5,978 | 🐛 111 | 🌐 Lua | 📅 2020-06-30 - A very powerful and friendly nginx base on lua-nginx-module( openresty  ) which provide WAF, Control Panel, and Dashboards.

* [nginx-boilerplate](https://github.com/Umkus/nginx-boilerplate) ⭐ 2,438 | 🐛 1 | 🌐 Dockerfile | 📅 2018-07-26 - Awesome Nginx configuration template.

* [NPMplus](https://github.com/ZoeyVid/NPMplus) ⭐ 2,301 | 🐛 13 | 🌐 TypeScript | 📅 2026-08-30 - Docker container for managing Nginx proxy hosts with a simple, powerful interface

* [nginx-conf](https://github.com/lebinh/nginx-conf) ⭐ 2,116 | 🐛 2 | 📅 2017-10-13 - A collection of useful Nginx configuration snippets.

* [nginx-systemtap-toolkit](https://github.com/openresty/nginx-systemtap-toolkit) ⭐ 1,668 | 🐛 28 | 🌐 Perl | 📅 2023-03-14 - Real-time analyzing and diagnosing tools for Nginx based on SystemTap.

* [gixy-ng](https://github.com/dvershinin/gixy) ⭐ 1,182 | 🐛 0 | 🌐 Python | 📅 2026-08-29 - Nginx configuration static analyzer

* [nginx-autoinstall](https://github.com/angristan/nginx-autoinstall) ⭐ 646 | 🐛 41 | 🌐 Shell | 📅 2025-02-01 - Compile Nginx from source with custom modules on Debian and Ubuntu

* [nginx-opentracing](https://github.com/opentracing-contrib/nginx-opentracing) ⭐ 515 | 🐛 41 | 🌐 C++ | 📅 2026-08-30 - NGINX plugin for OpenTracing.

* [puppet-nginx](https://github.com/jfryman/puppet-nginx) ⭐ 468 | 🐛 106 | 🌐 Ruby | 📅 2026-07-27 - Puppet Module to manage NGINX on various UNIXes.

* [test-nginx](https://github.com/openresty/test-nginx) ⭐ 456 | 🐛 44 | 🌐 Perl | 📅 2026-08-24 - Data-driven test scaffold for Nginx C module and OpenResty Lua library development.

* [nginx-build](https://github.com/cubicdaiya/nginx-build) ⭐ 427 | 🐛 8 | 🌐 Go | 📅 2026-08-29 - seamless nginx builder.

* [nginx-config-formatter](https://github.com/slomkowski/nginx-config-formatter) ⭐ 424 | 🐛 3 | 🌐 Python | 📅 2026-03-09 - Nginx config file formatter/beautifier written in Python.

* [nginx-gdb-utils](https://github.com/openresty/nginx-gdb-utils) ⭐ 348 | 🐛 3 | 🌐 Python | 📅 2023-12-18 - GDB Utilities for Nginx, ngx\_lua, LuaJIT, and etc.

* [apache2nginx](https://github.com/nhnc-nginx/apache2nginx) ⭐ 282 | 🐛 6 | 🌐 C | 📅 2019-01-17 - A command line tool, which can be used to generate nginx config file according to given config files of Apache.

* [nixy](https://github.com/martensson/nixy) ⭐ 270 | 🐛 1 | 🌐 Go | 📅 2019-07-01 - Nginx auto configuration and service discovery for Mesos/Marathon

* [nginx-devel-utils](https://github.com/openresty/nginx-devel-utils) ⭐ 268 | 🐛 1 | 🌐 Perl | 📅 2026-05-15 - Utilities for nginx module development.

* [nginx-cache-purge](https://github.com/perusio/nginx-cache-purge) ⭐ 249 | 🐛 5 | 🌐 Shell | 📅 2017-05-21 - A bash script for deleting items from Nginx cache.

* [nginx-lua](https://github.com/fabiocicerchia/nginx-lua) ⭐ 225 | 🐛 5 | 🌐 Dockerfile | 📅 2026-08-30 - Latest Nginx with LuaJIT on six base distros (Alma, Alpine, Amazon, Debian, Fedora, Ubuntu).

* [nginx-binaries](https://github.com/jirutka/nginx-binaries) ⭐ 82 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-23 - Nginx and njs binaries for Linux (x86\_64, aarch64, ppc64le), macOS and Windows; Linux binaries are static so works on every Linux.

* [no-pool-nginx](https://github.com/openresty/no-pool-nginx) ⭐ 76 | 🐛 0 | 🌐 Shell | 📅 2026-08-24 - replace nginx's pool mechanism with plain malloc & free to help tools like valgrind.

* [build-nginx](https://github.com/jaygooby/build-nginx) ⭐ 55 | 🐛 0 | 🌐 Shell | 📅 2026-06-03 - An nginx build tool to really simplify downloading and building specific versions of nginx with different core and 3rd-party modules.

* [nginx-dtrace](https://github.com/openresty/nginx-dtrace) ⭐ 44 | 🐛 0 | 🌐 C | 📅 2016-05-02 - An nginx fork that adds dtrace USDT probes.

* [nginx-testing](https://github.com/jirutka/nginx-testing) ⭐ 28 | 🐛 3 | 🌐 TypeScript | 📅 2023-07-19 - Support for integration/acceptance testing of nginx configuration in TypeScript/JavaScript.

* [libngxcore](https://github.com/cubicdaiya/libngxcore) ⭐ 26 | 🐛 1 | 🌐 C | 📅 2015-01-17 - libngxcore is the library built from nginx core APIs..

* [akamai-nginx](https://github.com/wyvern8/akamai-nginx) ⭐ 26 | 🐛 1 | 🌐 JavaScript | 📅 2025-08-08 - Autoconfigure nginx based on Akamai property api rules using generated lua.

* [nginx-modules](https://github.com/blendbyte/nginx-modules) ⭐ 24 | 🐛 0 | 🌐 Shell | 📅 2026-07-10 - APT repository providing pre-built NGINX dynamic modules for Debian and Ubuntu (amd64/arm64), installable via `apt` without compiling from source.

* [ngx-admintools](https://github.com/rmacd/ngx-admintools) ⭐ 5 | 🐛 0 | 📅 2011-05-25 - Debian Administration Tools for nginx web server.

* [seo-sidecar](https://github.com/Janady13/seo-sidecar) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2026-05-27 - FastAPI + nginx SSI sidecar that injects fresh Schema.org JSON-LD into nginx-served sites without redeploys or cron jobs. Production-ready, MIT licensed.

* [maint](https://github.com/glidecraft/nginx-maint) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2026-08-02 - Toggle nginx maintenance mode per site via a flag file, no reload needed to flip it on or off. Whole-site and partial-site gating snippets included, plus a styled 503 page. MIT licensed.

* [nginx-scanner-trap](https://github.com/gistrec/nginx-scanner-trap) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-08-21 - One-script honeypot for existing nginx servers: bots probing paths like /.env or /.git get banned on all ports via fail2ban + nftables. Interactive install with whitelisting, dry-run preview, Debian/Ubuntu, MIT licensed.

* [GoAccess](https://goaccess.io/) - real-time web log analyzer and interactive viewer that runs in a terminal in \*nix systems or through your browser.

* [GetPageSpeed Extras for Debian/Ubuntu](https://www.getpagespeed.com/ubuntu-and-debian-repository) - Free APT repository with 100+ pre-built NGINX dynamic modules for Debian (Bookworm/Trixie) and Ubuntu (Bionic/Focal/Jammy/Noble) on amd64 and arm64. No signup or auth required. Covers ModSecurity, brotli, geoip2, headers-more, JWT, TOTP, naxsi, NJS, and a long tail of modules not packaged elsewhere. Cross-distro counterpart for RHEL/SLES/Amazon Linux at extras.getpagespeed.com.

## Tutorials

* [Nginx book](https://github.com/taobao/nginx-book) ⭐ 6,963 | 🐛 542 | 🌐 Python | 📅 2023-11-20 - Nginx from primer to expert (In Chinese).
* [Nginx tutorials](https://github.com/openresty/nginx-tutorials) ⭐ 2,868 | 🐛 5 | 🌐 Perl | 📅 2021-03-05 - Nginx tutorials by [Agentzh](https://github.com/agentzh).
* [Nginx-cheatsheet](https://github.com/SimulatedGREG/nginx-cheatsheet) ⭐ 342 | 🐛 0 | 📅 2016-12-06 - A quick reference to common server configurations from serving static files to using in congruency with Node.js applications.
* [Nginx docs cn](https://github.com/taobao/nginx-docs-cn) ⭐ 120 | 🐛 1 | 🌐 Ruby | 📅 2013-04-01 - The chinese translation of nginx documentation.
* [Nginx admin guide](https://www.nginx.com/resources/admin-guide/) - Nginx and nginx plus admin guide.
* [Nginx documentation](http://nginx.org/en/docs/) - Nginx documentation introduction.
* [Nginx blog](https://www.nginx.com/blog/) - News, views, and how-tos from nginx.
* [Nginx beginner’s Guide](http://nginx.org/en/docs/beginners_guide.html) - This guide gives a basic introduction to nginx and describes some simple tasks that can be done with it.
* [Nginx module development](http://www.evanmiller.org/nginx-modules-guide.html) - Emiller's guide to nginx module development.
* [OpenResty best practice](https://www.gitbook.com/book/moonbingbing/openresty-best-practices/details) - OpenResty best practice(In Chinese).
* [Monitoring Nginx on Kubernetes](https://sysdig.com/blog/monitor-nginx-kubernetes/) - Deployment options, use cases, metrics and alerts for containerized Nginx instances on Kubernetes.

## Mailing Lists

* [Nginx Mailman](http://mailman.nginx.org/mailman/listinfo)

## Forum

* [Nginx Forum](http://forum.nginx.org/)
* [Nginx Community Slack](https://community.nginx.org/joinslack)
* [OpenResty Forum](http://groups.google.com/group/openresty-en)

## Active Developers

* [Maxim Dounin](https://twitter.com/mdounin)
* [Roman Arutyunyan](https://github.com/arut)
* Sergey Kandaurov

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-30._

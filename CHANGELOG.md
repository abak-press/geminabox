# 0.13.9 (2017-09-25)

Enhancements:

* Make it be configurable HTTPClient options of Geminabox.http_adapter

# 0.13.8 (2017-09-24)

Fixes:

* gem inabox command should unescape username/password of geminabox url
* gem inabox command should get gemname from gemspec rather than directory name
* Concurrent reindex(:force_rebuild) should be serialized

# 0.13.7 (2017-09-23)

Fix vulnerabilities:

* Fix CSRF vulnerabilities - CVE-2017-14683 (reported by Barak Tawily)

# 0.13.6 (2017-09-19)

Fix vulnerabilities:

* Fix XSS vulnerabilities - CVE-2017-14506 (reported by Barak Tawily)

# 0.13.5 (2017-01-14)

Fixes:

* disk_cache.rb: ignore Errno::ENOENT, and EOFError. There is a possibility that the file is removed by another process after checking File.exist?.

# 0.13.4 (2016-10-25)

Fixes:

* Fix allow_remote_failure was not working in proxy/file_handler

# 0.13.3 (2016-10-13)

Enhancements:

* Add force_rebuild query parameter option to reindex route #244 (thanks to kbacha)

# 0.13.2 (2016-10-13)

Enhancements:

* Add the allow_upload config #247 (thanks to CAFxX)

Fixes:

* Atomic writes proxy latest specs #245 (thanks to dsolsona)

* [How to read this book](how-to-read.md)
* [The cURL project](project.md)
    * [How it started](project/started.md)
    * [The name](project/name.md)
    * [What does curl do?](project/does.md)
    * [Project communication](project/comm.md)
    * [Mailing list etiquette](project/etiquette.md)
    * [Mailing lists](project/maillists.md)
    * [Reporting bugs](project/bugs.md)
    * [Releases](project/releases.md)
    * [Security](project/security.md)
    * [Trust](project/trust.md)
    * [The development team](project/devteam.md)
    * [Users of curl](project/users.md)
    * [Future](project/future.md)
* [Get curl](get.md)
    * [Linux](get/linux.md)
    * [Windows](get/windows.md)
    * [macOS](get/macos.md)
* [Open Source](opensource.md)
    * [License](opensource/license.md)
    * [Copyright and Legal](opensource/copyright.md)
    * [Code of Conduct](opensource/coc.md)<
    * [Development](opensource/devel.md)
* [The source code](source.md)
    * [Code layout](source/layout.md)
    * [Handling build options](source/options.md)
    * [Code style](source/style.md)
    * [Contributing](source/contributing.md)
    * [Reporting vulnerabilities](source/reportvuln.md)
    * [Web site](source/web.md)
    * [Build and install](source/build.md)
      * [Build from source](source/build/fromsource.md)
      * [Dependencies](source/build/deps.md)
      * [TLS libraries](source/build/tls.md)
          * [BoringSSL](source/build/boringssl.md)
* [Network and protocols](protocols.md)
    * [Networking simplified](protocols/network.md)
    * [Protocols](protocols/protocols.md)
    * [curl protocols](protocols/curl.md)
* [Command line basics](cmdline.md)
    * [Command line options](cmdline/options.md)
    * [Options depend on version](cmdline/versions.md)
    * [URLs](cmdline/urls.md)
    * [URL globbing](cmdline/globbing.md)
    * [List options](cmdline/listopts.md)
    * [Config file](cmdline/configfile.md)
    * [Passwords](cmdline/passwords.md)
    * [Progress meter](cmdline/progressmeter.md)
* [Using curl](usingcurl.md)
    * [Verbose](usingcurl/verbose.md)
        * [Trace options](usingcurl/verbose/trace.md)
        * [Write out](usingcurl/verbose/writeout.md)
    * [Version](usingcurl/version.md)
    * [Persistent connections](usingcurl/persist.md)
    * [Downloads](usingcurl/downloads.md)
    * [Uploads](usingcurl/uploads.md)
    * [Connections](usingcurl/connections.md)
    * [Timeouts](usingcurl/timeouts.md)
    * [.netrc](usingcurl/netrc.md)
    * [Proxies](usingcurl/proxies.md)
    * [Exit status](usingcurl/returns.md)
    * [SCP and SFTP](usingcurl/scpsftp.md)
    * [Reading email](usingcurl/reademail.md)
    * [Sending email](usingcurl/smtp.md)
    * [MQTT](usingcurl/mqtt.md)
    * [TELNET](usingcurl/telnet.md)
    * [TLS](usingcurl/tls.md)
        * [SSLKEYLOGFILE](usingcurl/tls/sslkeylogfile.md)
    * [Copy as curl](usingcurl/copyas.md)
* [HTTP with curl](http.md)
    * [Protocol basics](http/basics.md)
    * [Responses](http/response.md)
    * [Authentication](http/auth.md)
    * [Ranges](http/ranges.md)
    * [HTTP versions](http/versions.md)
    * [Conditionals](http/conditionals.md)
    * [HTTPS](http/https.md)
    * [HTTP POST](http/post.md)
    * [Multipart formposts](http/multipart.md)
    * [-d vs -F](http/postvspost.md)
    * [Redirects](http/redirects.md)
    * [Modify the HTTP request](http/requests.md)
    * [HTTP PUT](http/put.md)
    * [Cookies](http/cookies.md)
    * [HTTP/2](http/http2.md)
    * [Alternative Services](http/altsvc.md)
    * [HTTP/3](http/http3.md)
    * [HSTS](http/hsts.md)
    * [HTTP cheat sheet](http/cheatsheet.md)
    * [Scripting browser-like tasks](http/browserlike.md)
* [FTP with curl](ftp.md)
    * [FTP Directory listing](ftp/dirlist.md)
    * [Uploading with FTP](ftp/upload.md)
    * [Custom FTP commands](ftp/cmds.md)
    * [Two connections](ftp/twoconnections.md)
    * [Directory traversing](ftp/traversedir.md)
    * [FTPS](ftp/ftps.md)
* [libcurl basics](libcurl.md)
    * [Easy handle](libcurl/easyhandle.md)
    * [Drive transfers](libcurl/drive.md)
        * [Drive with easy](libcurl/drive/easy.md)
        * [Drive with multi](libcurl/drive/multi.md)
        * [Drive with multi_socket](libcurl/drive/multi-socket.md)
    * [Connection reuse](libcurl/connectionreuse.md)
    * [Callbacks](libcurl/callbacks.md)
        * [Write data](libcurl/callbacks/write.md)
        * [Read data](libcurl/callbacks/read.md)
        * [Progress information](libcurl/callbacks/progress.md)
        * [Header data](libcurl/callbacks/header.md)
        * [Debug](libcurl/callbacks/debug.md)
        * [sockopt](libcurl/callbacks/sockopt.md)
        * [SSL context](libcurl/callbacks/sslcontext.md)
        * [Seek and ioctl](libcurl/callbacks/seek.md)
        * [Network data conversion](libcurl/callbacks/conversions.md)
        * [Opensocket and closesocket](libcurl/callbacks/openclosesocket.md)
        * [SSH key](libcurl/callbacks/sshkey.md)
        * [RTSP interleaved data](libcurl/callbacks/rtsp.md)
        * [FTP matching](libcurl/callbacks/ftpmatch.md)
    * [Cleanup](libcurl/cleanup.md)
    * [Name resolving](libcurl/names.md)
    * [Proxies](libcurl/proxies.md)
    * [Post transfer info](libcurl/getinfo.md)
    * [Share data between handles](libcurl/sharing.md)
    * [URL API](libcurl/url.md)
    * [API compatibility](libcurl/api.md)
    * [--libcurl](libcurl/--libcurl.md)
    * [Header files](libcurl/headers.md)
    * [Global initialization](libcurl/globalinit.md)
    * [multi-threading](libcurl/threading.md)
    * [curl easy options](libcurl/options.md)
        * [TLS options](libcurl/tlsoptions.md)
    * [CURLcode return codes](libcurl/curlcode.md)
    * [Verbose operations](libcurl/verbose.md)
    * [libcurl examples](libcurl/examples.md)
        * [Get a simple HTTP page](libcurl/examples/get.md)
        * [Get a page in memory](libcurl/examples/getinmem.md)
        * [Submit a login form over HTTP](libcurl/examples/login.md)
        * [Get an FTP directory listing](libcurl/examples/ftplist.md)
    * [for C++ programmers](libcurl/cplusplus.md)
* [HTTP with libcurl](libcurl-http.md)
    * [HTTP responses](libcurl-http/responses.md)
    * [HTTP requests](libcurl-http/requests.md)
    * [HTTP versions](libcurl-http/versions.md)
    * [HTTP ranges](libcurl-http/ranges.md)
    * [HTTP authentication](libcurl-http/auth.md)
    * [Cookies with libcurl](libcurl-http/cookies.md)
    * [Download](libcurl-http/download.md)
    * [Upload](libcurl-http/upload.md)
* [Bindings](bindings.md)
* [libcurl internals](internals.md)
* [Index](bookindex.md)

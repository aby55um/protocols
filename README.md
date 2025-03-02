<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Protocols and file signatures

_Network, application, OS protocols and file signatures_

</header>

<!--
  todo: Populate the board with the most important protocols
-->

## Network protocols

_Physical, Data Link, Network, Transport, Session, Presentation, Application_

1. Transport Layer Security (TLS)
Source: [RFC 5246](https://datatracker.ietf.org/doc/html/rfc5246)

1. Syslog
Source: [RFC 5424](https://datatracker.ietf.org/doc/html/rfc5424)
-syslog content
-syslog application (originator -> relay -> collector)
-syslog transport

## File signatures

1. Android Package (apk)
Source: No official specification
[Wikipedia](https://en.wikipedia.org/wiki/Apk_(file_format))

```The apk is a zip archive that usually contains the following files and directories:  
- META-INF directory:  
  - MANIFEST.MF: the manifest file  
  - The certificate of the application  
  - CERT.SF: The list of resources and a SHA-1 digest of the corresponding lines in the MANIFEST.MF file  
- lib: the directory containing the -platform dependent- compiled code  
  - armeabi-v7a  
  - arm64-v8a  
  - x86  
  - x86_64  
- res: the directory containing resources not compiled into resources.arsc  
- assets: a directory containing applications assets, which can be retrieved by AssetManager  
- AndroidManifest.xml: an additional manifest file, describing the name, version, access rights, referenced library files for the application. This file may be in Android binary XML.  
- classes.dex: The classes compiled in the dex file format, executed by Android Runtime (or Dalvik virtual machine used in previous versions)  
- resources.arsc: a file containing precompiled resources, such as binary XML  
```


<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---
</footer>

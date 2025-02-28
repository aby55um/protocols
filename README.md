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
Source: [title](https://datatracker.ietf.org/doc/html/rfc5246)


## File signatures

1. Android Package (apk)
Source: No official specification
[title](https://en.wikipedia.org/wiki/Apk_(file_format))

The apk is a zip archive that usually contains the following files and directories:  
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



**What is _Markdown_?** Markdown is a [lightweight syntax](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) for communicating on GitHub. You can format text to add a heading, lists, **bold**, _italics_, tables, and many other stylings. You can use Markdown in most places around GitHub:

- Comments on [issues](https://docs.github.com/issues/tracking-your-work-with-issues/about-issues), [pull requests](https://docs.github.com/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests), and [discussions](https://docs.github.com/discussions/collaborating-with-your-community-using-discussions/about-discussions)
- Files with the `.md` or `.markdown` extension
- Sharing snippets of text in [Gists](https://docs.github.com/github/writing-on-github/editing-and-sharing-content-with-gists/creating-gists)

**What is a _header_?** A header is a larger bit of text at the beginning of a section. There are six sizes.

### Example

```md
# This is an `<h1>` header, which is the largest

## This is an `<h2>` header

###### This is an `<h6>` header, which is the smallest
```

#### How it looks

# This is an `<h1>` header, which is the largest

## This is an `<h2>` header

###### This is an `<h6>` header, which is the smallest

### :keyboard: Activity: Edit your file with headers

1. Open a new browser tab, and work on the steps in your second tab while you read the instructions in this tab.
1. Open the **pull requests** tab.
1. Click **New pull request**, for the branches to compare, select `base: main` and `compare: start-markdown`.
1. Click **Create pull request**.
1. In this pull request, go to the **Files changed** tab. We made an empty file `index.md` for you.
1. Select **Edit file** from the three dotted **...** menu in the upper right corner of the file view on `index.md`.
1. On the **Edit file** tab, add a `#`, followed by a **space**, before any content you like to make it an H1 Header. You can add more headers, using one to six `#` characters followed by a **space**.
1. Above your new content, click **Preview**.
1. At the bottom of the page, type a short, meaningful commit message that describes the change you made to the file.
1. Click **Commit changes**.
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/communicate-using-markdown) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>

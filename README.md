# The abc of Digital Literacy

There's a [description of the project](https://victor-fancelli-capdevila.github.io/abc_dl/about/) with a FAQ.

If you want to participate, check the [Documentation²](https://victor-fancelli-capdevila.github.io/abc_dl/this-website/). You can use GitHub to propose changes or the HfG Cloud. For the second, [request the membership to the circle "The abc of digital literacy"](https://cloud.hfg-karlsruhe.de/apps/contacts/circle/5brS9N1EiZj2wMFQawiStcUORcMjVUb)


## Usage

### 1. Install Jekyll
To achieve that, follow the instructions of [Jekyll Quick start](https://jekyllrb.com/docs/installation/)

### 2. Get the code

You can clone the repository:

```bash
git clone https://victor-fancelli-capdevila.github.io/abc_dl/ abc_dl
cd abc_dl
```

### 3. Serve

Depending on how you installed Jekyll:

```bash
jekyll serve -b /abc_dl
# or
bundle exec jekyll serve -b /abc_dl
```

**NOTE:** If the above serve command throws an error saying `require': cannot load such file -- webrick (LoadError)` try to run `bundle add webrick` to automatically add the webrick gem to your Gemfile, or manually add `gem "webrick"` line to the Gemfile and then run the serve command again.

**NOTE:** The `-b /abc_dl` serves the website in the subfolder /abc_dl. Depending on your configuration, you may get errors if you serve it directly on the "root" folder.

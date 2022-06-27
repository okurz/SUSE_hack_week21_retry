## Motivation
Sometimes stuff fails, especially when network is involved -> just retry

## Goals
* **G1:** A "retry" command is submitted to openSUSE:Factory as part of a package

## Execution
* Research existing approaches and distributions
* Package existing solution or develop alternative on your own
* Submit package to a devel repository and then openSUSE:Factory and work on feedback

---

## Results

```
$ sporadic_failure
This failed!
$ zypper -n in retry && retry sporadic_failure
This failed!
Retrying up to 3 more times after sleeping 3s …
SUCCESS
```

[![asciicast](https://asciinema.org/a/qoD8FL5QLBeevojHO4yPxm7qa.svg)](https://asciinema.org/a/qoD8FL5QLBeevojHO4yPxm7qa)

---

### The end … Questions? Corrections? Additions?

<p><img src="img/chameleon.svg" style="max-height:300px;"></p>

https://v.gd/okurz_retry

<small>
Presentation created using <br><a href="https://github.com/krig/opensuse-presentation-template">https://github.com/krig/opensuse-presentation-template</a>
</small>

#### License
<small>
This slide deck is licensed under the Creative Commons Attribution-ShareAlike 4.0 International license.
It can be shared and adapted for any purpose (even commercially) as long as Attribution is given and any derivative work is distributed under the same license. Details can be found at <a href="https://creativecommons.org/licenses/by-sa/4.0/">https://creativecommons.org/licenses/by-sa/4.0/</a>
</small>

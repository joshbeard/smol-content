# smol-content

Files served for jbeard.co.

```text
gemini/   Jetforce root (gemini://jbeard.co/)
gopher/   Gophernicus root, including the jbeard.co virtual host
finger/   optional finger2020 files copied over /etc/finger
www/      HTTPS page for jbeard.co
```

The resume is not here. The [resume repo](https://github.com/joshbeard/resume) publishes it to S3, and the instance lays `resume.gmi`, `resume.txt`, and the other formats over this tree on each sync. Gopher's `jbeard.co/resume.txt` is the narrow text version. Edit the resume there, not here.

The photo library stays on https://joshbeard.me/photos. `gemini/photos` and `gopher/jbeard.co/photos` were symlinks to that library on the homelab, so this repo has a short pointer page in each place instead of the files.

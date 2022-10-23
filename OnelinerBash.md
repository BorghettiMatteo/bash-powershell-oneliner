#Convert a bunch of `.webp` images to `.png`

launch this script in the repositories containing the images you want to convert

```bash
for image in $(ls *.webp); do ffmpeg -i $image $(basename $image).png; done
```

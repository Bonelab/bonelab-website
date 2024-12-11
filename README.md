
# Bone Imaging Laboratory
We are a team of researchers at the University of Calgary focused on studying bone, with an emphasis 
on using advanced medical imaging. Visit **[bonelab.ca](https://bonelab.ca)** 🚀

## Webpage Updates
Any lab member can make changes to the web site by creating a branch. Pull requests to merge to the 
`main` branch are approved by the site administrator.

If you simply want to request a change (add a photo, update a member profile, etc.), [send an email](mailto:bonelab@ucalgary.ca).

Create a branch and clone the repository to your computer. Download, install and run [Docker](https://www.docker.com). 
Navigate to the base directory of your local copy of the repo and get things running:
```
$ cd bonelab-website
$ ./.docker/run.sh
```
It’ll process the site and then give you the URL to put in your browser:
```
http://localhost:4000
```
Edit your local repo files and whenever you save a file your local web browser will be updated. When you're done, push your updates to GitHub to update the site online.

If you've edited files (e.g., _cite/.cache/cache.db) you may need to restore from the master branch before pushing: 
```
git restore _cite/.cache/cache.db
```
## Common Updates
Here are some tips for simple updates.

### Post a new idea for a project
A new [idea]("ideas") can be added by simply creating a new file in `_posts/` such as `2024-08-19-vertebral-fractures.md`.

### Members
Each member file is stored in `_members`. See other files for examples or refer to `template.txt` in that 
directory. Update your profile, such as personal links (e.g., Email, Instagram, LinkedIn, PubMed, etc) or your biography as you please.

Adding a new member is as simple as creating a new member file in `_members`. 

Profile photos should be 600px X 600px and are stored in `images/headshots` using the naming format `FirstnameLastname.png`.

All changes to `_members` are reflected on the web page upon pushing to GitHub and merging.

### Citations
Citations are based on the ORCID ID of Dr. Steven Boyd. If you see a missing citation you can edit `_data/sources.yaml` and identify
the missing publication by DOI. If you want to associate an image with a particular citation, that is defined in the same file. 
Typically a copy of the first page of the journal publication is a good image to use, and these are stored in `images/journal/`.

## University of Calgary Brand Standards
Since we are all members of the [University of Calgary](https://www.ucalgary.ca) we try to stick to the brand standards. Details
can be found [here](https://www.ucalgary.ca/brand/standards-and-guidelines/colours).

### Primary Colours
| | |
|:-------------------------:|:-------------------------:|
|<img width="120" alt="Red: d6001c" src="/images/brandstandard/BrandStandardRed.png">  d6001c|<img width="120" alt="Gold: ffcd00" src="/images/brandstandard/BrandStandardGold.png">  ffcd00|

### Secondary Colours
| | | | |
|:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:|
|<img width="120" alt="Light orange: ffa300" src="/images/brandstandard/BrandStandardLightOrange.png">  ffa300|<img width="120" alt="Dark orange: ff671f" src="/images/brandstandard/BrandStandardDarkOrange.png">  ff671f|<img width="120" alt="Rubine Red C: ed0a72" src="/images/brandstandard/BrandStandardRubine.png">  ed0a72|<img width="120" alt="1945 C (Berry): 9c0534" src="/images/brandstandard/BrandStandardBerry.png">  9c0534|

### Accent Colours
| | | | |
|:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:|
|<img width="120" alt="2400 C (Teal): 47a67c" src="/images/brandstandard/BrandStandardTeal.png">  47a67c|<img width="120" alt="100 C (Light Yellow): ffe57b" src="/images/brandstandard/BrandStandardLightYellow.png">  ffe57b| <img width="120" alt="7602 C (Brown): 6c3302" src="/images/brandstandard/BrandStandardBrown.png">  6c3302|<img width="120" alt="2311 C (Taupe): d3ac8b" src="/images/brandstandard/BrandStandardTaupe.png">  d3ac8b|

### Neutrals (for text only)
| | | | 
|:-------------------------:|:-------------------------:|:-------------------------:|
|<img width="120" alt="Black: 000000" src="/images/brandstandard/BrandStandardBlack.png">  000000|<img width="120" alt="Dark Grey: 6d6e71" src="/images/brandstandard/BrandStandardDarkGrey.png">  6d6e71| <img width="120" alt="Light Grey: c7c8ca" src="/images/brandstandard/BrandStandardLightGreg.png">  c7c8ca|


_Built with [Lab Website Template](https://greene-lab.gitbook.io/lab-website-template-docs)_
